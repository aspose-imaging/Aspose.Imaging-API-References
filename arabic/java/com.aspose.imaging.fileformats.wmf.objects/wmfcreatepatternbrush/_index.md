---
title: "WmfCreatePatternBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل META_CREATEPATTERNBRUSH ينشئ كائن فرشاة بنمط محدد بواسطة صورة bitmap."
type: docs
weight: 23
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePatternBrush extends WmfGraphicObject
```

سجل META\_CREATEPATTERNBRUSH ينشئ كائن فرشاة بنمط محدد بواسطة صورة نقطية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfCreatePatternBrush()](#WmfCreatePatternBrush--) | سجل WMFs. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitmap()](#getBitmap--) | الحصول على أو تعيين الـ bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | الحصول على أو تعيين الـ bitmap. |
| [getReserved()](#getReserved--) | يحصل أو يعيّن الحجز. |
| [setReserved(byte[] value)](#setReserved-byte---) | يحصل أو يعيّن الحجز. |
| [getPattern()](#getPattern--) | يحصل أو يعيّن النمط. |
| [setPattern(byte[] value)](#setPattern-byte---) | يحصل أو يعيّن النمط. |
### WmfCreatePatternBrush() {#WmfCreatePatternBrush--}
```
public WmfCreatePatternBrush()
```


سجل WMFs.

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


الحصول على أو تعيين الـ bitmap.

القيمة: صورة bitmap التي تحدد النمط للفرشاة.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


الحصول على أو تعيين الـ bitmap.

القيمة: صورة bitmap التي تحدد النمط للفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

### getReserved() {#getReserved--}
```
public byte[] getReserved()
```


يحصل أو يعيّن الحجز.

القيمة: المحجوز. يجب تجاهل هذا الحقل.

**Returns:**
byte[]
### setReserved(byte[] value) {#setReserved-byte---}
```
public void setReserved(byte[] value)
```


يحصل أو يعيّن الحجز.

القيمة: المحجوز. يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getPattern() {#getPattern--}
```
public byte[] getPattern()
```


يحصل أو يعيّن النمط.

القيمة: مصفوفة بطول متغير من البايتات تُعرّف بيانات بكسل صورة bitmap التي تُكوّن نمط الفرشاة. يمكن حساب طول هذا الحقل، بالبايتات، من معلمات bitmap كما يلي.

**Returns:**
byte[]
### setPattern(byte[] value) {#setPattern-byte---}
```
public void setPattern(byte[] value)
```


يحصل أو يعيّن النمط.

القيمة: مصفوفة بطول متغير من البايتات تُعرّف بيانات بكسل صورة bitmap التي تُكوّن نمط الفرشاة. يمكن حساب طول هذا الحقل، بالبايتات، من معلمات bitmap كما يلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

