---
title: "EmfPlusBitmap Classe"
type: docs
weight: 50
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---

**Summary:** The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmap

**Inheritance:** EmfPlusBaseImageData

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusBitmap()](#EmfPlusBitmap__1) | Inizializza una nuova istanza della classe EmfPlusBitmap |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bitmap_data | [EmfPlusBaseBitmapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata/) | r/w | Ottiene o imposta i dati bitmap<br/>            BitmapData (variabile): Dati a lunghezza variabile che definiscono l'oggetto dati bitmap specificato nel campo Type. Il<br/>            contenuto e il formato dei dati possono variare per ogni tipo di bitmap. |
| height | int | r/w | Ottiene o imposta l'altezza del bitmap<br/>            Height (4 byte): Un intero con segno a 32 bit che specifica l'altezza in pixel dell'area occupata dal bitmap.<br/>            Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato. |
| pixel_format | [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) | r/w | Ottiene o imposta il formato pixel<br/>            PixelFormat (4 byte): Un intero senza segno a 32 bit che specifica il formato dei pixel che compongono l'immagine bitmap.<br/>            I formati pixel supportati sono specificati nell'enumerazione [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) (sezione<br/>            2.1.1.25).<br/>            Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato. |
| stride | int | r/w | Ottiene o imposta lo stride dell'immagine<br/>            Stride (4 byte): Un intero con segno a 32 bit che specifica l'offset in byte tra l'inizio di una scan-line e<br/>            la successiva. Questo valore è il numero di byte per pixel, specificato nel campo PixelFormat, moltiplicato per<br/>            la larghezza in pixel, specificata nel campo Width. Il valore di questo campo DEVE essere un multiplo di quattro.<br/>            Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato. |
| type | [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) | r/w | Ottiene o imposta il tipo dell'immagine<br/>            Type (4 byte): Un intero senza segno a 32 bit che specifica il tipo di dati nel campo BitmapData. Questo valore DEVE<br/>            essere definito nell'enumerazione [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) (sezione 2.1.1.2). |
| width | int | r/w | Ottiene o imposta la larghezza dell'immagine<br/>            Width (4 byte): Un intero con segno a 32 bit che specifica la larghezza in pixel dell'area occupata dal bitmap.<br/>            Se l'immagine è compressa, secondo il campo Type, questo valore è indefinito e DEVE essere ignorato. |


### Constructor: EmfPlusBitmap() {#EmfPlusBitmap__1}


```
 EmfPlusBitmap() 
```

Inizializza una nuova istanza della classe EmfPlusBitmap

