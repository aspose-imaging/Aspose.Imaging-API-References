---
title: MetaImage.GetUsedFonts
second_title: Aspose.Imaging for .NET API Reference
description: MetaImage method. Returns the list of font which used inside metafile
type: docs
weight: 40
url: /net/aspose.imaging.fileformats.emf/metaimage/getusedfonts/
---
## MetaImage.GetUsedFonts method

Returns the list of font which used inside metafile.

```csharp
public abstract string[] GetUsedFonts()
```

### Return Value

The font list

## Examples

The following example shows how to print information about used and missed fonts in WMF/EMF images.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\net\\issues\\3544";

// To make all fonts unaccessable
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

// The STDOUT log may look like this:
//========== TestWmfText.wmf ==========
//Used font: Garamond
//Used font: Arial
//Used font: Bookman Old Style
//Used font: Comic Sans MS
//Used font: Courier
//Used font: Courier New
//Used font: Impact
//Used font: Modern
//Used font: MS Sans Serif
//Used font: MS Serif
//Used font: Small Fonts
//Used font: Symbol
//Used font: Tahoma
//Used font: Times New Roman
//Used font: Verdana
//Used font: Wingdings
//Missed font: Garamond
//Missed font: Arial
//Missed font: Bookman Old Style
//Missed font: Comic Sans MS
//Missed font: Courier
//Missed font: Courier New
//Missed font: Impact
//Missed font: Modern
//Missed font: MS Sans Serif
//Missed font: MS Serif
//Missed font: Small Fonts
//Missed font: Symbol
//Missed font: Tahoma
//Missed font: Verdana
//Missed font: Wingdings
//========== TestEmfFonts.emf ==========
//Used font: Arial
//Used font: Verdana
//Used font: Times New Roman
//Used font: Symbol
//Missed font: Arial
//Missed font: Verdana
//Missed font: Symbol
//========== TestEmfPlusFonts.emf ==========
//Used font: MICROSOFT SANS SERIF
//Missed font: MICROSOFT SANS SERIF
```

### See Also

* class [MetaImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf](../../metaimage/)
* assembly [Aspose.Imaging](../../../)


