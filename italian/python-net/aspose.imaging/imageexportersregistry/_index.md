---
title: "ImageExportersRegistry Classe"
type: docs
weight: 5700
url: /it/python-net/aspose.imaging/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageExportersRegistry

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | r | Ottiene i descrittori degli esportatori registrati. |
| registered_formats [static] | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Ottiene i formati di esportazione registrati. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Crea il primo esportatore trovato adatto alle opzioni di salvataggio e all'immagine specificate. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Ottiene il primo descrittore supportato trovato adatto alle opzioni di salvataggio e all'immagine specificate. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Registra il descrittore dell'esportatore di immagini specificato. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Registra l'esportatore. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Annulla la registrazione dell'esportatore. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Crea il primo esportatore trovato adatto alle opzioni di salvataggio e all'immagine specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da esportare. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio da utilizzare per l'esportazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | L'esportatore che supporta l'immagine e le opzioni di salvataggio specificate o null se non viene trovato alcun esportatore corrispondente. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Ottiene il primo descrittore supportato trovato adatto alle opzioni di salvataggio e all'immagine specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine da esportare. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Il descrittore dell'esportatore che supporta l'immagine e le opzioni di salvataggio specificate o null se non viene trovato alcun descrittore corrispondente. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Registra il descrittore dell'esportatore di immagini specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Il descrittore dell'esportatore di immagini. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Registra l'esportatore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Il descrittore dell'esportatore da registrare. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Annulla la registrazione dell'esportatore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Il descrittore dell'esportatore da annullare la registrazione. |

