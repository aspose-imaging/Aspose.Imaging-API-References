---
title: "GuidPacketRepresentation"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La version du paquet est utilisée dans les protocoles de bloc."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class GuidPacketRepresentation extends Struct<GuidPacketRepresentation>
```

La version du paquet est utilisée dans les protocoles de blocs. Le diagramme suivant représente un GUID comme une séquence opaque d'octets. Un GUID, également appelé UUID, est une structure de 16 octets, destinée à servir d'identifiant unique pour un objet. Il existe trois représentations d'un GUID, comme décrit dans les sections suivantes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GuidPacketRepresentation()](#GuidPacketRepresentation--) |  |
| [GuidPacketRepresentation(int data1, short data2, short data3, long data4)](#GuidPacketRepresentation-int-short-short-long-) | Initialise une nouvelle instance de la structure `GuidPacketRepresentation`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getData1()](#getData1--) | Obtient ou définit la valeur du membre Data1 (section 2.3.4), en ordre d'octets little-endian. |
| [setData1(int value)](#setData1-int-) | Obtient ou définit la valeur du membre Data1 (section 2.3.4), en ordre d'octets little-endian. |
| [getData2()](#getData2--) | Obtient ou définit la valeur du membre Data2 (section 2.3.4), en ordre d'octets little-endian. |
| [setData2(short value)](#setData2-short-) | Obtient ou définit la valeur du membre Data2 (section 2.3.4), en ordre d'octets little-endian. |
| [getData3()](#getData3--) | Obtient ou définit la valeur du membre Data3 (section 2.3.4), en ordre d'octets little-endian. |
| [setData3(short value)](#setData3-short-) | Obtient ou définit la valeur du membre Data3 (section 2.3.4), en ordre d'octets little-endian. |
| [getData4()](#getData4--) | Obtient ou définit la valeur du membre Data4 (section 2.3.4), en ordre d'octets little-endian. |
| [setData4(long value)](#setData4-long-) | Obtient ou définit la valeur du membre Data4 (section 2.3.4), en ordre d'octets little-endian. |
| [toString()](#toString--) | Renvoie une `System.String` qui représente cette instance. |
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


Initialise une nouvelle instance de la structure `GuidPacketRepresentation`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data1 | int | Le data1. |
| data2 | short | Le data2. |
| data3 | short | Le data3. |
| data4 | long | Le data4. |

### getData1() {#getData1--}
```
public int getData1()
```


Obtient ou définit la valeur du membre Data1 (section 2.3.4), en ordre d'octets little-endian.

Valeur : Le data1.

**Returns:**
int
### setData1(int value) {#setData1-int-}
```
public void setData1(int value)
```


Obtient ou définit la valeur du membre Data1 (section 2.3.4), en ordre d'octets little-endian.

Valeur : Le data1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getData2() {#getData2--}
```
public short getData2()
```


Obtient ou définit la valeur du membre Data2 (section 2.3.4), en ordre d'octets little-endian.

Valeur : les data2.

**Returns:**
short
### setData2(short value) {#setData2-short-}
```
public void setData2(short value)
```


Obtient ou définit la valeur du membre Data2 (section 2.3.4), en ordre d'octets little-endian.

Valeur : les data2.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getData3() {#getData3--}
```
public short getData3()
```


Obtient ou définit la valeur du membre Data3 (section 2.3.4), en ordre d'octets little-endian.

Valeur : les data3.

**Returns:**
short
### setData3(short value) {#setData3-short-}
```
public void setData3(short value)
```


Obtient ou définit la valeur du membre Data3 (section 2.3.4), en ordre d'octets little-endian.

Valeur : les data3.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getData4() {#getData4--}
```
public long getData4()
```


Obtient ou définit la valeur du membre Data4 (section 2.3.4), en ordre d'octets little-endian.

Valeur : les data4.

**Returns:**
long
### setData4(long value) {#setData4-long-}
```
public void setData4(long value)
```


Obtient ou définit la valeur du membre Data4 (section 2.3.4), en ordre d'octets little-endian.

Valeur : les data4.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une `System.String` qui représente cette instance.

**Returns:**
java.lang.String - Une `System.String` qui représente cette instance.
### CloneTo(GuidPacketRepresentation that) {#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void CloneTo(GuidPacketRepresentation that)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2) {#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public static boolean isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |
| obj2 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

**Returns:**
boolean
