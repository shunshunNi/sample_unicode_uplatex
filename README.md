# sample_unicode_uplatex

## 概要
GitHub上のpdfにおいて日本語が表示されない問題のサンプル。  
詳しくはQiitaの記事[リンク](https://qiita.com/nisshy82/items/2c403e8787cf551255a1) を参照のこと

## pdffontsの実行結果
uniの部分が違う
### shippai.pdf
```shell
> pdffonts shippai.pdf
name                                           type              emb sub uni prob object ID
---------------------------------------------- ----------------- --- --- --- ---- ---------
HMJJZA+CMR10                                   Type 1C           yes yes yes           4  0
DXMPHG+HaranoAjiMincho-Regular-Identity-H      CID Type 0C       yes yes no            5  0
```

### seiko.pdf
```shell
> pdffonts seiko.pdf
name                                           type              emb sub uni prob object ID
---------------------------------------------- ----------------- --- --- --- ---- ---------
BWNIUU+CMR10                                   Type 1C           yes yes yes           4  0
LXJENX+NotoSerifJP-Regular-Identity-H          CID Type 0C       yes yes yes           5  0
```
