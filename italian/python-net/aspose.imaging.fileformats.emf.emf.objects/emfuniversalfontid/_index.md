---
title: "Classe EmfUniversalFontId"
type: docs
weight: 280
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---

**Summary:** The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfUniversalFontId()](#EmfUniversalFontId__1) | Inizializza una nuova istanza della classe EmfUniversalFontId |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| checksum | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che è il checksum del carattere.<br/>Il valore del checksum ha i seguenti significati.<br/>0x00000000  L'oggetto è un carattere dispositivo. <br/>0x00000001  L'oggetto è un carattere Type 1 installato sulla macchina client e viene <br/>elencato dal driver stampante PostScript come carattere dispositivo. <br/>0x00000002  L'oggetto non è un carattere ma è un rasterizzatore Type 1. <br/>3 ≤ valore   L'oggetto è un bitmap, vettoriale o un carattere TrueType, o un carattere rasterizzato Type 1 che <br/>è stato creato da un rasterizzatore Type 1. |
| index | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che è un indice associato all'oggetto carattere. Il <br/>significato di questo campo è determinato dal tipo di carattere. |


### Constructor: EmfUniversalFontId() {#EmfUniversalFontId__1}


```
 EmfUniversalFontId() 
```

Inizializza una nuova istanza della classe EmfUniversalFontId

