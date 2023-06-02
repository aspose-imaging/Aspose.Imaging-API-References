---
title: ImageExportersRegistry Class
type: docs
weight: 530
url: /python-net/aspose.imaging/imageexportersregistry/
---

Represents the image exporters registry.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.ImageExportersRegistry

**Assembly:**  Aspose.Imaging Version: 23.5.0

The ImageExportersRegistry type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|registered_formats|Gets the registered export formats.|
|registered_exporter_descriptors|Gets the registered exporter descriptors.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|register(image_exporter_descriptor)|Registers the specified image exporter descriptor.|
|get_first_supported_descriptor(image, options)|Gets the fist found supported descriptor suitable for the specified save options and image.|
|create_first_supported_exporter(image, options)|Creates the first found exporter suitable for the specified save options and image.|
|register_exporter(exporter_descriptor)|Registers the exporter.|
|unregister_exporter(exporter_descriptor)|Unregisters the exporter.|
