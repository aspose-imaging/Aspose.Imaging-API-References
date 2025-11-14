---
title: Class TimeInterval
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.TimeInterval class. Represents the time interval in milliseconds
type: docs
weight: 10560
url: /net/aspose.imaging.imageoptions/timeinterval/
---
## TimeInterval class

Represents the time interval in milliseconds

```csharp
public class TimeInterval
```

## Constructors

| Name | Description |
| --- | --- |
| [TimeInterval](timeinterval/)(uint, uint) | Initializes a new instance of the `TimeInterval` class. |

## Properties

| Name | Description |
| --- | --- |
| [From](../../aspose.imaging.imageoptions/timeinterval/from/) { get; set; } | Gets or sets From milliseconds. |
| [To](../../aspose.imaging.imageoptions/timeinterval/to/) { get; set; } | Gets or sets To milliseconds. |

## Examples

Export of part of animation from GIF image based on time interval.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

### See Also

* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


