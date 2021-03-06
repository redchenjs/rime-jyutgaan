# 粵語簡拼

配方： ℞ **redchenjs/rime-jyutgaan**

AUR： [rime-jyutgaan](https://aur.archlinux.org/packages/rime-jyutgaan)

[Rime](https://rime.im) 粵語簡拼輸入方案

[香港語言學會粵語拼音方案](https://zh.wikipedia.org/wiki/%E9%A6%99%E6%B8%AF%E8%AA%9E%E8%A8%80%E5%AD%B8%E5%AD%B8%E6%9C%83%E7%B2%B5%E8%AA%9E%E6%8B%BC%E9%9F%B3%E6%96%B9%E6%A1%88)

## 用法

| 聲母 | ng | gw | kw |
| :--: | -: | -: | -: |
| 按鍵 |  r |  y |  x |

| 韻腹 | aa | oe | eo | yu |
| :--: | -: | -: | -: | -: |
| 按鍵 |  q |  v |  v |  y |

| 韻尾 | ng |
| :--: | -: |
| 按鍵 |  b |

註：
* 輸入時將對應音節依照上述規則進行替換即可（單獨的aa，oe，ng，m音節直接輸入，不使用簡拼），其餘音節輸入方法與原粵拼方案無異。
* 本方案支持首字母簡拼及完整拼音提示（僅供參考，多音字註音可能有誤），不支持聲調輸入。
* 本方案可用漢語拼音（使用“\`”鍵）來反查字音。

## 依賴

* [粵語拼音](https://github.com/rime/rime-cantonese)：粵音字、詞庫
* [朙月拼音](https://github.com/rime/rime-luna-pinyin)：拼音反查

## 安裝

[東風破](https://github.com/rime/plum) 安裝口令：
```
bash rime-install redchenjs/rime-jyutgaan
```

授權條款：見 [LICENSE](LICENSE)
