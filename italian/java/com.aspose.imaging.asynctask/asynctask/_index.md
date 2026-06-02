---
title: "AsyncTask"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La classe factory statica per creare i task asincroni"
type: docs
weight: 10
url: /it/java/com.aspose.imaging.asynctask/asynctask/
---
**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

La classe factory statica per creare i task asincroni
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.imaging.asynctask.AsyncTaskAction-) | Crea l'attività asincrona senza alcun risultato. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.imaging.asynctask.AsyncTaskFunc-) | Crea l'attività asincrona con risultato di tipo generico. |
### create(AsyncTaskAction taskAction) {#create-com.aspose.imaging.asynctask.AsyncTaskAction-}
```
public static IAsyncTask create(AsyncTaskAction taskAction)
```


Crea l'attività asincrona senza alcun risultato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.imaging.asynctask/asynctaskaction) | L'azione dell'attività. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.imaging.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Crea l'attività asincrona con risultato di tipo generico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.imaging.asynctask/asynctaskfunc) | La funzione dell'attività. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
