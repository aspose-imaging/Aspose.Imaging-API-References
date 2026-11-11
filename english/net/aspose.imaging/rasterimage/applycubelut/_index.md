---
title: RasterImage.ApplyCubeLut
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Applies a 3D cube lookup table LUT loaded from the specified file to the pixels within the specified bounds of the image
type: docs
weight: 230
url: /net/aspose.imaging/rasterimage/applycubelut/
---
## ApplyCubeLut(string, Rectangle) {#applycubelut_5}

Applies a 3D cube lookup table (LUT) loaded from the specified file to the pixels within the specified bounds of the image.

```csharp
public void ApplyCubeLut(string fileName, Rectangle bounds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path to the `.cube` file containing the lookup table. |
| bounds | Rectangle | The rectangular region of the image to which the lookup table is applied. Pixels outside this region are not modified. |

## Remarks

The LUT file is opened for reading and the resulting stream is disposed automatically after the operation has completed.

### See Also

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## ApplyCubeLut(string) {#applycubelut_4}

Applies a 3D cube lookup table (LUT) loaded from the specified file to the entire image.

```csharp
public void ApplyCubeLut(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path to the `.cube` file containing the lookup table. |

## Remarks

The lookup table is applied to !:Bounds, causing all pixels within the image bounds to be processed.

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## ApplyCubeLut(Stream) {#applycubelut_2}

Applies a 3D cube lookup table (LUT) loaded from the specified stream to the entire image.

```csharp
public void ApplyCubeLut(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream containing the `.cube` lookup table data. |

## Remarks

The lookup table is applied to !:Bounds, causing all pixels within the image bounds to be processed. The stream is used to load the lookup table and is not explicitly disposed by this method.

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## ApplyCubeLut(Stream, Rectangle) {#applycubelut_3}

Applies a 3D cube lookup table (LUT) loaded from the specified stream to the pixels within the specified bounds of the image.

```csharp
public void ApplyCubeLut(Stream stream, Rectangle bounds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream containing the `.cube` lookup table data. |
| bounds | Rectangle | The rectangular region of the image to which the lookup table is applied. Pixels outside this region are not modified. |

## Remarks

The lookup table is parsed from the supplied stream by [`Load`](../../../aspose.imaging.lut.cubelut/cubelut/load/) and then applied to the specified image region. The stream is not explicitly disposed by this method.

### See Also

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## ApplyCubeLut(CubeLut, Rectangle) {#applycubelut_1}

Applies the specified 3D cube lookup table (LUT) to the pixels within the specified bounds of the image.

```csharp
public virtual void ApplyCubeLut(CubeLut cubeLut, Rectangle bounds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cubeLut | CubeLut | The [`CubeLut`](../../../aspose.imaging.lut.cubelut/cubelut/) instance containing the color transformation to apply to the image pixels. |
| bounds | Rectangle | The rectangular region of the image to which the lookup table is applied. Pixels outside this region are not modified. |

## Remarks

Image pixels within the specified region are loaded in ARGB32 format and transformed in place using the LUT processor. The transformed pixels are then written back to the corresponding image region.

### See Also

* class [CubeLut](../../../aspose.imaging.lut.cubelut/cubelut/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## ApplyCubeLut(CubeLut) {#applycubelut}

Applies the specified 3D cube lookup table (LUT) to the entire image.

```csharp
public void ApplyCubeLut(CubeLut cubeLut)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cubeLut | CubeLut | The [`CubeLut`](../../../aspose.imaging.lut.cubelut/cubelut/) instance containing the color transformation to apply to the image pixels. |

## Remarks

The lookup table is applied to !:Bounds, causing all pixels within the image bounds to be processed.

### See Also

* class [CubeLut](../../../aspose.imaging.lut.cubelut/cubelut/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


