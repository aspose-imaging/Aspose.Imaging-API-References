---
title: "PathResource"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل مورد مسار Photoshop."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
**Inheritance:**
java.lang.Object
```
public class PathResource
```

يمثل مورد مسار Photoshop.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PathResource()](#PathResource--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBlockId()](#getBlockId--) | يحصل على معرف الكتلة. |
| [setBlockId(short value)](#setBlockId-short-) | يضبط معرف الكتلة. |
| [getName()](#getName--) | يحصل على الاسم. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [getRecords()](#getRecords--) | يحصل على السجلات. |
| [setRecords(List<VectorPathRecord> value)](#setRecords-java.util.List-com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord--) | يضبط السجلات. |

## Example: The following example shows how to create Clipping Path in TIFF image.
المثال التالي يوضح كيفية إنشاء Clipping Path في صورة TIFF. للقيام بذلك تحتاج إلى إنشاء نسخة من الفئة PathResource. يوضح الشيفرة التالية الطريقة التي يمكنك من خلالها إنشاء مسار فارغ في صورة TIFF.
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
    // إنشاء GraphicsPath باستخدام PathResources من صورة TIFF
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // ارسم خطًا أحمر واحفظ الصورة
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
        // إنشاء Figure مستطيلة لـ GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // إنشاء GraphicsPath باستخدام Figure الخاص بنا
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // تعيين PathResources باستخدام GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // احفظ الصورة
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


يحصل على معرف الكتلة.

القيمة: معرف الكتلة.

**Returns:**
short - معرف الكتلة.
### setBlockId(short value) {#setBlockId-short-}
```
public final void setBlockId(short value)
```


يضبط معرف الكتلة.

القيمة: معرف الكتلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short | معرف الكتلة. |

### getName() {#getName--}
```
public final String getName()
```


يحصل على الاسم.

القيمة: الاسم.

**Returns:**
java.lang.String - الاسم.
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يضبط الاسم.

القيمة: الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | الاسم. |

### getRecords() {#getRecords--}
```
public final List<VectorPathRecord> getRecords()
```


يحصل على السجلات.

القيمة: السجلات.

**Returns:**
java.util.List<com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord> - السجلات.
### setRecords(List<VectorPathRecord> value) {#setRecords-java.util.List-com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord--}
```
public final void setRecords(List<VectorPathRecord> value)
```


يضبط السجلات.

القيمة: السجلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.List<com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord> | السجلات. |

