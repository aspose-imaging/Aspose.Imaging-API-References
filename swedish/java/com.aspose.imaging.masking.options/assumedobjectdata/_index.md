---
title: "AssumedObjectData"
second_title: "Aspose.Imaging för Java API-referens"
description: "De antagna objektens data."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.masking.options/assumedobjectdata/
---
**Inheritance:**
java.lang.Object
```
public class AssumedObjectData
```

Det antagna objektets data. Inkluderar objektets typ och område.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AssumedObjectData()](#AssumedObjectData--) | Initierar en ny instans av klassen [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
| [AssumedObjectData(int type, Rectangle bounds)](#AssumedObjectData-int-com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
| [AssumedObjectData(String type, Rectangle bounds)](#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Hämtar objektets typ. |
| [setType(int value)](#setType-int-) | Ställer in objektets typ. |
| [getBounds()](#getBounds--) | Hämtar objektets gränser. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ställer in objektets gränser. |

## Example: Saving image masking result with feathering based on image size.
Sparar resultatet av bildmaskering med mjukning baserat på bildstorlek. Bildmaskering utförs med automatiskt beräknade standardstreck. Dessutom specificeras data för de två antagna objekten i egenskapen AssumedObjects i AutoMaskingGraphCutOptions.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// frisläpp resurser
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.
Sparar resultatet av bildmaskering med mjukning baserat på bildstorlek och återanvänder maskeringsalternativ för den nya maskeringsiterationen. Bildmaskering utförs med automatiskt beräknade standardstreck. Dessutom specificeras data för de två antagna objekten i egenskapen AssumedObjects i AutoMaskingGraphCutOptions. Efter att ha fått det initiala maskeringsresultatet modifieras de tillämpade bakgrunds-/förgrundsstrecken och en ny maskeringsiteration utförs.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Vid detta tillfälle kan de tillämpade förgrunds-/bakgrundsstrecken analyseras och baserat på dem ytterligare
// förgrunds-/bakgrundsstrecken kan tillhandahållas manuellt.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// frisläpp resurser
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // Genom att återanvända AutoMaskingGraphCutOptions behövs inte standardstrecksberäkningarna utföras en andra gång.
    options.setCalculateDefaultStrokes(false);
    // När både standardstreck och ObjectsPoints i Args-egenskapen i AutoMaskingArgs tillhandahålls, kombineras punktarrayerna i slutändan.
    // Det första ObjectsPoints-arrayet betraktas som ett bakgrundspunktsarray och
    // det andra ObjectsPoints‑arrayet anses vara ett förgrundspunkts‑array.
    // När både DefaultObjectsRectangles och ObjectsRectangles i Args‑egenskapen för AutoMaskingArgs tillhandahålls,
    // används endast arrayen från Args.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// frisläpp resurser
for (MaskingResult res : results)
{
    res.close();
}

```


## Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.
Sparar bildmaskeringsresultatet med fjädring baserat på bildstorlek, modifierar de erhållna standardstrokarna och använder dem för den nya maskeringsiterationen. Bildmaskering utförs med automatiskt beräknade standardstrokar. Dessutom anges data för de två antagna objekten i AssumedObjects‑egenskapen för AutoMaskingGraphCutOptions. Efter att ha fått det initiala maskeringsresultatet modifieras de tillämpade bakgrunds‑/förgrundsstrokarna och en ytterligare maskeringsiteration utförs med en ny GraphCutMaskingOptions‑instans.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Vid detta tillfälle kan de tillämpade förgrunds-/bakgrundsstrecken analyseras och baserat på dem ytterligare
// förgrunds-/bakgrundsstrecken kan tillhandahållas manuellt.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// frisläpp resurser
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// frisläpp resurser
for (MaskingResult res : results)
{
    res.close();
}
```

### AssumedObjectData() {#AssumedObjectData--}
```
public AssumedObjectData()
```


Initierar en ny instans av klassen [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

### AssumedObjectData(int type, Rectangle bounds) {#AssumedObjectData-int-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(int type, Rectangle bounds)
```


Initierar en ny instans av klassen [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Objektets typ. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | Objektets gränser. |

### AssumedObjectData(String type, Rectangle bounds) {#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(String type, Rectangle bounds)
```


Initierar en ny instans av klassen [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | java.lang.String | Objektets typ. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | Objektets gränser. |

### getType() {#getType--}
```
public final int getType()
```


Hämtar objektets typ.

**Returns:**
int - objektets typ.
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Ställer in objektets typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | objektets typ. |

### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Hämtar objektets gränser.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the object's bounds.
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Ställer in objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | objektets gränser. |

