---
title: Filter
second_title: Aspose.Imaging för .NET API-referens
description: Filtrerar den angivna rektangeln.
type: docs
weight: 220
url: /sv/net/aspose.imaging.fileformats.dicom/dicomimage/filter/
---
## DicomImage.Filter method

Filtrerar den angivna rektangeln.

```csharp
public override void Filter(Rectangle rectangle, FilterOptionsBase options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | Rectangle | Rektangeln. |
| options | FilterOptionsBase | Alternativen. |

### Exempel

Följande exempel tillämpar olika typer av filter på en DICOM-bild.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Använd ett medianfilter med en rektangelstorlek på 5 på hela bilden.
    dicomImage.Filter(dicomImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    dicomImage.Save(dir + "sample.MedianFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Applicera ett bilateralt utjämningsfilter med en kärnstorlek på 5 på hela bilden.
    dicomImage.Filter(dicomImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    dicomImage.Save(dir + "sample.BilateralSmoothingFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Applicera ett Gaussiskt oskärpafilter med en radie på 5 och ett sigmavärde på 4,0 på hela bilden.
    dicomImage.Filter(dicomImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    dicomImage.Save(dir + "sample.GaussianBlurFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Applicera ett Gauss-Wiener-filter med en radie på 5 och ett jämnt värde på 4,0 på hela bilden.
    dicomImage.Filter(dicomImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    dicomImage.Save(dir + "sample.GaussWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Applicera ett motion wiener-filter med en längd på 5, ett jämnt värde på 4,0 och en vinkel på 90,0 grader på hela bilden.
    dicomImage.Filter(dicomImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    dicomImage.Save(dir + "sample.MotionWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Använd ett skärpa filter med en kärnstorlek på 5 och ett sigmavärde på 4,0 på hela bilden.
    dicomImage.Filter(dicomImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    dicomImage.Save(dir + "sample.SharpenFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [FilterOptionsBase](../../../aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
* class [DicomImage](../../dicomimage)
* namnutrymme [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
