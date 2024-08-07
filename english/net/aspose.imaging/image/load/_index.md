---
title: Image.Load
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Loads a new image from the specified file path or URL. If filePath is a file path the method just opens the file. If filePath is an URL the method downloads the file stores it as a temporary one and opens it
type: docs
weight: 20
url: /net/aspose.imaging/image/load/
---
## Load(string, LoadOptions) {#load_3}

Loads a new image from the specified file path or URL. If *filePath* is a file path the method just opens the file. If *filePath* is an URL, the method downloads the file, stores it as a temporary one, and opens it.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path or URL to load image from. |
| loadOptions | LoadOptions | The load options. |

### Return Value

The loaded image.

### See Also

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Load(string) {#load_2}

Loads a new image from the specified file path or URL. If *filePath* is a file path the method just opens the file. If *filePath* is an URL, the method downloads the file, stores it as a temporary one, and opens it.

```csharp
public static Image Load(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path or URL to load image from. |

### Return Value

The loaded image.

## Examples

This example demonstrates the loading of an existing Image file into an instance of Aspose.Imaging.Image using file path specified

```csharp
[C#]

//Create Image instance and initialize it with an existing image file from disk location
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
{
    //do some image processing
}
```

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Loads a new image from the specified stream.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load image from. |
| loadOptions | LoadOptions | The load options. |

### Return Value

The loaded image.

### See Also

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Load(Stream) {#load}

Loads a new image from the specified stream.

```csharp
public static Image Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load image from. |

### Return Value

The loaded image.

## Examples

This example demonstrates the use of System.IO.Stream objects to load an existing Image file

```csharp
[C#]

//Create an instance of FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.bmp", System.IO.FileMode.Open))
{
    //Create an instance of Image class and load an existing file through FileStream object by calling Load method
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(stream))
    {
        //do some image processing.
    }
}
```

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


