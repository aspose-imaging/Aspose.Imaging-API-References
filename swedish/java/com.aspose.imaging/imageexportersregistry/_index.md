---
title: "ImageExportersRegistry"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar registret för bildexportörer."
type: docs
weight: 59
url: /sv/java/com.aspose.imaging/imageexportersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Representerar registret för bildexportörer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Hämtar de registrerade exportformaten. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Hämtar de registrerade exportörsbeskrivningarna. |
| [register(IImageExporterDescriptor exporterDescriptor)](#register-com.aspose.imaging.IImageExporterDescriptor-) | Registrerar den angivna bildexportörsbeskrivningen. |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Hämtar den först hittade stödda beskrivningen som är lämplig för de angivna sparalternativen och bilden. |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Skapar den först hittade exportören som är lämplig för de angivna sparalternativen och bilden. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.imaging.IImageExporterDescriptor-) | Registrerar exportören. |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-) | Avregistrerar exportören. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Hämtar de registrerade exportformaten.

Värde: De registrerade exportformaten.

**Returns:**
long
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Hämtar de registrerade exportörsbeskrivningarna.

Värde: De registrerade exportörsbeskrivningarna.

**Returns:**
com.aspose.imaging.IImageExporterDescriptor[]
### register(IImageExporterDescriptor exporterDescriptor) {#register-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor exporterDescriptor)
```


Registrerar den angivna bildexportörsbeskrivningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Bildexportörsbeskrivningen. |

### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


Hämtar den först hittade stödda beskrivningen som är lämplig för de angivna sparalternativen och bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Bilden att exportera. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Alternativen. |

Den första exportörsbeskrivningen kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


Skapar den först hittade exportören som är lämplig för de angivna sparalternativen och bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Bilden att exportera. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Sparalternativen att använda för export. |

Den första exportören kommer faktiskt att vara den sista som registreras. |

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Registrerar exportören.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Exportörsbeskrivningen att registrera. |

### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


Avregistrerar exportören.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Exportörsbeskrivningen att avregistrera. |

