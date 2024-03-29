---
title: EmfLogBrushEx
second_title: Aspose.Imaging for .NET API 参考
description: LogBrushEx 对象定义与设备无关的画笔的样式颜色和图案
type: docs
weight: 3020
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
## EmfLogBrushEx class

LogBrushEx 对象定义与设备无关的画笔的样式、颜色和图案。

```csharp
public sealed class EmfLogBrushEx : EmfObject
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfLogBrushEx](emflogbrushex)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Argb32ColorRef](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/argb32colorref) { get; set; } | 获取或设置指定 a 颜色的 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节）。该字段的解释取决于BrushStyle的值，如下表 中的解释。 |
| [BrushHatch](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/brushhatch) { get; set; } | 获取或设置一个包含画笔阴影数据的 32 位无符号字段。它的 解释取决于BrushStyle的值， |
| [BrushStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/brushstyle) { get; set; } | 获取或设置指定画笔样式的 32 位无符号整数。值必须 是来自 WMF BrushStyle 枚举的枚举（[MS-WMF] 第 2.1.1.4 节）。此结构中支持的样式 值在本节后面列出。 BS_NULL 样式 应该用于指定没有效果的画笔。 |

### 也可以看看

* class [EmfObject](../emfobject)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
