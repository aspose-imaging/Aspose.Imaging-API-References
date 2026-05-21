---
title: "EmfPlusSerializableObject"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSerializableObject definisce un blocco di parametri di effetti immagine che è stato serializzato in un buffer di dati."
type: docs
weight: 53
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusSerializableObject extends EmfPlusObjectRecordType
```

Il record EmfPlusSerializableObject definisce un blocco di parametri di effetti immagine che è stato serializzato in un buffer di dati.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSerializableObject(EmfPlusRecord source)](#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSerializableObject`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFlags()](#getFlags--) | Ottiene o imposta un intero senza segno a 16 bit che non è utilizzato. |
| [setFlags(short value)](#setFlags-short-) | Ottiene o imposta un intero senza segno a 16 bit che non è utilizzato. |
| [getObjectGuid()](#getObjectGuid--) | Ottiene o imposta il valore di rappresentazione del pacchetto GUID ([MS-DTYP] sezione 2.3.4.2) per l'effetto immagine. |
| [setObjectGuid(GuidPacketRepresentation value)](#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) | Ottiene o imposta il valore di rappresentazione del pacchetto GUID ([MS-DTYP] sezione 2.3.4.2) per l'effetto immagine. |
| [getBufferSize()](#getBufferSize--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in byte del campo Buffer allineato a 32 bit. |
| [setBufferSize(int value)](#setBufferSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in byte del campo Buffer allineato a 32 bit. |
| [getBuffer()](#getBuffer--) | Ottiene o imposta un array di byte di dimensione BufferSize che contiene il blocco di parametri degli effetti immagine serializzati corrispondente al GUID nel campo ObjectGUID. |
| [setBuffer(byte[] value)](#setBuffer-byte---) | Ottiene o imposta un array di byte di dimensione BufferSize che contiene il blocco di parametri degli effetti immagine serializzati corrispondente al GUID nel campo ObjectGUID. |
| [getImageEffect()](#getImageEffect--) | Ottiene o imposta l'effetto immagine. |
| [setImageEffect(EmfPlusImageEffectsObjectType value)](#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-) | Ottiene o imposta l'effetto immagine. |
### EmfPlusSerializableObject(EmfPlusRecord source) {#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSerializableObject(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSerializableObject`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Ottiene o imposta un intero senza segno a 16 bit non utilizzato. Questo campo DOVREBBE essere impostato a zero e DEVE essere ignorato al ricevimento.

Valore: I flag.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Ottiene o imposta un intero senza segno a 16 bit non utilizzato. Questo campo DOVREBBE essere impostato a zero e DEVE essere ignorato al ricevimento.

Valore: I flag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getObjectGuid() {#getObjectGuid--}
```
public GuidPacketRepresentation getObjectGuid()
```


Ottiene o imposta il valore di rappresentazione del pacchetto GUID ([MS-DTYP] sezione 2.3.4.2) per l'effetto immagine. Questo DEVE corrispondere a uno degli identificatori ImageEffects (sezione 2.1.3.1).

**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### setObjectGuid(GuidPacketRepresentation value) {#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void setObjectGuid(GuidPacketRepresentation value)
```


Ottiene o imposta il valore di rappresentazione del pacchetto GUID ([MS-DTYP] sezione 2.3.4.2) per l'effetto immagine. Questo DEVE corrispondere a uno degli identificatori ImageEffects (sezione 2.1.3.1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### getBufferSize() {#getBufferSize--}
```
public int getBufferSize()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in byte del campo Buffer allineato a 32 bit.

**Returns:**
int
### setBufferSize(int value) {#setBufferSize-int-}
```
public void setBufferSize(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in byte del campo Buffer allineato a 32 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```


Ottiene o imposta un array di byte di dimensione BufferSize che contiene il blocco di parametri degli effetti immagine serializzati corrispondente al GUID nel campo ObjectGUID. Questo DEVE essere uno degli oggetti Image Effects (sezione 2.2.3).

**Returns:**
byte[]
### setBuffer(byte[] value) {#setBuffer-byte---}
```
public void setBuffer(byte[] value)
```


Ottiene o imposta un array di byte di dimensione BufferSize che contiene il blocco di parametri degli effetti immagine serializzati corrispondente al GUID nel campo ObjectGUID. Questo DEVE essere uno degli oggetti Image Effects (sezione 2.2.3).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getImageEffect() {#getImageEffect--}
```
public EmfPlusImageEffectsObjectType getImageEffect()
```


Ottiene o imposta l'effetto immagine.

Valore: L'effetto immagine.

**Returns:**
[EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
### setImageEffect(EmfPlusImageEffectsObjectType value) {#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-}
```
public void setImageEffect(EmfPlusImageEffectsObjectType value)
```


Ottiene o imposta l'effetto immagine.

Valore: L'effetto immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype) |  |

