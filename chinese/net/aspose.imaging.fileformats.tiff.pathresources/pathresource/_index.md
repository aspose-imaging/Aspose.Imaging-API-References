---
title: PathResource
second_title: Aspose.Imaging for .NET API 参考
description: 表示 Photoshop 路径资源
type: docs
weight: 7830
url: /zh/net/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

表示 Photoshop 路径资源。

```csharp
public class PathResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PathResource](pathresource)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid) { get; set; } | 获取或设置块标识符。 |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name) { get; set; } | 获取或设置名称。 |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records) { get; set; } | 获取或设置记录。 |

### 例子

在从 TIFF 导出到 PSD 图像期间传输剪切路径。

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                              // 根据 Photoshop 规范的块 ID
            Name = "My Clipping Path",                                                   // 路径名
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)      // 使用坐标
创建路径记录
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // 使用坐标
 创建贝塞尔记录

    records.Insert(0, new LengthRecord                                               // Photoshop 规范要求的 LengthRecord
    {
        IsOpen = false,                                                                  // 让我们创建封闭路径
        RecordCount = (ushort)records.Count                                              // path
中的记录计数
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

以下示例显示如何在 TIFF 图像中创建剪切路径。为此，您需要创建 PathResource 类的实例。以下代码演示了如何在 TIFF 图像中创建空路径。

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                              // 根据 Photoshop 规范的块 ID
            Name = "My Clipping Path",                                                   // 路径名
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)      // 使用坐标
创建路径记录
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // 使用坐标
 创建贝塞尔记录

    records.Insert(0, new LengthRecord                                               // Photoshop 规范要求的 LengthRecord
    {
        IsOpen = false,                                                                  // 让我们创建封闭路径
        RecordCount = (ushort)records.Count                                              // path
中的记录计数
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

从 TIFF 图像中的路径资源创建图形路径。

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                              // 根据 Photoshop 规范的块 ID
            Name = "My Clipping Path",                                                   // 路径名
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)      // 使用坐标
创建路径记录
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // 使用坐标
 创建贝塞尔记录

    records.Insert(0, new LengthRecord                                               // Photoshop 规范要求的 LengthRecord
    {
        IsOpen = false,                                                                  // 让我们创建封闭路径
        RecordCount = (ushort)records.Count                                              // path
中的记录计数
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

使用图形路径创建路径资源。

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                              // 根据 Photoshop 规范的块 ID
            Name = "My Clipping Path",                                                   // 路径名
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)      // 使用坐标
创建路径记录
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // 使用坐标
 创建贝塞尔记录

    records.Insert(0, new LengthRecord                                               // Photoshop 规范要求的 LengthRecord
    {
        IsOpen = false,                                                                  // 让我们创建封闭路径
        RecordCount = (ushort)records.Count                                              // path
中的记录计数
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

手动创建剪切路径。

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                              // 根据 Photoshop 规范的块 ID
            Name = "My Clipping Path",                                                   // 路径名
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)      // 使用坐标
创建路径记录
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // 使用坐标
 创建贝塞尔记录

    records.Insert(0, new LengthRecord                                               // Photoshop 规范要求的 LengthRecord
    {
        IsOpen = false,                                                                  // 让我们创建封闭路径
        RecordCount = (ushort)records.Count                                              // path
中的记录计数
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

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
