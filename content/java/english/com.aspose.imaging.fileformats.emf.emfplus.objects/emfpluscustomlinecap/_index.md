---
title: EmfPlusCustomLineCap
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusCustomLineCap object specifies the shape to use at the ends of a line drawn by a graphics pen.
type: docs
weight: 34
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusCustomLineCap extends EmfPlusGraphicsObjectType
```

The EmfPlusCustomLineCap object specifies the shape to use at the ends of a line drawn by a graphics pen.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusCustomLineCap()](#EmfPlusCustomLineCap--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Gets or sets a 32-bit signed integer that specifies the type of custom line cap object, which determines the contents of the CustomLineCapData field. |
| [setType(int value)](#setType-int-) | Gets or sets a 32-bit signed integer that specifies the type of custom line cap object, which determines the contents of the CustomLineCapData field. |
| [getCustomLineCapData()](#getCustomLineCapData--) | Gets or sets Variable-length data that defines the custom line cap data object specified in the Type field. |
| [setCustomLineCapData(EmfPlusCustomBaseLineCap value)](#setCustomLineCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap-) | Gets or sets Variable-length data that defines the custom line cap data object specified in the Type field. |
### EmfPlusCustomLineCap() {#EmfPlusCustomLineCap--}
```
public EmfPlusCustomLineCap()
```


### getType() {#getType--}
```
public int getType()
```


Gets or sets a 32-bit signed integer that specifies the type of custom line cap object, which determines the contents of the CustomLineCapData field.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Gets or sets a 32-bit signed integer that specifies the type of custom line cap object, which determines the contents of the CustomLineCapData field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCustomLineCapData() {#getCustomLineCapData--}
```
public EmfPlusCustomBaseLineCap getCustomLineCapData()
```


Gets or sets Variable-length data that defines the custom line cap data object specified in the Type field. The content and format of the data can be different for every custom line cap type.

**Returns:**
[EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
### setCustomLineCapData(EmfPlusCustomBaseLineCap value) {#setCustomLineCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap-}
```
public void setCustomLineCapData(EmfPlusCustomBaseLineCap value)
```


Gets or sets Variable-length data that defines the custom line cap data object specified in the Type field. The content and format of the data can be different for every custom line cap type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap) |  |

