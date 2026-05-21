---
title: "EmfRegionData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "RegionData nesnesi, üst üste gelmeyen dikdörtgenlerden oluşan bir bölgeyi tanımlayan verileri belirtir."
type: docs
weight: 33
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionData extends EmfObject
```

RegionData nesnesi, birbirine çakışmayan dikdörtgenlerden oluşan bir bölgeyi tanımlayan verileri belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfRegionData()](#EmfRegionData--) | Yeni bir `EmfRegionData` sınıfı örneği başlatır. |
| [EmfRegionData(Rectangle rectangle)](#EmfRegionData-com.aspose.imaging.Rectangle-) | Yeni bir `EmfRegionData` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRegionDataHeader()](#getRegionDataHeader--) | Aşağıdaki verileri tanımlayan 256-bit RegionDataHeader nesnesini alır. |
| [setRegionDataHeader(EmfRegionDataHeader value)](#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-) | Aşağıdaki verileri tanımlayan 256-bit RegionDataHeader nesnesini ayarlar. |
| [getData()](#getData--) | WMF RectL nesnelerinin bir dizisini alır ([MS-WMF] bölüm 2.2.2.19); nesneler birleştirilerek bölge oluşturulur. |
| [setData(Rectangle[] value)](#setData-com.aspose.imaging.Rectangle---) | WMF RectL nesnelerinin bir dizisini ayarlar ([MS-WMF] bölüm 2.2.2.19); nesneler birleştirilerek bölge oluşturulur. |
### EmfRegionData() {#EmfRegionData--}
```
public EmfRegionData()
```


Yeni bir `EmfRegionData` sınıfı örneği başlatır.

### EmfRegionData(Rectangle rectangle) {#EmfRegionData-com.aspose.imaging.Rectangle-}
```
public EmfRegionData(Rectangle rectangle)
```


Yeni bir `EmfRegionData` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |

### getRegionDataHeader() {#getRegionDataHeader--}
```
public EmfRegionDataHeader getRegionDataHeader()
```


Aşağıdaki verileri tanımlayan 256-bit RegionDataHeader nesnesini alır.

**Returns:**
[EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader)
### setRegionDataHeader(EmfRegionDataHeader value) {#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-}
```
public void setRegionDataHeader(EmfRegionDataHeader value)
```


Aşağıdaki verileri tanımlayan 256-bit RegionDataHeader nesnesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader) |  |

### getData() {#getData--}
```
public Rectangle[] getData()
```


WMF RectL nesnelerinin bir dizisini alır ([MS-WMF] bölüm 2.2.2.19); nesneler birleştirilerek bölge oluşturulur.

**Returns:**
com.aspose.imaging.Rectangle[]
### setData(Rectangle[] value) {#setData-com.aspose.imaging.Rectangle---}
```
public void setData(Rectangle[] value)
```


WMF RectL nesnelerinin bir dizisini ayarlar ([MS-WMF] bölüm 2.2.2.19); nesneler birleştirilerek bölge oluşturulur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

