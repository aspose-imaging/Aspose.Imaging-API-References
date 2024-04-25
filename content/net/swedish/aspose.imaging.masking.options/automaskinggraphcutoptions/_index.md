---
title: AutoMaskingGraphCutOptions
second_title: Aspose.Imaging för .NET API-referens
description: Automaskeringsalternativen för GraphCut.
type: docs
weight: 10460
url: /sv/aspose.imaging.masking.options/automaskinggraphcutoptions/
---
## AutoMaskingGraphCutOptions class

Automaskeringsalternativen för GraphCut.

```csharp
public class AutoMaskingGraphCutOptions : GraphCutMaskingOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [AutoMaskingGraphCutOptions](automaskinggraphcutoptions)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Args](../../aspose.imaging.masking.options/maskingoptions/args) { get; set; } | Hämtar eller ställer in argumenten för segmenteringsalgoritmen. |
| [AssumedObjects](../../aspose.imaging.masking.options/automaskinggraphcutoptions/assumedobjects) { get; set; } | Hämtar eller ställer in de antagna objekten. |
| [BackgroundReplacementColor](../../aspose.imaging.masking.options/maskingoptions/backgroundreplacementcolor) { get; set; } | Hämtar eller ställer in bakgrundsersättningsfärgen. |
| [CalculateDefaultStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/calculatedefaultstrokes) { get; set; } | Hämtar eller ställer in ett värde som indikerar om standardlinjer ska beräknas. |
| [Decompose](../../aspose.imaging.masking.options/maskingoptions/decompose) { get; set; } | Hämtar eller ställer in ett värde som indikerar om onödigt att separera varje Shape från mask som individuellt objekt eller som förenat objekt från mask separerat från bakgrund. |
| [DefaultBackgroundStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultbackgroundstrokes) { get; } | Får standardbakgrundslinjerna. |
| [DefaultForegroundStrokes](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultforegroundstrokes) { get; } | Hämtar de förberäknade standardförgrundsslagen. |
| [DefaultObjectsRectangles](../../aspose.imaging.masking.options/automaskinggraphcutoptions/defaultobjectsrectangles) { get; } | Hämtar standardobjektens rektanglar. |
| [ExportOptions](../../aspose.imaging.masking.options/maskingoptions/exportoptions) { get; set; } | Hämtar eller ställer in alternativ för bildexport. |
| [FeatheringRadius](../../aspose.imaging.masking.options/graphcutmaskingoptions/featheringradius) { get; set; } | Hämtar eller ställer in fjäderradien. |
| [MaskingArea](../../aspose.imaging.masking.options/maskingoptions/maskingarea) { get; set; } | Hämtar eller ställer in maskeringsområdet. |
| [Method](../../aspose.imaging.masking.options/maskingoptions/method) { get; set; } | Hämtar eller ställer in segmenteringsmetoden. |
| [PrecalculationProgressEventHandler](../../aspose.imaging.masking.options/automaskinggraphcutoptions/precalculationprogresseventhandler) { get; set; } | Hämtar eller ställer in standardvärden för förberäkningsprocessens framstegshändelsehanterare för poäng. |

### Exempel

Sparar bildmaskeringsresultat med fjädring baserat på bildstorlek. Bildmaskering utförs med automatiskt beräknade standardlinjer. Args-egenskapen för AutoMaskingGraphCutOptions kan utelämnas eftersom standardlinjer placeras där i slutet.

```csharp
[C#]

MaskingResult[] results;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions
                                                {
                                                    CalculateDefaultStrokes = true,
                                                    FeatheringRadius = (Math.Max(image.Width, image.Height) / 500) + 1,
                                                    Method = SegmentationMethod.GraphCut,
                                                    Decompose = false,
                                                    ExportOptions =
                                                        new PngOptions()
                                                            {
                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                Source = new FileCreateSource("tempFile")
                                                            },
                                                    BackgroundReplacementColor = Color.Transparent
    };

    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Sparar bildmaskeringsresultat med fjädring baserat på bildstorlek. Bildmaskering utförs med automatiskt beräknade standardlinjer. Dessutom specificeras data för de två antagna objekten i egenskapen AssumedObjects i AutoMaskingGraphCutOptions.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions
                                                {
                                                    AssumedObjects = assumedObjects,
                                                    CalculateDefaultStrokes = true,
                                                    FeatheringRadius = (Math.Max(image.Width, image.Height) / 500) + 1,
                                                    Method = SegmentationMethod.GraphCut,
                                                    Decompose = false,
                                                    ExportOptions =
                                                        new PngOptions()
                                                            {
                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                Source = new FileCreateSource("tempFile")
                                                            },
                                                    BackgroundReplacementColor = Color.Transparent
    };

    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Spara bildmaskeringsresultat med utjämning baserat på bildstorlek och återanvändning av maskeringsalternativ för den nya maskeringsiterationen. Bildmaskering utförs med automatiskt beräknade standardlinjer. Dessutom specificeras data för de två antagna objekten i egenskapen AssumedObjects i AutoMaskingGraphCutOptions. Efter att ha fått initialt maskeringsresultat, modifieras applicerade bakgrunds-/förgrundslinjer och ytterligare en maskeringsiteration utförs.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    options = new AutoMaskingGraphCutOptions
                    {
                        AssumedObjects = assumedObjects,
                        CalculateDefaultStrokes = true,
                        FeatheringRadius = 3,
                        Method = SegmentationMethod.GraphCut,
                        Decompose = false,
                        ExportOptions =
                            new PngOptions()
                                {
                                    ColorType = PngColorType.TruecolorWithAlpha,
                                    Source = new FileCreateSource("tempFile")
                                },
                        BackgroundReplacementColor = Color.Transparent
                    };

    results = new ImageMasking(image).Decompose(options);
}

