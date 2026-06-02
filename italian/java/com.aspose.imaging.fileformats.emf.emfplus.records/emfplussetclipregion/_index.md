---
title: "EmfPlusSetClipRegion"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSetClipRegion combina la regione di ritaglio corrente con un'altra regione grafica."
type: docs
weight: 57
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRegion extends EmfPlusClippingRecordType
```

Il record EmfPlusSetClipRegion combina la regione di ritaglio corrente con un'altra regione grafica. La nuova regione di ritaglio corrente è impostata sul risultato dell'operazione CombineMode eseguita sulla precedente regione di ritaglio corrente e sull'oggetto EmfPlusRegion specificato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSetClipRegion(EmfPlusRecord source)](#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSetClipRegion`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCm()](#getCm--) | Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. |
| [setCm(byte value)](#setCm-byte-) | Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'indice di un oggetto EmfPlusRegion (sezione 2.2.1.8) nella tabella degli oggetti EMF+. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'indice di un oggetto EmfPlusRegion (sezione 2.2.1.8) nella tabella degli oggetti EMF+. Il valore DEVE essere compreso tra 0 e 63, inclusi. |
### EmfPlusSetClipRegion(EmfPlusRecord source) {#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRegion(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSetClipRegion`.

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


Ottiene o imposta l'indice di un oggetto EmfPlusRegion (sezione 2.2.1.8) nella tabella degli oggetti EMF+. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'indice di un oggetto EmfPlusRegion (sezione 2.2.1.8) nella tabella degli oggetti EMF+. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

