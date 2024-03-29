---
title: Html5CanvasOptions
second_title: Справочник по Aspose.Imaging for .NET API
description: Параметры создания файла формата Html5 Canvas.
type: docs
weight: 10010
url: /ru/net/aspose.imaging.imageoptions/html5canvasoptions/
---
## Html5CanvasOptions class

Параметры создания файла формата Html5 Canvas.

```csharp
public class Html5CanvasOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Html5CanvasOptions](html5canvasoptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [CanvasTagId](../../aspose.imaging.imageoptions/html5canvasoptions/canvastagid) { get; set; } | Получает или задает идентификатор тега холста. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [Encoding](../../aspose.imaging.imageoptions/html5canvasoptions/encoding) { get; set; } | Получает или задает кодировку. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [FullHtmlPage](../../aspose.imaging.imageoptions/html5canvasoptions/fullhtmlpage) { get; set; } | Получает или задает значение, указывающее, следует ли создавать полную HTML-страницу. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения в. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |

### Примеры

Любое векторное изображение (SVG, WMF, CMX и т. д.) может быть использовано в качестве источника для ваших изображений Canvas. Следующий код создает простое изображение Canvas.

```csharp
[C#]

using (var image = Image.Load(@"Sample.svg"))
{
    image.Save(@"Canvas.html", new Html5CanvasOptions
    {
        VectorRasterizationOptions = new SvgRasterizationOptions()
    });
}
```

Вы можете встроить более одного изображения Canvas в HTML-страницу или обновить уже существующую страницу. Для этого вам нужно экспортировать только тег Canvas.

```csharp
[C#]

using (var image = Image.Load(@"Sample.svg"))
{
    image.Save(@"Canvas.html", new Html5CanvasOptions
    {
        VectorRasterizationOptions = new SvgRasterizationOptions(),
        FullHtmlPage = false
    });
}
```

### Смотрите также

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* пространство имен [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
