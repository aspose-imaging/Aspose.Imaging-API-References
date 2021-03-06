---
title: EmfRectangle
second_title: Aspose.Imaging for .NET API 参考
description: EMR_RECTANGLE 记录绘制一个矩形矩形使用当前笔 勾勒出轮廓并使用当前画笔填充
type: docs
weight: 4160
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
## EmfRectangle class

EMR_RECTANGLE 记录绘制一个矩形。矩形使用当前笔 勾勒出轮廓，并使用当前画笔填充。

```csharp
public sealed class EmfRectangle : EmfDrawingRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfRectangle](emfrectangle#constructor)() | 初始化[`EmfRectangle`](../emfrectangle)类的新实例。 |
| [EmfRectangle](emfrectangle#constructor_1)(EmfRecord) | 初始化[`EmfRectangle`](../emfrectangle)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Box](../../aspose.imaging.fileformats.emf.emf.records/emfrectangle/box) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象，在 [MS-WMF] 第 2.2.2.19 节中指定，其中 指定包含-包含矩形来绘制。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 评论

Rectangle 既不使用也不更新当前位置。 如果使用 PS_NULL 笔，则矩形的尺寸在高度上减少 1 个像素，在宽度上减少 1 个像素 。

### 也可以看看

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
