---
title: "EmfPlgBlt Класс"
type: docs
weight: 750
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

**Summary:** The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlgBlt(source)](#EmfPlgBlt_source_1) | Инициализирует новый экземпляр класса [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| aptl_dest | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает массив из трёх объектов WMF PointL ([MS-WMF] раздел 2.2.2.15), который<br/>определяет три угла области назначения параллелограмма для блочного переноса.<br/>Верхний‑левый угол исходного прямоугольника отображается на первую точку в этом массиве, <br/>верхний‑правый угол — на вторую точку, а нижний‑левый угол — на третью точку. Нижний‑правый угол исходного прямоугольника отображается на неявную четвёртую точку в <br/>параллелограмме, которая вычисляется из первых трёх точек (A, B и C), рассматривая их как <br/>векторы. <br/>D = B + C A |
| bk_src_argb_32_color | int | r/w | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет <br/>цвет фона исходного битмапа. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет <br/>ограничивающий прямоугольник в единицах устройства для вывода в назначение. |
| cx_src | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую ширину исходного прямоугольника. |
| cy_src | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую высоту исходного прямоугольника. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Получает или задает буфер, содержащий маску битмапа, который не <br/>            требуется быть непрерывным с фиксированной частью записи EMR_PLGBLT или друг с другом. <br/>            Соответственно, поля в этом буфере, помеченные "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. |
| size | int | r/w | Получает или задает размер записи |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Получает или задает буфер, содержащий исходный битмап, который не <br/>            требуется быть непрерывным с фиксированной частью записи EMR_PLGBLT или друг с другом. <br/>            Соответственно, поля в этом буфере, помеченные "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет, как интерпретировать значения в <br/>            таблице цветов заголовка маски битмапа. Это значение MUST be in the DIBColors enumeration. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет, как интерпретировать значения в <br/>            таблице цветов заголовка исходного битмапа. Это значение ДОЛЖНО быть в перечислении DIBColors. |
| x_form_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| x_mask | int | r/w | Получает или задает 32-битное знаковое целое число, которое указывает логическую x-координату верхнего левого угла битовой карты маски. |
| x_src | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату x верхнего левого <br/> угла исходного прямоугольника. |
| y_mask | int | r/w | Получает или задает 32-битное знаковое целое число, которое указывает логическую y-координату верхнего левого угла битовой карты маски. |
| y_src | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату y верхнего левого <br/> угла исходного прямоугольника. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPlgBlt(source) {#EmfPlgBlt_source_1}


```
 EmfPlgBlt(source) 
```

Инициализирует новый экземпляр класса [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Источник. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Источник. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Тип записи. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


