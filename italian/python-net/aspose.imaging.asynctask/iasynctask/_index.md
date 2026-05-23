---
title: "Classe IAsyncTask"
type: docs
weight: 30
url: /it/python-net/aspose.imaging.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| is_busy | bool | r | Restituisce un valore che indica se questa attività è attualmente in esecuzione. |
| is_canceled | bool | r | Restituisce un valore che indica se questa attività è stata annullata. |
| is_faulted | bool | r | Restituisce un valore che indica se questa attività ha generato un errore. |
| result | System.Object | r | Restituisce il risultato di questa attività. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| abort() | Interrompe questa attività.<br/>            L'attività viene completata immediatamente, con il rischio di non liberare le risorse non gestite interne. |
| cancel() | Annulla questa attività.<br/>            L'attività viene completata in modo sicuro mediante l'arresto controllato dell'algoritmo. |
| run_async() | Esegue questa attività. |
| wait_on_done() | Attende fino al completamento dell'attività. |


