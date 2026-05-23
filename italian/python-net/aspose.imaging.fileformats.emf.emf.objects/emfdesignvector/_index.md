---
title: "Classe EmfDesignVector"
type: docs
weight: 40
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---

**Summary:** The DesignVector (section 2.2.3) object defines the design vector, which specifies values for the font axes of a multiple master font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfDesignVector

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfDesignVector()](#EmfDesignVector__1) | Inizializza una nuova istanza della classe EmfDesignVector |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| num_axes | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di elementi in <br/>            l'array Values. Deve essere compreso nell'intervallo da 0 a 16, inclusi. |
| signature | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE essere impostato al valore 0x08007664. |
| values | int[] | r/w | Ottiene o imposta un array opzionale di interi con segno a 32 bit che specificano i valori <br/>            degli assi del carattere di un font OpenType a più master. Il numero massimo di valori nell'array è 16. |


### Constructor: EmfDesignVector() {#EmfDesignVector__1}


```
 EmfDesignVector() 
```

Inizializza una nuova istanza della classe EmfDesignVector

