---
title: "EmfPlusClear"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusClear cancella lo spazio delle coordinate di output e lo inizializza con un colore di sfondo e trasparenza."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusClear extends EmfPlusDrawingRecordType
```

Il record EmfPlusClear cancella lo spazio delle coordinate di output e lo inizializza con un colore di sfondo e trasparenza.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusClear(EmfPlusRecord source)](#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusClear`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getArgb32Color()](#getArgb32Color--) | Ottiene o imposta il colore. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Ottiene o imposta il colore. |
### EmfPlusClear(EmfPlusRecord source) {#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusClear(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusClear`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Ottiene o imposta il colore. Un oggetto EmfPlusARGB (sezione 2.2.2.1) che definisce il colore da utilizzare per dipingere lo schermo. Tutti i colori sono specificati in [IEC-RGB], salvo diversa indicazione.

Valore: Il colore.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Ottiene o imposta il colore. Un oggetto EmfPlusARGB (sezione 2.2.2.1) che definisce il colore da utilizzare per dipingere lo schermo. Tutti i colori sono specificati in [IEC-RGB], salvo diversa indicazione.

Valore: Il colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

