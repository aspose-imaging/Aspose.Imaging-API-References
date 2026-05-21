---
title: "IAsyncTask"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La tâche asynchrone."
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.asynctask/iasynctask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

La tâche asynchrone.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient le gestionnaire d'événement de progression de la tâche asynchrone. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Définit le gestionnaire d'événement de progression de la tâche asynchrone. |
| [isBusy()](#isBusy--) | Obtient une valeur indiquant si cette tâche est actuellement en cours d'exécution. |
| [isCanceled()](#isCanceled--) | Obtient une valeur indiquant si cette tâche a été annulée. |
| [isFaulted()](#isFaulted--) | Obtient une valeur indiquant si cette tâche a échoué. |
| [getError()](#getError--) | Obtient l'erreur de la tâche qui est disponible après que la tâche soit terminée. |
| [getResult()](#getResult--) | Obtient le résultat de cette tâche. |
| [runAsync()](#runAsync--) | Exécute cette tâche. |
| [runAsync(int priority)](#runAsync-int-) | Exécute cette tâche. |
| [cancel()](#cancel--) | Annule cette tâche. |
| [abort()](#abort--) | Interrompt cette tâche. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-) | Définit le délégué de rappel de fin. |
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Obtient le gestionnaire d'événement de progression de la tâche asynchrone.

Valeur : le gestionnaire d'événement de progression de la tâche asynchrone.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler of the asynchronous task.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Définit le gestionnaire d'événement de progression de la tâche asynchrone.

Valeur : le gestionnaire d'événement de progression de la tâche asynchrone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | le gestionnaire d'événement de progression de la tâche asynchrone. |

### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Obtient une valeur indiquant si cette tâche est actuellement en cours d'exécution.

Valeur : `true` si cette tâche est actuellement en cours d'exécution ; sinon, `false`.

**Returns:**
booléen - une valeur indiquant si cette tâche est actuellement en cours d'exécution.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Obtient une valeur indiquant si cette tâche a été annulée.

Valeur : `true` si cette tâche a été annulée ; sinon, `false`.

**Returns:**
booléen - une valeur indiquant si cette tâche a été annulée.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Obtient une valeur indiquant si cette tâche a échoué.

Valeur : `true` si cette tâche a échoué ; sinon, `false`.

**Returns:**
booléen - une valeur indiquant si cette tâche a échoué.
### getError() {#getError--}
```
public abstract Throwable getError()
```


Obtient l'erreur de la tâche qui est disponible après que la tâche soit terminée.

Valeur : l’erreur de la tâche.

**Returns:**
java.lang.Throwable - l’erreur de la tâche disponible après l’achèvement de la tâche.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Obtient le résultat de cette tâche.

Valeur : le résultat de cette tâche.

**Returns:**
java.lang.Object - le résultat de cette tâche.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Exécute cette tâche.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Exécute cette tâche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| priorité | int | La priorité du thread. |

### cancel() {#cancel--}
```
public abstract void cancel()
```


Annule cette tâche. La tâche est terminée en toute sécurité grâce à l’arrêt contrôlé de l’algorithme.

### abort() {#abort--}
```
public abstract void abort()
```


Interrompt cette tâche. La tâche est terminée immédiatement, avec le risque de ne pas libérer les ressources internes non gérées.

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Définit le délégué de rappel de fin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.imaging.asynctask/completecallback) | Le rappel complet. |

