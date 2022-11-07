---
title: Layer
second_title: Aspose.Imaging for Java API Reference
description: Represents Photoshop text layer.
type: docs
weight: 11
url: /java/com.aspose.imaging.xmp.schemas.photoshop/layer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

Represents Photoshop text layer.
## Constructors

| Constructor | Description |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | Initializes a new instance of the `Layer` class. |
| [Layer()](#Layer--) | Initializes a new instance of the `Layer` class. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets or sets the name of the text layer. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the name of the text layer. |
| [getText()](#getText--) | Gets or sets the text content of the layer. |
| [setText(String value)](#setText-java.lang.String-) | Gets or sets the text content of the layer. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns string contained value in XMP format. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified `System.Object`, is equal to this instance. |
| [isEquals(Layer other)](#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-) | Indicates whether the current object is equal to another object of the same type. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


Initializes a new instance of the `Layer` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layerName | java.lang.String | Name of the layer. |
| layerText | java.lang.String | The layer text. |

### Layer() {#Layer--}
```
public Layer()
```


Initializes a new instance of the `Layer` class.

### getName() {#getName--}
```
public String getName()
```


Gets or sets the name of the text layer.

Value: The name of the text layer.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Gets or sets the name of the text layer.

Value: The name of the text layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getText() {#getText--}
```
public String getText()
```


Gets or sets the text content of the layer.

Value: The text content of the layer.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Gets or sets the text content of the layer.

Value: The text content of the layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returns string contained value in XMP format.

**Returns:**
java.lang.String - Returns string contained value in XMP format.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified `System.Object`, is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `System.Object` to compare with this instance. |

**Returns:**
boolean - `true` if the specified `System.Object` is equal to this instance; otherwise, `false`.
### isEquals(Layer other) {#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Layer](../../com.aspose.imaging.xmp.schemas.photoshop/layer) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the `other` parameter; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
