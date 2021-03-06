---
title: PathResourceConverter
second_title: Aspose.Imaging for .NET API 参考
description: 将PathResource./pathresource转换为GraphicsPath../aspose.imaging/graphicspath反之亦然
type: docs
weight: 7840
url: /zh/net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---
## PathResourceConverter class

将[`PathResource`](../pathresource)转换为[`GraphicsPath`](../../aspose.imaging/graphicspath)反之亦然。

```csharp
public static class PathResourceConverter
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromGraphicsPath](../../aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/fromgraphicspath)(GraphicsPath, Size) | 将[`GraphicsPath`](../../aspose.imaging/graphicspath)实例转换为路径资源。 |
| static [ToGraphicsPath](../../aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/tographicspath)(PathResource[], Size) | 将路径资源转换为[`GraphicsPath`](../../aspose.imaging/graphicspath)实例。 |

### 例子

从 TIFF 图像中的路径资源创建图形路径。

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // 为 GraphicsPath
 创建矩形图形
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // 使用我们的 Figure
 创建 GraphicsPath
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

            // 使用 GraphicsPath
 设置 PathResources
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

            // 保存图片
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

使用图形路径创建路径资源。

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // 为 GraphicsPath
 创建矩形图形
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // 使用我们的 Figure
 创建 GraphicsPath
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

            // 使用 GraphicsPath
 设置 PathResources
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

            // 保存图片
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

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
