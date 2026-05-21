---
title: "AsyncTask"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La classe fabrique statique pour créer les tâches asynchrones"
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.asynctask/asynctask/
---
**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

La classe fabrique statique pour créer les tâches asynchrones
## Méthodes

| Méthode | Description |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.imaging.asynctask.AsyncTaskAction-) | Crée la tâche asynchrone sans aucun résultat. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.imaging.asynctask.AsyncTaskFunc-) | Crée la tâche asynchrone avec un résultat de type générique. |
### create(AsyncTaskAction taskAction) {#create-com.aspose.imaging.asynctask.AsyncTaskAction-}
```
public static IAsyncTask create(AsyncTaskAction taskAction)
```


Crée la tâche asynchrone sans aucun résultat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.imaging.asynctask/asynctaskaction) | L'action de la tâche. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.imaging.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Crée la tâche asynchrone avec un résultat de type générique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.imaging.asynctask/asynctaskfunc) | La fonction de la tâche. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
