---
title: "EmfMaskBlt"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_MASKBLT يحدد نقل كتلة من البكسلات من صورة مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة وتطبيق صورة قناع لوني وفق عمليات الراستر المحددة للواجهة والخلفية."
type: docs
weight: 69
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfMaskBlt extends EmfBitmapRecordType
```

السجل EMR\_MASKBLT يحدد نقلًا كتلًا من البكسلات من صورة مصدر إلى مستطيل وجهة، ويمكن دمجه اختياريًا مع نمط فرشاة وتطبيق صورة قناع لوني، وفقًا لعمليات نقطية أمامية وخلفية محددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfMaskBlt(EmfRecord source)](#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfMaskBlt`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز. |
| [getXDest()](#getXDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [setXDest(int value)](#setXDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [getYDest()](#getYDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [setYDest(int value)](#setYDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [getCxDest()](#getCxDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل الوجهة. |
| [setCxDest(int value)](#setCxDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل الوجهة. |
| [getCyDest()](#getCyDest--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| [setCyDest(int value)](#setCyDest-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| [getRop4()](#getRop4--) | يحصل أو يعيّن عملية راستر رباعية، والتي تحدد عمليات راستر ثلاثية لألوان الواجهة والخلفية لصورة bitmap. |
| [setRop4(EmfRop4 value)](#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-) | يحصل أو يعيّن عملية راستر رباعية، والتي تحدد عمليات راستر ثلاثية لألوان الواجهة والخلفية لصورة bitmap. |
| [getXSrc()](#getXSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setXSrc(int value)](#setXSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getYSrc()](#getYSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setYSrc(int value)](#setYSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getXformSrc()](#getXformSrc--) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [setXformSrc(Matrix value)](#setXformSrc-com.aspose.imaging.Matrix-) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [getArgb32BkColorSrc()](#getArgb32BkColorSrc--) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية الصورة النقطية المصدر. |
| [setArgb32BkColorSrc(int value)](#setArgb32BkColorSrc-int-) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية الصورة النقطية المصدر. |
| [getUsageSrc()](#getUsageSrc--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [getXMask()](#getXMask--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى لصورة القناع. |
| [setXMask(int value)](#setXMask-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى لصورة القناع. |
| [getYMask()](#getYMask--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى لصورة القناع. |
| [setYMask(int value)](#setYMask-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى لصورة القناع. |
| [getUsageMask()](#getUsageMask--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع. |
| [setUsageMask(int value)](#setUsageMask-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع. |
| [getSourceBitmap()](#getSourceBitmap--) | يحصل أو يعيّن مخزنًا يحتوي على صور المصدر، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_MASKBLT أو مع بعضها البعض. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا يحتوي على صور المصدر، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_MASKBLT أو مع بعضها البعض. |
| [getMaskBitmap()](#getMaskBitmap--) | يحصل أو يعيّن مخزنًا يحتوي على صور القناع، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_MASKBLT أو مع بعضها البعض. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا يحتوي على صور القناع، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_MASKBLT أو مع بعضها البعض. |
### EmfMaskBlt(EmfRecord source) {#EmfMaskBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMaskBlt(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfMaskBlt`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل الحدود الوجهة بوحدات الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCxDest() {#getCxDest--}
```
public int getCxDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل الوجهة.

**Returns:**
int
### setCxDest(int value) {#setCxDest-int-}
```
public void setCxDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCyDest() {#getCyDest--}
```
public int getCyDest()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل الوجهة.

**Returns:**
int
### setCyDest(int value) {#setCyDest-int-}
```
public void setCyDest(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRop4() {#getRop4--}
```
public EmfRop4 getRop4()
```


يحصل أو يعيّن عملية راستر رباعية، والتي تحدد عمليات راستر ثلاثية لألوان الواجهة والخلفية لصورة bitmap. هذه القيم تحدد كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الهدف.

**Returns:**
[EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4)
### setRop4(EmfRop4 value) {#setRop4-com.aspose.imaging.fileformats.emf.emf.records.EmfRop4-}
```
public void setRop4(EmfRop4 value)
```


يحصل أو يعيّن عملية راستر رباعية، والتي تحدد عمليات راستر ثلاثية لألوان الواجهة والخلفية لصورة bitmap. هذه القيم تحدد كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الهدف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfRop4](../../com.aspose.imaging.fileformats.emf.emf.records/emfrop4) |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getXformSrc() {#getXformSrc--}
```
public Matrix getXformSrc()
```


يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXformSrc(Matrix value) {#setXformSrc-com.aspose.imaging.Matrix-}
```
public void setXformSrc(Matrix value)
```


يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getArgb32BkColorSrc() {#getArgb32BkColorSrc--}
```
public int getArgb32BkColorSrc()
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية الصورة النقطية المصدر.

**Returns:**
int
### setArgb32BkColorSrc(int value) {#setArgb32BkColorSrc-int-}
```
public void setArgb32BkColorSrc(int value)
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية الصورة النقطية المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getXMask() {#getXMask--}
```
public int getXMask()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى لصورة القناع.

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى لصورة القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى لصورة القناع.

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى لصورة القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع. يجب أن تكون هذه القيمة ضمن تعداد DIBColors.

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع. يجب أن تكون هذه القيمة ضمن تعداد DIBColors.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


يحصل أو يعيّن مخزنًا يحتوي على صور المصدر، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_MASKBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل التسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا يحتوي على صور المصدر، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_MASKBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل التسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


يحصل أو يعيّن مخزنًا يحتوي على صور القناع، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_MASKBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل التسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا يحتوي على صور القناع، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR\_MASKBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل التسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

