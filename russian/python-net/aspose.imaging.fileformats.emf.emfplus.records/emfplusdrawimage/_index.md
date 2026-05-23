---
title: "Класс EmfPlusDrawImage"
type: docs
weight: 130
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

**Summary:** The EmfPlusDrawImage record specifies drawing a scaled image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawImage(source)](#EmfPlusDrawImage_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| сжатый | bool | r/w | Получает или задает значение, указывающее, сжаты ли данные PointData.<br/>            Если установлено, RectData содержит объект EmfPlusRect (раздел 2.2.2.38).<br/>            Если сброшено, RectData содержит объект EmfPlusRectF (раздел 2.2.2.39). |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| image_attributes_id | int | r/w | Получает или задает идентификатор атрибутов изображения<br/> 32‑битное беззнаковое целое, которое указывает индекс необязательного объекта EmfPlusImageAttributes (раздел 2.2.1.5) в таблице объектов EMF+. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс объекта EmfPlusImage (section 2.2.1.4) в таблице объектов EMF+<br/>            , который определяет изображение для отрисовки. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Получает или задает данные прямоугольника<br/> Либо объект EmfPlusRect, либо EmfPlusRectF, определяющий ограничивающий прямоугольник изображения.<br/> Часть изображения, указанная в поле SrcRect, масштабируется, чтобы вписаться в этот прямоугольник. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Получает или задает исходный прямоугольник<br/> Объект EmfPlusRectF, который указывает часть изображения для отрисовки.<br/> Часть изображения, указанная этим прямоугольником, масштабируется, чтобы вписаться в целевой<br/> прямоугольник, указанный в поле RectData. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Получает или задает единицу исходного измерения<br/> 32‑битное знаковое целое, которое указывает единицы поля SrcRect.<br/> Оно ДОЛЖНО быть членом UnitTypePixel перечисления UnitType (раздел 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawImage(source) {#EmfPlusDrawImage_source_1}


```
 EmfPlusDrawImage(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

