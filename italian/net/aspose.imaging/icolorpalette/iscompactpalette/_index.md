---
title: IsCompactPalette
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene un valore che indica se viene utilizzata la tavolozza compatta.
type: docs
weight: 40
url: /it/net/aspose.imaging/icolorpalette/iscompactpalette/
---
## IColorPalette.IsCompactPalette property

Ottiene un valore che indica se viene utilizzata la tavolozza compatta.

```csharp
public bool IsCompactPalette { get; }
```

### Valore della proprietà

`VERO` se viene utilizzata una tavolozza compatta; altrimenti,`falso`.

### Osservazioni

Tavolozza compatta significa che l'immagine conterrà solo le voci della tavolozza specificate, se possibile, o in altre parole l'immagine sarà più compatta e occuperà meno spazio; altrimenti ci saranno voci 2^BitsPerPixel e l'immagine riserverà più spazio per tutte le voci possibili della tavolozza. L'impostazione di questo valore su true e la modifica delle voci della tavolozza possono causare una riduzione delle prestazioni poiché potrebbe verificarsi lo spostamento dei dati, quindi utilizzarlo con attenzione.

### Guarda anche

* interface [IColorPalette](../../icolorpalette)
* spazio dei nomi [Aspose.Imaging](../../icolorpalette)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->