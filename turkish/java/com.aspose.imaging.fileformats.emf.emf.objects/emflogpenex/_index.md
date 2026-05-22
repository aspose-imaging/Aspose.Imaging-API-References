---
title: "EmfLogPenEx"
second_title: "Aspose.Imaging for Java API Referansı"
description: "LogPenEx nesnesi, genişletilmiş mantıksal bir kalemin stil genişliğini ve rengini belirtir."
type: docs
weight: 28
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPenEx extends EmfBasePen
```

LogPenEx nesnesi, genişletilmiş mantıksal bir kalemin stilini, genişliğini ve rengini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Kalem stilini alır veya ayarlar |
| [setPenStyle(int value)](#setPenStyle-int-) | Kalem stilini alır veya ayarlar |
| [getWidth()](#getWidth--) | Kalemle çizilen çizginin genişliğini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setWidth(int value)](#setWidth-int-) | Kalemle çizilen çizginin genişliğini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getBrushStyle()](#getBrushStyle--) | WMF BrushStyle enumerasyonundan ([MS-WMF] bölüm 2.1.1.4) kalem için bir fırça stilini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | WMF BrushStyle enumerasyonundan ([MS-WMF] bölüm 2.1.1.4) kalem için bir fırça stilini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | [MS-WMF] bölüm 2.2.2.8'de tanımlı bir WMF ColorRef nesnesini alır veya ayarlar. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | [MS-WMF] bölüm 2.2.2.8'de tanımlı bir WMF ColorRef nesnesini alır veya ayarlar. |
| [getBrushHatch()](#getBrushHatch--) | Fırça tarama desenini alır veya ayarlar. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Fırça tarama desenini alır veya ayarlar. |
| [getNumStyleEntities()](#getNumStyleEntities--) | StyleEntry alanında belirtilen dizideki öğe sayısını alır. |
| [getStyleEntry()](#getStyleEntry--) | PenStyle değeri PS\_USERSTYLE olduğunda, bu kalemle çizilen çizgideki tire ve boşluk uzunluklarını tanımlayan isteğe bağlı 32 bit işaretsiz tam sayı dizisini alır veya ayarlar. |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | PenStyle değeri PS\_USERSTYLE olduğunda, bu kalemle çizilen çizgideki tire ve boşluk uzunluklarını tanımlayan isteğe bağlı 32 bit işaretsiz tam sayı dizisini alır veya ayarlar. |
| [getBrushDibPattern()](#getBrushDibPattern--) | Fırça dib desenini alır veya ayarlar. |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Fırça dib desenini alır veya ayarlar. |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Kalem stilini alır veya ayarlar

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Kalem stilini alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Kalemle çizilen çizginin genişliğini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. PenStyle alanındaki kalem türü PS\_GEOMETRIC ise, bu değer mantıksal birimlerdeki genişliktir; aksi takdirde genişlik cihaz birimlerinde belirtilir. PenStyle alanındaki kalem türü PS\_COSMETIC ise, bu değer 0x00000001 olmalıdır.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Kalemle çizilen çizginin genişliğini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. PenStyle alanındaki kalem türü PS\_GEOMETRIC ise, bu değer mantıksal birimlerdeki genişliktir; aksi takdirde genişlik cihaz birimlerinde belirtilir. PenStyle alanındaki kalem türü PS\_COSMETIC ise, bu değer 0x00000001 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


WMF BrushStyle enumerasyonundan ([MS-WMF] bölüm 2.1.1.4) kalem için bir fırça stilini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. PenStyle alanındaki kalem türü PS\_GEOMETRIC ise, bu değer BS\_SOLID ya da BS\_HATCHED olmalıdır. Bu alanın değeri BS\_NULL olabilir, ancak yalnızca PenStyle'da belirtilen çizgi stili PS\_NULL ise. BS\_NULL stili, etkisi olmayan bir fırça belirtmek için KULLANILMALIdır.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


WMF BrushStyle enumerasyonundan ([MS-WMF] bölüm 2.1.1.4) kalem için bir fırça stilini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. PenStyle alanındaki kalem türü PS\_GEOMETRIC ise, bu değer BS\_SOLID ya da BS\_HATCHED olmalıdır. Bu alanın değeri BS\_NULL olabilir, ancak yalnızca PenStyle'da belirtilen çizgi stili PS\_NULL ise. BS\_NULL stili, etkisi olmayan bir fırça belirtmek için KULLANILMALIdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


[MS-WMF] bölüm 2.2.2.8'de tanımlı bir WMF ColorRef nesnesini alır veya ayarlar. Bu alanın yorumu, bu bölümdeki tabloda gösterildiği gibi BrushStyle değerine bağlıdır.

Değer: 32 bit ARGB renk

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


[MS-WMF] bölüm 2.2.2.8'de tanımlı bir WMF ColorRef nesnesini alır veya ayarlar. Bu alanın yorumu, bu bölümdeki tabloda gösterildiği gibi BrushStyle değerine bağlıdır.

Değer: 32 bit ARGB renk

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Fırça tarama desenini alır veya ayarlar. Bu alanın tanımı, bu bölümdeki tabloda gösterildiği gibi BrushStyle değerine bağlıdır.

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Fırça tarama desenini alır veya ayarlar. Bu alanın tanımı, bu bölümdeki tabloda gösterildiği gibi BrushStyle değerine bağlıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


StyleEntry alanında belirtilen dizideki öğe sayısını alır. PenStyle PS\_USERSTYLE belirtmiyorsa bu değer sıfır OLmalıdır.

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


PenStyle değeri PS\_USERSTYLE olduğunda, bu kalemle çizilen çizgideki tire ve boşluk uzunluklarını tanımlayan isteğe bağlı 32 bit işaretsiz tam sayı dizisini alır veya ayarlar. Dizi, NumStyleEntries tarafından belirtilen sayıda girdi içerir, ancak sanki sonsuz tekrar ediyormuş gibi kullanılır. Dizideki ilk girdi ilk tire uzunluğunu, ikinci girdi ise ilk boşluk uzunluğunu belirtir. Bundan sonra tire ve boşluk uzunlukları dönüşümlü olarak devam eder. PenStyle alanındaki kalem türü PS\_GEOMETRIC ise, uzunluklar mantıksal birimlerde; aksi takdirde cihaz birimlerinde belirtilir.

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


PenStyle değeri PS\_USERSTYLE olduğunda, bu kalemle çizilen çizgideki tire ve boşluk uzunluklarını tanımlayan isteğe bağlı 32 bit işaretsiz tam sayı dizisini alır veya ayarlar. Dizi, NumStyleEntries tarafından belirtilen sayıda girdi içerir, ancak sanki sonsuz tekrar ediyormuş gibi kullanılır. Dizideki ilk girdi ilk tire uzunluğunu, ikinci girdi ise ilk boşluk uzunluğunu belirtir. Bundan sonra tire ve boşluk uzunlukları dönüşümlü olarak devam eder. PenStyle alanındaki kalem türü PS\_GEOMETRIC ise, uzunluklar mantıksal birimlerde; aksi takdirde cihaz birimlerinde belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


Fırça dib desenini alır veya ayarlar.

Değer: Fırça dib deseni.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


Fırça dib desenini alır veya ayarlar.

Değer: Fırça dib deseni.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

