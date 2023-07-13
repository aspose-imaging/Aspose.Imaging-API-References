---
title: IMaskingSession Class
type: docs
weight: 80
url: /python-net/aspose.imaging.masking/imaskingsession/
---

The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

**Aspose.Imaging Version:** 23.6

The IMaskingSession type exposes the following members:
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_0) | Save the session state to the specified stream. |
| [save(file_path)](#save_file_path_1) | Saves the session state to the specified file. |
| [decompose()](#decompose__2) | Performs first rough decompose operation |
| [decompose_async()](#decompose_async__3) | Creates the asynchronous task which can perform first rough decompose operation |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_4) | Performs retraining decompose operation |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_5) | Creates the asynchronous task which can perform retraining decompose operation |

### save(stream) {#save_stream_0}


```
 save(stream) 
```

Save the session state to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

### save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Saves the session state to the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |

### decompose() {#decompose__2}


```
 decompose() 
```

Performs first rough decompose operation

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Result of masking operation as array of segment image providers. |


### decompose_async() {#decompose_async__3}


```
 decompose_async() 
```

Creates the asynchronous task which can perform first rough decompose operation

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask) | The asynchronous decompose task |


### improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_4}


```
 improve_decomposition(masking_arguments) 
```

Performs retraining decompose operation

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | The masking arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Result of masking operation as array of segment image providers. |


### improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_5}


```
 improve_decomposition_async(masking_arguments) 
```

Creates the asynchronous task which can perform retraining decompose operation

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | The masking arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask) | The asynchronous decompose task |


