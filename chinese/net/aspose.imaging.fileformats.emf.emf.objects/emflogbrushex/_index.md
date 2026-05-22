---
title: "类 EmfLogBrushEx"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx 类。LogBrushEx 对象定义了设备无关画刷的样式、颜色和图案。"
type: docs
weight: 3110
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
## EmfLogBrushEx class

LogBrushEx 对象定义了设备无关画刷的样式、颜色和图案。

```csharp
public sealed class EmfLogBrushEx : EmfObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfLogBrushEx](emflogbrushex/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Argb32ColorRef](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/argb32colorref/) { get; set; } | 获取或设置一个 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），用于指定颜色。此字段的解释取决于 BrushStyle 的值，如下表所述。 |
| [BrushHatch](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/brushhatch/) { get; set; } | 获取或设置一个包含画刷填充数据的 32 位无符号字段。其解释取决于 BrushStyle 的值， |
| [BrushStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/brushstyle/) { get; set; } | 获取或设置一个指定画刷样式的 32 位无符号整数。该值必须是 WMF BrushStyle 枚举中的一个成员（[MS-WMF] 第 2.1.1.4 节）。本结构支持的样式值在本节后面列出。应使用 BS_NULL 样式来指定没有效果的画刷。 |

### 另请参见

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


