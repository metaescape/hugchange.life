#

Mathjax 本地化:

将官方库下载到本地(大概 24M)：

```bash
git clone https://github.com/mathjax/MathJax.git mj-tmp --depth 1
mv mj-tmp/es5 ~/codes/hugchangelife/mathjax
rm -rf mj-tmp
```

在网页中加入：

```html
<script id="MathJax-script" async src="/mathjax/tex-chtml.js"></script>
```
