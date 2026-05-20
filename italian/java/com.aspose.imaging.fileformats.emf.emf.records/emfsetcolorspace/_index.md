---
title: "EmfSetColorSpace"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETCOLORSPACE definisce l'oggetto spazio colore logico corrente per le operazioni grafiche."
type: docs
weight: 123
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetColorSpace extends EmfObjectManipulationRecordType
```

Il record EMR\_SETCOLORSPACE definisce l'oggetto di spazio colore logico corrente per le operazioni grafiche.

L'oggetto spazio colore logico definito da questo record DEVE essere utilizzato nelle operazioni di disegno specificate dai successivi record EMF, fino a quando un diverso oggetto spazio colore logico non venga specificato da un altro record EMR\_SETCOLORSPACE, o l'oggetto venga rimosso da un record EMR\_DELETECOLORSPACE.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetColorSpace(EmfRecord source)](#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetColorSpace`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhCS()](#getIhCS--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto di spazio colore logico nella EMF Object Table (sezione 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto di spazio colore logico nella EMF Object Table (sezione 3.1.1.1). |
### EmfSetColorSpace(EmfRecord source) {#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorSpace(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetColorSpace`.

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

