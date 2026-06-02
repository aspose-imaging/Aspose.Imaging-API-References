---
title: "WmfDeviceIndependentBitmap"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يقوم كائن DeviceIndependentBitmap بتعريف صورة بتنسيق bitmap المستقل عن الجهاز DIB."
type: docs
weight: 27
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfDeviceIndependentBitmap extends MetaObject
```

كائن DeviceIndependentBitmap يعرّف صورة بتنسيق صورة نقطية مستقلة عن الجهاز (DIB).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHeader()](#getHeader--) | يحصل أو يعيّن إما كائن BitmapCoreHeader (القسم 2.2.2.2) أو كائن BitmapInfoHeader (القسم 2.2.2.3) الذي يحدد معلومات حول الصورة. |
| [setHeader(WmfBitmapBaseHeader value)](#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-) | يحصل أو يعيّن إما كائن BitmapCoreHeader (القسم 2.2.2.2) أو كائن BitmapInfoHeader (القسم 2.2.2.3) الذي يحدد معلومات حول الصورة. |
| [getColorsData()](#getColorsData--) | يحصل أو يعيّن مصفوفة اختيارية إما لكائنات RGBQuad (القسم 2.2.2.20) أو أعداد صحيحة غير موقعة 16‑بت تُعرّف جدول ألوان. |
| [setColorsData(byte[] value)](#setColorsData-byte---) | يحصل أو يعيّن مصفوفة اختيارية إما لكائنات RGBQuad (القسم 2.2.2.20) أو أعداد صحيحة غير موقعة 16‑بت تُعرّف جدول ألوان. |
| [getAData()](#getAData--) | يحصل أو يعيّن مصفوفة من البايتات التي تُعرّف الصورة. |
| [setAData(byte[] value)](#setAData-byte---) | يحصل أو يعيّن مصفوفة من البايتات التي تُعرّف الصورة. |
| [getCachedImage()](#getCachedImage--) | يحصل على صورة الراستر المخزنة مؤقتًا. |
| [setCachedImage(byte[] value)](#setCachedImage-byte---) | يعيّن صورة الراستر المخزنة مؤقتًا. |
### WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap--}
```
public WmfDeviceIndependentBitmap()
```


### getHeader() {#getHeader--}
```
public WmfBitmapBaseHeader getHeader()
```


يحصل أو يعيّن إما كائن BitmapCoreHeader (القسم 2.2.2.2) أو كائن BitmapInfoHeader (القسم 2.2.2.3) الذي يحدد معلومات حول الصورة.

**Returns:**
[WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
### setHeader(WmfBitmapBaseHeader value) {#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-}
```
public void setHeader(WmfBitmapBaseHeader value)
```


يحصل أو يعيّن إما كائن BitmapCoreHeader (القسم 2.2.2.2) أو كائن BitmapInfoHeader (القسم 2.2.2.3) الذي يحدد معلومات حول الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader) |  |

### getColorsData() {#getColorsData--}
```
public byte[] getColorsData()
```


يحصل أو يعيّن مصفوفة اختيارية إما لكائنات RGBQuad (القسم 2.2.2.20) أو أعداد صحيحة غير موقعة 16‑بت تُعرّف جدول ألوان. يجب تحديد حجم ومحتوى هذا الحقل من سجل الميتافايل أو الكائن الذي يحتوي على DeviceIndependentBitmap ومن المعلومات الموجودة في حقل DIBHeaderInfo. راجع تعداد ColorUsage (القسم 2.1.1.6) وتعداد BitCount (القسم 2.1.1.3) للحصول على تفاصيل إضافية.

**Returns:**
byte[]
### setColorsData(byte[] value) {#setColorsData-byte---}
```
public void setColorsData(byte[] value)
```


يحصل أو يعيّن مصفوفة اختيارية إما لكائنات RGBQuad (القسم 2.2.2.20) أو أعداد صحيحة غير موقعة 16‑بت تُعرّف جدول ألوان. يجب تحديد حجم ومحتوى هذا الحقل من سجل الميتافايل أو الكائن الذي يحتوي على DeviceIndependentBitmap ومن المعلومات الموجودة في حقل DIBHeaderInfo. راجع تعداد ColorUsage (القسم 2.1.1.6) وتعداد BitCount (القسم 2.1.1.3) للحصول على تفاصيل إضافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getAData() {#getAData--}
```
public byte[] getAData()
```


يحصل أو يعيّن مصفوفة من البايتات التي تُعرّف الصورة. يتم تحديد حجم وشكل هذه البيانات بناءً على المعلومات الموجودة في حقل DIBHeaderInfo.

**Returns:**
byte[]
### setAData(byte[] value) {#setAData-byte---}
```
public void setAData(byte[] value)
```


يحصل أو يعيّن مصفوفة من البايتات التي تُعرّف الصورة. يتم تحديد حجم وشكل هذه البيانات بناءً على المعلومات الموجودة في حقل DIBHeaderInfo.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getCachedImage() {#getCachedImage--}
```
public final byte[] getCachedImage()
```


يحصل على صورة الراستر المخزنة مؤقتًا.

القيمة: الصورة المخزنة مؤقتًا.

**Returns:**
byte[]
### setCachedImage(byte[] value) {#setCachedImage-byte---}
```
public void setCachedImage(byte[] value)
```


يعيّن صورة الراستر المخزنة مؤقتًا.

القيمة: الصورة المخزنة مؤقتًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

