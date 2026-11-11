---
title: ApngOptions.LoopCount
second_title: Aspose.Imaging for .NET API Reference
description: ApngOptions property. Gets or sets the number of times to loop animation. Default is 1 meaning the value may be inherited from saved image or will be set to 0 infinite looping
type: docs
weight: 30
url: /net/aspose.imaging.imageoptions/apngoptions/loopcount/
---
## ApngOptions.LoopCount property

Gets or sets the number of times to loop animation. Default is -1 meaning the value may be inherited from saved image or will be set to 0 (infinite looping).

```csharp
public int LoopCount { get; set; }
```

## Examples

The following example shows how to export to APNG file format.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Export to APNG animation with unlimited animation cycles as default
    image.Save("Animation1.webp.png", new ApngOptions());
    // Setting up animation cycles
    image.Save("Animation2.webp.png", new ApngOptions() { LoopCount = 5 }); // 5 cycles
}
```

### See Also

* class [ApngOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../apngoptions/)
* assembly [Aspose.Imaging](../../../)


