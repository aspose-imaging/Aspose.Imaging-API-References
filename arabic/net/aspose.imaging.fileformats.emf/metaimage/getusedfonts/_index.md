---
title: "MetaImage.GetUsedFonts"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة MetaImage. تُرجع قائمة الخطوط المستخدمة داخل ملف الميتا"
type: docs
weight: 40
url: /ar/net/aspose.imaging.fileformats.emf/metaimage/getusedfonts/
---
## MetaImage.GetUsedFonts method

يعيد قائمة الخطوط المستخدمة داخل ملف الميتا.

```csharp
public abstract string[] GetUsedFonts()
```

### قيمة الإرجاع

قائمة الخطوط

## أمثلة

المثال التالي يوضح كيفية طباعة معلومات حول الخطوط المستخدمة والمفقودة في صور WMF/EMF.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\net\\issues\\3544";

// لجعل جميع الخطوط غير قابلة للوصول
string[] fontDirectories = Aspose.Imaging.FontSettings.GetFontsFolders();
Aspose.Imaging.FontSettings.SetFontsFolder("empty");
string[] files = new string[]
{
    "TestWmfText.wmf",
    "TestEmfFonts.emf",
    "TestEmfPlusFonts.emf",
};

try
{
    foreach (string file in files)
    {
        System.Console.WriteLine("========== {0} ==========", file);
        using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(System.IO.Path.Combine(dir, file)))
        {
            string[] used = image.GetUsedFonts();
            foreach (string it in used)
            {
                System.Console.WriteLine("Used font: " + it);
            }

            string[] missed = image.GetMissedFonts();
            foreach (string it in missed)
            {
                System.Console.WriteLine("Missed font: " + it);
            }

            int ui = 0, mi = 0;
            foreach (string it in used)
            {
                if (it.Contains("Times"))
                {
                    ui++;
                    continue;
                }

                if (used[ui] != missed[mi])
                {
                    throw new System.Exception("Font lists must be equal!");
                }

                ui++; mi++;
            }
        }
    }
}
finally
{
    Aspose.Imaging.FontSettings.SetFontsFolders(fontDirectories, true);
}

// قد يبدو سجل STDOUT هكذا:
//========== TestWmfText.wmf ==========
//الخط المستخدم: Garamond
//الخط المستخدم: Arial
//الخط المستخدم: Bookman Old Style
//الخط المستخدم: Comic Sans MS
//الخط المستخدم: Courier
//الخط المستخدم: Courier New
//الخط المستخدم: Impact
//الخط المستخدم: Modern
//الخط المستخدم: MS Sans Serif
//الخط المستخدم: MS Serif
//الخط المستخدم: Small Fonts
//الخط المستخدم: Symbol
//الخط المستخدم: Tahoma
//الخط المستخدم: Times New Roman
//الخط المستخدم: Verdana
//الخط المستخدم: Wingdings
//الخط المفقود: Garamond
//الخط المفقود: Arial
//الخط المفقود: Bookman Old Style
//الخط المفقود: Comic Sans MS
//الخط المفقود: Courier
//الخط المفقود: Courier New
//الخط المفقود: Impact
//الخط المفقود: Modern
//الخط المفقود: MS Sans Serif
//الخط المفقود: MS Serif
//الخط المفقود: Small Fonts
//الخط المفقود: Symbol
//الخط المفقود: Tahoma
//الخط المفقود: Verdana
//الخط المفقود: Wingdings
//========== TestEmfFonts.emf ==========
//الخط المستخدم: Arial
//الخط المستخدم: Verdana
//الخط المستخدم: Times New Roman
//الخط المستخدم: Symbol
//الخط المفقود: Arial
//الخط المفقود: Verdana
//الخط المفقود: Symbol
//========== TestEmfPlusFonts.emf ==========
//الخط المستخدم: MICROSOFT SANS SERIF
//الخط المفقود: MICROSOFT SANS SERIF
```

### انظر أيضًا

* class [MetaImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf](../../metaimage/)
* assembly [Aspose.Imaging](../../../)


