---
title: RasterImage.IsDigitalSigned
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Performs a fast check to determine if the image is digitally signed using the provided password and threshold
type: docs
weight: 390
url: /net/aspose.imaging/rasterimage/isdigitalsigned/
---
## RasterImage.IsDigitalSigned method

Performs a fast check to determine if the image is digitally signed, using the provided password and threshold.

```csharp
public virtual bool IsDigitalSigned(string password, int percentageThreshold = -1)
```

| Parameter | Type | Description |
| --- | --- | --- |
| password | String | The password to check the signing. |
| percentageThreshold | Int32 | The threshold (in percentage)[0-100] that determines if the image is considered signed. If not specified, a default threshold (`75`) will be applied. |

### Return Value

True if the image is signed, otherwise false.

## Remarks

This method provides the fastest detection by leveraging !:GetSignPercentage. Once the extracted data meets the specified threshold, further extraction steps aimed at improving detection accuracy are skipped.

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


