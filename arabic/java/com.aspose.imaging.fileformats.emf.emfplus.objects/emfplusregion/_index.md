---
title: "EmfPlusRegion"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusRegion يحدد مقاطع الخط والمنحنى التي تُعرّف شكلاً غير مستطيل."
type: docs
weight: 68
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusRegion extends EmfPlusGraphicsObjectType
```

كائن EmfPlusRegion يحدد مقاطع الخط والمنحنى التي تُعرّف شكلاً غير مستطيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusRegion()](#EmfPlusRegion--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRegionNode()](#getRegionNode--) | يحصل أو يعيّن مصفوفة من كائنات RegionNodeCount+1 EmfPlusRegionNode (القسم 2.2.2.40). |
| [setRegionNode(EmfPlusRegionNode[] value)](#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---) | يحصل أو يعيّن مصفوفة من كائنات RegionNodeCount+1 EmfPlusRegionNode (القسم 2.2.2.40). |
### EmfPlusRegion() {#EmfPlusRegion--}
```
public EmfPlusRegion()
```


### getRegionNode() {#getRegionNode--}
```
public EmfPlusRegionNode[] getRegionNode()
```


يحصل أو يعيّن مصفوفة من كائنات RegionNodeCount+1 EmfPlusRegionNode (القسم 2.2.2.40). يتم تحديد المناطق كشجرة ثنائية من عقد المنطقة، ويجب أن تكون كل عقدة إما عقدة نهائية أو تحدد عقدة أو عقدتين فرعيتين. يجب أن تحتوي RegionNode على عنصر واحد على الأقل.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode[]
### setRegionNode(EmfPlusRegionNode[] value) {#setRegionNode-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusRegionNode---}
```
public void setRegionNode(EmfPlusRegionNode[] value)
```


يحصل أو يعيّن مصفوفة من كائنات RegionNodeCount+1 EmfPlusRegionNode (القسم 2.2.2.40). يتم تحديد المناطق كشجرة ثنائية من عقد المنطقة، ويجب أن تكون كل عقدة إما عقدة نهائية أو تحدد عقدة أو عقدتين فرعيتين. يجب أن تحتوي RegionNode على عنصر واحد على الأقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusRegionNode\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusregionnode) |  |

