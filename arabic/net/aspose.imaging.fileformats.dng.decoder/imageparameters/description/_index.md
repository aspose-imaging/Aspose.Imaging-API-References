---
title: "ImageParameters.Description"
second_title: "Aspose.Imaging for .NET API Reference"
description: "ImageParameters خاصية. يحصل على وصف الألوان RGBGRGBEGMCY أو GBTG"
type: docs
weight: 30
url: /ar/net/aspose.imaging.fileformats.dng.decoder/imageparameters/description/
---
## ImageParameters.Description property

يحصل على وصف الألوان (RGBG,RGBE,GMCY, أو GBTG).

```csharp
public string Description { get; }
```

### Property Value

الـ cdesc.

## أمثلة

يوضح هذا المثال كيفية تحميل صورة DNG من ملف، طباعة خصائصها وحفظها كـ PNG.

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
        //System.Console.WriteLine("المؤلف:                           {0}", otherParameters.Artist);
        System.Console.WriteLine("The description:                      {0}", otherParameters.Description);
        System.Console.WriteLine("The focal length:                     {0}", otherParameters.FocalLength);
        System.Console.WriteLine("The ISO sensitivity:                  {0}", otherParameters.IsoSpeed);
        System.Console.WriteLine("The serial number of the image:       {0}", otherParameters.ShotOrder);
        System.Console.WriteLine("The shutter speed:                    {0}", otherParameters.ShutterSpeed);
        System.Console.WriteLine("The date of shooting:                 {0}", System.DateTime.FromFileTime(otherParameters.Timestamp));
    }

    // تصدير إلى PNG باستخدام الخيارات الافتراضية.
    dngImage.Save(dir + "test.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

// مصنع الكاميرا:              Leica
// طراز الكاميرا:                     M8 Digital Camera
// عدد الألوان:                     3
// وصف الألوان:               RGBG
// إصدار DNG:                      16777216
// عدد صور RAW في الملف: 1
// البرنامج:                         1.107
// ترتيب بكسلات اللون:        10110100101101001011010010110100
// فتحة العدسة:                         0
// الوصف:                      
// البعد البؤري:                     50
// حساسية ISO:                  160
// الرقم التسلسلي للصورة:       0
// سرعة الغالق:                    12
// تاريخ التصوير:                 8/3/2007 3:13:49 ص
```

### انظر أيضًا

* class [ImageParameters](../)
* namespace [Aspose.Imaging.FileFormats.Dng.Decoder](../../imageparameters/)
* assembly [Aspose.Imaging](../../../)


