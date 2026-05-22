---
title: "类 EmfCloseFigure"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCloseFigure 类。此记录关闭路径中的打开图形。处理 EMR_CLOSEFIGURE 记录时，必须通过从当前点绘制一条线到图形的第一个点来关闭图形，然后必须使用线段连接样式连接这些线段。如果图形是通过处理 EMR_LINETO 记录而不是 EMR_CLOSEFIGURE 记录来关闭的，则使用端帽来创建拐角而不是连接。EMR_LINETO 在第 2.3.5.13 节中指定。只有在回放设备上下文中存在打开的路径括号时，才应使用 EMR_CLOSEFIGURE 记录。路径中的图形默认是打开的，除非通过处理此记录显式关闭。"
type: docs
weight: 3410
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
## EmfCloseFigure class

此记录关闭路径中的打开图形。处理 EMR_CLOSEFIGURE 记录时必须通过从当前位置信息绘制到图形的第一个点来关闭图形，然后必须使用线段连接样式连接这些线段。如果图形是通过处理 EMR_LINETO 记录而不是 EMR_CLOSEFIGURE 记录来关闭的，则使用端帽来创建拐角而不是连接。EMR_LINETO 在第 2.3.5.13 节中指定。只有在回放设备上下文中存在打开的路径括号时才应使用 EMR_CLOSEFIGURE 记录。路径中的图形默认是打开的，除非通过处理此记录显式关闭。

```csharp
public sealed class EmfCloseFigure : EmfPathBracketRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfCloseFigure](emfclosefigure/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

注意：即使当前点与图形的起始点相同，图形仍可能是打开的。处理 EMR_CLOSEFIGURE 记录后，向路径添加线条或曲线必须开始一个新图形。

### 另请参见

* class [EmfPathBracketRecordType](../emfpathbracketrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


