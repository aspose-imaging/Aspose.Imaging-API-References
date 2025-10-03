---
title: ApngImage.InsertFrame
second_title: Aspose.Imaging for .NET API Reference
description: ApngImage method. Effortlessly insert a new frame into your frame collection at the specified with this intuitive method. Ideal for developers seeking precise control over the arrangement of frames in their animations of multiframe images. A new frame will be created according to the size of the current image
type: docs
weight: 230
url: /net/aspose.imaging.fileformats.apng/apngimage/insertframe/
---
## InsertFrame(int) {#insertframe}

Effortlessly insert a new frame into your frame collection at the specified with this intuitive method. Ideal for developers seeking precise control over the arrangement of frames in their animations of multi-frame images. A new frame will be created according to the size of the current image.

```csharp
public ApngFrame InsertFrame(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The index. |

### Return Value

The newly created APNG frame.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* is less than 0. or *index* is greater than [`PageCount`](../pagecount/). |

### See Also

* class [ApngFrame](../../apngframe/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## InsertFrame(int, RasterImage) {#insertframe_1}

Inserts new frame into the own frame collection at the specified index. The contents of the new frame will be filled from the specified image.

```csharp
public void InsertFrame(int index, RasterImage frameImage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The index. |
| frameImage | RasterImage | The frame image. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* is less than 0. or *index* is greater than [`PageCount`](../pagecount/). |
| ArgumentNullException | frameImage is null. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## InsertFrame(int, RasterImage, uint) {#insertframe_2}

Inserts new frame into the own frame collection at the specified index. The contents of the new frame will be filled from the specified image.

```csharp
public void InsertFrame(int index, RasterImage frameImage, uint frameTime)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The index. |
| frameImage | RasterImage | The frame image. |
| frameTime | UInt32 | The frame duration, in milliseconds. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* is less than 0. or *index* is greater than [`PageCount`](../pagecount/). |
| ArgumentNullException | frameImage is null. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)


