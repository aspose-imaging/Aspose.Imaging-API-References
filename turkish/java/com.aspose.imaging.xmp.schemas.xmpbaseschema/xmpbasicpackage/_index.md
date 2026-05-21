---
title: "XmpBasicPackage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "XMP temel ad alanını temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

XMP temel ad alanını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Yeni bir `XmpBasicPackage` sınıfı örneğini başlatır. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Yeni bir `XmpBasicPackage` sınıfı örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [RATING_REJECTED](#RATING-REJECTED) | Puan reddedilen değer. |
| [RATING_MIN](#RATING-MIN) | Puan minimum değer. |
| [RATING_MAX](#RATING-MAX) | Puan maksimum değer. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setLabel(String label)](#setLabel-java.lang.String-) | Etiketi ayarlar. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Dize özelliği ekler. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Kaynak oluşturulma tarihini ekler. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Kaynak oluşturulma tarihini ekler. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Oluşturucu aracını ayarlar. |
| [setIdentifier(String[] identifier)](#setIdentifier-java.lang.String---) | Tanımlayıcıyı ayarlar. |
| [setMetadataDate(Date metadataDate)](#setMetadataDate-java.util.Date-) | Meta verilerin son değiştirilme tarihini ekler. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Meta verilerin son değiştirilme tarihini ekler. |
| [setModifyDate(Date modifiedDate)](#setModifyDate-java.util.Date-) | Kaynak son değiştirilme tarihini ekler. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Kaynak son değiştirilme tarihini ekler. |
| [setRating(int choice)](#setRating-int-) | Puanı ayarlar. |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Yeni bir `XmpBasicPackage` sınıfı örneğini başlatır.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Yeni bir `XmpBasicPackage` sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| önek | java.lang.String | Önek. |
| namespaceUri | java.lang.String | Ad alanı URI'si. |

### RATING_REJECTED {#RATING-REJECTED}
```
public static final int RATING_REJECTED
```


Puan reddedilen değer.

### RATING_MIN {#RATING-MIN}
```
public static final int RATING_MIN
```


Puan minimum değer.

### RATING_MAX {#RATING-MAX}
```
public static final int RATING_MAX
```


Puan maksimum değer.

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Etiketi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| etiket | java.lang.String | Etiket. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Dize özelliği ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | java.lang.String | Dize değeri. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Kaynak oluşturulma tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createdDate | java.util.Date | Oluşturulma tarihi. |

### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Kaynak oluşturulma tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createdDate | java.lang.String | Oluşturulma tarihi. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Oluşturucu aracını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| creatorTool | java.lang.String | Aracın adı. |

### setIdentifier(String[] identifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] identifier)
```


Tanımlayıcıyı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tanımlayıcı | java.lang.String[] | Tanımlayıcı. |

### setMetadataDate(Date metadataDate) {#setMetadataDate-java.util.Date-}
```
public void setMetadataDate(Date metadataDate)
```


Meta verilerin son değiştirilme tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metadataDate | java.util.Date | Meta veri tarihi. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Meta verilerin son değiştirilme tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metadataDate | java.lang.String | Meta veri tarihi. |

### setModifyDate(Date modifiedDate) {#setModifyDate-java.util.Date-}
```
public void setModifyDate(Date modifiedDate)
```


Kaynak son değiştirilme tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| modifiedDate | java.util.Date | Son değiştirilme tarihi. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Kaynak son değiştirilme tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| modifiedDate | java.lang.String | Son değiştirilme tarihi. |

### setRating(int choice) {#setRating-int-}
```
public void setRating(int choice)
```


Puanı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seçim | int | -1'den 5'e kadar |

