---
title: "WmfDibCreatePatternBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل META_DIBCREATEPATTERNBRUSH ينشئ قسم كائن فرشاة 2.2.1.1 مع نمط محدد بواسطة كائن DeviceIndependentBitmap DIB القسم 2.2.2.9."
type: docs
weight: 29
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging/fileformats/wmf.objects/wmfgraphicobject)
```
public class WmfDibCreatePatternBrush extends WmfGraphicObject
```

سجل META\_DIBCREATEPATTERNBRUSH ينشئ كائن فرشاة (القسم 2.2.1.1) بنمط محدد بواسطة كائن DeviceIndependentBitmap (DIB) (القسم 2.2.9).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfDibCreatePatternBrush()](#WmfDibCreatePatternBrush--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStyle()](#getStyle--) | يحصل أو يضبط النمط. |
| [setStyle(int value)](#setStyle-int-) | يحصل أو يضبط النمط. |
| [getColorUsage()](#getColorUsage--) | الحصول أو تعيين استخدام اللون. |
| [setColorUsage(int value)](#setColorUsage-int-) | الحصول أو تعيين استخدام اللون. |
| [getSourceBitmap()](#getSourceBitmap--) | الحصول أو تعيين صورة البت المصدر. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | الحصول أو تعيين صورة البت المصدر. |
### WmfDibCreatePatternBrush() {#WmfDibCreatePatternBrush--}
```
public WmfDibCreatePatternBrush()
```


### getStyle() {#getStyle--}
```
public int getStyle()
```


يحصل أو يضبط النمط.

القيمة: القيم القانونية لهذا الحقل معرفة كما يلي: إذا لم تكن القيمة BS\_PATTERN، يجب افتراض BS\_DIBPATTERNPT. هذه القيم محددة في تعداد BrushStyle (القسم 2.1.1.4).

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


يحصل أو يضبط النمط.

القيمة: القيم القانونية لهذا الحقل معرفة كما يلي: إذا لم تكن القيمة BS\_PATTERN، يجب افتراض BS\_DIBPATTERNPT. هذه القيم محددة في تعداد BrushStyle (القسم 2.1.1.4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


الحصول أو تعيين استخدام اللون.

القيمة: حقل Colors في كائن DIB يحتوي على قيم RGB صريحة، أو فهارس إلى لوحة ألوان.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


الحصول أو تعيين استخدام اللون.

القيمة: حقل Colors في كائن DIB يحتوي على قيم RGB صريحة، أو فهارس إلى لوحة ألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


الحصول أو تعيين صورة البت المصدر.

القيمة: بيانات كائن DIB ذات البت المتغير التي تحدد النمط المستخدم في الفرشاة.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


الحصول أو تعيين صورة البت المصدر.

القيمة: بيانات كائن DIB ذات البت المتغير التي تحدد النمط المستخدم في الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

