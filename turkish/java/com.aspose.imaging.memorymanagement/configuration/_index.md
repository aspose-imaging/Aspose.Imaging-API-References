---
title: "Yapılandırma"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bellek yönetimi genel yapılandırması"
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.memorymanagement/configuration/
---
**Inheritance:**
java.lang.Object
```
public final class Configuration
```

Bellek yönetimi genel yapılandırması
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu alır. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu ayarlar. |
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu alır.

Değer: Bellek boyutu ipucu, megabayt cinsinden. Pozitif olmayan değer, dahili tamponlar için bellek sınırlaması olmadığı anlamına gelir

**Returns:**
int - tampon boyutu ipucu, tüm dahili tamponlar için tanımlanan maksimum izin verilen boyut.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu ayarlar.

Değer: Bellek boyutu ipucu, megabayt cinsinden. Pozitif olmayan değer, dahili tamponlar için bellek sınırlaması olmadığı anlamına gelir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | tampon boyutu ipucu, tüm dahili tamponlar için tanımlanan maksimum izin verilen boyut. |

