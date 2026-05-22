---
title: "EmfPlusPathGradientBrushData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusPathGradientBrushData nesnesi, bir grafik fırçası için yol degrade (gradient) belirtir."
type: docs
weight: 59
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusPathGradientBrushData extends EmfPlusBaseBrushData
```

EmfPlusPathGradientBrushData nesnesi, bir grafik fırçası için yol degrade (gradient) belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | OptionalData alanındaki veriyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | OptionalData alanındaki veriyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getWrapMode()](#getWrapMode--) | Brush'ın sınırının dışındaki alanın boyanıp boyanmayacağını belirten WrapMode enumarasyonundan (bölüm 2.1.1.34) 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setWrapMode(int value)](#setWrapMode-int-) | Brush'ın sınırının dışındaki alanın boyanıp boyanmayacağını belirten WrapMode enumarasyonundan (bölüm 2.1.1.34) 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | Alır veya ayarlar EmfPlusARGB nesnesi (bölüm 2.2.2.1) yol gradyan fırçasının merkez rengini belirten, fırçanın merkez noktasında görülen renk. |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | Alır veya ayarlar EmfPlusARGB nesnesi (bölüm 2.2.2.1) yol gradyan fırçasının merkez rengini belirten, fırçanın merkez noktasında görülen renk. |
| [getCenterPointF()](#getCenterPointF--) | Alır veya ayarlar EmfPlusARGB nesnesi (bölüm 2.2.2.1) yol gradyan fırçasının merkez rengini belirten, fırçanın merkez noktasında görülen renk. |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | Alır veya ayarlar EmfPlusARGB nesnesi (bölüm 2.2.2.1) yol gradyan fırçasının merkez rengini belirten, fırçanın merkez noktasında görülen renk. |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | Alır veya ayarlar SurroundingColorCount EmfPlusARGB nesnelerinin dizisini, fırçanın sınırındaki ayrı noktalar için renkleri belirten. |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | Alır veya ayarlar SurroundingColorCount EmfPlusARGB nesnelerinin dizisini, fırçanın sınırındaki ayrı noktalar için renkleri belirten. |
| [getBoundaryData()](#getBoundaryData--) | Alır veya ayarlar yol gradyan fırçasının sınırını, bu sınırın bir yol veya kapalı kardinal spline ile belirtildiği. |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | Alır veya ayarlar yol gradyan fırçasının sınırını, bu sınırın bir yol veya kapalı kardinal spline ile belirtildiği. |
| [getOptionalData()](#getOptionalData--) | Alır veya ayarlar isteğe bağlı EmfPlusPathGradientBrushOptionalData nesnesi (bölüm 2.2.2.30), yol gradyan fırçası için ek verileri belirten. |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | Alır veya ayarlar isteğe bağlı EmfPlusPathGradientBrushOptionalData nesnesi (bölüm 2.2.2.30), yol gradyan fırçası için ek verileri belirten. |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Alır veya ayarlar 32 bit işaretsiz tamsayı, OptionalData alanındaki veriyi belirten. Bu değer BrushData bayraklarından (bölüm 2.1.2.1) oluşmalıdır. Aşağıdaki bayraklar bir yol gradyan fırçası için ilgilidir:

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Alır veya ayarlar 32 bit işaretsiz tamsayı, OptionalData alanındaki veriyi belirten. Bu değer BrushData bayraklarından (bölüm 2.1.2.1) oluşmalıdır. Aşağıdaki bayraklar bir yol gradyan fırçası için ilgilidir:

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Alır veya ayarlar WrapMode numaralandırmasından (bölüm 2.1.1.34) 32 bit işaretli tamsayı, fırçanın sınırının dışındaki alanın boyanıp boyanmayacağını belirten. Sınırın dışı boyandığında, sarma modu renk gradyanının nasıl tekrarlandığını belirler.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Alır veya ayarlar WrapMode numaralandırmasından (bölüm 2.1.1.34) 32 bit işaretli tamsayı, fırçanın sınırının dışındaki alanın boyanıp boyanmayacağını belirten. Sınırın dışı boyandığında, sarma modu renk gradyanının nasıl tekrarlandığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


Alır veya ayarlar EmfPlusARGB nesnesi (bölüm 2.2.2.1) yol gradyan fırçasının merkez rengini belirten, fırçanın merkez noktasında görülen renk. Fırçanın rengi, sınır renginden merkez rengine doğru, sınırdan merkez noktasına ilerledikçe kademeli olarak değişir.

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


Alır veya ayarlar EmfPlusARGB nesnesi (bölüm 2.2.2.1) yol gradyan fırçasının merkez rengini belirten, fırçanın merkez noktasında görülen renk. Fırçanın rengi, sınır renginden merkez rengine doğru, sınırdan merkez noktasına ilerledikçe kademeli olarak değişir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


Alır veya ayarlar EmfPlusARGB nesnesi (bölüm 2.2.2.1) yol gradyan fırçasının merkez rengini belirten, fırçanın merkez noktasında görülen renk. Fırçanın rengi, sınır renginden merkez rengine doğru, sınırdan merkez noktasına ilerledikçe kademeli olarak değişir.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


Alır veya ayarlar EmfPlusARGB nesnesi (bölüm 2.2.2.1) yol gradyan fırçasının merkez rengini belirten, fırçanın merkez noktasında görülen renk. Fırçanın rengi, sınır renginden merkez rengine doğru, sınırdan merkez noktasına ilerledikçe kademeli olarak değişir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


Alır veya ayarlar SurroundingColorCount EmfPlusARGB nesnelerinin dizisini, fırçanın sınırındaki ayrı noktalar için renkleri belirten.

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


Alır veya ayarlar SurroundingColorCount EmfPlusARGB nesnelerinin dizisini, fırçanın sınırındaki ayrı noktalar için renkleri belirten.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


Alır veya ayarlar yol gradyan fırçasının sınırını, bu sınırın bir yol veya kapalı kardinal spline ile belirtildiği. Eğer BrushDataFlags alanında BrushDataPath bayrağı ayarlıysa, bu alan EmfPlusBoundaryPathData nesnesi (bölüm 2.2.2.6) içermelidir; aksi takdirde bu alan EmfPlusBoundaryPointData nesnesi (bölüm 2.2.2.7) içermelidir.

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


Alır veya ayarlar yol gradyan fırçasının sınırını, bu sınırın bir yol veya kapalı kardinal spline ile belirtildiği. Eğer BrushDataFlags alanında BrushDataPath bayrağı ayarlıysa, bu alan EmfPlusBoundaryPathData nesnesi (bölüm 2.2.2.6) içermelidir; aksi takdirde bu alan EmfPlusBoundaryPointData nesnesi (bölüm 2.2.2.7) içermelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


Alır veya ayarlar isteğe bağlı EmfPlusPathGradientBrushOptionalData nesnesi (bölüm 2.2.2.30), yol gradyan fırçası için ek verileri belirten. Bu alanın belirli içeriği BrushDataFlags alanının değerine göre belirlenir.

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


Alır veya ayarlar isteğe bağlı EmfPlusPathGradientBrushOptionalData nesnesi (bölüm 2.2.2.30), yol gradyan fırçası için ek verileri belirten. Bu alanın belirli içeriği BrushDataFlags alanının değerine göre belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

