---
title: "EmfCreateBrushIndirect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_CREATEBRUSHINDIRECT definisce un pennello logico per operazioni grafiche."
type: docs
weight: 35
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

Il record EMR\_CREATEBRUSHINDIRECT definisce un pennello logico per operazioni grafiche.

L'oggetto pennello logico definito da questo record può essere selezionato nel contesto del dispositivo di riproduzione tramite un record EMR\_SELECTOBJECT (sezione 2.3.8.5), che specifica il pennello logico da utilizzare nelle successive operazioni grafiche.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCreateBrushIndirect`. |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | Inizializza una nuova istanza della classe `EmfCreateBrushIndirect`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello logico nella EMF Object Table (sezione 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello logico nella EMF Object Table (sezione 3.1.1.1). |
| [getLogBrush()](#getLogBrush--) | Ottiene o imposta un oggetto LogBrushEx (sezione 2.2.12) che specifica lo stile, il colore e il motivo del pennello logico. |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | Ottiene o imposta un oggetto LogBrushEx (sezione 2.2.12) che specifica lo stile, il colore e il motivo del pennello logico. |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCreateBrushIndirect`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


Inizializza una nuova istanza della classe `EmfCreateBrushIndirect`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello logico nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato in modo che questo oggetto possa essere riutilizzato o modificato.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello logico nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato in modo che questo oggetto possa essere riutilizzato o modificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


Ottiene o imposta un oggetto LogBrushEx (sezione 2.2.12) che specifica lo stile, il colore e il motivo del pennello logico. Il campo BrushStyle in questo oggetto DEVE essere BS\_SOLID, BS\_HATCHED o BS\_NULL.

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


Ottiene o imposta un oggetto LogBrushEx (sezione 2.2.12) che specifica lo stile, il colore e il motivo del pennello logico. Il campo BrushStyle in questo oggetto DEVE essere BS\_SOLID, BS\_HATCHED o BS\_NULL.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

