---
title: EmfPlgBlt
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_PLGBLT определяет блочный перенос пикселей из исходного растрового изображения в целевой параллелограмм с применением растрового изображения цветовой маски.
type: docs
weight: 3950
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
## EmfPlgBlt class

Запись EMR_PLGBLT определяет блочный перенос пикселей из исходного растрового изображения в целевой параллелограмм с применением растрового изображения цветовой маски.

```csharp
public sealed class EmfPlgBlt : EmfBitmapRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlgBlt](emfplgblt)(EmfRecord) | Инициализирует новый экземпляр класса[`EmfPlgBlt`](../emfplgblt). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AptlDest](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest) { get; set; } | Получает или задает массив из трех объектов WMF PointL ([MS-WMF], раздел 2.2.2.15), которые определяют три угла параллелограмма назначения место для передачи блока. Верхний левый угол исходного прямоугольника сопоставляется с первой точкой в этом массиве, верхний правый угол со второй точкой, а нижний левый угол с третий пункт. Нижний правый угол исходного прямоугольника сопоставляется с неявной четвертой точкой параллелограмма , который вычисляется из первых трех точек (A, B и C), рассматривая их как векторов. D = B + CA |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bksrcargb32color) { get; set; } | Получает или задает объект WMF ColorRef ([MS-WMF], раздел 2.2.2.8), который определяет цвет фона исходного растрового изображения. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bounds) { get; set; } | Получает или задает объект RectL WMF ([MS-WMF], раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства, для вывода в пункт назначения. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cxsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую ширину исходного прямоугольника. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую высоту исходного прямоугольника. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/maskbitmap) { get; set; } | Получает или задает буфер, содержащий растровое изображение маски, которое не обязательно должно быть непрерывным с фиксированной частью записи EMR_PLGBLT или с каждой Другой. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или устанавливает размер записи |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/sourcebitmap) { get; set; } | Получает или задает буфер, содержащий исходное растровое изображение, которое не обязательно должно быть непрерывным с фиксированной частью записи EMR_PLGBLT или с каждой Другой. Соответственно, поля в этом буфере, помеченные как "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagemask) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее, как интерпретировать значения в таблице цветов в заголовке растрового изображения маски. Это значение ДОЛЖНО быть в перечислении DIBColors. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagesrc) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее, как интерпретировать значения в таблице цветов в заголовке исходного растрового изображения. Это значение ДОЛЖНО быть в перечислении DIBColors |
| [XFormSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xformsrc) { get; set; } | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование мирового пространства в пространство страницы для применения к исходному растровому изображению. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xmask) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату x левого верхнего угла растрового изображения маски. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату x левого верхнего угла исходного прямоугольника. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ymask) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату y левого верхнего угла растрового изображения маски. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату y левого верхнего угла исходного прямоугольника. |

### Смотрите также

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
