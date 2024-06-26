---
title: TgaImage.Crop
second_title: Aspose.Imaging for .NET API Reference
description: TgaImage method. Crop the image to a specified region. This method allows you to define a rectangular area within the image to retain discarding the rest. This operation is useful for focusing on specific content within the image or removing unwanted portions
type: docs
weight: 310
url: /net/aspose.imaging.fileformats.tga/tgaimage/crop/
---
## Crop(Rectangle) {#crop}

Crop the image to a specified region. This method allows you to define a rectangular area within the image to retain, discarding the rest. This operation is useful for focusing on specific content within the image or removing unwanted portions.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle. |

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Crop the image by specifying shifts for the left, right, top, and bottom boundaries. This method allows you to trim the image by moving its boundaries independently along the horizontal and vertical axes. By adjusting these shifts, you can precisely control which portions of the image to retain, effectively cropping it to the desired dimensions.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | Int32 | The left shift. |
| rightShift | Int32 | The right shift. |
| topShift | Int32 | The top shift. |
| bottomShift | Int32 | The bottom shift. |

### See Also

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


