---
title: "EmfCreatePen"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_CREATEPEN definisce una penna logica per le operazioni grafiche."
type: docs
weight: 41
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePen extends EmfObjectCreationRecordType
```

Il record EMR\_CREATEPEN definisce una penna logica per operazioni grafiche.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCreatePen(EmfRecord source)](#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCreatePen`. |
| [EmfCreatePen()](#EmfCreatePen--) | Inizializza una nuova istanza della classe `EmfCreatePen`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhPen()](#getIhPen--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto penna logica nella EMF Object Table (sezione 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto penna logica nella EMF Object Table (sezione 3.1.1.1). |
| [getLogPen()](#getLogPen--) | Ottiene o imposta un oggetto LogPen (sezione 2.2.19) che specifica lo stile, la larghezza e il colore della penna logica. |
| [setLogPen(EmfLogPen value)](#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-) | Ottiene o imposta un oggetto LogPen (sezione 2.2.19) che specifica lo stile, la larghezza e il colore della penna logica. |
### EmfCreatePen(EmfRecord source) {#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePen(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCreatePen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


Inizializza una nuova istanza della classe `EmfCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto penna logica nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto penna logica nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLogPen() {#getLogPen--}
```
public EmfLogPen getLogPen()
```


Ottiene o imposta un oggetto LogPen (sezione 2.2.19) che specifica lo stile, la larghezza e il colore della penna logica.

**Returns:**
[EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen)
### setLogPen(EmfLogPen value) {#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-}
```
public void setLogPen(EmfLogPen value)
```


Ottiene o imposta un oggetto LogPen (sezione 2.2.19) che specifica lo stile, la larghezza e il colore della penna logica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen) |  |

