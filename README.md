# mtranserver-lzcapp

## 模型下载
+ [国内](https://ocn4e4onws23.feishu.cn/drive/folder/C3kffkLr8lxdtid5GYicAcFAnTh)
+ [github](https://github.com/xxnuo/MTranServer/releases/tag/models)
  小众论坛  https://meta.appinn.net/t/topic/67121/4
更多模型下载 [github](https://github.com/mozilla/firefox-translations-models)

按需要下载模型后，解压每个语言的压缩包到 models 文件夹内。
下载了英译中模型的当前文件夹结构示意图：
compose.yml
```
models/
├── enzh
│   ├── lex.50.50.enzh.s2t.bin
│   ├── model.enzh.intgemm.alphas.bin
│   └── vocab.enzh.spm
```

如果你下载添加多个模型，这是有中译英、英译中模型文件夹结构示意图：

compose.yml

```
models/
├── enzh
│   ├── lex.50.50.enzh.s2t.bin
│   ├── model.enzh.intgemm.alphas.bin
│   └── vocab.enzh.spm
├── zhen
│   ├── lex.50.50.zhen.t2s.bin
│   ├── model.zhen.intgemm.alphas.bin
│   └── vocab.zhen.spm
```

用不到的模型没必要下载。按自己的需求下载模型。

> 注意：例如中译日的过程是先中译英，再英译日，也就是需要两个模型 zhen 和 enja。其他语言翻译过程类似。
