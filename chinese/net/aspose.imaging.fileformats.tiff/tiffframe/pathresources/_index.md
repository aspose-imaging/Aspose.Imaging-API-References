---
title: "TiffFrame.PathResources"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffFrame 属性。获取或设置路径资源"
type: docs
weight: 100
url: /zh/net/aspose.imaging.fileformats.tiff/tiffframe/pathresources/
---
## TiffFrame.PathResources property

获取或设置路径资源。

```csharp
public List<PathResource> PathResources { get; set; }
```

### Property Value

路径资源。

## 示例

在从 TIFF 导出到 PSD 图像时传输剪切路径。

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

以下示例展示了如何从 TIFF 图像中检索路径并在控制台中显示其名称。

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Sample.tif"))
{
    foreach (var path in image.ActiveFrame.PathResources)
    {
        Console.WriteLine(path.Name);
    }
}
```

以下示例展示了如何修改已存在的裁剪路径。例如，您可以在图像中仅保留一个裁剪路径。

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Sample.tif"))
{
    var paths = image.ActiveFrame.PathResources;
    image.ActiveFrame.PathResources = paths.Take(1).ToList();
    image.Save();
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

* class [PathResource](../../../aspose.imaging.fileformats.tiff.pathresources/pathresource/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


