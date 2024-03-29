---
title: EmfPolyBezier
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_POLYBEZIER указывает одну или несколько кривых Безье.
type: docs
weight: 3960
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
## EmfPolyBezier class

Запись EMR_POLYBEZIER указывает одну или несколько кривых Безье.

```csharp
public sealed class EmfPolyBezier : EmfDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPolyBezier](emfpolybezier#constructor)() | Инициализирует новый экземпляр[`EmfPolyBezier`](../emfpolybezier) класс. |
| [EmfPolyBezier](emfpolybezier#constructor_1)(EmfRecord) | Инициализирует новый экземпляр[`EmfPolyBezier`](../emfpolybezier) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezier/apoints) { get; set; } | Получает или задает массив длин объектов WMF PointL ([MS-WMF], раздел 2.2.2.15) , который определяет конечные точки и контрольные точки кривых Безье в логических единицах. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezier/bounds) { get; set; } | Получает или задает 128-битный объект RectL WMF ([MS-WMF], раздел 2.2.2.19), который указывает ограничивающий прямоугольник в единицах измерения устройства. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или задает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Примечания

Кубические кривые Безье определяются с использованием конечных и контрольных точек, указанных в поле aPoints . Первая кривая строится от первой точки до четвертой, используя вторую и третью точки в качестве контрольных точек. Каждой последующей кривой в последовательности требуется ровно три точки: конечная точка предыдущей кривой используется в качестве начальной точки, следующие две точки в последовательности являются контрольными точками, а третья является конечной точкой. Кубические кривые Безье ДОЛЖНЫ быть нарисованы с использованием текущего pen

### Смотрите также

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
