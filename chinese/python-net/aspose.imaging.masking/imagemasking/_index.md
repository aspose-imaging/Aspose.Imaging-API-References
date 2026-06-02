---
title: "ImageMasking 类"
type: docs
weight: 90
url: /zh/python-net/aspose.imaging.masking/imagemasking/
---

**Summary:** Provides image masking operations

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.ImageMasking

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ImageMasking(source_image)](#ImageMasking_source_image_1) | 初始化 [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/) 类的新实例。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [apply_mask(target_image, mask, masking_options)](#apply_mask_target_image_mask_masking_options_1) | 将掩码应用于指定的源图像。 |
| [create_session(options)](#create_session_options_2) | 创建可执行重新训练分解操作的掩码会话。 |
| [decompose(options)](#decompose_options_3) | 使用指定的掩码选项执行分解操作 |
| [decompose_async(options)](#decompose_async_options_4) | 使用指定的掩码选项创建异步分解任务。 |
| [load_session(file_path)](#load_session_file_path_5) | 从指定文件加载会话。 |
| [load_session(stream)](#load_session_stream_6) | 从指定流加载会话。 |
| [load_session_from_stream(stream)](#load_session_from_stream_stream_7) | 从指定流加载会话。 |


### Constructor: ImageMasking(source_image) {#ImageMasking_source_image_1}


```
 ImageMasking(source_image) 
```

初始化 [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 源图像。 |

### Method: apply_mask(target_image, mask, masking_options)  [static] {#apply_mask_target_image_mask_masking_options_1}


```
 apply_mask(target_image, mask, masking_options) 
```

将掩码应用于指定的源图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| target_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 目标图像。 |
| mask | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 要应用的掩码图像。 |
| masking_options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | 掩码选项。 |

### Method: create_session(options) {#create_session_options_2}


```
 create_session(options) 
```

创建可执行重新训练分解操作的掩码会话。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | 选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | 可执行重新训练分解操作的掩码会话。 |


### Method: decompose(options) {#decompose_options_3}


```
 decompose(options) 
```

使用指定的掩码选项执行分解操作

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | 掩码选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | 掩码操作的结果，以段图像提供程序数组形式。 |


### Method: decompose_async(options) {#decompose_async_options_4}


```
 decompose_async(options) 
```

使用指定的掩码选项创建异步分解任务。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | 掩码选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | 异步分解任务 |


### Method: load_session(file_path) {#load_session_file_path_5}


```
 load_session(file_path) 
```

从指定文件加载会话。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | 可执行重新训练分解操作的掩码会话。 |


### Method: load_session(stream) {#load_session_stream_6}


```
 load_session(stream) 
```

从指定流加载会话。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | 可执行重新训练分解操作的掩码会话。 |


### Method: load_session_from_stream(stream) {#load_session_from_stream_stream_7}


```
 load_session_from_stream(stream) 
```

从指定流加载会话。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | 可执行重新训练分解操作的掩码会话。 |


