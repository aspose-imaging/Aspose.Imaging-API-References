---
title: "EmfPlgBlt"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_PLGBLT يحدد نقلًا كتليًا للبكسلات من صورة مصدر إلى متوازي أضلاع الوجهة مع تطبيق صورة قناع لوني."
type: docs
weight: 84
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfPlgBlt extends EmfBitmapRecordType
```

سجل EMR\_PLGBLT يحدد نقل كتلة من البكسلات من صورة مصدر إلى متوازي أضلاع هدف، مع تطبيق صورة قناع لوني.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlgBlt(EmfRecord source)](#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا للفئة `EmfPlgBlt`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدّي، بوحدات الجهاز، للإخراج إلى الوجهة. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدّي، بوحدات الجهاز، للإخراج إلى الوجهة. |
| [getAptlDest()](#getAptlDest--) | يحصل أو يعيّن مصفوفة من ثلاثة كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد ثلاثة زوايا لمنطقة الوجهة على شكل متوازي أضلاع للنقل الكتلي. |
| [setAptlDest(Point[] value)](#setAptlDest-com.aspose.imaging.Point---) | يحصل أو يعيّن مصفوفة من ثلاثة كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد ثلاثة زوايا لمنطقة الوجهة على شكل متوازي أضلاع للنقل الكتلي. |
| [getXSrc()](#getXSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setXSrc(int value)](#setXSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getYSrc()](#getYSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setYSrc(int value)](#setYSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getCxSrc()](#getCxSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر. |
| [setCxSrc(int value)](#setCxSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر. |
| [getCySrc()](#getCySrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [setCySrc(int value)](#setCySrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [getXFormSrc()](#getXFormSrc--) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [setXFormSrc(Matrix value)](#setXFormSrc-com.aspose.imaging.Matrix-) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية لصورة المصدر. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية لصورة المصدر. |
| [getUsageSrc()](#getUsageSrc--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [getXMask()](#getXMask--) | الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى لصورة القناع النقطية. |
| [setXMask(int value)](#setXMask-int-) | الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى لصورة القناع النقطية. |
| [getYMask()](#getYMask--) | الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى لصورة القناع النقطية. |
| [setYMask(int value)](#setYMask-int-) | الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى لصورة القناع النقطية. |
| [getUsageMask()](#getUsageMask--) | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع النقطية. |
| [setUsageMask(int value)](#setUsageMask-int-) | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع النقطية. |
| [getSourceBitmap()](#getSourceBitmap--) | يحصل أو يعيّن مخزنًا يحتوي على صورة المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا يحتوي على صورة المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. |
| [getMaskBitmap()](#getMaskBitmap--) | يحصل أو يعيّن مخزنًا يحتوي على صورة القناع، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا يحتوي على صورة القناع، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. |
### EmfPlgBlt(EmfRecord source) {#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPlgBlt(EmfRecord source)
```


يُنشئ مثيلًا جديدًا للفئة `EmfPlgBlt`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدّي، بوحدات الجهاز، للإخراج إلى الوجهة.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدّي، بوحدات الجهاز، للإخراج إلى الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAptlDest() {#getAptlDest--}
```
public Point[] getAptlDest()
```


يحصل أو يعيّن مصفوفة من ثلاثة كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد ثلاثة زوايا لمنطقة الوجهة على شكل متوازي أضلاع للنقل الكتلي. الزاوية العليا اليسرى للمستطيل المصدر تُطابق النقطة الأولى في هذه المصفوفة، والزاوية العليا اليمنى تُطابق النقطة الثانية، والزاوية السفلى اليسرى تُطابق النقطة الثالثة. الزاوية السفلى اليمنى للمستطيل المصدر تُطابق النقطة الرابعة الضمنية في المتوازي أضلاع، والتي تُحسب من الثلاث نقاط الأولى (A, B, C) باعتبارها متجهات. D = B + C A

**Returns:**
com.aspose.imaging.Point[]
### setAptlDest(Point[] value) {#setAptlDest-com.aspose.imaging.Point---}
```
public void setAptlDest(Point[] value)
```


يحصل أو يعيّن مصفوفة من ثلاثة كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد ثلاثة زوايا لمنطقة الوجهة على شكل متوازي أضلاع للنقل الكتلي. الزاوية العليا اليسرى للمستطيل المصدر تُطابق النقطة الأولى في هذه المصفوفة، والزاوية العليا اليمنى تُطابق النقطة الثانية، والزاوية السفلى اليسرى تُطابق النقطة الثالثة. الزاوية السفلى اليمنى للمستطيل المصدر تُطابق النقطة الرابعة الضمنية في المتوازي أضلاع، والتي تُحسب من الثلاث نقاط الأولى (A, B, C) باعتبارها متجهات. D = B + C A

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getXFormSrc() {#getXFormSrc--}
```
public Matrix getXFormSrc()
```


يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setXFormSrc(Matrix value) {#setXFormSrc-com.aspose.imaging.Matrix-}
```
public void setXFormSrc(Matrix value)
```


يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBkSrcArgb32Color() {#getBkSrcArgb32Color--}
```
public int getBkSrcArgb32Color()
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية لصورة المصدر.

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية لصورة المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية تفسير القيم في جدول الألوان في رأس صورة المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors.

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية تفسير القيم في جدول الألوان في رأس صورة المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getXMask() {#getXMask--}
```
public int getXMask()
```


الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى لصورة القناع النقطية.

**Returns:**
int
### setXMask(int value) {#setXMask-int-}
```
public void setXMask(int value)
```


الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى لصورة القناع النقطية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getYMask() {#getYMask--}
```
public int getYMask()
```


الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى لصورة القناع النقطية.

**Returns:**
int
### setYMask(int value) {#setYMask-int-}
```
public void setYMask(int value)
```


الحصول أو تعيين عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى لصورة القناع النقطية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getUsageMask() {#getUsageMask--}
```
public int getUsageMask()
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع النقطية. يجب أن تكون هذه القيمة ضمن تعداد DIBColors.

**Returns:**
int
### setUsageMask(int value) {#setUsageMask-int-}
```
public void setUsageMask(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع النقطية. يجب أن تكون هذه القيمة ضمن تعداد DIBColors.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


يحصل أو يعيّن مخزنًا يحتوي على صورة المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تم تسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا يحتوي على صورة المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تم تسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


يحصل أو يعيّن مخزنًا يحتوي على صورة القناع، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تم تسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا يحتوي على صورة القناع، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تم تسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

