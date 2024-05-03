---
title: ImageOtherParameters.Aperture
second_title: Aspose.Imaging for .NET API Reference
description: ImageOtherParameters property. Gets the aperture
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.dng.decoder/imageotherparameters/aperture/
---
## ImageOtherParameters.Aperture property

Gets the aperture.

```csharp
public float Aperture { get; }
```

### Property Value

The aperture.

## Examples

This example shows how to load a DNG image from a file, print its properties and save it to PNG.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "test.dng"))
{
    Aspose.Imaging.FileFormats.Dng.DngImage dngImage = (Aspose.Imaging.FileFormats.Dng.DngImage) image;
    Aspose.Imaging.FileFormats.Dng.Decoder.RawData rawData = dngImage.ImgData;
    Aspose.Imaging.FileFormats.Dng.Decoder.ImageParameters parameters = rawData.ImageDataParameters;
    if (parameters != null)
    {
        System.Console.WriteLine("The camera manufacturer:              {0}", parameters.CameraManufacturer);
        System.Console.WriteLine("The camera model:                     {0}", parameters.Model);
        System.Console.WriteLine("The colors count:                     {0}", parameters.ColorsCount);
        System.Console.WriteLine("The colors description:               {0}", parameters.Description);
        System.Console.WriteLine("The DNG version:                      {0}", parameters.DngVersion);
        System.Console.WriteLine("The number of RAW images in the file: {0}", parameters.RawCount);
        System.Console.WriteLine("The software:                         {0}", parameters.Software);
        System.Console.WriteLine("The order of the color pixels:        {0}", System.Convert.ToString(parameters.Filters, 2));

        string[] translationCfaDng = parameters.TranslationCfaDng;
        if (translationCfaDng != null)
        {
            System.Console.WriteLine("The translation array for CFA mosaic {0}:", translationCfaDng.Length);
            foreach (string s in translationCfaDng)
            {
                System.Console.WriteLine("- {0}", s);
            }
        }
    }

    Aspose.Imaging.FileFormats.Dng.Decoder.ImageOtherParameters otherParameters = rawData.ImageOtherParameters;
    if (otherParameters != null)
    {
        System.Console.WriteLine("The aperture:                         {0}", otherParameters.Aperture);
        //System.Console.WriteLine("The author:                           {0}", otherParameters.Artist);
        System.Console.WriteLine("The description:                      {0}", otherParameters.Description);
        System.Console.WriteLine("The focal length:                     {0}", otherParameters.FocalLength);
        System.Console.WriteLine("The ISO sensitivity:                  {0}", otherParameters.IsoSpeed);
        System.Console.WriteLine("The serial number of the image:       {0}", otherParameters.ShotOrder);
        System.Console.WriteLine("The shutter speed:                    {0}", otherParameters.ShutterSpeed);
        System.Console.WriteLine("The date of shooting:                 {0}", System.DateTime.FromFileTime(otherParameters.Timestamp));
    }

    // Export to PNG with default options.
    dngImage.Save(dir + "test.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

// The camera manufacturer:              Leica
// The camera model:                     M8 Digital Camera
// The colors count:                     3
// The colors description:               RGBG
// The DNG version:                      16777216
// The number of RAW images in the file: 1
// The software:                         1.107
// The order of the color pixels:        10110100101101001011010010110100
// The aperture:                         0
// The description:                      
// The focal length:                     50
// The ISO sensitivity:                  160
// The serial number of the image:       0
// The shutter speed:                    12
// The date of shooting:                 8/3/2007 3:13:49 AM
```

### See Also

* class [ImageOtherParameters](../)
* namespace [Aspose.Imaging.FileFormats.Dng.Decoder](../../imageotherparameters/)
* assembly [Aspose.Imaging](../../../)


