---
title: "类 EmfVertexData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfVertexData 类。对象用于指定矩形或三角形的顶点以及对应的颜色"
type: docs
weight: 4770
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
## EmfVertexData class

指定矩形或三角形顶点及其对应颜色的对象。

```csharp
public sealed class EmfVertexData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfVertexData](emfvertexdata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [VertexIndexes](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexindexes/) { get; set; } | 获取或设置一个 nTri GradientRectangle 对象数组（第 2.2.7 节）或 GradientTriangle 对象数组（第 2.2.8 节），取决于 ulMode 字段的值。每个对象指定 VertexObjects 字段中 TriVertex 对象数组的索引。 |
| [VertexObjects](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexobjects/) { get; set; } | 获取或设置一个 nVer TriVertex 对象数组（第 2.2.26 节）。每个对象指定矩形或三角形的顶点位置和颜色，取决于 ulMode 字段的值。 |
| [VertexPadding](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexpadding/) { get; set; } | 获取或设置一个可选的可变长度数组，其长度为 nTri × 4 字节；如果 ulMode 字段的值指示 GradientRectangle 对象（第 2.2.7 节），则此数组必须存在。如果 ulMode 字段的值指示 GradientTriangle 对象（第 2.2.8 节），则不存在 VertexPadding。此字段必须被忽略。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


