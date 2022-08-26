---
title: AssumedObjectData
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die Daten des angenommenen Objekts. Beinhaltet Typ und Fläche des Objekts.
type: docs
weight: 10440
url: /de/net/aspose.imaging.masking.options/assumedobjectdata/
---
## AssumedObjectData class

Die Daten des angenommenen Objekts. Beinhaltet Typ und Fläche des Objekts.

```csharp
public class AssumedObjectData
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [AssumedObjectData](assumedobjectdata#constructor)() | Initialisiert eine neue Instanz von[`AssumedObjectData`](../assumedobjectdata) Klasse. |
| [AssumedObjectData](assumedobjectdata#constructor_1)(DetectedObjectType, Rectangle) | Initialisiert eine neue Instanz von[`AssumedObjectData`](../assumedobjectdata) Klasse. |
| [AssumedObjectData](assumedobjectdata#constructor_2)(string, Rectangle) | Initialisiert eine neue Instanz von[`AssumedObjectData`](../assumedobjectdata) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bounds](../../aspose.imaging.masking.options/assumedobjectdata/bounds) { get; set; } | Ruft die Grenzen des Objekts ab oder legt sie fest. |
| [Type](../../aspose.imaging.masking.options/assumedobjectdata/type) { get; set; } | Ruft den Typ des Objekts ab oder legt ihn fest. |

### Beispiele

Speichern des Ergebnisses der Bildmaskierung mit weichem Rand basierend auf der Bildgröße. Die Bildmaskierung erfolgt mit automatisch berechneten Standardstrichen. Zusätzlich werden die Daten der beiden angenommenen Objekte auch in der Eigenschaft AssumedObjects der AutoMaskingGraphCutOptions angegeben.

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

Speichern des Bildmaskierungsergebnisses mit weichem Rand basierend auf der Bildgröße und Wiederverwendung der Maskierungsoptionen für die neue Maskierungs-Iteration. Die Bildmaskierung erfolgt mit automatisch berechneten Standardstrichen. Zusätzlich werden die Daten der beiden angenommenen Objekte auch in der Eigenschaft AssumedObjects der AutoMaskingGraphCutOptions angegeben. Nachdem das anfängliche Maskierungsergebnis erhalten wurde, werden die angewendeten Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration durchgeführt.

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

// An dieser Stelle können angewendete Vordergrund-/Hintergrundstriche analysiert und darauf aufbauend weiter ausgeführt werden 
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    // Durch die Wiederverwendung von AutoMaskingGraphCutOptions ist es nicht erforderlich, die Standardstrichberechnungen ein zweites Mal durchzuführen.
    options.CalculateDefaultStrokes = false;
    // Wenn sowohl Standardstriche als auch ObjectsPoints in der Args-Eigenschaft von AutoMaskingArgs bereitgestellt werden, werden Point-Arrays am Ende kombiniert.
    // Das erste ObjectsPoints-Array wird als Hintergrundpunkte-Array betrachtet und 
    // Das zweite ObjectsPoints-Array wird als Vordergrundpunkte-Array betrachtet.
    // Wenn sowohl DefaultObjectsRectangles als auch ObjectsRectangles in der Args-Eigenschaft von AutoMaskingArgs angegeben sind, 
    // nur das Array von Args wird verwendet.
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

Speichern des Bildmaskierungsergebnisses mit Federn basierend auf der Bildgröße, Modifizieren der erhaltenen Standardstriche und Verwenden für die neue Maskierungsiteration. Die Bildmaskierung erfolgt mit automatisch berechneten Standardstrichen. Zusätzlich werden die Daten der beiden angenommenen Objekte auch in der Eigenschaft AssumedObjects der AutoMaskingGraphCutOptions angegeben. Nach Erhalt des ersten Maskierungsergebnisses werden angewendete Hintergrund-/Vordergrundstriche modifiziert und eine weitere Maskierungsiteration wird unter Verwendung einer neuen GraphCutMaskingOptions-Instanz durchgeführt.

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

// An dieser Stelle können angewendete Vordergrund-/Hintergrundstriche analysiert und darauf aufbauend weiter ausgeführt werden 
// Vordergrund-/Hintergrundstriche können manuell bereitgestellt werden.
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

### Siehe auch

* namensraum [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