// Vid denna tidpunkt kan applicerade förgrunds-/bakgrundslinjer analyseras och baseras på det ytterligare 
// förgrunds-/bakgrundslinjer kan tillhandahållas manuellt.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    // Återanvända AutoMaskingGraphCutOptions det finns inget behov av att utföra standardberäkningar av streck andra gången.
    options.CalculateDefaultStrokes = false;
    // När både standardlinjer och ObjectsPoints i Args-egenskapen för AutoMaskingArgs tillhandahålls, kombineras punktmatriser.
    // Den första ObjectsPoints-matrisen anses vara en bakgrundspoängmatris och 
    // den andra ObjectsPoints-matrisen anses vara en förgrundspunktsmatris.
    // När både DefaultObjectsRectangles och ObjectsRectangles i Args-egenskapen för AutoMaskingArgs tillhandahålls, 
    // endast arrayen från Args används.
    options.Args = new AutoMaskingArgs()
                        {
                            ObjectsPoints = new Point[][]
                                                {
                                                    new Point[] { new Point(100, 100), new Point(150, 100) }, 
                                                    new Point[] { new Point(500, 200) }, 
                                                },
                            ObjectsRectangles = new Rectangle[]
                                                    {
                                                        new Rectangle(100, 100, 300, 300), 
                                                    }
                        };
    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Sparar bildmaskeringsresultat med utjämning baserat på bildstorlek, modifierar erhållna standardlinjer och använder det för den nya maskeringsiterationen. Bildmaskering utförs med automatiskt beräknade standardlinjer. Dessutom specificeras data för de två antagna objekten i egenskapen AssumedObjects i AutoMaskingGraphCutOptions. Efter att ha fått initialt maskeringsresultat, modifieras tillämpade bakgrunds-/förgrundslinjer och ytterligare en maskeringsiteration utförs med den nya GraphCutMaskingOptions-instansen.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options;

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    options = new AutoMaskingGraphCutOptions
                    {
                        AssumedObjects = assumedObjects,
                        CalculateDefaultStrokes = true,
                        FeatheringRadius = 3,
                        Method = SegmentationMethod.GraphCut,
                        Decompose = false,
                        ExportOptions =
                            new PngOptions()
                                {
                                    ColorType = PngColorType.TruecolorWithAlpha,
                                    Source = new FileCreateSource("tempFile")
                                },
                        BackgroundReplacementColor = Color.Transparent
                    };

    results = new ImageMasking(image).Decompose(options);
}

// Vid denna tidpunkt kan applicerade förgrunds-/bakgrundslinjer analyseras och baseras på det ytterligare 
// förgrunds-/bakgrundslinjer kan tillhandahållas manuellt.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions()
                                                    {
                                                        FeatheringRadius = 3,
                                                        Method = SegmentationMethod.GraphCut,
                                                        Decompose = false,
                                                        ExportOptions = new PngOptions()
                                                                            {
                                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                                Source = new FileCreateSource("tempFile")
                                                                            },
                                                        BackgroundReplacementColor = Color.Transparent,
                                                        Args = new AutoMaskingArgs()
                                                                {
                                                                    ObjectsPoints = new Point[][]
                                                                                        {
                                                                                            appliedBackgroundStrokes,
                                                                                            appliedForegroundStrokes
                                                                                        },
                                                                    ObjectsRectangles = appliedObjectRectangles
                                                                }
                                                    };
    results = new ImageMasking(image).Decompose(graphCutOptions);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Se även

* class [GraphCutMaskingOptions](../graphcutmaskingoptions)
* namnutrymme [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
