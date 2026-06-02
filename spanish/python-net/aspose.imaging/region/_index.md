---
title: "Clase Region"
type: docs
weight: 7170
url: /es/python-net/aspose.imaging/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Region

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Region()](#Region__1) | Inicializa una nueva [Region](/imaging/python-net/aspose.imaging/region/). |
| [Region(path)](#Region_path_2) | Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado. |
| [Region(rect)](#Region_rect_3) | Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) a partir de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [Region(rect)](#Region_rect_4) | Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) a partir de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [complement(path)](#complement_path_1) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_2) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_3) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(region)](#complement_region_4) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción del [Region](/imaging/python-net/aspose.imaging/region/) especificado que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_path(path)](#complement_path_path_5) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect(rect)](#complement_rect_rect_6) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect_f(rect)](#complement_rect_f_rect_7) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rgn(region)](#complement_rgn_region_8) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción del [Region](/imaging/python-net/aspose.imaging/region/) especificado que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/). |
| [create_with_path(path)](#create_with_path_path_9) | Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado. |
| [create_with_rect(rect)](#create_with_rect_rect_10) | Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) a partir de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [create_with_rect_f(rect)](#create_with_rect_f_rect_11) | Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) a partir de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [deep_clone()](#deep_clone__12) | Crea una copia profunda exacta de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [exclude(path)](#exclude_path_13) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado. |
| [exclude(rect)](#exclude_rect_14) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [exclude(rect)](#exclude_rect_15) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [exclude(region)](#exclude_region_16) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con el [Region](/imaging/python-net/aspose.imaging/region/) especificado. |
| [exclude_path(path)](#exclude_path_path_17) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado. |
| [exclude_rect(rect)](#exclude_rect_rect_18) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [exclude_rect_f(rect)](#exclude_rect_f_rect_19) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [exclude_rgn(region)](#exclude_rgn_region_20) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con el [Region](/imaging/python-net/aspose.imaging/region/) especificado. |
| [intersect(path)](#intersect_path_21) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado. |
| [intersect(rect)](#intersect_rect_22) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [intersect(rect)](#intersect_rect_23) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [intersect(region)](#intersect_region_24) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con el [Region](/imaging/python-net/aspose.imaging/region/) especificado. |
| [intersect_path(path)](#intersect_path_path_25) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado. |
| [intersect_rect(rect)](#intersect_rect_rect_26) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [intersect_rect_f(rect)](#intersect_rect_f_rect_27) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [intersect_rgn(region)](#intersect_rgn_region_28) | Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con el [Region](/imaging/python-net/aspose.imaging/region/) especificado. |
| [is_empty(g)](#is_empty_g_29) | Comprueba si este [Region](/imaging/python-net/aspose.imaging/region/) tiene un interior vacío en la superficie de dibujo especificada. |
| [is_infinite(g)](#is_infinite_g_30) | Comprueba si este [Region](/imaging/python-net/aspose.imaging/region/) tiene un interior infinito en la superficie de dibujo especificada. |
| [is_visible(point)](#is_visible_point_31) | Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point)](#is_visible_point_32) | Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point, g)](#is_visible_point_g_33) | Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible(point, g)](#is_visible_point_g_34) | Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible(rect)](#is_visible_rect_35) | Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect)](#is_visible_rect_36) | Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_37) | Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible(rect, g)](#is_visible_rect_g_38) | Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible(x, y)](#is_visible_x_y_39) | Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_40) | Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible(x, y, g)](#is_visible_x_y_g_41) | Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_42) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_43) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_44) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_45) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_f(x, y)](#is_visible_f_x_y_46) | Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point(point)](#is_visible_point_point_47) | Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_48) | Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f_with_graphics(point, g)](#is_visible_point_f_with_graphics_point_g_49) | Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_point_with_graphics(point, g)](#is_visible_point_with_graphics_point_g_50) | Comprueba si la estructura [Point](/imaging/python-net/aspose.imaging/point/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_rect(rect)](#is_visible_rect_rect_51) | Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f(rect)](#is_visible_rect_f_rect_52) | Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f_with_graphics(rect, g)](#is_visible_rect_f_with_graphics_rect_g_53) | Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_rect_with_graphics(rect, g)](#is_visible_rect_with_graphics_rect_g_54) | Comprueba si alguna porción de la estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_with_graphics(x, y, g)](#is_visible_with_graphics_x_y_g_55) | Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_with_graphics_f(x, y, g)](#is_visible_with_graphics_f_x_y_g_56) | Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_xywh(x, y, width, height)](#is_visible_xywh_x_y_width_height_57) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_xywh_graphics(x, y, width, height, g)](#is_visible_xywh_graphics_x_y_width_height_g_58) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_xywh_graphics_f(x, y, width, height, g)](#is_visible_xywh_graphics_f_x_y_width_height_g_59) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado. |
| [is_visible_xywhf(x, y, width, height)](#is_visible_xywhf_x_y_width_height_60) | Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/). |
| make_empty() | Inicializa este [Region](/imaging/python-net/aspose.imaging/region/) con un interior vacío. |
| make_infinite() | Inicializa este objeto [Region](/imaging/python-net/aspose.imaging/region/) con un interior infinito. |
| [transform(matrix)](#transform_matrix_61) | Transforma esta [Region](/imaging/python-net/aspose.imaging/region/) mediante la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada. |
| [translate(dx, dy)](#translate_dx_dy_62) | Desplaza las coordenadas de esta [Region](/imaging/python-net/aspose.imaging/region/) por la cantidad especificada. |
| [translate(dx, dy)](#translate_dx_dy_63) | Desplaza las coordenadas de esta [Region](/imaging/python-net/aspose.imaging/region/) por la cantidad especificada. |
| [translate_f(dx, dy)](#translate_f_dx_dy_64) | Desplaza las coordenadas de esta [Region](/imaging/python-net/aspose.imaging/region/) por la cantidad especificada. |
| [union(path)](#union_path_65) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado. |
| [union(rect)](#union_rect_66) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [union(rect)](#union_rect_67) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [union(region)](#union_region_68) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la [Region](/imaging/python-net/aspose.imaging/region/) especificada. |
| [union_path(path)](#union_path_path_69) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado. |
| [union_rect(rect)](#union_rect_rect_70) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [union_rect_f(rect)](#union_rect_f_rect_71) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [union_rgn(region)](#union_rgn_region_72) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la [Region](/imaging/python-net/aspose.imaging/region/) especificada. |
| [xor(path)](#xor_path_73) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado. |
| [xor(rect)](#xor_rect_74) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [xor(rect)](#xor_rect_75) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [xor(region)](#xor_region_76) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la [Region](/imaging/python-net/aspose.imaging/region/) especificada. |
| [xor_path(path)](#xor_path_path_77) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado. |
| [xor_rect(rect)](#xor_rect_rect_78) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [xor_rect_f(rect)](#xor_rect_f_rect_79) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada. |
| [xor_rgn(region)](#xor_rgn_region_80) | Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la [Region](/imaging/python-net/aspose.imaging/region/) especificada. |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Inicializa una nueva [Region](/imaging/python-net/aspose.imaging/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) que define la nueva [Region](/imaging/python-net/aspose.imaging/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) a partir de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que define el interior de la nueva [Region](/imaging/python-net/aspose.imaging/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) a partir de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que define el interior de la nueva [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para complementar esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para complementar esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para complementar esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción del [Region](/imaging/python-net/aspose.imaging/region/) especificado que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | El objeto [Region](/imaging/python-net/aspose.imaging/region/) para complementar este objeto [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_path(path) {#complement_path_path_5}


```
 complement_path(path) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para complementar esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rect(rect) {#complement_rect_rect_6}


```
 complement_rect(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para complementar esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rect_f(rect) {#complement_rect_f_rect_7}


```
 complement_rect_f(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para complementar esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rgn(region) {#complement_rgn_region_8}


```
 complement_rgn(region) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga la porción del [Region](/imaging/python-net/aspose.imaging/region/) especificado que no intersecta con este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | El objeto [Region](/imaging/python-net/aspose.imaging/region/) para complementar este objeto [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: create_with_path(path)  [static] {#create_with_path_path_9}


```
 create_with_path(path) 
```

Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) que define la nueva [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect(rect)  [static] {#create_with_rect_rect_10}


```
 create_with_rect(rect) 
```

Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) a partir de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que define el interior de la nueva [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect_f(rect)  [static] {#create_with_rect_f_rect_11}


```
 create_with_rect_f(rect) 
```

Inicializa un nuevo [Region](/imaging/python-net/aspose.imaging/region/) a partir de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) que define el interior de la nueva [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: deep_clone() {#deep_clone__12}


```
 deep_clone() 
```

Crea una copia profunda exacta de este [Region](/imaging/python-net/aspose.imaging/region/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) que crea este método. |


### Method: exclude(path) {#exclude_path_13}


```
 exclude(path) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para excluir de esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(rect) {#exclude_rect_14}


```
 exclude(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para excluir de esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(rect) {#exclude_rect_15}


```
 exclude(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para excluir de esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(region) {#exclude_region_16}


```
 exclude(region) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con el [Region](/imaging/python-net/aspose.imaging/region/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) para excluir de esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_path(path) {#exclude_path_path_17}


```
 exclude_path(path) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para excluir de esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rect(rect) {#exclude_rect_rect_18}


```
 exclude_rect(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para excluir de esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rect_f(rect) {#exclude_rect_f_rect_19}


```
 exclude_rect_f(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para excluir de esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rgn(region) {#exclude_rgn_region_20}


```
 exclude_rgn(region) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) para que contenga solo la porción de su interior que no intersecta con el [Region](/imaging/python-net/aspose.imaging/region/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) para excluir de esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(path) {#intersect_path_21}


```
 intersect(path) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para intersectar con esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(rect) {#intersect_rect_22}


```
 intersect(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para intersectar con esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(rect) {#intersect_rect_23}


```
 intersect(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para intersectar con esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(region) {#intersect_region_24}


```
 intersect(region) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con el [Region](/imaging/python-net/aspose.imaging/region/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) para intersectar con esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_path(path) {#intersect_path_path_25}


```
 intersect_path(path) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para intersectar con esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rect(rect) {#intersect_rect_rect_26}


```
 intersect_rect(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para intersectar con esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rect_f(rect) {#intersect_rect_f_rect_27}


```
 intersect_rect_f(rect) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para intersectar con esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rgn(region) {#intersect_rgn_region_28}


```
 intersect_rgn(region) 
```

Actualiza este [Region](/imaging/python-net/aspose.imaging/region/) a la intersección de sí mismo con el [Region](/imaging/python-net/aspose.imaging/region/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) para intersectar con esta [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: is_empty(g) {#is_empty_g_29}


```
 is_empty(g) 
```

Comprueba si este [Region](/imaging/python-net/aspose.imaging/region/) tiene un interior vacío en la superficie de dibujo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa una superficie de dibujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true si el interior de esta [Region](/imaging/python-net/aspose.imaging/region/) está vacío cuando se aplica la transformación asociada con _g_; de lo contrario, false. |


### Method: is_infinite(g) {#is_infinite_g_30}


```
 is_infinite(g) 
```

Comprueba si este [Region](/imaging/python-net/aspose.imaging/region/) tiene un interior infinito en la superficie de dibujo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa una superficie de dibujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true si el interior de esta [Region](/imaging/python-net/aspose.imaging/region/) es infinito cuando se aplica la transformación asociada con _g_; de lo contrario, false. |


### Method: is_visible(point) {#is_visible_point_31}


```
 is_visible(point) 
```

Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) para probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _point_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(point) {#is_visible_point_32}


```
 is_visible(point) 
```

Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) para probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _point_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(point, g) {#is_visible_point_g_33}


```
 is_visible(point, g) 
```

Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) para probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _point_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(point, g) {#is_visible_point_g_34}


```
 is_visible(point, g) 
```

Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) para probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _point_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(rect) {#is_visible_rect_35}


```
 is_visible(rect) 
```

Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte de _rect_ está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(rect) {#is_visible_rect_36}


```
 is_visible(rect) 
```

Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte de _rect_ está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(rect, g) {#is_visible_rect_g_37}


```
 is_visible(rect, g) 
```

Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _rect_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(rect, g) {#is_visible_rect_g_38}


```
 is_visible(rect, g) 
```

Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _rect_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(x, y) {#is_visible_x_y_39}


```
 is_visible(x, y) 
```

Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero cuando el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_40}


```
 is_visible(x, y, g) 
```

Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero cuando el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_41}


```
 is_visible(x, y, g) 
```

Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero cuando el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_42}


```
 is_visible(x, y, width, height) 
```

Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | float | El ancho del rectángulo a probar. |
| height | float | La altura del rectángulo a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este objeto [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_43}


```
 is_visible(x, y, width, height) 
```

Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | int | El ancho del rectángulo a probar. |
| height | int | La altura del rectángulo a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este objeto [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_44}


```
 is_visible(x, y, width, height, g) 
```

Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | float | El ancho del rectángulo a probar. |
| height | float | La altura del rectángulo a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_45}


```
 is_visible(x, y, width, height, g) 
```

Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | int | El ancho del rectángulo a probar. |
| height | int | La altura del rectángulo a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_f(x, y) {#is_visible_f_x_y_46}


```
 is_visible_f(x, y) 
```

Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero cuando el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_point(point) {#is_visible_point_point_47}


```
 is_visible_point(point) 
```

Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) para probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _point_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_48}


```
 is_visible_point_f(point) 
```

Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) para probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _point_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_point_f_with_graphics(point, g) {#is_visible_point_f_with_graphics_point_g_49}


```
 is_visible_point_f_with_graphics(point, g) 
```

Comprueba si la estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La estructura [PointF](/imaging/python-net/aspose.imaging/pointf/) para probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _point_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_point_with_graphics(point, g) {#is_visible_point_with_graphics_point_g_50}


```
 is_visible_point_with_graphics(point, g) 
```

Comprueba si la estructura [Point](/imaging/python-net/aspose.imaging/point/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La estructura [Point](/imaging/python-net/aspose.imaging/point/) a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _point_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_rect(rect) {#is_visible_rect_rect_51}


```
 is_visible_rect(rect) 
```

Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte de _rect_ está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_rect_f(rect) {#is_visible_rect_f_rect_52}


```
 is_visible_rect_f(rect) 
```

Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte de _rect_ está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_rect_f_with_graphics(rect, g) {#is_visible_rect_f_with_graphics_rect_g_53}


```
 is_visible_rect_f_with_graphics(rect, g) 
```

Comprueba si alguna porción de la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando _rect_ está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_rect_with_graphics(rect, g) {#is_visible_rect_with_graphics_rect_g_54}


```
 is_visible_rect_with_graphics(rect, g) 
```

Comprueba si alguna porción de la estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) especificada está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte de _rect_ está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_with_graphics(x, y, g) {#is_visible_with_graphics_x_y_g_55}


```
 is_visible_with_graphics(x, y, g) 
```

Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero cuando el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_with_graphics_f(x, y, g) {#is_visible_with_graphics_f_x_y_g_56}


```
 is_visible_with_graphics_f(x, y, g) 
```

Comprueba si el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero cuando el punto especificado está contenido dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_xywh(x, y, width, height) {#is_visible_xywh_x_y_width_height_57}


```
 is_visible_xywh(x, y, width, height) 
```

Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | int | El ancho del rectángulo a probar. |
| height | int | La altura del rectángulo a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este objeto [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_xywh_graphics(x, y, width, height, g) {#is_visible_xywh_graphics_x_y_width_height_g_58}


```
 is_visible_xywh_graphics(x, y, width, height, g) 
```

Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | int | El ancho del rectángulo a probar. |
| height | int | La altura del rectángulo a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_xywh_graphics_f(x, y, width, height, g) {#is_visible_xywh_graphics_f_x_y_width_height_g_59}


```
 is_visible_xywh_graphics_f(x, y, width, height, g) 
```

Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/) cuando se dibuja usando el [Graphics](/imaging/python-net/aspose.imaging/graphics/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | float | El ancho del rectángulo a probar. |
| height | float | La altura del rectángulo a probar. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) que representa un contexto gráfico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: is_visible_xywhf(x, y, width, height) {#is_visible_xywhf_x_y_width_height_60}


```
 is_visible_xywhf(x, y, width, height) 
```

Comprueba si alguna porción del rectángulo especificado está contenida dentro de este [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a probar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a probar. |
| width | float | El ancho del rectángulo a probar. |
| height | float | La altura del rectángulo a probar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | verdadero cuando cualquier parte del rectángulo especificado está contenida dentro de este objeto [Region](/imaging/python-net/aspose.imaging/region/); de lo contrario, falso. |


### Method: transform(matrix) {#transform_matrix_61}


```
 transform(matrix) 
```

Transforma esta [Region](/imaging/python-net/aspose.imaging/region/) mediante la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) mediante la cual transformar este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_62}


```
 translate(dx, dy) 
```

Desplaza las coordenadas de esta [Region](/imaging/python-net/aspose.imaging/region/) por la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | La cantidad para desplazar horizontalmente este [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | float | La cantidad para desplazar verticalmente este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_63}


```
 translate(dx, dy) 
```

Desplaza las coordenadas de esta [Region](/imaging/python-net/aspose.imaging/region/) por la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | int | La cantidad para desplazar horizontalmente este [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | int | La cantidad para desplazar verticalmente este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate_f(dx, dy) {#translate_f_dx_dy_64}


```
 translate_f(dx, dy) 
```

Desplaza las coordenadas de esta [Region](/imaging/python-net/aspose.imaging/region/) por la cantidad especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | La cantidad para desplazar horizontalmente este [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | float | La cantidad para desplazar verticalmente este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(path) {#union_path_65}


```
 union(path) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para unir con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(rect) {#union_rect_66}


```
 union(rect) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para unir con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(rect) {#union_rect_67}


```
 union(rect) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para unir con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(region) {#union_region_68}


```
 union(region) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la [Region](/imaging/python-net/aspose.imaging/region/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | El [Region](/imaging/python-net/aspose.imaging/region/) para unir con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_path(path) {#union_path_path_69}


```
 union_path(path) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para unir con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rect(rect) {#union_rect_rect_70}


```
 union_rect(rect) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para unir con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rect_f(rect) {#union_rect_f_rect_71}


```
 union_rect_f(rect) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para unir con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rgn(region) {#union_rgn_region_72}


```
 union_rgn(region) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión de ella misma y la [Region](/imaging/python-net/aspose.imaging/region/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | El [Region](/imaging/python-net/aspose.imaging/region/) para unir con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(path) {#xor_path_73}


```
 xor(path) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para xor con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(rect) {#xor_rect_74}


```
 xor(rect) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para xor con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(rect) {#xor_rect_75}


```
 xor(rect) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para xor con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(region) {#xor_region_76}


```
 xor(region) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la [Region](/imaging/python-net/aspose.imaging/region/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | El [Region](/imaging/python-net/aspose.imaging/region/) para xor con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_path(path) {#xor_path_path_77}


```
 xor_path(path) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con el [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | El [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) para xor con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rect(rect) {#xor_rect_rect_78}


```
 xor_rect(rect) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para xor con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rect_f(rect) {#xor_rect_f_rect_79}


```
 xor_rect_f(rect) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La estructura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) para xor con este [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rgn(region) {#xor_rgn_region_80}


```
 xor_rgn(region) 
```

Actualiza esta [Region](/imaging/python-net/aspose.imaging/region/) a la unión menos la intersección de ella misma con la [Region](/imaging/python-net/aspose.imaging/region/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | El [Region](/imaging/python-net/aspose.imaging/region/) para xor con este [Region](/imaging/python-net/aspose.imaging/region/). |

