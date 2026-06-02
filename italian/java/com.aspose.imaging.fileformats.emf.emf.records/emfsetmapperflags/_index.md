---
title: "EmfSetMapperFlags"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETMAPPERFLAGS specifica i parametri del processo di associazione dei caratteri logici a quelli fisici, eseguito dal mapper dei caratteri."
type: docs
weight: 131
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetMapperFlags extends EmfStateRecordType
```

Il record EMR\_SETMAPPERFLAGS specifica i parametri del processo di associazione dei font logici a quelli fisici, eseguito dal mapper dei font.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetMapperFlags(EmfRecord source)](#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetMapperFlags`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFlags()](#getFlags--) | Ottiene o imposta un intero senza segno a 32 bit che specifica i parametri del processo di associazione dei caratteri. |
| [setFlags(int value)](#setFlags-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica i parametri del processo di associazione dei caratteri. |
### EmfSetMapperFlags(EmfRecord source) {#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetMapperFlags(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetMapperFlags`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica i parametri del processo di associazione dei caratteri.

0x00000001 Il mapper dei caratteri DEVE selezionare solo i caratteri che corrispondono al rapporto d'aspetto del dispositivo di output, come attualmente definito nel contesto del dispositivo di riproduzione.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica i parametri del processo di associazione dei caratteri.

0x00000001 Il mapper dei caratteri DEVE selezionare solo i caratteri che corrispondono al rapporto d'aspetto del dispositivo di output, come attualmente definito nel contesto del dispositivo di riproduzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

