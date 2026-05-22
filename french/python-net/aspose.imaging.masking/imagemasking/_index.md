---
title: "Classe ImageMasking"
type: docs
weight: 90
url: /fr/python-net/aspose.imaging.masking/imagemasking/
---

**Summary:** Provides image masking operations

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.ImageMasking

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageMasking(source_image)](#ImageMasking_source_image_1) | Initialise une nouvelle instance de la classe [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply_mask(target_image, mask, masking_options)](#apply_mask_target_image_mask_masking_options_1) | Applique le masque à l'image source spécifiée. |
| [create_session(options)](#create_session_options_2) | Crée la session de masquage qui peut effectuer des opérations de décomposition de réapprentissage. |
| [decompose(options)](#decompose_options_3) | Effectue l'opération de décomposition en utilisant les options de masquage spécifiées |
| [decompose_async(options)](#decompose_async_options_4) | Crée la tâche de décomposition asynchrone en utilisant les options de masquage spécifiées. |
| [load_session(file_path)](#load_session_file_path_5) | Charge la session depuis le fichier spécifié. |
| [load_session(stream)](#load_session_stream_6) | Charge la session depuis le flux spécifié. |
| [load_session_from_stream(stream)](#load_session_from_stream_stream_7) | Charge la session depuis le flux spécifié. |


### Constructor: ImageMasking(source_image) {#ImageMasking_source_image_1}


```
 ImageMasking(source_image) 
```

Initialise une nouvelle instance de la classe [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image source. |

### Method: apply_mask(target_image, mask, masking_options)  [static] {#apply_mask_target_image_mask_masking_options_1}


```
 apply_mask(target_image, mask, masking_options) 
```

Applique le masque à l'image source spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| target_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image cible. |
| mask | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image de masque à appliquer. |
| masking_options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Les options de masquage. |

### Method: create_session(options) {#create_session_options_2}


```
 create_session(options) 
```

Crée la session de masquage qui peut effectuer des opérations de décomposition de réapprentissage.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Les options. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la session de masquage qui peut effectuer des opérations de décomposition de réapprentissage. |


### Method: decompose(options) {#decompose_options_3}


```
 decompose(options) 
```

Effectue l'opération de décomposition en utilisant les options de masquage spécifiées

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Les options de masquage. |

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Résultat de l'opération de masquage sous forme de tableau de fournisseurs d'images segmentées. |


### Method: decompose_async(options) {#decompose_async_options_4}


```
 decompose_async(options) 
```

Crée la tâche de décomposition asynchrone en utilisant les options de masquage spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Les options de masquage. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | La tâche de décomposition asynchrone |


### Method: load_session(file_path) {#load_session_file_path_5}


```
 load_session(file_path) 
```

Charge la session depuis le fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la session de masquage qui peut effectuer des opérations de décomposition de réapprentissage. |


### Method: load_session(stream) {#load_session_stream_6}


```
 load_session(stream) 
```

Charge la session depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la session de masquage qui peut effectuer des opérations de décomposition de réapprentissage. |


### Method: load_session_from_stream(stream) {#load_session_from_stream_stream_7}


```
 load_session_from_stream(stream) 
```

Charge la session depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

**Returns**

| Type | Description |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la session de masquage qui peut effectuer des opérations de décomposition de réapprentissage. |


