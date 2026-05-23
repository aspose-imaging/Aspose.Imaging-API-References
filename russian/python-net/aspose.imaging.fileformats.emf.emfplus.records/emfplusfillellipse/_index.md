---
title: "Класс EmfPlusFillEllipse"
type: docs
weight: 240
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---

**Summary:** The EmfPlusFillEllipse record specifies filling the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillEllipse(source)](#EmfPlusFillEllipse_source_1) | Инициализирует новый экземпляр класса [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Получает или задает идентификатор кисти<br/>            32-битное беззнаковое целое, определяющее кисть, содержимое которой<br/>            определяется битом S в поле Flags. Это определение используется <br/>            для заполнения внутренней части эллипса. |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| is_color | bool | r/w | Получает или задает значение, указывающее, является ли данный экземпляр цветным.<br/>            Если установлено, BrushId задает цвет как объект EmfPlusARGB (раздел 2.2.2.1).<br/>            Если сброшено, BrushId содержит индекс объекта EmfPlusBrush <br/>            (раздел 2.2.1.1) в таблице объектов EMF+. |
| is_compressed | bool | r/w | Получает или задает значение, указывающее, сжата ли эта сущность.<br/>            Если установлено, RectData содержит объект EmfPlusRect (section 2.2.2.38). <br/>            Если сброшено, RectData содержит объект EmfPlusRectF (section 2.2.2.39). |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Получает или задает данные прямоугольника<br/>            Это объект EmfPlusRect или EmfPlusRectF, определяющий ограничивающий прямоугольник эллипса. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusFillEllipse(source) {#EmfPlusFillEllipse_source_1}


```
 EmfPlusFillEllipse(source) 
```

Инициализирует новый экземпляр класса [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

