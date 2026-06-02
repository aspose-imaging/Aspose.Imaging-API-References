---
title: "AsyncTask"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La clase estática de fábrica para crear las tareas asíncronas"
type: docs
weight: 10
url: /es/java/com.aspose.imaging.asynctask/asynctask/
---
**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

La clase estática de fábrica para crear las tareas asíncronas
## Métodos

| Método | Descripción |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.imaging.asynctask.AsyncTaskAction-) | Crea la tarea asíncrona sin ningún resultado. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.imaging.asynctask.AsyncTaskFunc-) | Crea la tarea asíncrona con un resultado de tipo genérico. |
### create(AsyncTaskAction taskAction) {#create-com.aspose.imaging.asynctask.AsyncTaskAction-}
```
public static IAsyncTask create(AsyncTaskAction taskAction)
```


Crea la tarea asíncrona sin ningún resultado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.imaging.asynctask/asynctaskaction) | La acción de la tarea. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.imaging.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Crea la tarea asíncrona con un resultado de tipo genérico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.imaging.asynctask/asynctaskfunc) | La función de la tarea. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
