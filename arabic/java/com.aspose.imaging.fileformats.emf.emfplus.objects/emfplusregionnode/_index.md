---
title: "EmfPlusRegionNode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد كائن EmfPlusRegionNode عقد منطقة رسومية."
type: docs
weight: 69
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusRegionNode extends EmfPlusStructureObjectType
```

يحدد كائن EmfPlusRegionNode عقد منطقة رسومية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusRegionNode()](#EmfPlusRegionNode--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRegionNodeData()](#getRegionNodeData--) | يحصل أو يعيّن بيانات اختيارية ذات طول متغيّر تُعرّف كائن بيانات عقدة المنطقة المحدد في حقل Type. |
| [setRegionNodeData(EmfPlusStructureObjectType value)](#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-) | يحصل أو يعيّن بيانات اختيارية ذات طول متغيّر تُعرّف كائن بيانات عقدة المنطقة المحدد في حقل Type. |
| [getType()](#getType--) | يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد نوع البيانات في حقل RegionNodeData. |
| [setType(int value)](#setType-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد نوع البيانات في حقل RegionNodeData. |
### EmfPlusRegionNode() {#EmfPlusRegionNode--}
```
public EmfPlusRegionNode()
```


### getRegionNodeData() {#getRegionNodeData--}
```
public EmfPlusStructureObjectType getRegionNodeData()
```


يحصل أو يعيّن بيانات اختيارية ذات طول متغيّر تُعرّف كائن بيانات عقدة المنطقة المحدد في حقل Type. يمكن أن يكون محتوى البيانات وتنسيقها مختلفًا لكل نوع من أنواع عقدة المنطقة. يجب ألا يكون هذا الحقل موجودًا إذا كان نوع العقدة هو RegionNodeDataTypeEmpty أو RegionNodeDataTypeInfinite. هذا الكائن عام ويُستخدم لتحديد أنواع مختلفة من بيانات عقدة المنطقة، بما في ذلك: كائن EmfPlusRegionNodePath (القسم 2.2.2.42) لعقدة نهائية؛ كائن EmfPlusRectF (القسم 2.2.2.39) لعقدة نهائية؛ وكائن EmfPlusRegionNodeChildNodes (القسم 2.2.2.41) لعقدة غير نهائية.

**Returns:**
[EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
### setRegionNodeData(EmfPlusStructureObjectType value) {#setRegionNodeData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType-}
```
public void setRegionNodeData(EmfPlusStructureObjectType value)
```


يحصل أو يعيّن بيانات اختيارية ذات طول متغيّر تُعرّف كائن بيانات عقدة المنطقة المحدد في حقل Type. يمكن أن يكون محتوى البيانات وتنسيقها مختلفًا لكل نوع من أنواع عقدة المنطقة. يجب ألا يكون هذا الحقل موجودًا إذا كان نوع العقدة هو RegionNodeDataTypeEmpty أو RegionNodeDataTypeInfinite. هذا الكائن عام ويُستخدم لتحديد أنواع مختلفة من بيانات عقدة المنطقة، بما في ذلك: كائن EmfPlusRegionNodePath (القسم 2.2.2.42) لعقدة نهائية؛ كائن EmfPlusRectF (القسم 2.2.2.39) لعقدة نهائية؛ وكائن EmfPlusRegionNodeChildNodes (القسم 2.2.2.41) لعقدة غير نهائية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype) |  |

### getType() {#getType--}
```
public int getType()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد نوع البيانات في حقل RegionNodeData. يجب أن تكون هذه القيمة معرفة في تعداد RegionNodeDataType (القسم 2.1.1.27).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد نوع البيانات في حقل RegionNodeData. يجب أن تكون هذه القيمة معرفة في تعداد RegionNodeDataType (القسم 2.1.1.27).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

