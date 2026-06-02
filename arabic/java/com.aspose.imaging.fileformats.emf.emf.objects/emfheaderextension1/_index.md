---
title: "EmfHeaderExtension1"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن HeaderExtension1 يحدد الامتداد الأول لرأس ملف EMF الميتافايل."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
```
public final class EmfHeaderExtension1 extends EmfHeaderObject
```

يحدد كائن HeaderExtension1 الامتداد الأول لرأس ملف EMF. يضيف دعمًا لكائن PixelFormatDescriptor (القسم 2.2.22) وسجلات OpenGL [OPENGL] (القسم 2.3.9).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يحدد حجم كائن PixelFormatDescriptor. |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يحدد حجم كائن PixelFormatDescriptor. |
| [getOffPixelFormat()](#getOffPixelFormat--) | يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يحدد الإزاحة إلى كائن PixelFormatDescriptor. |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يحدد الإزاحة إلى كائن PixelFormatDescriptor. |
| [getBOpenGl()](#getBOpenGl--) | يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يشير إلى ما إذا كانت أوامر OpenGL موجودة في ملف التعريف. |
| [setBOpenGl(int value)](#setBOpenGl-int-) | يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يشير إلى ما إذا كانت أوامر OpenGL موجودة في ملف التعريف. |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يحدد حجم كائن PixelFormatDescriptor. يجب أن يكون هذا 0x00000000 إذا لم يتم تعيين تنسيق بكسل.

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يحدد حجم كائن PixelFormatDescriptor. يجب أن يكون هذا 0x00000000 إذا لم يتم تعيين تنسيق بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يحدد الإزاحة إلى كائن PixelFormatDescriptor. يجب أن يكون هذا 0x00000000 إذا لم يتم تعيين تنسيق بكسل.

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يحدد الإزاحة إلى كائن PixelFormatDescriptor. يجب أن يكون هذا 0x00000000 إذا لم يتم تعيين تنسيق بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يشير إلى ما إذا كانت أوامر OpenGL موجودة في ملف التعريف. 0x00000000 سجلات OpenGL غير موجودة في ملف التعريف. 0x00000001 سجلات OpenGL موجودة في ملف التعريف.

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقعًا 32 بت يشير إلى ما إذا كانت أوامر OpenGL موجودة في ملف التعريف. 0x00000000 سجلات OpenGL غير موجودة في ملف التعريف. 0x00000001 سجلات OpenGL موجودة في ملف التعريف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

