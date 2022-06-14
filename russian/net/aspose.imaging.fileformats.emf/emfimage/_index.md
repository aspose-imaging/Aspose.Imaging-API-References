---
title: EmfImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Изображение в формате EMF.
type: docs
weight: 4670
url: /ru/net/aspose.imaging.fileformats.emf/emfimage/
---
## EmfImage class

Изображение в формате EMF.

```csharp
public sealed class EmfImage : MetaImage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfImage](emfimage#constructor)() | Инициализирует новый экземпляр класса[`EmfImage`](../emfimage). |
| [EmfImage](emfimage#constructor_1)(int, int) | Инициализирует новый экземпляр класса[`EmfImage`](../emfimage). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Получает или задает значение цвета фона. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.emf/emfimage/bitsperpixel) { get; } | Получает количество бит изображения на пиксель. Этот параметр неприменим к векторным изображениям |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [Container](../../aspose.imaging/image/container) { get; } | Получает контейнер[`Image`](../../aspose.imaging/image). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| override [FileFormat](../../aspose.imaging.fileformats.emf/emfimage/fileformat) { get; } | Получает значение формата файла |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| [Header](../../aspose.imaging.fileformats.emf/emfimage/header) { get; set; } | Получает или устанавливает запись заголовка |
| override [Height](../../aspose.imaging.fileformats.emf/emfimage/height) { get; } | Получает высоту изображения. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Получает высоту объекта в дюймах. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Получает или устанавливает монитор прерываний. |
| override [IsCached](../../aspose.imaging.fileformats.emf/emfimage/iscached) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные объекта и чтение данных не требуется. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| override [Records](../../aspose.imaging.fileformats.emf/emfimage/records) { get; set; } | Получает или устанавливает записи. |
| [Size](../../aspose.imaging/image/size) { get; } | Получает размер изображения. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Получает размер объекта в дюймах. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Получает значение, указывающее, используется ли палитра изображения. |
| override [Width](../../aspose.imaging.fileformats.emf/emfimage/width) { get; } | Получает ширину изображения. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Получает ширину объекта в дюймах. |

## Методы

| Имя | Описание |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.emf/emfimage/cachedata)() | Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполняться из базового[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer). |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| override [Crop](../../aspose.imaging.fileformats.emf/emfimage/crop#crop)(Rectangle) | Обрезает указанный прямоугольник. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop)(int, int, int, int) | Обрезать изображение со сдвигами. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.emf/emfimage/getdefaultoptions)(object[]) | Получает параметры по умолчанию. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Получает внедренные изображения. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts)() | Возвращает список шрифтов, которые использовались внутри метафайла, но не были найдены. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Получает параметры на основе исходных настроек файла. Это может быть полезно для сохранения битовой глубины и других параметров исходного изображения без изменений. Например, если мы загрузим черно-белое изображение PNG с 1 битом на пиксель, а затем сохраним его с помощью [`Save`](../../aspose.imaging/datastreamsupporter/save)будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их в[`Save`](../../aspose.imaging/image/save)метод в качестве второго параметра. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.emf/emfimage/getusedfonts)() | Возвращает список шрифтов, используемых внутри метафайла. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Изменяет размер изображения. По умолчанию используетсяNearestNeighbourResample. |
| override [Resize](../../aspose.imaging.fileformats.emf/emfimage/resize#resize_1)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.imaging.fileformats.emf/emfimage/resize#resize_2)(int, int, ResizeType) | Изменяет размер изображения. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.emf/emfimage/resizecanvas)(Rectangle) | Изменяет размер холста. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Пропорционально изменяет размер высоты. По умолчанию используетсяNearestNeighbourResample. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Пропорционально изменяет размер высоты. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Пропорционально изменяет размер высоты. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Пропорционально изменяет ширину. По умолчанию используетсяNearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Пропорционально изменяет ширину. |
| override [RotateFlip](../../aspose.imaging.fileformats.emf/emfimage/rotateflip)(RotateFlipType) | Вращает, переворачивает или поворачивает и переворачивает изображение. |
| [Save](../../aspose.imaging/image/save)() | Сохраняет данные изображения в основной поток. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Сохраняет данные объекта в указанный поток. |
| override [Save](../../aspose.imaging/image/save)(string) | Сохраняет изображение в указанное местоположение файла. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Сохраняет данные объекта в указанном месте файла. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| override [SetPalette](../../aspose.imaging.fileformats.emf/emfimage/setpalette)(IColorPalette, bool) | Устанавливает палитру изображения. |

### Примеры

В следующем примере показано, как преобразовать изображения emz в emf fromat

```csharp
[C#]

string dir = "c:\\temp\\";

 // Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки всех типов изображений, включая EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

     // Текст будет преобразован в фигуры.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

     // Цвет фона поверхности рисования.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

     // Размер страницы.
    rasterizationOptions.PageSize = emfImage.Size;

     // Если встроенная ЭДС существует, то визуализировать ЭДС; в противном случае визуализируйте wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

     // Установить горизонтальное поле
    rasterizationOptions.BorderX = 50;

     // Устанавливаем вертикальную маржу
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

В следующем примере показано, как преобразовать изображения emf в emz fromat

```csharp
[C#]

string dir = "c:\\temp\\";

 // Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки всех типов изображений, включая EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

     // Текст будет преобразован в фигуры.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

     // Цвет фона поверхности рисования.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

     // Размер страницы.
    rasterizationOptions.PageSize = emfImage.Size;

     // Если встроенная ЭДС существует, то визуализировать ЭДС; в противном случае визуализируйте wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

     // Установить горизонтальное поле
    rasterizationOptions.BorderX = 50;

     // Устанавливаем вертикальную маржу
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

В следующем примере показано, как преобразовать сжатые изображения (*.emz, *.wmz, *.svgz) в растр из at

```csharp
[C#]

string dir = "c:\\temp\\";

 // Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки всех типов изображений, включая EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

     // Текст будет преобразован в фигуры.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

     // Цвет фона поверхности рисования.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

     // Размер страницы.
    rasterizationOptions.PageSize = emfImage.Size;

     // Если встроенная ЭДС существует, то визуализировать ЭДС; в противном случае визуализируйте wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

     // Установить горизонтальное поле
    rasterizationOptions.BorderX = 50;

     // Устанавливаем вертикальную маржу
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

В этом примере показано, как загрузить изображение EMF из файла и преобразовать его в SVG с помощью EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки всех типов изображений, включая EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

     // Текст будет преобразован в фигуры.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

     // Цвет фона поверхности рисования.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

     // Размер страницы.
    rasterizationOptions.PageSize = emfImage.Size;

     // Если встроенная ЭДС существует, то визуализировать ЭДС; в противном случае визуализируйте wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

     // Установить горизонтальное поле
    rasterizationOptions.BorderX = 50;

     // Устанавливаем вертикальную маржу
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### Смотрите также

* class [MetaImage](../metaimage)
* пространство имен [Aspose.Imaging.FileFormats.Emf](../../aspose.imaging.fileformats.emf)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
