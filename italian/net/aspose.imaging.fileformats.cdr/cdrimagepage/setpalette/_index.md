---
title: SetPalette
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Imposta la tavolozza dellimmagine.
type: docs
weight: 120
url: /it/net/aspose.imaging.fileformats.cdr/cdrimagepage/setpalette/
---
## CdrImagePage.SetPalette method

Imposta la tavolozza dell'immagine.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | IColorPalette | La tavolozza da impostare. |
| updateColors | Boolean | se impostato su`VERO` colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici di colore rimangono invariati. Si noti che gli indici non modificati possono causare il crash dell'immagine durante il caricamento se alcuni indici non hanno voci di tavolozza corrispondenti. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException |  |

### Guarda anche

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [CdrImagePage](../../cdrimagepage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Cdr](../../cdrimagepage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
