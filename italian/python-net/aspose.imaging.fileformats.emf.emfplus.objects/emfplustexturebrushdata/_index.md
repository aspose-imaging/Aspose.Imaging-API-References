---
title: "EmfPlusTextureBrushData Classe"
type: docs
weight: 680
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

**Summary:** The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData__1) | Inizializza una nuova istanza della classe EmfPlusTextureBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. <br/>            Questo valore DEVE essere composto dai flag BrushData (sezione 2.1.2.1). <br/>            I seguenti flag sono rilevanti per un pennello texture<br/>            BrushDataTransform<br/>            BrushDataIsGammaCorrected<br/>            BrushDataDoNotTransform |
| optional_data | [EmfPlusTextureBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/) | r/w | Ottiene o imposta un oggetto opzionale EmfPlusTextureBrushOptionalData (sezione 2.2.2.46) che <br/>            specifica dati aggiuntivi per il pennello texture. Il contenuto specifico di <br/>            questo campo è determinato dal valore del campo BrushDataFlags |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Ottiene o imposta un intero con segno a 32 bit dall'enumerazione WrapMode (sezione 2.1.1.34) <br/>            che specifica come ripetere l'immagine texture su una forma, quando l'<br/>            immagine è più piccola dell'area da riempire. |


### Constructor: EmfPlusTextureBrushData() {#EmfPlusTextureBrushData__1}


```
 EmfPlusTextureBrushData() 
```

Inizializza una nuova istanza della classe EmfPlusTextureBrushData

