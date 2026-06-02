---
title: "Classe IMaskingSession"
type: docs
weight: 80
url: /fr/python-net/aspose.imaging.masking/imaskingsession/
---

**Summary:** The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [decompose()](#decompose__1) | Effectue la première opération de décomposition grossière |
| [decompose_async()](#decompose_async__2) | Crée la tâche asynchrone qui peut effectuer la première opération de décomposition grossière |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_3) | Effectue l'opération de décomposition de réapprentissage |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_4) | Crée la tâche asynchrone qui peut effectuer l'opération de décomposition de réapprentissage |
| [save(file_path)](#save_file_path_5) | Enregistre l'état de la session dans le fichier spécifié. |
| [save(stream)](#save_stream_6) | Enregistrez l'état de la session dans le flux spécifié. |


### Method: decompose() {#decompose__1}


```
 decompose() 
```

Effectue la première opération de décomposition grossière

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Résultat de l'opération de masquage sous forme de tableau de fournisseurs d'images segmentées. |


### Method: decompose_async() {#decompose_async__2}


```
 decompose_async() 
```

Crée la tâche asynchrone qui peut effectuer la première opération de décomposition grossière

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | La tâche de décomposition asynchrone |


### Method: improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_3}


```
 improve_decomposition(masking_arguments) 
```

Effectue l'opération de décomposition de réapprentissage

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Les arguments de masquage. |

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Résultat de l'opération de masquage sous forme de tableau de fournisseurs d'images segmentées. |


### Method: improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_4}


```
 improve_decomposition_async(masking_arguments) 
```

Crée la tâche asynchrone qui peut effectuer l'opération de décomposition de réapprentissage

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Les arguments de masquage. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | La tâche de décomposition asynchrone |


### Method: save(file_path) {#save_file_path_5}


```
 save(file_path) 
```

Enregistre l'état de la session dans le fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Enregistrez l'état de la session dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

