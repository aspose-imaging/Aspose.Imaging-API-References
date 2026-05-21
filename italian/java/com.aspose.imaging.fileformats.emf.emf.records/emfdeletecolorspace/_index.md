---
title: "EmfDeleteColorSpace"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_DELETECOLORSPACE elimina un oggetto di spazio colore logico."
type: docs
weight: 42
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfDeleteColorSpace extends EmfObjectManipulationRecordType
```

Il record EMR\_DELETECOLORSPACE elimina un oggetto spazio colore logico.

Un record EMR\_DELETEOBJECT DOVREBBE essere usato al posto di EMR\_DELETECOLORSPACE per eliminare un oggetto di spazio colore logico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfDeleteColorSpace(EmfRecord source)](#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfDeleteColorSpace`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhCS()](#getIhCS--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto di spazio colore logico nella EMF Object Table (sezione 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto di spazio colore logico nella EMF Object Table (sezione 3.1.1.1). |
### EmfDeleteColorSpace(EmfRecord source) {#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteColorSpace(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfDeleteColorSpace`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto di spazio colore logico nella EMF Object Table (sezione 3.1.1.1).

Questo oggetto è un oggetto WMF LogColorSpace o LogColorSpaceW ([MS-WMF] sezioni 2.2.2.11 e 2.2.2.12, rispettivamente).

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto di spazio colore logico nella EMF Object Table (sezione 3.1.1.1).

Questo oggetto è un oggetto WMF LogColorSpace o LogColorSpaceW ([MS-WMF] sezioni 2.2.2.11 e 2.2.2.12, rispettivamente).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

