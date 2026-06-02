---
title: "WmfFontQuality"
second_title: "Aspose.Imaging for Java API Referansı"
description: "FontQuality Sıralaması, metin işlenirken mantıksal yazı tipinin özelliklerinin fiziksel yazı tipiyle ne kadar yakın eşleşmesi gerektiğini belirtir."
type: docs
weight: 19
url: /tr/java/com.aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFontQuality extends System.Enum
```

FontQuality Sıralaması, metin işlenirken mantıksal yazı tipinin özelliklerinin fiziksel yazı tipiyle ne kadar yakın eşleşmesi gerektiğini belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Default](#Default) | Yazı tipinin karakter kalitesinin önemli olmadığını, bu yüzden DRAFT kullanılabileceğini belirtir. |
| [Draft](#Draft) | Yazı tipinin karakter kalitesinin, mantıksal özniteliklerin eşleşmesinden daha az önemli olduğunu belirtir. |
| [Proof](#Proof) | Yazı tipinin karakter kalitesinin, mantıksal özniteliklerin eşleşmesinden daha önemli olduğunu belirtir. |
| [Nonantialiased](#Nonantialiased) | Metin render edildiğinde anti-aliasing'in KULLANILMAMASI gerektiğini belirtir. |
| [Antialiased](#Antialiased) | Metin render edildiğinde, yazı tipi destekliyorsa anti-aliasing'in KULLANILMASI gerektiğini belirtir. |
| [Cleartype](#Cleartype) | Metin render edildiğinde, yazı tipi destekliyorsa ClearType anti-aliasing'in KULLANILMASI gerektiğini belirtir. |
### Default {#Default}
```
public static final byte Default
```


Yazı tipinin karakter kalitesinin önemli olmadığını, bu yüzden DRAFT kullanılabileceğini belirtir.

### Draft {#Draft}
```
public static final byte Draft
```


Yazı tipinin karakter kalitesinin, mantıksal özniteliklerin eşleşmesinden daha az önemli olduğunu belirtir. Rasterleştirilmiş yazı tipleri için ölçekleme KULLANILMALI, bu da daha fazla yazı tipi boyutunun mevcut olduğu anlamına gelir.

### Proof {#Proof}
```
public static final byte Proof
```


Yazı tipinin karakter kalitesinin, mantıksal özniteliklerin eşleşmesinden daha önemli olduğunu belirtir. Rasterleştirilmiş yazı tipleri için ölçekleme DEVRE DIŞI BIRAKILMALI ve boyutu en yakın olan yazı tipi SEÇİLMELİDİR.

### Nonantialiased {#Nonantialiased}
```
public static final byte Nonantialiased
```


Metin render edildiğinde anti-aliasing'in KULLANILMAMASI gerektiğini belirtir.

### Antialiased {#Antialiased}
```
public static final byte Antialiased
```


Metin render edildiğinde, yazı tipi destekliyorsa anti-aliasing'in KULLANILMASI gerektiğini belirtir.

### Cleartype {#Cleartype}
```
public static final byte Cleartype
```


Metin render edildiğinde, yazı tipi destekliyorsa ClearType anti-aliasing'in KULLANILMASI gerektiğini belirtir.

