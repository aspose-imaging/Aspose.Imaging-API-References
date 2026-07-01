---
title: "WmfBitmapBaseHeader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة رأس الصورة النقطية الأساسية."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public abstract class WmfBitmapBaseHeader extends MetaObject
```

فئة رأس الصورة النقطية الأساسية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfBitmapBaseHeader()](#WmfBitmapBaseHeader--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد حجم هذا الكائن بالبايت. |
| [setHeaderSize(int value)](#setHeaderSize-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد حجم هذا الكائن بالبايت. |
| [getPlanes()](#getPlanes--) | يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد عدد `planes` للجهاز المستهدف. |
| [setPlanes(short value)](#setPlanes-short-) | يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد عدد `planes` للجهاز المستهدف. |
| [getBitCount()](#getBitCount--) | يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد تنسيق كل بكسل، والحد الأقصى لعدد الألوان في DIB. |
| [setBitCount(short value)](#setBitCount-short-) | يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد تنسيق كل بكسل، والحد الأقصى لعدد الألوان في DIB. |
### WmfBitmapBaseHeader() {#WmfBitmapBaseHeader--}
```
public WmfBitmapBaseHeader()
```


### getHeaderSize() {#getHeaderSize--}
```
public int getHeaderSize()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد حجم هذا الكائن بالبايت.

**Returns:**
int
### setHeaderSize(int value) {#setHeaderSize-int-}
```
public void setHeaderSize(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد حجم هذا الكائن بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عدد صحيح غير موقع 16 بت يحدد عدد `planes` للجهاز المستهدف. يجب أن تكون هذه القيمة 0x0001. |

### getPlanes() {#getPlanes--}
```
public short getPlanes()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد عدد `planes` للجهاز المستهدف. يجب أن تكون هذه القيمة 0x0001.

**Returns:**
short - عدد صحيح غير موقع 16 بت يحدد عدد `planes` للجهاز المستهدف.
### setPlanes(short value) {#setPlanes-short-}
```
public void setPlanes(short value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد عدد `planes` للجهاز المستهدف. يجب أن تكون هذه القيمة 0x0001.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير | عدد صحيح غير موقع 16 بت يحدد عدد `planes` للجهاز المستهدف. يجب أن تكون هذه القيمة \\* 0x0001. |

### getBitCount() {#getBitCount--}
```
public short getBitCount()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد تنسيق كل بكسل، والحد الأقصى لعدد الألوان في DIB. يجب أن تكون هذه القيمة ضمن تعداد `BitCount` (القسم 2.1.1.3).

**Returns:**
short - عدد صحيح غير موقع 16 بت يحدد تنسيق كل بكسل، والحد الأقصى لعدد الألوان في DIB.
### setBitCount(short value) {#setBitCount-short-}
```
public void setBitCount(short value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 16 بت يحدد تنسيق كل بكسل، والحد الأقصى لعدد الألوان في DIB. يجب أن تكون هذه القيمة ضمن تعداد `BitCount` (القسم 2.1.1.3).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير | عدد صحيح غير موقع 16 بت يحدد تنسيق كل بكسل، والحد الأقصى لعدد الألوان في DIB. |

