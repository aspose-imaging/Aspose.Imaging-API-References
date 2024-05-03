---
title: SvgImage.SvgImage
second_title: Aspose.Imaging for .NET API Reference
description: SvgImage constructor. Instantiates a new object of the SvgImage class utilizing the specified path to locate and load the image. This constructor facilitates the creation of SVG image instances from external files enabling seamless integration into software systems and workflows
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.svg/svgimage/svgimage/
---
## SvgImage(string) {#constructor_3}

Instantiates a new object of the [`SvgImage`](../) class, utilizing the specified path to locate and load the image. This constructor facilitates the creation of SVG image instances from external files, enabling seamless integration into software systems and workflows.

```csharp
public SvgImage(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load image from and initialize pixel and palette data with. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | path is null. |

### See Also

* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)

---

## SvgImage(Stream) {#constructor_2}

Creates a new instance of the [`SvgImage`](../) class, loading the image from the provided stream. This constructor enables the direct loading of SVG images from streams, enhancing flexibility and efficiency in handling image resources within software applications.

```csharp
public SvgImage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load image from and initialize pixel and palette data with. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | stream is null. |

## Examples

This example shows how to load an SVG image from a file stream and rasterize it to PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load an SVG image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.svg"))
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = new Aspose.Imaging.FileFormats.Svg.SvgImage(stream))
{
    // In order to rasterize SVG we need to specify rasterization options.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### See Also

* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)

---

## SvgImage(int, int) {#constructor_1}

Instantiates a new [`SvgImage`](../) object with the specified width and height. This constructor allows developers to create SVG images with predefined dimensions, facilitating precise control over the image's size during initialization.

```csharp
public SvgImage(int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width. |
| height | Int32 | The image height. |

### See Also

* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)

---

## SvgImage(SvgOptions, int, int) {#constructor}

Creates a new instance of the [`SvgImage`](../) class with specified SVG options, image width, and height parameters. This constructor enables developers to initialize SVG images with custom options and dimensions, providing flexibility in managing SVG content and layout.

```csharp
public SvgImage(SvgOptions svgOptions, int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| svgOptions | SvgOptions | The SVG options. |
| width | Int32 | Image width. |
| height | Int32 | Image height. |

### See Also

* class [SvgOptions](../../../aspose.imaging.imageoptions/svgoptions/)
* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)


