---
title: "PathResource"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente la ressource de chemin Photoshop."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
**Inheritance:**
java.lang.Object
```
public class PathResource
```

Représente la ressource de chemin Photoshop.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PathResource()](#PathResource--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBlockId()](#getBlockId--) | Obtient l'identifiant du bloc. |
| [setBlockId(short value)](#setBlockId-short-) | Définit l'identifiant du bloc. |
| [getName()](#getName--) | Obtient le nom. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [getRecords()](#getRecords--) | Obtient les enregistrements. |
| [setRecords(List<VectorPathRecord> value)](#setRecords-java.util.List-com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord--) | Définit les enregistrements. |

## Example: The following example shows how to create Clipping Path in TIFF image.
L'exemple suivant montre comment créer un Chemin de détourage dans une image TIFF. Pour ce faire, vous devez créer une instance de la classe PathResource. Le code suivant montre comment créer un chemin vide dans une image TIFF.
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
    // Créer le GraphicsPath en utilisant PathResources à partir d'une image TIFF
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Dessiner une ligne rouge et enregistrer l'image
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
        // Créer une Figure rectangulaire pour GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Créer GraphicsPath en utilisant notre Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Définir PathResources en utilisant GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Enregistrer l'image
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


Obtient l'identifiant du bloc.

Valeur : l'identifiant du bloc.

**Returns:**
short - l'identifiant du bloc.
### setBlockId(short value) {#setBlockId-short-}
```
public final void setBlockId(short value)
```


Définit l'identifiant du bloc.

Valeur : l'identifiant du bloc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short | l'identifiant du bloc. |

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom.

Valeur : Le nom.

**Returns:**
java.lang.String - le nom.
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Définit le nom.

Valeur : Le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | le nom. |

### getRecords() {#getRecords--}
```
public final List<VectorPathRecord> getRecords()
```


Obtient les enregistrements.

Valeur : Les enregistrements.

**Returns:**
java.util.List<com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord> - les enregistrements.
### setRecords(List<VectorPathRecord> value) {#setRecords-java.util.List-com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord--}
```
public final void setRecords(List<VectorPathRecord> value)
```


Définit les enregistrements.

Valeur : Les enregistrements.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord> | les enregistrements. |

