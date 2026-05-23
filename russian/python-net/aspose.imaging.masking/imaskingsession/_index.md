---
title: "IMaskingSession Класс"
type: docs
weight: 80
url: /ru/python-net/aspose.imaging.masking/imaskingsession/
---

**Summary:** The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [decompose()](#decompose__1) | Выполняет первую грубую операцию разложения |
| [decompose_async()](#decompose_async__2) | Создаёт асинхронную задачу, которая может выполнить первую грубую операцию разложения |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_3) | Выполняет операцию декомпозиции переобучения |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_4) | Создаёт асинхронную задачу, которая может выполнять операцию декомпозиции переобучения |
| [save(file_path)](#save_file_path_5) | Сохраняет состояние сеанса в указанный файл. |
| [save(stream)](#save_stream_6) | Сохранить состояние сеанса в указанный поток. |


### Method: decompose() {#decompose__1}


```
 decompose() 
```

Выполняет первую грубую операцию разложения

**Returns**

| Тип | Описание |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Результат операции маскирования в виде массива поставщиков сегментных изображений. |


### Method: decompose_async() {#decompose_async__2}


```
 decompose_async() 
```

Создаёт асинхронную задачу, которая может выполнить первую грубую операцию разложения

**Returns**

| Тип | Описание |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Асинхронная задача декомпозиции |


### Method: improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_3}


```
 improve_decomposition(masking_arguments) 
```

Выполняет операцию декомпозиции переобучения

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Аргументы маскирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Результат операции маскирования в виде массива поставщиков сегментных изображений. |


### Method: improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_4}


```
 improve_decomposition_async(masking_arguments) 
```

Создаёт асинхронную задачу, которая может выполнять операцию декомпозиции переобучения

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Аргументы маскирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | Асинхронная задача декомпозиции |


### Method: save(file_path) {#save_file_path_5}


```
 save(file_path) 
```

Сохраняет состояние сеанса в указанный файл.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Сохранить состояние сеанса в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

