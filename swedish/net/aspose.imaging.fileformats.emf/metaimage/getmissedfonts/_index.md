---
title: GetMissedFonts
second_title: Aspose.Imaging för .NET API-referens
description: Returnerar listan över teckensnitt som används i metafilen men som inte hittades.
type: docs
weight: 30
url: /sv/net/aspose.imaging.fileformats.emf/metaimage/getmissedfonts/
---
## MetaImage.GetMissedFonts method

Returnerar listan över teckensnitt som används i metafilen men som inte hittades.

```csharp
public string[] GetMissedFonts()
```

### Returvärde

Teckensnittslistan

### Exempel

Följande exempel visar hur du skriver ut information om använda och missade teckensnitt i WMF/EMF-bilder.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\net\\issues\\3544";

// För att göra alla teckensnitt oåtkomliga
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

// STDOUT-loggen kan se ut så här:
//========== TestWmfText.wmf ==========
//Använt teckensnitt: Garamond
//Använt teckensnitt: Arial
//Använt teckensnitt: Bookman Old Style
//Använt teckensnitt: Comic Sans MS
//Använt teckensnitt: Courier
//Använt teckensnitt: Courier New
//Använt teckensnitt: Impact
//Använt teckensnitt: Modern
//Använt teckensnitt: MS Sans Serif
//Använt teckensnitt: MS Serif
//Använt teckensnitt: Små teckensnitt
//Använt teckensnitt: Symbol
//Använt teckensnitt: Tahoma
//Använt teckensnitt: Times New Roman
//Använt teckensnitt: Verdana
//Använt teckensnitt: Wingdings
//Missade teckensnitt: Garamond
// Missat teckensnitt: Arial
//Missade teckensnitt: Bookman Old Style
//Missat teckensnitt: Comic Sans MS
//Missade teckensnitt: Courier
//Missade teckensnitt: Courier New
//Missat teckensnitt: Impact
//Missat typsnitt: Modernt
//Missade teckensnitt: MS Sans Serif
//Missat teckensnitt: MS Serif
//Missade teckensnitt: Små teckensnitt
//Missat teckensnitt: Symbol
//Missade teckensnitt: Tahoma
//Missade teckensnitt: Verdana
//Missade teckensnitt: Wingdings
//========== TestEmfFonts.emf ==========
//Använt teckensnitt: Arial
//Använt teckensnitt: Verdana
//Använt teckensnitt: Times New Roman
//Använt teckensnitt: Symbol
// Missat teckensnitt: Arial
//Missade teckensnitt: Verdana
//Missat teckensnitt: Symbol
//========== TestEmfPlusFonts.emf ==========
//Använt teckensnitt: MICROSOFT SANS SERIF
//Missat teckensnitt: MICROSOFT SANS SERIF
```

### Se även

* class [MetaImage](../../metaimage)
* namnutrymme [Aspose.Imaging.FileFormats.Emf](../../metaimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->