---
title: "ImageExportersRegistry"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente le registre des exportateurs d'images."
type: docs
weight: 59
url: /fr/java/com.aspose.imaging/imageexportersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Représente le registre des exportateurs d'images.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Obtient les formats d'exportation enregistrés. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Obtient les descripteurs d'exportateur enregistrés. |
| [register(IImageExporterDescriptor exporterDescriptor)](#register-com.aspose.imaging.IImageExporterDescriptor-) | Enregistre le descripteur d'exportateur d'image spécifié. |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Obtient le premier descripteur pris en charge trouvé adapté aux options d'enregistrement spécifiées et à l'image. |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Crée le premier exportateur trouvé adapté aux options d'enregistrement spécifiées et à l'image. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.imaging.IImageExporterDescriptor-) | Enregistre l'exportateur. |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-) | Désenregistre l'exportateur. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Obtient les formats d'exportation enregistrés.

Valeur : les formats d'exportation enregistrés.

**Returns:**
long
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Obtient les descripteurs d'exportateur enregistrés.

Valeur : les descripteurs d'exportateur enregistrés.

**Returns:**
com.aspose.imaging.IImageExporterDescriptor[]
### register(IImageExporterDescriptor exporterDescriptor) {#register-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor exporterDescriptor)
```


Enregistre le descripteur d'exportateur d'image spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Le descripteur d'exportateur d'image. |

### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


Obtient le premier descripteur pris en charge trouvé adapté aux options d'enregistrement spécifiées et à l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'image à exporter. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options. |

Le premier descripteur d'exportateur sera en fait le dernier enregistré. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


Crée le premier exportateur trouvé adapté aux options d'enregistrement spécifiées et à l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'image à exporter. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d'enregistrement à utiliser pour l'exportation. |

Le premier exportateur sera en fait le dernier enregistré. |

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Enregistre l'exportateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Le descripteur d'exportateur à enregistrer. |

### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


Désenregistre l'exportateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Le descripteur d'exportateur à désenregistrer. |

