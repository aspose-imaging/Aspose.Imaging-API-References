---
title: "EmfPlusDrawDriverString Класс"
type: docs
weight: 110
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

**Summary:** The EmfPlusDrawDriverString record specifies text output with character positions.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawDriverString(source)](#EmfPlusDrawDriverString_source_1) | Инициализирует новый экземпляр класса [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Получает или задает идентификатор кисти<br/>            32‑битное беззнаковое целое, определяющее либо цвет переднего плана текста, либо графическую кисть,<br/>            в зависимости от значения флага S в поле Flags. |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| driver_string_options_flags | [EmfPlusDriverStringOptionsFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/) | r/w | Получает или задает флаги параметров строкового драйвера<br/>            32‑битное беззнаковое целое, определяющее интервал, ориентацию и качество отрисовки строки. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| glyph_count | int | r/w | Получает или задает количество глифов<br/>            32‑битное беззнаковое целое, определяющее число глифов в строке. |
| glyph_pos | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает массив позиций глифов<br/>            Массив объектов EmfPlusPointF (раздел 2.2.2.36), определяющих выходную позицию каждого глифа символа.<br/>            ДОЛЖНО быть GlyphCount элементов, которые находятся в один‑к‑одному соответствие с элементами массива Glyphs.<br/>            Позиции глифов вычисляются из позиции первого глифа, если установлен флаг DriverStringOptionsRealizedAdvance<br/>            в флагах DriverStringOptions. В этом случае GlyphPos указывает только позицию первого глифа. |
| glyphs | int[] | r/w | Получает или задает массив глифов<br/>            Массив 16‑битных значений, определяющих текстовую строку для отрисовки.<br/>            Если установлен флаг DriverStringOptionsCmapLookup в поле DriverStringOptionsFlags, каждое значение в этом<br/>            массиве указывает Unicode‑символ. В противном случае каждое значение указывает индекс к<br/>            глифу символа в объекте EmfPlusFont, указанном значением ObjectId в поле Flags. |
| is_color | bool | r/w | Получает или задает значение, указывающее, является ли данный экземпляр цветом.<br/>            Этот бит указывает тип данных в поле BrushId.<br/>            Если установлен, BrushId задаёт значение цвета в объекте EmfPlusARGB<br/>            (раздел 2.2.2.1). Если сброшен, BrushId содержит индекс в таблице объектов EMF+ для объекта EmfPlusBrush (раздел 2.1.1). |
| matrix_present | int | r/w | Получает или задает флаг наличия матрицы<br/>            32‑битное беззнаковое целое, определяющее, присутствует ли матрица преобразования в поле TransformMatrix<br/>            0 — матрица отсутствует. 1 — матрица преобразования находится в поле TransformMatrix. |
| object_id | System.Byte | r/w | Получает или задает идентификатор объекта.<br/>            Индекс в таблице объектов EMF+ для объекта ***EmfPlusFont*** (раздел<br/>            2.2.1.3), используемого для отрисовки текста. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает матрицу преобразования<br/>            Необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), определяющий преобразование, применяемое к<br/>            каждому значению в массиве текста. Наличие этих данных определяется полем MatrixPresent. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusDrawDriverString(source) {#EmfPlusDrawDriverString_source_1}


```
 EmfPlusDrawDriverString(source) 
```

Инициализирует новый экземпляр класса [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

