---
title: Image.CanLoad
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Determines whether image can be loaded from the specified file path
type: docs
weight: 340
url: /net/aspose.imaging/image/canload/
---
## CanLoad(string) {#canload_2}

Determines whether image can be loaded from the specified file path.

```csharp
public static bool CanLoad(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |

### Return Value

`true` if image can be loaded from the specified file; otherwise, `false`.

## Examples

This example determines whether image can be loaded from a file.

```csharp
[C#]

// Use an absolute path to the file
bool canLoad = Aspose.Imaging.Image.CanLoad(@"c:\temp\sample.gif");
```

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## CanLoad(string, LoadOptions) {#canload_3}

Determines whether image can be loaded from the specified file path and optionally using the specified open options.

```csharp
public static bool CanLoad(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |
| loadOptions | LoadOptions | The load options. |

### Return Value

`true` if image can be loaded from the specified file; otherwise, `false`.

### See Also

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## CanLoad(Stream) {#canload}

Determines whether image can be loaded from the specified stream.

```csharp
public static bool CanLoad(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load from. |

### Return Value

`true` if image can be loaded from the specified stream; otherwise, `false`.

## Examples

This example determines whether image can be loaded from a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

bool canLoad;

// Use a file stream
using (System.IO.FileStream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    canLoad = Aspose.Imaging.Image.CanLoad(stream);
}

// The following data is not a valid image stream, so CanLoad returns false.
byte[] imageData = new byte[] { 0, 0, 0, 0, 0, 0, 0, 0 };
using (System.IO.MemoryStream stream = new System.IO.MemoryStream(imageData))
{
    canLoad = Aspose.Imaging.Image.CanLoad(stream);
}
```

### See Also

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## CanLoad(Stream, LoadOptions) {#canload_1}

Determines whether image can be loaded from the specified stream and optionally using the specified *loadOptions*.

```csharp
public static bool CanLoad(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load from. |
| loadOptions | LoadOptions | The load options. |

### Return Value

`true` if image can be loaded from the specified stream; otherwise, `false`.

### See Also

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


