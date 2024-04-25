---
title: CdrImagePage
second_title: Справочник по Aspose.Imaging for .NET API
description: Страница образа Cdr
type: docs
weight: 1430
url: /ru/aspose.imaging.fileformats.cdr/cdrimagepage/
---
## CdrImagePage class

Страница образа Cdr

```csharp
public class CdrImagePage : VectorImage, ICdrImage
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Получает или задает значение цвета фона. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.cdr/cdrimagepage/bitsperpixel) { get; } | Получает количество бит изображения на пиксель. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [CdrDocument](../../aspose.imaging.fileformats.cdr/cdrimagepage/cdrdocument) { get; } | Получает или задает документ CDR. |
| [Container](../../aspose.imaging/image/container) { get; } | Получает[`Image`](../../aspose.imaging/image) контейнер. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| override [FileFormat](../../aspose.imaging.fileformats.cdr/cdrimagepage/fileformat) { get; } | Получает значение формата файла |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| override [Height](../../aspose.imaging.fileformats.cdr/cdrimagepage/height) { get; } | Получает высоту изображения. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Получает высоту объекта в дюймах. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Получает или устанавливает монитор прерываний. |
| override [IsCached](../../aspose.imaging.fileformats.cdr/cdrimagepage/iscached) { get; } | Получает значение, указывающее, кэшируются ли данные объекта в данный момент и чтение данных не требуется. |
| [PageNumber](../../aspose.imaging.fileformats.cdr/cdrimagepage/pagenumber) { get; } | Получает номер страницы. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| [ParentImage](../../aspose.imaging.fileformats.cdr/cdrimagepage/parentimage) { get; } | Получает родительский образ. |
| [Size](../../aspose.imaging/image/size) { get; } | Получает размер изображения. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Получает размер объекта в дюймах. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Получает значение, указывающее, используется ли палитра изображения. |
| override [Width](../../aspose.imaging.fileformats.cdr/cdrimagepage/width) { get; } | Получает ширину изображения. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Получает ширину объекта в дюймах. |

## Методы

| Имя | Описание |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.cdr/cdrimagepage/cachedata)() | Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполняться из базового[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанном формате файла, представленном переданными параметрами сохранения. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Получает параметры по умолчанию. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Получает встроенные изображения. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Получает параметры, основанные на настройках исходного файла. Это может быть полезно для сохранения без изменений битовой глубины и других параметров исходного изображения. Например, если мы загружаем черно-белое изображение PNG с 1 битом на пиксель, а затем сохраните его, используя the [`Save`](../../aspose.imaging/datastreamsupporter/save) будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их [`Save`](../../aspose.imaging/image/save) метод в качестве второго параметра. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Изменяет размер изображения. По умолчаниюNearestNeighbourResample используется. |
| override [Resize](../../aspose.imaging.fileformats.cdr/cdrimagepage/resize#resize_1)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.imaging.fileformats.cdr/cdrimagepage/resize#resize_2)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Изменяет размер высоты пропорционально. По умолчаниюNearestNeighbourResample используется. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Изменяет размер высоты пропорционально. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Изменяет размер высоты пропорционально. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Изменяет ширину пропорционально. По умолчаниюNearestNeighbourResample используется. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Изменяет ширину пропорционально. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Изменяет ширину пропорционально. |
| override [RotateFlip](../../aspose.imaging.fileformats.cdr/cdrimagepage/rotateflip)(RotateFlipType) | Вращает, переворачивает или поворачивает и переворачивает изображение. |
| [Save](../../aspose.imaging/image/save)() | Сохраняет данные изображения в базовый поток. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Сохраняет данные объекта в указанный поток. |
| override [Save](../../aspose.imaging/image/save)(string) | Сохраняет изображение в указанном месте файла. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Сохраняет данные объекта в указанном месте файла. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| override [SetPalette](../../aspose.imaging.fileformats.cdr/cdrimagepage/setpalette)(IColorPalette, bool) | Задает палитру изображения. |

### Смотрите также

* class [Image](../../aspose.imaging/image)
* interface [ICdrImage](../icdrimage)
* class [VectorImage](../../aspose.imaging/vectorimage)
* пространство имен [Aspose.Imaging.FileFormats.Cdr](../../aspose.imaging.fileformats.cdr)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
