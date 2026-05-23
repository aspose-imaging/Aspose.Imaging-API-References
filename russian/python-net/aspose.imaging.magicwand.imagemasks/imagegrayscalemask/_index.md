---
title: "Класс ImageGrayscaleMask"
type: docs
weight: 60
url: /ru/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---

**Summary:** Describes a grayscale image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask

**Inheritance:** IImageMask

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageGrayscaleMask(image)](#ImageGrayscaleMask_image_1) | Создаёт новый экземпляр класса [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) с размером указанного существующего [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).<br/>            Указанный [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) будет сохранён как исходное изображение. |
| [ImageGrayscaleMask(width, height)](#ImageGrayscaleMask_width_height_2) | Создаёт новый экземпляр класса [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) с указанной шириной и высотой. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Получает границы, в пикселях, этой маски. |
| height | int | r | Получает высоту, в пикселях, этой маски. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Получает границы выбранной части маски в пикселях. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Получает исходное изображение, использованное для создания этой маски, если оно существует. |
| width | int | r | Получает ширину, в пикселях, этой маски. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| apply() | Применяет текущую маску к источнику [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), если он существует. |
| [apply_to(image)](#apply_to_image_1) | Применяет текущую маску к указанному [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [clone()](#clone__2) | Создаёт новый объект, являющийся копией текущего экземпляра. |
| [crop(rectangle)](#crop_rectangle_3) | Обрезает маску с указанным прямоугольником. |
| [crop(size)](#crop_size_4) | Обрезает маску с указанным размером. |
| [crop(width, height)](#crop_width_height_5) | Обрезает маску с указанными шириной и высотой. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_6) | Получает исключающее ИЛИ текущей маски с предоставленным. |
| [get(x, y)](#get_x_y_7) | Получает или задаёт непрозрачность указанного пикселя. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_8) | Получает непрозрачность указанного пикселя с точностью до байта. |
| [intersect(mask)](#intersect_mask_9) | Получает пересечение текущей маски с предоставленной. |
| [invert()](#invert__10) | Получает инверсию текущей маски. |
| [is_opaque(x, y)](#is_opaque_x_y_11) | Проверяет, является ли указанный пиксель непрозрачным. |
| [is_transparent(x, y)](#is_transparent_x_y_12) | Проверяет, является ли указанный пиксель прозрачным. |
| [set(x, y, value)](#set_x_y_value_13) | Задаёт непрозрачность указанного пикселя. |
| [subtract(mask)](#subtract_mask_14) | Получает вычитание предоставленной маски из текущей. |
| [union(mask)](#union_mask_15) | Объединение двух масок. |


### Constructor: ImageGrayscaleMask(image) {#ImageGrayscaleMask_image_1}


```
 ImageGrayscaleMask(image) 
```

Создаёт новый экземпляр класса [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) с размером указанного существующего [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).<br/>            Указанный [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) будет сохранён как исходное изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Исходное изображение. |

### Constructor: ImageGrayscaleMask(width, height) {#ImageGrayscaleMask_width_height_2}


```
 ImageGrayscaleMask(width, height) 
```

Создаёт новый экземпляр класса [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) с указанной шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина маски. |
| height | int | Высота маски. |

### Method: apply_to(image) {#apply_to_image_1}


```
 apply_to(image) 
```

Применяет текущую маску к указанному [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение, к которому применяется маска. |

### Method: clone() {#clone__2}


```
 clone() 
```

Создаёт новый объект, являющийся копией текущего экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Object | Новый объект, являющийся копией данного экземпляра. |


### Method: crop(rectangle) {#crop_rectangle_3}


```
 crop(rectangle) 
```

Обрезает маску с указанным прямоугольником.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Указанный прямоугольник. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Обрезанный [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: crop(size) {#crop_size_4}


```
 crop(size) 
```

Обрезает маску с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Указанный размер. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Обрезанный [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: crop(width, height) {#crop_width_height_5}


```
 crop(width, height) 
```

Обрезает маску с указанными шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Указанная ширина. |
| height | int | Указанная высота. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Обрезанный [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_6}


```
 exclusive_disjunction(mask) 
```

Получает исключающее ИЛИ текущей маски с предоставленным.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Предоставленная маска |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Новый [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: get(x, y) {#get_x_y_7}


```
 get(x, y) 
```

Получает или задаёт непрозрачность указанного пикселя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Значение байта; 0 — если прозрачно; 255 — если непрозрачно. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_8}


```
 get_byte_opacity(x, y) 
```

Получает непрозрачность указанного пикселя с точностью до байта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Значение байта, представляющее непрозрачность указанного пикселя. |


### Method: intersect(mask) {#intersect_mask_9}


```
 intersect(mask) 
```

Получает пересечение текущей маски с предоставленной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Предоставленная маска |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Новый [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: invert() {#invert__10}


```
 invert() 
```

Получает инверсию текущей маски.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Новый [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_11}


```
 is_opaque(x, y) 
```

Проверяет, является ли указанный пиксель непрозрачным.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, если указанный пиксель непрозрачный; в противном случае — false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_12}


```
 is_transparent(x, y) 
```

Проверяет, является ли указанный пиксель прозрачным.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, если указанный пиксель прозрачный; в противном случае — false. |


### Method: set(x, y, value) {#set_x_y_value_13}


```
 set(x, y, value) 
```

Задаёт непрозрачность указанного пикселя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| значение | System.Byte | Значение байта; 0 — если прозрачно; 255 — если непрозрачно. |

### Method: subtract(mask) {#subtract_mask_14}


```
 subtract(mask) 
```

Получает вычитание предоставленной маски из текущей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Предоставленная маска |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Новый [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: union(mask) {#union_mask_15}


```
 union(mask) 
```

Объединение двух масок.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Предоставленная маска |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Новый [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


