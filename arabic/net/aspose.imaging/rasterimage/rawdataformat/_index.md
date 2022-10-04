---
title: RawDataFormat
second_title: Aspose.Imaging لمرجع NET API
description: يحصل على تنسيق البيانات الأولية.
type: docs
weight: 80
url: /ar/net/aspose.imaging/rasterimage/rawdataformat/
---
## RasterImage.RawDataFormat property

يحصل على تنسيق البيانات الأولية.

```csharp
public virtual PixelDataFormat RawDataFormat { get; }
```

### Property_Value

تنسيق البيانات الأولية .

### أمثلة

يقوم المثال التالي بتحميل الصور النقطية ويطبع معلومات حول تنسيق البيانات الأولية وقناة ألفا.

```csharp
[C#]

// ملفات الصور المراد تحميلها.
string[] fileNames = new string[]
{
    @"c:\temp\sample.bmp",
    @"c:\temp\alpha.png",
};

foreach (string fileName in fileNames)
{
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
    {
        Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
        System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, rasterImage.RawDataFormat, rasterImage.HasAlpha);
    }
}

// قد يبدو الإخراج كالتالي:
// ImageFile = c: \ temp \ sample.bmp ، FileFormat = Rgb24Bpp ، القنوات المستخدمة: 8،8،8 ، HasAlpha = False
// ImageFile = c: \ temp \ alpha.png، FileFormat = RGBA32Bpp، القنوات المستخدمة: 8،8،8،8، HasAlpha = True
```

يوضح هذا المثال كيفية تحميل صورة DJVU من دفق ملف وطباعة معلومات حول الصفحات.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بتحميل صورة DJVU من دفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        System.Console.WriteLine("The total number of pages: {0}", djvuImage.Pages.Length);
        System.Console.WriteLine("The active page number:    {0}", djvuImage.ActivePage.PageNumber);
        System.Console.WriteLine("The first page number:     {0}", djvuImage.FirstPage.PageNumber);
        System.Console.WriteLine("The last page number:      {0}", djvuImage.LastPage.PageNumber);

        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            System.Console.WriteLine("--------------------------------------------------");
            System.Console.WriteLine("Page number:     {0}", djvuPage.PageNumber);
            System.Console.WriteLine("Page size:       {0}", djvuPage.Size);
            System.Console.WriteLine("Page raw format: {0}", djvuPage.RawDataFormat);
        }
    }
}

// قد يبدو الإخراج كالتالي:
// إجمالي عدد الصفحات: 2
// رقم الصفحة النشطة: 1
// رقم الصفحة الأولى: 1
// رقم الصفحة الأخيرة: 2
// ------------------------------------------------ -
// رقم الصفحة: 1
// حجم الصفحة: {العرض = 2481 ، الارتفاع = 3508}
// تنسيق الصفحة الخام: RgbIndexed1Bpp ، القنوات المستخدمة: 1
// ------------------------------------------------ -
// رقم الصفحة: 2
// حجم الصفحة: {العرض = 2481 ، الارتفاع = 3508}
// تنسيق الصفحة الخام: RgbIndexed1Bpp ، القنوات المستخدمة: 1
```

### أنظر أيضا

* class [PixelDataFormat](../../pixeldataformat)
* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->