---
title: "WmfSetTextCharExtra"
second_title: "Aspose.Imaging for Java API Referansı"
description: "META_SETTEXTCHAREXTRA kaydı, oynatma aygıt bağlamında metin hizalaması için karakterler arası boşluğu tanımlar."
type: docs
weight: 86
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetTextCharExtra extends WmfObject
```

META\_SETTEXTCHAREXTRA kaydı, oynatma aygıt bağlamında metin hizalaması için karakterler arası boşluğu tanımlar. Boşluk, her karakter arasındaki beyaz alana, `` karakterleri dahil, hizalanmış bir metin satırı çıktığında eklenir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfSetTextCharExtra()](#WmfSetTextCharExtra--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCharExtra()](#getCharExtra--) | Karakter ekini alır veya ayarlar. |
| [setCharExtra(int value)](#setCharExtra-int-) | Karakter ekini alır veya ayarlar. |
### WmfSetTextCharExtra() {#WmfSetTextCharExtra--}
```
public WmfSetTextCharExtra()
```


### getCharExtra() {#getCharExtra--}
```
public int getCharExtra()
```


Karakter ekini alır veya ayarlar.

Değer: Her karaktere eklenecek ekstra boşluk miktarı, mantıksal birimlerde. Mevcut eşleme modu MM\_TEXT değilse, bu değer dönüştürülür ve en yakın piksele yuvarlanır. Eşleme modunun ayarlanmasıyla ilgili ayrıntılar için META\_SETMAPMODE (bölüm 2.3.5.17) bakınız.

**Returns:**
int
### setCharExtra(int value) {#setCharExtra-int-}
```
public void setCharExtra(int value)
```


Karakter ekini alır veya ayarlar.

Değer: Her karaktere eklenecek ekstra boşluk miktarı, mantıksal birimlerde. Mevcut eşleme modu MM\_TEXT değilse, bu değer dönüştürülür ve en yakın piksele yuvarlanır. Eşleme modunun ayarlanmasıyla ilgili ayrıntılar için META\_SETMAPMODE (bölüm 2.3.5.17) bakınız.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

