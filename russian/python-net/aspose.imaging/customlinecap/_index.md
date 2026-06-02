---
title: "CustomLineCap Класс"
type: docs
weight: 1350
url: /ru/python-net/aspose.imaging/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CustomLineCap

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Инициализирует новый экземпляр класса [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) с указанным контуром и заливкой. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Инициализирует новый экземпляр класса [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) из указанного существующего перечисления [LineCap](/imaging/python-net/aspose.imaging/linecap/) с указанным контуром и заливкой. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Инициализирует новый экземпляр класса [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) из указанного существующего перечисления [LineCap](/imaging/python-net/aspose.imaging/linecap/) с указанным контуром, заливкой и отступом. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Получает или задает перечисление [LineCap](/imaging/python-net/aspose.imaging/linecap/), на котором основан этот [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/). |
| base_inset | float | r/w | Получает или задает расстояние между заглушкой и линией. |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Получает или задает объект, определяющий заливку для пользовательской заглушки. |
| stroke_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Получает или задает перечисление [LineJoin](/imaging/python-net/aspose.imaging/linejoin/), определяющее, как соединяются линии, составляющие объект [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/). |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Получает или задает объект, определяющий контур пользовательской заглушки. |
| width_scale | float | r/w | Получает или задает величину, на которую следует масштабировать объект класса [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) относительно ширины объекта. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Получает заглушки, используемые для начала и окончания линий, составляющих эту пользовательскую заглушку. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Задает заглушки, используемые для начала и окончания линий, составляющих эту пользовательскую заглушку. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Инициализирует новый экземпляр класса [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) с указанным контуром и заливкой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), определяющий заливку для пользовательской заглушки. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), определяющий контур пользовательской заглушки. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Инициализирует новый экземпляр класса [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) из указанного существующего перечисления [LineCap](/imaging/python-net/aspose.imaging/linecap/) с указанным контуром и заливкой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), определяющий заливку для пользовательской заглушки. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), определяющий контур пользовательской заглушки. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Заглушка линии, из которой создаётся пользовательская заглушка. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Инициализирует новый экземпляр класса [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) из указанного существующего перечисления [LineCap](/imaging/python-net/aspose.imaging/linecap/) с указанным контуром, заливкой и отступом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), определяющий заливку для пользовательской заглушки. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), определяющий контур пользовательской заглушки. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Заглушка линии, из которой создаётся пользовательская заглушка. |
| base_inset | float | Расстояние между заглушкой и линией. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Получает заглушки, используемые для начала и окончания линий, составляющих эту пользовательскую заглушку.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | Перечисление [LineCap](/imaging/python-net/aspose.imaging/linecap/), используемое в начале линии внутри этой заглушки. |
| end_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | Перечисление [LineCap](/imaging/python-net/aspose.imaging/linecap/), используемое в конце линии внутри этой заглушки. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Задает заглушки, используемые для начала и окончания линий, составляющих эту пользовательскую заглушку.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Перечисление [LineCap](/imaging/python-net/aspose.imaging/linecap/), используемое в начале линии внутри этой заглушки. |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Перечисление [LineCap](/imaging/python-net/aspose.imaging/linecap/), используемое в конце линии внутри этой заглушки. |

