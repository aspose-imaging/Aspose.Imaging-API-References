---
title: "PathResource"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el recurso de ruta de Photoshop."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
**Inheritance:**
java.lang.Object
```
public class PathResource
```

Representa el recurso de ruta de Photoshop.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PathResource()](#PathResource--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBlockId()](#getBlockId--) | Obtiene el identificador del bloque. |
| [setBlockId(short value)](#setBlockId-short-) | Establece el identificador del bloque. |
| [getName()](#getName--) | Obtiene el nombre. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [getRecords()](#getRecords--) | Obtiene los registros. |
| [setRecords(List<VectorPathRecord> value)](#setRecords-java.util.List-com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord--) | Establece los registros. |

## Example: The following example shows how to create Clipping Path in TIFF image.
El siguiente ejemplo muestra cómo crear una Ruta de Recorte en una imagen TIFF. Para ello, necesita crear una instancia de la clase PathResource. El siguiente código demuestra la forma en que puede crear una ruta vacía en una imagen TIFF.
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
    // Crear el GraphicsPath usando PathResources de una imagen TIFF
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Dibujar una línea roja y guardar la imagen
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
        // Crear una Figure rectangular para GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Crear GraphicsPath usando nuestra Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Establecer PathResources usando GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Guardar la imagen
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


Obtiene el identificador del bloque.

Valor: El identificador del bloque.

**Returns:**
short - el identificador del bloque.
### setBlockId(short value) {#setBlockId-short-}
```
public final void setBlockId(short value)
```


Establece el identificador del bloque.

Valor: El identificador del bloque.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short | el identificador del bloque. |

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre.

Valor: el nombre.

**Returns:**
java.lang.String - el nombre.
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Establece el nombre.

Valor: el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | el nombre. |

### getRecords() {#getRecords--}
```
public final List<VectorPathRecord> getRecords()
```


Obtiene los registros.

Valor: los registros.

**Returns:**
java.util.List<com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord> - los registros.
### setRecords(List<VectorPathRecord> value) {#setRecords-java.util.List-com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord--}
```
public final void setRecords(List<VectorPathRecord> value)
```


Establece los registros.

Valor: los registros.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord> | los registros. |

