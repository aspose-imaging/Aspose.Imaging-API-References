---
title: EmfStretchBlt
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_STRETCHBLT определяет блочный перенос пикселей из исходного растрового изображения в целевой прямоугольник  опционально в сочетании с шаблоном кисти в соответствии с указанной операцией raster  растягивая или сжимая выходные данные чтобы они соответствовали размерам целевого объекта если это необходимо. .
type: docs
weight: 4590
url: /ru/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
## EmfStretchBlt class

Запись EMR_STRETCHBLT определяет блочный перенос пикселей из исходного растрового изображения в целевой прямоугольник , опционально в сочетании с шаблоном кисти, в соответствии с указанной операцией raster , растягивая или сжимая выходные данные, чтобы они соответствовали размерам целевого объекта, если это необходимо. .

```csharp
public sealed class EmfStretchBlt : EmfBitmapRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfStretchBlt](emfstretchblt#constructor)() | Инициализирует новый экземпляр[`EmfStretchBlt`](../emfstretchblt) класс. |
| [EmfStretchBlt](emfstretchblt#constructor_1)(EmfRecord) | Инициализирует новый экземпляр[`EmfStretchBlt`](../emfstretchblt) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/argb32bkcolorsrc) { get; set; } | Получает или задает объект WMF ColorRef (раздел 2.2.2.8 [MS-WMF], в котором указывается цвет фона исходного растрового изображения. |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bitbltrasteroperation) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее код растровой операции . Этот код определяет, как данные цвета исходного прямоугольника должны быть объединены с данными цвета целевого прямоугольника и, возможно, с рисунком кисти, чтобы получить окончательный цвет |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bounds) { get; set; } | Получает или задает объект WMF RectL ([MS-WMF], раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах измерения устройства. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxdest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую ширину целевого прямоугольника. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую ширину исходного прямоугольника. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cydest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую высоту целевого прямоугольника. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую высоту исходного прямоугольника. |
| [DestRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/destrect) { get; set; } | Получает или задает адрес назначения. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или задает размер записи |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/sourcebitmap) { get; set; } | Получает или задает буфер, содержащий исходное растровое изображение, которое не обязательно должно быть непрерывным с фиксированной частью записи EMR_STRETCHBLT. Соответственно, поля в этом буфере , помеченные как «UndefinedSpace», являются необязательными и ДОЛЖНЫ игнорироваться. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/srcrect) { get; set; } | Получает или задает исходный прямоугольник. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/usagesrc) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее, как интерпретировать значения в таблице цветов в заголовке исходного растрового изображения. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xdest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату x левого верхнего угла целевого прямоугольника. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xformsrc) { get; set; } | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование мирового пространства в пространство страницы для применения к исходному растровому изображению. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату x левого верхнего угла исходного прямоугольника. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ydest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату Y левого верхнего угла целевого прямоугольника. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату y левого верхнего угла исходного прямоугольника. |

### Смотрите также

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
