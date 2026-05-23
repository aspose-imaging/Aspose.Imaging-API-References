---
title: "Clase ImageCreatorsRegistry"
type: docs
weight: 5690
url: /es/python-net/aspose.imaging/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageCreatorsRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | r | Obtiene los descriptores registrados. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Obtiene los formatos de creación de imágenes registrados. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Crea el primer creador encontrado que sea adecuado para lo especificado. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Obtiene el primer descriptor compatible encontrado que sea adecuado para lo especificado. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Registra el descriptor de creador de imágenes especificado. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Registra el creador. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Anula el registro del creador. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Crea el primer creador encontrado que sea adecuado para lo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | El creador que soporta lo especificado o null si no se encuentra tal creador. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Obtiene el primer descriptor compatible encontrado que sea adecuado para lo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | El descriptor del creador que soporta lo especificado o null si no se encuentra tal descriptor. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Registra el descriptor de creador de imágenes especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | El descriptor del creador de imágenes. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Registra el creador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | El descriptor del creador a registrar. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Anula el registro del creador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | El descriptor del creador. |

