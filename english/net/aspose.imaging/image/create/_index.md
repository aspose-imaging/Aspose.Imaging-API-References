---
title: Image.Create
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Creates a new image using the specified create options
type: docs
weight: 10
url: /net/aspose.imaging/image/create/
---
## Create(ImageOptionsBase, int, int) {#create_1}

Creates a new image using the specified create options.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | The image options. |
| width | Int32 | The width. |
| height | Int32 | The height. |

### Return Value

The newly created image.

## Examples

This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case.

```csharp
[C#]

//Create an instance of BmpOptions and set its various properties
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
//Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Create an instance of Image and initialize it with instance of BmpOptions by calling Create method
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //do some image processing

    // save all changes
    image.Save();
}
```

### See Also

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(Image[]) {#create_2}

Creates a new image using the specified images as pages

```csharp
public static Image Create(Image[] images)
```

| Parameter | Type | Description |
| --- | --- | --- |
| images | Image[] | The images. |

### Return Value

The Image as IMultipageImage

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(MultipageCreateOptions) {#create}

Creates the specified multipage create options.

```csharp
public static Image Create(MultipageCreateOptions multipageCreateOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| multipageCreateOptions | MultipageCreateOptions | The multipage create options. |

### Return Value

The multipage image

### See Also

* class [MultipageCreateOptions](../../../aspose.imaging.imageoptions/multipagecreateoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(string[], bool) {#create_5}

Creates the multipage image containing the specified files.

```csharp
public static Image Create(string[] files, bool throwExceptionOnLoadError)
```

| Parameter | Type | Description |
| --- | --- | --- |
| files | String[] | The files. |
| throwExceptionOnLoadError | Boolean | if set to `true` [throw exception on load error]. |

### Return Value

The multipage image

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(string[]) {#create_4}

Creates the multipage image containing the specified files.

```csharp
public static Image Create(string[] files)
```

| Parameter | Type | Description |
| --- | --- | --- |
| files | String[] | The files. |

### Return Value

The multipage image

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(Image[], bool) {#create_3}

Creates a new image the specified images as pages.

```csharp
public static Image Create(Image[] images, bool disposeImages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| images | Image[] | The images. |
| disposeImages | Boolean | if set to `true` [dispose images]. |

### Return Value

The Image as IMultipageImage

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


