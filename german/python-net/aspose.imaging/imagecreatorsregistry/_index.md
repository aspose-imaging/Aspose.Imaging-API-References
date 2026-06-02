---
title: "ImageCreatorsRegistry Klasse"
type: docs
weight: 5690
url: /de/python-net/aspose.imaging/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageCreatorsRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | r | Ruft die registrierten Deskriptoren ab. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Ermittelt die registrierten Bild-Erstellungsformate. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Erstellt den zuerst gefundenen Ersteller, der für das Angegebene geeignet ist. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Ermittelt den zuerst gefundenen unterstützten Deskriptor, der für das Angegebene geeignet ist. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Registriert den angegebenen Bild-Ersteller-Deskriptor. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Registriert den Ersteller. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Deregistriert den Ersteller. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Erstellt den zuerst gefundenen Ersteller, der für das Angegebene geeignet ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Bildoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Der Ersteller, der das Angegebene unterstützt, oder null, wenn kein solcher Ersteller gefunden wird. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Ermittelt den zuerst gefundenen unterstützten Deskriptor, der für das Angegebene geeignet ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Die Bildoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Der Ersteller-Deskriptor, der das Angegebene unterstützt, oder null, wenn kein solcher Deskriptor gefunden wird. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Registriert den angegebenen Bild-Ersteller-Deskriptor.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Der Bild-Ersteller-Deskriptor. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Registriert den Ersteller.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Der zu registrierende Ersteller-Deskriptor. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Deregistriert den Ersteller.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Der Ersteller-Deskriptor. |

