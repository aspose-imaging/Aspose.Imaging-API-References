---
title: EmfPlusSetTsGraphics
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusSetTSGraphics определяет состояние контекста графического устройства для терминального сервера.
type: docs
weight: 6410
url: /ru/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

Запись EmfPlusSetTSGraphics определяет состояние контекста графического устройства для терминального сервера.

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics)(EmfPlusRecord) | Инициализирует новый экземпляр[`EmfPlusSetTsGraphics`](../emfplussettsgraphics) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode) { get; set; } | Получает или задает 8-битное целое число без знака, указывающее качество рендеринга линий, включая тип сглаживания линий. Он ДОЛЖЕН быть определен в перечислении SmoothingMode (раздел 2.1.1.28). |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors) { get; } | Получает значение, указывающее, используются ли [основные цвета VGA]. Если установлено, палитра содержит только основные цвета VGA. |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode) { get; set; } | Получает или задает 8-разрядное целое число без знака, указывающее, как исходные цвета сочетаются с цветами фона. Это ДОЛЖНО быть значение в перечислении CompositingMode (раздел 2.1.1.5). |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality) { get; set; } | Получает или задает 8-разрядное целое число без знака, указывающее степень сглаживания, применяемую к линиям, кривым и краям заполненных областей, чтобы сделать их более непрерывными или четко определенными. Это ДОЛЖНО быть значение в перечислении CompositingQuality (раздел 2.1.1.6). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное количество байтов данных в следующем поле RecordData. Это число не включает 12-байтовый заголовок записи. |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype) { get; set; } | Получает или задает 8-битное целое число без знака, указывающее, как выполняется масштабирование, включая stretching и сжатие. Это ДОЛЖНО быть значение в перечислении FilterType (раздел 2.1.1.11). |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция, и о структуре записи. |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette) { get; } | Получает значение, указывающее, [есть ли палитра]. Если установлено, эта запись содержит объект EmfPlusPalette (раздел 2.2.2.28) в поле палитры после данных состояния графики. |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette) { get; set; } | Получает или задает необязательный объект EmfPlusPalette. |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset) { get; set; } | Получает или задает 8-разрядное целое число без знака, определяющее общее качество процесса рендеринга изображения и текста. Это ДОЛЖНО быть значение в перечислении PixelOffsetMode (раздел 2.1.1.26). |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx) { get; set; } | Получает или задает 16-разрядное целое число со знаком, которое является горизонтальной координатой начала координат для рендеринга полутоновых матриц и матриц сглаживания. |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy) { get; set; } | Получает или задает 16-разрядное целое число со знаком, которое является вертикальной координатой origin для рендеринга матриц полутонов и дизеринга. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее 32-разрядное выровненное количество байтов во всей записи, включая 12-разрядный заголовок записи и данные, относящиеся к записи. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее значение гамма-коррекции , используемое для отрисовки сглаженного текста и текста ClearType. Это значение ДОЛЖНО находиться в диапазоне от 0 до 12 включительно. |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint) { get; set; } | Получает или задает 8-битное целое число без знака, указывающее качество рендеринга text , включая тип сглаживания текста. Он ДОЛЖЕН быть определен в перечислении TextRenderingHint (раздел 2.1.1.32). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice) { get; set; } | Получает или задает 192-битный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование пространства мира в пространство устройства. |

### Смотрите также

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
