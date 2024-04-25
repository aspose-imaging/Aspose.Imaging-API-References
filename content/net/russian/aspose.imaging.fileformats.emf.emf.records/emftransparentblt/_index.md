---
title: EmfTransparentBlt
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_TRANSPARENTBLT определяет блочную передачу пикселей из исходного растрового изображения в целевой прямоугольник  обрабатывая указанный цвет как прозрачный растягивая или сжимая выходные данные  чтобы они соответствовали размерам назначения если это необходимо
type: docs
weight: 4640
url: /ru/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
## EmfTransparentBlt class

Запись EMR_TRANSPARENTBLT определяет блочную передачу пикселей из исходного растрового изображения в целевой прямоугольник , обрабатывая указанный цвет как прозрачный, растягивая или сжимая выходные данные , чтобы они соответствовали размерам назначения, если это необходимо

```csharp
public sealed class EmfTransparentBlt : EmfBitmapRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfTransparentBlt](emftransparentblt)(EmfRecord) | Инициализирует новый экземпляр[`EmfTransparentBlt`](../emftransparentblt) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/bounds) { get; set; } | Получает или задает объект WMF RectL ([MS-WMF], раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах измерения устройства. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxdest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую ширину целевого прямоугольника. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую ширину исходного прямоугольника. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cydest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую высоту целевого прямоугольника. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую высоту исходного прямоугольника. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или задает размер записи |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/sourcebitmap) { get; set; } | Получает или задает буфер, содержащий исходное растровое изображение, которое не обязательно должно быть непрерывным с фиксированной частью записи EMR_TRANSPARENTBLT. Соответственно, поля в этого буфера, помеченные как «UndefinedSpace», являются необязательными и ДОЛЖНЫ игнорироваться. |
| [SrcBkArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/srcbkargb32color) { get; set; } | Получает или задает объект WMF ColorRef, указывающий цвет фона исходного растрового изображения. |
| [TransparentArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/transparentargb32color) { get; set; } | Получает или задает объект WMF ColorRef ([MS-WMF], раздел 2.2.2.8), который указывает цвет исходного растрового изображения, который следует рассматривать как прозрачный. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/usagesrc) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее, как интерпретировать значения в таблице цветов в заголовке исходного растрового изображения. Это значение ДОЛЖНО быть в перечислении DIBColors (раздел 2.1.9) |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xdest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату x левого верхнего угла целевого прямоугольника. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xformsrc) { get; set; } | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование мирового пространства в пространство страницы для применения к исходному растровому изображению. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату x левого верхнего угла исходного прямоугольника. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ydest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату Y левого верхнего угла целевого прямоугольника. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату y левого верхнего угла исходного прямоугольника. |

### Смотрите также

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
