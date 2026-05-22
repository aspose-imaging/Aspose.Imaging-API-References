---
title: "Region.Xor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Region 方法。将此 Region 更新为自身与指定 RectangleF 结构的并集减去交集。"
type: docs
weight: 160
url: /zh/net/aspose.imaging/region/xor/
---
## Xor(RectangleF) {#xor_2}

将此 [`Region`](../) 更新为自身与指定 [`RectangleF`](../../rectanglef/) 结构的并集减去交集。

```csharp
public void Xor(RectangleF rect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | RectangleF | 用于与此 [`Region`](../) 进行异或的 [`RectangleF`](../../rectanglef/) 结构。 |

### 另请参见

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## Xor(Rectangle) {#xor_1}

将此 [`Region`](../) 更新为自身与指定的 [`Rectangle`](../../rectangle/) 结构的并集减去交集。

```csharp
public void Xor(Rectangle rect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 用于与此 [`Region`](../) 进行异或的 [`Rectangle`](../../rectangle/) 结构。 |

### 另请参见

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## Xor(GraphicsPath) {#xor}

将此 [`Region`](../) 更新为自身与指定的 [`GraphicsPath`](../../graphicspath/) 的并集减去交集。

```csharp
public void Xor(GraphicsPath path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | GraphicsPath | 用于与此 [`Region`](../) 进行异或的 [`GraphicsPath`](../../graphicspath/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *path* 为 null。 |

### 另请参见

* class [GraphicsPath](../../graphicspath/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## Xor(Region) {#xor_3}

将此 [`Region`](../) 更新为自身与指定的 [`Region`](../) 的并集减去交集。

```csharp
public void Xor(Region region)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | Region | 用于与此 [`Region`](../) 进行异或的 [`Region`](../)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *region* 为 null。 |

### 另请参见

* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)


