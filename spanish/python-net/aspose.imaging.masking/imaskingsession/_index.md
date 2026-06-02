---
title: "Clase IMaskingSession"
type: docs
weight: 80
url: /es/python-net/aspose.imaging.masking/imaskingsession/
---

**Summary:** The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [decompose()](#decompose__1) | Realiza la primera operación de descomposición aproximada |
| [decompose_async()](#decompose_async__2) | Crea la tarea asíncrona que puede realizar la primera operación de descomposición aproximada |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_3) | Realiza la operación de descomposición de reentrenamiento |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_4) | Crea la tarea asincrónica que puede realizar la operación de descomposición de reentrenamiento |
| [save(file_path)](#save_file_path_5) | Guarda el estado de la sesión en el archivo especificado. |
| [save(stream)](#save_stream_6) | Guarda el estado de la sesión en el flujo especificado. |


### Method: decompose() {#decompose__1}


```
 decompose() 
```

Realiza la primera operación de descomposición aproximada

**Returns**

| Tipo | Descripción |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Resultado de la operación de enmascarado como una matriz de proveedores de imágenes de segmento. |


### Method: decompose_async() {#decompose_async__2}


```
 decompose_async() 
```

Crea la tarea asíncrona que puede realizar la primera operación de descomposición aproximada

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | La tarea de descomposición asincrónica |


### Method: improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_3}


```
 improve_decomposition(masking_arguments) 
```

Realiza la operación de descomposición de reentrenamiento

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Los argumentos de enmascarado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | Resultado de la operación de enmascarado como una matriz de proveedores de imágenes de segmento. |


### Method: improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_4}


```
 improve_decomposition_async(masking_arguments) 
```

Crea la tarea asincrónica que puede realizar la operación de descomposición de reentrenamiento

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | Los argumentos de enmascarado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | La tarea de descomposición asincrónica |


### Method: save(file_path) {#save_file_path_5}


```
 save(file_path) 
```

Guarda el estado de la sesión en el archivo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Guarda el estado de la sesión en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |

