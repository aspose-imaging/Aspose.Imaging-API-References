---
title: ImageAttributes.SetWrapMode
second_title: Aspose.Imaging for .NET API Reference
description: ImageAttributes method. Sets the wrap mode that is used to decide how to tile a texture across a shape or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling
type: docs
weight: 210
url: /net/aspose.imaging/imageattributes/setwrapmode/
---
## SetWrapMode(WrapMode) {#setwrapmode}

Sets the wrap mode that is used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.

```csharp
public void SetWrapMode(WrapMode mode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mode | WrapMode | An element of [`WrapMode`](../../wrapmode/) that specifies how repeated copies of an image are used to tile an area. |

### See Also

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mode | WrapMode | An element of [`WrapMode`](../../wrapmode/) that specifies how repeated copies of an image are used to tile an area. |
| color | Color | An [`ImageAttributes`](../) object that specifies the color of pixels outside of a rendered image. This color is visible if the mode parameter is set to Clamp and the source rectangle passed to DrawImage is larger than the image itself. |

### See Also

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. A texture is tiled across a shape to fill it in when the texture is smaller than the shape it is filling.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mode | WrapMode | An element of [`WrapMode`](../../wrapmode/) that specifies how repeated copies of an image are used to tile an area. |
| color | Color | A color object that specifies the color of pixels outside of a rendered image. This color is visible if the mode parameter is set to Clamp and the source rectangle passed to DrawImage is larger than the image itself. |
| clamp | Boolean | This parameter has no effect. Set it to false. |

### See Also

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)


