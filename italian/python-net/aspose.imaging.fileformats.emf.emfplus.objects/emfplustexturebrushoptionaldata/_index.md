---
title: "EmfPlusTextureBrushOptionalData Classe"
type: docs
weight: 690
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---

**Summary:** he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData__1) | Inizializza una nuova istanza della classe EmfPlusTextureBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| image_object | [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) | r/w | Ottiene o imposta un oggetto EmfPlusImage opzionale (sezione 2.2.1.4) che specifica la<br/>            trama del pennello. Questo campo DEVE essere presente se la dimensione del <br/>            record EmfPlusObject (sezione 2.3.5.1) che definisce questo pennello di trama <br/>            è sufficientemente grande da contenere un oggetto EmfPlusImage oltre ai <br/>            campi obbligatori dell'oggetto EmfPlusTextureBrushData <br/>            e, facoltativamente, di un oggetto EmfPlusTransformMatrix. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta un oggetto EmfPlusTransformMatrix opzionale (sezione 2.2.47) <br/>            che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il<br/>            pennello di trama. Questo campo DEVE essere presente se il flag BrushDataTransform <br/>            è impostato nel campo BrushDataFlags dell'oggetto EmfPlusTextureBrushData. |


### Constructor: EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData__1}


```
 EmfPlusTextureBrushOptionalData() 
```

Inizializza una nuova istanza della classe EmfPlusTextureBrushOptionalData

