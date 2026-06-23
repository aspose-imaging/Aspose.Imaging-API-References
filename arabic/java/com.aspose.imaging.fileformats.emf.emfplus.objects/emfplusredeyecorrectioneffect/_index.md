---
title: "EmfPlusRedEyeCorrectionEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن RedEyeCorrectionEffect يحدد مناطق في الصورة يتم تطبيق تصحيح العين الحمراء عليها."
type: docs
weight: 67
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusredeyecorrectioneffect/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusRedEyeCorrectionEffect extends EmfPlusImageEffectsObjectType
```

كائن RedEyeCorrectionEffect يحدد مناطق في الصورة يتم تطبيق تصحيح العين الحمراء عليها.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusRedEyeCorrectionEffect()](#EmfPlusRedEyeCorrectionEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNumberOfAreas()](#getNumberOfAreas--) | يحصل أو يعيّن عددًا صحيحًا 32-بت موقعًا يحدد عدد المستطيلات في حقل Areas. |
| [setNumberOfAreas(int value)](#setNumberOfAreas-int-) | يحصل أو يعيّن عددًا صحيحًا 32-بت موقعًا يحدد عدد المستطيلات في حقل Areas. |
| [getAreas()](#getAreas--) | يحصل أو يعيّن مصفوفة من كائنات NumberOfAreas WMF RectL، المحددة في القسم 2.2.2.19 من [MS-WMF]. |
| [setAreas(Rectangle[] value)](#setAreas-com.aspose.imaging.Rectangle---) | يحصل أو يعيّن مصفوفة من كائنات NumberOfAreas WMF RectL، المحددة في القسم 2.2.2.19 من [MS-WMF]. |
### EmfPlusRedEyeCorrectionEffect() {#EmfPlusRedEyeCorrectionEffect--}
```
public EmfPlusRedEyeCorrectionEffect()
```


### getNumberOfAreas() {#getNumberOfAreas--}
```
public int getNumberOfAreas()
```


يحصل أو يعيّن عددًا صحيحًا 32-بت موقعًا يحدد عدد المستطيلات في حقل Areas.

القيمة: عدد المناطق.

**Returns:**
int
### setNumberOfAreas(int value) {#setNumberOfAreas-int-}
```
public void setNumberOfAreas(int value)
```


يحصل أو يعيّن عددًا صحيحًا 32-بت موقعًا يحدد عدد المستطيلات في حقل Areas.

القيمة: عدد المناطق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAreas() {#getAreas--}
```
public Rectangle[] getAreas()
```


يحصل أو يعيّن مصفوفة من كائنات NumberOfAreas WMF RectL، المحددة في القسم 2.2.2.19 من [MS-WMF]. كل مستطيل يحدد منطقة من صورة البت ماب التي يجب تطبيق تأثير تصحيح العين الحمراء عليها SHOULD.

القيمة: المناطق.

**Returns:**
com.aspose.imaging.Rectangle[]
### setAreas(Rectangle[] value) {#setAreas-com.aspose.imaging.Rectangle---}
```
public void setAreas(Rectangle[] value)
```


يحصل أو يعيّن مصفوفة من كائنات NumberOfAreas WMF RectL، المحددة في القسم 2.2.2.19 من [MS-WMF]. كل مستطيل يحدد منطقة من صورة البت ماب التي يجب تطبيق تأثير تصحيح العين الحمراء عليها SHOULD.

القيمة: المناطق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

