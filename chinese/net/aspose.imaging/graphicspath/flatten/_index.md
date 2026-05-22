---
title: "GraphicsPath.Flatten"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GraphicsPath 方法。将此路径中的每条曲线转换为一系列相连的线段"
type: docs
weight: 100
url: /zh/net/aspose.imaging/graphicspath/flatten/
---
## Flatten() {#flatten}

将此路径中的每条曲线转换为一系列相连的线段。

```csharp
public void Flatten()
```

### 另请参见

* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Flatten(Matrix) {#flatten_1}

应用指定的变换，然后将此 [`GraphicsPath`](../) 中的每条曲线转换为一系列相连的线段。

```csharp
public void Flatten(Matrix matrix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | Matrix | 用于在展平之前转换此 [`GraphicsPath`](../) 的 [`Matrix`](../../matrix/)。 |

### 另请参见

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

将此 [`GraphicsPath`](../) 中的每条曲线转换为一系列相连的线段。

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | Matrix | 用于在展平之前转换此 [`GraphicsPath`](../) 的 [`Matrix`](../../matrix/)。 |
| 平滑度 | 单精度 | 指定曲线与其展平近似之间允许的最大误差。默认值为 0.25。降低平整度值会增加近似中的线段数量。 |

### 另请参见

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)


