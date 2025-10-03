---
title: Image.GetFileFormat
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Gets the file format
type: docs
weight: 350
url: /net/aspose.imaging/image/getfileformat/
---
## GetFileFormat(string) {#getfileformat_1}

Gets the file format.

```csharp
public static FileFormat GetFileFormat(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |

### Return Value

The determined file format.

## Remarks

The file format determined does not mean that the specified image may be loaded. Use one of the CanLoad method overloads to determine whether file may be loaded.

## Examples

This example shows how to determine the image format without loading the entire image from a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Use an absolute path to the file
Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(dir + "sample.gif");
System.Console.WriteLine("The file format is {0}", format);
```

### See Also

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## GetFileFormat(Stream) {#getfileformat}

Gets the file format.

```csharp
public static FileFormat GetFileFormat(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |

### Return Value

The determined file format.

## Remarks

The file format determined does not mean that the specified image may be loaded. Use one of the CanLoad method overloads to determine whether stream may be loaded.

## Examples

This example shows how to determine the image format without loading the entire image from a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

// Use a file stream
using (System.IO.FileStream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(stream);
    System.Console.WriteLine("The file format is {0}", format);
}

// The following data is not a valid image stream, so GetFileFormat returns FileFormat.Undefined.
byte[] imageData = new byte[] { 0, 0, 0, 0, 0, 0, 0, 0 };
using (System.IO.MemoryStream stream = new System.IO.MemoryStream(imageData))
{
    Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(stream);
    System.Console.WriteLine("The file format is {0}", format);
}
```

### See Also

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


