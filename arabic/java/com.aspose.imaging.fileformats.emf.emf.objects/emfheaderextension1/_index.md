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

كائن HeaderExtension1 يعرّف الامتداد الأول لرأس ملف EMF. يضيف دعمًا لكائن PixelFormatDescriptor (القسم 2.2.22) وسجلات OpenGL [OPENGL] (القسم 2.3.9).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد حجم كائن PixelFormatDescriptor. |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد حجم كائن PixelFormatDescriptor. |
| [getOffPixelFormat()](#getOffPixelFormat--) | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد الإزاحة إلى كائن PixelFormatDescriptor. |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد الإزاحة إلى كائن PixelFormatDescriptor. |
| [getBOpenGl()](#getBOpenGl--) | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يشير إلى ما إذا كانت أوامر OpenGL موجودة في ملف الميتافايل. |
| [setBOpenGl(int value)](#setBOpenGl-int-) | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يشير إلى ما إذا كانت أوامر OpenGL موجودة في ملف الميتافايل. |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد حجم كائن PixelFormatDescriptor. يجب أن يكون هذا 0x00000000 إذا لم يتم تعيين تنسيق بكسل.

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد حجم كائن PixelFormatDescriptor. يجب أن يكون هذا 0x00000000 إذا لم يتم تعيين تنسيق بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد الإزاحة إلى كائن PixelFormatDescriptor. يجب أن يكون هذا 0x00000000 إذا لم يتم تعيين تنسيق بكسل.

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد الإزاحة إلى كائن PixelFormatDescriptor. يجب أن يكون هذا 0x00000000 إذا لم يتم تعيين تنسيق بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يشير إلى ما إذا كانت أوامر OpenGL موجودة في ملف الميتافايل. 0x00000000 سجلات OpenGL غير موجودة في ملف الميتافايل. 0x00000001 سجلات OpenGL موجودة في ملف الميتافايل.

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يشير إلى ما إذا كانت أوامر OpenGL موجودة في ملف الميتافايل. 0x00000000 سجلات OpenGL غير موجودة في ملف الميتافايل. 0x00000001 سجلات OpenGL موجودة في ملف الميتافايل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

