---
title: WmfBitmapInfoHeader
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект BitmapInfoHeader содержит информацию о размерах и цветовом формате аппаратно-независимого растрового изображения DIB.
type: docs
weight: 8470
url: /ru/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

Объект BitmapInfoHeader содержит информацию о размерах и цветовом формате аппаратно-независимого растрового изображения (DIB).

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount) { get; set; } | Получает или задает 16-разрядное целое число без знака, определяющее формат каждого пикселя и максимальное количество цветов в DIB. Это значение ДОЛЖНО быть в[`BitCount`](../wmfbitmapbaseheader/bitcount) Перечисление (раздел 2.1.1.3). |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое определяет количество индексов цвета, необходимых для отображения DIB. Если это значение равно нулю, требуются все индексы цвета |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее количество индексов в таблице цветов, используемой DIB, поскольку следует: Если это значение равно нулю, DIB использует максимальное количество цветов, соответствующих значению BitCount. Если это значение не равно нулю, а значение BitCount меньше 16, это значение указывает количество цветов, используемых DIB. Если это значение не равно нулю, а значение BitCount равно 16 или больше, это значение указывает размер цвета table используется для оптимизации производительности системной палитры. Примечание. Если это значение не равно нулю и превышает максимально возможный размер таблицы цветов на основе значения BitCount , СЛЕДУЕТ использовать максимальный размер таблицы цветов. |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression) { get; set; } | Получает или задает 32-разрядное целое число без знака, определяющее режим сжатия DIB. Это значение ДОЛЖНО быть в перечислении сжатия (раздел 2.1.1.7). Это значение НЕ ДОЛЖНО указывать сжатый формат, если DIB является растровым изображением сверху вниз, как указано значением высоты. |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize) { get; set; } | Получает или задает 32-разрядное целое число без знака, определяющее размер объекта this в байтах. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height) { get; set; } | Получает или задает 32-разрядное целое число со знаком, определяющее высоту DIB в пикселях. Это значение НЕ ДОЛЖНО быть равно нулю. Если это значение положительное, DIB является растровым изображением снизу вверх, а его источником является нижний левый угол. Если это значение отрицательное, DIB является растровым изображением сверху вниз, его начало — верхний левый угол. Растровые изображения сверху вниз не поддерживают сжатие. В этом поле СЛЕДУЕТ указывать высоту распакованного файла изображения, если значение Compression указывает формат JPEG или PNG . |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize) { get; set; } | Получает или задает 32-битное целое число без знака, которое определяет размер изображения в байтах. Если значение сжатия равно BI_RGB, это значение ДОЛЖНО быть равно нулю и ДОЛЖНО игнорироваться. это значение ДОЛЖНО указывать размер буфера изображения JPEG или PNG, соответственно. |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes) { get; set; } | Получает или задает 16-разрядное целое число без знака, определяющее число planes для целевого устройства. Это значение ДОЛЖНО быть 0x0001. |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width) { get; set; } | Получает или задает 32-разрядное целое число со знаком, определяющее ширину DIB в пикселях. Это значение ДОЛЖНО быть положительным. В этом поле СЛЕДУЕТ указывать ширину распакованного файла изображения, если значение Compression указывает формат JPEG или PNG . |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter) { get; set; } | Получает или задает 32-разрядное целое число со знаком, определяющее горизонтальное разрешение в пикселях на метр устройства target для DIB |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter) { get; set; } | Получает или задает 32-разрядное целое число со знаком, определяющее вертикальное разрешение в пикселях на метр устройства target для DIB |

## Поля

| Имя | Описание |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize) | Размер структуры |

### Смотрите также

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader)
* пространство имен [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
