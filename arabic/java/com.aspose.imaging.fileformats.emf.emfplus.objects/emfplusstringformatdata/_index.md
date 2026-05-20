---
title: "EmfPlusStringFormatData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد كائن EmfPlusStringFormatData مواضع التبويب ومواقع الأحرف لسلسلة رسومية."
type: docs
weight: 75
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusStringFormatData extends EmfPlusStructureObjectType
```

يحدد كائن EmfPlusStringFormatData مواضع التبويب ومواقع الأحرف لسلسلة رسومية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTabStops()](#getTabStops--) | يحصل أو يعيّن مصفوفة اختيارية من القيم العشرية التي تحدد مواقع إيقاف التبويب الاختيارية لهذا الكائن. |
| [setTabStops(float[] value)](#setTabStops-float---) | يحصل أو يعيّن مصفوفة اختيارية من القيم العشرية التي تحدد مواقع إيقاف التبويب الاختيارية لهذا الكائن. |
| [getCharRange()](#getCharRange--) | يحصل أو يعيّن مصفوفة اختيارية من كائنات RangeCount EmfPlusCharacterRange التي تحدد نطاق مواضع الأحرف داخل سلسلة نصية. |
| [setCharRange(EmfPlusCharacterRange[] value)](#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---) | يحصل أو يعيّن مصفوفة اختيارية من كائنات RangeCount EmfPlusCharacterRange التي تحدد نطاق مواضع الأحرف داخل سلسلة نصية. |
### EmfPlusStringFormatData() {#EmfPlusStringFormatData--}
```
public EmfPlusStringFormatData()
```


### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


يحصل أو يعيّن مصفوفة اختيارية من القيم العشرية التي تحدد مواقع إيقاف التبويب الاختيارية لهذا الكائن. كل قيمة إيقاف تبويب تمثل عدد المسافات بين إيقافات التبويب أو، لإيقاف التبويب الأول، عدد المسافات بين بداية سطر النص وإيقاف التبويب الأول. يجب أن يكون هذا الحقل موجودًا إذا كانت قيمة الحقل TabStopCount في كائن EmfPlusStringFormat أكبر من 0.

**Returns:**
float[]
### setTabStops(float[] value) {#setTabStops-float---}
```
public void setTabStops(float[] value)
```


يحصل أو يعيّن مصفوفة اختيارية من القيم العشرية التي تحدد مواقع إيقاف التبويب الاختيارية لهذا الكائن. كل قيمة إيقاف تبويب تمثل عدد المسافات بين إيقافات التبويب أو، لإيقاف التبويب الأول، عدد المسافات بين بداية سطر النص وإيقاف التبويب الأول. يجب أن يكون هذا الحقل موجودًا إذا كانت قيمة الحقل TabStopCount في كائن EmfPlusStringFormat أكبر من 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float[] |  |

### getCharRange() {#getCharRange--}
```
public EmfPlusCharacterRange[] getCharRange()
```


يحصل أو يعيّن مصفوفة اختيارية من كائنات RangeCount EmfPlusCharacterRange التي تحدد نطاق مواضع الأحرف داخل سلسلة نصية. يتم تعريف المنطقة المحيطة بواسطة مساحة العرض التي يشغلها مجموعة الأحرف المحددة بنطاق الأحرف. يجب أن يكون هذا الحقل موجودًا إذا كانت قيمة الحقل RangeCount في كائن EmfPlusStringFormat أكبر من 0.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange[]
### setCharRange(EmfPlusCharacterRange[] value) {#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---}
```
public void setCharRange(EmfPlusCharacterRange[] value)
```


يحصل أو يعيّن مصفوفة اختيارية من كائنات RangeCount EmfPlusCharacterRange التي تحدد نطاق مواضع الأحرف داخل سلسلة نصية. يتم تعريف المنطقة المحيطة بواسطة مساحة العرض التي يشغلها مجموعة الأحرف المحددة بنطاق الأحرف. يجب أن يكون هذا الحقل موجودًا إذا كانت قيمة الحقل RangeCount في كائن EmfPlusStringFormat أكبر من 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusCharacterRange\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange) |  |

