---
title: RasterImage.AnalyzePercentageDigitalSignature
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Calculates the percentage similarity between the extracted data and the original password
type: docs
weight: 210
url: /net/aspose.imaging/rasterimage/analyzepercentagedigitalsignature/
---
## RasterImage.AnalyzePercentageDigitalSignature method

Calculates the percentage similarity between the extracted data and the original password.

```csharp
public virtual int AnalyzePercentageDigitalSignature(string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| password | String | The password used to extract the embedded data. |

### Return Value

The percentage similarity value.

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

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


