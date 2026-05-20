---
title: "EmfVertexData"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "指定矩形或三角形的顶点及其对应颜色的对象。"
type: docs
weight: 155
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
**Inheritance:**
java.lang.Object
```
public final class EmfVertexData
```

指定矩形或三角形的顶点及其对应颜色的对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfVertexData()](#EmfVertexData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVertexObjects()](#getVertexObjects--) | 获取或设置 nVer TriVertex 对象的数组（第 2.2.26 节）。 |
| [setVertexObjects(EmfTriVertex[] value)](#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---) | 获取或设置 nVer TriVertex 对象的数组（第 2.2.26 节）。 |
| [getVertexIndexes()](#getVertexIndexes--) | 获取或设置 nTri GradientRectangle 对象（第 2.2.7 节）或 GradientTriangle 对象（第 2.2.8 节）的数组，取决于 ulMode 字段的值。 |
| [setVertexIndexes(EmfGradientRectangle[] value)](#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---) | 获取或设置 nTri GradientRectangle 对象（第 2.2.7 节）或 GradientTriangle 对象（第 2.2.8 节）的数组，取决于 ulMode 字段的值。 |
| [getVertexPadding()](#getVertexPadding--) | 获取或设置一个可选的可变长度数组，其长度为 nTri 乘以四字节，如果 ulMode 字段的值指示 GradientRectangle 对象（第 2.2.7 节），则该数组必须存在。 |
| [setVertexPadding(byte[] value)](#setVertexPadding-byte---) | 获取或设置一个可选的可变长度数组，其长度为 nTri 乘以四字节，如果 ulMode 字段的值指示 GradientRectangle 对象（第 2.2.7 节），则该数组必须存在。 |
### EmfVertexData() {#EmfVertexData--}
```
public EmfVertexData()
```


### getVertexObjects() {#getVertexObjects--}
```
public EmfTriVertex[] getVertexObjects()
```


获取或设置 nVer TriVertex 对象（第 2.2.26 节）的数组。每个对象指定矩形或三角形的顶点位置和颜色，取决于 ulMode 字段的值。

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex[]
### setVertexObjects(EmfTriVertex[] value) {#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---}
```
public void setVertexObjects(EmfTriVertex[] value)
```


获取或设置 nVer TriVertex 对象（第 2.2.26 节）的数组。每个对象指定矩形或三角形的顶点位置和颜色，取决于 ulMode 字段的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfTriVertex\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftrivertex) |  |

### getVertexIndexes() {#getVertexIndexes--}
```
public EmfGradientRectangle[] getVertexIndexes()
```


获取或设置 nTri GradientRectangle 对象（第 2.2.7 节）或 GradientTriangle 对象（第 2.2.8 节）的数组，取决于 ulMode 字段的值。每个对象指定在 VertexObjects 字段中 TriVertex 对象数组的索引。

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle[]
### setVertexIndexes(EmfGradientRectangle[] value) {#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---}
```
public void setVertexIndexes(EmfGradientRectangle[] value)
```


获取或设置 nTri GradientRectangle 对象（第 2.2.7 节）或 GradientTriangle 对象（第 2.2.8 节）的数组，取决于 ulMode 字段的值。每个对象指定在 VertexObjects 字段中 TriVertex 对象数组的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfGradientRectangle\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle) |  |

### getVertexPadding() {#getVertexPadding--}
```
public byte[] getVertexPadding()
```


获取或设置一个可选的可变长度数组，其长度为 nTri 乘以四字节，如果 ulMode 字段的值指示 GradientRectangle 对象（第 2.2.7 节），则该数组必须存在。如果 ulMode 字段的值指示 GradientTriangle 对象（第 2.2.8 节），则不存在 VertexPadding。此字段必须被忽略。

**Returns:**
byte[]
### setVertexPadding(byte[] value) {#setVertexPadding-byte---}
```
public void setVertexPadding(byte[] value)
```


获取或设置一个可选的可变长度数组，其长度为 nTri 乘以四字节，如果 ulMode 字段的值指示 GradientRectangle 对象（第 2.2.7 节），则该数组必须存在。如果 ulMode 字段的值指示 GradientTriangle 对象（第 2.2.8 节），则不存在 VertexPadding。此字段必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

