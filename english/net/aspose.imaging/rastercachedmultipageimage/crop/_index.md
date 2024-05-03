---
title: RasterCachedMultipageImage.Crop
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedMultipageImage method. Cropping the image
type: docs
weight: 210
url: /net/aspose.imaging/rastercachedmultipageimage/crop/
---
## Crop(Rectangle) {#crop}

Cropping the image.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle. |

### See Also

* struct [Rectangle](../../rectangle/)
* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Crop image with shifts.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | Int32 | The left shift. |
| rightShift | Int32 | The right shift. |
| topShift | Int32 | The top shift. |
| bottomShift | Int32 | The bottom shift. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Rectangle incorrect. - rectangle or Rectangle must be contained in the image bounds. - rectangle |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | Can't crop image. Frame index: " + frameIndex or Can't crop image. |

### See Also

* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)


