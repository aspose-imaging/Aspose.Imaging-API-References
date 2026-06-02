---
title: "IMaskingSession 类"
type: docs
weight: 80
url: /zh/python-net/aspose.imaging.masking/imaskingsession/
---

**Summary:** The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [decompose()](#decompose__1) | 执行首次粗略分解操作 |
| [decompose_async()](#decompose_async__2) | 创建可执行首次粗略分解操作的异步任务 |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_3) | 执行重新训练分解操作 |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_4) | 创建可执行重新训练分解操作的异步任务 |
| [save(file_path)](#save_file_path_5) | 将会话状态保存到指定文件。 |
| [save(stream)](#save_stream_6) | 将会话状态保存到指定流。 |


### Method: decompose() {#decompose__1}


```
 decompose() 
```

执行首次粗略分解操作

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | 掩码操作的结果，以段图像提供程序数组形式。 |


### Method: decompose_async() {#decompose_async__2}


```
 decompose_async() 
```

创建可执行首次粗略分解操作的异步任务

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | 异步分解任务 |


### Method: improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_3}


```
 improve_decomposition(masking_arguments) 
```

执行重新训练分解操作

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | 掩码参数。 |

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | 掩码操作的结果，以段图像提供程序数组形式。 |


### Method: improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_4}


```
 improve_decomposition_async(masking_arguments) 
```

创建可执行重新训练分解操作的异步任务

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | 掩码参数。 |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | 异步分解任务 |


### Method: save(file_path) {#save_file_path_5}


```
 save(file_path) 
```

将会话状态保存到指定文件。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

将会话状态保存到指定流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |

