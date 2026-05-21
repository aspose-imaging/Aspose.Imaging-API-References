---
title: "IMatchingAsyncTask"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет асинхронную задачу маскирования."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.masking/imaskingasynctask/
---
**All Implemented Interfaces:**
[com.aspose.imaging.asynctask.IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask)
```
public interface IMaskingAsyncTask extends IAsyncTask
```

Представляет асинхронную задачу маскирования.
## Методы

| Метод | Описание |
| --- | --- |
| [getMaskingResult()](#getMaskingResult--) | Возвращает результат операции маскирования |
| [getErrorString()](#getErrorString--) | Возвращает ошибку операции маскирования |
### getMaskingResult() {#getMaskingResult--}
```
public abstract MaskingResult getMaskingResult()
```


Возвращает результат операции маскирования

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - The result of this task.
### getErrorString() {#getErrorString--}
```
public abstract String getErrorString()
```


Возвращает ошибку операции маскирования

**Returns:**
java.lang.String — Ошибка задачи.
