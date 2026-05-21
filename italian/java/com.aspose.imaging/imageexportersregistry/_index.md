---
title: "ImageExportersRegistry"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta il registro degli esportatori di immagini."
type: docs
weight: 59
url: /it/java/com.aspose.imaging/imageexportersregistry/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Rappresenta il registro degli esportatori di immagini.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRegisteredFormats()](#getRegisteredFormats--) | Restituisce i formati di esportazione registrati. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Restituisce i descrittori degli esportatori registrati. |
| [register(IImageExporterDescriptor exporterDescriptor)](#register-com.aspose.imaging.IImageExporterDescriptor-) | Registra il descrittore dell'esportatore di immagini specificato. |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Restituisce il primo descrittore supportato trovato adatto alle opzioni di salvataggio e all'immagine specificate. |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Crea il primo esportatore trovato adatto alle opzioni di salvataggio e all'immagine specificate. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.imaging.IImageExporterDescriptor-) | Registra l'esportatore. |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-) | Annulla la registrazione dell'esportatore. |
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Restituisce i formati di esportazione registrati.

Valore: I formati di esportazione registrati.

**Returns:**
long
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Restituisce i descrittori degli esportatori registrati.

Valore: I descrittori degli esportatori registrati.

**Returns:**
com.aspose.imaging.IImageExporterDescriptor[]
### register(IImageExporterDescriptor exporterDescriptor) {#register-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor exporterDescriptor)
```


Registra il descrittore dell'esportatore di immagini specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Il descrittore dell'esportatore di immagini. |

### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


Restituisce il primo descrittore supportato trovato adatto alle opzioni di salvataggio e all'immagine specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'immagine da esportare. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Le opzioni. |

Il primo descrittore dell'esportatore sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


Crea il primo esportatore trovato adatto alle opzioni di salvataggio e all'immagine specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'immagine da esportare. |
|  | options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Le opzioni di salvataggio da utilizzare per l'esportazione. |

Il primo esportatore sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Registra l'esportatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Il descrittore dell'esportatore da registrare. |

### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.imaging.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


Annulla la registrazione dell'esportatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.imaging/iimageexporterdescriptor) | Il descrittore dell'esportatore da deregistrare. |

