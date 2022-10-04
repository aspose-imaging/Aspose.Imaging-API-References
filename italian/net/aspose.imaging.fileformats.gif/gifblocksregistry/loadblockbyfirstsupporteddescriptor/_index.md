---
title: LoadBlockByFirstSupportedDescriptor
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Carica il blocco gif utilizzando il primo apri trovato adatto a quello specificatostream .
type: docs
weight: 40
url: /it/net/aspose.imaging.fileformats.gif/gifblocksregistry/loadblockbyfirstsupporteddescriptor/
---
## GifBlocksRegistry.LoadBlockByFirstSupportedDescriptor method

Carica il blocco gif utilizzando il primo apri trovato adatto a quello specificato*stream* .

```csharp
public static IGifBlock LoadBlockByFirstSupportedDescriptor(Stream stream, 
    IColorPalette containerPalette)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |
| containerPalette | IColorPalette | La tavolozza dei contenitori. |

### Valore di ritorno

Il blocco gif caricato o null se non viene trovato alcun apri.

### Osservazioni

Il primo apri sarà effettivamente l'ultimo registrato.

### Guarda anche

* interface [IGifBlock](../../igifblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifBlocksRegistry](../../gifblocksregistry)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif](../../gifblocksregistry)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->