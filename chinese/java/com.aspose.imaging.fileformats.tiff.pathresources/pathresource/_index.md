---
title: "PathResource"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示 Photoshop 路径资源。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
**Inheritance:**
java.lang.Object
```
public class PathResource
```

表示 Photoshop 路径资源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PathResource()](#PathResource--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlockId()](#getBlockId--) | 获取块标识符。 |
| [setBlockId(short value)](#setBlockId-short-) | 设置块标识符。 |
| [getName()](#getName--) | 获取名称。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [getRecords()](#getRecords--) | 获取记录。 |
| [setRecords(List<VectorPathRecord> value)](#setRecords-java.util.List-com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord--) | 设置记录。 |

## Example: The following example shows how to create Clipping Path in TIFF image.
以下示例展示了如何在 TIFF 图像中创建 Clipping Path。为此，您需要创建一个 PathResource 类的实例。以下代码演示了如何在 TIFF 图像中创建空路径。
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
    // 使用来自 TIFF 图像的 PathResources 创建 GraphicsPath
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // 绘制红色线条并保存图像
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
        // 为 GraphicsPath 创建矩形 Figure
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // 使用我们的 Figure 创建 GraphicsPath
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // 使用 GraphicsPath 设置 PathResources
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // 保存图像
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


获取块标识符。

值：块标识符。

**Returns:**
short - 块标识符。
### setBlockId(short value) {#setBlockId-short-}
```
public final void setBlockId(short value)
```


设置块标识符。

值：块标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short | 块标识符。 |

### getName() {#getName--}
```
public final String getName()
```


获取名称。

值：名称。

**Returns:**
java.lang.String - 名称。
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


设置名称。

值：名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 名称。 |

### getRecords() {#getRecords--}
```
public final List<VectorPathRecord> getRecords()
```


获取记录。

值：记录。

**Returns:**
java.util.List<com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord> - 记录。
### setRecords(List<VectorPathRecord> value) {#setRecords-java.util.List-com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord--}
```
public final void setRecords(List<VectorPathRecord> value)
```


设置记录。

值：记录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.List<com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord> | 记录。 |

