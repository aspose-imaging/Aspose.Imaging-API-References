---
title: GetFirstSupportedDescriptor
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene il primo descrittore di apertura supportato.
type: docs
weight: 20
url: /it/net/aspose.imaging.fileformats.gif/gifblocksregistry/getfirstsupporteddescriptor/
---
## GifBlocksRegistry.GetFirstSupportedDescriptor method

Ottiene il primo descrittore di apertura supportato.

```csharp
public static IGifBlockLoaderDescriptor GetFirstSupportedDescriptor(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |

### Valore di ritorno

Il descrittore di apertura del blocco gif o null se nessun descrittore di apertura è supportato per tale flusso.

### Osservazioni

Il primo ad aprire sarà effettivamente l'ultimo registrato.

### Guarda anche

* interface [IGifBlockLoaderDescriptor](../../igifblockloaderdescriptor)
* class [GifBlocksRegistry](../../gifblocksregistry)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif](../../gifblocksregistry)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->