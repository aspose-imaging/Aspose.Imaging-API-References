---
title: "EmfSelectClipPath"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SELECTCLIPPATH specifica il percorso corrente come regione di ritaglio per un contesto di dispositivo di riproduzione, combinando la nuova regione con eventuali regioni di ritaglio esistenti usando la modalità specificata."
type: docs
weight: 115
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfSelectClipPath extends EmfClippingRecordType
```

Il record EMR\_SELECTCLIPPATH specifica il percorso corrente come regione di ritaglio per un contesto di dispositivo di riproduzione, combinando la nuova regione con qualsiasi regione di ritaglio esistente usando la modalità specificata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSelectClipPath(EmfRecord source)](#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSelectClipPath`. |
| [EmfSelectClipPath()](#EmfSelectClipPath--) | Inizializza una nuova istanza della classe `EmfSelectClipPath`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRegionMode()](#getRegionMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il modo di utilizzare il percorso. |
| [setRegionMode(int value)](#setRegionMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il modo di utilizzare il percorso. |
### EmfSelectClipPath(EmfRecord source) {#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectClipPath(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSelectClipPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfSelectClipPath() {#EmfSelectClipPath--}
```
public EmfSelectClipPath()
```


Inizializza una nuova istanza della classe `EmfSelectClipPath`.

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il modo di utilizzare il percorso. Il valore DEVE appartenere all'enumerazione RegionMode (sezione 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il modo di utilizzare il percorso. Il valore DEVE appartenere all'enumerazione RegionMode (sezione 2.1.29).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

