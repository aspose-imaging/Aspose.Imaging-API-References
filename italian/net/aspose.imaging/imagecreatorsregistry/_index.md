---
title: ImageCreatorsRegistry
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Rappresenta il registro dei creatori di immagini.
type: docs
weight: 9690
url: /it/net/aspose.imaging/imagecreatorsregistry/
---
## ImageCreatorsRegistry class

Rappresenta il registro dei creatori di immagini.

```csharp
public static class ImageCreatorsRegistry
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.imaging/imagecreatorsregistry/registereddescriptors) { get; } | Ottiene i descrittori registrati. |
| static [RegisteredFormats](../../aspose.imaging/imagecreatorsregistry/registeredformats) { get; } | Ottiene i formati di creazione dell'immagine registrati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [CreateFirstSupportedCreator](../../aspose.imaging/imagecreatorsregistry/createfirstsupportedcreator)(ImageOptionsBase) | Crea il primo creatore trovato adatto per l'oggetto specificato. |
| static [GetFirstSupportedDescriptor](../../aspose.imaging/imagecreatorsregistry/getfirstsupporteddescriptor)(ImageOptionsBase) | Ottiene il primo descrittore supportato trovato adatto per l'oggetto specificato. |
| static [Register](../../aspose.imaging/imagecreatorsregistry/register)(IImageCreatorDescriptor) | Registra il descrittore del creatore di immagini specificato. |
| static [RegisterCreator](../../aspose.imaging/imagecreatorsregistry/registercreator)(IImageCreatorDescriptor) | Registra il creatore. |
| static [UnregisterCreator](../../aspose.imaging/imagecreatorsregistry/unregistercreator)(IImageCreatorDescriptor) | Annulla la registrazione del creatore. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->