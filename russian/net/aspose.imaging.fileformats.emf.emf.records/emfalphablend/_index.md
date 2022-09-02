---
title: EmfAlphaBlend
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_ALPHABLEND определяет блочную передачу пикселей из исходного растрового изображения в целевой прямоугольник  включая данные альфа-прозрачности в соответствии с указанной операцией смешивания.
type: docs
weight: 3200
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
## EmfAlphaBlend class

Запись EMR_ALPHABLEND определяет блочную передачу пикселей из исходного растрового изображения в целевой прямоугольник , включая данные альфа-прозрачности, в соответствии с указанной операцией смешивания.

```csharp
public sealed class EmfAlphaBlend : EmfBitmapRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfAlphaBlend](emfalphablend)(EmfRecord) | Инициализирует новый экземпляр[`EmfAlphaBlend`](../emfalphablend) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bksrcargb32color) { get; set; } | Получает или задает объект WMF ColorRef ([MS-WMF], раздел 2.2.2.8, который указывает цвет фона исходного растрового изображения. |
| [BlendFunction](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/blendfunction) { get; set; } | Получает или задает структуру, определяющую операции смешивания для исходных и растровых изображений назначения |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bounds) { get; set; } | Получает или задает объект WMF RectL ([MS-WMF], раздел 2.2.2.19), который определяет ограничивающий прямоугольник назначения в единицах измерения устройства. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxdest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую ширину целевого прямоугольника . Это значение ДОЛЖНО быть больше нуля. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую ширину исходного прямоугольника. Это значение ДОЛЖНО быть больше нуля. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cydest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую высоту целевого прямоугольника . Это значение ДОЛЖНО быть больше нуля. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую высоту исходного прямоугольника . Это значение ДОЛЖНО быть больше нуля. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или задает размер записи |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/sourcebitmap) { get; set; } | Получает или задает буфер, содержащий исходное растровое изображение, которое не обязательно должно быть непрерывным с фиксированной частью записи EMR_ALPHABLEND. Соответственно, поля в этом буфере , помеченные как «UndefinedSpace», являются необязательными и ДОЛЖНЫ игнорироваться. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/usagesrc) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее, как интерпретировать значения в таблице цветов в заголовке исходного растрового изображения. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xdest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату x левого верхнего угла целевого прямоугольника. |
| [XformSr](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xformsr) { get; set; } | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование мирового пространства в пространство страницы для применения к исходному растровому изображению. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xsrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату x левого верхнего угла исходного прямоугольника. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ydest) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату Y левого верхнего угла целевого прямоугольника. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ysrc) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее логическую координату y левого верхнего угла исходного прямоугольника. |

### Смотрите также

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
