---
title: "EmfPlusFillClosedCurve.Compressed"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusFillClosedCurve 属性。获取或设置一个值，指示此 EmfPlusFillClosedCurve 是否已压缩。此位指示 PointData 字段是否包含压缩数据。如果设置，PointData 指定坐标空间中使用 16 位整数坐标的绝对位置。如果清除，PointData 指定坐标空间中使用 32 位浮点坐标的绝对位置。  绕行填充操作根据偶奇奇偶规则填充区域。根据此规则，可以通过以下方式确定测试点是在闭合曲线内部还是外部：从测试点画一条线到远离曲线的点。如果该线与曲线相交奇数次，则测试点在曲线内部；否则在曲线外部。  交替填充操作根据非零规则填充区域。根据此规则，可以通过以下方式确定测试点是在闭合曲线内部还是外部：从测试点画一条线到远离曲线的点。统计曲线从左向右穿过测试线的次数，以及从右向左穿过的次数。如果这两个数字相同，则测试点在曲线外部；否则在曲线内部。"
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed/
---
## EmfPlusFillClosedCurve.Compressed property

获取或设置一个值，指示此 [`EmfPlusFillClosedCurve`](../) 是否已压缩。此位指示 PointData 字段是否包含压缩数据。如果设置，PointData 指定坐标空间中使用 16 位整数坐标的绝对位置。如果清除，PointData 指定坐标空间中使用 32 位浮点坐标的绝对位置。 ---------------------- “绕行”填充操作根据“偶奇奇偶”规则填充区域。根据此规则，可以通过以下方式确定测试点是在闭合曲线内部还是外部：从测试点画一条线到远离曲线的点。如果该线与曲线相交奇数次，则测试点在曲线内部；否则在曲线外部。 --------------------- “交替”填充操作根据“非零”规则填充区域。根据此规则，可以通过以下方式确定测试点是在闭合曲线内部还是外部：从测试点画一条线到远离曲线的点。统计曲线从左向右穿过测试线的次数，以及从右向左穿过的次数。如果这两个数字相同，则测试点在曲线外部；否则在曲线内部。

```csharp
public bool Compressed { get; set; }
```

### Property Value

`true` 表示已压缩；否则为 `false`。

### 另请参见

* class [EmfPlusFillClosedCurve](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusfillclosedcurve/)
* assembly [Aspose.Imaging](../../../)


