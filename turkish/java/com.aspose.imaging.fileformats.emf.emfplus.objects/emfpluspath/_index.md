---
title: "EmfPlusPath"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusPath nesnesi, bir grafik yolu oluşturan çizgi ve eğri segmentlerinden oluşan bir dizi belirtir."
type: docs
weight: 58
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusPath extends EmfPlusGraphicsObjectType
```

EmfPlusPath nesnesi, bir grafik yolunu oluşturan bir dizi çizgi ve eğri segmentini belirtir. Bezier veri noktalarının sırası başlangıç noktası, kontrol noktası 1, kontrol noktası 2 ve bitiş noktasıdır. Daha fazla bilgi için [MSDN - DrawBeziers] bölümüne bakın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusPath()](#EmfPlusPath--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPathPointFlags()](#getPathPointFlags--) | Path noktası sayısını alır veya ayarlar. Bu nesne tarafından tanımlanan noktaları ve ilişkili nokta türlerini nasıl yorumlayacağını belirten 32 bit işaretsiz tamsayı. |
| [setPathPointFlags(short value)](#setPathPointFlags-short-) | Path noktası sayısını alır veya ayarlar. Bu nesne tarafından tanımlanan noktaları ve ilişkili nokta türlerini nasıl yorumlayacağını belirten 32 bit işaretsiz tamsayı. |
| [getPathPoints()](#getPathPoints--) | Yolu belirten PathPointCount noktasından oluşan bir dizi yol noktasını alır veya ayarlar. |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | Yolu belirten PathPointCount noktasından oluşan bir dizi yol noktasını alır veya ayarlar. |
| [getPathPointTypes()](#getPathPointTypes--) | PathPoints alanındaki noktaların yolu çizmek için nasıl kullanılacağını belirten bir diziyi alır veya ayarlar. |
| [setPathPointTypes(EmfPlusBasePointType[] value)](#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---) | PathPoints alanındaki noktaların yolu çizmek için nasıl kullanılacağını belirten bir diziyi alır veya ayarlar. |
### EmfPlusPath() {#EmfPlusPath--}
```
public EmfPlusPath()
```


### getPathPointFlags() {#getPathPointFlags--}
```
public short getPathPointFlags()
```


Path noktası sayısını alır veya ayarlar. Bu nesne tarafından tanımlanan noktaları ve ilişkili nokta türlerini nasıl yorumlayacağını belirten 32 bit işaretsiz tamsayı.

**Returns:**
short
### setPathPointFlags(short value) {#setPathPointFlags-short-}
```
public void setPathPointFlags(short value)
```


Path noktası sayısını alır veya ayarlar. Bu nesne tarafından tanımlanan noktaları ve ilişkili nokta türlerini nasıl yorumlayacağını belirten 32 bit işaretsiz tamsayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Yolu belirten PathPointCount noktasından oluşan bir dizi yol noktasını alır veya ayarlar. Bu dizideki nesnelerin türü PathPointFlags alanı tarafından aşağıdaki gibi belirlenir: P bayrağı ayarlıysa, noktalar EmfPlusPointR nesneleri (bölüm 2.2.2.37) tarafından belirtilen göreli konumlardır. P bayrağı temiz ve C bayrağı ayarlıysa, noktalar EmfPlusPoint nesneleri (bölüm 2.2.2.35) tarafından belirtilen mutlak konumlardır. P ve C bayrakları temizse, noktalar EmfPlusPointF nesneleri (bölüm 2.2.2.36) tarafından belirtilen mutlak konumlardır.

**Returns:**
com.aspose.imaging.PointF[]
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public void setPathPoints(PointF[] value)
```


Yolu belirten PathPointCount noktasından oluşan bir dizi yol noktasını alır veya ayarlar. Bu dizideki nesnelerin türü PathPointFlags alanı tarafından aşağıdaki gibi belirlenir: P bayrağı ayarlıysa, noktalar EmfPlusPointR nesneleri (bölüm 2.2.2.37) tarafından belirtilen göreli konumlardır. P bayrağı temiz ve C bayrağı ayarlıysa, noktalar EmfPlusPoint nesneleri (bölüm 2.2.2.35) tarafından belirtilen mutlak konumlardır. P ve C bayrakları temizse, noktalar EmfPlusPointF nesneleri (bölüm 2.2.2.36) tarafından belirtilen mutlak konumlardır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getPathPointTypes() {#getPathPointTypes--}
```
public EmfPlusBasePointType[] getPathPointTypes()
```


PathPoints alanındaki noktaların yolu çizmek için nasıl kullanılacağını belirten bir diziyi alır veya ayarlar. Bu dizideki nesnelerin türü PathPointFlags alanındaki R bayrağı tarafından belirlenir.

Değer: Yol nokta türleri.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType[]
### setPathPointTypes(EmfPlusBasePointType[] value) {#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---}
```
public void setPathPointTypes(EmfPlusBasePointType[] value)
```


PathPoints alanındaki noktaların yolu çizmek için nasıl kullanılacağını belirten bir diziyi alır veya ayarlar. Bu dizideki nesnelerin türü PathPointFlags alanındaki R bayrağı tarafından belirlenir.

Değer: Yol nokta türleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusBasePointType\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype) |  |

