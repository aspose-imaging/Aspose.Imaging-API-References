---
title: Class ClaheFilterOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageFilters.FilterOptions.ClaheFilterOptions class. Provides options for configuring the ContrastLimited Adaptive Histogram Equalization CLAHE filter
type: docs
weight: 9950
url: /net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
## ClaheFilterOptions class

Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

```csharp
public class ClaheFilterOptions : FilterOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [ClaheFilterOptions](clahefilteroptions/)(bool, int, int, double) | Initializes a new instance of the `ClaheFilterOptions` class with the specified parameters. |

## Properties

| Name | Description |
| --- | --- |
| [ClipLimit](../../aspose.imaging.imagefilters.filteroptions/clahefilteroptions/cliplimit/) { get; } | Gets the contrast limiting threshold. Higher values allow more contrast; lower values limit the enhancement to prevent noise amplification. |
| [IsGrayscale](../../aspose.imaging.imagefilters.filteroptions/clahefilteroptions/isgrayscale/) { get; } | Gets a value indicating whether the filter operates in grayscale mode. |
| [TilesNumberHorizontal](../../aspose.imaging.imagefilters.filteroptions/clahefilteroptions/tilesnumberhorizontal/) { get; } | Gets the number of tiles in the horizontal direction. Determines how many regions the image is divided into horizontally for local contrast equalization. |
| [TilesNumberVertical](../../aspose.imaging.imagefilters.filteroptions/clahefilteroptions/tilesnumbervertical/) { get; } | Gets the number of tiles in the vertical direction. Determines how many regions the image is divided into vertically for local contrast equalization. |

### See Also

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


