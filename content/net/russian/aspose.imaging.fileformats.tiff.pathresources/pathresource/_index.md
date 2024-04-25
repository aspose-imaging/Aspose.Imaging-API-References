---
title: PathResource
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет ресурс пути Photoshop.
type: docs
weight: 7830
url: /ru/aspose.imaging.fileformats.tiff.pathresources/pathresource/
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

Передача обтравочных контуров при экспорте из TIFF в PSD-изображение.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

В следующем примере показано, как создать обтравочный контур в изображении TIFF. Для этого вам нужно создать экземпляр класса PathResource. Следующий код демонстрирует, как можно создать пустой путь в изображении TIFF.

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

Создайте графический путь из ресурсов пути в изображении TIFF.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // Создаем GraphicsPath, используя PathResources из изображения TIFF
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Рисуем красную линию и сохраняем изображение
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Создайте ресурсы пути, используя графический путь.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Создаем прямоугольную фигуру для GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Создаем GraphicsPath, используя нашу фигуру
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Установить PathResources с помощью GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Сохраняем изображение
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

Создайте обтравочный контур вручную.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                          // Идентификатор блока согласно спецификации Photoshop
            Name = "My Clipping Path",                                               // Имя пути
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)  // Создаем записи пути, используя координаты
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // Создаем записи Безье, используя координаты

    records.Insert(0, new LengthRecord                                               // LengthRecord требуется спецификацией Photoshop
    {
        IsOpen = false,                                                              // Создадим закрытый путь
        RecordCount = (ushort)records.Count                                          // Количество записей в пути
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
