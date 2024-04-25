---
title: EmfPlusImageAttributes
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusImageAttributes object specifies how bitmap image colors are manipulated during rendering.
type: docs
weight: 48
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImageAttributes extends EmfPlusGraphicsObjectType
```

The EmfPlusImageAttributes object specifies how bitmap image colors are manipulated during rendering.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Gets or sets a 32-bit unsigned integer that specifies how to handle edge conditions with a value from the WrapMode enumeration (section 2.1.1.34). |
| [setWrapMode(int value)](#setWrapMode-int-) | Gets or sets a 32-bit unsigned integer that specifies how to handle edge conditions with a value from the WrapMode enumeration (section 2.1.1.34). |
| [getClampArgb32Color()](#getClampArgb32Color--) | Gets or sets EmfPlusARGB (section 2.2.2.1) object that specifies the edge color to use when the WrapMode value is WrapModeClamp. |
| [setClampArgb32Color(int value)](#setClampArgb32Color-int-) | Gets or sets EmfPlusARGB (section 2.2.2.1) object that specifies the edge color to use when the WrapMode value is WrapModeClamp. |
| [getObjectClamp()](#getObjectClamp--) | Gets or sets 32-bit signed integer that specifies the object clamping behavior. |
| [setObjectClamp(int value)](#setObjectClamp-int-) | Gets or sets 32-bit signed integer that specifies the object clamping behavior. |
### EmfPlusImageAttributes() {#EmfPlusImageAttributes--}
```
public EmfPlusImageAttributes()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Gets or sets a 32-bit unsigned integer that specifies how to handle edge conditions with a value from the WrapMode enumeration (section 2.1.1.34).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how to handle edge conditions with a value from the WrapMode enumeration (section 2.1.1.34).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getClampArgb32Color() {#getClampArgb32Color--}
```
public int getClampArgb32Color()
```


Gets or sets EmfPlusARGB (section 2.2.2.1) object that specifies the edge color to use when the WrapMode value is WrapModeClamp. This color is visible when the source rectangle processed by an EmfPlusDrawImage (section 2.3.4.8) record is larger than the image itself.

**Returns:**
int
### setClampArgb32Color(int value) {#setClampArgb32Color-int-}
```
public void setClampArgb32Color(int value)
```


Gets or sets EmfPlusARGB (section 2.2.2.1) object that specifies the edge color to use when the WrapMode value is WrapModeClamp. This color is visible when the source rectangle processed by an EmfPlusDrawImage (section 2.3.4.8) record is larger than the image itself.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getObjectClamp() {#getObjectClamp--}
```
public int getObjectClamp()
```


Gets or sets 32-bit signed integer that specifies the object clamping behavior. It is not used until this object is applied to an image being drawn. This value MUST be one of the values defined in the following table.

**Returns:**
int
### setObjectClamp(int value) {#setObjectClamp-int-}
```
public void setObjectClamp(int value)
```


Gets or sets 32-bit signed integer that specifies the object clamping behavior. It is not used until this object is applied to an image being drawn. This value MUST be one of the values defined in the following table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

