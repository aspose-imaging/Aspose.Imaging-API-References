---
title: "Clase GifBlocksRegistry"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

**Summary:** Represents the gif blocks openers registry.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IGifBlockLoaderDescriptor[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | r | Obtiene los descriptores registrados. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Obtiene el primer descriptor de apertura compatible. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Obtiene el primer descriptor compatible por su nombre de tipo. |
| [load_block_by_first_supported_descriptor(stream, container_palette)](#load_block_by_first_supported_descriptor_stream_container_palette_3) | Carga el bloque gif usando el primer abridor encontrado adecuado para el _stream_ especificado. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registra el abridor. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Anula el registro del abridor. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Obtiene el primer descriptor de apertura compatible.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | El descriptor de apertura del bloque gif o null si no hay un descriptor de apertura compatible para dicho stream. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Obtiene el primer descriptor compatible por su nombre de tipo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| descriptor_type_name | string | El nombre del tipo de descriptor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | El primer descriptor de apertura encontrado o null si no se encuentra tal descriptor. |


### Method: load_block_by_first_supported_descriptor(stream, container_palette)  [static] {#load_block_by_first_supported_descriptor_stream_container_palette_3}


```
 load_block_by_first_supported_descriptor(stream, container_palette) 
```

Carga el bloque gif usando el primer abridor encontrado adecuado para el _stream_ especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta del contenedor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | El bloque gif cargado o null si no se encuentra ningún abridor. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registra el abridor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | El descriptor de apertura a registrar. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Anula el registro del abridor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | El descriptor de apertura a anular el registro. |

