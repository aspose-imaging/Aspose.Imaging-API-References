---
title: TiffTags
second_title: Справочник по Aspose.Imaging for .NET API
description: Перечисление тега tiff.
type: docs
weight: 7740
url: /ru/net/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

Перечисление тега tiff.

```csharp
public enum TiffTags
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| SubFileType | `254` | Дескриптор данных подфайла. |
| OsubfileType | `255` | [устарело TIFF rev. 5.0]&lt;br /&gt; Тип данных в подфайле. |
| ImageWidth | `256` | Ширина изображения в пикселях. |
| ImageLength | `257` | Высота изображения в пикселях. |
| BitsPerSample | `258` | Бит на канал (выборка). |
| Compression | `259` | Техника сжатия данных. |
| Photometric | `262` | Фотометрическая интерпретация. |
| Thresholding | `263` | [устарело TIFF rev. 5.0]&lt;br /&gt; Для данных используется пороговое значение. |
| CellWidth | `264` | [устарело TIFF rev. 5.0]&lt;br /&gt; Ширина матрицы дизеринга. |
| CellLength | `265` | [устарело TIFF rev. 5.0]&lt;br /&gt; Высота матрицы дизеринга. |
| FillOrder | `266` | Порядок данных внутри байта. |
| DocumentName | `269` | Имя документа, который содержит изображение. |
| ImageDescription | `270` | Информация об изображении. |
| Make | `271` | Название производителя сканера. |
| Model | `272` | Название/номер модели сканера. |
| StripOffsets | `273` | Смещения к полосам данных. |
| Orientation | `274` | [устарело TIFF rev. 5.0]&lt;br /&gt; Ориентация изображения. |
| SamplesPerPixel | `277` | Выборки на пиксель. |
| RowsPerStrip | `278` | Количество строк на полосу данных. |
| StripByteCounts | `279` | Количество байтов для полос. |
| MinSampleValue | `280` | [устарело TIFF rev. 5.0]&lt;br /&gt; Минимальное значение выборки. |
| MaxSampleValue | `281` | [устарело TIFF rev. 5.0]&lt;br /&gt; Максимальное значение выборки. |
| Xresolution | `282` | Пиксели/разрешение в x. |
| Yresolution | `283` | Пиксели/разрешение в y. |
| PlanarConfig | `284` | Организация хранения. |
| PageName | `285` | Изображение с названия страницы. |
| Xposition | `286` | Смещение X страницы изображения слева. |
| Yposition | `287` | Смещение Y страницы изображения слева. |
| FreeOffsets | `288` | [устарело TIFF rev. 5.0]&lt;br /&gt; Байтовое смещение до свободного блока. |
| FreeByteCounts | `289` | [устарело TIFF rev. 5.0]&lt;br /&gt; Размеры свободных блоков. |
| GrayResponseUnit | `290` | [устарело TIFF rev. 6.0]&lt;br /&gt; Точность кривой шкалы серого. |
| GrayResponseCurve | `291` | [устарело TIFF rev. 6.0]&lt;br /&gt; Кривая отклика шкалы серого. |
| T4Options | `292` | Псевдоним собственного имени TIFF 6.0 для GROUP3OPTIONS. Параметры кодирования факса CCITT Group 3. 32 флаговых бита. |
| T6Options | `293` | Параметры кодирования факса CCITT Group 4. 32 флаговых бита. Псевдоним собственного имени TIFF 6.0 для GROUP4OPTIONS. |
| ResolutionUnit | `296` | Единицы разрешения. |
| PageNumber | `297` | Номера страниц многостраничного. |
| ColorResponseUnit | `300` | [устарело TIFF rev. 6.0]&lt;br /&gt; Точность цветовой кривой. |
| TransferFunction | `301` | Колориметрическая информация. |
| Software | `305` | Имя &amp; выпускать. |
| DateTime | `306` | Дата и время создания. |
| Artist | `315` | Создатель образа. |
| HostComputer | `316` | Машина, на которой создана. |
| Predictor | `317` | Схема предсказания с LZW. |
| WhitePoint | `318` | Белая точка изображения. |
| PrimaryChromaticities | `319` | Первичные цветности. |
| ColorMap | `320` | Карта RGB для изображения палитры. |
| HalftoneHints | `321` | Информация о бликах и тенях. |
| TileWidth | `322` | Ширина тайла в пикселях. |
| TileLength | `323` | Высота тайла в пикселях. |
| TileOffsets | `324` | Смещения к листам данных. |
| TileByteCounts | `325` | Количество байтов для тайлов. |
| BadFaxLines | `326` | Линии с неправильным количеством пикселей. |
| CleanFaxData | `327` | Восстановленная информация о строке. |
| ConsecutiveBadFaxLines | `328` | Максимальное количество последовательных плохих строк. |
| SubIfd | `330` | Дескрипторы подобраза. |
| InkSet | `332` | Краски в отдельном изображении. |
| InkNames | `333` | ASCII имена красок. |
| NumberOfInks | `334` | Количество чернил. |
| DotRange | `336` | 0% и 100% точечные коды. |
| TargetPrinter | `337` | Цель разделения. |
| ExtraSamples | `338` | Информация о дополнительных образцах. |
| SampleFormat | `339` | Формат образца данных. |
| SminSampleValue | `340` | Переменная MinSampleValue. |
| SmaxSampleValue | `341` | Переменная MaxSampleValue. |
| TransferRange | `342` | Переменная TransferRange |
| ClipPath | `343` | Путь клипа. Представлен пост TIFF rev 6.0 от Adobe TIFF technote 2. |
| Xclippathunits | `344` | XClipPathUnits. Представлен пост TIFF rev 6.0 от Adobe TIFF technote 2. |
| Yclippathunits | `345` | YClipPathUnits. Представлен пост TIFF rev 6.0 от Adobe TIFF technote 2. |
| Indexed | `346` | Индексировано. Представлен пост TIFF rev 6.0 от Adobe TIFF Technote 3. |
| JpegTables | `347` | Поток таблицы JPEG. Представлен пост TIFF rev 6.0. |
| OpiProxy | `351` | Прокси OPI. Представлен пост TIFF rev 6.0 технической заметкой Adobe TIFF. |
| JpegProc | `512` | [устарело Техническим примечанием № 2, в котором указывается пересмотренная схема JPEG-in-TIFF]&lt;br /&gt; Алгоритм обработки JPEG. |
| JpegInerchangeFormat | `513` | [устарело Техническим примечанием № 2, в котором указывается пересмотренная схема JPEG-in-TIFF]&lt;br /&gt; Указатель на маркер SOI. |
| JpegInterchangeFormatLength | `514` | [устарело Техническим примечанием № 2, в котором указывается пересмотренная схема JPEG-in-TIFF]&lt;br /&gt; Длина потока JFIF |
| JpegRestartInterval | `515` | [устарело техническим примечанием № 2, в котором указывается пересмотренная схема JPEG-in-TIFF]&lt;br /&gt; Длина интервала перезапуска. |
| JpegLosslessPredictors | `517` | [устарело Техническим примечанием № 2, в котором указывается пересмотренная схема JPEG-in-TIFF]&lt;br /&gt; Предсказатель procless без потерь. |
| JpegPointTransform | `518` | [устарело Техническим примечанием № 2, в котором указывается пересмотренная схема JPEG-in-TIFF]&lt;br /&gt; Точечное преобразование без потерь. |
| JpegQTables | `519` | [устарело Техническим примечанием № 2, в котором указывается пересмотренная схема JPEG-in-TIFF]&lt;br /&gt; Смещения матрицы Q. |
| JpegDCtables | `520` | [устарело Техническим примечанием № 2, в котором указывается пересмотренная схема JPEG-in-TIFF]&lt;br /&gt; Табличные смещения DCT. |
| JpegACtables | `521` | [устарело Техническим примечанием № 2, в котором указывается пересмотренная схема JPEG-in-TIFF]&lt;br /&gt; Смещения коэффициента AC. |
| YcbcrCoefficients | `529` | RGB -&gt; Преобразование YCbCr. |
| YcbcrSubSampling | `530` | Коэффициенты подвыборки YCbCr. |
| YcbcrPositioning | `531` | Позиционирование подвыборки. |
| ReferenceBlackWhite | `532` | Колориметрическая информация. |
| XmlPacket | `700` | Пакет XML. Представлена версия TIFF версии 6.0 по спецификации Adobe XMP, январь 2004 г. |
| OpiImageid | `32781` | Идентификатор изображения OPI. Представлен пост TIFF rev 6.0 технической заметкой Adobe TIFF. |
| Refpts | `32953` | Опорные точки изображения. Частный тег, зарегистрированный в Island Graphics. |
| Copyright | `33432` | Строка авторских прав. Этот тег указан в TIFF rev. 6.0 с неизвестным владельцем. |
| PhotoshopResources | `34377` | Ресурсы изображений Photoshop. |
| IccProfile | `34675` | Встроенный профиль устройства ICC |
| ExifIfdPointer | `34665` | Указатель на Exif IFD. |
| XPTitle | `40091` | Информация об изображении, используемом проводником Windows. XPTitleигнорируется проводником Windows, еслиImageDescriptionсуществует. |
| XPComment | `40092` | Комментарий к изображению, используемому проводником Windows. |
| XPAuthor | `40093` | Автор изображения, используемый проводником Windows. XPAuthorигнорируется проводником Windows, еслиArtistсуществует. |
| XPKeywords | `40094` | Ключевые слова изображения, используемые Проводником Windows. |
| XPSubject | `40095` | Изображение темы, используемое проводником Windows. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
