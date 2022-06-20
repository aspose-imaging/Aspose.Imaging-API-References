---
title: EmfPlusDrawCurve
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusDrawCurve определяет рисование кардинального сплайна ПРИМЕЧАНИЕObjectID 1 байтиндекс объекта EmfPlusPen раздел 2.2.1.7 в таблице объектов EMF чтобы нарисовать кривую. Значение ДОЛЖНО быть от нуля до 63 включительно.
type: docs
weight: 5930
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
## EmfPlusDrawCurve class

Запись EmfPlusDrawCurve определяет рисование кардинального сплайна ПРИМЕЧАНИЕ:ObjectID (1 байт):индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, чтобы нарисовать кривую. Значение ДОЛЖНО быть от нуля до 63 включительно.

```csharp
public sealed class EmfPlusDrawCurve : EmfPlusDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusDrawCurve](emfplusdrawcurve)(EmfPlusRecord) | Инициализирует новый экземпляр класса[`EmfPlusDrawCurve`](../emfplusdrawcurve). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/compressed) { get; set; } | Получает или задает значение, указывающее, сжат ли этот файл[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve). Этот бит указывает, указывает ли поле PointData сжатые данные. Если установлено, PointData указывает абсолютные местоположения в координатном пространстве с 16-битными целочисленными координатами. Если этот флажок не установлен, PointData указывает абсолютные местоположения в координатном пространстве с 32-битными координатами с плавающей запятой Примечание. Если установлен флаг Relative (ниже), этот флаг не определен и ДОЛЖЕН игнорировать |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное число байтов данных в поле RecordData, которое следует. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция , и о структуре запись. |
| [NumSegments](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/numsegments) { get; set; } | Получает или задает количество сегментов 32-разрядное целое число без знака, указывающее количество сегментов линии, составляющих сплайн. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/objectid) { get; set; } | Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+ для построения кривой. Значение ДОЛЖНО быть от нуля до 63 включительно. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/pointdata) { get; set; } | Получает или задает массив либо 32-разрядных целых чисел со знаком, либо 32-разрядных чисел с плавающей запятой Длина счетчика, определяющая значения координат конечные точки линий, которые необходимо обвести. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее число байтов, выровненных по 32-разрядному выравниванию во всей записи, включая 12 -байтовый заголовок записи и данные, относящиеся к записи. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/tension) { get; set; } | Получает или задает натяжение 32-разрядное число с плавающей запятой, указывающее, насколько сильно сплайн изгибается при изгибе проходит через точки. Значение 0 указывает, что сплайн представляет собой последовательность прямых линий. По мере увеличения значения кривая становится более округлой. Для получения дополнительной информации см. [SPLINE77] и [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Смотрите также

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->