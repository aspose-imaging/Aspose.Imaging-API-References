---
title: EmfVertexData
second_title: Aspose.Imaging for Java API Reference
description: Objects that specify the vertexes of either rectangles or triangles and the colors that correspond to them.
type: docs
weight: 155
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
**Inheritance:**
java.lang.Object
```
public final class EmfVertexData
```

Objects that specify the vertexes of either rectangles or triangles and the colors that correspond to them.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfVertexData()](#EmfVertexData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getVertexObjects()](#getVertexObjects--) | Gets or sets an array of nVer TriVertex objects (section 2.2.26). |
| [setVertexObjects(EmfTriVertex[] value)](#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---) | Gets or sets an array of nVer TriVertex objects (section 2.2.26). |
| [getVertexIndexes()](#getVertexIndexes--) | Gets or sets an array of nTri GradientRectangle objects (section 2.2.7) or GradientTriangle objects (section 2.2.8), depending on the value of the ulMode field. |
| [setVertexIndexes(EmfGradientRectangle[] value)](#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---) | Gets or sets an array of nTri GradientRectangle objects (section 2.2.7) or GradientTriangle objects (section 2.2.8), depending on the value of the ulMode field. |
| [getVertexPadding()](#getVertexPadding--) | Gets or sets an optional variable-length array of nTri times four bytes that MUST be present if the value of the ulMode field indicates GradientRectangle objects (section 2.2.7). |
| [setVertexPadding(byte[] value)](#setVertexPadding-byte---) | Gets or sets an optional variable-length array of nTri times four bytes that MUST be present if the value of the ulMode field indicates GradientRectangle objects (section 2.2.7). |
### EmfVertexData() {#EmfVertexData--}
```
public EmfVertexData()
```


### getVertexObjects() {#getVertexObjects--}
```
public EmfTriVertex[] getVertexObjects()
```


Gets or sets an array of nVer TriVertex objects (section 2.2.26). Each object specifies the position and color of a vertex of either a rectangle or a triangle, depending on the value of the ulMode field.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex[]
### setVertexObjects(EmfTriVertex[] value) {#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---}
```
public void setVertexObjects(EmfTriVertex[] value)
```


Gets or sets an array of nVer TriVertex objects (section 2.2.26). Each object specifies the position and color of a vertex of either a rectangle or a triangle, depending on the value of the ulMode field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfTriVertex\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftrivertex) |  |

### getVertexIndexes() {#getVertexIndexes--}
```
public EmfGradientRectangle[] getVertexIndexes()
```


Gets or sets an array of nTri GradientRectangle objects (section 2.2.7) or GradientTriangle objects (section 2.2.8), depending on the value of the ulMode field. Each object specifies indexes into the array of TriVertex objects in the VertexObjects field.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle[]
### setVertexIndexes(EmfGradientRectangle[] value) {#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---}
```
public void setVertexIndexes(EmfGradientRectangle[] value)
```


Gets or sets an array of nTri GradientRectangle objects (section 2.2.7) or GradientTriangle objects (section 2.2.8), depending on the value of the ulMode field. Each object specifies indexes into the array of TriVertex objects in the VertexObjects field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfGradientRectangle\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle) |  |

### getVertexPadding() {#getVertexPadding--}
```
public byte[] getVertexPadding()
```


Gets or sets an optional variable-length array of nTri times four bytes that MUST be present if the value of the ulMode field indicates GradientRectangle objects (section 2.2.7). If the value of the ulMode field indicates GradientTriangle objects (section 2.2.8), no VertexPadding is present. This field MUST be ignored.

**Returns:**
byte[]
### setVertexPadding(byte[] value) {#setVertexPadding-byte---}
```
public void setVertexPadding(byte[] value)
```


Gets or sets an optional variable-length array of nTri times four bytes that MUST be present if the value of the ulMode field indicates GradientRectangle objects (section 2.2.7). If the value of the ulMode field indicates GradientTriangle objects (section 2.2.8), no VertexPadding is present. This field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

