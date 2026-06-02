---
title: "EmfSetPaletteEntries"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SETPALETTEENTRIES kaydı, mevcut bir LogPalette (bölüm 2.2.17) nesnesi için giriş aralığındaki RGB renk değerlerini tanımlar."
type: docs
weight: 134
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetPaletteEntries extends EmfObjectManipulationRecordType
```

EMR\_SETPALETTEENTRIES kaydı, mevcut bir LogPalette (bölüm 2.2.17) nesnesi için giriş aralığında RGB renk değerlerini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfSetPaletteEntries(EmfRecord source)](#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfSetPaletteEntries` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIhPal()](#getIhPal--) | Palet EMF Object Table dizinini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setIhPal(int value)](#setIhPal-int-) | Palet EMF Object Table dizinini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getStart()](#getStart--) | Ayarlanacak ilk girişin dizinini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setStart(int value)](#setStart-int-) | Ayarlanacak ilk girişin dizinini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getNumberofEntries()](#getNumberofEntries--) | Giriş sayısını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setNumberofEntries(int value)](#setNumberofEntries-int-) | Giriş sayısını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getArgb32PalEntries()](#getArgb32PalEntries--) | Palet giriş verilerini belirten, NumberOfEntries uzunluğunda LogPaletteEntry (bölüm 2.2.18) nesnelerinden oluşan bir dizi alır veya ayarlar. |
| [setArgb32PalEntries(int[] value)](#setArgb32PalEntries-int---) | Palet giriş verilerini belirten, NumberOfEntries uzunluğunda LogPaletteEntry (bölüm 2.2.18) nesnelerinden oluşan bir dizi alır veya ayarlar. |
### EmfSetPaletteEntries(EmfRecord source) {#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPaletteEntries(EmfRecord source)
```


Yeni bir `EmfSetPaletteEntries` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Palet EMF Object Table dizinini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Palet EMF Object Table dizinini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStart() {#getStart--}
```
public int getStart()
```


Ayarlanacak ilk girişin dizinini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setStart(int value) {#setStart-int-}
```
public void setStart(int value)
```


Ayarlanacak ilk girişin dizinini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getNumberofEntries() {#getNumberofEntries--}
```
public int getNumberofEntries()
```


Giriş sayısını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setNumberofEntries(int value) {#setNumberofEntries-int-}
```
public void setNumberofEntries(int value)
```


Giriş sayısını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getArgb32PalEntries() {#getArgb32PalEntries--}
```
public int[] getArgb32PalEntries()
```


Palet giriş verilerini belirten, NumberOfEntries uzunluğunda LogPaletteEntry (bölüm 2.2.18) nesnelerinden oluşan bir dizi alır veya ayarlar. Values üyeleri herhangi bir değer içermez.

**Returns:**
int[]
### setArgb32PalEntries(int[] value) {#setArgb32PalEntries-int---}
```
public void setArgb32PalEntries(int[] value)
```


Palet giriş verilerini belirten, NumberOfEntries uzunluğunda LogPaletteEntry (bölüm 2.2.18) nesnelerinden oluşan bir dizi alır veya ayarlar. Values üyeleri herhangi bir değer içermez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

