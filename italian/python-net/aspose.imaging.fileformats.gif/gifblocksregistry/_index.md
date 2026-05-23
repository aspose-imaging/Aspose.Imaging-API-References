---
title: "GifBlocksRegistry Classe"
type: docs
weight: 30
url: /it/python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

**Summary:** Represents the gif blocks openers registry.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IGifBlockLoaderDescriptor[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | r | Ottiene i descrittori registrati. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Restituisce il primo descrittore di apertura supportato. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Ottiene il primo descrittore supportato per il suo nome di tipo. |
| [load_block_by_first_supported_descriptor(stream, container_palette)](#load_block_by_first_supported_descriptor_stream_container_palette_3) | Carica il blocco gif utilizzando il primo apritore trovato adatto per lo _stream_ specificato. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registra l'opener. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Deregistra l'opener. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Restituisce il primo descrittore di apertura supportato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Il descrittore dell'apertura del blocco gif o null se nessun descrittore di apertura è supportato per tale stream. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Ottiene il primo descrittore supportato per il suo nome di tipo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| descriptor_type_name | string | Il nome del tipo di descrittore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Il primo descrittore di apertura trovato o null se non viene trovato alcun descrittore. |


### Method: load_block_by_first_supported_descriptor(stream, container_palette)  [static] {#load_block_by_first_supported_descriptor_stream_container_palette_3}


```
 load_block_by_first_supported_descriptor(stream, container_palette) 
```

Carica il blocco gif utilizzando il primo apritore trovato adatto per lo _stream_ specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza del contenitore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Il blocco gif caricato o null se non viene trovato alcun opener. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registra l'opener.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Il descrittore dell'opener da registrare. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Deregistra l'opener.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Il descrittore dell'opener da deregistrare. |

