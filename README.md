# Loafer-s-mind
share &amp; learn.ML &amp; Algorithm

- 对有道翻译的js加密进行破解爬虫文件，只进行了初步的破解，并没有完善后续的信息的提取和推广使用，后期会继续修改的

- 分析一下 https://fanyi.youdao.com 网页的内容，由于js加密只会在浏览器端产生，去找到有道反爬虫的js加密文件
- 查看源码的form表单，salt，sign为加密关键，在js源码中找到salt和sign的生成方式，然后用Python解密即可
