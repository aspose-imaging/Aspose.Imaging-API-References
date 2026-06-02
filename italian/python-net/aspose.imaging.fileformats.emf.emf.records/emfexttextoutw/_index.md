---
title: "Classe EmfExtTextOutW"
type: docs
weight: 480
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---

**Summary:** The EMR_EXTTEXTOUTW record draws an ASCII text string using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtTextOutW

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfExtTextOutW()](#EmfExtTextOutW__1) | Inizializza una nuova istanza della classe [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/). |
| [EmfExtTextOutW(source)](#EmfExtTextOutW_source_2) | Inizializza una nuova istanza della classe [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19). Non è utilizzato e <br/>            DEVE essere ignorato al ricevimento. |
| ex_scale | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala da applicare lungo <br/>            l'asse X per convertire le unità di spazio pagina in unità .01mm. Questo DOVREBBE essere usato solo se il <br/>            modo grafico specificato da iGraphicsMode è GM_COMPATIBLE. |
| ey_scale | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il fattore di scala da applicare lungo <br/>            l'asse Y per convertire le unità di spazio pagina in unità .01mm. Questo DOVREBBE essere usato solo se il <br/>            modo grafico specificato da iGraphicsMode è GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il modo grafico dall'enumerazione <br/>            GraphicsMode (sezione 2.1.16). |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
| w_emr_text | [EmfText](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | Ottiene o imposta un oggetto EmrText (sezione 2.2.5) che specifica la stringa di output in caratteri Unicode UTF16-LE a 16 bit, con attributi di testo e valori di spaziatura. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtTextOutW() {#EmfExtTextOutW__1}


```
 EmfExtTextOutW() 
```

Inizializza una nuova istanza della classe [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/).

### Constructor: EmfExtTextOutW(source) {#EmfExtTextOutW_source_2}


```
 EmfExtTextOutW(source) 
```

Inizializza una nuova istanza della classe [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La sorgente. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La sorgente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Il tipo di record. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


