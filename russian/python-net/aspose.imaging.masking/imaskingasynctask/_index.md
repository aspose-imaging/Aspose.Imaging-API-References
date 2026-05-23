---
title: "Класс IMatchingAsyncTask"
type: docs
weight: 60
url: /ru/python-net/aspose.imaging.masking/imaskingasynctask/
---

**Summary:** Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | Возвращает значение, указывающее, выполняется ли эта задача в данный момент. |
| is_canceled | bool | r | Возвращает значение, указывающее, была ли эта задача отменена. |
| is_faulted | bool | r | Возвращает значение, указывающее, произошла ли ошибка в этой задаче. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | Прерывает эту задачу.<br/>            Задача завершается немедленно, с риском не освобождения внутренних неуправляемых ресурсов. |
| cancel() | Отменяет эту задачу.<br/>            Задача завершается безопасно за счёт контролируемой остановки алгоритма. |
| [get_error()](#get_error__1) | Возвращает ошибку операции маскирования |
| [get_masking_result()](#get_masking_result__2) | Возвращает результат операции маскирования |
| run_async() | Запускает эту задачу. |
| wait_on_done() | Ожидает, пока задача не будет завершена. |


### Method: get_error() {#get_error__1}


```
 get_error() 
```

Возвращает ошибку операции маскирования

**Returns**

| Тип | Описание |
| :- | :- |
| string | Ошибка задачи. |


### Method: get_masking_result() {#get_masking_result__2}


```
 get_masking_result() 
```

Возвращает результат операции маскирования

**Returns**

| Тип | Описание |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Результат этой задачи. |


