---
title: "Classe Region"
type: docs
weight: 7170
url: /it/python-net/aspose.imaging/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Region

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Region()](#Region__1) | Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/). |
| [Region(path)](#Region_path_2) | Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato. |
| [Region(rect)](#Region_rect_3) | Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) dalla struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [Region(rect)](#Region_rect_4) | Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) dalla struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [complement(path)](#complement_path_1) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_2) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_3) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(region)](#complement_region_4) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione del [Region](/imaging/python-net/aspose.imaging/region/) specificato che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_path(path)](#complement_path_path_5) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect(rect)](#complement_rect_rect_6) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect_f(rect)](#complement_rect_f_rect_7) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rgn(region)](#complement_rgn_region_8) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione del [Region](/imaging/python-net/aspose.imaging/region/) specificato che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [create_with_path(path)](#create_with_path_path_9) | Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato. |
| [create_with_rect(rect)](#create_with_rect_rect_10) | Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) dalla struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [create_with_rect_f(rect)](#create_with_rect_f_rect_11) | Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) dalla struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [deep_clone()](#deep_clone__12) | Crea una copia profonda esatta di questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [exclude(path)](#exclude_path_13) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato. |
| [exclude(rect)](#exclude_rect_14) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [exclude(rect)](#exclude_rect_15) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [exclude(region)](#exclude_region_16) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca il [Region](/imaging/python-net/aspose.imaging/region/) specificato. |
| [exclude_path(path)](#exclude_path_path_17) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato. |
| [exclude_rect(rect)](#exclude_rect_rect_18) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [exclude_rect_f(rect)](#exclude_rect_f_rect_19) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [exclude_rgn(region)](#exclude_rgn_region_20) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca il [Region](/imaging/python-net/aspose.imaging/region/) specificato. |
| [intersect(path)](#intersect_path_21) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato. |
| [intersect(rect)](#intersect_rect_22) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [intersect(rect)](#intersect_rect_23) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [intersect(region)](#intersect_region_24) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con il [Region](/imaging/python-net/aspose.imaging/region/) specificato. |
| [intersect_path(path)](#intersect_path_path_25) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato. |
| [intersect_rect(rect)](#intersect_rect_rect_26) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [intersect_rect_f(rect)](#intersect_rect_f_rect_27) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [intersect_rgn(region)](#intersect_rgn_region_28) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con il [Region](/imaging/python-net/aspose.imaging/region/) specificato. |
| [is_empty(g)](#is_empty_g_29) | Verifica se questo [Region](/imaging/python-net/aspose.imaging/region/) ha un interno vuoto sulla superficie di disegno specificata. |
| [is_infinite(g)](#is_infinite_g_30) | Verifica se questo [Region](/imaging/python-net/aspose.imaging/region/) ha un interno infinito sulla superficie di disegno specificata. |
| [is_visible(point)](#is_visible_point_31) | Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point)](#is_visible_point_32) | Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point, g)](#is_visible_point_g_33) | Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible(point, g)](#is_visible_point_g_34) | Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible(rect)](#is_visible_rect_35) | Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect)](#is_visible_rect_36) | Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_37) | Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible(rect, g)](#is_visible_rect_g_38) | Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible(x, y)](#is_visible_x_y_39) | Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_40) | Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnato usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible(x, y, g)](#is_visible_x_y_g_41) | Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnato usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_42) | Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_43) | Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_44) | Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_45) | Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible_f(x, y)](#is_visible_f_x_y_46) | Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point(point)](#is_visible_point_point_47) | Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_48) | Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f_with_graphics(point, g)](#is_visible_point_f_with_graphics_point_g_49) | Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible_point_with_graphics(point, g)](#is_visible_point_with_graphics_point_g_50) | Verifica se la struttura [Point](/imaging/python-net/aspose.imaging/point/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible_rect(rect)](#is_visible_rect_rect_51) | Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f(rect)](#is_visible_rect_f_rect_52) | Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f_with_graphics(rect, g)](#is_visible_rect_f_with_graphics_rect_g_53) | Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible_rect_with_graphics(rect, g)](#is_visible_rect_with_graphics_rect_g_54) | Verifica se qualche porzione della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible_with_graphics(x, y, g)](#is_visible_with_graphics_x_y_g_55) | Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnato usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible_with_graphics_f(x, y, g)](#is_visible_with_graphics_f_x_y_g_56) | Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnato usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible_xywh(x, y, width, height)](#is_visible_xywh_x_y_width_height_57) | Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_xywh_graphics(x, y, width, height, g)](#is_visible_xywh_graphics_x_y_width_height_g_58) | Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible_xywh_graphics_f(x, y, width, height, g)](#is_visible_xywh_graphics_f_x_y_width_height_g_59) | Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato. |
| [is_visible_xywhf(x, y, width, height)](#is_visible_xywhf_x_y_width_height_60) | Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/). |
| make_empty() | Inizializza questo [Region](/imaging/python-net/aspose.imaging/region/) con un interno vuoto. |
| make_infinite() | Inizializza questo oggetto [Region](/imaging/python-net/aspose.imaging/region/) con un interno infinito. |
| [transform(matrix)](#transform_matrix_61) | Trasforma questo [Region](/imaging/python-net/aspose.imaging/region/) mediante la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata. |
| [translate(dx, dy)](#translate_dx_dy_62) | Sposta le coordinate di questo [Region](/imaging/python-net/aspose.imaging/region/) dell'importo specificato. |
| [translate(dx, dy)](#translate_dx_dy_63) | Sposta le coordinate di questo [Region](/imaging/python-net/aspose.imaging/region/) dell'importo specificato. |
| [translate_f(dx, dy)](#translate_f_dx_dy_64) | Sposta le coordinate di questo [Region](/imaging/python-net/aspose.imaging/region/) dell'importo specificato. |
| [union(path)](#union_path_65) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato. |
| [union(rect)](#union_rect_66) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [union(rect)](#union_rect_67) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [union(region)](#union_region_68) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e del [Region](/imaging/python-net/aspose.imaging/region/) specificato. |
| [union_path(path)](#union_path_path_69) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato. |
| [union_rect(rect)](#union_rect_rect_70) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [union_rect_f(rect)](#union_rect_f_rect_71) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [union_rgn(region)](#union_rgn_region_72) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e del [Region](/imaging/python-net/aspose.imaging/region/) specificato. |
| [xor(path)](#xor_path_73) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato. |
| [xor(rect)](#xor_rect_74) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [xor(rect)](#xor_rect_75) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [xor(region)](#xor_region_76) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con il [Region](/imaging/python-net/aspose.imaging/region/) specificato. |
| [xor_path(path)](#xor_path_path_77) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato. |
| [xor_rect(rect)](#xor_rect_rect_78) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [xor_rect_f(rect)](#xor_rect_f_rect_79) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata. |
| [xor_rgn(region)](#xor_rgn_region_80) | Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con il [Region](/imaging/python-net/aspose.imaging/region/) specificato. |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) che definisce il nuovo [Region](/imaging/python-net/aspose.imaging/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) dalla struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che definisce l'interno del nuovo [Region](/imaging/python-net/aspose.imaging/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) dalla struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che definisce l'interno del nuovo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) per completare questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) per completare questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) per completare questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione del [Region](/imaging/python-net/aspose.imaging/region/) specificato che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | L'oggetto [Region](/imaging/python-net/aspose.imaging/region/) per completare questo oggetto [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_path(path) {#complement_path_path_5}


```
 complement_path(path) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) per completare questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rect(rect) {#complement_rect_rect_6}


```
 complement_rect(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) per completare questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rect_f(rect) {#complement_rect_f_rect_7}


```
 complement_rect_f(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) per completare questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rgn(region) {#complement_rgn_region_8}


```
 complement_rgn(region) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere la porzione del [Region](/imaging/python-net/aspose.imaging/region/) specificato che non interseca questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | L'oggetto [Region](/imaging/python-net/aspose.imaging/region/) per completare questo oggetto [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: create_with_path(path)  [static] {#create_with_path_path_9}


```
 create_with_path(path) 
```

Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) che definisce il nuovo [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect(rect)  [static] {#create_with_rect_rect_10}


```
 create_with_rect(rect) 
```

Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) dalla struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che definisce l'interno del nuovo [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect_f(rect)  [static] {#create_with_rect_f_rect_11}


```
 create_with_rect_f(rect) 
```

Inizializza un nuovo [Region](/imaging/python-net/aspose.imaging/region/) dalla struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Una struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) che definisce l'interno del nuovo [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: deep_clone() {#deep_clone__12}


```
 deep_clone() 
```

Crea una copia profonda esatta di questo [Region](/imaging/python-net/aspose.imaging/region/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) | Il [Region](/imaging/python-net/aspose.imaging/region/) che questo metodo crea. |


### Method: exclude(path) {#exclude_path_13}


```
 exclude(path) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da escludere da questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(rect) {#exclude_rect_14}


```
 exclude(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da escludere da questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(rect) {#exclude_rect_15}


```
 exclude(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da escludere da questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(region) {#exclude_region_16}


```
 exclude(region) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca il [Region](/imaging/python-net/aspose.imaging/region/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Il [Region](/imaging/python-net/aspose.imaging/region/) da escludere da questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_path(path) {#exclude_path_path_17}


```
 exclude_path(path) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da escludere da questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rect(rect) {#exclude_rect_rect_18}


```
 exclude_rect(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da escludere da questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rect_f(rect) {#exclude_rect_f_rect_19}


```
 exclude_rect_f(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da escludere da questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rgn(region) {#exclude_rgn_region_20}


```
 exclude_rgn(region) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) per contenere solo la porzione del suo interno che non interseca il [Region](/imaging/python-net/aspose.imaging/region/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Il [Region](/imaging/python-net/aspose.imaging/region/) da escludere da questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(path) {#intersect_path_21}


```
 intersect(path) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da intersecare con questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(rect) {#intersect_rect_22}


```
 intersect(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da intersecare con questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(rect) {#intersect_rect_23}


```
 intersect(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da intersecare con questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(region) {#intersect_region_24}


```
 intersect(region) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con il [Region](/imaging/python-net/aspose.imaging/region/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Il [Region](/imaging/python-net/aspose.imaging/region/) da intersecare con questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_path(path) {#intersect_path_path_25}


```
 intersect_path(path) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da intersecare con questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rect(rect) {#intersect_rect_rect_26}


```
 intersect_rect(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da intersecare con questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rect_f(rect) {#intersect_rect_f_rect_27}


```
 intersect_rect_f(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da intersecare con questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rgn(region) {#intersect_rgn_region_28}


```
 intersect_rgn(region) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'intersezione di sé con il [Region](/imaging/python-net/aspose.imaging/region/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Il [Region](/imaging/python-net/aspose.imaging/region/) da intersecare con questo [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: is_empty(g) {#is_empty_g_29}


```
 is_empty(g) 
```

Verifica se questo [Region](/imaging/python-net/aspose.imaging/region/) ha un interno vuoto sulla superficie di disegno specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta una superficie di disegno. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | true se l'interno di questo [Region](/imaging/python-net/aspose.imaging/region/) è vuoto quando viene applicata la trasformazione associata a _g_; altrimenti, false. |


### Method: is_infinite(g) {#is_infinite_g_30}


```
 is_infinite(g) 
```

Verifica se questo [Region](/imaging/python-net/aspose.imaging/region/) ha un interno infinito sulla superficie di disegno specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta una superficie di disegno. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | true se l'interno di questo [Region](/imaging/python-net/aspose.imaging/region/) è infinito quando viene applicata la trasformazione associata a _g_; altrimenti, false. |


### Method: is_visible(point) {#is_visible_point_31}


```
 is_visible(point) 
```

Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _point_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(point) {#is_visible_point_32}


```
 is_visible(point) 
```

Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _point_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(point, g) {#is_visible_point_g_33}


```
 is_visible(point, g) 
```

Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _point_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(point, g) {#is_visible_point_g_34}


```
 is_visible(point, g) 
```

Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _point_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(rect) {#is_visible_rect_35}


```
 is_visible(rect) 
```

Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte di _rect_ è contenuta in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(rect) {#is_visible_rect_36}


```
 is_visible(rect) 
```

Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte di _rect_ è contenuta in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(rect, g) {#is_visible_rect_g_37}


```
 is_visible(rect, g) 
```

Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _rect_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(rect, g) {#is_visible_rect_g_38}


```
 is_visible(rect, g) 
```

Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _rect_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(x, y) {#is_visible_x_y_39}


```
 is_visible(x, y) 
```

Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero quando il punto specificato è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_40}


```
 is_visible(x, y, g) 
```

Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnato usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero quando il punto specificato è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_41}


```
 is_visible(x, y, g) 
```

Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnato usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero quando il punto specificato è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_42}


```
 is_visible(x, y, width, height) 
```

Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | float | La larghezza del rettangolo da testare. |
| height | float | L'altezza del rettangolo da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta in questo oggetto [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_43}


```
 is_visible(x, y, width, height) 
```

Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | int | La larghezza del rettangolo da testare. |
| height | int | L'altezza del rettangolo da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta in questo oggetto [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_44}


```
 is_visible(x, y, width, height, g) 
```

Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | float | La larghezza del rettangolo da testare. |
| height | float | L'altezza del rettangolo da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_45}


```
 is_visible(x, y, width, height, g) 
```

Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | int | La larghezza del rettangolo da testare. |
| height | int | L'altezza del rettangolo da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_f(x, y) {#is_visible_f_x_y_46}


```
 is_visible_f(x, y) 
```

Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero quando il punto specificato è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_point(point) {#is_visible_point_point_47}


```
 is_visible_point(point) 
```

Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _point_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_48}


```
 is_visible_point_f(point) 
```

Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _point_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_point_f_with_graphics(point, g) {#is_visible_point_f_with_graphics_point_g_49}


```
 is_visible_point_f_with_graphics(point, g) 
```

Verifica se la struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La struttura [PointF](/imaging/python-net/aspose.imaging/pointf/) da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _point_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_point_with_graphics(point, g) {#is_visible_point_with_graphics_point_g_50}


```
 is_visible_point_with_graphics(point, g) 
```

Verifica se la struttura [Point](/imaging/python-net/aspose.imaging/point/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La struttura [Point](/imaging/python-net/aspose.imaging/point/) da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _point_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_rect(rect) {#is_visible_rect_rect_51}


```
 is_visible_rect(rect) 
```

Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte di _rect_ è contenuta in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_rect_f(rect) {#is_visible_rect_f_rect_52}


```
 is_visible_rect_f(rect) 
```

Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte di _rect_ è contenuta in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_rect_f_with_graphics(rect, g) {#is_visible_rect_f_with_graphics_rect_g_53}


```
 is_visible_rect_f_with_graphics(rect, g) 
```

Verifica se qualche porzione della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando _rect_ è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_rect_with_graphics(rect, g) {#is_visible_rect_with_graphics_rect_g_54}


```
 is_visible_rect_with_graphics(rect, g) 
```

Verifica se qualche porzione della struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) specificata è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte di _rect_ è contenuta in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_with_graphics(x, y, g) {#is_visible_with_graphics_x_y_g_55}


```
 is_visible_with_graphics(x, y, g) 
```

Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnato usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero quando il punto specificato è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_with_graphics_f(x, y, g) {#is_visible_with_graphics_f_x_y_g_56}


```
 is_visible_with_graphics_f(x, y, g) 
```

Verifica se il punto specificato è contenuto in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnato usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero quando il punto specificato è contenuto in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_xywh(x, y, width, height) {#is_visible_xywh_x_y_width_height_57}


```
 is_visible_xywh(x, y, width, height) 
```

Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | int | La larghezza del rettangolo da testare. |
| height | int | L'altezza del rettangolo da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta in questo oggetto [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_xywh_graphics(x, y, width, height, g) {#is_visible_xywh_graphics_x_y_width_height_g_58}


```
 is_visible_xywh_graphics(x, y, width, height, g) 
```

Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | int | La larghezza del rettangolo da testare. |
| height | int | L'altezza del rettangolo da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_xywh_graphics_f(x, y, width, height, g) {#is_visible_xywh_graphics_f_x_y_width_height_g_59}


```
 is_visible_xywh_graphics_f(x, y, width, height, g) 
```

Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/) quando viene disegnata usando il [Graphics](/imaging/python-net/aspose.imaging/graphics/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | float | La larghezza del rettangolo da testare. |
| height | float | L'altezza del rettangolo da testare. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) che rappresenta un contesto grafico. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta in questa [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: is_visible_xywhf(x, y, width, height) {#is_visible_xywhf_x_y_width_height_60}


```
 is_visible_xywhf(x, y, width, height) 
```

Verifica se qualche porzione del rettangolo specificato è contenuta in questo [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da testare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da testare. |
| width | float | La larghezza del rettangolo da testare. |
| height | float | L'altezza del rettangolo da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | vero quando qualsiasi parte del rettangolo specificato è contenuta in questo oggetto [Region](/imaging/python-net/aspose.imaging/region/); altrimenti, falso. |


### Method: transform(matrix) {#transform_matrix_61}


```
 transform(matrix) 
```

Trasforma questo [Region](/imaging/python-net/aspose.imaging/region/) mediante la [Matrix](/imaging/python-net/aspose.imaging/matrix/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) con cui trasformare questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_62}


```
 translate(dx, dy) 
```

Sposta le coordinate di questo [Region](/imaging/python-net/aspose.imaging/region/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | La quantità di spostamento orizzontale di questa [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | float | La quantità di spostamento verticale di questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_63}


```
 translate(dx, dy) 
```

Sposta le coordinate di questo [Region](/imaging/python-net/aspose.imaging/region/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | int | La quantità di spostamento orizzontale di questa [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | int | La quantità di spostamento verticale di questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate_f(dx, dy) {#translate_f_dx_dy_64}


```
 translate_f(dx, dy) 
```

Sposta le coordinate di questo [Region](/imaging/python-net/aspose.imaging/region/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | La quantità di spostamento orizzontale di questa [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | float | La quantità di spostamento verticale di questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(path) {#union_path_65}


```
 union(path) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da unire a questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(rect) {#union_rect_66}


```
 union(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da unire a questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(rect) {#union_rect_67}


```
 union(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da unire a questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(region) {#union_region_68}


```
 union(region) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e del [Region](/imaging/python-net/aspose.imaging/region/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) da unire a questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_path(path) {#union_path_path_69}


```
 union_path(path) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e del [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da unire a questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rect(rect) {#union_rect_rect_70}


```
 union_rect(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da unire a questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rect_f(rect) {#union_rect_f_rect_71}


```
 union_rect_f(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e della struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da unire a questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rgn(region) {#union_rgn_region_72}


```
 union_rgn(region) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione di sé stesso e del [Region](/imaging/python-net/aspose.imaging/region/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) da unire a questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(path) {#xor_path_73}


```
 xor(path) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da xor con questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(rect) {#xor_rect_74}


```
 xor(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da xor con questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(rect) {#xor_rect_75}


```
 xor(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da xor con questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(region) {#xor_region_76}


```
 xor(region) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con il [Region](/imaging/python-net/aspose.imaging/region/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) da xor con questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_path(path) {#xor_path_path_77}


```
 xor_path(path) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Il [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) da xor con questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rect(rect) {#xor_rect_rect_78}


```
 xor_rect(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da xor con questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rect_f(rect) {#xor_rect_f_rect_79}


```
 xor_rect_f(rect) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con la struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La struttura [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) da xor con questa [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rgn(region) {#xor_rgn_region_80}


```
 xor_rgn(region) 
```

Aggiorna questo [Region](/imaging/python-net/aspose.imaging/region/) all'unione meno l'intersezione di sé stesso con il [Region](/imaging/python-net/aspose.imaging/region/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) da xor con questa [Region](/imaging/python-net/aspose.imaging/region/). |

