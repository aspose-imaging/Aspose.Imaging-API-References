---
title: "EmfMetafileHeaderExtension1"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EmfMetafileHeaderExtension1 هو سجل الرأس المستخدم في الامتداد الأول لملفات EMF الميتا."
type: docs
weight: 71
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
```
public class EmfMetafileHeaderExtension1 extends EmfMetafileHeader
```

سجل EmfMetafileHeaderExtension1 هو سجل الرأس المستخدم في الامتداد الأول لملفات EMF. بعد حقل EmfHeaderExtension1، تكون الحقول المتبقية اختيارية ويمكن أن تكون موجودة بأي ترتيب.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfMetafileHeaderExtension1(EmfMetafileHeader header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | ينشئ مثلاً جديداً من الفئة `EmfMetafileHeaderExtension1`. |
| [EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-) | ينشئ مثلاً جديداً من الفئة `EmfMetafileHeaderExtension1`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEmfHeaderExtension1()](#getEmfHeaderExtension1--) | يحصل أو يعيّن كائن HeaderExtension1، الذي يحدد معلومات إضافية حول الصورة في ملف الميتا. |
| [setEmfHeaderExtension1(EmfHeaderExtension1 value)](#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-) | يحصل أو يعيّن كائن HeaderExtension1، الذي يحدد معلومات إضافية حول الصورة في ملف الميتا. |
| [getEmfPixelFormatBuffer()](#getEmfPixelFormatBuffer--) | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحتوي على موصّف تنسيق بكسل EMF، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EmfMetafileHeaderExtension1 أو مع سلسلة وصف EMF. |
| [setEmfPixelFormatBuffer(byte[] value)](#setEmfPixelFormatBuffer-byte---) | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحتوي على موصّف تنسيق بكسل EMF، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EmfMetafileHeaderExtension1 أو مع سلسلة وصف EMF. |
### EmfMetafileHeaderExtension1(EmfMetafileHeader header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeader header)
```


ينشئ مثلاً جديداً من الفئة `EmfMetafileHeaderExtension1`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | الرأس. |

### EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)
```


ينشئ مثلاً جديداً من الفئة `EmfMetafileHeaderExtension1`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| header | [EmfMetafileHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | الرأس. |

### getEmfHeaderExtension1() {#getEmfHeaderExtension1--}
```
public EmfHeaderExtension1 getEmfHeaderExtension1()
```


يحصل أو يعيّن كائن HeaderExtension1، الذي يحدد معلومات إضافية حول الصورة في ملف الميتا.

**Returns:**
[EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1)
### setEmfHeaderExtension1(EmfHeaderExtension1 value) {#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-}
```
public void setEmfHeaderExtension1(EmfHeaderExtension1 value)
```


يحصل أو يعيّن كائن HeaderExtension1، الذي يحدد معلومات إضافية حول الصورة في ملف الميتا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1) |  |

### getEmfPixelFormatBuffer() {#getEmfPixelFormatBuffer--}
```
public byte[] getEmfPixelFormatBuffer()
```


يحصل أو يعيّن مصفوفة اختيارية من البايتات تحتوي على موصّف تنسيق بكسل EMF، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EmfMetafileHeaderExtension1 أو مع سلسلة وصف EMF. وبالتالي، الحقل في هذا المخزن المؤقت المسمّى "UndefinedSpace" هو اختياري ويجب تجاهله.

**Returns:**
byte[]
### setEmfPixelFormatBuffer(byte[] value) {#setEmfPixelFormatBuffer-byte---}
```
public void setEmfPixelFormatBuffer(byte[] value)
```


يحصل أو يعيّن مصفوفة اختيارية من البايتات تحتوي على موصّف تنسيق بكسل EMF، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EmfMetafileHeaderExtension1 أو مع سلسلة وصف EMF. وبالتالي، الحقل في هذا المخزن المؤقت المسمّى "UndefinedSpace" هو اختياري ويجب تجاهله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

