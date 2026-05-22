---
title: "Classe IAsyncTask"
type: docs
weight: 30
url: /fr/python-net/aspose.imaging.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | Obtient une valeur indiquant si cette tâche est actuellement en cours d'exécution. |
| is_canceled | bool | r | Obtient une valeur indiquant si cette tâche a été annulée. |
| is_faulted | bool | r | Obtient une valeur indiquant si cette tâche a échoué. |
| result | System.Object | r | Obtient le résultat de cette tâche. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | Interrompt cette tâche.<br/>            La tâche est terminée immédiatement, avec le risque de ne pas libérer les ressources internes non gérées. |
| cancel() | Annule cette tâche.<br/>            La tâche est terminée en toute sécurité par l'arrêt contrôlé de l'algorithme. |
| run_async() | Exécute cette tâche. |
| wait_on_done() | Attend que la tâche soit terminée. |


