---
title: "Класс ImageBitMask"
type: docs
weight: 50
url: /ru/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/
---

**Summary:** Describes a binary image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageBitMask

**Inheritance:** IImageMask, ImageMask

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageBitMask(image)](#ImageBitMask_image_1) | Создаёт новый экземпляр класса [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) с размером указанного существующего [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).<br/>            Указанный [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) будет сохранён как исходное изображение. |
| [ImageBitMask(width, height)](#ImageBitMask_width_height_2) | Создаёт новый экземпляр класса [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) с указанной шириной и высотой. |
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
| [exclusive_disjunction(image, settings)](#exclusive_disjunction_image_settings_6) | Получает исключающее ИЛИ текущей маски с результатом выбора волшебной палочки, примененного к предоставленному изображению. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_7) | Получает исключающее ИЛИ текущей маски с предоставленным. |
| [exclusive_disjunction(settings)](#exclusive_disjunction_settings_8) | Получает исключающее ИЛИ текущей маски с результатом выбора волшебной палочки, примененного к источнику маски. |
| [get(x, y)](#get_x_y_9) | Получает позицию в массиве хранения указанного пикселя. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_10) | Получает непрозрачность указанного пикселя с точностью до байта. |
| [get_feathered(settings)](#get_feathered_settings_11) | Получает маску в градациях серого с размытой границей согласно указанным настройкам. |
| [inflate(size)](#inflate_size_12) | Увеличивает эту маску на указанную величину. |
| [intersect(image, settings)](#intersect_image_settings_13) | Получает пересечение текущей маски с результатом выделения волшебной палочкой, применённого к предоставленному изображению. |
| [intersect(mask)](#intersect_mask_14) | Получает пересечение текущей маски с предоставленной. |
| [intersect(settings)](#intersect_settings_15) | Получает пересечение текущей маски с результатом выделения волшебной палочкой, применённого к источнику маски. |
| [invert()](#invert__16) | Получает инверсию текущей маски. |
| [is_opaque(x, y)](#is_opaque_x_y_17) | Проверяет, является ли указанный пиксель непрозрачным. |
| [is_transparent(x, y)](#is_transparent_x_y_18) | Проверяет, является ли указанный пиксель прозрачным. |
| [set_mask_pixel(x, y, value)](#set_mask_pixel_x_y_value_19) | Устанавливает непрозрачность указанного пикселя. |
| [subtract(image, settings)](#subtract_image_settings_20) | Получает результат выделения волшебной палочкой, применённого к предоставленному изображению, вычтенный из текущей маски. |
| [subtract(mask)](#subtract_mask_21) | Получает вычитание предоставленной маски из текущей. |
| [subtract(settings)](#subtract_settings_22) | Получает результат выделения волшебной палочкой, применённого к источнику текущей маски, вычтенный из маски. |
| [union(image, settings)](#union_image_settings_23) | Получает объединение текущей маски с результатом выделения волшебной палочкой, применённого к предоставленному изображению. |
| [union(mask)](#union_mask_24) | Получает объединение текущей маски с предоставленной. |
| [union(settings)](#union_settings_25) | Получает объединение текущей маски с результатом выделения волшебной палочкой, применённого к источнику маски. |


### Constructor: ImageBitMask(image) {#ImageBitMask_image_1}


```
 ImageBitMask(image) 
```

Создаёт новый экземпляр класса [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) с размером указанного существующего [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).<br/>            Указанный [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) будет сохранён как исходное изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Исходное изображение. |

### Constructor: ImageBitMask(width, height) {#ImageBitMask_width_height_2}


```
 ImageBitMask(width, height) 
```

Создаёт новый экземпляр класса [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) с указанной шириной и высотой.

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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Обрезанный [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) как [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/). |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | ImageMask. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | ImageMask. |


### Method: exclusive_disjunction(image, settings) {#exclusive_disjunction_image_settings_6}


```
 exclusive_disjunction(image, settings) 
```

Получает исключающее ИЛИ текущей маски с результатом выбора волшебной палочки, примененного к предоставленному изображению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение для волшебной палочки. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Настройки волшебной палочки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_7}


```
 exclusive_disjunction(mask) 
```

Получает исключающее ИЛИ текущей маски с предоставленным.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Предоставленная маска |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(settings) {#exclusive_disjunction_settings_8}


```
 exclusive_disjunction(settings) 
```

Получает исключающее ИЛИ текущей маски с результатом выбора волшебной палочки, примененного к источнику маски.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Настройки волшебной палочки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: get(x, y) {#get_x_y_9}


```
 get(x, y) 
```

Получает позицию в массиве хранения указанного пикселя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Целочисленное значение, представляющее позицию в хранилище. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_10}


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


### Method: get_feathered(settings) {#get_feathered_settings_11}


```
 get_feathered(settings) 
```

Получает маску в градациях серого с размытой границей согласно указанным настройкам.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| settings | [FeatheringSettings](/imaging/python-net/aspose.imaging.magicwand.imagemasks/featheringsettings/) | Настройки растушевки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) с растушеванной границей. |


### Method: inflate(size) {#inflate_size_12}


```
 inflate(size) 
```

Увеличивает эту маску на указанную величину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| size | int | Величина, на которую следует надуть эту маску. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Раздутый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) как [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/). |


### Method: intersect(image, settings) {#intersect_image_settings_13}


```
 intersect(image, settings) 
```

Получает пересечение текущей маски с результатом выделения волшебной палочкой, применённого к предоставленному изображению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение для волшебной палочки. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Настройки волшебной палочки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(mask) {#intersect_mask_14}


```
 intersect(mask) 
```

Получает пересечение текущей маски с предоставленной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Предоставленная маска |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(settings) {#intersect_settings_15}


```
 intersect(settings) 
```

Получает пересечение текущей маски с результатом выделения волшебной палочкой, применённого к источнику маски.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Настройки волшебной палочки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: invert() {#invert__16}


```
 invert() 
```

Получает инверсию текущей маски.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_17}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_18}


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


### Method: set_mask_pixel(x, y, value) {#set_mask_pixel_x_y_value_19}


```
 set_mask_pixel(x, y, value) 
```

Устанавливает непрозрачность указанного пикселя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| значение | bool | true, если указанный пиксель непрозрачный; в противном случае — false. |

### Method: subtract(image, settings) {#subtract_image_settings_20}


```
 subtract(image, settings) 
```

Получает результат выделения волшебной палочкой, применённого к предоставленному изображению, вычтенный из текущей маски.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение для волшебной палочки. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Настройки волшебной палочки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(mask) {#subtract_mask_21}


```
 subtract(mask) 
```

Получает вычитание предоставленной маски из текущей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Предоставленная маска |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(settings) {#subtract_settings_22}


```
 subtract(settings) 
```

Получает результат выделения волшебной палочкой, применённого к источнику текущей маски, вычтенный из маски.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Настройки волшебной палочки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(image, settings) {#union_image_settings_23}


```
 union(image, settings) 
```

Получает объединение текущей маски с результатом выделения волшебной палочкой, применённого к предоставленному изображению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение для волшебной палочки. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Настройки волшебной палочки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(mask) {#union_mask_24}


```
 union(mask) 
```

Получает объединение текущей маски с предоставленной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Предоставленная маска |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(settings) {#union_settings_25}


```
 union(settings) 
```

Получает объединение текущей маски с результатом выделения волшебной палочкой, применённого к источнику маски.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Настройки волшебной палочки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


