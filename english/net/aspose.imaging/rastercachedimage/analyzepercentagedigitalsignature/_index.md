---
title: RasterCachedImage.AnalyzePercentageDigitalSignature
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedImage method. Calculates the percentage similarity between the extracted data and the original password
type: docs
weight: 50
url: /net/aspose.imaging/rastercachedimage/analyzepercentagedigitalsignature/
---
## RasterCachedImage.AnalyzePercentageDigitalSignature method

Calculates the percentage similarity between the extracted data and the original password.

```csharp
public override int AnalyzePercentageDigitalSignature(string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| password | String | The password used to extract the embedded data. |

### Return Value

The percentage similarity value.

### Exceptions

| exception | condition |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | Thrown in any processing issues. |

## Examples

The example illustrates how to determine the probability (from 0% to 100%) that an image contains a digital signature created with the specified password.

```csharp
[C#]

using (var image = Image.Load(outputPath))
{
    var signedPercentage = image.AnalyzePercentageDigitalSignature(password);
}
```

### See Also

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


