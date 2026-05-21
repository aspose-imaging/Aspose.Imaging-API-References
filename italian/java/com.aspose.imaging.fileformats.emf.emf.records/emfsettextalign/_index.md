---
title: "EmfSetTextAlign"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETTEXTALIGN specifica l'allineamento del testo."
type: docs
weight: 139
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextAlign extends EmfStateRecordType
```

Il record EMR\_SETTEXTALIGN specifica l'allineamento del testo.

I record EMR\_SMALLTEXTOUT, EMR\_EXTTEXTOUTA e EMR\_EXTTEXTOUTW usano i valori di allineamento del testo per posizionare una stringa di testo sul supporto di output. I valori specificano la relazione tra un punto di riferimento e un rettangolo che delimita il testo. Il punto di riferimento è sia la posizione corrente sia un punto passato a un record di output del testo. Il rettangolo che delimita il testo è formato dalle celle dei caratteri nella stringa di testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetTextAlign(EmfRecord source)](#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetTextAlign`. |
| [EmfSetTextAlign()](#EmfSetTextAlign--) | Inizializza una nuova istanza della classe `EmfSetTextAlign`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextAlignmentMode()](#getTextAlignmentMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'allineamento del testo usando una maschera di flag di allineamento del testo. |
| [setTextAlignmentMode(int value)](#setTextAlignmentMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'allineamento del testo usando una maschera di flag di allineamento del testo. |
### EmfSetTextAlign(EmfRecord source) {#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextAlign(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetTextAlign`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


Inizializza una nuova istanza della classe `EmfSetTextAlign`.

### getTextAlignmentMode() {#getTextAlignmentMode--}
```
public int getTextAlignmentMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'allineamento del testo usando una maschera di flag di allineamento del testo. Questi sono o `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] sezione 2.1.2.3) per testo con linea di base orizzontale, o `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] sezione 2.1.2.4) per testo con linea di base verticale. È possibile scegliere un solo valore tra quelli che influenzano l'allineamento orizzontale e verticale.

**Returns:**
int
### setTextAlignmentMode(int value) {#setTextAlignmentMode-int-}
```
public void setTextAlignmentMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'allineamento del testo usando una maschera di flag di allineamento del testo. Questi sono o `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] sezione 2.1.2.3) per testo con linea di base orizzontale, o `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] sezione 2.1.2.4) per testo con linea di base verticale. È possibile scegliere un solo valore tra quelli che influenzano l'allineamento orizzontale e verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

