---
title: IMaskingSession Class
type: docs
weight: 80
url: /python-net/aspose.imaging.masking/imaskingsession/
---

**Summary:** The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [decompose()](#decompose__1) | Performs first rough decompose operation |
| [decompose_async()](#decompose_async__2) | Creates the asynchronous task which can perform first rough decompose operation |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_3) | Performs retraining decompose operation |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_4) | Creates the asynchronous task which can perform retraining decompose operation |
| [save(file_path)](#save_file_path_5) | Saves the session state to the specified file. |
| [save(stream)](#save_stream_6) | Save the session state to the specified stream. |


### Method: decompose() {#decompose__1}


```
 decompose() 
```

Performs first rough decompose operation

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Result of masking operation as array of segment image providers. |


### Method: decompose_async() {#decompose_async__2}


```
 decompose_async() 
```

Creates the asynchronous task which can perform first rough decompose operation

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | The asynchronous decompose task |


### Method: improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_3}


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


### Method: improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_4}


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
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | The asynchronous decompose task |


### Method: save(file_path) {#save_file_path_5}


```
 save(file_path) 
```

Saves the session state to the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Save the session state to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

