---
title: "GuidPacketRepresentation"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La versione del pacchetto è utilizzata nei protocolli a blocchi."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class GuidPacketRepresentation extends Struct<GuidPacketRepresentation>
```

La versione del pacchetto è utilizzata nei protocolli a blocchi. Il diagramma seguente rappresenta un GUID come una sequenza opaca di byte. Un GUID, noto anche come UUID, è una struttura di 16 byte, destinata a fungere da identificatore univoco per un oggetto. Esistono tre rappresentazioni di un GUID, come descritto nelle sezioni seguenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GuidPacketRepresentation()](#GuidPacketRepresentation--) |  |
| [GuidPacketRepresentation(int data1, short data2, short data3, long data4)](#GuidPacketRepresentation-int-short-short-long-) | Inizializza una nuova istanza della struct `GuidPacketRepresentation`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getData1()](#getData1--) | Ottiene o imposta il valore del membro Data1 (sezione 2.3.4), in ordine di byte little-endian. |
| [setData1(int value)](#setData1-int-) | Ottiene o imposta il valore del membro Data1 (sezione 2.3.4), in ordine di byte little-endian. |
| [getData2()](#getData2--) | Ottiene o imposta il valore del membro Data2 (sezione 2.3.4), in ordine di byte little-endian. |
| [setData2(short value)](#setData2-short-) | Ottiene o imposta il valore del membro Data2 (sezione 2.3.4), in ordine di byte little-endian. |
| [getData3()](#getData3--) | Ottiene o imposta il valore del membro Data3 (sezione 2.3.4), in ordine di byte little-endian. |
| [setData3(short value)](#setData3-short-) | Ottiene o imposta il valore del membro Data3 (sezione 2.3.4), in ordine di byte little-endian. |
| [getData4()](#getData4--) | Ottiene o imposta il valore del membro Data4 (sezione 2.3.4), in ordine di byte little-endian. |
| [setData4(long value)](#setData4-long-) | Ottiene o imposta il valore del membro Data4 (sezione 2.3.4), in ordine di byte little-endian. |
| [toString()](#toString--) | Restituisce una `System.String` che rappresenta questa istanza. |
| [CloneTo(GuidPacketRepresentation that)](#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) |  |
| [Clone()](#Clone--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)](#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) |  |
### GuidPacketRepresentation() {#GuidPacketRepresentation--}
```
public GuidPacketRepresentation()
```


### GuidPacketRepresentation(int data1, short data2, short data3, long data4) {#GuidPacketRepresentation-int-short-short-long-}
```
public GuidPacketRepresentation(int data1, short data2, short data3, long data4)
```


Inizializza una nuova istanza della struct `GuidPacketRepresentation`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data1 | int | Il data1. |
| data2 | short | Il data2. |
| data3 | short | Il data3. |
| data4 | long | Il data4. |

### getData1() {#getData1--}
```
public int getData1()
```


Ottiene o imposta il valore del membro Data1 (sezione 2.3.4), in ordine di byte little-endian.

Valore: Il data1.

**Returns:**
int
### setData1(int value) {#setData1-int-}
```
public void setData1(int value)
```


Ottiene o imposta il valore del membro Data1 (sezione 2.3.4), in ordine di byte little-endian.

Valore: Il data1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getData2() {#getData2--}
```
public short getData2()
```


Ottiene o imposta il valore del membro Data2 (sezione 2.3.4), in ordine di byte little-endian.

Valore: i dati2.

**Returns:**
short
### setData2(short value) {#setData2-short-}
```
public void setData2(short value)
```


Ottiene o imposta il valore del membro Data2 (sezione 2.3.4), in ordine di byte little-endian.

Valore: i dati2.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getData3() {#getData3--}
```
public short getData3()
```


Ottiene o imposta il valore del membro Data3 (sezione 2.3.4), in ordine di byte little-endian.

Valore: i dati3.

**Returns:**
short
### setData3(short value) {#setData3-short-}
```
public void setData3(short value)
```


Ottiene o imposta il valore del membro Data3 (sezione 2.3.4), in ordine di byte little-endian.

Valore: i dati3.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getData4() {#getData4--}
```
public long getData4()
```


Ottiene o imposta il valore del membro Data4 (sezione 2.3.4), in ordine di byte little-endian.

Valore: i dati4.

**Returns:**
long
### setData4(long value) {#setData4-long-}
```
public void setData4(long value)
```


Ottiene o imposta il valore del membro Data4 (sezione 2.3.4), in ordine di byte little-endian.

Valore: i dati4.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una `System.String` che rappresenta questa istanza.

**Returns:**
java.lang.String - Una `System.String` che rappresenta questa istanza.
### CloneTo(GuidPacketRepresentation that) {#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void CloneTo(GuidPacketRepresentation that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### Clone() {#Clone--}
```
public GuidPacketRepresentation Clone()
```




**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2) {#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public static boolean isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |
| obj2 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

**Returns:**
boolean
