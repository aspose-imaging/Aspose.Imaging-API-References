---
title: ImageAttributes
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: AnImageAttributes./imageattributes oggetto contiene informazioni su come vengono manipolati i colori bitmap e metafile durante il rendering. UnImageAttributes./imageattributesoggetto mantiene diverse impostazioni di regolazione del colore incluse matrici di regolazione del colore matrici di regolazione della scala di grigi valori di correzione gamma tabelle della mappa dei colori e valori di soglia dei colori. Durante il rendering i colori possono essere corretti scuriti schiariti e rimossi. Per applicare tali manipolazioni inizializzare anImageAttributes./imageattributes oggetto e passare il percorso di quelloImageAttributes./imageattributes oggetto insieme al percorso di anImage./image  al metodo DrawImage.
type: docs
weight: 9680
url: /it/net/aspose.imaging/imageattributes/
---
## ImageAttributes class

An[`ImageAttributes`](../imageattributes) oggetto contiene informazioni su come vengono manipolati i colori bitmap e metafile durante il rendering. Un[`ImageAttributes`](../imageattributes)oggetto mantiene diverse impostazioni di regolazione del colore, incluse matrici di regolazione del colore, matrici di regolazione della scala di grigi, valori di correzione gamma, tabelle della mappa dei colori e valori di soglia dei colori. Durante il rendering, i colori possono essere corretti, scuriti, schiariti e rimossi. Per applicare tali manipolazioni, inizializzare an[`ImageAttributes`](../imageattributes) oggetto e passare il percorso di quello[`ImageAttributes`](../imageattributes) oggetto (insieme al percorso di an[`Image`](../image) ) al metodo DrawImage.

```csharp
public sealed class ImageAttributes
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageAttributes](imageattributes)() | Default_Costruttore |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable)() | Cancella la tabella di rimappatura del colore del pennello[`ImageAttributes`](../imageattributes) oggetto. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey)() | Cancella la chiave colore (intervallo di trasparenza) per la categoria predefinita. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey_1)(ColorAdjustType) | Cancella la chiave del colore (intervallo di trasparenza) per una categoria specificata. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix)() | Cancella la matrice di regolazione del colore per la categoria predefinita. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix_1)(ColorAdjustType) | Cancella la matrice di regolazione del colore per una categoria specificata. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma)() | Disabilita la correzione gamma per la categoria predefinita. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma_1)(ColorAdjustType) | Disabilita la correzione gamma per una categoria specificata. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop)() | Cancella l'impostazione NoOp per la categoria predefinita. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop_1)(ColorAdjustType) | Cancella l'impostazione NoOp per una categoria specificata. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel)() | Cancella l'impostazione del canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel_1)(ColorAdjustType) | Cancella l'impostazione del canale di uscita (ciano-magenta-giallo-nero) per una categoria specificata. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile)() | Cancella l'impostazione del profilo colore del canale di output per la categoria predefinita. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Cancella l'impostazione del profilo colore del canale di output per una categoria specificata. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable)() | Cancella la tabella di rimappatura dei colori per la categoria predefinita. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable_1)(ColorAdjustType) | Cancella la tabella di rimappatura dei colori per una categoria specificata. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold)() | Cancella il valore di soglia per la categoria predefinita. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold_1)(ColorAdjustType) | Cancella il valore di soglia per una categoria specificata. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable)(ColorMap[]) | Imposta la tabella di rimappatura dei colori per la categoria del pennello. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey)(Color, Color) | Imposta la chiave colore per la categoria predefinita. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey_1)(Color, Color, ColorAdjustType) | Imposta la chiave colore (intervallo di trasparenza) per una categoria specificata. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices)(ColorMatrix, ColorMatrix) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per una categoria specificata. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix)(ColorMatrix) | Imposta la matrice di regolazione del colore per la categoria predefinita. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Imposta la matrice di regolazione del colore per la categoria predefinita. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Imposta la matrice di regolazione del colore per una categoria specificata. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma)(float) | Imposta il valore gamma per la categoria predefinita. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma_1)(float, ColorAdjustType) | Imposta il valore gamma per una categoria specificata. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop)() | Disattiva la regolazione del colore per la categoria predefinita. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop_1)(ColorAdjustType) | Disattiva la regolazione del colore per una categoria specificata. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel)(ColorChannelFlag) | Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Imposta il canale di uscita CMYK (ciano-magenta-giallo-nero) per una categoria specificata. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile)(string) | Imposta il file del profilo colore del canale di output per la categoria predefinita. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Imposta il file del profilo colore del canale di output per una categoria specificata. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable)(ColorMap[]) | Imposta la tabella di rimappatura dei colori per la categoria predefinita. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable_1)(ColorMap[], ColorAdjustType) | Imposta la tabella di rimappatura dei colori per una categoria specificata. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold)(float) | Imposta la soglia (intervallo di trasparenza) per la categoria predefinita. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold_1)(float, ColorAdjustType) | Imposta la soglia (intervallo di trasparenza) per una categoria specificata. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode)(WrapMode) | Imposta la modalità di avvolgimento utilizzata per decidere come affiancare una trama su una forma o ai limiti della forma. Una trama viene affiancata su una forma per riempirla quando la trama è più piccola della forma che sta riempiendo. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_1)(WrapMode, Color) | Imposta la modalità di avvolgimento e il colore utilizzati per decidere come affiancare una trama su una forma o ai limiti della forma. Una trama viene affiancata su una forma per riempirla quando la trama è più piccola della forma che sta riempiendo. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_2)(WrapMode, Color, bool) | Imposta la modalità di avvolgimento e il colore utilizzati per decidere come affiancare una trama su una forma o ai limiti della forma. Una trama viene affiancata su una forma per riempirla quando la trama è più piccola della forma che sta riempiendo. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
