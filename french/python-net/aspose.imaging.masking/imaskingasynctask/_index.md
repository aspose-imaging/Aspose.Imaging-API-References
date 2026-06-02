---
title: "Classe IMaskingAsyncTask"
type: docs
weight: 60
url: /fr/python-net/aspose.imaging.masking/imaskingasynctask/
---

**Summary:** Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | Obtient une valeur indiquant si cette tâche est actuellement en cours d'exécution. |
| is_canceled | bool | r | Obtient une valeur indiquant si cette tâche a été annulée. |
| is_faulted | bool | r | Obtient une valeur indiquant si cette tâche a échoué. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | Interrompt cette tâche.<br/>            La tâche est terminée immédiatement, avec le risque de ne pas libérer les ressources internes non gérées. |
| cancel() | Annule cette tâche.<br/>            La tâche est terminée en toute sécurité par l'arrêt contrôlé de l'algorithme. |
| [get_error()](#get_error__1) | Renvoie une erreur de l'opération de masquage |
| [get_masking_result()](#get_masking_result__2) | Renvoie le résultat de l'opération de masquage |
| run_async() | Exécute cette tâche. |
| wait_on_done() | Attend que la tâche soit terminée. |


### Method: get_error() {#get_error__1}


```
 get_error() 
```

Renvoie une erreur de l'opération de masquage

**Returns**

| Type | Description |
| :- | :- |
| string | L'erreur de la tâche. |


### Method: get_masking_result() {#get_masking_result__2}


```
 get_masking_result() 
```

Renvoie le résultat de l'opération de masquage

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Le résultat de cette tâche. |


