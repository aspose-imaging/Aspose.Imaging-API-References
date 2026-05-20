---
title: "ImageExportersRegistry"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt das Register der Bild‑Exportierer dar."
type: docs
weight: 59
url: /de/java/com.aspose.imaging/imageexportersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Stellt das Register der Bild‑Exportierer dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Liefert die registrierten Exportformate. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Liefert die registrierten Exporter‑Deskriptoren. |
| [register(IImageExporterDescriptor exporterDescriptor)](#register-com.aspose.imaging.IImageExporterDescriptor-) | Registriert den angegebenen Bild‑Exporter‑Deskriptor. |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Liefert den zuerst gefundenen unterstützten Deskriptor, der zu den angegebenen Speicheroptionen und dem Bild passt. |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Erstellt den zuerst gefundenen Exporter, der zu den angegebenen Speicheroptionen und dem Bild passt. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.imaging.IImageExporterDescriptor-) | Registriert den Exporter. |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-) | Deregistriert den Exporter. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Liefert die registrierten Exportformate.

Wert: Die registrierten Exportformate.

**Returns:**
long
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Liefert die registrierten Exporter‑Deskriptoren.

Wert: Die registrierten Exporter‑Deskriptoren.

**Returns:**
com.aspose.imaging.IImageExporterDescriptor[]
### register(IImageExporterDescriptor exporterDescriptor) {#register-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor exporterDescriptor)
```


Registriert den angegebenen Bild‑Exporter‑Deskriptor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Der Bild‑Exporter‑Deskriptor. |

### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


Liefert den zuerst gefundenen unterstützten Deskriptor, der zu den angegebenen Speicheroptionen und dem Bild passt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das Bild zum Exportieren. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Optionen. |

Der erste Exporter‑Deskriptor wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


Erstellt den zuerst gefundenen Exporter, der zu den angegebenen Speicheroptionen und dem Bild passt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das Bild zum Exportieren. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die zu verwendenden Speicheroptionen für den Export. |

Der erste Exporter wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Registriert den Exporter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Der Exporter-Deskriptor zum Registrieren. |

### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


Deregistriert den Exporter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Der Exporter-Deskriptor zum Abmelden. |

