---
title: "Класс EmfPlusDrawString"
type: docs
weight: 190
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

**Summary:** The EmfPlusDrawString record specifies text output with string formatting

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawString(source)](#EmfPlusDrawString_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Получает или задает идентификатор кисти<br/>            32‑битное беззнаковое целое, которое указывает кисть, содержимое которой <br/>            определяется битом S в поле Flags. Это определение используется <br/>            для рисования цвета текста переднего плана; то есть только самих глифов. |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| format_id | int | r/w | Получает или задает идентификатор формата<br/>            32‑битное беззнаковое целое, которое указывает индекс необязательного <br/>            объекта EmfPlusStringFormat (раздел 2.2.1.9) в таблице объектов EMF+. <br/>            Этот объект определяет информацию о расположении текста и манипуляции отображения, <br/>            которые применяются к строке. |
| is_color | bool | r/w | Получает или задает значение, указывающее, является ли данный экземпляр цветным.<br/>            Если установлено, BrushId задает цвет как объект EmfPlusARGB (раздел 2.2.2.1).<br/>            Если сброшено, BrushId содержит индекс объекта EmfPlusBrush <br/>            (раздел 2.2.1.1) в таблице объектов EMF+. |
| layout_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Получает или задает прямоугольник размещения<br/>            Объект EmfPlusRectF (раздел 2.2.2.39), определяющий ограничивающую область <br/>            назначения, которое получит строку. |
| length | int | r/w | Получает или задает длину<br/>            32‑битное беззнаковое целое, которое указывает количество символов в строке. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс объекта EmfPlusFont (раздел 2.2.1.3) в таблице объектов EMF+<br/>            для отображения текста. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| string_data | string | r/w | Получает или задает данные строки<br/>            Массив 16‑битных Unicode‑символов, определяющий строку для отрисовки. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawString(source) {#EmfPlusDrawString_source_1}


```
 EmfPlusDrawString(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

