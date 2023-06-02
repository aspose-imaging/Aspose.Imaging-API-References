---
title: GifBlocksRegistry Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.gif/gifblocksregistry/
---

Represents the gif blocks openers registry.

**Namespace:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Class Name:** aspose.imaging.fileformats.gif.GifBlocksRegistry

**Assembly:**  Aspose.Imaging Version: 23.5.0

The GifBlocksRegistry type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|registered_descriptors|Gets the registered descriptors.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_first_supported_descriptor_by_type_name(descriptor_type_name)|Gets the first supported descriptor by its type name.|
|get_first_supported_descriptor(stream)|Gets the first supported opener descriptor.|
|load_block_by_first_supported_descriptor(stream, container_palette)|Loads gif block using first found opener suitable for the specified|
|register_opener(opener_descriptor)|Registers the opener.|
|unregister_opener(opener_descriptor)|Unregisters the opener.|
