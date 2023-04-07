---
title: ImageCreatorsRegistry Class
type: docs
weight: 510
url: /python-net/api-reference/aspose.imaging/imagecreatorsregistry/
---

Represents the image creators registry.

**Namespace:** [aspose.imaging](/imaging/python-net/api-reference/aspose.imaging/)

**Full Class Name:** aspose.imaging.ImageCreatorsRegistry

**Assembly:**  Aspose.Imaging Version: 23.3.0

The ImageCreatorsRegistry type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|registered_formats|Gets the registered image creation formats.|
|registered_descriptors|Gets the registered descriptors.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|register(image_creator_descriptor)|Registers the specified image creator descriptor.|
|get_first_supported_descriptor(image_options)|Gets the fist found supported descriptor suitable for the specified.|
|create_first_supported_creator(image_options)|Creates the first found creator suitable for the specified.|
|register_creator(creator_descriptor)|Registers the creator.|
|unregister_creator(creator_descriptor)|Unregisters the creator.|
