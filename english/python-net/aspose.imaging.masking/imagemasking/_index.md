---
title: ImageMasking Class
type: docs
weight: 90
url: /python-net/aspose.imaging.masking/imagemasking/
---

Provides image masking operations

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.ImageMasking

**Aspose.Imaging Version:** 23.6

The ImageMasking type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [ImageMasking(source_image)](#ImageMasking_source_image_0) | Initializes a new instance of the [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/) class. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [load_session(stream)](#load_session_stream_1) | Load the session from the specified stream. |
| [load_session(file_path)](#load_session_file_path_2) | Load the session from the specified file. |
| [apply_mask(target_image, mask, masking_options)](#apply_mask_target_image_mask_masking_options_3) | Applies the mask to specified source image. |
| [decompose(options)](#decompose_options_4) | Performs the decompose operation using specified masking options |
| [decompose_async(options)](#decompose_async_options_5) | Creates the asynchronous decompose task using specified masking options. |
| [create_session(options)](#create_session_options_6) | Creates the masking session which can perform retraining decompose operations. |
| [load_session_from_stream(stream)](#load_session_from_stream_stream_7) | Load the session from the specified stream. |

### ImageMasking(source_image) {#ImageMasking_source_image_0}


```
 ImageMasking(source_image) 
```

Initializes a new instance of the [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The source image. |

### load_session(stream) {#load_session_stream_1}


```
 load_session(stream) 
```

Load the session from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession) | the masking session which can perform retraining decompose operations. |


### load_session(file_path) {#load_session_file_path_2}


```
 load_session(file_path) 
```

Load the session from the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession) | the masking session which can perform retraining decompose operations. |


### apply_mask(target_image, mask, masking_options)  [static] {#apply_mask_target_image_mask_masking_options_3}


```
 apply_mask(target_image, mask, masking_options) 
```

Applies the mask to specified source image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| target_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The target image. |
| mask | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The mask image to apply. |
| masking_options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | The masking options. |

### decompose(options) {#decompose_options_4}


```
 decompose(options) 
```

Performs the decompose operation using specified masking options

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | The masking options. |

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Result of masking operation as array of segment image providers. |


### decompose_async(options) {#decompose_async_options_5}


```
 decompose_async(options) 
```

Creates the asynchronous decompose task using specified masking options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | The masking options. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask) | The asynchronous decompose task |


### create_session(options) {#create_session_options_6}


```
 create_session(options) 
```

Creates the masking session which can perform retraining decompose operations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | The options. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession) | the masking session which can perform retraining decompose operations. |


### load_session_from_stream(stream) {#load_session_from_stream_stream_7}


```
 load_session_from_stream(stream) 
```

Load the session from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession) | the masking session which can perform retraining decompose operations. |


