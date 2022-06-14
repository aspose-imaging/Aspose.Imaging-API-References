---
title: EmfStretchDiBits
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_STRETCHDIBITS определяет блочный перенос пикселей из исходного растрового изображения в прямоугольник назначения  возможно в сочетании с рисунком кисти согласно указанный растр операция растягивание или сжатие вывода чтобы соответствовать размерам места назначения если это необходимо.
type: docs
weight: 4600
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
## EmfStretchDiBits class

Запись EMR_STRETCHDIBITS определяет блочный перенос пикселей из исходного растрового изображения в прямоугольник назначения , возможно, в сочетании с рисунком кисти, согласно указанный растр операция, растягивание или сжатие вывода, чтобы соответствовать размерам места назначения, если это необходимо.

```csharp
public sealed class EmfStretchDiBits : EmfBitmapRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfStretchDiBits](emfstretchdibits)(EmfRecord) | Инициализирует новый экземпляр класса[`EmfStretchDiBits`](../emfstretchdibits). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bitbltrasteroperation) { get; set; } | Получает или задает 32-разрядное целое число без знака, определяющее код растровой операции . Эти коды определяют, как данные цвета исходного прямоугольника должны быть объединены с данными цвета прямоугольника назначения и, возможно, образцом кисти для получения окончательного цвета. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bounds) { get; set; } | Получает или задает объект WMF RectL ([MS-WMF], раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах устройства. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxdest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую ширину целевого прямоугольника. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее ширину исходного прямоугольника в пикселях. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cydest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую высоту целевого прямоугольника. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее высоту исходного прямоугольника в пикселях. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или устанавливает размер записи |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/sourcebitmap) { get; set; } | Получает или задает буфер, содержащий исходное растровое изображение, которое не обязательно должно быть непрерывным с фиксированной частью записи EMR_STRETCHDIBITS. Соответственно, поля в этого буфера, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/usagesrc) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее, как интерпретировать значения в таблице цветов в заголовке исходного растрового изображения. Это значение ДОЛЖНО быть в перечислении DIBColors (раздел 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xdest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату x левого верхнего угла целевого прямоугольника. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее координату x в пикселях левого верхнего угла исходного прямоугольника. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ydest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату y левого верхнего угла целевого прямоугольника. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее координату y в пикселях левого верхнего угла исходного прямоугольника. |

### Примечания

Эта запись поддерживает исходные изображения в форматах JPEG и PNG. Поле Compression в исходном заголовке растрового изображения определяет формат изображения. Если знаки исходного и целевого полей высоты и ширины различаются, эта запись задает зеркальную копию исходного растрового изображения в место назначения. То есть, если cxSrc и cxDest имеют разные знаки, то указывается зеркальное отображение исходного растрового изображения по оси x. Если cySrc и cyDest имеют разные знаки, указывается зеркальное отображение исходного растрового изображения по оси Y.

### Смотрите также

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
