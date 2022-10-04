---
title: GetUsedFonts
second_title: Aspose.Imaging for .NET API Referansı
description: Meta dosyası içinde kullanılan yazı tipinin listesini döndürür.
type: docs
weight: 40
url: /tr/net/aspose.imaging.fileformats.emf/metaimage/getusedfonts/
---
## MetaImage.GetUsedFonts method

Meta dosyası içinde kullanılan yazı tipinin listesini döndürür.

```csharp
public abstract string[] GetUsedFonts()
```

### Geri dönüş değeri

yazı tipi listesi

### Örnekler

Aşağıdaki örnek, WMF/EMF görüntülerinde kullanılan ve atlanan yazı tipleriyle ilgili bilgilerin nasıl yazdırılacağını gösterir.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\net\\issues\\3544";

// Tüm yazı tiplerini erişilemez hale getirmek için
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

// STDOUT günlüğü şöyle görünebilir:
//========== TestWmfText.wmf ==========
//Kullanılan yazı tipi: Garamond
//Kullanılan yazı tipi: Arial
//Kullanılan yazı tipi: Bookman Eski Stil
//Kullanılan yazı tipi: Comic Sans MS
//Kullanılan yazı tipi: Courier
//Kullanılan yazı tipi: Courier New
//Kullanılan yazı tipi: Etki
//Kullanılan yazı tipi: Modern
//Kullanılan yazı tipi: MS Sans Serif
//Kullanılan yazı tipi: MS Serif
//Kullanılan yazı tipi: Küçük Yazı Tipleri
//Kullanılan yazı tipi: Sembol
//Kullanılan yazı tipi: Tahoma
//Kullanılan yazı tipi: Times New Roman
//Kullanılan yazı tipi: Verdana
//Kullanılan yazı tipi: Wingdings
// Kaçırılan yazı tipi: Garamond
// Kaçırılan yazı tipi: Arial
// Kaçırılan yazı tipi: Bookman Eski Stil
//Eksik yazı tipi: Comic Sans MS
//Eksik yazı tipi: Courier
//Eksik yazı tipi: Courier New
// Kaçırılan yazı tipi: Etki
// Kaçırılan yazı tipi: Modern
//Eksik yazı tipi: MS Sans Serif
//Eksik yazı tipi: MS Serif
// Kaçırılan yazı tipi: Küçük Yazı Tipleri
// Kaçırılan yazı tipi: Sembol
// Kaçırılan yazı tipi: Tahoma
// Kaçırılan yazı tipi: Verdana
// Kaçırılan yazı tipi: Wingdings
//========== TestEmfFonts.emf ===========
//Kullanılan yazı tipi: Arial
//Kullanılan yazı tipi: Verdana
//Kullanılan yazı tipi: Times New Roman
//Kullanılan yazı tipi: Sembol
// Kaçırılan yazı tipi: Arial
// Kaçırılan yazı tipi: Verdana
// Kaçırılan yazı tipi: Sembol
//========== TestEmfPlusFonts.emf ==========
//Kullanılan yazı tipi: MICROSOFT SANS SERIF
//Eksik yazı tipi: MICROSOFT SANS SERIF
```

### Ayrıca bakınız

* class [MetaImage](../../metaimage)
* ad alanı [Aspose.Imaging.FileFormats.Emf](../../metaimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->