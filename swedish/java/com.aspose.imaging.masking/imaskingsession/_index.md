---
title: "IMaskingSession"
second_title: "Aspose.Imaging för Java API-referens"
description: "Maskeringssessionen"
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.masking/imaskingsession/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IMaskingSession extends System.IDisposable
```

Maskeringssessionen
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [decompose()](#decompose--) | Utför den första grova dekomponeringsoperationen |
| [decomposeAsync()](#decomposeAsync--) | Skapar den asynkrona uppgiften som kan utföra den första grova dekomponeringsoperationen |
| [improveDecomposition(IMaskingArgs maskingArguments)](#improveDecomposition-com.aspose.imaging.masking.options.IMaskingArgs-) | Utför återträningsdekomponeringsoperationen |
| [improveDecompositionAsync(IMaskingArgs maskingArguments)](#improveDecompositionAsync-com.aspose.imaging.masking.options.IMaskingArgs-) | Skapar den asynkrona uppgiften som kan utföra återträningsdekomponeringsoperationen |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Spara sessionstillståndet till den angivna strömmen. |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) | Spara sessionstillståndet till den angivna strömmen. |
| [save(String filePath)](#save-java.lang.String-) | Sparar sessionstillståndet till den angivna filen. |

## Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// Maskerings‑exportalternativ
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Använd GraphCut‑klustring.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Bakgrundsfärgen kommer att vara orange.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Startar en session för första gången och sparar till en fil
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    com.aspose.imaging.masking.IMaskingSession session = masking.createSession(maskingOptions);
    try
    {
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.decompose();
        try
        {
            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step1.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }

        session.save(sessionBackupFile);
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image.close();
}

// Återupptar en maskeringssession från en fil
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Analysera bilden visuellt och sätt punkterna som tillhör separata objekt.
        args.setObjectsPoints(new Point[][]
                {
                        new Point[]
                                {
                                        new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                        new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                        new Point(3, 0), new Point(3, 1)
                                },
                });
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.improveDecomposition(args);
        try
        {
            // Explicit överföring av exportalternativ, eftersom den inte är serialiserbar
            maskingResult.MaskingOptions.setExportOptions(exportOptions);

            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step2.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image2.close();
}
```

### decompose() {#decompose--}
```
public abstract MaskingResult decompose()
```


Utför den första grova dekomponeringsoperationen

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - Result of masking operation as array of segment image providers.

**Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.**

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// Maskerings‑exportalternativ
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Använd GraphCut‑klustring.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Bakgrundsfärgen kommer att vara orange.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Startar en session för första gången och sparar till en fil
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    com.aspose.imaging.masking.IMaskingSession session = masking.createSession(maskingOptions);
    try
    {
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.decompose();
        try
        {
            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step1.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }

        session.save(sessionBackupFile);
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image.close();
}

// Återupptar en maskeringssession från en fil
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Analysera bilden visuellt och sätt punkterna som tillhör separata objekt.
        args.setObjectsPoints(new Point[][]
                {
                        new Point[]
                                {
                                        new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                        new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                        new Point(3, 0), new Point(3, 1)
                                },
                });
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.improveDecomposition(args);
        try
        {
            // Explicit överföring av exportalternativ, eftersom den inte är serialiserbar
            maskingResult.MaskingOptions.setExportOptions(exportOptions);

            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step2.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image2.close();
}
```

### decomposeAsync() {#decomposeAsync--}
```
public abstract IMaskingAsyncTask decomposeAsync()
```


Skapar den asynkrona uppgiften som kan utföra den första grova dekomponeringsoperationen

**Returns:**
[IMaskingAsyncTask](../../com.aspose.imaging.masking/imaskingasynctask) - The asynchronous decompose task
### improveDecomposition(IMaskingArgs maskingArguments) {#improveDecomposition-com.aspose.imaging.masking.options.IMaskingArgs-}
```
public abstract MaskingResult improveDecomposition(IMaskingArgs maskingArguments)
```


Utför återträningsdekomponeringsoperationen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maskingArguments | [IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) | Maskeringsargumenten. |

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - Result of masking operation as array of segment image providers.

**Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.**

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// Maskerings‑exportalternativ
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Använd GraphCut‑klustring.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Bakgrundsfärgen kommer att vara orange.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// Startar en session för första gången och sparar till en fil
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    com.aspose.imaging.masking.IMaskingSession session = masking.createSession(maskingOptions);
    try
    {
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.decompose();
        try
        {
            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step1.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }

        session.save(sessionBackupFile);
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image.close();
}

// Återupptar en maskeringssession från en fil
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Analysera bilden visuellt och sätt punkterna som tillhör separata objekt.
        args.setObjectsPoints(new Point[][]
                {
                        new Point[]
                                {
                                        new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                        new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                        new Point(3, 0), new Point(3, 1)
                                },
                });
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.improveDecomposition(args);
        try
        {
            // Explicit överföring av exportalternativ, eftersom den inte är serialiserbar
            maskingResult.MaskingOptions.setExportOptions(exportOptions);

            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step2.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image2.close();
}
```

### improveDecompositionAsync(IMaskingArgs maskingArguments) {#improveDecompositionAsync-com.aspose.imaging.masking.options.IMaskingArgs-}
```
public abstract IMaskingAsyncTask improveDecompositionAsync(IMaskingArgs maskingArguments)
```


Skapar den asynkrona uppgiften som kan utföra återträningsdekomponeringsoperationen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maskingArguments | [IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) | Maskeringsargumenten. |

**Returns:**
[IMaskingAsyncTask](../../com.aspose.imaging.masking/imaskingasynctask) - The asynchronous decompose task
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


Spara sessionstillståndet till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Strömmen. |

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public abstract void save(System.IO.Stream stream)
```


Spara sessionstillståndet till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | com.aspose.ms.System.IO.Stream | Strömmen. |

### save(String filePath) {#save-java.lang.String-}
```
public abstract void save(String filePath)
```


Sparar sessionstillståndet till den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen. |

