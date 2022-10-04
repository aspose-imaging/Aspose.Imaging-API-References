---
title: ExifData
second_title: Aspose.Imaging för .NET API-referens
description: Hämta eller ställ in exif data container
type: docs
weight: 70
url: /sv/net/aspose.imaging.fileformats.jpeg/jpegimage/exifdata/
---
## JpegImage.ExifData property

Hämta eller ställ in exif data container

```csharp
public JpegExifData ExifData { get; set; }
```

### Exempel

Följande exempel visar hur man extraherar EXIF-taggar från en JPEG-bild.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "original.jpg"))
{
    Aspose.Imaging.Exif.ExifData exifData = image.ExifData;

    System.Console.WriteLine("The general EXIF data");
    System.Console.WriteLine("------------------------------------------");
    if (exifData != null)
    {
        System.Console.WriteLine("The EXIF version: {0}", exifData.ExifVersion);
        System.Console.WriteLine("The camera serial number: {0}", exifData.BodySerialNumber);
        System.Console.WriteLine("The color space: {0}", exifData.ColorSpace);
        System.Console.WriteLine("The brightness: {0}", exifData.BrightnessValue);
        System.Console.WriteLine("The contrast: {0}", exifData.Contrast);
        System.Console.WriteLine("The gamma: {0}", exifData.Gamma);
        System.Console.WriteLine("The sharpness: {0}", exifData.Sharpness);
        System.Console.WriteLine("The aperture: {0}", exifData.ApertureValue);
        System.Console.WriteLine("The exposure mode: {0}", exifData.ExposureMode);
        System.Console.WriteLine("The exposure bias: {0}", exifData.ExposureBiasValue);
        System.Console.WriteLine("The exposure time: {0}", exifData.ExposureTime);
        System.Console.WriteLine("The focal length: {0}", exifData.FocalLength);
        System.Console.WriteLine("The focal plane resolution unit: {0}", exifData.FocalPlaneResolutionUnit);
        System.Console.WriteLine("The lens model: {0}", exifData.LensModel);
        System.Console.WriteLine("The shutter speed: {0}", exifData.ShutterSpeedValue);
    }

    System.Console.WriteLine("The JPEG EXIF data");
    System.Console.WriteLine("------------------------------------------");
    Aspose.Imaging.Exif.JpegExifData jpegExifData = image.ExifData as Aspose.Imaging.Exif.JpegExifData;
    if (jpegExifData != null)
    {
        System.Console.WriteLine("The camera manufacturer: {0}", jpegExifData.Make);
        System.Console.WriteLine("The camera model: {0}", jpegExifData.Model);
        System.Console.WriteLine("The photometric interpretation: {0}", jpegExifData.PhotometricInterpretation);
        System.Console.WriteLine("The artist: {0}", jpegExifData.Artist);
        System.Console.WriteLine("The copyright: {0}", jpegExifData.Copyright);
        System.Console.WriteLine("The image description: {0}", jpegExifData.ImageDescription);
        System.Console.WriteLine("The orientation: {0}", jpegExifData.Orientation);
        System.Console.WriteLine("The software: {0}", jpegExifData.Software);
    }
}

//Utgången ser ut så här:
//De allmänna EXIF-data
//--------------------------------------------------------
//EXIF-versionen: System.Byte[]
//Kamerans serienummer: 7100536
//Färgutrymmet: SRgb
//Ljusstyrkan:
//Kontrasten: Normal
//Gamma:
//Skärpan: 0
//Bländaren: 4,64(4643856 / 1000000)
//Exponeringsläget: Manuell
//Exponeringsbias: 0,67(4 / 6)
//Exponeringstiden: 0,01(1 / 160)
//Brännvidden: 145,00(1450 / 10)
//Bokplanets upplösningsenhet: Cm
//Linsmodellen: 70,0 - 200,0 mm f/ 4,0
//Slutartiden: 7,32(7321928 / 1000000)
//JPEG EXIF-data
//--------------------------------------------------------
//Kamerans tillverkare: NIKON CORPORATION
//Kameramodellen: NIKON D5
//Den fotometriska tolkningen: 0
//Konstnären: 
//Upphovsrätten: 
//Bildbeskrivningen:
//Orienteringen: TopLeft
//Programvaran: Adobe Photoshop Camera Raw 9.9(Macintosh)
```

### Se även

* class [JpegExifData](../../../aspose.imaging.exif/jpegexifdata)
* class [JpegImage](../../jpegimage)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->