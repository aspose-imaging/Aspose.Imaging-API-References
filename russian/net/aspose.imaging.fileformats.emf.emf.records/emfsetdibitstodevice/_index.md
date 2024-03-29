---
title: EmfSetDiBitsToDevice
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_SETDIBITSTODEVICE определяет блочную передачу пикселей из указанных строк развертки исходного растрового изображения в прямоугольник назначения.
type: docs
weight: 4330
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
## EmfSetDiBitsToDevice class

Запись EMR_SETDIBITSTODEVICE определяет блочную передачу пикселей из указанных строк развертки исходного растрового изображения в прямоугольник назначения.

```csharp
public sealed class EmfSetDiBitsToDevice : EmfBitmapRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfSetDiBitsToDevice](emfsetdibitstodevice)(EmfRecord) | Инициализирует новый экземпляр[`EmfSetDiBitsToDevice`](../emfsetdibitstodevice) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/bounds) { get; set; } | Получает или задает объект WMF RectL ([MS-WMF], раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах измерения устройства. |
| [CScans](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cscans) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее количество строк развертки. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cxsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее ширину исходного прямоугольника в пикселях. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее высоту исходного прямоугольника в пикселях. |
| [IStartScan](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/istartscan) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее первую строку сканирования в массиве. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или задает размер записи |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/sourcebitmap) { get; set; } | Получает или задает буфер, содержащий исходное растровое изображение, которое не обязательно должно быть непрерывным с фиксированной частью записи EMR_SETDIBITSTODEVICE. Соответственно, поля в этом буфере с пометкой «UndefinedSpace» являются необязательными и ДОЛЖНЫ игнорироваться. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/usagesrc) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее, как интерпретировать значения в таблице цветов в заголовке исходного растрового изображения. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/xdest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату x левого верхнего угла целевого прямоугольника. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/xsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее координату x в пикселях нижнего левого угла исходного прямоугольника. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/ydest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату Y левого верхнего угла целевого прямоугольника. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/ysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее координату Y в пикселях нижнего левого угла исходного прямоугольника. |

### Примечания

Эта запись поддерживает исходные изображения в формате JPEG и PNG. Поле Compression в заголовке исходного растрового изображения указывает формат изображения.

### Смотрите также

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
