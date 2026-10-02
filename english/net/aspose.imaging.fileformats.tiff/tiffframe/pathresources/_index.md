---
title: TiffFrame.PathResources
second_title: Aspose.Imaging for .NET API Reference
description: TiffFrame property. Gets or sets the path resources
type: docs
weight: 110
url: /net/aspose.imaging.fileformats.tiff/tiffframe/pathresources/
---
## TiffFrame.PathResources property

Gets or sets the path resources.

```csharp
public List<PathResource> PathResources { get; set; }
```

### Property Value

The path resources.

## Examples

Transfer Clipping Paths during export from TIFF to PSD image.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

The following example shows how to retrieve paths from TIFF image and display their names in the console.

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

The following example shows how to modify already existing Clipping Paths. For instance, you can keep only one Clipping Path in the image.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Sample.tif"))
{
    var paths = image.ActiveFrame.PathResources;
    image.ActiveFrame.PathResources = paths.Take(1).ToList();
    image.Save();
}
```

The following example shows how to create Clipping Path in TIFF image. In order to do that you need to create an instance of PathResource class. The following code demonstrates the way how you can create an empty path in TIFF image.

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

Create Clipping Path manually.

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

### See Also

* class [PathResource](../../../aspose.imaging.fileformats.tiff.pathresources/pathresource/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


