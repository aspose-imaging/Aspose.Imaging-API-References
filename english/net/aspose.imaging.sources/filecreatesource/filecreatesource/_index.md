---
title: FileCreateSource.FileCreateSource
second_title: Aspose.Imaging for .NET API Reference
description: FileCreateSource constructor. Initializes a new instance of the FileCreateSource class
type: docs
weight: 10
url: /net/aspose.imaging.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Initializes a new instance of the [`FileCreateSource`](../) class.

```csharp
public FileCreateSource(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to create. |

## Examples

This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. If second parameter is not passed to the constructor of FileCreateSource, then by default the file to be created has property IsTemporal set to True. With IsTemporal set to True, no file will be saved on disk at the end of execution.

```csharp
[C#]

//Creates an instance of BmpOptions and set its various properties
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
//If second parameter is not passed, then by default the file has IsTemporal set to True
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Creates an instance of Image 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //do some image processing
}
```

### See Also

* class [FileCreateSource](../)
* namespace [Aspose.Imaging.Sources](../../filecreatesource/)
* assembly [Aspose.Imaging](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Initializes a new instance of the [`FileCreateSource`](../) class.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to create. |
| isTemporal | Boolean | If set to `true` the created file will be temporal. |

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

* class [FileCreateSource](../)
* namespace [Aspose.Imaging.Sources](../../filecreatesource/)
* assembly [Aspose.Imaging](../../../)


