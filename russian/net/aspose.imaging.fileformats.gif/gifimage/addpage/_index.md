---
title: AddPage
second_title: Справочник по Aspose.Imaging for .NET API
description: Добавляет страницу к изображению.
type: docs
weight: 220
url: /ru/net/aspose.imaging.fileformats.gif/gifimage/addpage/
---
## GifImage.AddPage method

Добавляет страницу к изображению.

```csharp
public void AddPage(RasterImage page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | RasterImage | Страница для добавления. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *page*равно null. |

### Примеры

Создание многостраничного GIF-изображения с использованием одностраничных растровых изображений.

```csharp
[C#]

static void Main(string[] args)
{
     // Загрузить кадры
    var frames = LoadFrames("Animation frames").ToArray();

     // Создаем GIF-изображение, используя первый frame
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
         // Добавляем кадры к GIF-изображению с помощью метода AddPage
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

         // Сохранить GIF image
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifImage](../../gifimage)
* пространство имен [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->