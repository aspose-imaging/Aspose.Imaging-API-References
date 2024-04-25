---
title: BitmapV5Header
second_title: Справочник по Aspose.Imaging for .NET API
description: Структура BitmapV5Header представляет собой файл заголовка информации о растровой карте. Это расширенная версия структуры BITMAPINFOHEADER. Если bV5Height имеет отрицательное значение указывая на DIB сверху вниз bV5Compression должен быть либо BI_RGB либо BI_BITFIELDS. Нисходящие DIB не могут быть сжаты. Интерфейс независимого управления цветом ICM 2.0 позволяет связывать или встраивать цветовые профили Международного консорциума по цвету ICC в DIB DIB. Дополнительные сведения см. в разделе Использование структур. Когда DIB загружается в память данные профиля если они есть должны следовать за таблицей цветов  а bV5ProfileData должен обеспечивать смещение данных профиля от начала структуры BITMAPV5HEADER. Значение хранящееся в bV5ProfileData будет отличаться от значения возвращаемого оператором sizeof с аргументом BITMAPV5HEADER  поскольку bV5ProfileData  это смещение в байтах от начала структуры BITMAPV5HEADER до начала данных профиля. Биты растрового изображения не соответствуют таблице цветов в памяти. Приложения должны изменить элемент bV5ProfileData после загрузки DIB в память. Для упакованных DIB данные профиля должны следовать за битами растрового изображения аналогичными формату файла. Элемент bV5ProfileData должен по-прежнему указывать смещение данных профиля от начала BITMAPV5HEADER. Приложения должны получать доступ к данным профиля только в том случае если bV5Size равен размеру BITMAPV5HEADER а bV5CSType равен PROFILE_EMBEDDED или PROFILE_LINKED.
type: docs
weight: 1370
url: /ru/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

Структура BitmapV5Header представляет собой файл заголовка информации о растровой карте. Это расширенная версия структуры BITMAPINFOHEADER. Если bV5Height имеет отрицательное значение, указывая на DIB сверху вниз, bV5Compression должен быть либо BI_RGB, либо BI_BITFIELDS. Нисходящие DIB не могут быть сжаты. Интерфейс независимого управления цветом (ICM) 2.0 позволяет связывать или встраивать цветовые профили Международного консорциума по цвету (ICC) в DIB (DIB). Дополнительные сведения см. в разделе Использование структур. Когда DIB загружается в память, данные профиля (если они есть) должны следовать за таблицей цветов, , а bV5ProfileData должен обеспечивать смещение данных профиля от начала структуры BITMAPV5HEADER. Значение, хранящееся в bV5ProfileData, будет отличаться от значения, возвращаемого оператором sizeof с аргументом BITMAPV5HEADER, , поскольку bV5ProfileData — это смещение в байтах от начала структуры BITMAPV5HEADER до начала данных профиля. (Биты растрового изображения не соответствуют таблице цветов в памяти). Приложения должны изменить элемент bV5ProfileData после загрузки DIB в память. Для упакованных DIB данные профиля должны следовать за битами растрового изображения, аналогичными формату файла. Элемент bV5ProfileData должен по-прежнему указывать смещение данных профиля от начала BITMAPV5HEADER. Приложения должны получать доступ к данным профиля только в том случае, если bV5Size равен размеру BITMAPV5HEADER, а bV5CSType равен PROFILE_EMBEDDED или PROFILE_LINKED.

```csharp
public class BitmapV5Header : BitmapV4Header
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask) { get; set; } | Получает или задает цветовую маску, определяющую альфа-компонент каждого пикселя. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant) { get; set; } | Получает или устанавливает количество важных цветов палитры. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused) { get; set; } | Получает или задает количество используемых цветов палитры. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression) { get; set; } | Получает или задает сжатие растрового изображения. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight) { get; set; } | Получает или задает высоту растрового изображения. |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize) { get; set; } | Получает или задает размер необработанных данных растрового изображения в байтах. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes) { get; set; } | Получает или задает количество плоскостей. |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth) { get; set; } | Получает или задает ширину растрового изображения. |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter) { get; set; } | Получает или задает разрешение в пикселях по горизонтали. |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter) { get; set; } | Получает или задает разрешение в пикселях по вертикали. |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel) { get; set; } | Получает или задает количество битов на пиксель. |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask) { get; set; } | Получает или задает цветовую маску, определяющую синий компонент каждого пикселя, допустимую, только если для параметра bV4Compression задано значение BI_BITFIELDS. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype) { get; set; } | Получает или задает цветовое пространство DIB. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints) { get; set; } | Получает или задает класс CoordinatesTriple. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks) { get; set; } | Получает или устанавливает дополнительные битовые маски. Присутствует только в том случае, если заголовок DIB является BITMAPINFOHEADER, а[`BitmapCompression`](../bitmapinfoheader/bitmapcompression) установлен либоBitfields (RGB) илиAlphaBitfields (RGBA). |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue) { get; set; } | Получает или задает гамму синего. |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen) { get; set; } | Получает или задает зеленую гамму. |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared) { get; set; } | Получает или задает гамму красного цвета. |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask) { get; set; } | Получает или задает цветовую маску, определяющую зеленый компонент каждого пикселя, допустимую, только если для параметра bV4Compression задано значение BI_BITFIELDS. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize) { get; set; } | Получает или устанавливает размер этой структуры в байтах. |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent) { get; set; } | Получает или задает цель рендеринга для растрового изображения. |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata) { get; set; } | Получает или задает данные профиля. |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize) { get; set; } | Получает или задает размер профиля. |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask) { get; set; } | Получает или задает цветовую маску, указывающую красный компонент каждого пикселя, действительную, только если для параметра bV4Compression задано значение BI_BITFIELDS. |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved) { get; set; } | Получает или задает зарезервированный элемент. |

### Смотрите также

* class [BitmapV4Header](../bitmapv4header)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
