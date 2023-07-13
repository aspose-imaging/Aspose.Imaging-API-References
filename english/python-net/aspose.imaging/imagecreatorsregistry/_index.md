---
title: ImageCreatorsRegistry Class
type: docs
weight: 5520
url: /python-net/aspose.imaging/imagecreatorsregistry/
---

Represents the image creators registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageCreatorsRegistry

**Aspose.Imaging Version:** 23.6

The ImageCreatorsRegistry type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r | Gets the registered image creation formats. |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/imaging/python-net/aspose.imaging/iimagecreatordescriptor) | r | Gets the registered descriptors. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_0) | Registers the specified image creator descriptor. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_1) | Gets the fist found supported descriptor suitable for the specified. |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_2) | Creates the first found creator suitable for the specified. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_3) | Registers the creator. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_4) | Unregisters the creator. |

### register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_0}


```
 register(image_creator_descriptor) 
```

Registers the specified image creator descriptor.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor) | The image creator descriptor. |

### get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_1}


```
 get_first_supported_descriptor(image_options) 
```

Gets the fist found supported descriptor suitable for the specified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The image options. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor) | The creator descriptor which supports the specified or null if no such descriptor is found. |


### create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_2}


```
 create_first_supported_creator(image_options) 
```

Creates the first found creator suitable for the specified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The image options. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator) | The creator which supports the specified or null if no such creator is found. |


### register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_3}


```
 register_creator(creator_descriptor) 
```

Registers the creator.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor) | The creator descriptor to register. |

### unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_4}


```
 unregister_creator(creator_descriptor) 
```

Unregisters the creator.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor) | The creator descriptor. |

