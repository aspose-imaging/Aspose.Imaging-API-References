---
title: "EmfPlusImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusImage يحدد صورة رسومية على شكل بت ماب أو ملف تعريف."
type: docs
weight: 47
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImage extends EmfPlusGraphicsObjectType
```

كائن EmfPlusImage يحدد صورة رسومية على شكل بت ماب أو ملف تعريف.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusImage()](#EmfPlusImage--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getImageData()](#getImageData--) | يحصل أو يعيّن بيانات Image المتغيرة الطول التي تحدد بيانات الصورة المحددة في الحقل Type. |
| [setImageData(EmfPlusBaseImageData value)](#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-) | يحصل أو يعيّن بيانات Image المتغيرة الطول التي تحدد بيانات الصورة المحددة في الحقل Type. |
| [getType()](#getType--) | يحصل أو يعيّن نوع الصورة عدد صحيح غير موقع 32‑بت يحدد نوع البيانات في حقل ImageData. |
| [setType(int value)](#setType-int-) | يحصل أو يعيّن نوع الصورة عدد صحيح غير موقع 32‑بت يحدد نوع البيانات في حقل ImageData. |
### EmfPlusImage() {#EmfPlusImage--}
```
public EmfPlusImage()
```


### getImageData() {#getImageData--}
```
public EmfPlusBaseImageData getImageData()
```


يحصل أو يعيّن بيانات Image المتغيرة الطول التي تحدد بيانات الصورة المحددة في الحقل Type. يمكن أن يكون محتوى البيانات وتنسيقها مختلفين لكل نوع صورة.

**Returns:**
[EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
### setImageData(EmfPlusBaseImageData value) {#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-}
```
public void setImageData(EmfPlusBaseImageData value)
```


يحصل أو يعيّن بيانات Image المتغيرة الطول التي تحدد بيانات الصورة المحددة في الحقل Type. يمكن أن يكون محتوى البيانات وتنسيقها مختلفين لكل نوع صورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata) |  |

### getType() {#getType--}
```
public int getType()
```


يحصل أو يعيّن نوع الصورة عدد صحيح غير موقع 32‑بت يحدد نوع البيانات في حقل ImageData. يجب أن تكون هذه القيمة معرفة في تعداد ImageDataType (القسم 2.1.1.15).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


يحصل أو يعيّن نوع الصورة عدد صحيح غير موقع 32‑بت يحدد نوع البيانات في حقل ImageData. يجب أن تكون هذه القيمة معرفة في تعداد ImageDataType (القسم 2.1.1.15).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

