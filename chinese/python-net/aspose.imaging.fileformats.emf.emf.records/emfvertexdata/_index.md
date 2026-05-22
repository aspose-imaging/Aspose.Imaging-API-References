---
title: "EmfVertexData 类"
type: docs
weight: 1460
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---

**Summary:** Objects that specify the vertexes of either rectangles or triangles and <br/>            the colors that correspond to them.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfVertexData

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfVertexData()](#EmfVertexData__1) | 初始化一个新的 EmfVertexData 类实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| vertex_indexes | [EmfGradientRectangle[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/) | r/w | 获取或设置一个 nTri GradientRectangle 对象数组（第 2.2.7 节）或 <br/>            GradientTriangle 对象数组（第 2.2.8 节），取决于 ulMode 字段的值。<br/>            每个对象指定 VertexObjects 字段中 TriVertex 对象数组的索引。 |
| vertex_objects | [EmfTriVertex[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftrivertex/) | r/w | 获取或设置一个 nVer TriVertex 对象数组（第 2.2.26 节）。每个<br/>            对象指定矩形或三角形的顶点位置和颜色，<br/>            取决于 ulMode 字段的值。 |
| vertex_padding | System.Byte | r/w | 获取或设置一个可选的可变长度数组，长度为 nTri × 四字节 <br/>            如果 ulMode 字段的值指示 GradientRectangle 对象（第 2.2.7 节），则此数组必须存在。<br/>            如果 ulMode 字段的值指示 GradientTriangle 对象（第 2.2.8 节），则不存在 VertexPadding。此字段必须被忽略。 |


### Constructor: EmfVertexData() {#EmfVertexData__1}


```
 EmfVertexData() 
```

初始化一个新的 EmfVertexData 类实例

