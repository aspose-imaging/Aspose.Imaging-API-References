---
title: "Класс EmfPlusSetTsGraphics"
type: docs
weight: 580
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

**Summary:** The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetTsGraphics(source)](#EmfPlusSetTsGraphics_source_1) | Инициализирует новый экземпляр класса [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| anti_alias_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Возвращает или задает 8‑битное беззнаковое целое, которое определяет качество отрисовки линий,<br/>            включая тип сглаживания линий. Оно ДОЛЖНО быть определено в перечислении SmoothingMode<br/>            (раздел 2.1.1.28). |
| basic_vga_colors | bool | r | Возвращает значение, указывающее, включены ли [basic vga colors].<br/>            Если установлено, палитра содержит только базовые цвета VGA. |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | Возвращает или задает 8‑битное беззнаковое целое, которое определяет, как исходные цвета<br/>            комбинируются с цветами фона. Оно ДОЛЖНО быть значением из перечисления CompositingMode<br/>            (раздел 2.1.1.5). |
| compositing_quality | [EmfPlusCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/) | r/w | Возвращает или задает 8‑битное беззнаковое целое, которое определяет степень<br/>            сглаживания, применяемую к линиям, кривым и краям заполненных областей, чтобы они выглядели более<br/>            непрерывными или чётко определёнными. Оно ДОЛЖНО быть значением из перечисления CompositingQuality (раздел 2.1.1.6). |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| filter_type | [EmfPlusFilterType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/) | r/w | Возвращает или задает 8‑битное беззнаковое целое, которое определяет, как выполняется масштабирование, включая растяжение<br/>            и сжатие. Оно ДОЛЖНО быть значением из перечисления FilterType (раздел 2.1.1.11). |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| have_palette | bool | r | Возвращает значение, указывающее, присутствует ли [have palette].<br/>            Если установлено, эта запись содержит объект EmfPlusPalette (раздел 2.2.2.28) в поле<br/>            Palette после данных состояния графики. |
| palette | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Возвращает или задает необязательный объект EmfPlusPalette. |
| pixel_offset | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Возвращает или задает 8‑битное беззнаковое целое, которое определяет общее качество изображения<br/>            и процесса отрисовки текста. Оно ДОЛЖНО быть значением из перечисления PixelOffsetMode (раздел 2.1.1.26). |
| render_origin_x | int | r/w | Возвращает или задает 16‑битное знаковое целое, которое является горизонтальной координатой<br/>            начала для отрисовки полутонов и матриц дизеринга. |
| render_origin_y | int | r/w | Возвращает или задает 16‑битное знаковое целое, которое является вертикальной координатой начала<br/>            для отрисовки полутонов и матриц дизеринга. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| text_contrast | int | r/w | Возвращает или задает 16‑битное беззнаковое целое, которое определяет значение гамма‑коррекции<br/>            используемое при отрисовке сглаженного и ClearType текста. Это значение ДОЛЖНО находиться в диапазоне от 0 до 12 включительно. |
| text_render_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Возвращает или задает 8‑битное беззнаковое целое, которое определяет качество отрисовки текста<br/>            включая тип сглаживания текста. Оно ДОЛЖНО быть определено в перечислении TextRenderingHint<br/>            (раздел 2.1.1.32). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |
| world_to_device | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает 192-битный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который<br/>            определяет преобразования из мирового пространства в пространство устройства. |


### Constructor: EmfPlusSetTsGraphics(source) {#EmfPlusSetTsGraphics_source_1}


```
 EmfPlusSetTsGraphics(source) 
```

Инициализирует новый экземпляр класса [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

