---
title: "Класс EmfPlusDrawClosedCurve"
type: docs
weight: 90
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---

**Summary:** The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawClosedCurve(source)](#EmfPlusDrawClosedCurve_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType — 16‑битное беззнаковое целое, которое идентифицирует этот тип записи как EmfPlusDrawClosedCurve<br/>            из перечисления RecordType (раздел 2.1.1.1). Значение ДОЛЖНО быть 0x4017. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Получает или задает значение, указывающее, сжат ли этот [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            Этот бит указывает, задает ли поле PointData сжатые данные.<br/>            Если установлен, PointData задает абсолютные положения в координатном пространстве с 16‑битными целочисленными координатами. <br/>            Если сброшен, PointData задает абсолютные положения в координатном пространстве с 32‑битными координатами с плавающей запятой.<br/>            Примечание: если установлен флаг Relative (ниже), этот флаг не определён и ДОЛЖЕН игнорироваться |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+<br/>            для рисования закрытой кривой. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает данные точек<br/>            Массив из Count точек, определяющих конечные точки линий, образующих сплайн. В закрытом кардинальном сплайне <br/>            кривая продолжается через последнюю точку массива PointData и соединяется с первой точкой массива.<br/>            Тип данных в этом массиве задаётся полем Flags следующим образом: Тип данных Значение<br/>            объект EmfPlusPointR (раздел 2.2.2.37)<br/>            Если флаг P установлен в Flags, точки задают относительные положения.<br/>            объект EmfPlusPointF (раздел 2.2.2.36)<br/>            Если биты P и C установлены в поле Flags, точки задают абсолютные положения.<br/>            объект EmfPlusPoint (раздел 2.2.2.35)<br/>            Если бит P сброшен, а бит C установлен в поле Flags, точки задают относительные положения. |
| relative | bool | r/w | Получает или задает значение, указывающее, является ли этот [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) относительным.<br/>            Этот бит указывает, задает ли поле PointData относительные или абсолютные положения.<br/>            Если установлен, каждый элемент в PointData задает положение в координатном пространстве, которое является относительным <br/>            к положению, указанному предыдущим элементом в массиве. В случае первого <br/>            элемента в PointData предполагается предыдущее положение с координатами (0,0). Если сброшен, <br/>            PointData задает абсолютные положения согласно флагу C.<br/>            Примечание: если этот флаг установлен, флаг Compressed (выше) не определён и ДОЛЖЕН игнорироваться |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| натяжение | float | r/w | Получает или задает натяжение<br/>            32‑разрядное число с плавающей точкой, определяющее, насколько сильно сплайн <br/>            изгибается при прохождении через точки. Значение 0 указывает, что <br/>            сплайн представляет собой последовательность прямых линий. По мере увеличения значения <br/>            кривая становится более округлой. Для получения дополнительной информации см. [SPLINE77] и [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawClosedCurve(source) {#EmfPlusDrawClosedCurve_source_1}


```
 EmfPlusDrawClosedCurve(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType — 16‑битное беззнаковое целое, которое идентифицирует этот тип записи как EmfPlusDrawClosedCurve<br/>            из перечисления RecordType (раздел 2.1.1.1). Значение ДОЛЖНО быть 0x4017.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

