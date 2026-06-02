---
title: "EmfLogFontPanose"
second_title: "Aspose.Imaging for Java API Referansı"
description: "LogFontPanose nesnesi, mantıksal bir fontun PANOSE özelliklerini belirtir."
type: docs
weight: 25
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public final class EmfLogFontPanose extends EmfLogFont
```

LogFontPanose nesnesi, mantıksal bir fontun PANOSE özelliklerini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfLogFontPanose(EmfLogFont emfLogFont)](#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | `EmfLogFontPanose` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFullName()](#getFullName--) | Yazı tipinin tam adını tanımlayan 64 Unicode karakterlik bir dize alır veya ayarlar. |
| [setFullName(String value)](#setFullName-java.lang.String-) | Yazı tipinin tam adını tanımlayan 64 Unicode karakterlik bir dize alır veya ayarlar. |
| [getStyle()](#getStyle--) | Alır veya ayarlar fontun stilini tanımlayan 32 Unicode karakterlik bir dizeyi. |
| [setStyle(String value)](#setStyle-java.lang.String-) | Alır veya ayarlar fontun stilini tanımlayan 32 Unicode karakterlik bir dizeyi. |
| [getVersion()](#getVersion--) | Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar. |
| [setVersion(int value)](#setVersion-int-) | Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar. |
| [getStyleSize()](#getStyleSize--) | Yazı tipi ipucu işleminin gerçekleştirildiği nokta boyutunu belirten 32-bit işaretsiz tamsayı alır veya ayarlar. |
| [setStyleSize(int value)](#setStyleSize-int-) | Yazı tipi ipucu işleminin gerçekleştirildiği nokta boyutunu belirten 32-bit işaretsiz tamsayı alır veya ayarlar. |
| [getMatch()](#getMatch--) | Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar. |
| [setMatch(int value)](#setMatch-int-) | Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar. |
| [getVendorId()](#getVendorId--) | Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar. |
| [setVendorId(int value)](#setVendorId-int-) | Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar. |
| [getCulture()](#getCulture--) | Sıfıra ayarlanması **MUST** ve yok sayılması **MUST** gereken 32-bit işaretsiz tamsayı alır veya ayarlar. |
| [setCulture(int value)](#setCulture-int-) | Sıfıra ayarlanması **MUST** ve yok sayılması **MUST** gereken 32-bit işaretsiz tamsayı alır veya ayarlar. |
| [getPanose()](#getPanose--) | Mantıksal yazı tipinin PANOSE özelliklerini belirten bir Panose nesnesi (bölüm 2.2.21) alır veya ayarlar. |
| [setPanose(EmfPanose value)](#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-) | Mantıksal yazı tipinin PANOSE özelliklerini belirten bir Panose nesnesi (bölüm 2.2.21) alır veya ayarlar. |
| [getPadding()](#getPadding--) | Bu yapının 32-bit hizalamasını sağlamak için yalnızca var olan bir alan alır veya ayarlar. |
| [setPadding(short value)](#setPadding-short-) | Bu yapının 32-bit hizalamasını sağlamak için yalnızca var olan bir alan alır veya ayarlar. |
### EmfLogFontPanose(EmfLogFont emfLogFont) {#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontPanose(EmfLogFont emfLogFont)
```


`EmfLogFontPanose` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | Temel log yazı tipi. |

### getFullName() {#getFullName--}
```
public String getFullName()
```


Yazı tipinin tam adını tanımlayan 64 Unicode karakterlik bir dize alır veya ayarlar. Bu dizenin uzunluğu 64 karakterden az ise, sonlandırıcı NULL **MUST** bulunmalı ve ardından bu alanın geri kalanı **MUST** yok sayılmalıdır.

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


Yazı tipinin tam adını tanımlayan 64 Unicode karakterlik bir dize alır veya ayarlar. Bu dizenin uzunluğu 64 karakterden az ise, sonlandırıcı NULL **MUST** bulunmalı ve ardından bu alanın geri kalanı **MUST** yok sayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getStyle() {#getStyle--}
```
public String getStyle()
```


Alır veya ayarlar fontun stilini tanımlayan 32 Unicode karakterlik bir dizeyi. Bu dize uzunluğu 32 karakterden az ise, sonlandırıcı NULL MUST bulunmalı, ardından bu alanın geri kalanı MUST yok sayılmalıdır.

**Returns:**
java.lang.String
### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


Alır veya ayarlar fontun stilini tanımlayan 32 Unicode karakterlik bir dizeyi. Bu dize uzunluğu 32 karakterden az ise, sonlandırıcı NULL MUST bulunmalı, ardından bu alanın geri kalanı MUST yok sayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStyleSize() {#getStyleSize--}
```
public int getStyleSize()
```


Yazı tipi ipucu işleminin gerçekleştirildiği nokta boyutunu belirten 32-bit işaretsiz tamsayı alır veya ayarlar. Sıfıra ayarlanırsa, yazı tipi ipucu, LogFont alanındaki Height alanına karşılık gelen nokta boyutunda gerçekleştirilir.

**Returns:**
int
### setStyleSize(int value) {#setStyleSize-int-}
```
public void setStyleSize(int value)
```


Yazı tipi ipucu işleminin gerçekleştirildiği nokta boyutunu belirten 32-bit işaretsiz tamsayı alır veya ayarlar. Sıfıra ayarlanırsa, yazı tipi ipucu, LogFont alanındaki Height alanına karşılık gelen nokta boyutunda gerçekleştirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMatch() {#getMatch--}
```
public int getMatch()
```


Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar.

**Returns:**
int
### setMatch(int value) {#setMatch-int-}
```
public void setMatch(int value)
```


Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVendorId() {#getVendorId--}
```
public int getVendorId()
```


Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar.

**Returns:**
int
### setVendorId(int value) {#setVendorId-int-}
```
public void setVendorId(int value)
```


Bu alan **MUST** yok sayılmalıdır; alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCulture() {#getCulture--}
```
public int getCulture()
```


Sıfıra ayarlanması **MUST** ve yok sayılması **MUST** gereken 32-bit işaretsiz tamsayı alır veya ayarlar.

**Returns:**
int
### setCulture(int value) {#setCulture-int-}
```
public void setCulture(int value)
```


Sıfıra ayarlanması **MUST** ve yok sayılması **MUST** gereken 32-bit işaretsiz tamsayı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPanose() {#getPanose--}
```
public EmfPanose getPanose()
```


Mantıksal yazı tipinin PANOSE özelliklerini belirten bir Panose nesnesi (bölüm 2.2.21) alır veya ayarlar. Bu nesnenin tüm alanları sıfır ise, **MUST** yok sayılmalıdır.

**Returns:**
[EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose)
### setPanose(EmfPanose value) {#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-}
```
public void setPanose(EmfPanose value)
```


Mantıksal yazı tipinin PANOSE özelliklerini belirten bir Panose nesnesi (bölüm 2.2.21) alır veya ayarlar. Bu nesnenin tüm alanları sıfır ise, **MUST** yok sayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose) |  |

### getPadding() {#getPadding--}
```
public short getPadding()
```


Bu yapının 32-bit hizalamasını sağlamak için yalnızca var olan bir alan alır veya ayarlar. **MUST** yok sayılmalıdır.

**Returns:**
short
### setPadding(short value) {#setPadding-short-}
```
public void setPadding(short value)
```


Bu yapının 32-bit hizalamasını sağlamak için yalnızca var olan bir alan alır veya ayarlar. **MUST** yok sayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

