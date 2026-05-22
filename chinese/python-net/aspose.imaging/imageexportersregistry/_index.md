---
title: "ImageExportersRegistry 类"
type: docs
weight: 5700
url: /zh/python-net/aspose.imaging/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageExportersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | r | 获取已注册的导出器描述符。 |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | 获取已注册的导出格式。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | 创建第一个符合指定保存选项和图像的导出器。 |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | 获取第一个符合指定保存选项和图像的受支持描述符。 |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | 注册指定的图像导出器描述符。 |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | 注册导出器。 |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | 注销导出器。 |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

创建第一个符合指定保存选项和图像的导出器。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要导出的图像。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 用于导出的保存选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | 支持指定图像和保存选项的导出器，如果未找到则为 null。 |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

获取第一个符合指定保存选项和图像的受支持描述符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要导出的图像。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | 支持指定图像和保存选项的导出器描述符，如果未找到则为 null。 |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

注册指定的图像导出器描述符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | 图像导出器描述符。 |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

注册导出器。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | 要注册的导出器描述符。 |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

注销导出器。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | 要注销的导出器描述符。 |

