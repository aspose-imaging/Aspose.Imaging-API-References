---
title: EmfPlusFillClosedCurve
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EmfPlusFillClosedCurve определяет заполнение внутренней части замкнутого кардинального сплайна
type: docs
weight: 6060
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

Запись EmfPlusFillClosedCurve определяет заполнение внутренней части замкнутого кардинального сплайна

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve)(EmfPlusRecord) | Инициализирует новый экземпляр[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid) { get; set; } | Получает или задает идентификатор кисти 32-разрядное целое число без знака, указывающее EmfPlusBrush, содержимое которого определяется битом S в поле Flags. Эта кисть используется для заполнения внутренней части замкнутого кардинального сплайна. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed) { get; set; } | Получает или задает значение, указывающее, является ли это[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)сжато. Этот бит указывает, задает ли поле PointData сжатые данные. Если установлено, PointData указывает абсолютные положения в координатном пространстве с 16-битными целочисленными координатами . Если флажок не установлен, PointData указывает абсолютные местоположения в координатном пространстве с 32-битными координатами с плавающей запятой. операция заполняет области в соответствии с правилом «четности четности». В соответствии с этим правилом можно определить, находится ли тестовая точка внутри или вне замкнутой кривой следующим образом: Проведите линию от контрольной точки до точки, удаленной на от кривой. Если эта линия пересекает кривую нечетное количество раз, тестовая точка находится внутри кривой; в противном случае контрольная точка находится за пределами кривой. --------------------- «Альтернативная» операция заливки заполняет области в соответствии с «ненулевым» правилом . В соответствии с этим правилом можно определить, находится ли тестовая точка внутри или снаружи замкнутой кривой следующим образом: Проведите линию от контрольной точки до точки, удаленной на от кривой. Подсчитайте, сколько раз кривая пересекает тестовую линию слева направо, и подсчитайте, сколько раз кривая пересекает тестовую линию справа налево. Если эти два числа совпадают, контрольная точка находится за пределами кривой; в противном случае контрольная точка находится внутри кривой. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО определять 32-разрядное выровненное количество байтов данных в следующем поле RecordData. Это число не включает 12-байтовый заголовок записи. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Получает или задает 16-разрядное целое число без знака, содержащее информацию для некоторых записей о том, как должна выполняться операция, и о структуре записи. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor) { get; set; } | Получает или задает значение, указывающее, является ли этот экземпляр цветом. Если установлено, BrushId указывает цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если этот параметр не установлен, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1). ) в таблице объектов EMF+. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata) { get; set; } | Получает или задает точку data Массив точек Count, указывающих конечные точки линий, определяющих сплайн. В замкнутом кардинальном сплайне кривая продолжается через последнюю точку массива PointData и соединяется с первой точкой массива |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative) { get; set; } | Получает или задает значение, указывающее, является ли это[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) является относительным. Этот бит указывает, указывает ли поле PointData относительное или абсолютное местоположение. В случае первого элемента в PointData предполагается предыдущее местоположение с координатами (0,0). Если не установлен, PointData указывает абсолютные местоположения в соответствии с флагом C. Примечание. Если этот флаг установлен, флаг C (выше) не определен и ДОЛЖЕН игнорироваться. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее 32-разрядное выровненное количество байтов во всей записи, включая 12-разрядный заголовок записи и данные, относящиеся к записи. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension) { get; set; } | Получает или задает натяжение 32-разрядное значение с плавающей запятой, указывающее, насколько сильно изгибается сплайн при прохождении через точки. Значение 0,0 указывает, что сплайн представляет собой последовательность прямых линий. По мере увеличения значения кривая становится более округлой. Для получения дополнительной информации см. [SPLINE77] и [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Получает 16-разрядное целое число без знака, определяющее тип записи. |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding) { get; set; } | Получает или задает значение, указывающее, является ли это[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)is winding. Этот бит указывает, как выполнять операцию заполнения. Если установлено, заполнение является "наматывающим" заполнением. Если флажок не установлен, заливка является "альтернативной". |

### Смотрите также

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
