---
title: "EmfRecord"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMF kayıtları için temel sınıf Tüm EMF kayıtlarının uzunluğu 4 baytın katı olmalıdır."
type: docs
weight: 106
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfRecord extends MetaObject implements IRecord
```

EMF kayıtları için temel sınıf. Tüm EMF kayıtlarının uzunluğu 4 baytın katı olmalıdır. Bu, önceki EMF kayıt türlerinin genel yapılarında, uygun yerlerde yapıların sonuna AlignmentPadding alanları eklenerek gösterilir. AlignmentPadding alanlarının içeriği MUST her zaman yok sayılmalıdır. Kısalık açısından, bu alanlar her bireysel EMF kaydı tanımında gösterilmemiştir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfRecord()](#EmfRecord--) | `EmfRecord` sınıfının yeni bir örneğini başlatır. |
| [EmfRecord(EmfRecord source)](#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfRecord` sınıfının yeni bir örneğini başlatır. |
| [EmfRecord(int type)](#EmfRecord-int-) | `EmfRecord` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Türü alır. |
| [setType(int value)](#setType-int-) | Türü ayarlar. |
| [getSize()](#getSize--) | Kaydın boyutunu alır. |
| [setSize(int value)](#setSize-int-) | Kaydın boyutunu ayarlar. |
### EmfRecord() {#EmfRecord--}
```
public EmfRecord()
```


`EmfRecord` sınıfının yeni bir örneğini başlatır.

### EmfRecord(EmfRecord source) {#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRecord(EmfRecord source)
```


`EmfRecord` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfRecord(int type) {#EmfRecord-int-}
```
public EmfRecord(int type)
```


`EmfRecord` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Kayıt türü. |

### getType() {#getType--}
```
public int getType()
```


Türü alır.

**Returns:**
int - Tür.
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Türü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Tür. |

### getSize() {#getSize--}
```
public int getSize()
```


Kaydın boyutunu alır.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Kaydın boyutunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

