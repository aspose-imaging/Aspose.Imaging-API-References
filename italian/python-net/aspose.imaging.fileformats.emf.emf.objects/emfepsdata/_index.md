---
title: "EmfEpsData Classe"
type: docs
weight: 50
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

**Summary:** The EpsData object is a container for EPS data

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfEpsData()](#EmfEpsData__1) | Inizializza una nuova istanza della classe EmfEpsData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| points | [EmfPoint28To4[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4/) | r/w | Ottiene o imposta un array di tre oggetti Point28_4 (sezione 2.2.23) che definisce le <br/>            coordinate del parallelogramma di output usando la notazione FIX a 28,4 bit |
| post_script_data | System.Byte | r/w | Ottiene o imposta un array di byte dei dati PostScript. La lunghezza di questo array può <br/>            essere calcolata dal campo SizeData. Questi dati POSSONO essere usati per renderizzare un'immagine. |
| size_data | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione totale di questo oggetto, in byte |
| versione | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il livello del linguaggio PostScript. Questo <br/>            valore DEVE essere 0x00000001 |


### Constructor: EmfEpsData() {#EmfEpsData__1}


```
 EmfEpsData() 
```

Inizializza una nuova istanza della classe EmfEpsData

