---
title: ImageCreatorsRegistry Class
type: docs
weight: 5640
url: /python-net/aspose.imaging/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageCreatorsRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | r | Gets the registered descriptors. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Gets the registered image creation formats. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Creates the first found creator suitable for the specified. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Gets the fist found supported descriptor suitable for the specified. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Registers the specified image creator descriptor. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Registers the creator. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Unregisters the creator. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Creates the first found creator suitable for the specified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The image options. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | The creator which supports the specified or null if no such creator is found. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Gets the fist found supported descriptor suitable for the specified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The image options. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | The creator descriptor which supports the specified or null if no such descriptor is found. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Registers the specified image creator descriptor.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | The image creator descriptor. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Registers the creator.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | The creator descriptor to register. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Unregisters the creator.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | The creator descriptor. |

