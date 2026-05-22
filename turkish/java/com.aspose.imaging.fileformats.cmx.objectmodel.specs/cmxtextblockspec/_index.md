---
title: "CmxTextBlockSpec"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Metin blokları için belirtilen bilgiyi temsil eder."
type: docs
weight: 17
url: /tr/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxtextblockspec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxTextBlockSpec implements ICmxObjectSpec
```

Metin blokları için belirtilen bilgiyi temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CmxTextBlockSpec()](#CmxTextBlockSpec--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParagraphStyle()](#getParagraphStyle--) | paragraf stilini alır. |
| [setParagraphStyle(CmxParagraphStyle value)](#setParagraphStyle-com.aspose.imaging.fileformats.cmx.objectmodel.styles.CmxParagraphStyle-) | paragraf stilini ayarlar. |
| [getFont()](#getFont--) | yazı tipini alır. |
| [setFont(Font value)](#setFont-com.aspose.imaging.Font-) | Yazı tipini ayarlar. |
| [getMatrix()](#getMatrix--) | Dönüşüm matrisini alır. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.imaging.Matrix-) | Dönüşüm matrisini ayarlar. |
| [getText()](#getText--) | Metni alır. |
| [setText(String value)](#setText-java.lang.String-) | Metni ayarlar. |
| [getCharLocations()](#getCharLocations--) | Karakter konumlarını alır. |
| [setCharLocations(PointF[] value)](#setCharLocations-com.aspose.imaging.PointF---) | Karakter konumlarını ayarlar. |
| [equals(Object o)](#equals-java.lang.Object-) | Nesnelerin eşit olup olmadığını kontrol et. |
| [hashCode()](#hashCode--) | Geçerli nesnenin karma kodunu al. |
### CmxTextBlockSpec() {#CmxTextBlockSpec--}
```
public CmxTextBlockSpec()
```


### getParagraphStyle() {#getParagraphStyle--}
```
public final CmxParagraphStyle getParagraphStyle()
```


paragraf stilini alır.

**Returns:**
[CmxParagraphStyle](../../com.aspose.imaging.fileformats.cmx.objectmodel.styles/cmxparagraphstyle) - the paragraph style.
### setParagraphStyle(CmxParagraphStyle value) {#setParagraphStyle-com.aspose.imaging.fileformats.cmx.objectmodel.styles.CmxParagraphStyle-}
```
public final void setParagraphStyle(CmxParagraphStyle value)
```


paragraf stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CmxParagraphStyle](../../com.aspose.imaging.fileformats.cmx.objectmodel.styles/cmxparagraphstyle) | paragraf stilini. |

### getFont() {#getFont--}
```
public final Font getFont()
```


yazı tipini alır.

**Returns:**
[Font](../../com.aspose.imaging/font) - the font.
### setFont(Font value) {#setFont-com.aspose.imaging.Font-}
```
public final void setFont(Font value)
```


Yazı tipini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Font](../../com.aspose.imaging/font) | yazı tipi. |

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


Dönüşüm matrisini alır.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - the transformation matrix.
### setMatrix(Matrix value) {#setMatrix-com.aspose.imaging.Matrix-}
```
public final void setMatrix(Matrix value)
```


Dönüşüm matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | dönüşüm matrisi. |

### getText() {#getText--}
```
public final String getText()
```


Metni alır.

**Returns:**
java.lang.String - metin.
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Metni ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | metin. |

### getCharLocations() {#getCharLocations--}
```
public final PointF[] getCharLocations()
```


Karakter konumlarını alır.

**Returns:**
com.aspose.imaging.PointF[] - karakter konumları.
### setCharLocations(PointF[] value) {#setCharLocations-com.aspose.imaging.PointF---}
```
public final void setCharLocations(PointF[] value)
```


Karakter konumlarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) | karakter konumları. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Nesnelerin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object | Diğer nesne. |

**Returns:**
boolean - Eşitlik karşılaştırma sonucu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesnenin karma kodunu al.

**Returns:**
int - Hash kodu.
