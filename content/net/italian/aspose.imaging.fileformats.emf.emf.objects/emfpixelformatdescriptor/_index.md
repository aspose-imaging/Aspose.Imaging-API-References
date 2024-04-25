---
title: EmfPixelFormatDescriptor
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto PixelFormatDescriptor può essere utilizzato nei record EMR_HEADER sezione 2.3.4.2 per specificare il formato pixel della superficie di output per il contesto del dispositivo di riproduzione.
type: docs
weight: 3120
url: /it/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
## EmfPixelFormatDescriptor class

L'oggetto PixelFormatDescriptor può essere utilizzato nei record EMR_HEADER (sezione 2.3.4.2) per specificare il formato pixel della superficie di output per il contesto del dispositivo di riproduzione.

```csharp
public sealed class EmfPixelFormatDescriptor : EmfObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPixelFormatDescriptor](emfpixelformatdescriptor)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BReserved](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/breserved) { get; set; } | Ottiene o imposta il numero di piani di sovrapposizione e di sovrapposizione. I bit da 0 a 3 specificano fino a 15 piani di sovrapposizione e i bit da 4 a 7 specificano fino a 15 piani di sovrapposizione |
| [CAccumAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumalphabits) { get; set; } | Ottiene o imposta il numero di bitplane alfa nel buffer di accumulo |
| [CAccumBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbits) { get; set; } | Ottiene o imposta il numero totale di bitplane nel buffer di accumulo. |
| [CAccumBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbluebits) { get; set; } | Ottiene o imposta il numero di bitplane blu nel buffer di accumulo. |
| [CAccumGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumgreenbits) { get; set; } | Ottiene o imposta il numero di bitplane verdi nell'accumulazione |
| [CAccumRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumredbits) { get; set; } | Ottiene o imposta il numero di bitplane rossi nel buffer di accumulo |
| [CAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphabits) { get; set; } | Ottiene o imposta Specifica il numero di bitplane alfa in ciascun buffer di colore RGBA |
| [CAlphaShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphashift) { get; set; } | Ottiene o imposta Specifica il conteggio di spostamento per i bitplane alfa in ciascun buffer di colore RGBA |
| [CAuxBuffers](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cauxbuffers) { get; set; } | Ottiene o imposta il numero di buffer ausiliari. I buffer ausiliari non sono supportati |
| [CBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cbluebits) { get; set; } | Ottiene o imposta Specifica il numero di bitplane blu in ciascun buffer di colore RGBA. |
| [CBlueShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cblueshift) { get; set; } | Ottiene o imposta Specifica il conteggio degli spostamenti per i bitplane blu in ciascun buffer di colore RGBA. |
| [CColorBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ccolorbits) { get; set; } | Ottiene o imposta il numero di bit per pixel per i tipi di pixel RGBA, esclusi i bitplane alfa. Per i pixel della tabella dei colori, è la dimensione di ciascuna tabella dei colori index |
| [CDepthBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cdepthbits) { get; set; } | Ottiene o imposta la profondità del buffer di profondità (asse z). |
| [CGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenbits) { get; set; } | Ottiene o imposta Specifica il numero di bitplane verdi in ciascun buffer di colore RGBA |
| [CGreenShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenshift) { get; set; } | Ottiene o imposta Specifica il conteggio di spostamento per i bitplane verdi in ciascun buffer di colore RGBA. |
| [CRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credbits) { get; set; } | Ottiene o imposta Specifica il numero di bitplane rossi in ciascun buffer di colore RGBA |
| [CRedShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credshift) { get; set; } | Ottiene o imposta Specifica il conteggio di spostamento in bit per i bitplane rossi in ciascun buffer di colore RGBA. |
| [CStencilBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cstencilbits) { get; set; } | Ottiene o imposta la profondità del buffer dello stencil. |
| [DwDamageMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwdamagemask) { get; set; } | Ottiene o imposta Questo campo PUÒ essere ignorato |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwflags) { get; set; } | Ottiene o imposta flag di bit che specificano le proprietà del buffer di pixel utilizzato per l'output sulla superficie del disegno. Queste proprietà non sono tutte mutuamente esclusive ; sono consentite combinazioni di flag, salvo diversa indicazione. |
| [DwLayerMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwlayermask) { get; set; } | Ottiene o imposta Questo campo PUÒ essere ignorato. |
| [DwVisibleMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwvisiblemask) { get; set; } | Ottiene o imposta il colore trasparente o l'indice di un piano di sovrapposizione. Quando il tipo di pixel è RGBA, dwVisibleMask è un valore di colore RGB trasparente. Quando il tipo di pixel è un indice di colore, è un valore di indice trasparente. |
| [ILayerType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ilayertype) { get; set; } | Ottiene o imposta Questo campo PUÒ essere ignorato |
| [IPixelType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ipixeltype) { get; set; } | Ottiene o imposta il tipo di dati dei pixel PFD_TYPE_RGBA 0x00 Il formato dei pixel è RGBA. PFD_TYPE_COLORINDEX 0x01 Ogni pixel è un indice in una tabella dei colori. |
| [NSize](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nsize) { get; set; } | Ottiene o imposta un numero intero a 16 bit che specifica la dimensione, in byte, di questa struttura dati. |
| [NVersion](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nversion) { get; set; } | Ottiene o imposta un numero intero a 16 bit che DEVE essere impostato su 0x0001. |

### Guarda anche

* class [EmfObject](../emfobject)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
