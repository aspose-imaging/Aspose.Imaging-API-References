---
title: "EmfPixelFormatDescriptor Classe"
type: docs
weight: 220
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---

**Summary:** The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor__1) | Inizializza una nuova istanza della classe EmfPixelFormatDescriptor |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| b_reserved | System.Byte | r/w | Imposta o ottiene specifica il numero di piani di overlay e underlay. I bit da 0 a 3 specificano <br/>            fino a 15 piani di overlay e i bit da 4 a 7 specificano fino a 15 piani di underlay. |
| c_accum_alpha_bits | System.Byte | r/w | Imposta o ottiene specifica il numero di bit alpha nel buffer di accumulazione. |
| c_accum_bits | System.Byte | r/w | Ottiene o imposta il numero totale di bitplane nel buffer di accumulazione. |
| c_accum_blue_bits | System.Byte | r/w | Ottiene o imposta il numero di bitplane blu nel buffer di accumulazione. |
| c_accum_green_bits | System.Byte | r/w | Ottiene o imposta il numero di bitplane verdi nell'accumulazione. |
| c_accum_red_bits | System.Byte | r/w | Ottiene o imposta il numero di bitplane rosse nel buffer di accumulazione. |
| c_alpha_bits | System.Byte | r/w | Ottiene o imposta il numero di bitplane alfa in ciascun buffer di colore RGBA. |
| c_alpha_shift | System.Byte | r/w | Ottiene o imposta il conteggio di spostamento per le bitplane alfa in ciascun buffer di colore RGBA. |
| c_aux_buffers | System.Byte | r/w | Ottiene o imposta il numero di buffer ausiliari. I buffer ausiliari non sono supportati. |
| c_blue_bits | System.Byte | r/w | Ottiene o imposta il numero di bitplane blu in ciascun buffer di colore RGBA. |
| c_blue_shift | System.Byte | r/w | Ottiene o imposta il conteggio di spostamento per le bitplane blu in ciascun buffer di colore RGBA. |
| c_color_bits | System.Byte | r/w | Ottiene o imposta il numero di bit per pixel per i tipi di pixel RGBA, escludendo le bitplane alfa. Per i pixel della tavola dei colori, è la dimensione di ciascun indice della tavola dei colori. |
| c_depth_bits | System.Byte | r/w | Ottiene o imposta la profondità del buffer di profondità (asse z). |
| c_green_bits | System.Byte | r/w | Ottiene o imposta il numero di bitplane verdi in ciascun buffer di colore RGBA. |
| c_green_shift | System.Byte | r/w | Ottiene o imposta  Specifica il conteggio di spostamento per i bitplane verdi in ciascun buffer di colore RGBA. |
| c_red_bits | System.Byte | r/w | Ottiene o imposta  Specifica il numero di bitplane rossi in ciascun buffer di colore RGBA |
| c_red_shift | System.Byte | r/w | Ottiene o imposta  Specifica il conteggio di spostamento in bit per i bitplane rossi in ciascun buffer di colore RGBA. |
| c_stencil_bits | System.Byte | r/w | Ottiene o imposta specifica la profondità del buffer stencil. |
| dw_damage_mask | int | r/w | Ottiene o imposta Questo campo POTREBBE essere ignorato |
| dw_flags | int | r/w | Ottiene o imposta flag bit che specificano le proprietà del buffer di pixel utilizzato <br/>            per l'output sulla superficie di disegno. Queste proprietà non sono tutte mutualmente <br/>            esclusive; sono consentite combinazioni di flag, tranne dove indicato diversamente. |
| dw_layer_mask | int | r/w | Ottiene o imposta Questo campo POTREBBE essere ignorato. |
| dw_visible_mask | int | r/w | Ottiene o imposta specifica il colore trasparente o l'indice di un piano di sottofondo. Quando il pixel <br/>            è di tipo RGBA, dwVisibleMask è un valore di colore RGB trasparente. Quando il pixel <br/>            è di tipo indice colore, è un valore di indice trasparente. |
| layer_type | System.Byte | r/w | Ottiene o imposta Questo campo POTREBBE essere ignorato |
| n_size | int | r/w | Ottiene o imposta un intero a 16 bit che specifica la dimensione, in byte, di questa struttura dati. |
| n_version | int | r/w | Ottiene o imposta un intero a 16 bit che DEVE essere impostato a 0x0001. |
| pixel_type | System.Byte | r/w | Ottiene o imposta il tipo di dati pixel<br/>            PFD_TYPE_RGBA       0x00 Il formato pixel è RGBA.<br/>            PFD_TYPE_COLORINDEX 0x01 Ogni pixel è un indice in una tavola dei colori. |


### Constructor: EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor__1}


```
 EmfPixelFormatDescriptor() 
```

Inizializza una nuova istanza della classe EmfPixelFormatDescriptor

