---
title: "ImageCreatorsRegistry Classe"
type: docs
weight: 5690
url: /it/python-net/aspose.imaging/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageCreatorsRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | r | Ottiene i descrittori registrati. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Restituisce i formati di creazione immagine registrati. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Crea il primo creatore trovato adatto a quanto specificato. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Restituisce il primo descrittore supportato trovato adatto a quanto specificato. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Registra il descrittore del creatore immagine specificato. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Registra il creatore. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Deregistra il creatore. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Crea il primo creatore trovato adatto a quanto specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni dell'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Il creatore che supporta quanto specificato o null se non viene trovato alcun creatore. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Restituisce il primo descrittore supportato trovato adatto a quanto specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni dell'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Il descrittore del creatore che supporta quanto specificato o null se non viene trovato alcun descrittore. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Registra il descrittore del creatore immagine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Il descrittore del creatore immagine. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Registra il creatore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Il descrittore del creatore da registrare. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Deregistra il creatore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Il descrittore del creatore. |

