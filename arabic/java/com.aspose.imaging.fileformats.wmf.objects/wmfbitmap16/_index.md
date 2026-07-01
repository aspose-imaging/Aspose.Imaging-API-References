---
title: "WmfBitmap16"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن Bitmap16 يحدد معلومات حول الأبعاد وتنسيق اللون للصور النقطية."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfBitmap16 extends MetaObject
```

كائن Bitmap16 يحدد معلومات حول الأبعاد وتنسيق اللون للصور النقطية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfBitmap16()](#WmfBitmap16--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يحصل أو يضبط النوع. |
| [setType(short value)](#setType-short-) | يحصل أو يضبط النوع. |
| [getWidth()](#getWidth--) | يحصل أو يعيّن العرض. |
| [setWidth(short value)](#setWidth-short-) | يحصل أو يعيّن العرض. |
| [getHeight()](#getHeight--) | يحصل أو يعيّن الارتفاع. |
| [setHeight(short value)](#setHeight-short-) | يحصل أو يعيّن الارتفاع. |
| [getWidthBytes()](#getWidthBytes--) | يحصل أو يعيّن بايتات العرض. |
| [setWidthBytes(short value)](#setWidthBytes-short-) | يحصل أو يعيّن بايتات العرض. |
| [getPlanes()](#getPlanes--) | يحصل أو يعيّن المستويات. |
| [setPlanes(byte value)](#setPlanes-byte-) | يحصل أو يعيّن المستويات. |
| [getBitsPixel()](#getBitsPixel--) | يحصل أو يعيّن بتات البكسل. |
| [setBitsPixel(byte value)](#setBitsPixel-byte-) | يحصل أو يعيّن بتات البكسل. |
| [getBits()](#getBits--) | يحصل أو يعيّن البتات. |
| [setBits(byte[] value)](#setBits-byte---) | يحصل أو يعيّن البتات. |
### WmfBitmap16() {#WmfBitmap16--}
```
public WmfBitmap16()
```


### getType() {#getType--}
```
public short getType()
```


يحصل أو يضبط النوع.

القيمة: نوع الـ bitmap.

**Returns:**
قصير
### setType(short value) {#setType-short-}
```
public void setType(short value)
```


يحصل أو يضبط النوع.

القيمة: نوع الـ bitmap.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


يحصل أو يعيّن العرض.

القيمة: عرض الصورة النقطية بالبكسل

**Returns:**
قصير
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


يحصل أو يعيّن العرض.

القيمة: عرض الصورة النقطية بالبكسل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


يحصل أو يعيّن الارتفاع.

القيمة: ارتفاع الصورة النقطية بخطوط المسح.

**Returns:**
قصير
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


يحصل أو يعيّن الارتفاع.

القيمة: ارتفاع الصورة النقطية بخطوط المسح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getWidthBytes() {#getWidthBytes--}
```
public short getWidthBytes()
```


يحصل أو يعيّن بايتات العرض.

القيمة: عدد البايتات لكل خط مسح.

**Returns:**
قصير
### setWidthBytes(short value) {#setWidthBytes-short-}
```
public void setWidthBytes(short value)
```


يحصل أو يعيّن بايتات العرض.

القيمة: عدد البايتات لكل خط مسح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getPlanes() {#getPlanes--}
```
public byte getPlanes()
```


يحصل أو يعيّن المستويات.

القيمة: يجب أن تكون قيمة هذا الحقل 0x01.

**Returns:**
byte
### setPlanes(byte value) {#setPlanes-byte-}
```
public void setPlanes(byte value)
```


يحصل أو يعيّن المستويات.

القيمة: يجب أن تكون قيمة هذا الحقل 0x01.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBitsPixel() {#getBitsPixel--}
```
public byte getBitsPixel()
```


يحصل أو يعيّن بتات البكسل.

القيمة: عدد بتات اللون المتجاورة على كل طبقة.

**Returns:**
byte
### setBitsPixel(byte value) {#setBitsPixel-byte-}
```
public void setBitsPixel(byte value)
```


يحصل أو يعيّن بتات البكسل.

القيمة: عدد بتات اللون المتجاورة على كل طبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBits() {#getBits--}
```
public byte[] getBits()
```


يحصل أو يعيّن البتات.

القيمة: بيانات بكسلات الصورة النقطية. يمكن حساب طول هذا الحقل بالبايت كما يلي.

**Returns:**
byte[]
### setBits(byte[] value) {#setBits-byte---}
```
public void setBits(byte[] value)
```


يحصل أو يعيّن البتات.

القيمة: بيانات بكسلات الصورة النقطية. يمكن حساب طول هذا الحقل بالبايت كما يلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

