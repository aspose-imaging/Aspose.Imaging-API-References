---
title: "PathResource"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die Photoshop-Pfadressource dar."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
**Inheritance:**
java.lang.Object
```
public class PathResource
```

Stellt die Photoshop-Pfadressource dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PathResource()](#PathResource--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBlockId()](#getBlockId--) | Ruft die Blockkennung ab. |
| [setBlockId(short value)](#setBlockId-short-) | Setzt die Blockkennung. |
| [getName()](#getName--) | Ruft den Namen ab. |
| [setName(String value)](#setName-java.lang.String-) | Setzt den Namen. |
| [getRecords()](#getRecords--) | Liest die Datensätze. |
| [setRecords(List<VectorPathRecord> value)](#setRecords-java.util.List-com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord--) | Setzt die Datensätze. |

## Example: The following example shows how to create Clipping Path in TIFF image.
Das folgende Beispiel zeigt, wie man einen Clipping Path in einem TIFF‑Bild erstellt. Dafür muss eine Instanz der Klasse PathResource erstellt werden. Der folgende Code demonstriert, wie Sie einen leeren Pfad in einem TIFF‑Bild erzeugen können.
``` java
TiffOptions options = new TiffOptions(TiffExpectedFormat.Default);
TiffFrame frame = new TiffFrame(options, 800, 600);

try (TiffImage image = new TiffImage(frame))
{
    List<PathResource> list = new ArrayList<PathResource>();
    PathResource pr = new PathResource();
    pr.setBlockId(2000);
    pr.setName("My Clipping Path");
    pr.setRecords(new ArrayList<VectorPathRecord>());
    image.getActiveFrame().setPathResources(list);

    image.save("ImageWithEmptyPath.tiff");
}
```


## Example: Transfer Clipping Paths during export from TIFF to PSD image.

``` java
try (Image image = Image.load("Sample.tif"))
{
    image.save("SampleWithPaths.psd", new PsdOptions());
}
```


## Example: Create Clipping Path manually.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Sample.tif"))
    {
        PathResource res = new PathResource();
        res.setBlockId((short) 2000);                                                  // Block Id according to Photoshop specification
        res.setName("My Clipping Path");                                               // Path name
        res.setRecords(createRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)); // Create path records using coordinates
                    
        image.getActiveFrame().setPathResources(Collections.singletonList(res));

        image.save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> createRecords(float ... coordinates)
{
    List<VectorPathRecord>  records = createBezierRecords(coordinates);                                  // Create Bezier records using coordinates

    LengthRecord lr = new LengthRecord(); // LengthRecord required by Photoshop specification
    lr.setOpen(false);                    // Lets create closed path
    lr.setRecordCount(records.size());    // Record count in the path
                
    records.add(0, lr);

    return records;
}

private static List<VectorPathRecord> createBezierRecords(float[] coordinates)
{
    List<VectorPathRecord> l = new LinkedList<VectorPathRecord>();
                
    for (int index = 0; index < coordinates.length - 1; index += 2)
    {
        PointF pt = new PointF(coordinates[index], coordinates[index + 1]);
        BezierKnotRecord br = new BezierKnotRecord();
        br.setPathPoints(new PointF[] {pt, pt, pt});
        l.add(br);
    }
                    
    return l;
}

```


## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Erstellen Sie den GraphicsPath mithilfe von PathResources aus einem TIFF-Bild
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Zeichnen Sie eine rote Linie und speichern Sie das Bild
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // Erstellen Sie eine rechteckige Figure für den GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Erstellen Sie den GraphicsPath mithilfe unserer Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Setzen Sie PathResources mithilfe des GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Speichern Sie das Bild
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### PathResource() {#PathResource--}
```
public PathResource()
```


### getBlockId() {#getBlockId--}
```
public final short getBlockId()
```


Ruft die Blockkennung ab.

Wert: Die Blockkennung.

**Returns:**
short - die Blockkennung.
### setBlockId(short value) {#setBlockId-short-}
```
public final void setBlockId(short value)
```


Setzt die Blockkennung.

Wert: Die Blockkennung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short | der Blockbezeichner. |

### getName() {#getName--}
```
public final String getName()
```


Ruft den Namen ab.

Wert: Der Name.

**Returns:**
java.lang.String - der Name.
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Setzt den Namen.

Wert: Der Name.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | der Name. |

### getRecords() {#getRecords--}
```
public final List<VectorPathRecord> getRecords()
```


Liest die Datensätze.

Wert: Die Datensätze.

**Returns:**
java.util.List<com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord> - die Datensätze.
### setRecords(List<VectorPathRecord> value) {#setRecords-java.util.List-com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord--}
```
public final void setRecords(List<VectorPathRecord> value)
```


Setzt die Datensätze.

Wert: Die Datensätze.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord> | die Datensätze. |

