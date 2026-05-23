---
title: "Класс ImageAttributes"
type: docs
weight: 5660
url: /ru/python-net/aspose.imaging/imageattributes/
---

**Summary:** An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageAttributes

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Инициализирует новый экземпляр класса [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear_brush_remap_table() | Очищает таблицу переопределения цветов кисти этого объекта [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
| clear_color_key() | Очищает ключ цвета (диапазон прозрачности) для категории по умолчанию. |
| [clear_color_key(type)](#clear_color_key_type_1) | Очищает ключ цвета (диапазон прозрачности) для указанной категории. |
| clear_color_matrix() | Очищает матрицу коррекции цвета для категории по умолчанию. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Очищает матрицу коррекции цвета для указанной категории. |
| clear_gamma() | Отключает гамма‑коррекцию для категории по умолчанию. |
| [clear_gamma(type)](#clear_gamma_type_3) | Отключает гамма‑коррекцию для указанной категории. |
| clear_no_op() | Очищает настройку NoOp для категории по умолчанию. |
| [clear_no_op(type)](#clear_no_op_type_4) | Очищает настройку NoOp для указанной категории. |
| clear_output_channel() | Очищает настройку выходного канала CMYK (циан‑пурпур‑желтый‑чёрный) для категории по умолчанию. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Очищает настройку (циан‑пурпур‑желтый‑чёрный) выходного канала для указанной категории. |
| clear_output_channel_color_profile() | Очищает настройку цветового профиля выходного канала для категории по умолчанию. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Очищает настройку цветового профиля выходного канала для указанной категории. |
| clear_remap_table() | Очищает таблицу переопределения цветов для категории по умолчанию. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Очищает таблицу переопределения цветов для указанной категории. |
| clear_threshold() | Очищает значение порога для категории по умолчанию. |
| [clear_threshold(type)](#clear_threshold_type_8) | Очищает значение порога для указанной категории. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Устанавливает таблицу перекраски цветов для категории кисти. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Устанавливает цветовой ключ для категории по умолчанию. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для категории по умолчанию. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для категории по умолчанию. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для указанной категории. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Устанавливает матрицу коррекции цвета для категории по умолчанию. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Устанавливает матрицу коррекции цвета для категории по умолчанию. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Устанавливает матрицу коррекции цвета для указанной категории. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Устанавливает значение гаммы для категории по умолчанию. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Устанавливает значение гаммы для указанной категории. |
| set_no_op() | Отключает коррекцию цвета для категории по умолчанию. |
| [set_no_op(type)](#set_no_op_type_20) | Отключает коррекцию цвета для указанной категории. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Устанавливает канал вывода CMYK (циан‑пурпур‑желтый‑черный) для категории по умолчанию. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Устанавливает канал вывода CMYK (циан‑пурпур‑желтый‑черный) для указанной категории. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Устанавливает файл цветового профиля канала вывода для категории по умолчанию. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Устанавливает файл цветового профиля канала вывода для указанной категории. |
| [set_remap_table(map)](#set_remap_table_map_25) | Устанавливает таблицу перекраски цветов для категории по умолчанию. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Устанавливает таблицу перекраски цветов для указанной категории. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Устанавливает порог (диапазон прозрачности) для категории по умолчанию. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Устанавливает порог (диапазон прозрачности) для указанной категории. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Устанавливает режим обтекания, который используется для определения того, как размещать текстуру по форме или на её границах. Текстура размещается по форме, заполняя её, когда текстура меньше формы, которую она заполняет. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Устанавливает режим обтекания и цвет, используемые для определения того, как размещать текстуру по форме или на её границах. Текстура размещается по форме, заполняя её, когда текстура меньше формы, которую она заполняет. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Устанавливает режим обтекания и цвет, используемые для определения того, как размещать текстуру по форме или на её границах. Текстура размещается по форме, заполняя её, когда текстура меньше формы, которую она заполняет. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Инициализирует новый экземпляр класса [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/).

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Очищает ключ цвета (диапазон прозрачности) для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой очищается цветовой ключ. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Очищает матрицу коррекции цвета для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой очищается матрица коррекции цвета. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Отключает гамма‑коррекцию для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой отключена коррекция гаммы. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Очищает настройку NoOp для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой параметр NoOp сбрасывается. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Очищает настройку (циан‑пурпур‑желтый‑чёрный) выходного канала для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой настройка выходного канала сбрасывается. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Очищает настройку цветового профиля выходного канала для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой настройка профиля выходного канала сбрасывается. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Очищает таблицу переопределения цветов для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой таблица переотображения сбрасывается. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Очищает значение порога для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой пороговое значение сбрасывается. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Устанавливает таблицу перекраски цветов для категории кисти.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Массив объектов [ColorMap](/imaging/python-net/aspose.imaging/colormap/). |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Устанавливает цветовой ключ для категории по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | Низкое значение цветового ключа. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | Высокое значение цветового ключа. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | Низкое значение цветового ключа. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | Высокое значение цветового ключа. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой задаётся цветовой ключ. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для категории по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Матрица коррекции цвета. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Матрица коррекции оттенков серого. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для категории по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Матрица коррекции цвета. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Матрица коррекции оттенков серого. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Элемент [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/), который указывает тип изображения и цвета, на которые будут влиять матрицы коррекции цвета и оттенков серого. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Матрица коррекции цвета. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Матрица коррекции оттенков серого. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Элемент [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/), который указывает тип изображения и цвета, на которые будут влиять матрицы коррекции цвета и оттенков серого. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой задаются матрицы коррекции цвета и оттенков серого. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Устанавливает матрицу коррекции цвета для категории по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Матрица коррекции цвета. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Устанавливает матрицу коррекции цвета для категории по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Матрица коррекции цвета. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Элемент [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/), который указывает тип изображения и цвета, на которые будет влиять матрица коррекции цвета. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Устанавливает матрицу коррекции цвета для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Матрица коррекции цвета. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Элемент [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/), который указывает тип изображения и цвета, на которые будет влиять матрица коррекции цвета. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой задаётся матрица коррекции цвета. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Устанавливает значение гаммы для категории по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| гамма | float | Значение гамма‑коррекции. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Устанавливает значение гаммы для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| гамма | float | Значение гамма‑коррекции. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент перечисления [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой задаётся значение гаммы. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Отключает коррекцию цвета для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой отключается коррекция цвета. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Устанавливает канал вывода CMYK (циан‑пурпур‑желтый‑черный) для категории по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Элемент [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/), который указывает выходной канал. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Устанавливает канал вывода CMYK (циан‑пурпур‑желтый‑черный) для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Элемент [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/), который указывает выходной канал. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой задаётся выходной канал. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Устанавливает файл цветового профиля канала вывода для категории по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_profile_filename | string | Путь к файлу цветового профиля. Если файл цветового профиля находится в каталоге %SystemRoot%\System32\Spool\Drivers\Color, этот параметр может быть именем файла. В противном случае параметр должен содержать полностью квалифицированный путь. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Устанавливает файл цветового профиля канала вывода для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_profile_filename | string | Путь к файлу цветового профиля. Если файл цветового профиля находится в каталоге %SystemRoot%\System32\Spool\Drivers\Color, этот параметр может быть именем файла. В противном случае параметр должен содержать полностью квалифицированный путь. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой задаётся файл цветового профиля выходного канала. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Устанавливает таблицу перекраски цветов для категории по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Массив пар цветов типа [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Каждая пара цветов содержит существующий цвет (первое значение) и цвет, к которому он будет преобразован (второе значение). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Устанавливает таблицу перекраски цветов для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Массив пар цветов типа [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Каждая пара цветов содержит существующий цвет (первое значение) и цвет, к которому он будет преобразован (второе значение). |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), который указывает категорию, для которой задаётся таблица переотображения цветов. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Устанавливает порог (диапазон прозрачности) для категории по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| порог | float | Вещественное число, указывающее значение порога. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Устанавливает порог (диапазон прозрачности) для указанной категории.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| порог | float | Значение порога от 0,0 до 1,0, используемое в качестве точки разрыва для сортировки цветов, которые будут сопоставлены либо с максимальным, либо с минимальным значением. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Элемент [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), указывающий категорию, для которой установлен цветовой порог. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Устанавливает режим обтекания, который используется для определения того, как размещать текстуру по форме или на её границах. Текстура размещается по форме, заполняя её, когда текстура меньше формы, которую она заполняет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Элемент [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), определяющий, как повторяющиеся копии изображения используются для заполнения области. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Устанавливает режим обтекания и цвет, используемые для определения того, как размещать текстуру по форме или на её границах. Текстура размещается по форме, заполняя её, когда текстура меньше формы, которую она заполняет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Элемент [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), определяющий, как повторяющиеся копии изображения используются для заполнения области. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Объект [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/), указывающий цвет пикселей за пределами отрисованного изображения. Этот цвет виден, если параметр mode установлен в [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) и прямоугольник источника, переданный в DrawImage, больше самого изображения. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Устанавливает режим обтекания и цвет, используемые для определения того, как размещать текстуру по форме или на её границах. Текстура размещается по форме, заполняя её, когда текстура меньше формы, которую она заполняет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Элемент [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), определяющий, как повторяющиеся копии изображения используются для заполнения области. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Объект цвета, указывающий цвет пикселей за пределами отрисованного изображения. Этот цвет виден, если параметр mode установлен в [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) и прямоугольник источника, переданный в DrawImage, больше самого изображения. |
| зажим | bool | Этот параметр не оказывает влияния. Установите его в false. |

