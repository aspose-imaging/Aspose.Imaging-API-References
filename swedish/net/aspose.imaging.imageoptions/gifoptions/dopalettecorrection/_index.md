---
title: DoPaletteCorrection
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in ett värde som anger om palettkorrigering tillämpas.
type: docs
weight: 50
url: /sv/net/aspose.imaging.imageoptions/gifoptions/dopalettecorrection/
---
## GifOptions.DoPaletteCorrection property

Hämtar eller ställer in ett värde som anger om palettkorrigering tillämpas.

```csharp
public bool DoPaletteCorrection { get; set; }
```

### Fastighetsvärde

`Sann` om palettkorrigering tillämpas; annat,`falsk` .

### Anmärkningar

Palettkorrigering innebär att när bilden exporteras till GIF kommer källbildens färger att analyseras för att skapa den bästa matchande paletten (om bildpaletten inte finns eller inte specificeras i alternativen). Analysprocessen tar lite tid men utdatabilden kommer att ha den bästa matchande färgpaletten och resultatet blir visuellt bättre.

### Exempel

Det här exemplet visar hur man sparar en BMP-bild i GIF-format med hjälp av olika alternativ.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(1000, 1000))
{
    // Fyll hela bilden med den blå-gula gradienten.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(bmpImage);
    graphics.FillRectangle(gradientBrush, bmpImage.Bounds);

    Aspose.Imaging.ImageOptions.GifOptions saveOptions = new Aspose.Imaging.ImageOptions.GifOptions();

    // Antalet bitar som krävs för att lagra en färg, minus 1.
    saveOptions.ColorResolution = 7;

    // Palettkorrigering innebär att när bilden exporteras till GIF kommer källbildens färger att analyseras
    // för att bygga den bäst matchande paletten (om bildpaletten inte finns eller inte anges i alternativen)
    saveOptions.DoPaletteCorrection = true;

    // Ladda en GIF-bild på ett progressivt sätt.
    // En sammanflätad GIF visar inte sina skanningslinjer linjärt uppifrån och ned, utan ordnar om den istället
    // så att innehållet i GIF:en blir tydligt redan innan den har laddats klart.
    saveOptions.Interlaced = true;

    // Spara som en förlustfri GIF.
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossless GIF: {0} bytes.", stream.Length);
    }

    // Ställ in den maximala tillåtna pixelskillnaden. Om den är större än noll kommer förlustbringande komprimering att användas.
    // Det rekommenderade värdet för optimal förlustkompression är 80. 30 är mycket lätt kompression, 200 är tung.
    saveOptions.MaxDiff = 80;

    // Spara som en förlorad GIF.
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.lossy.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossy GIF: {0} bytes.", stream.Length);
    }
}

//Utgången kan se ut så här:
//Storleken på den förlustfria GIF:en: 212816 byte.
//Storleken på den förlorade GIF:en: 89726 byte.
```

### Se även

* class [GifOptions](../../gifoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../gifoptions)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->