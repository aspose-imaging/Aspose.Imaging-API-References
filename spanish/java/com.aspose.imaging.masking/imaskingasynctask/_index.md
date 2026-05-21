---
title: "IMaskingAsyncTask"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa la tarea asincrónica de enmascarado."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.masking/imaskingasynctask/
---
**All Implemented Interfaces:**
[com.aspose.imaging.asynctask.IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask)
```
public interface IMaskingAsyncTask extends IAsyncTask
```

Representa la tarea asincrónica de enmascarado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getMaskingResult()](#getMaskingResult--) | Devuelve el resultado de la operación de enmascarado |
| [getErrorString()](#getErrorString--) | Devuelve un error de la operación de enmascarado |
### getMaskingResult() {#getMaskingResult--}
```
public abstract MaskingResult getMaskingResult()
```


Devuelve el resultado de la operación de enmascarado

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - The result of this task.
### getErrorString() {#getErrorString--}
```
public abstract String getErrorString()
```


Devuelve un error de la operación de enmascarado

**Returns:**
java.lang.String - El error de la tarea.
