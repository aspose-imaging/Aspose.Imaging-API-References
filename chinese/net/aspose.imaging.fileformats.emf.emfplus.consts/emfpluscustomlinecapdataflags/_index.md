---
title: "枚举 EmfPlusCustomLineCapDataFlags"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusCustomLineCapDataFlags 枚举。CustomLineCapData 标志指定自定义线帽的数据。这些标志可以组合以指定多个选项。"
type: docs
weight: 4880
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/
---
## EmfPlusCustomLineCapDataFlags enumeration

CustomLineCapData 标志指定自定义线帽的数据。这些标志可以组合以指定多个选项。

```csharp
[Flags]
public enum EmfPlusCustomLineCapDataFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| CustomLineCapDataFillPath | `1` | 如果设置，则必须在 [`EmfPlusCustomLineCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/) 对象的 OptionalData 字段中指定一个 [`EmfPlusFillPath`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath/) 对象，以填充自定义线帽。 |
| CustomLineCapDataLinePath | `2` | 如果设置，则必须在 EmfPlusCustomLineCapData 对象的 OptionalData 字段中指定一个 [`EmfPlusLinePath`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath/) 对象，以描绘自定义线帽。 |

## 备注

自定义图形线帽由 [`EmfPlusCustomLineCap`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecap/) 对象指定。

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


