---
title: "Класс Region"
type: docs
weight: 7170
url: /ru/python-net/aspose.imaging/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Region

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Region()](#Region__1) | Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/). |
| [Region(path)](#Region_path_2) | Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [Region(rect)](#Region_rect_3) | Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) из указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [Region(rect)](#Region_rect_4) | Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) из указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [complement(path)](#complement_path_1) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_2) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(rect)](#complement_rect_3) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement(region)](#complement_region_4) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанного [Region](/imaging/python-net/aspose.imaging/region/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_path(path)](#complement_path_path_5) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect(rect)](#complement_rect_rect_6) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rect_f(rect)](#complement_rect_f_rect_7) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/). |
| [complement_rgn(region)](#complement_rgn_region_8) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанного [Region](/imaging/python-net/aspose.imaging/region/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/). |
| [create_with_path(path)](#create_with_path_path_9) | Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [create_with_rect(rect)](#create_with_rect_rect_10) | Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) из указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [create_with_rect_f(rect)](#create_with_rect_f_rect_11) | Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) из указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [deep_clone()](#deep_clone__12) | Создаёт точную глубокую копию этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [exclude(path)](#exclude_path_13) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [exclude(rect)](#exclude_rect_14) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [exclude(rect)](#exclude_rect_15) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [exclude(region)](#exclude_region_16) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанным [Region](/imaging/python-net/aspose.imaging/region/). |
| [exclude_path(path)](#exclude_path_path_17) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [exclude_rect(rect)](#exclude_rect_rect_18) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [exclude_rect_f(rect)](#exclude_rect_f_rect_19) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [exclude_rgn(region)](#exclude_rgn_region_20) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанным [Region](/imaging/python-net/aspose.imaging/region/). |
| [intersect(path)](#intersect_path_21) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [intersect(rect)](#intersect_rect_22) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [intersect(rect)](#intersect_rect_23) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [intersect(region)](#intersect_region_24) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанным [Region](/imaging/python-net/aspose.imaging/region/). |
| [intersect_path(path)](#intersect_path_path_25) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [intersect_rect(rect)](#intersect_rect_rect_26) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [intersect_rect_f(rect)](#intersect_rect_f_rect_27) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [intersect_rgn(region)](#intersect_rgn_region_28) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанным [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_empty(g)](#is_empty_g_29) | Проверяет, имеет ли этот [Region](/imaging/python-net/aspose.imaging/region/) пустую внутреннюю область на указанной поверхности рисования. |
| [is_infinite(g)](#is_infinite_g_30) | Проверяет, имеет ли этот [Region](/imaging/python-net/aspose.imaging/region/) бесконечную внутреннюю область на указанной поверхности рисования. |
| [is_visible(point)](#is_visible_point_31) | Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point)](#is_visible_point_32) | Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(point, g)](#is_visible_point_g_33) | Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(point, g)](#is_visible_point_g_34) | Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(rect)](#is_visible_rect_35) | Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect)](#is_visible_rect_36) | Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(rect, g)](#is_visible_rect_g_37) | Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(rect, g)](#is_visible_rect_g_38) | Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y)](#is_visible_x_y_39) | Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_40) | Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, g)](#is_visible_x_y_g_41) | Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_42) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_43) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_44) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_45) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_f(x, y)](#is_visible_f_x_y_46) | Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point(point)](#is_visible_point_point_47) | Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f(point)](#is_visible_point_f_point_48) | Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_point_f_with_graphics(point, g)](#is_visible_point_f_with_graphics_point_g_49) | Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_point_with_graphics(point, g)](#is_visible_point_with_graphics_point_g_50) | Проверяет, содержится ли указанная структура [Point](/imaging/python-net/aspose.imaging/point/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_rect(rect)](#is_visible_rect_rect_51) | Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f(rect)](#is_visible_rect_f_rect_52) | Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_rect_f_with_graphics(rect, g)](#is_visible_rect_f_with_graphics_rect_g_53) | Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_rect_with_graphics(rect, g)](#is_visible_rect_with_graphics_rect_g_54) | Проверяет, содержится ли какая‑либо часть указанной структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_with_graphics(x, y, g)](#is_visible_with_graphics_x_y_g_55) | Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_with_graphics_f(x, y, g)](#is_visible_with_graphics_f_x_y_g_56) | Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xywh(x, y, width, height)](#is_visible_xywh_x_y_width_height_57) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| [is_visible_xywh_graphics(x, y, width, height, g)](#is_visible_xywh_graphics_x_y_width_height_g_58) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xywh_graphics_f(x, y, width, height, g)](#is_visible_xywh_graphics_f_x_y_width_height_g_59) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/). |
| [is_visible_xywhf(x, y, width, height)](#is_visible_xywhf_x_y_width_height_60) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/). |
| make_empty() | Инициализирует этот [Region](/imaging/python-net/aspose.imaging/region/) пустой внутренней областью. |
| make_infinite() | Инициализирует этот объект [Region](/imaging/python-net/aspose.imaging/region/) бесконечным внутренним пространством. |
| [transform(matrix)](#transform_matrix_61) | Трансформирует этот [Region](/imaging/python-net/aspose.imaging/region/) с помощью указанной [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [translate(dx, dy)](#translate_dx_dy_62) | Смещает координаты этого [Region](/imaging/python-net/aspose.imaging/region/) на указанную величину. |
| [translate(dx, dy)](#translate_dx_dy_63) | Смещает координаты этого [Region](/imaging/python-net/aspose.imaging/region/) на указанную величину. |
| [translate_f(dx, dy)](#translate_f_dx_dy_64) | Смещает координаты этого [Region](/imaging/python-net/aspose.imaging/region/) на указанную величину. |
| [union(path)](#union_path_65) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [union(rect)](#union_rect_66) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [union(rect)](#union_rect_67) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [union(region)](#union_region_68) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанным [Region](/imaging/python-net/aspose.imaging/region/). |
| [union_path(path)](#union_path_path_69) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [union_rect(rect)](#union_rect_rect_70) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [union_rect_f(rect)](#union_rect_f_rect_71) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [union_rgn(region)](#union_rgn_region_72) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанным [Region](/imaging/python-net/aspose.imaging/region/). |
| [xor(path)](#xor_path_73) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [xor(rect)](#xor_rect_74) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [xor(rect)](#xor_rect_75) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [xor(region)](#xor_region_76) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанным [Region](/imaging/python-net/aspose.imaging/region/). |
| [xor_path(path)](#xor_path_path_77) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [xor_rect(rect)](#xor_rect_rect_78) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [xor_rect_f(rect)](#xor_rect_f_rect_79) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/). |
| [xor_rgn(region)](#xor_rgn_region_80) | Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанным [Region](/imaging/python-net/aspose.imaging/region/). |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/).

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), определяющий новый [Region](/imaging/python-net/aspose.imaging/region/). |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) из указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая внутреннее пространство нового [Region](/imaging/python-net/aspose.imaging/region/). |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) из указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая внутреннее пространство нового [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), дополняющий этот [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), дополняющая этот [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), дополняющая этот [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанного [Region](/imaging/python-net/aspose.imaging/region/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Объект [Region](/imaging/python-net/aspose.imaging/region/), дополняющий этот объект [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_path(path) {#complement_path_path_5}


```
 complement_path(path) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанного [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), дополняющий этот [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rect(rect) {#complement_rect_rect_6}


```
 complement_rect(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), дополняющая этот [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rect_f(rect) {#complement_rect_f_rect_7}


```
 complement_rect_f(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), дополняющая этот [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: complement_rgn(region) {#complement_rgn_region_8}


```
 complement_rgn(region) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал часть указанного [Region](/imaging/python-net/aspose.imaging/region/), не пересекающуюся с этим [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Объект [Region](/imaging/python-net/aspose.imaging/region/), дополняющий этот объект [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: create_with_path(path)  [static] {#create_with_path_path_9}


```
 create_with_path(path) 
```

Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), определяющий новый [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect(rect)  [static] {#create_with_rect_rect_10}


```
 create_with_rect(rect) 
```

Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) из указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая внутреннее пространство нового [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: create_with_rect_f(rect)  [static] {#create_with_rect_f_rect_11}


```
 create_with_rect_f(rect) 
```

Инициализирует новый [Region](/imaging/python-net/aspose.imaging/region/) из указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), определяющая внутреннее пространство нового [Region](/imaging/python-net/aspose.imaging/region/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) |  |


### Method: deep_clone() {#deep_clone__12}


```
 deep_clone() 
```

Создаёт точную глубокую копию этого [Region](/imaging/python-net/aspose.imaging/region/).

**Returns**

| Тип | Описание |
| :- | :- |
| [Region](/imaging/python-net/aspose.imaging/region/) | Объект [Region](/imaging/python-net/aspose.imaging/region/), который создаёт этот метод. |


### Method: exclude(path) {#exclude_path_13}


```
 exclude(path) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), исключаемый из этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(rect) {#exclude_rect_14}


```
 exclude(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), исключаемая из этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(rect) {#exclude_rect_15}


```
 exclude(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), исключаемая из этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude(region) {#exclude_region_16}


```
 exclude(region) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанным [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Объект [Region](/imaging/python-net/aspose.imaging/region/), исключаемый из этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_path(path) {#exclude_path_path_17}


```
 exclude_path(path) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), исключаемый из этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rect(rect) {#exclude_rect_rect_18}


```
 exclude_rect(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), исключаемая из этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rect_f(rect) {#exclude_rect_f_rect_19}


```
 exclude_rect_f(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), исключаемая из этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: exclude_rgn(region) {#exclude_rgn_region_20}


```
 exclude_rgn(region) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), чтобы он содержал только ту часть своей внутренней области, которая не пересекается с указанным [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Объект [Region](/imaging/python-net/aspose.imaging/region/), исключаемый из этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(path) {#intersect_path_21}


```
 intersect(path) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), пересекающийся с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(rect) {#intersect_rect_22}


```
 intersect(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), пересекающаяся с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(rect) {#intersect_rect_23}


```
 intersect(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), пересекающаяся с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect(region) {#intersect_region_24}


```
 intersect(region) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанным [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Объект [Region](/imaging/python-net/aspose.imaging/region/), пересекающийся с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_path(path) {#intersect_path_path_25}


```
 intersect_path(path) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Объект [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/), пересекающийся с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rect(rect) {#intersect_rect_rect_26}


```
 intersect_rect(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), пересекающаяся с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rect_f(rect) {#intersect_rect_f_rect_27}


```
 intersect_rect_f(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/), пересекающаяся с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: intersect_rgn(region) {#intersect_rgn_region_28}


```
 intersect_rgn(region) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/), задавая его пересечение с указанным [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | Объект [Region](/imaging/python-net/aspose.imaging/region/), пересекающийся с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: is_empty(g) {#is_empty_g_29}


```
 is_empty(g) 
```

Проверяет, имеет ли этот [Region](/imaging/python-net/aspose.imaging/region/) пустую внутреннюю область на указанной поверхности рисования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/), представляющий поверхность для рисования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, если внутреннее пространство этого [Region](/imaging/python-net/aspose.imaging/region/) пусто при применении преобразования, связанного с _g_; иначе false. |


### Method: is_infinite(g) {#is_infinite_g_30}


```
 is_infinite(g) 
```

Проверяет, имеет ли этот [Region](/imaging/python-net/aspose.imaging/region/) бесконечную внутреннюю область на указанной поверхности рисования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/), представляющий поверхность для рисования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, если внутреннее пространство этого [Region](/imaging/python-net/aspose.imaging/region/) бесконечно при применении преобразования, связанного с _g_; иначе false. |


### Method: is_visible(point) {#is_visible_point_31}


```
 is_visible(point) 
```

Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _point_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(point) {#is_visible_point_32}


```
 is_visible(point) 
```

Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _point_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(point, g) {#is_visible_point_g_33}


```
 is_visible(point, g) 
```

Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _point_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(point, g) {#is_visible_point_g_34}


```
 is_visible(point, g) 
```

Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _point_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(rect) {#is_visible_rect_35}


```
 is_visible(rect) 
```

Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть _rect_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(rect) {#is_visible_rect_36}


```
 is_visible(rect) 
```

Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть _rect_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_37}


```
 is_visible(rect, g) 
```

Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _rect_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_38}


```
 is_visible(rect, g) 
```

Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _rect_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(x, y) {#is_visible_x_y_39}


```
 is_visible(x, y) 
```

Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, когда указанная точка находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_40}


```
 is_visible(x, y, g) 
```

Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, когда указанная точка находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_41}


```
 is_visible(x, y, g) 
```

Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, когда указанная точка находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_42}


```
 is_visible(x, y, width, height) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | float | Координата y верхнего левого угла прямоугольника для тестирования. |
| width | float | Ширина прямоугольника для тестирования. |
| height | float | Высота прямоугольника для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника находится в этом объекте [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_43}


```
 is_visible(x, y, width, height) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | int | Координата y верхнего левого угла прямоугольника для тестирования. |
| width | int | Ширина прямоугольника для тестирования. |
| height | int | Высота прямоугольника для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника находится в этом объекте [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_44}


```
 is_visible(x, y, width, height, g) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | float | Координата y верхнего левого угла прямоугольника для тестирования. |
| width | float | Ширина прямоугольника для тестирования. |
| height | float | Высота прямоугольника для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника находится в этом [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_45}


```
 is_visible(x, y, width, height, g) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | int | Координата y верхнего левого угла прямоугольника для тестирования. |
| width | int | Ширина прямоугольника для тестирования. |
| height | int | Высота прямоугольника для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника находится в этом [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_f(x, y) {#is_visible_f_x_y_46}


```
 is_visible_f(x, y) 
```

Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, когда указанная точка находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_point(point) {#is_visible_point_point_47}


```
 is_visible_point(point) 
```

Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _point_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_point_f(point) {#is_visible_point_f_point_48}


```
 is_visible_point_f(point) 
```

Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _point_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_point_f_with_graphics(point, g) {#is_visible_point_f_with_graphics_point_g_49}


```
 is_visible_point_f_with_graphics(point, g) 
```

Проверяет, содержится ли указанная структура [PointF](/imaging/python-net/aspose.imaging/pointf/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Структура [PointF](/imaging/python-net/aspose.imaging/pointf/) для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _point_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_point_with_graphics(point, g) {#is_visible_point_with_graphics_point_g_50}


```
 is_visible_point_with_graphics(point, g) 
```

Проверяет, содержится ли указанная структура [Point](/imaging/python-net/aspose.imaging/point/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | Структура [Point](/imaging/python-net/aspose.imaging/point/) для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _point_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_rect(rect) {#is_visible_rect_rect_51}


```
 is_visible_rect(rect) 
```

Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть _rect_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_rect_f(rect) {#is_visible_rect_f_rect_52}


```
 is_visible_rect_f(rect) 
```

Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть _rect_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_rect_f_with_graphics(rect, g) {#is_visible_rect_f_with_graphics_rect_g_53}


```
 is_visible_rect_f_with_graphics(rect, g) 
```

Проверяет, содержится ли какая‑либо часть указанной структуры [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда _rect_ находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_rect_with_graphics(rect, g) {#is_visible_rect_with_graphics_rect_g_54}


```
 is_visible_rect_with_graphics(rect, g) 
```

Проверяет, содержится ли какая‑либо часть указанной структуры [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть _rect_ находится в этом [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_with_graphics(x, y, g) {#is_visible_with_graphics_x_y_g_55}


```
 is_visible_with_graphics(x, y, g) 
```

Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, когда указанная точка находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_with_graphics_f(x, y, g) {#is_visible_with_graphics_f_x_y_g_56}


```
 is_visible_with_graphics_f(x, y, g) 
```

Проверяет, содержится ли указанная точка внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, когда указанная точка находится внутри этого [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_xywh(x, y, width, height) {#is_visible_xywh_x_y_width_height_57}


```
 is_visible_xywh(x, y, width, height) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | int | Координата y верхнего левого угла прямоугольника для тестирования. |
| width | int | Ширина прямоугольника для тестирования. |
| height | int | Высота прямоугольника для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника находится в этом объекте [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_xywh_graphics(x, y, width, height, g) {#is_visible_xywh_graphics_x_y_width_height_g_58}


```
 is_visible_xywh_graphics(x, y, width, height, g) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | int | Координата y верхнего левого угла прямоугольника для тестирования. |
| width | int | Ширина прямоугольника для тестирования. |
| height | int | Высота прямоугольника для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника находится в этом [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_xywh_graphics_f(x, y, width, height, g) {#is_visible_xywh_graphics_f_x_y_width_height_g_59}


```
 is_visible_xywh_graphics_f(x, y, width, height, g) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/) при отрисовке с использованием указанного [Graphics](/imaging/python-net/aspose.imaging/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | float | Координата y верхнего левого угла прямоугольника для тестирования. |
| width | float | Ширина прямоугольника для тестирования. |
| height | float | Высота прямоугольника для тестирования. |
| g | [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Объект [Graphics](/imaging/python-net/aspose.imaging/graphics/) представляющий графический контекст. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника находится в этом [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: is_visible_xywhf(x, y, width, height) {#is_visible_xywhf_x_y_width_height_60}


```
 is_visible_xywhf(x, y, width, height) 
```

Проверяет, содержится ли какая‑либо часть указанного прямоугольника внутри этого [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | float | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | float | Координата y верхнего левого угла прямоугольника для тестирования. |
| width | float | Ширина прямоугольника для тестирования. |
| height | float | Высота прямоугольника для тестирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, когда любая часть указанного прямоугольника находится в этом объекте [Region](/imaging/python-net/aspose.imaging/region/); иначе false. |


### Method: transform(matrix) {#transform_matrix_61}


```
 transform(matrix) 
```

Трансформирует этот [Region](/imaging/python-net/aspose.imaging/region/) с помощью указанной [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Матрица [Matrix](/imaging/python-net/aspose.imaging/matrix/) для преобразования этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_62}


```
 translate(dx, dy) 
```

Смещает координаты этого [Region](/imaging/python-net/aspose.imaging/region/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Величина горизонтального смещения этого [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | float | Величина вертикального смещения этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_63}


```
 translate(dx, dy) 
```

Смещает координаты этого [Region](/imaging/python-net/aspose.imaging/region/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | int | Величина горизонтального смещения этого [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | int | Величина вертикального смещения этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: translate_f(dx, dy) {#translate_f_dx_dy_64}


```
 translate_f(dx, dy) 
```

Смещает координаты этого [Region](/imaging/python-net/aspose.imaging/region/) на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Величина горизонтального смещения этого [Region](/imaging/python-net/aspose.imaging/region/). |
| dy | float | Величина вертикального смещения этого [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(path) {#union_path_65}


```
 union(path) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) для объединения с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(rect) {#union_rect_66}


```
 union(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для объединения с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(rect) {#union_rect_67}


```
 union(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для объединения с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union(region) {#union_region_68}


```
 union(region) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанным [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) для объединения с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_path(path) {#union_path_path_69}


```
 union_path(path) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) для объединения с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rect(rect) {#union_rect_rect_70}


```
 union_rect(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для объединения с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rect_f(rect) {#union_rect_f_rect_71}


```
 union_rect_f(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для объединения с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: union_rgn(region) {#union_rgn_region_72}


```
 union_rgn(region) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения себя с указанным [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) для объединения с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(path) {#xor_path_73}


```
 xor(path) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) для XOR с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(rect) {#xor_rect_74}


```
 xor(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для XOR с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(rect) {#xor_rect_75}


```
 xor(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для XOR с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor(region) {#xor_region_76}


```
 xor(region) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанным [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) для XOR с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_path(path) {#xor_path_path_77}


```
 xor_path(path) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанным [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) для XOR с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rect(rect) {#xor_rect_rect_78}


```
 xor_rect(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для XOR с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rect_f(rect) {#xor_rect_f_rect_79}


```
 xor_rect_f(rect) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанной структурой [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Структура [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) для XOR с этим [Region](/imaging/python-net/aspose.imaging/region/). |

### Method: xor_rgn(region) {#xor_rgn_region_80}


```
 xor_rgn(region) 
```

Обновляет этот [Region](/imaging/python-net/aspose.imaging/region/) до объединения за вычетом пересечения себя с указанным [Region](/imaging/python-net/aspose.imaging/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| region | [Region](/imaging/python-net/aspose.imaging/region/) | [Region](/imaging/python-net/aspose.imaging/region/) для XOR с этим [Region](/imaging/python-net/aspose.imaging/region/). |

