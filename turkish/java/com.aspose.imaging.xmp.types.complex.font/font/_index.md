---
title: "Yazı tipi"
second_title: "Aspose.Imaging for Java API Referansı"
description: "XMP Yazı tipini temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.xmp.types.complex.font/font/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

XMP Yazı tipini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Font()](#Font--) | Yeni bir `Font` sınıfı örneği başlatır. |
| [Font(String fontFamily)](#Font-java.lang.String-) | Yeni bir `Font` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChildFontFiles()](#getChildFontFiles--) | Bir birleşik yazı tipini oluşturan yazı tipleri için dosya adı dizisini alır veya ayarlar. |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Bir birleşik yazı tipini oluşturan yazı tipleri için dosya adı dizisini alır veya ayarlar. |
| [isComposite()](#isComposite--) | Bu yazı tipinin birleşik olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setComposite(boolean value)](#setComposite-boolean-) | Bu yazı tipinin birleşik olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getFontFace()](#getFontFace--) | Yazı tipi yüzünü alır veya ayarlar. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Yazı tipi yüzünü alır veya ayarlar. |
| [getFontFamily()](#getFontFamily--) | Yazı tipi ailesini alır veya ayarlar. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Yazı tipi ailesini alır veya ayarlar. |
| [getFontFileName()](#getFontFileName--) | Tam yol olmadan yazı tipi dosya adını alır veya ayarlar. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Tam yol olmadan yazı tipi dosya adını alır veya ayarlar. |
| [getFontName()](#getFontName--) | PostScript yazı tipi adını alır veya ayarlar. |
| [setFontName(String value)](#setFontName-java.lang.String-) | PostScript yazı tipi adını alır veya ayarlar. |
| [getFontType()](#getFontType--) | Yazı tipi türünü alır veya ayarlar. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Yazı tipi türünü alır veya ayarlar. |
| [getVersion()](#getVersion--) | Yazı tipi sürümünü alır veya ayarlar. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Yazı tipi sürümünü alır veya ayarlar. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP formatında içerilen dize değerini alır. |
### Font() {#Font--}
```
public Font()
```


Yeni bir `Font` sınıfı örneği başlatır.

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Yeni bir `Font` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontFamily | java.lang.String | Yazı tipi ailesi. |

### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Bir birleşik yazı tipini oluşturan yazı tipleri için dosya adı dizisini alır veya ayarlar.

Değer: Bir birleşik yazı tipini oluşturan yazı tipleri için dosya adı dizisi.

**Returns:**
java.lang.String[]
### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


Bir birleşik yazı tipini oluşturan yazı tipleri için dosya adı dizisini alır veya ayarlar.

Değer: Bir birleşik yazı tipini oluşturan yazı tipleri için dosya adı dizisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String[] |  |

### isComposite() {#isComposite--}
```
public boolean isComposite()
```


Bu yazı tipinin birleşik olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: Bu yazı tipi birleşik ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Bu yazı tipinin birleşik olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: Bu yazı tipi birleşik ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


Yazı tipi yüzünü alır veya ayarlar.

Değer: Yazı tipi yüzü.

**Returns:**
java.lang.String
### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Yazı tipi yüzünü alır veya ayarlar.

Değer: Yazı tipi yüzü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Yazı tipi ailesini alır veya ayarlar.

Değer: Yazı tipi ailesi.

**Returns:**
java.lang.String
### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Yazı tipi ailesini alır veya ayarlar.

Değer: Yazı tipi ailesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Tam yol olmadan yazı tipi dosya adını alır veya ayarlar.

Değer: Tam yol olmadan yazı tipi dosya adı.

**Returns:**
java.lang.String
### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Tam yol olmadan yazı tipi dosya adını alır veya ayarlar.

Değer: Tam yol olmadan yazı tipi dosya adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontName() {#getFontName--}
```
public String getFontName()
```


PostScript yazı tipi adını alır veya ayarlar.

Değer: PostScript yazı tipi adı.

**Returns:**
java.lang.String
### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


PostScript yazı tipi adını alır veya ayarlar.

Değer: PostScript yazı tipi adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontType() {#getFontType--}
```
public String getFontType()
```


Yazı tipi türünü alır veya ayarlar.

TrueType, Type 1, Open Type vb. Değer: Yazı tipi türü.

**Returns:**
java.lang.String
### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Yazı tipi türünü alır veya ayarlar.

TrueType, Type 1, Open Type vb. Değer: Yazı tipi türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Yazı tipi sürümünü alır veya ayarlar.

/version for Type1 fonts nameId 5 for Apple True Type and OpenType /CIDFontVersion for CID fonts bitmap fontlar için boş dize Değer: Yazı tipi sürümü.

**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Yazı tipi sürümünü alır veya ayarlar.

/version for Type1 fonts nameId 5 for Apple True Type and OpenType /CIDFontVersion for CID fonts bitmap fontlar için boş dize Değer: Yazı tipi sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP formatında içerilen dize değerini alır.

**Returns:**
java.lang.String - XMP biçiminde içerilen dize değerini döndürür.
