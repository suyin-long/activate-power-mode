# activate-power-mode

[power mode](https://github.com/codeinthedark/editor/pull/1) script for any website

[demo](http://0xABCDEF.com/activate-power-mode/)

used [textarea-caret-position library](https://github.com/component/textarea-caret-position).


## 如何使用

```html
<script src="https://cdn.jsdelivr.net/gh/suyin-long/activate-power-mode@1.0/dist/activate-power-mode.js"></script>
<script>
POWERMODE.colorful = true; // make power mode colorful
POWERMODE.shake = false; // turn off shake
document.body.addEventListener('input', POWERMODE);
</script>
```

## 在Hexo Next主题上使用

**1.[Hexo](https://hexo.io/)配置**
- 在`/Hexo/source/`目录下新建`_data`目录
- 在`_data`目录下新建`footer.njk`文件夹
- 在文件夹中写入以下代码：
  ```njk
  <script src="https://cdn.jsdelivr.net/gh/suyin-long/activate-power-mode@1.0/dist/activate-power-mode.js"></script>
  <script>
  POWERMODE.colorful = true; // make power mode colorful
  POWERMODE.shake = false; // turn off shake
  document.body.addEventListener('input', POWERMODE);
  </script>
  ```
**2.[Next](https://github.com/next-theme/hexo-theme-next)配置**
- 在Next配置文件中找到`custom_file_path:`
- 取消`footer: source/_data/footer.njk`的注释

## 效果展示

- https://suyin-blog.club/
