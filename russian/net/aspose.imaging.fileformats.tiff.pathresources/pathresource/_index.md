---
title: PathResource
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет ресурс пути Photoshop.
type: docs
weight: 7830
url: /ru/net/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

Представляет ресурс пути Photoshop.

```csharp
public class PathResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PathResource](pathresource)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid) { get; set; } | Получает или задает идентификатор блока. |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name) { get; set; } | Получает или задает имя. |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records) { get; set; } | Получает или устанавливает записи. |

### Примеры

Перенос обтравочных контуров при экспорте из TIFF в PSD изображение.

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

Создание графического пути из ресурсов пути в изображении TIFF.

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

Создание ресурсов пути с помощью графического пути.

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

* пространство имен [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
