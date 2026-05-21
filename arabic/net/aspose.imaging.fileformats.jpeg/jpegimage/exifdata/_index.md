---
title: "JpegImage.ExifData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية JpegImage. إدارة بيانات EXIF باستخدام هذه الخاصية التي تتيح لك إضافة أو استرجاع البيانات الوصفية المرتبطة بالصورة. سواءً كان استخراج معلومات حول إعدادات الكاميرا أو تعديل البيانات الوصفية الموجودة، توفر هذه الخاصية مرونة في إدارة حاوية بيانات EXIF."
type: docs
weight: 70
url: /ar/net/aspose.imaging.fileformats.jpeg/jpegimage/exifdata/
---
## JpegImage.ExifData property

إدارة بيانات EXIF باستخدام هذه الخاصية، مما يتيح لك إضافة أو استرجاع البيانات الوصفية المرتبطة بالصورة. سواءً كان استخراج معلومات حول إعدادات الكاميرا أو تعديل البيانات الوصفية الموجودة، توفر هذه الخاصية مرونة في إدارة حاوية بيانات EXIF.

```csharp
public JpegExifData ExifData { get; set; }
```

## أمثلة

يوضح المثال التالي كيفية استخراج وسوم EXIF من صورة JPEG.

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

//الإخراج يبدو هكذا:
//بيانات EXIF العامة
//------------------------------------------
//إصدار EXIF: System.Byte[]
//الرقم التسلسلي للكاميرا: 7100536
//مساحة اللون: SRgb
//السطوع:
//التباين: عادي
//جاما:
//الحدة: 0
//فتحة العدسة: 4.64(4643856 / 1000000)
//وضع التعرض: يدوي
//تحيز التعرض: 0.67(4 / 6)
//وقت التعرض: 0.01(1 / 160)
//البعد البؤري: 145.00(1450 / 10)
//وحدة دقة المستوى البؤري: سم
//طراز العدسة: 70.0 - 200.0 مم f/ 4.0
//سرعة الغالق: 7.32(7321928 / 1000000)
//بيانات JPEG EXIF
//------------------------------------------
//مصنع الكاميرا: NIKON CORPORATION
//طراز الكاميرا: NIKON D5
//التفسير الضوئي: 0
//الفنان: 
//حقوق النشر: 
//وصف الصورة:
//الاتجاه: TopLeft
//البرنامج: Adobe Photoshop Camera Raw 9.9 (Macintosh)
```

### انظر أيضًا

* class [JpegExifData](../../../aspose.imaging.exif/jpegexifdata/)
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


