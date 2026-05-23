---
title: "EmfPlusBlurEffect Classe"
type: docs
weight: 100
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

**Summary:** The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect__1) | Inizializza una nuova istanza della classe EmfPlusBlurEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| blur_radius | float | r/w | Ottiene o imposta un numero a virgola mobile a 32 bit che specifica il raggio di sfocatura in pixel,<br/>            che determina il numero di pixel coinvolti nel calcolo del nuovo valore di un dato pixel.<br/>            Questo valore DEVE essere nell'intervallo da 0.0 a 255.0. |
| expand_edge | bool | r/w | Ottiene o imposta un valore booleano a 32 bit che specifica se la bitmap si espande di<br/>            una quantità pari al valore di BlurRadius per produrre bordi morbidi. Questo valore DEVE essere<br/>            uno dei seguenti:<br/>            FALSE<br/>            0x00000000<br/>            La dimensione della bitmap NON DEVE cambiare, e i suoi bordi morbidi DOVREBBERO essere ritagliati alla<br/>            dimensione di BlurRadius.<br/>            TRUE<br/>            0x00000001<br/>            La dimensione della bitmap DOVREBBE espandersi di una quantità pari a BlurRadius per<br/>            produrre bordi morbidi. |


### Constructor: EmfPlusBlurEffect() {#EmfPlusBlurEffect__1}


```
 EmfPlusBlurEffect() 
```

Inizializza una nuova istanza della classe EmfPlusBlurEffect

