---
title: "EmfPlusDrawLines.Relative"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusDrawLines 属性。获取或设置一个值，指示此 EmfPlusDrawClosedCurve 是否为相对。此位指示 PointData 字段是指定相对位置还是绝对位置。若设置，PointData 中的每个元素指定相对于数组中前一个元素位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置坐标为 0,0。若未设置，PointData 根据 C 标志指定绝对位置。注意：如果设置了此标志，上面的 Compressed 标志未定义，必须被忽略。"
type: docs
weight: 60
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/relative/
---
## EmfPlusDrawLines.Relative property

获取或设置一个值，指示此 [`EmfPlusDrawClosedCurve`](../../emfplusdrawclosedcurve/) 是否为相对的。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，则 PointData 中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置坐标为 (0,0)。如果未设置，PointData 根据 C 标志指定绝对位置。注意：如果此标志被设置，上面的 Compressed 标志未定义，必须被忽略

```csharp
public bool Relative { get; set; }
```

### Property Value

`true` 表示相对；否则为 `false`。

### 另请参见

* class [EmfPlusDrawLines](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawlines/)
* assembly [Aspose.Imaging](../../../)


