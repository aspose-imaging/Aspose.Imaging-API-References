---
title: Region.Complement
second_title: Aspose.Imaging for .NET API Reference
description: Region method. Updates this Region to contain the portion of the specified RectangleF structure that does not intersect with this Region
type: docs
weight: 20
url: /net/aspose.imaging/region/complement/
---
## Complement(RectangleF) {#complement_2}

Updates this [`Region`](../) to contain the portion of the specified [`RectangleF`](../../rectanglef/) structure that does not intersect with this [`Region`](../).

```csharp
public void Complement(RectangleF rect)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | RectangleF | The [`RectangleF`](../../rectanglef/) structure to complement this [`Region`](../). |

### See Also

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## Complement(Rectangle) {#complement_1}

Updates this [`Region`](../) to contain the portion of the specified [`Rectangle`](../../rectangle/) structure that does not intersect with this [`Region`](../).

```csharp
public void Complement(Rectangle rect)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The [`Rectangle`](../../rectangle/) structure to complement this [`Region`](../). |

### See Also

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## Complement(GraphicsPath) {#complement}

Updates this [`Region`](../) to contain the portion of the specified [`GraphicsPath`](../../graphicspath/) that does not intersect with this [`Region`](../).

```csharp
public void Complement(GraphicsPath path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | GraphicsPath | The [`GraphicsPath`](../../graphicspath/) to complement this [`Region`](../). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *path* isnull. |

### See Also

* class [GraphicsPath](../../graphicspath/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## Complement(Region) {#complement_3}

Updates this [`Region`](../) to contain the portion of the specified [`Region`](../) that does not intersect with this [`Region`](../).

```csharp
public void Complement(Region region)
```

| Parameter | Type | Description |
| --- | --- | --- |
| region | Region | The [`Region`](../) object to complement this [`Region`](../) object. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *region* isnull. |

### See Also

* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)


