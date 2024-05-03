---
title: GraphicsPath.Flatten
second_title: Aspose.Imaging for .NET API Reference
description: GraphicsPath method. Converts each curve in this path into a sequence of connected line segments
type: docs
weight: 100
url: /net/aspose.imaging/graphicspath/flatten/
---
## Flatten() {#flatten}

Converts each curve in this path into a sequence of connected line segments.

```csharp
public void Flatten()
```

### See Also

* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Flatten(Matrix) {#flatten_1}

Applies the specified transform and then converts each curve in this [`GraphicsPath`](../) into a sequence of connected line segments.

```csharp
public void Flatten(Matrix matrix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | Matrix | A [`Matrix`](../../matrix/) by which to transform this [`GraphicsPath`](../) before flattening. |

### See Also

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Converts each curve in this [`GraphicsPath`](../) into a sequence of connected line segments.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | Matrix | A [`Matrix`](../../matrix/) by which to transform this [`GraphicsPath`](../) before flattening. |
| flatness | Single | Specifies the maximum permitted error between the curve and its flattened approximation. A value of 0.25 is the default. Reducing the flatness value will increase the number of line segments in the approximation. |

### See Also

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)


