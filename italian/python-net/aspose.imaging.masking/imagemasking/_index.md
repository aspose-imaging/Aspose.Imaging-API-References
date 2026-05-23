---
title: "ImageMasking Classe"
type: docs
weight: 90
url: /it/python-net/aspose.imaging.masking/imagemasking/
---

**Summary:** Provides image masking operations

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.ImageMasking

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [ImageMasking(source_image)](#ImageMasking_source_image_1) | Inizializza una nuova istanza della classe [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagematching/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [apply_mask(target_image, mask, masking_options)](#apply_mask_target_image_mask_masking_options_1) | Applica la maschera all'immagine sorgente specificata. |
| [create_session(options)](#create_session_options_2) | Crea la sessione di mascheramento che può eseguire operazioni di decomposizione di riaddestramento. |
| [decompose(options)](#decompose_options_3) | Esegue l'operazione di decomposizione utilizzando le opzioni di mascheramento specificate |
| [decompose_async(options)](#decompose_async_options_4) | Crea l'attività asincrona di decomposizione utilizzando le opzioni di mascheramento specificate. |
| [load_session(file_path)](#load_session_file_path_5) | Carica la sessione dal file specificato. |
| [load_session(stream)](#load_session_stream_6) | Carica la sessione dallo stream specificato. |
| [load_session_from_stream(stream)](#load_session_from_stream_stream_7) | Carica la sessione dallo stream specificato. |


### Constructor: ImageMasking(source_image) {#ImageMasking_source_image_1}


```
 ImageMasking(source_image) 
```

Inizializza una nuova istanza della classe [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagematching/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine di origine. |

### Method: apply_mask(target_image, mask, masking_options)  [static] {#apply_mask_target_image_mask_masking_options_1}


```
 apply_mask(target_image, mask, masking_options) 
```

Applica la maschera all'immagine sorgente specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| target_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine di destinazione. |
| mask | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine maschera da applicare. |
| masking_options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Le opzioni di mascheramento. |

### Method: create_session(options) {#create_session_options_2}


```
 create_session(options) 
```

Crea la sessione di mascheramento che può eseguire operazioni di decomposizione di riaddestramento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Le opzioni. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la sessione di mascheramento che può eseguire operazioni di decomposizione di riaddestramento. |


### Method: decompose(options) {#decompose_options_3}


```
 decompose(options) 
```

Esegue l'operazione di decomposizione utilizzando le opzioni di mascheramento specificate

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Le opzioni di mascheramento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Risultato dell'operazione di mascheramento come array di provider di immagini segmentate. |


### Method: decompose_async(options) {#decompose_async_options_4}


```
 decompose_async(options) 
```

Crea l'attività asincrona di decomposizione utilizzando le opzioni di mascheramento specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Le opzioni di mascheramento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | L'attività asincrona di decomposizione |


### Method: load_session(file_path) {#load_session_file_path_5}


```
 load_session(file_path) 
```

Carica la sessione dal file specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la sessione di mascheramento che può eseguire operazioni di decomposizione di riaddestramento. |


### Method: load_session(stream) {#load_session_stream_6}


```
 load_session(stream) 
```

Carica la sessione dallo stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la sessione di mascheramento che può eseguire operazioni di decomposizione di riaddestramento. |


### Method: load_session_from_stream(stream) {#load_session_from_stream_stream_7}


```
 load_session_from_stream(stream) 
```

Carica la sessione dallo stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la sessione di mascheramento che può eseguire operazioni di decomposizione di riaddestramento. |


