---
title: "EmfRegionDataHeader"
second_title: "Aspose.Imaging for Java API Referansı"
description: "RegionDataHeader nesnesi, bir RegionData nesnesinin özelliklerini tanımlar."
type: docs
weight: 34
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionDataHeader extends EmfObject
```

RegionDataHeader nesnesi, bir RegionData nesnesinin özelliklerini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | Bu nesnenin bayt cinsinden boyutunu belirten 32 bit işaretsiz tam sayıyı alır. |
| [setSize(int value)](#setSize-int-) | Bu nesnenin bayt cinsinden boyutunu belirten 32 bit işaretsiz tam sayıyı ayarlar. |
| [getType()](#getType--) | Bölge tipini belirten 32 bit işaretsiz tam sayıyı alır. |
| [setType(int value)](#setType-int-) | Bölge tipini belirten 32 bit işaretsiz tam sayıyı ayarlar. |
| [getCountRects()](#getCountRects--) | Bu bölgede bulunan dikdörtgen sayısını belirten 32 bit işaretsiz tam sayıyı alır. |
| [setCountRects(int value)](#setCountRects-int-) | Bu bölgede bulunan dikdörtgen sayısını belirten 32 bit işaretsiz tamsayıyı ayarlar. |
| [getRgnSize()](#getRgnSize--) | Dikdörtgen tamponunun bayt cinsinden boyutunu belirten 32 bit işaretsiz tamsayıyı alır. |
| [setRgnSize(int value)](#setRgnSize-int-) | Dikdörtgen tamponunun bayt cinsinden boyutunu belirten 32 bit işaretsiz tamsayıyı ayarlar. |
| [getBounds()](#getBounds--) | Bölgenin sınırlarını belirten 128 bit WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Bölgenin sınırlarını belirten 128 bit WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) ayarlar. |
### EmfRegionDataHeader() {#EmfRegionDataHeader--}
```
public EmfRegionDataHeader()
```


### getSize() {#getSize--}
```
public int getSize()
```


Bu nesnenin bayt cinsinden boyutunu belirten 32 bit işaretsiz tamsayıyı alır. Bu 0x00000020 olmalıdır.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Bu nesnenin bayt cinsinden boyutunu belirten 32 bit işaretsiz tamsayıyı ayarlar. Bu 0x00000020 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getType() {#getType--}
```
public int getType()
```


Bölge tipini belirten 32 bit işaretsiz tamsayıyı alır. Bu RDH\_RECTANGLES (0x00000001) olmalıdır.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Bölge tipini belirten 32 bit işaretsiz tamsayıyı ayarlar. Bu RDH\_RECTANGLES (0x00000001) olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCountRects() {#getCountRects--}
```
public int getCountRects()
```


Bu bölgede bulunan dikdörtgen sayısını belirten 32 bit işaretsiz tam sayıyı alır.

**Returns:**
int
### setCountRects(int value) {#setCountRects-int-}
```
public void setCountRects(int value)
```


Bu bölgede bulunan dikdörtgen sayısını belirten 32 bit işaretsiz tamsayıyı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRgnSize() {#getRgnSize--}
```
public int getRgnSize()
```


Dikdörtgen tamponunun bayt cinsinden boyutunu belirten 32 bit işaretsiz tamsayıyı alır.

**Returns:**
int
### setRgnSize(int value) {#setRgnSize-int-}
```
public void setRgnSize(int value)
```


Dikdörtgen tamponunun bayt cinsinden boyutunu belirten 32 bit işaretsiz tamsayıyı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Bölgenin sınırlarını belirten 128 bit WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Bölgenin sınırlarını belirten 128 bit WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

