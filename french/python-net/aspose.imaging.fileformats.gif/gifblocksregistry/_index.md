---
title: "GifBlocksRegistry Classe"
type: docs
weight: 30
url: /fr/python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

**Summary:** Represents the gif blocks openers registry.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IGifBlockLoaderDescriptor[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | r | Obtient les descripteurs enregistrés. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Obtient le premier descripteur d'ouvreurs pris en charge. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Obtient le premier descripteur pris en charge par son nom de type. |
| [load_block_by_first_supported_descriptor(stream, container_palette)](#load_block_by_first_supported_descriptor_stream_container_palette_3) | Charge le bloc gif en utilisant le premier ouvreur trouvé adapté au _stream_ spécifié. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Enregistre l'ouvreurs. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Désenregistre l'ouvreurs. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Obtient le premier descripteur d'ouvreurs pris en charge.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

**Returns**

| Type | Description |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Le descripteur d'ouvreurs de bloc gif ou null si aucun descripteur d'ouvreurs n'est pris en charge pour ce flux. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Obtient le premier descripteur pris en charge par son nom de type.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| descriptor_type_name | string | Le nom du type de descripteur. |

**Returns**

| Type | Description |
| :- | :- |
| [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Le premier descripteur d'ouvreurs trouvé ou null si aucun tel descripteur n'est trouvé. |


### Method: load_block_by_first_supported_descriptor(stream, container_palette)  [static] {#load_block_by_first_supported_descriptor_stream_container_palette_3}


```
 load_block_by_first_supported_descriptor(stream, container_palette) 
```

Charge le bloc gif en utilisant le premier ouvreur trouvé adapté au _stream_ spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette du conteneur. |

**Returns**

| Type | Description |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Le bloc gif chargé ou null si aucun ouvreur n'est trouvé. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Enregistre l'ouvreurs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Le descripteur d'ouvreurs à enregistrer. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Désenregistre l'ouvreurs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| opener_descriptor | [IGifBlockLoaderDescriptor](/imaging/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/) | Le descripteur d'ouvreurs à désenregistrer. |

