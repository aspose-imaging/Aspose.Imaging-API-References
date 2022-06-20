---
title: EmfPlusFillPolygon
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusFillPolygon определяет заполнение внутренней части полигона.
type: docs
weight: 6100
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
## EmfPlusFillPolygon class

Запись EmfPlusFillPolygon определяет заполнение внутренней части полигона.

```csharp
public sealed class EmfPlusFillPolygon : EmfPlusDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusFillPolygon](emfplusfillpolygon)(EmfPlusRecord) | Инициализирует новый экземпляр класса[`EmfPlusFillPolygon`](../emfplusfillpolygon). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/brushid) { get; set; } | Получает или задает идентификатор кисти 32-битное целое число без знака, определяющее кисть, содержимое которой определяется битом S в поле Flags. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное число байтов данных в поле RecordData, которое следует. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция , и о структуре запись. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscolor) { get; set; } | Получает или задает значение, указывающее, является ли данный экземпляр цветным. Если установлено, BrushId определяет цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если флажок не установлен, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+. |
| [IsCompressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscompressed) { get; set; } | Получает или задает значение, указывающее, сжат ли этот экземпляр. Если установлено, PointData указывает абсолютные местоположения в координатном пространстве с 16-битными целочисленными координатами. Если этот флажок установлен, PointData указывает абсолютные местоположения в координатах пробел с 32-битными координатами с плавающей запятой |
| [IsRelative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/isrelative) { get; set; } | Получает или задает значение, указывающее, является ли данный экземпляр относительным. Если установлено, каждый элемент в PointData указывает положение в координатах пространстве, которое относится к местоположению, указанному предыдущим элементом в массиве. В случае первого элемента в PointData предполагается предыдущее местоположение с координатами (0,0). Если флажок не установлен, PointData указывает абсолютные местоположения в соответствии с флагом C |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/pointdata) { get; set; } | Получает или задает данные точек Массив точек Count, определяющих вершины многоугольника. Первые две точки в массиве определяют первую сторону многоугольника. Каждая дополнительная точка задает новую сторону, вершины которой включают точку и предыдущую точку. Если последняя точка и первая точка не совпадают, они определяют последнюю сторону многоугольника. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее число байтов, выровненных по 32-разрядному выравниванию во всей записи, включая 12 -байтовый заголовок записи и данные, относящиеся к записи. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |

### Смотрите также

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->