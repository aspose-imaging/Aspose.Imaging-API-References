---
title: "IImageExporterDescriptor 类"
type: docs
weight: 5330
url: /zh/python-net/aspose.imaging/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IImageExporterDescriptor

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | 确定图像导出器是否可以将指定的图像导出为保存选项指定的图像格式。 |
| [create_instance()](#create_instance__2) | 创建一个新的导出器实例。 |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

确定图像导出器是否可以将指定的图像导出为保存选项指定的图像格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | 要导出的图像。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项基类。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>True</c> 如果由此描述符创建的导出器可以将指定的图像导出为指定的文件格式；否则为 <c>false</c>。 |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

创建一个新的导出器实例。

**Returns**

| Type | Description |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | 新的导出器实例。 |


