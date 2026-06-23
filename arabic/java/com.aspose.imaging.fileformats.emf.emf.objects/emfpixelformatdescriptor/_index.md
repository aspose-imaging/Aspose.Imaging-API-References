---
title: "EmfPixelFormatDescriptor"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمكن استخدام كائن PixelFormatDescriptor في سجلات EMR_HEADER القسم 2.3.4.2 لتحديد تنسيق البكسل للسطح الخارجي لجهاز التشغيل."
type: docs
weight: 31
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPixelFormatDescriptor extends EmfObject
```

كائن PixelFormatDescriptor يمكن استخدامه في سجلات EMR\_HEADER (القسم 2.3.4.2) لتحديد تنسيق البكسل للسطح الخارجي في سياق جهاز التشغيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNSize()](#getNSize--) | يحصل أو يعيّن عددًا صحيحًا 16‑بت يحدد حجم هذا الهيكل البياني بالبايت. |
| [setNSize(short value)](#setNSize-short-) | يحصل أو يعيّن عددًا صحيحًا 16‑بت يحدد حجم هذا الهيكل البياني بالبايت. |
| [getNVersion()](#getNVersion--) | يحصل أو يعيّن عددًا صحيحًا 16‑بت يجب أن يكون قيمته 0x0001. |
| [setNVersion(short value)](#setNVersion-short-) | يحصل أو يعيّن عددًا صحيحًا 16‑بت يجب أن يكون قيمته 0x0001. |
| [getDwFlags()](#getDwFlags--) | يحصل أو يعيّن أعلام البت التي تحدد خصائص مخزن البكسل المستخدم للإخراج إلى سطح الرسم. |
| [setDwFlags(int value)](#setDwFlags-int-) | يحصل أو يعيّن أعلام البت التي تحدد خصائص مخزن البكسل المستخدم للإخراج إلى سطح الرسم. |
| [getIPixelType()](#getIPixelType--) | يحصل أو يعيّن نوع بيانات البكسل PFD\_TYPE\_RGBA 0x00 تنسيق البكسل هو RGBA. |
| [setIPixelType(byte value)](#setIPixelType-byte-) | يحصل أو يعيّن نوع بيانات البكسل PFD\_TYPE\_RGBA 0x00 تنسيق البكسل هو RGBA. |
| [getCColorBits()](#getCColorBits--) | يحصل أو يعيّن عدد البتات لكل بكسل لأنواع بكسل RGBA، باستثناء مستويات ألفا. |
| [setCColorBits(byte value)](#setCColorBits-byte-) | يحصل أو يعيّن عدد البتات لكل بكسل لأنواع بكسل RGBA، باستثناء مستويات ألفا. |
| [getCRedBits()](#getCRedBits--) | يحصل أو يعيّن عدد مستويات البت الأحمر في كل مخزن ألوان RGBA. |
| [setCRedBits(byte value)](#setCRedBits-byte-) | يحصل أو يعيّن عدد مستويات البت الأحمر في كل مخزن ألوان RGBA. |
| [getCRedShift()](#getCRedShift--) | يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأحمر في كل مخزن ألوان RGBA. |
| [setCRedShift(byte value)](#setCRedShift-byte-) | يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأحمر في كل مخزن ألوان RGBA. |
| [getCGreenBits()](#getCGreenBits--) | يحصل أو يعيّن عدد مستويات البت الأخضر في كل مخزن ألوان RGBA. |
| [setCGreenBits(byte value)](#setCGreenBits-byte-) | يحصل أو يعيّن عدد مستويات البت الأخضر في كل مخزن ألوان RGBA. |
| [getCGreenShift()](#getCGreenShift--) | يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأخضر في كل مخزن ألوان RGBA. |
| [setCGreenShift(byte value)](#setCGreenShift-byte-) | يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأخضر في كل مخزن ألوان RGBA. |
| [getCBlueBits()](#getCBlueBits--) | يحصل أو يعيّن عدد مستويات البت الأزرق في كل مخزن ألوان RGBA. |
| [setCBlueBits(byte value)](#setCBlueBits-byte-) | يحصل أو يعيّن عدد مستويات البت الأزرق في كل مخزن ألوان RGBA. |
| [getCBlueShift()](#getCBlueShift--) | يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأزرق في كل مخزن ألوان RGBA. |
| [setCBlueShift(byte value)](#setCBlueShift-byte-) | يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأزرق في كل مخزن ألوان RGBA. |
| [getCAlphaBits()](#getCAlphaBits--) | يحصل أو يعيّن عدد مستويات البت ألفا في كل مخزن ألوان RGBA. |
| [setCAlphaBits(byte value)](#setCAlphaBits-byte-) | يحصل أو يعيّن عدد مستويات البت ألفا في كل مخزن ألوان RGBA. |
| [getCAlphaShift()](#getCAlphaShift--) | يحصل أو يعيّن عدد إزاحة البتات لمستويات البت ألفا في كل مخزن ألوان RGBA. |
| [setCAlphaShift(byte value)](#setCAlphaShift-byte-) | يحصل أو يعيّن عدد إزاحة البتات لمستويات البت ألفا في كل مخزن ألوان RGBA. |
| [getCAccumBits()](#getCAccumBits--) | الحصول أو الضبط يحدد العدد الإجمالي للطبقات الثنائية في مخزن التجميع. |
| [setCAccumBits(byte value)](#setCAccumBits-byte-) | الحصول أو الضبط يحدد العدد الإجمالي للطبقات الثنائية في مخزن التجميع. |
| [getCAccumRedBits()](#getCAccumRedBits--) | الحصول أو الضبط يحدد عدد طبقات البت الحمراء في مخزن التجميع |
| [setCAccumRedBits(byte value)](#setCAccumRedBits-byte-) | الحصول أو الضبط يحدد عدد طبقات البت الحمراء في مخزن التجميع |
| [getCAccumGreenBits()](#getCAccumGreenBits--) | الحصول أو الضبط يحدد عدد طبقات البت الخضراء في التجميع |
| [setCAccumGreenBits(byte value)](#setCAccumGreenBits-byte-) | الحصول أو الضبط يحدد عدد طبقات البت الخضراء في التجميع |
| [getCAccumBlueBits()](#getCAccumBlueBits--) | الحصول أو الضبط يحدد عدد طبقات البت الزرقاء في مخزن التجميع. |
| [setCAccumBlueBits(byte value)](#setCAccumBlueBits-byte-) | الحصول أو الضبط يحدد عدد طبقات البت الزرقاء في مخزن التجميع. |
| [getCAccumAlphaBits()](#getCAccumAlphaBits--) | الحصول أو الضبط يحدد عدد طبقات البت ألفا في مخزن التجميع |
| [setCAccumAlphaBits(byte value)](#setCAccumAlphaBits-byte-) | الحصول أو الضبط يحدد عدد طبقات البت ألفا في مخزن التجميع |
| [getCDepthBits()](#getCDepthBits--) | الحصول أو الضبط يحدد عمق مخزن العمق (محور z). |
| [setCDepthBits(byte value)](#setCDepthBits-byte-) | الحصول أو الضبط يحدد عمق مخزن العمق (محور z). |
| [getCStencilBits()](#getCStencilBits--) | الحصول أو الضبط يحدد عمق مخزن القالب. |
| [setCStencilBits(byte value)](#setCStencilBits-byte-) | الحصول أو الضبط يحدد عمق مخزن القالب. |
| [getCAuxBuffers()](#getCAuxBuffers--) | الحصول أو الضبط يحدد عدد المخازن المساعدة. |
| [setCAuxBuffers(byte value)](#setCAuxBuffers-byte-) | الحصول أو الضبط يحدد عدد المخازن المساعدة. |
| [getILayerType()](#getILayerType--) | الحصول أو الضبط قد يتم تجاهل هذا الحقل |
| [setILayerType(byte value)](#setILayerType-byte-) | الحصول أو الضبط قد يتم تجاهل هذا الحقل |
| [getBReserved()](#getBReserved--) | الحصول أو الضبط يحدد عدد مستويات التراكب والطبقات السفلية. |
| [setBReserved(byte value)](#setBReserved-byte-) | الحصول أو الضبط يحدد عدد مستويات التراكب والطبقات السفلية. |
| [getDwLayerMask()](#getDwLayerMask--) | الحصول أو الضبط قد يتم تجاهل هذا الحقل. |
| [setDwLayerMask(int value)](#setDwLayerMask-int-) | الحصول أو الضبط قد يتم تجاهل هذا الحقل. |
| [getDwVisibleMask()](#getDwVisibleMask--) | الحصول أو الضبط يحدد اللون الشفاف أو الفهرس لسطح تحتاني. |
| [setDwVisibleMask(int value)](#setDwVisibleMask-int-) | الحصول أو الضبط يحدد اللون الشفاف أو الفهرس لسطح تحتاني. |
| [getDwDamageMask()](#getDwDamageMask--) | الحصول أو الضبط قد يتم تجاهل هذا الحقل |
| [setDwDamageMask(int value)](#setDwDamageMask-int-) | الحصول أو الضبط قد يتم تجاهل هذا الحقل |
### EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor--}
```
public EmfPixelFormatDescriptor()
```


### getNSize() {#getNSize--}
```
public short getNSize()
```


يحصل أو يعيّن عددًا صحيحًا 16‑بت يحدد حجم هذا الهيكل البياني بالبايت.

**Returns:**
قصير
### setNSize(short value) {#setNSize-short-}
```
public void setNSize(short value)
```


يحصل أو يعيّن عددًا صحيحًا 16‑بت يحدد حجم هذا الهيكل البياني بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getNVersion() {#getNVersion--}
```
public short getNVersion()
```


يحصل أو يعيّن عددًا صحيحًا 16‑بت يجب أن يكون قيمته 0x0001.

**Returns:**
قصير
### setNVersion(short value) {#setNVersion-short-}
```
public void setNVersion(short value)
```


يحصل أو يعيّن عددًا صحيحًا 16‑بت يجب أن يكون قيمته 0x0001.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


الحصول أو الضبط يحدد أعلام البت التي تحدد خصائص مخزن البكسل المستخدم للإخراج إلى سطح الرسم. هذه الخصائص ليست جميعها حصرية؛ يُسمح بدمج الأعلام، باستثناء ما هو مذكور خلاف ذلك.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


الحصول أو الضبط يحدد أعلام البت التي تحدد خصائص مخزن البكسل المستخدم للإخراج إلى سطح الرسم. هذه الخصائص ليست جميعها حصرية؛ يُسمح بدمج الأعلام، باستثناء ما هو مذكور خلاف ذلك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getIPixelType() {#getIPixelType--}
```
public byte getIPixelType()
```


الحصول أو الضبط يحدد نوع بيانات البكسل PFD\_TYPE\_RGBA 0x00 تنسيق البكسل هو RGBA. PFD\_TYPE\_COLORINDEX 0x01 كل بكسل هو فهرس في جدول ألوان.

**Returns:**
byte
### setIPixelType(byte value) {#setIPixelType-byte-}
```
public void setIPixelType(byte value)
```


الحصول أو الضبط يحدد نوع بيانات البكسل PFD\_TYPE\_RGBA 0x00 تنسيق البكسل هو RGBA. PFD\_TYPE\_COLORINDEX 0x01 كل بكسل هو فهرس في جدول ألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCColorBits() {#getCColorBits--}
```
public byte getCColorBits()
```


الحصول أو الضبط يحدد عدد البتات لكل بكسل لأنواع بكسل RGBA، باستثناء طبقات البت ألفا. بالنسبة لبكسلات جدول الألوان، فهو حجم كل فهرس في جدول الألوان.

**Returns:**
byte
### setCColorBits(byte value) {#setCColorBits-byte-}
```
public void setCColorBits(byte value)
```


الحصول أو الضبط يحدد عدد البتات لكل بكسل لأنواع بكسل RGBA، باستثناء طبقات البت ألفا. بالنسبة لبكسلات جدول الألوان، فهو حجم كل فهرس في جدول الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCRedBits() {#getCRedBits--}
```
public byte getCRedBits()
```


يحصل أو يعيّن عدد مستويات البت الأحمر في كل مخزن ألوان RGBA.

**Returns:**
byte
### setCRedBits(byte value) {#setCRedBits-byte-}
```
public void setCRedBits(byte value)
```


يحصل أو يعيّن عدد مستويات البت الأحمر في كل مخزن ألوان RGBA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCRedShift() {#getCRedShift--}
```
public byte getCRedShift()
```


يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأحمر في كل مخزن ألوان RGBA.

**Returns:**
byte
### setCRedShift(byte value) {#setCRedShift-byte-}
```
public void setCRedShift(byte value)
```


يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأحمر في كل مخزن ألوان RGBA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCGreenBits() {#getCGreenBits--}
```
public byte getCGreenBits()
```


يحصل أو يعيّن عدد مستويات البت الأخضر في كل مخزن ألوان RGBA.

**Returns:**
byte
### setCGreenBits(byte value) {#setCGreenBits-byte-}
```
public void setCGreenBits(byte value)
```


يحصل أو يعيّن عدد مستويات البت الأخضر في كل مخزن ألوان RGBA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCGreenShift() {#getCGreenShift--}
```
public byte getCGreenShift()
```


يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأخضر في كل مخزن ألوان RGBA.

**Returns:**
byte
### setCGreenShift(byte value) {#setCGreenShift-byte-}
```
public void setCGreenShift(byte value)
```


يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأخضر في كل مخزن ألوان RGBA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCBlueBits() {#getCBlueBits--}
```
public byte getCBlueBits()
```


يحصل أو يعيّن عدد مستويات البت الأزرق في كل مخزن ألوان RGBA.

**Returns:**
byte
### setCBlueBits(byte value) {#setCBlueBits-byte-}
```
public void setCBlueBits(byte value)
```


يحصل أو يعيّن عدد مستويات البت الأزرق في كل مخزن ألوان RGBA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCBlueShift() {#getCBlueShift--}
```
public byte getCBlueShift()
```


يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأزرق في كل مخزن ألوان RGBA.

**Returns:**
byte
### setCBlueShift(byte value) {#setCBlueShift-byte-}
```
public void setCBlueShift(byte value)
```


يحصل أو يعيّن عدد إزاحة البتات لمستويات البت الأزرق في كل مخزن ألوان RGBA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCAlphaBits() {#getCAlphaBits--}
```
public byte getCAlphaBits()
```


يحصل أو يعيّن عدد مستويات البت ألفا في كل مخزن ألوان RGBA.

**Returns:**
byte
### setCAlphaBits(byte value) {#setCAlphaBits-byte-}
```
public void setCAlphaBits(byte value)
```


يحصل أو يعيّن عدد مستويات البت ألفا في كل مخزن ألوان RGBA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCAlphaShift() {#getCAlphaShift--}
```
public byte getCAlphaShift()
```


يحصل أو يعيّن عدد إزاحة البتات لمستويات البت ألفا في كل مخزن ألوان RGBA.

**Returns:**
byte
### setCAlphaShift(byte value) {#setCAlphaShift-byte-}
```
public void setCAlphaShift(byte value)
```


يحصل أو يعيّن عدد إزاحة البتات لمستويات البت ألفا في كل مخزن ألوان RGBA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCAccumBits() {#getCAccumBits--}
```
public byte getCAccumBits()
```


الحصول أو الضبط يحدد العدد الإجمالي للطبقات الثنائية في مخزن التجميع.

**Returns:**
byte
### setCAccumBits(byte value) {#setCAccumBits-byte-}
```
public void setCAccumBits(byte value)
```


الحصول أو الضبط يحدد العدد الإجمالي للطبقات الثنائية في مخزن التجميع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCAccumRedBits() {#getCAccumRedBits--}
```
public byte getCAccumRedBits()
```


الحصول أو الضبط يحدد عدد طبقات البت الحمراء في مخزن التجميع

**Returns:**
byte
### setCAccumRedBits(byte value) {#setCAccumRedBits-byte-}
```
public void setCAccumRedBits(byte value)
```


الحصول أو الضبط يحدد عدد طبقات البت الحمراء في مخزن التجميع

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCAccumGreenBits() {#getCAccumGreenBits--}
```
public byte getCAccumGreenBits()
```


الحصول أو الضبط يحدد عدد طبقات البت الخضراء في التجميع

**Returns:**
byte
### setCAccumGreenBits(byte value) {#setCAccumGreenBits-byte-}
```
public void setCAccumGreenBits(byte value)
```


الحصول أو الضبط يحدد عدد طبقات البت الخضراء في التجميع

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCAccumBlueBits() {#getCAccumBlueBits--}
```
public byte getCAccumBlueBits()
```


الحصول أو الضبط يحدد عدد طبقات البت الزرقاء في مخزن التجميع.

**Returns:**
byte
### setCAccumBlueBits(byte value) {#setCAccumBlueBits-byte-}
```
public void setCAccumBlueBits(byte value)
```


الحصول أو الضبط يحدد عدد طبقات البت الزرقاء في مخزن التجميع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCAccumAlphaBits() {#getCAccumAlphaBits--}
```
public byte getCAccumAlphaBits()
```


الحصول أو الضبط يحدد عدد طبقات البت ألفا في مخزن التجميع

**Returns:**
byte
### setCAccumAlphaBits(byte value) {#setCAccumAlphaBits-byte-}
```
public void setCAccumAlphaBits(byte value)
```


الحصول أو الضبط يحدد عدد طبقات البت ألفا في مخزن التجميع

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCDepthBits() {#getCDepthBits--}
```
public byte getCDepthBits()
```


الحصول أو الضبط يحدد عمق مخزن العمق (محور z).

**Returns:**
byte
### setCDepthBits(byte value) {#setCDepthBits-byte-}
```
public void setCDepthBits(byte value)
```


الحصول أو الضبط يحدد عمق مخزن العمق (محور z).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCStencilBits() {#getCStencilBits--}
```
public byte getCStencilBits()
```


الحصول أو الضبط يحدد عمق مخزن القالب.

**Returns:**
byte
### setCStencilBits(byte value) {#setCStencilBits-byte-}
```
public void setCStencilBits(byte value)
```


الحصول أو الضبط يحدد عمق مخزن القالب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCAuxBuffers() {#getCAuxBuffers--}
```
public byte getCAuxBuffers()
```


الحصول أو الضبط يحدد عدد المخازن المساعدة. المخازن المساعدة غير مدعومة

**Returns:**
byte
### setCAuxBuffers(byte value) {#setCAuxBuffers-byte-}
```
public void setCAuxBuffers(byte value)
```


الحصول أو الضبط يحدد عدد المخازن المساعدة. المخازن المساعدة غير مدعومة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getILayerType() {#getILayerType--}
```
public byte getILayerType()
```


الحصول أو الضبط قد يتم تجاهل هذا الحقل

**Returns:**
byte
### setILayerType(byte value) {#setILayerType-byte-}
```
public void setILayerType(byte value)
```


الحصول أو الضبط قد يتم تجاهل هذا الحقل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBReserved() {#getBReserved--}
```
public byte getBReserved()
```


الحصول أو الضبط يحدد عدد مستويات التراكب والطبقات السفلية. البتات من 0 إلى 3 تحدد حتى 15 مستوى تراكب والبِتات من 4 إلى 7 تحدد حتى 15 طبقة سفلية

**Returns:**
byte
### setBReserved(byte value) {#setBReserved-byte-}
```
public void setBReserved(byte value)
```


الحصول أو الضبط يحدد عدد مستويات التراكب والطبقات السفلية. البتات من 0 إلى 3 تحدد حتى 15 مستوى تراكب والبِتات من 4 إلى 7 تحدد حتى 15 طبقة سفلية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getDwLayerMask() {#getDwLayerMask--}
```
public int getDwLayerMask()
```


الحصول أو الضبط قد يتم تجاهل هذا الحقل.

**Returns:**
int
### setDwLayerMask(int value) {#setDwLayerMask-int-}
```
public void setDwLayerMask(int value)
```


الحصول أو الضبط قد يتم تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDwVisibleMask() {#getDwVisibleMask--}
```
public int getDwVisibleMask()
```


الحصول أو الضبط يحدد اللون الشفاف أو الفهرس لسطح تحتاني. عندما يكون نوع البكسل RGBA، يكون dwVisibleMask قيمة لون RGB شفاف. عندما يكون نوع البكسل فهرس ألوان، يكون قيمة فهرس شفافة.

**Returns:**
int
### setDwVisibleMask(int value) {#setDwVisibleMask-int-}
```
public void setDwVisibleMask(int value)
```


الحصول أو الضبط يحدد اللون الشفاف أو الفهرس لسطح تحتاني. عندما يكون نوع البكسل RGBA، يكون dwVisibleMask قيمة لون RGB شفاف. عندما يكون نوع البكسل فهرس ألوان، يكون قيمة فهرس شفافة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDwDamageMask() {#getDwDamageMask--}
```
public int getDwDamageMask()
```


الحصول أو الضبط قد يتم تجاهل هذا الحقل

**Returns:**
int
### setDwDamageMask(int value) {#setDwDamageMask-int-}
```
public void setDwDamageMask(int value)
```


الحصول أو الضبط قد يتم تجاهل هذا الحقل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

