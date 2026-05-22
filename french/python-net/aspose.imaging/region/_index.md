---
title: "Classe Region"
type: docs
weight: 7170
url: /fr/python-net/aspose.imaging/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Region

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Region()](#Region__1) | Initialise un nouveau [Region](/imaging/python-net/aspose.imaging/region/). |
| [Region(path)](#Region_path_2) | Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié. |
| [Region(rect)](#Region_rect_3) | Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) à partir de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [Region(rect)](#Region_rect_4) | Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) à partir de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [complement(path)](#complement_path_1) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie du [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_2) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie de la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_3) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie de la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(region)](#complement_region_4) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie du [Region](/imaging/python-net/aspose.imaging/region/) spécifié qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_path(path)](#complement_path_path_5) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie du [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect(rect)](#complement_rect_rect_6) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie de la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect_f(rect)](#complement_rect_f_rect_7) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie de la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rgn(region)](#complement_rgn_region_8) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie du [Region](/imaging/python-net/aspose.imaging/region/) spécifié qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [create_with_path(path)](#create_with_path_path_9) | Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié. |
| [create_with_rect(rect)](#create_with_rect_rect_10) | Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) à partir de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [create_with_rect_f(rect)](#create_with_rect_f_rect_11) | Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) à partir de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [deep_clone()](#deep_clone__12) | Crée une copie profonde exacte de ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [exclude(path)](#exclude_path_13) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié. |
| [exclude(rect)](#exclude_rect_14) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [exclude(rect)](#exclude_rect_15) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [exclude(region)](#exclude_region_16) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [Region](/imaging/python-net/aspose.imaging/region/) spécifié. |
| [exclude_path(path)](#exclude_path_path_17) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié. |
| [exclude_rect(rect)](#exclude_rect_rect_18) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [exclude_rect_f(rect)](#exclude_rect_f_rect_19) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [exclude_rgn(region)](#exclude_rgn_region_20) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [Region](/imaging/python-net/aspose.imaging/region/) spécifié. |
| [intersect(path)](#intersect_path_21) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié. |
| [intersect(rect)](#intersect_rect_22) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [intersect(rect)](#intersect_rect_23) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [intersect(region)](#intersect_region_24) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec le [Region](/imaging/python-net/aspose.imaging/region/) spécifié. |
| [intersect_path(path)](#intersect_path_path_25) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié. |
| [intersect_rect(rect)](#intersect_rect_rect_26) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [intersect_rect_f(rect)](#intersect_rect_f_rect_27) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [intersect_rgn(region)](#intersect_rgn_region_28) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec le [Region](/imaging/python-net/aspose.imaging/region/) spécifié. |
| [is_empty(g)](#is_empty_g_29) | Teste si ce [Region](/imaging/python-net/aspose.imaging/region/) a un intérieur vide sur la surface de dessin spécifiée. |
| [is_infinite(g)](#is_infinite_g_30) | Teste si ce [Region](/imaging/python-net/aspose.imaging/region/) a un intérieur infini sur la surface de dessin spécifiée. |
| [is_visible(point)](#is_visible_point_31) | Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point)](#is_visible_point_32) | Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point, g)](#is_visible_point_g_33) | Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible(point, g)](#is_visible_point_g_34) | Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible(rect)](#is_visible_rect_35) | Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect)](#is_visible_rect_36) | Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_37) | Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible(rect, g)](#is_visible_rect_g_38) | Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible(x, y)](#is_visible_x_y_39) | Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_40) | Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible(x, y, g)](#is_visible_x_y_g_41) | Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_42) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_43) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_44) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_45) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_f(x, y)](#is_visible_f_x_y_46) | Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point(point)](#is_visible_point_point_47) | Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_48) | Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f_with_graphics(point, g)](#is_visible_point_f_with_graphics_point_g_49) | Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_point_with_graphics(point, g)](#is_visible_point_with_graphics_point_g_50) | Teste si la structure [Point](/imaging/python-net/aspose.imaging/point/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_rect(rect)](#is_visible_rect_rect_51) | Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f(rect)](#is_visible_rect_f_rect_52) | Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f_with_graphics(rect, g)](#is_visible_rect_f_with_graphics_rect_g_53) | Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_rect_with_graphics(rect, g)](#is_visible_rect_with_graphics_rect_g_54) | Teste si une partie de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_with_graphics(x, y, g)](#is_visible_with_graphics_x_y_g_55) | Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_with_graphics_f(x, y, g)](#is_visible_with_graphics_f_x_y_g_56) | Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_xywh(x, y, width, height)](#is_visible_xywh_x_y_width_height_57) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_xywh_graphics(x, y, width, height, g)](#is_visible_xywh_graphics_x_y_width_height_g_58) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_xywh_graphics_f(x, y, width, height, g)](#is_visible_xywh_graphics_f_x_y_width_height_g_59) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié. |
| [is_visible_xywhf(x, y, width, height)](#is_visible_xywhf_x_y_width_height_60) | Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/). |
| make_empty() | Initialise ce [Region](/imaging/python-net/aspose.imaging/region/) à un intérieur vide. |
| make_infinite() | Initialise cet objet [Region](/imaging/python-net/aspose.imaging/region/) avec un intérieur infini. |
| [transform(matrix)](#transform_matrix_61) | Transforme ce [Region](/imaging/python-net/aspose.imaging/region/) selon la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée. |
| [translate(dx, dy)](#translate_dx_dy_62) | Décale les coordonnées de ce [Region](/imaging/python-net/aspose.imaging/region/) du montant spécifié. |
| [translate(dx, dy)](#translate_dx_dy_63) | Décale les coordonnées de ce [Region](/imaging/python-net/aspose.imaging/region/) du montant spécifié. |
| [translate_f(dx, dy)](#translate_f_dx_dy_64) | Décale les coordonnées de ce [Region](/imaging/python-net/aspose.imaging/region/) du montant spécifié. |
| [union(path)](#union_path_65) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et du [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié. |
| [union(rect)](#union_rect_66) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [union(rect)](#union_rect_67) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [union(region)](#union_region_68) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et du [Region](/imaging/python-net/aspose.imaging/region/) spécifié. |
| [union_path(path)](#union_path_path_69) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et du [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié. |
| [union_rect(rect)](#union_rect_rect_70) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [union_rect_f(rect)](#union_rect_f_rect_71) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [union_rgn(region)](#union_rgn_region_72) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et du [Region](/imaging/python-net/aspose.imaging/region/) spécifié. |
| [xor(path)](#xor_path_73) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié. |
| [xor(rect)](#xor_rect_74) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [xor(rect)](#xor_rect_75) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [xor(region)](#xor_region_76) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec le [Region](/imaging/python-net/aspose.imaging/region/) spécifié. |
| [xor_path(path)](#xor_path_path_77) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié. |
| [xor_rect(rect)](#xor_rect_rect_78) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [xor_rect_f(rect)](#xor_rect_f_rect_79) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée. |
| [xor_rgn(region)](#xor_rgn_region_80) | Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec le [Region](/imaging/python-net/aspose.imaging/region/) spécifié. |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Initialise un nouveau [Region](/imaging/python-net/aspose.imaging/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) qui définit le nouveau [Region](/imaging/python-net/aspose.imaging/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) à partir de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui définit l’intérieur du nouveau [Region](/imaging/python-net/aspose.imaging/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) à partir de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui définit l’intérieur du nouveau [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie du [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) pour compléter ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie de la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) pour compléter ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie de la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) pour compléter ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie du [Region](/imaging/python-net/aspose.imaging/region/) spécifié qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | L’objet [Region](/imaging/python-net/aspose.imaging/region/) pour compléter cet objet [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_path(path) {#complement_path_path_5}


```
 complement_path(path) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie du [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) pour compléter ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rect(rect) {#complement_rect_rect_6}


```
 complement_rect(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie de la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) pour compléter ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rect_f(rect) {#complement_rect_f_rect_7}


```
 complement_rect_f(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie de la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) pour compléter ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rgn(region) {#complement_rgn_region_8}


```
 complement_rgn(region) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu'il contienne la partie du [Region](/imaging/python-net/aspose.imaging/region/) spécifié qui n'intersecte pas ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | L’objet [Region](/imaging/python-net/aspose.imaging/region/) pour compléter cet objet [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: create_with_path(path)  [static] {#create_with_path_path_9}


```
 create_with_path(path) 
```

Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Un [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) qui définit le nouveau [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect(rect)  [static] {#create_with_rect_rect_10}


```
 create_with_rect(rect) 
```

Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) à partir de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui définit l’intérieur du nouveau [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect_f(rect)  [static] {#create_with_rect_f_rect_11}


```
 create_with_rect_f(rect) 
```

Initialise une nouvelle [Region](/imaging/python-net/aspose.imaging/region/) à partir de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui définit l’intérieur du nouveau [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: deep_clone() {#deep_clone__12}


```
 deep_clone() 
```

Crée une copie profonde exacte de ce [Region](/imaging/python-net/aspose.imaging/region/).

**Returns**

| Type | Description |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) | Le [Region](/imaging/python-net/aspose.imaging/region/) que cette méthode crée. |


### Method: exclude(path) {#exclude_path_13}


```
 exclude(path) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à exclure de ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(rect) {#exclude_rect_14}


```
 exclude(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à exclure de ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(rect) {#exclude_rect_15}


```
 exclude(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à exclure de ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(region) {#exclude_region_16}


```
 exclude(region) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [Region](/imaging/python-net/aspose.imaging/region/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Le [Region](/imaging/python-net/aspose.imaging/region/) à exclure de ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_path(path) {#exclude_path_path_17}


```
 exclude_path(path) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à exclure de ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rect(rect) {#exclude_rect_rect_18}


```
 exclude_rect(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à exclure de ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rect_f(rect) {#exclude_rect_f_rect_19}


```
 exclude_rect_f(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à exclure de ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rgn(region) {#exclude_rgn_region_20}


```
 exclude_rgn(region) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour ne contenir que la partie de son intérieur qui n'intersecte pas le [Region](/imaging/python-net/aspose.imaging/region/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Le [Region](/imaging/python-net/aspose.imaging/region/) à exclure de ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(path) {#intersect_path_21}


```
 intersect(path) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à intersecter avec ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(rect) {#intersect_rect_22}


```
 intersect(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à intersecter avec ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(rect) {#intersect_rect_23}


```
 intersect(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à intersecter avec ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(region) {#intersect_region_24}


```
 intersect(region) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec le [Region](/imaging/python-net/aspose.imaging/region/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Le [Region](/imaging/python-net/aspose.imaging/region/) à intersecter avec ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_path(path) {#intersect_path_path_25}


```
 intersect_path(path) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à intersecter avec ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rect(rect) {#intersect_rect_rect_26}


```
 intersect_rect(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à intersecter avec ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rect_f(rect) {#intersect_rect_f_rect_27}


```
 intersect_rect_f(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec la [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à intersecter avec ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rgn(region) {#intersect_rgn_region_28}


```
 intersect_rgn(region) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) à l'intersection de lui-même avec le [Region](/imaging/python-net/aspose.imaging/region/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Le [Region](/imaging/python-net/aspose.imaging/region/) à intersecter avec ce [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: is_empty(g) {#is_empty_g_29}


```
 is_empty(g) 
```

Teste si ce [Region](/imaging/python-net/aspose.imaging/region/) a un intérieur vide sur la surface de dessin spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente une surface de dessin. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true si l’intérieur de ce [Region](/imaging/python-net/aspose.imaging/region/) est vide lorsque la transformation associée à _g_ est appliquée ; sinon, false. |


### Method: is_infinite(g) {#is_infinite_g_30}


```
 is_infinite(g) 
```

Teste si ce [Region](/imaging/python-net/aspose.imaging/region/) a un intérieur infini sur la surface de dessin spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente une surface de dessin. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true si l’intérieur de ce [Region](/imaging/python-net/aspose.imaging/region/) est infini lorsque la transformation associée à _g_ est appliquée ; sinon, false. |


### Method: is_visible(point) {#is_visible_point_31}


```
 is_visible(point) 
```

Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La structure [PointF](/imaging/python-net/aspose.imaging/pointf/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _point_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(point) {#is_visible_point_32}


```
 is_visible(point) 
```

Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La structure [PointF](/imaging/python-net/aspose.imaging/pointf/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _point_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(point, g) {#is_visible_point_g_33}


```
 is_visible(point, g) 
```

Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La structure [PointF](/imaging/python-net/aspose.imaging/pointf/) à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _point_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(point, g) {#is_visible_point_g_34}


```
 is_visible(point, g) 
```

Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La structure [PointF](/imaging/python-net/aspose.imaging/pointf/) à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _point_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(rect) {#is_visible_rect_35}


```
 is_visible(rect) 
```

Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie de _rect_ est contenue dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(rect) {#is_visible_rect_36}


```
 is_visible(rect) 
```

Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie de _rect_ est contenue dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(rect, g) {#is_visible_rect_g_37}


```
 is_visible(rect, g) 
```

Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _rect_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(rect, g) {#is_visible_rect_g_38}


```
 is_visible(rect, g) 
```

Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _rect_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(x, y) {#is_visible_x_y_39}


```
 is_visible(x, y) 
```

Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai lorsque le point spécifié est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_40}


```
 is_visible(x, y, g) 
```

Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai lorsque le point spécifié est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_41}


```
 is_visible(x, y, g) 
```

Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai lorsque le point spécifié est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_42}


```
 is_visible(x, y, width, height) 
```

Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | float | La largeur du rectangle à tester. |
| height | float | La hauteur du rectangle à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cet objet [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_43}


```
 is_visible(x, y, width, height) 
```

Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | int | La largeur du rectangle à tester. |
| height | int | La hauteur du rectangle à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cet objet [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_44}


```
 is_visible(x, y, width, height, g) 
```

Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | float | La largeur du rectangle à tester. |
| height | float | La hauteur du rectangle à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_45}


```
 is_visible(x, y, width, height, g) 
```

Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | int | La largeur du rectangle à tester. |
| height | int | La hauteur du rectangle à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_f(x, y) {#is_visible_f_x_y_46}


```
 is_visible_f(x, y) 
```

Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai lorsque le point spécifié est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_point(point) {#is_visible_point_point_47}


```
 is_visible_point(point) 
```

Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La structure [PointF](/imaging/python-net/aspose.imaging/pointf/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _point_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_48}


```
 is_visible_point_f(point) 
```

Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La structure [PointF](/imaging/python-net/aspose.imaging/pointf/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _point_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_point_f_with_graphics(point, g) {#is_visible_point_f_with_graphics_point_g_49}


```
 is_visible_point_f_with_graphics(point, g) 
```

Teste si la structure [PointF](/imaging/python-net/aspose.imaging/pointf/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | La structure [PointF](/imaging/python-net/aspose.imaging/pointf/) à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _point_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_point_with_graphics(point, g) {#is_visible_point_with_graphics_point_g_50}


```
 is_visible_point_with_graphics(point, g) 
```

Teste si la structure [Point](/imaging/python-net/aspose.imaging/point/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | La structure [Point](/imaging/python-net/aspose.imaging/point/) à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _point_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_rect(rect) {#is_visible_rect_rect_51}


```
 is_visible_rect(rect) 
```

Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie de _rect_ est contenue dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_rect_f(rect) {#is_visible_rect_f_rect_52}


```
 is_visible_rect_f(rect) 
```

Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie de _rect_ est contenue dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_rect_f_with_graphics(rect, g) {#is_visible_rect_f_with_graphics_rect_g_53}


```
 is_visible_rect_f_with_graphics(rect, g) 
```

Teste si une partie de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque _rect_ est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_rect_with_graphics(rect, g) {#is_visible_rect_with_graphics_rect_g_54}


```
 is_visible_rect_with_graphics(rect, g) 
```

Teste si une partie de la structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) spécifiée est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'elle est dessinée avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie de _rect_ est contenue dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_with_graphics(x, y, g) {#is_visible_with_graphics_x_y_g_55}


```
 is_visible_with_graphics(x, y, g) 
```

Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du point à tester. |
| y | int | La coordonnée y du point à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai lorsque le point spécifié est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_with_graphics_f(x, y, g) {#is_visible_with_graphics_f_x_y_g_56}


```
 is_visible_with_graphics_f(x, y, g) 
```

Teste si le point spécifié est contenu dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du point à tester. |
| y | float | La coordonnée y du point à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai lorsque le point spécifié est contenu dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_xywh(x, y, width, height) {#is_visible_xywh_x_y_width_height_57}


```
 is_visible_xywh(x, y, width, height) 
```

Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | int | La largeur du rectangle à tester. |
| height | int | La hauteur du rectangle à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cet objet [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_xywh_graphics(x, y, width, height, g) {#is_visible_xywh_graphics_x_y_width_height_g_58}


```
 is_visible_xywh_graphics(x, y, width, height, g) 
```

Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | int | La largeur du rectangle à tester. |
| height | int | La hauteur du rectangle à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_xywh_graphics_f(x, y, width, height, g) {#is_visible_xywh_graphics_f_x_y_width_height_g_59}


```
 is_visible_xywh_graphics_f(x, y, width, height, g) 
```

Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/) lorsqu'il est dessiné avec le [Graphics](/imaging/python-net/aspose.imaging/graphics/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | float | La largeur du rectangle à tester. |
| height | float | La hauteur du rectangle à tester. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Un [Graphics](/imaging/python-net/aspose.imaging/graphics/) qui représente un contexte graphique. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cette [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: is_visible_xywhf(x, y, width, height) {#is_visible_xywhf_x_y_width_height_60}


```
 is_visible_xywhf(x, y, width, height) 
```

Teste si une partie du rectangle spécifié est contenue dans ce [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à tester. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à tester. |
| width | float | La largeur du rectangle à tester. |
| height | float | La hauteur du rectangle à tester. |

**Returns**

| Type | Description |
| :- | :- |
| bool | vrai lorsque n'importe quelle partie du rectangle spécifié est contenue dans cet objet [Region](/imaging/python-net/aspose.imaging/region/); sinon, faux. |


### Method: transform(matrix) {#transform_matrix_61}


```
 transform(matrix) 
```

Transforme ce [Region](/imaging/python-net/aspose.imaging/region/) selon la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle transformer cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_62}


```
 translate(dx, dy) 
```

Décale les coordonnées de ce [Region](/imaging/python-net/aspose.imaging/region/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La quantité pour décaler horizontalement cette [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | float | La quantité pour décaler verticalement cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_63}


```
 translate(dx, dy) 
```

Décale les coordonnées de ce [Region](/imaging/python-net/aspose.imaging/region/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | int | La quantité pour décaler horizontalement cette [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | int | La quantité pour décaler verticalement cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate_f(dx, dy) {#translate_f_dx_dy_64}


```
 translate_f(dx, dy) 
```

Décale les coordonnées de ce [Region](/imaging/python-net/aspose.imaging/region/) du montant spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La quantité pour décaler horizontalement cette [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | float | La quantité pour décaler verticalement cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(path) {#union_path_65}


```
 union(path) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et du [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à unir avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(rect) {#union_rect_66}


```
 union(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à unir avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(rect) {#union_rect_67}


```
 union(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à unir avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(region) {#union_region_68}


```
 union(region) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et du [Region](/imaging/python-net/aspose.imaging/region/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) à unir avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_path(path) {#union_path_path_69}


```
 union_path(path) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et du [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à unir avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rect(rect) {#union_rect_rect_70}


```
 union_rect(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à unir avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rect_f(rect) {#union_rect_f_rect_71}


```
 union_rect_f(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et de la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à unir avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rgn(region) {#union_rgn_region_72}


```
 union_rgn(region) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union de lui‑même et du [Region](/imaging/python-net/aspose.imaging/region/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) à unir avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(path) {#xor_path_73}


```
 xor(path) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à xor avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(rect) {#xor_rect_74}


```
 xor(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à xor avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(rect) {#xor_rect_75}


```
 xor(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à xor avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(region) {#xor_region_76}


```
 xor(region) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec le [Region](/imaging/python-net/aspose.imaging/region/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) à xor avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_path(path) {#xor_path_path_77}


```
 xor_path(path) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) à xor avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rect(rect) {#xor_rect_rect_78}


```
 xor_rect(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à xor avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rect_f(rect) {#xor_rect_f_rect_79}


```
 xor_rect_f(rect) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec la structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | La structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) à xor avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rgn(region) {#xor_rgn_region_80}


```
 xor_rgn(region) 
```

Met à jour ce [Region](/imaging/python-net/aspose.imaging/region/) pour qu’il soit l’union moins l’intersection de lui‑même avec le [Region](/imaging/python-net/aspose.imaging/region/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | La [Region](/imaging/python-net/aspose.imaging/region/) à xor avec cette [Region](/imaging/python-net/aspose.imaging/region/). |

