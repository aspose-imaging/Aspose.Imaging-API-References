---
title: EmfPlusDrawClosedCurve
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusDrawClosedCurve определяет рисование замкнутого кардинального сплайна
type: docs
weight: 5920
url: /ru/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

Запись EmfPlusDrawClosedCurve определяет рисование замкнутого кардинального сплайна

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve)(EmfPlusRecord) | Инициализирует новый экземпляр[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve) class. RecordType — 16-битное целое число без знака, которое идентифицирует этот тип записи как EmfPlusDrawClosedCurve из перечисления RecordType (раздел 2.1.1.1). Значение ДОЛЖНО быть 0x4017. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed) { get; set; } | Получает или задает значение, указывающее, является ли это[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)сжато. Этот бит указывает, задает ли поле PointData сжатые данные. Если установлено, PointData указывает абсолютные местоположения в координатном пространстве с 16-битными целочисленными координатами. Если этот флажок не установлен, PointData указывает абсолютные местоположения в пространстве координат с 32-битными координатами с плавающей запятой. Примечание. Если установлен флаг Relative (ниже), этот флаг не определен и ДОЛЖЕН игнорироваться |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное количество байтов данных в следующем поле RecordData. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция, и о структуре записи. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid) { get; set; } | Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+ для построения замкнутой кривой. Значение ДОЛЖНО быть от нуля до 63 включительно. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata) { get; set; } | Получает или задает точку data Массив точек Count, указывающих конечные точки линий, определяющих сплайн. В замкнутом кардинальном сплайне кривая продолжается через последнюю точку массива PointData и соединяется с первой точкой массива. Тип данных в этом массиве определяется полем Flags следующим образом: объекта (раздел 2.2.2.37) Если в поле Flags установлен флаг P, точки указывают относительное расположение. Объект EmfPlusPointF (раздел 2.2.2.36) абсолютные местоположения. Объект EmfPlusPoint (раздел 2.2.2.35) Если бит P сброшен, а бит C установлен в поле Flags, точки указывают относительные местоположения. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative) { get; set; } | Получает или задает значение, указывающее, является ли это[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)является относительным. Этот бит указывает, указывает ли поле PointData относительные или абсолютные местоположения. Если установлено, каждый элемент в PointData указывает местоположение в координатном пространстве, относительное к местоположению, указанному предыдущим элементом в массиве. В случае первого элемента в PointData предполагается предыдущее местоположение с координатами (0,0). Если он не установлен, PointData указывает абсолютные местоположения в соответствии с флагом C. Примечание. Если этот флаг установлен, флаг Compressed (выше) не определен и ДОЛЖЕН игнорироваться |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее 32-разрядное выровненное количество байтов во всей записи, включая 12-разрядный заголовок записи и данные, относящиеся к записи. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension) { get; set; } | Получает или задает натяжение 32-разрядное число с плавающей запятой, указывающее, насколько сильно изгибается сплайн при прохождении через точки. Значение 0 указывает, что сплайн представляет собой последовательность прямых линий. По мере увеличения значения кривая становится более округлой. Для получения дополнительной информации см. [SPLINE77] и [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Смотрите также

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
