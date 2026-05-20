---
title: "EmfPlusSetClipPath"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSetClipPath combina la regione di ritaglio corrente con un percorso grafico."
type: docs
weight: 55
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipPath extends EmfPlusClippingRecordType
```

Il record EmfPlusSetClipPath combina la regione di ritaglio corrente con un percorso grafico. La nuova regione di ritaglio corrente è impostata sul risultato dell'operazione CombineMode.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSetClipPath(EmfPlusRecord source)](#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSetClipPath`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCm()](#getCm--) | Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. |
| [setCm(byte value)](#setCm-byte-) | Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'indice di un oggetto EmfPlusPath (sezione 2.2.1.6) nella EMF+ Object Table. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'indice di un oggetto EmfPlusPath (sezione 2.2.1.6) nella EMF+ Object Table. |
### EmfPlusSetClipPath(EmfPlusRecord source) {#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipPath(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSetClipPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getCm() {#getCm--}
```
public byte getCm()
```


Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. Vedere l'enumerazione CombineMode (sezione 2.1.1.4) per il significato dei valori.

Valore: Il cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. Vedere l'enumerazione CombineMode (sezione 2.1.1.4) per il significato dei valori.

Valore: Il cm.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'indice di un oggetto EmfPlusPath (sezione 2.2.1.6) nella EMF+ Object Table. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'indice di un oggetto EmfPlusPath (sezione 2.2.1.6) nella EMF+ Object Table. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

