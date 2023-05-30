---
title: ImageLoadersRegistry Class
type: docs
weight: 540
url: /python-net/aspose.imaging/imageloadersregistry/
---

Represents the image loaders registry.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.ImageLoadersRegistry

**Assembly:**  Aspose.Imaging Version: 23.5.6

The ImageLoadersRegistry type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|registered_formats|Gets the registered image loading formats.|
|registered_descriptors|Gets the registered descriptors.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|register(image_loader_descriptor)|Registers the specified image loader descriptor.|
|get_first_supported_descriptor_by_type_name(descriptor_type_name)|Gets the first supported descriptor by its type name.|
|get_first_supported_descriptor_by_file_format(file_format)|Gets the first supported file format by its type name.|
|get_first_supported_descriptor(stream, load_options)|Gets the fist found supported descriptor suitable for the specified|
|create_first_supported_loader(stream, load_options)|Creates the first found loader suitable for the specified|
|register_loader(loader_descriptor)|Registers the loader.|
|unregister_loader(loader_descriptor)|Unregisters the loader.|
