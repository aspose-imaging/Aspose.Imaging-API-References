---
title: "Pen.CompoundArray"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Pen 属性。获取或设置指定复合笔的值数组。复合笔绘制由平行线和间隔组成的复合线。"
type: docs
weight: 50
url: /zh/net/aspose.imaging/pen/compoundarray/
---
## Pen.CompoundArray property

获取或设置指定复合笔的值数组。复合笔绘制由平行线和间隔组成的复合线。

```csharp
public float[] CompoundArray { get; set; }
```

### Property Value

一个实数数组，用于指定复合数组。数组中的元素必须按递增顺序排列，且不小于 0，且不大于 1。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | `CompoundArray` 属性设置在不可变的 [`Pen`](../) 上，例如由 [`Pen`](../) 类返回的实例。 |

### 另请参见

* class [Pen](../)
* namespace [Aspose.Imaging](../../pen/)
* assembly [Aspose.Imaging](../../../)


