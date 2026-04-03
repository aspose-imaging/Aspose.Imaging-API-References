---
title: RasterCachedMultipageImage.IsDigitalSigned
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedMultipageImage method. Performs a fast check to determine if the image is digitally signed using the provided password and threshold
type: docs
weight: 280
url: /net/aspose.imaging/rastercachedmultipageimage/isdigitalsigned/
---
## RasterCachedMultipageImage.IsDigitalSigned method

Performs a fast check to determine if the image is digitally signed, using the provided password and threshold.

```csharp
public override bool IsDigitalSigned(string password, int percentageThreshold = -1)
```

| Parameter | Type | Description |
| --- | --- | --- |
| password | String | The password to check the signing. |
| percentageThreshold | Int32 | The threshold (in percentage)[0-100] that determines if the image is considered signed. If not specified, a default threshold (`75`) will be applied. |

### Return Value

True if the image is signed, otherwise false.

## Remarks

This method provides the fastest detection by leveraging !:GetSignPercentage. Once the extracted data meets the specified threshold, further extraction steps aimed at improving detection accuracy are skipped.

The result is `true` only if all pages in the multi-page image are recognized as signed; otherwise, the image is considered unsigned.

## Examples

The example demonstrates how to verify that the embedded digital signature matches the provided password against the specified probability threshold.

```csharp
[C#]

var threshold = 100;
using (var image = Image.Load(outputPath))
{
    var isSigned = image.IsDigitalSigned(password, threshold);
}
```

### See Also

* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)


