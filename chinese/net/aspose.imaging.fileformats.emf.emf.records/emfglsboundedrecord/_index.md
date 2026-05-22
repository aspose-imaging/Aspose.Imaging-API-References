---
title: "类 EmfGlsBoundedRecord"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfGlsBoundedRecord 类。EMR_GLSBOUNDEDRECORD 记录指定一个带有输出边界矩形的 OpenGL 函数。"
type: docs
weight: 3840
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
## EmfGlsBoundedRecord class

EMR_GLSBOUNDEDRECORD 记录指定一个带有输出边界矩形的 OpenGL 函数。

```csharp
public sealed class EmfGlsBoundedRecord : EmfOpenGlRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfGlsBoundedRecord](emfglsboundedrecord/)(EmfRecord) | 初始化 `EmfGlsBoundedRecord` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/bounds/) { get; set; } | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），定义以设备单位表示的边界矩形，用于执行 OpenGL 函数产生的输出。 |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/cbdata/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 Data 字段的大小（以字节为单位）。如果该值为零，则此记录不附加任何数据。 |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/data/) { get; set; } | 获取或设置一个可选的长度为 cbData 的字节数组，指定 OpenGL 函数的数据。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfOpenGlRecordType](../emfopenglrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


