---
title: "EmfPlusCustomLineCapOptionalData Classe"
type: docs
weight: 280
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---

**Summary:** The EmfPlusCustomLineCapOptionalData object specifies optional fill and outline data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData__1) | Inizializza una nuova istanza della classe EmfPlusCustomLineCapOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| fill_data | [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath/) | r/w | Ottiene o imposta l'oggetto opzionale EmfPlusFillPath (sezione 2.2.2.17) che specifica il percorso per riempire un cap di linea grafica personalizzato<br/>            Questo campo DEVE essere presente se il flag CustomLineCapDataFillPath è impostato nei CustomLineCapDataFlags<br/>            campo dell'oggetto EmfPlusCustomLineCapData. |
| outline_data | [EmfPlusLinePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath/) | r/w | Ottiene o imposta l'oggetto opzionale EmfPlusLinePath (sezione 2.2.2.26) <br/>            che specifica il percorso per delineare un cap di linea grafica personalizzato. Questo campo DEVE essere presente se il flag CustomLineCapDataLinePath è impostato nei CustomLineCapDataFlags <br/>            campo dell'oggetto EmfPlusCustomLineCapData. |


### Constructor: EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData__1}


```
 EmfPlusCustomLineCapOptionalData() 
```

Inizializza una nuova istanza della classe EmfPlusCustomLineCapOptionalData

