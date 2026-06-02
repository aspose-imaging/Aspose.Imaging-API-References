---
title: "EmfExtCreateFontIndirectW"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_EXTCREATEFONTINDIRECTW definisce un font logico per le operazioni grafiche."
type: docs
weight: 51
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreateFontIndirectW extends EmfObjectCreationRecordType
```

Il record EMR\_EXTCREATEFONTINDIRECTW definisce un carattere logico per le operazioni grafiche.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfExtCreateFontIndirectW(EmfRecord source)](#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfExtCreateFontIndirectW`. |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW--) | Inizializza una nuova istanza della classe `EmfExtCreateFontIndirectW`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhFonts()](#getIhFonts--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto font logico nella EMF Object Table (sezione 3.1.1.1). |
| [setIhFonts(int value)](#setIhFonts-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto font logico nella EMF Object Table (sezione 3.1.1.1). |
| [getElw()](#getElw--) | Ottiene o imposta un oggetto LogFontExDv (sezione 2.2.15), che specifica il font logico. |
| [setElw(EmfLogFont value)](#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Ottiene o imposta un oggetto LogFontExDv (sezione 2.2.15), che specifica il font logico. |
### EmfExtCreateFontIndirectW(EmfRecord source) {#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreateFontIndirectW(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfExtCreateFontIndirectW`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW--}
```
public EmfExtCreateFontIndirectW()
```


Inizializza una nuova istanza della classe `EmfExtCreateFontIndirectW`.

### getIhFonts() {#getIhFonts--}
```
public int getIhFonts()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto font logico nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Returns:**
int
### setIhFonts(int value) {#setIhFonts-int-}
```
public void setIhFonts(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto font logico nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getElw() {#getElw--}
```
public EmfLogFont getElw()
```


Ottiene o imposta un oggetto LogFontExDv (sezione 2.2.15), che specifica il font logico. Un oggetto LogFont 2.2.13 PUÒ essere presente invece.[90]Il processo per determinare il tipo di oggetto in questo campo è descritto di seguito.

**Returns:**
[EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
### setElw(EmfLogFont value) {#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public void setElw(EmfLogFont value)
```


Ottiene o imposta un oggetto LogFontExDv (sezione 2.2.15), che specifica il font logico. Un oggetto LogFont 2.2.13 PUÒ essere presente invece.[90]Il processo per determinare il tipo di oggetto in questo campo è descritto di seguito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) |  |

