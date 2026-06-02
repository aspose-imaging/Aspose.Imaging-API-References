---
title: "Класс ImageMasking"
type: docs
weight: 90
url: /ru/python-net/aspose.imaging.masking/imagemasking/
---

**Summary:** Provides image masking operations

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.ImageMasking

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageMasking(source_image)](#ImageMasking_source_image_1) | Инициализирует новый экземпляр класса [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply_mask(target_image, mask, masking_options)](#apply_mask_target_image_mask_masking_options_1) | Применяет маску к указанному исходному изображению. |
| [create_session(options)](#create_session_options_2) | Создаёт сеанс маскирования, который может выполнять операции декомпозиции переобучения. |
| [decompose(options)](#decompose_options_3) | Выполняет операцию декомпозиции, используя указанные параметры маскирования |
| [decompose_async(options)](#decompose_async_options_4) | Создаёт асинхронную задачу декомпозиции, используя указанные параметры маскирования. |
| [load_session(file_path)](#load_session_file_path_5) | Загрузить сеанс из указанного файла. |
| [load_session(stream)](#load_session_stream_6) | Загрузить сеанс из указанного потока. |
| [load_session_from_stream(stream)](#load_session_from_stream_stream_7) | Загрузить сеанс из указанного потока. |


### Constructor: ImageMasking(source_image) {#ImageMasking_source_image_1}


```
 ImageMasking(source_image) 
```

Инициализирует новый экземпляр класса [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Исходное изображение. |

### Method: apply_mask(target_image, mask, masking_options)  [static] {#apply_mask_target_image_mask_masking_options_1}


```
 apply_mask(target_image, mask, masking_options) 
```

Применяет маску к указанному исходному изображению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| target_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Целевое изображение. |
| mask | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение маски для применения. |
| masking_options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Параметры маскирования. |

### Method: create_session(options) {#create_session_options_2}


```
 create_session(options) 
```

Создаёт сеанс маскирования, который может выполнять операции декомпозиции переобучения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Параметры. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | сеанс маскирования, который может выполнять операции декомпозиции переобучения. |


### Method: decompose(options) {#decompose_options_3}


```
 decompose(options) 
```

Выполняет операцию декомпозиции, используя указанные параметры маскирования

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Параметры маскирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Результат операции маскирования в виде массива поставщиков сегментных изображений. |


### Method: decompose_async(options) {#decompose_async_options_4}


```
 decompose_async(options) 
```

Создаёт асинхронную задачу декомпозиции, используя указанные параметры маскирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Параметры маскирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Асинхронная задача декомпозиции |


### Method: load_session(file_path) {#load_session_file_path_5}


```
 load_session(file_path) 
```

Загрузить сеанс из указанного файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | сеанс маскирования, который может выполнять операции декомпозиции переобучения. |


### Method: load_session(stream) {#load_session_stream_6}


```
 load_session(stream) 
```

Загрузить сеанс из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | сеанс маскирования, который может выполнять операции декомпозиции переобучения. |


### Method: load_session_from_stream(stream) {#load_session_from_stream_stream_7}


```
 load_session_from_stream(stream) 
```

Загрузить сеанс из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | сеанс маскирования, который может выполнять операции декомпозиции переобучения. |


