---
title: "CustomLineCap Clase"
type: docs
weight: 1350
url: /es/python-net/aspose.imaging/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.CustomLineCap

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Inicializa una nueva instancia de la clase [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) con el contorno y el relleno especificados. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Inicializa una nueva instancia de la clase [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) a partir de la enumeración [LineCap](/imaging/python-net/aspose.imaging/linecap/) existente especificada, con el contorno y el relleno especificados. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Inicializa una nueva instancia de la clase [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) a partir de la enumeración [LineCap](/imaging/python-net/aspose.imaging/linecap/) existente especificada, con el contorno, el relleno y la inserción especificados. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Obtiene o establece la enumeración [LineCap](/imaging/python-net/aspose.imaging/linecap/) en la que se basa este [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/). |
| base_inset | float | r/w | Obtiene o establece la distancia entre la tapa y la línea. |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Obtiene o establece el objeto que define el relleno para la tapa personalizada. |
| stroke_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Obtiene o establece la enumeración [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) que determina cómo se unen las líneas que componen este objeto [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/). |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r/w | Obtiene o establece el objeto que define el contorno de la tapa personalizada. |
| width_scale | float | r/w | Obtiene o establece la cantidad por la que escalar este objeto de clase [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) con respecto al ancho del objeto. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Obtiene las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Establece las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Inicializa una nueva instancia de la clase [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) con el contorno y el relleno especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objeto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) que define el relleno para la tapa personalizada. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objeto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) que define el contorno de la tapa personalizada. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Inicializa una nueva instancia de la clase [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) a partir de la enumeración [LineCap](/imaging/python-net/aspose.imaging/linecap/) existente especificada, con el contorno y el relleno especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objeto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) que define el relleno para la tapa personalizada. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objeto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) que define el contorno de la tapa personalizada. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | La tapa de línea a partir de la cual crear la tapa personalizada. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Inicializa una nueva instancia de la clase [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) a partir de la enumeración [LineCap](/imaging/python-net/aspose.imaging/linecap/) existente especificada, con el contorno, el relleno y la inserción especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fill_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objeto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) que define el relleno para la tapa personalizada. |
| stroke_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un objeto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) que define el contorno de la tapa personalizada. |
| base_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | La tapa de línea a partir de la cual crear la tapa personalizada. |
| base_inset | float | La distancia entre la tapa y la línea. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Obtiene las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | La enumeración [LineCap](/imaging/python-net/aspose.imaging/linecap/) usada al inicio de una línea dentro de esta tapa. |
| end_cap | [LineCap[]](/imaging/python-net/aspose.imaging/linecap/) | La enumeración [LineCap](/imaging/python-net/aspose.imaging/linecap/) usada al final de una línea dentro de esta tapa. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Establece las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | La enumeración [LineCap](/imaging/python-net/aspose.imaging/linecap/) usada al inicio de una línea dentro de esta tapa. |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | La enumeración [LineCap](/imaging/python-net/aspose.imaging/linecap/) usada al final de una línea dentro de esta tapa. |

