---
title: "Classe ImageCreatorsRegistry"
type: docs
weight: 5690
url: /fr/python-net/aspose.imaging/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageCreatorsRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | r | Obtient les descripteurs enregistrés. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Obtient les formats de création d'image enregistrés. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Crée le premier créateur trouvé adapté à la spécification. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Obtient le premier descripteur pris en charge trouvé adapté à la spécification. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Enregistre le descripteur de créateur d'image spécifié. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Enregistre le créateur. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Désenregistre le créateur. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Crée le premier créateur trouvé adapté à la spécification.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'image. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Le créateur qui prend en charge le spécifié ou null si aucun créateur de ce type n'est trouvé. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Obtient le premier descripteur pris en charge trouvé adapté à la spécification.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'image. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Le descripteur de créateur qui prend en charge le spécifié ou null si aucun descripteur de ce type n'est trouvé. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Enregistre le descripteur de créateur d'image spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Le descripteur de créateur d'image. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Enregistre le créateur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Le descripteur de créateur à enregistrer. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Désenregistre le créateur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Le descripteur de créateur. |

