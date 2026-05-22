---
title: "EmfPlusFillClosedCurve.Relative"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusFillClosedCurve 属性。获取或设置一个值，指示此 EmfPlusFillClosedCurve 是否为相对。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，PointData 中的每个元素指定相对于数组中前一个元素位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置坐标为 00。如果清除，PointData 根据 C 标志指定绝对位置。注意：如果设置此标志，上面的 C 标志未定义，必须被忽略。"
type: docs
weight: 60
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative/
---
## EmfPlusFillClosedCurve.Relative property

获取或设置一个值，指示此 [`EmfPlusFillClosedCurve`](../) 是否为相对。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，PointData 中的每个元素指定相对于数组中前一个元素位置的坐标空间位置。在 PointData 的第一个元素的情况下，假定前一个位置坐标为 (0,0)。如果清除，PointData 根据 C 标志指定绝对位置。注意：如果设置此标志，上面的 C 标志 (above) 未定义，必须被忽略。

```csharp
public bool Relative { get; set; }
```

### Property Value

`true` 表示相对；否则为 `false`。

### 另请参见

* class [EmfPlusFillClosedCurve](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusfillclosedcurve/)
* assembly [Aspose.Imaging](../../../)


