---
title: "Clase ImageMasking"
type: docs
weight: 90
url: /es/python-net/aspose.imaging.masking/imagemasking/
---

**Summary:** Provides image masking operations

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.ImageMasking

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ImageMasking(source_image)](#ImageMasking_source_image_1) | Inicializa una nueva instancia de la clase [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagematching/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [apply_mask(target_image, mask, masking_options)](#apply_mask_target_image_mask_masking_options_1) | Aplica la máscara a la imagen fuente especificada. |
| [create_session(options)](#create_session_options_2) | Crea la sesión de enmascarado que puede realizar operaciones de descomposición de reentrenamiento. |
| [decompose(options)](#decompose_options_3) | Realiza la operación de descomposición usando las opciones de enmascarado especificadas |
| [decompose_async(options)](#decompose_async_options_4) | Crea la tarea de descomposición asincrónica usando las opciones de enmascarado especificadas. |
| [load_session(file_path)](#load_session_file_path_5) | Carga la sesión desde el archivo especificado. |
| [load_session(stream)](#load_session_stream_6) | Carga la sesión desde el flujo especificado. |
| [load_session_from_stream(stream)](#load_session_from_stream_stream_7) | Carga la sesión desde el flujo especificado. |


### Constructor: ImageMasking(source_image) {#ImageMasking_source_image_1}


```
 ImageMasking(source_image) 
```

Inicializa una nueva instancia de la clase [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagematching/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen de origen. |

### Method: apply_mask(target_image, mask, masking_options)  [static] {#apply_mask_target_image_mask_masking_options_1}


```
 apply_mask(target_image, mask, masking_options) 
```

Aplica la máscara a la imagen fuente especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| target_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen objetivo. |
| mask | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen de máscara a aplicar. |
| masking_options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Las opciones de enmascarado. |

### Method: create_session(options) {#create_session_options_2}


```
 create_session(options) 
```

Crea la sesión de enmascarado que puede realizar operaciones de descomposición de reentrenamiento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Las opciones. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la sesión de enmascarado que puede realizar operaciones de descomposición de reentrenamiento. |


### Method: decompose(options) {#decompose_options_3}


```
 decompose(options) 
```

Realiza la operación de descomposición usando las opciones de enmascarado especificadas

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Las opciones de enmascarado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Resultado de la operación de enmascarado como una matriz de proveedores de imágenes de segmento. |


### Method: decompose_async(options) {#decompose_async_options_4}


```
 decompose_async(options) 
```

Crea la tarea de descomposición asincrónica usando las opciones de enmascarado especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | Las opciones de enmascarado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | La tarea de descomposición asincrónica |


### Method: load_session(file_path) {#load_session_file_path_5}


```
 load_session(file_path) 
```

Carga la sesión desde el archivo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la sesión de enmascarado que puede realizar operaciones de descomposición de reentrenamiento. |


### Method: load_session(stream) {#load_session_stream_6}


```
 load_session(stream) 
```

Carga la sesión desde el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la sesión de enmascarado que puede realizar operaciones de descomposición de reentrenamiento. |


### Method: load_session_from_stream(stream) {#load_session_from_stream_stream_7}


```
 load_session_from_stream(stream) 
```

Carga la sesión desde el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | la sesión de enmascarado que puede realizar operaciones de descomposición de reentrenamiento. |


