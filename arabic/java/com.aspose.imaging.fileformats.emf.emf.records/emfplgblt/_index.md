---
title: "EmfPlgBlt"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_PLGBLT يحدد نقل كتلة من البكسلات من صورة مصدر إلى متوازي أضلاع هدف مع تطبيق صورة قناع لوني."
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
| [EmfPlgBlt(EmfRecord source)](#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfPlgBlt`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز للإخراج إلى الوجهة. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز للإخراج إلى الوجهة. |
| [getAptlDest()](#getAptlDest--) | يحصل أو يعيّن مصفوفة من ثلاث كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد ثلاثة زوايا لمنطقة وجهة متوازي أضلاع لعملية النقل الكتلي. |
| [setAptlDest(Point[] value)](#setAptlDest-com.aspose.imaging.Point---) | يحصل أو يعيّن مصفوفة من ثلاث كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد ثلاثة زوايا لمنطقة وجهة متوازي أضلاع لعملية النقل الكتلي. |
| [getXSrc()](#getXSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setXSrc(int value)](#setXSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي x المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getYSrc()](#getYSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [setYSrc(int value)](#setYSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الإحداثي y المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [getCxSrc()](#getCxSrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل المصدر. |
| [setCxSrc(int value)](#setCxSrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل المصدر. |
| [getCySrc()](#getCySrc--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [setCySrc(int value)](#setCySrc-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [getXFormSrc()](#getXFormSrc--) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [setXFormSrc(Matrix value)](#setXFormSrc-com.aspose.imaging.Matrix-) | يحصل أو يعيّن كائن XForm (القسم 2.2.28) الذي يحدد تحويلًا من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [getBkSrcArgb32Color()](#getBkSrcArgb32Color--) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية صورة البت المصدر. |
| [setBkSrcArgb32Color(int value)](#setBkSrcArgb32Color-int-) | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية صورة البت المصدر. |
| [getUsageSrc()](#getUsageSrc--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بتًا يحدد طريقة تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. |
| [getXMask()](#getXMask--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى لصورة القناع. |
| [setXMask(int value)](#setXMask-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي x المنطقي للزاوية العلوية اليسرى لصورة القناع. |
| [getYMask()](#getYMask--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى لصورة القناع. |
| [setYMask(int value)](#setYMask-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الإحداثي y المنطقي للزاوية العلوية اليسرى لصورة القناع. |
| [getUsageMask()](#getUsageMask--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع. |
| [setUsageMask(int value)](#setUsageMask-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع. |
| [getSourceBitmap()](#getSourceBitmap--) | يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. |
| [getMaskBitmap()](#getMaskBitmap--) | يحصل أو يعيّن مخزنًا يحتوي على صورة البت القناع، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. |
| [setMaskBitmap(WmfDeviceIndependentBitmap value)](#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا يحتوي على صورة البت القناع، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. |
### EmfPlgBlt(EmfRecord source) {#EmfPlgBlt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPlgBlt(EmfRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfPlgBlt`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز للإخراج إلى الوجهة.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز للإخراج إلى الوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAptlDest() {#getAptlDest--}
```
public Point[] getAptlDest()
```


يحصل أو يعيّن مصفوفة من ثلاث كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد ثلاثة زوايا لمنطقة وجهة متوازي أضلاع لعملية النقل الكتلي. يتم ربط الزاوية العليا اليسرى للمستطيل المصدر بالنقطة الأولى في هذه المصفوفة، والزاوية العليا اليمنى بالنقطة الثانية، والزاوية السفلى اليسرى بالنقطة الثالثة. يتم ربط الزاوية السفلى اليمنى للمستطيل المصدر بالنقطة الرابعة الضمنية في متوازي الأضلاع، والتي تُحسب من الثلاث نقاط الأولى (A, B, و C) باعتبارها متجهات. D = B + C A

**Returns:**
com.aspose.imaging.Point[]
### setAptlDest(Point[] value) {#setAptlDest-com.aspose.imaging.Point---}
```
public void setAptlDest(Point[] value)
```


يحصل أو يعيّن مصفوفة من ثلاث كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد ثلاثة زوايا لمنطقة وجهة متوازي أضلاع لعملية النقل الكتلي. يتم ربط الزاوية العليا اليسرى للمستطيل المصدر بالنقطة الأولى في هذه المصفوفة، والزاوية العليا اليمنى بالنقطة الثانية، والزاوية السفلى اليسرى بالنقطة الثالثة. يتم ربط الزاوية السفلى اليمنى للمستطيل المصدر بالنقطة الرابعة الضمنية في متوازي الأضلاع، والتي تُحسب من الثلاث نقاط الأولى (A, B, و C) باعتبارها متجهات. D = B + C A

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

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

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل المصدر.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد العرض المنطقي للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل المصدر.

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بتًا يحدد الارتفاع المنطقي للمستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية صورة البت المصدر.

**Returns:**
int
### setBkSrcArgb32Color(int value) {#setBkSrcArgb32Color-int-}
```
public void setBkSrcArgb32Color(int value)
```


يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية صورة البت المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية تفسير القيم في جدول الألوان في رأس صورة البت المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors.

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية تفسير القيم في جدول الألوان في رأس صورة البت المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors.

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


يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل التسمية \"UndefinedSpace\" هي اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل التسمية \"UndefinedSpace\" هي اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

### getMaskBitmap() {#getMaskBitmap--}
```
public WmfDeviceIndependentBitmap getMaskBitmap()
```


يحصل أو يعيّن مخزنًا يحتوي على صورة البت القناع، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل التسمية \"UndefinedSpace\" هي اختيارية ويجب تجاهلها.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setMaskBitmap(WmfDeviceIndependentBitmap value) {#setMaskBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setMaskBitmap(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا يحتوي على صورة البت القناع، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR\_PLGBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل التسمية \"UndefinedSpace\" هي اختيارية ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

