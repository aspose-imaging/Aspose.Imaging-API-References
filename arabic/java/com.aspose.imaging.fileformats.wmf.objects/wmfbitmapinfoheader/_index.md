---
title: "WmfBitmapInfoHeader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن BitmapInfoHeader يحتوي على معلومات حول الأبعاد وتنسيق اللون لملف bitmap مستقل عن الجهاز DIB."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
```
public class WmfBitmapInfoHeader extends WmfBitmapBaseHeader
```

كائن BitmapInfoHeader يحتوي على معلومات حول الأبعاد وتنسيق اللون لصورة نقطية مستقلة عن الجهاز (DIB).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [STRUCTURE_SIZE](#STRUCTURE-SIZE) | حجم الهيكل |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد عرض DIB بالبكسل. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد عرض DIB بالبكسل. |
| [getHeight()](#getHeight--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد ارتفاع DIB بالبكسل. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد ارتفاع DIB بالبكسل. |
| [getCompression()](#getCompression--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد وضع الضغط لـ DIB. |
| [setCompression(int value)](#setCompression-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد وضع الضغط لـ DIB. |
| [getImageSize()](#getImageSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم الصورة بالبايت. |
| [setImageSize(int value)](#setImageSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم الصورة بالبايت. |
| [getXPelsPerMeter()](#getXPelsPerMeter--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الدقة الأفقية، بوحدات بكسل لكل متر، للجهاز الهدف لـ DIB |
| [setXPelsPerMeter(int value)](#setXPelsPerMeter-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الدقة الأفقية، بوحدات بكسل لكل متر، للجهاز الهدف لـ DIB |
| [getYPelsPerMeter()](#getYPelsPerMeter--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الدقة العمودية، بوحدات بكسل لكل متر، للجهاز الهدف لـ DIB |
| [setYPelsPerMeter(int value)](#setYPelsPerMeter-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الدقة العمودية، بوحدات بكسل لكل متر، للجهاز الهدف لـ DIB |
| [getColorUsed()](#getColorUsed--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الفهارس في جدول الألوان المستخدم بواسطة DIB، كما يلي: إذا كانت هذه القيمة صفرًا، يستخدم DIB الحد الأقصى لعدد الألوان التي تتطابق مع قيمة BitCount. |
| [setColorUsed(int value)](#setColorUsed-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الفهارس في جدول الألوان المستخدم بواسطة DIB، كما يلي: إذا كانت هذه القيمة صفرًا، يستخدم DIB الحد الأقصى لعدد الألوان التي تتطابق مع قيمة BitCount. |
| [getColorImportant()](#getColorImportant--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد فهارس الألوان المطلوبة لعرض DIB. |
| [setColorImportant(int value)](#setColorImportant-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد فهارس الألوان المطلوبة لعرض DIB. |
### WmfBitmapInfoHeader() {#WmfBitmapInfoHeader--}
```
public WmfBitmapInfoHeader()
```


### STRUCTURE_SIZE {#STRUCTURE-SIZE}
```
public static final int STRUCTURE_SIZE
```


حجم الهيكل

### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد عرض DIB بالبكسل. يجب أن تكون هذه القيمة موجبة. يجب أن يحدد هذا الحقل عرض ملف الصورة غير المضغوطة إذا كانت قيمة Compression تحدد تنسيق JPEG أو PNG.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد عرض DIB بالبكسل. يجب أن تكون هذه القيمة موجبة. يجب أن يحدد هذا الحقل عرض ملف الصورة غير المضغوطة إذا كانت قيمة Compression تحدد تنسيق JPEG أو PNG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد ارتفاع DIB بالبكسل. يجب ألا تكون هذه القيمة صفرًا. إذا كانت هذه القيمة موجبة، يكون DIB صورة bitmap من الأسفل إلى الأعلى، وأصلها هو الزاوية السفلية اليسرى. إذا كانت هذه القيمة سالبة، يكون DIB صورة bitmap من الأعلى إلى الأسفل، وأصلها هو الزاوية العلوية اليسرى. لا تدعم صور bitmap من الأعلى إلى الأسفل الضغط. يجب أن يحدد هذا الحقل ارتفاع ملف الصورة غير المضغوطة إذا كانت قيمة Compression تحدد تنسيق JPEG أو PNG.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد ارتفاع DIB بالبكسل. يجب ألا تكون هذه القيمة صفرًا. إذا كانت هذه القيمة موجبة، يكون DIB صورة bitmap من الأسفل إلى الأعلى، وأصلها هو الزاوية السفلية اليسرى. إذا كانت هذه القيمة سالبة، يكون DIB صورة bitmap من الأعلى إلى الأسفل، وأصلها هو الزاوية العلوية اليسرى. لا تدعم صور bitmap من الأعلى إلى الأسفل الضغط. يجب أن يحدد هذا الحقل ارتفاع ملف الصورة غير المضغوطة إذا كانت قيمة Compression تحدد تنسيق JPEG أو PNG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد وضع الضغط لـ DIB. يجب أن تكون هذه القيمة ضمن تعداد Compression (القسم 2.1.1.7). يجب ألا تحدد هذه القيمة تنسيقًا مضغوطًا إذا كان DIB صورة bitmap من الأعلى إلى الأسفل، كما هو موضح بقيمة Height.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد وضع الضغط لـ DIB. يجب أن تكون هذه القيمة ضمن تعداد Compression (القسم 2.1.1.7). يجب ألا تحدد هذه القيمة تنسيقًا مضغوطًا إذا كان DIB صورة bitmap من الأعلى إلى الأسفل، كما هو موضح بقيمة Height.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getImageSize() {#getImageSize--}
```
public int getImageSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم الصورة بالبايت. إذا كانت قيمة Compression هي BI\_RGB، يجب أن تكون هذه القيمة صفرًا ويجب تجاهلها. إذا كانت قيمة Compression هي BI\_JPEG أو BI\_PNG، يجب أن تحدد هذه القيمة حجم مخزن صورة JPEG أو PNG على التوالي.

**Returns:**
int
### setImageSize(int value) {#setImageSize-int-}
```
public void setImageSize(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم الصورة بالبايت. إذا كانت قيمة Compression هي BI\_RGB، يجب أن تكون هذه القيمة صفرًا ويجب تجاهلها. إذا كانت قيمة Compression هي BI\_JPEG أو BI\_PNG، يجب أن تحدد هذه القيمة حجم مخزن صورة JPEG أو PNG على التوالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getXPelsPerMeter() {#getXPelsPerMeter--}
```
public int getXPelsPerMeter()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الدقة الأفقية، بوحدات بكسل لكل متر، للجهاز الهدف لـ DIB

**Returns:**
int
### setXPelsPerMeter(int value) {#setXPelsPerMeter-int-}
```
public void setXPelsPerMeter(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الدقة الأفقية، بوحدات بكسل لكل متر، للجهاز الهدف لـ DIB

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getYPelsPerMeter() {#getYPelsPerMeter--}
```
public int getYPelsPerMeter()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الدقة العمودية، بوحدات بكسل لكل متر، للجهاز الهدف لـ DIB

**Returns:**
int
### setYPelsPerMeter(int value) {#setYPelsPerMeter-int-}
```
public void setYPelsPerMeter(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد الدقة العمودية، بوحدات بكسل لكل متر، للجهاز الهدف لـ DIB

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColorUsed() {#getColorUsed--}
```
public int getColorUsed()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الفهارس في جدول الألوان المستخدم بواسطة DIB، كما يلي: إذا كانت هذه القيمة صفرًا، يستخدم DIB الحد الأقصى لعدد الألوان التي تتطابق مع قيمة BitCount. إذا كانت هذه القيمة غير صفرية وكانت قيمة BitCount أقل من 16، تحدد هذه القيمة عدد الألوان المستخدمة بواسطة DIB. إذا كانت هذه القيمة غير صفرية وكانت قيمة BitCount 16 أو أكثر، تحدد هذه القيمة حجم جدول الألوان المستخدم لتحسين أداء لوحة النظام. ملاحظة: إذا كانت هذه القيمة غير صفرية وأكبر من الحد الأقصى الممكن لحجم جدول الألوان بناءً على قيمة BitCount، يجب افتراض الحد الأقصى لحجم جدول الألوان.

**Returns:**
int
### setColorUsed(int value) {#setColorUsed-int-}
```
public void setColorUsed(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد الفهارس في جدول الألوان المستخدم بواسطة DIB، كما يلي: إذا كانت هذه القيمة صفرًا، يستخدم DIB الحد الأقصى لعدد الألوان التي تتطابق مع قيمة BitCount. إذا كانت هذه القيمة غير صفرية وكانت قيمة BitCount أقل من 16، تحدد هذه القيمة عدد الألوان المستخدمة بواسطة DIB. إذا كانت هذه القيمة غير صفرية وكانت قيمة BitCount 16 أو أكثر، تحدد هذه القيمة حجم جدول الألوان المستخدم لتحسين أداء لوحة النظام. ملاحظة: إذا كانت هذه القيمة غير صفرية وأكبر من الحد الأقصى الممكن لحجم جدول الألوان بناءً على قيمة BitCount، يجب افتراض الحد الأقصى لحجم جدول الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColorImportant() {#getColorImportant--}
```
public int getColorImportant()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد فهارس الألوان المطلوبة لعرض DIB. إذا كانت هذه القيمة صفرًا، تكون جميع فهارس الألوان مطلوبة.

**Returns:**
int
### setColorImportant(int value) {#setColorImportant-int-}
```
public void setColorImportant(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد عدد فهارس الألوان المطلوبة لعرض DIB. إذا كانت هذه القيمة صفرًا، تكون جميع فهارس الألوان مطلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

