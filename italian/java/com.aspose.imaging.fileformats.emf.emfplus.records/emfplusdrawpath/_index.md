---
title: "EmfPlusDrawPath"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawPath specifica il disegno di un percorso grafico."
type: docs
weight: 25
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPath extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawPath specifica il disegno di un percorso grafico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawPath(EmfPlusRecord source)](#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawPath`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getPenId()](#getPenId--) | Ottiene o imposta l'identificatore della penna Un intero senza segno a 32 bit che specifica un indice nella EMF+ Object Table per un oggetto EmfPlusPen (sezione 2.2.1.7) da utilizzare per disegnare l'EmfPlusPath. |
| [setPenId(int value)](#setPenId-int-) | Ottiene o imposta l'identificatore della penna Un intero senza segno a 32 bit che specifica un indice nella EMF+ Object Table per un oggetto EmfPlusPen (sezione 2.2.1.7) da utilizzare per disegnare l'EmfPlusPath. |
### EmfPlusDrawPath(EmfPlusRecord source) {#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPath(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice dell'oggetto EmfPlusPath (sezione 2.2.1.6) da disegnare, nella EMF+ Object Table. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice dell'oggetto EmfPlusPath (sezione 2.2.1.6) da disegnare, nella EMF+ Object Table. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getPenId() {#getPenId--}
```
public int getPenId()
```


Ottiene o imposta l'identificatore della penna Un intero senza segno a 32 bit che specifica un indice nella EMF+ Object Table per un oggetto EmfPlusPen (sezione 2.2.1.7) da utilizzare per disegnare l'EmfPlusPath. Il valore DEVE essere compreso tra 0 e 63, inclusi.

**Returns:**
int
### setPenId(int value) {#setPenId-int-}
```
public void setPenId(int value)
```


Ottiene o imposta l'identificatore della penna Un intero senza segno a 32 bit che specifica un indice nella EMF+ Object Table per un oggetto EmfPlusPen (sezione 2.2.1.7) da utilizzare per disegnare l'EmfPlusPath. Il valore DEVE essere compreso tra 0 e 63, inclusi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

