---
title: "EmfPlusRegion"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد كائن EmfPlusRegion مقاطع الخط والمنحنى التي تُعرّف شكلاً غير مستطيلاً"
type: docs
weight: 68
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

يحدد كائن EmfPlusRegion مقاطع الخط والمنحنى التي تُعرّف شكلاً غير مستطيلاً
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | يحصل أو يضبط مصفوفة من كائنات EmfPlusRegionNode عددها RegionNodeCount+1 (القسم 2.2.2.40). |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | يحصل أو يضبط مصفوفة من كائنات EmfPlusRegionNode عددها RegionNodeCount+1 (القسم 2.2.2.40). |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


يحصل أو يضبط مصفوفة من كائنات EmfPlusRegionNode عددها RegionNodeCount+1 (القسم 2.2.2.40). تُحدد المناطق كشجرة ثنائية من عقد المنطقة، ويجب أن تكون كل عقدة إما عقدة نهائية أو تحدد عقدة أو عقدتين فرعيتين. يجب أن يحتوي RegionNode على عنصر واحد على الأقل.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


يحصل أو يضبط مصفوفة من كائنات EmfPlusRegionNode عددها RegionNodeCount+1 (القسم 2.2.2.40). تُحدد المناطق كشجرة ثنائية من عقد المنطقة، ويجب أن تكون كل عقدة إما عقدة نهائية أو تحدد عقدة أو عقدتين فرعيتين. يجب أن يحتوي RegionNode على عنصر واحد على الأقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

