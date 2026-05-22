---
title: "类 EmfRectangle"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle 类。EMR_RECTANGLE 记录绘制矩形。矩形使用当前笔描边，并使用当前画刷填充。"
type: docs
weight: 4280
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
## EmfRectangle class

该 EMR_RECTANGLE 记录绘制一个矩形。矩形使用当前笔进行描边，使用当前刷子进行填充。

```csharp
public sealed class EmfRectangle : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfRectangle](emfrectangle/#constructor)() | 初始化 `EmfRectangle` 类的新实例。 |
| [EmfRectangle](emfrectangle/#constructor_1)(EmfRecord) | 初始化 `EmfRectangle` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Box](../../aspose.imaging.fileformats.emf.emf.records/emfrectangle/box/) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象，定义于 [MS-WMF] 第 2.2.2.19 节，指定要绘制的包含性矩形。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

Rectangle 不会使用也不会更新当前坐标。如果使用 PS_NULL 笔，则矩形的高度和宽度各减少 1 像素。

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


