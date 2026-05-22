---
title: "ImageCreatorsRegistry 类"
type: docs
weight: 5690
url: /zh/python-net/aspose.imaging/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageCreatorsRegistry

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | r | 获取已注册的描述符。 |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | 获取已注册的图像创建格式。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | 创建第一个找到的适用于指定条件的创建者。 |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | 获取第一个找到的适用于指定条件的受支持描述符。 |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | 注册指定的图像创建者描述符。 |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | 注册创建者。 |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | 注销创建者。 |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

创建第一个找到的适用于指定条件的创建者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 图像选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | 支持指定条件的创建者，若未找到则返回 null。 |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

获取第一个找到的适用于指定条件的受支持描述符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 图像选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | 支持指定条件的创建者描述符，若未找到则返回 null。 |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

注册指定的图像创建者描述符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | 图像创建者描述符。 |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

注册创建者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | 要注册的创建者描述符。 |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

注销创建者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | 创建者描述符。 |

