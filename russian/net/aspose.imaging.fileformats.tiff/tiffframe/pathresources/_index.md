---
title: PathResources
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает ресурсы пути.
type: docs
weight: 120
url: /ru/net/aspose.imaging.fileformats.tiff/tiffframe/pathresources/
---
## TiffFrame.PathResources property

Получает или задает ресурсы пути.

```csharp
public List<PathResource> PathResources { get; set; }
```

### Стоимость имущества

Ресурсы пути.

### Примеры

Перенос обтравочных контуров при экспорте изображения из TIFF в PSD.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                           // Идентификатор блока согласно спецификации Photoshop
            Name = "My Clipping Path",                                                // Имя пути
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)   // Создаем записи пути, используя координаты
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                   // Создаем записи Безье, используя координаты

    records.Insert(0, new LengthRecord                                                // LengthRecord требуется спецификацией Photoshop
    {
        IsOpen = false,                                                               // Создадим замкнутый путь
        RecordCount = (ushort)records.Count                                           // Количество записей в path
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

В следующем примере показано, как получить пути из изображения TIFF и отобразить их имена в консоли.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                           // Идентификатор блока согласно спецификации Photoshop
            Name = "My Clipping Path",                                                // Имя пути
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)   // Создаем записи пути, используя координаты
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                   // Создаем записи Безье, используя координаты

    records.Insert(0, new LengthRecord                                                // LengthRecord требуется спецификацией Photoshop
    {
        IsOpen = false,                                                               // Создадим замкнутый путь
        RecordCount = (ushort)records.Count                                           // Количество записей в path
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

В следующем примере показано, как изменить уже существующие обтравочные контуры. Например, вы можете оставить на изображении только один обтравочный контур.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                           // Идентификатор блока согласно спецификации Photoshop
            Name = "My Clipping Path",                                                // Имя пути
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)   // Создаем записи пути, используя координаты
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                   // Создаем записи Безье, используя координаты

    records.Insert(0, new LengthRecord                                                // LengthRecord требуется спецификацией Photoshop
    {
        IsOpen = false,                                                               // Создадим замкнутый путь
        RecordCount = (ushort)records.Count                                           // Количество записей в path
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

В следующем примере показано, как создать обтравочный контур в изображении TIFF. Для этого вам нужно создать экземпляр класса PathResource. Следующий код демонстрирует, как можно создать пустой путь в изображении TIFF.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                           // Идентификатор блока согласно спецификации Photoshop
            Name = "My Clipping Path",                                                // Имя пути
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)   // Создаем записи пути, используя координаты
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                   // Создаем записи Безье, используя координаты

    records.Insert(0, new LengthRecord                                                // LengthRecord требуется спецификацией Photoshop
    {
        IsOpen = false,                                                               // Создадим замкнутый путь
        RecordCount = (ushort)records.Count                                           // Количество записей в path
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

Создать обтравочный контур вручную.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                           // Идентификатор блока согласно спецификации Photoshop
            Name = "My Clipping Path",                                                // Имя пути
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)   // Создаем записи пути, используя координаты
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                   // Создаем записи Безье, используя координаты

    records.Insert(0, new LengthRecord                                                // LengthRecord требуется спецификацией Photoshop
    {
        IsOpen = false,                                                               // Создадим замкнутый путь
        RecordCount = (ushort)records.Count                                           // Количество записей в path
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

### Смотрите также

* class [PathResource](../../../aspose.imaging.fileformats.tiff.pathresources/pathresource)
* class [TiffFrame](../../tiffframe)
* пространство имен [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
