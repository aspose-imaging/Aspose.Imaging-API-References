---
title: "类 PathResource"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Tiff.PathResources.PathResource 类。表示 Photoshop 路径资源"
type: docs
weight: 7980
url: /zh/net/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

表示 Photoshop 路径资源。

```csharp
public class PathResource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PathResource](pathresource/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid/) { get; set; } | 获取或设置块标识符。 |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name/) { get; set; } | 获取或设置名称。 |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records/) { get; set; } | 获取或设置记录。 |

## 示例

在从 TIFF 导出到 PSD 图像时传输剪切路径。

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

以下示例展示了如何在 TIFF 图像中创建剪切路径。为此，您需要创建 PathResource 类的实例。下面的代码演示了如何在 TIFF 图像中创建空路径。

```csharp
[C#]

var options = new TiffOptions(TiffExpectedFormat.Default);
var frame = new TiffFrame(options, 800, 600);

using (var image = new TiffImage(frame))
{
    image.ActiveFrame.PathResources = new List<PathResource>
    {
        new PathResource
        {
            BlockId = 2000,
            Name = "My Clipping Path",
            Records = new List<VectorPathRecord>()
        }
    };

    image.Save("ImageWithEmptyPath.tiff");
}
```

从 TIFF 图像的路径资源创建图形路径。

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // 使用来自 TIFF 图像的 PathResources 创建 GraphicsPath
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // 绘制红色线条并保存图像
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

使用 Graphics Path 创建路径资源。

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // 为 GraphicsPath 创建矩形 Figure
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // 使用我们的 Figure 创建 GraphicsPath
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // 使用 GraphicsPath 设置 PathResources
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // 保存图像
        image.Save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape CreateBezierShape(params float[] coordinates)
{
    var bezierPoints = CoordinatesToBezierPoints(coordinates).ToArray();
    return new BezierShape(bezierPoints, true);
}

private static IEnumerable<PointF> CoordinatesToBezierPoints(float[] coordinates)
{
    for (var coordinateIndex = 0; coordinateIndex < coordinates.Length; coordinateIndex += 2)
        for (var index = 0; index < 3; index++)
            yield return new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
}
```

手动创建 Clipping Path。

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                          // Block Id according to Photoshop specification
            Name = "My Clipping Path",                                               // Path name
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)  // Create path records using coordinates
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // Create Bezier records using coordinates

    records.Insert(0, new LengthRecord                                               // LengthRecord required by Photoshop specification
    {
        IsOpen = false,                                                              // Lets create closed path
        RecordCount = (ushort)records.Count                                          // Record count in the path
    });

    return records;
}

private static List<VectorPathRecord> CreateBezierRecords(float[] coordinates)
{
    return CoordinatesToPoints(coordinates)
        .Select(CreateBezierRecord)
        .ToList();
}

private static IEnumerable<PointF> CoordinatesToPoints(float[] coordinates)
{
    for (var index = 0; index < coordinates.Length; index += 2)
        yield return new PointF(coordinates[index], coordinates[index + 1]);
}

private static VectorPathRecord CreateBezierRecord(PointF point)
{
    return new BezierKnotRecord { PathPoints = new[] { point, point, point } };
}
```

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources/)
* assembly [Aspose.Imaging](../../)


