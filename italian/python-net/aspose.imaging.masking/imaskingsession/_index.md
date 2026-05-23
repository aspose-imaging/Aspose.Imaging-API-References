---
title: "Classe IMaskingSession"
type: docs
weight: 80
url: /it/python-net/aspose.imaging.masking/imaskingsession/
---

**Summary:** The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [decompose()](#decompose__1) | Esegue la prima operazione di decomposizione grezza |
| [decompose_async()](#decompose_async__2) | Crea l'attività asincrona che può eseguire la prima operazione di decomposizione grezza |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_3) | Esegue l'operazione di decomposizione di riaddestramento |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_4) | Crea l'attività asincrona che può eseguire l'operazione di decomposizione di riaddestramento |
| [save(file_path)](#save_file_path_5) | Salva lo stato della sessione nel file specificato. |
| [save(stream)](#save_stream_6) | Salva lo stato della sessione nello stream specificato. |


### Method: decompose() {#decompose__1}


```
 decompose() 
```

Esegue la prima operazione di decomposizione grezza

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Risultato dell'operazione di mascheramento come array di provider di immagini segmentate. |


### Method: decompose_async() {#decompose_async__2}


```
 decompose_async() 
```

Crea l'attività asincrona che può eseguire la prima operazione di decomposizione grezza

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | L'attività asincrona di decomposizione |


### Method: improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_3}


```
 improve_decomposition(masking_arguments) 
```

Esegue l'operazione di decomposizione di riaddestramento

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Gli argomenti del mascheramento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Risultato dell'operazione di mascheramento come array di provider di immagini segmentate. |


### Method: improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_4}


```
 improve_decomposition_async(masking_arguments) 
```

Crea l'attività asincrona che può eseguire l'operazione di decomposizione di riaddestramento

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Gli argomenti del mascheramento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | L'attività asincrona di decomposizione |


### Method: save(file_path) {#save_file_path_5}


```
 save(file_path) 
```

Salva lo stato della sessione nel file specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Salva lo stato della sessione nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

