---
title: "类 EmfChord"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfChord 类。EMR_CHORD 记录指定一个弦，该弦是由椭圆与称为割线的线段相交形成的区域。弦使用当前画笔描边，并使用当前画刷填充。"
type: docs
weight: 3390
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfchord/
---
## EmfChord class

EMR_CHORD 记录指定弦线，即由椭圆与一条线段（称为割线）相交形成的区域。弦线使用当前笔进行描边，并使用当前画刷进行填充。

```csharp
public sealed class EmfChord : EmfDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfChord](emfchord/#constructor)() | 初始化 `EmfChord` 类的新实例。 |
| [EmfChord](emfchord/#constructor_1)(EmfRecord) | 初始化 `EmfChord` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Box](../../aspose.imaging.fileformats.emf.emf.records/emfchord/box/) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定包含式的边界矩形。 |
| [End](../../aspose.imaging.fileformats.emf.emf.records/emfchord/end/) { get; set; } | 获取或设置一个 64 位 WMF PointL 对象，该对象指定定义弦结束端的径向的逻辑坐标。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Start](../../aspose.imaging.fileformats.emf.emf.records/emfchord/start/) { get; set; } | 获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定定义弦起始端的径向的逻辑坐标。 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


