---
title: EmfPlusCustomLineCapOptionalData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusCustomLineCapOptionalData object specifies optional fill and outline data for a custom line cap.
type: docs
weight: 37
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCustomLineCapOptionalData extends EmfPlusStructureObjectType
```

The EmfPlusCustomLineCapOptionalData object specifies optional fill and outline data for a custom line cap.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFillData()](#getFillData--) | Gets or sets optional EmfPlusFillPath object (section 2.2.2.17) that specifies the path for filling a custom graphics line cap. |
| [setFillData(EmfPlusFillPath value)](#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-) | Gets or sets optional EmfPlusFillPath object (section 2.2.2.17) that specifies the path for filling a custom graphics line cap. |
| [getOutlineData()](#getOutlineData--) | Gets or sets optional EmfPlusLinePath object (section 2.2.2.26) that specifies the path for outlining a custom graphics line cap. |
| [setOutlineData(EmfPlusLinePath value)](#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-) | Gets or sets optional EmfPlusLinePath object (section 2.2.2.26) that specifies the path for outlining a custom graphics line cap. |
### EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData--}
```
public EmfPlusCustomLineCapOptionalData()
```


### getFillData() {#getFillData--}
```
public EmfPlusFillPath getFillData()
```


Gets or sets optional EmfPlusFillPath object (section 2.2.2.17) that specifies the path for filling a custom graphics line cap. This field MUST be present if the CustomLineCapDataFillPath flag is set in the CustomLineCapDataFlags field of the EmfPlusCustomLineCapData object.

**Returns:**
[EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath)
### setFillData(EmfPlusFillPath value) {#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-}
```
public void setFillData(EmfPlusFillPath value)
```


Gets or sets optional EmfPlusFillPath object (section 2.2.2.17) that specifies the path for filling a custom graphics line cap. This field MUST be present if the CustomLineCapDataFillPath flag is set in the CustomLineCapDataFlags field of the EmfPlusCustomLineCapData object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath) |  |

### getOutlineData() {#getOutlineData--}
```
public EmfPlusLinePath getOutlineData()
```


Gets or sets optional EmfPlusLinePath object (section 2.2.2.26) that specifies the path for outlining a custom graphics line cap. This field MUST be present if the CustomLineCapDataLinePath flag is set in the CustomLineCapDataFlags field of the EmfPlusCustomLineCapData object.

**Returns:**
[EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath)
### setOutlineData(EmfPlusLinePath value) {#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-}
```
public void setOutlineData(EmfPlusLinePath value)
```


Gets or sets optional EmfPlusLinePath object (section 2.2.2.26) that specifies the path for outlining a custom graphics line cap. This field MUST be present if the CustomLineCapDataLinePath flag is set in the CustomLineCapDataFlags field of the EmfPlusCustomLineCapData object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath) |  |

