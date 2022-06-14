---
title: EpsBinaryImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Класс для формата Encapsulated PostScript с двоичным заголовком
type: docs
weight: 6550
url: /ru/net/aspose.imaging.fileformats.eps/epsbinaryimage/
---
## EpsBinaryImage class

Класс для формата Encapsulated PostScript с двоичным заголовком

```csharp
public class EpsBinaryImage : EpsImage
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Получает или задает значение цвета фона. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel) { get; } | Получает количество бит изображения на пиксель. |
| [BoundingBoxBottomLeft](../../aspose.imaging.fileformats.eps/epsimage/boundingboxbottomleft) { get; } | Получает нижнее левое положение ограничительной рамки |
| [BoundingBoxString](../../aspose.imaging.fileformats.eps/epsimage/boundingboxstring) { get; } | Получает строковое значение BoundingBox |
| [BoundingBoxTopRight](../../aspose.imaging.fileformats.eps/epsimage/boundingboxtopright) { get; } | Получает верхнюю правую позицию ограничительной рамки |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [Container](../../aspose.imaging/image/container) { get; } | Получает контейнер[`Image`](../../aspose.imaging/image). |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate) { get; } | Получает поле CreationDate |
| [CreationDateString](../../aspose.imaging.fileformats.eps/epsimage/creationdatestring) { get; } | Получает строковое значение поля CreationDate |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator) { get; } | Получает поле Creator |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| override [EpsType](../../aspose.imaging.fileformats.eps/epsbinaryimage/epstype) { get; } | Получает значение подтипа EPS |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat) { get; } | Получает значение формата файла |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| override [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsbinaryimage/hasrasterpreview) { get; } | Получает значение, указывающее, имеет ли данный экземпляр предварительный просмотр растра для конкретного формата |
| override [Height](../../aspose.imaging.fileformats.eps/epsimage/height) { get; } | Получает высоту изображения. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Получает высоту объекта в дюймах. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Получает или устанавливает монитор прерываний. |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные объекта и чтение данных не требуется. |
| [PageNumber](../../aspose.imaging.fileformats.eps/epsimage/pagenumber) { get; } | Получает номер страницы |
| [PagesCount](../../aspose.imaging.fileformats.eps/epsimage/pagescount) { get; } | Получает количество страниц |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| [PhotoshopThumbnail](../../aspose.imaging.fileformats.eps/epsimage/photoshopthumbnail) { get; } | Получает миниатюру предварительного просмотра Photoshop (если она присутствует в исходных данных EPS) |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion) { get; } | Получает поле версии PostScript |
| [Size](../../aspose.imaging/image/size) { get; } | Получает размер изображения. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Получает размер объекта в дюймах. |
| [TiffPreview](../../aspose.imaging.fileformats.eps/epsbinaryimage/tiffpreview) { get; } | Получает предварительный просмотр TIFF. |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title) { get; } | Получает поле Заголовок |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Получает значение, указывающее, используется ли палитра изображения. |
| override [Width](../../aspose.imaging.fileformats.eps/epsimage/width) { get; } | Получает ширину изображения. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Получает ширину объекта в дюймах. |
| [WmfPreview](../../aspose.imaging.fileformats.eps/epsbinaryimage/wmfpreview) { get; } | Получает предварительный просмотр WMF. |

## Методы

| Имя | Описание |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata)() | Кэш нельзя использовать. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| [ConvertToInterchange](../../aspose.imaging.fileformats.eps/epsbinaryimage/converttointerchange)() | Преобразует этот экземпляр в[`EpsInterchangeImage`](../epsinterchangeimage) |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.eps/epsimage/getdefaultoptions)(object[]) | Получает параметры по умолчанию. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Получает внедренные изображения. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Получает параметры на основе исходных настроек файла. Это может быть полезно для сохранения битовой глубины и других параметров исходного изображения без изменений. Например, если мы загрузим черно-белое изображение PNG с 1 битом на пиксель, а затем сохраним его с помощью [`Save`](../../aspose.imaging/datastreamsupporter/save)будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их в[`Save`](../../aspose.imaging/image/save)метод в качестве второго параметра. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Изменяет размер изображения. По умолчанию используетсяNearestNeighbourResample. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Пропорционально изменяет размер высоты. По умолчанию используетсяNearestNeighbourResample. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Пропорционально изменяет размер высоты. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Пропорционально изменяет размер высоты. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Пропорционально изменяет ширину. По умолчанию используетсяNearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Пропорционально изменяет ширину. |
| override [RotateFlip](../../aspose.imaging.fileformats.eps/epsimage/rotateflip)(RotateFlipType) | Вращает, переворачивает или поворачивает и переворачивает изображение. |
| [Save](../../aspose.imaging/image/save)() | Сохраняет данные изображения в основной поток. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Сохраняет данные объекта в указанный поток. |
| override [Save](../../aspose.imaging/image/save)(string) | Сохраняет изображение в указанное местоположение файла. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Сохраняет данные объекта в указанном месте файла. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette)(IColorPalette, bool) | Устанавливает палитру изображения. |
| [explicit operator](../../aspose.imaging.fileformats.eps/epsbinaryimage/op_explicit) | Выполняет явное преобразование из[`EpsInterchangeImage`](../epsinterchangeimage)в[`EpsBinaryImage`](../epsbinaryimage) |

### Смотрите также

* class [EpsImage](../epsimage)
* пространство имен [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
