---
title: "XmpCollection"
second_title: "Aspose.Imaging för Java API-referens"
description: "En XMP-elementsamling."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.xmp/xmpcollection/
---
**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype)
```
public class XmpCollection extends ArrayList<IXmpType> implements IXmpType
```

En XMP-elementsamling.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpCollection()](#XmpCollection--) | Initierar en ny instans av klassen [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addItem(Object item)](#addItem-java.lang.Object-) | Lägger till ett nytt objekt. |
| [addObject(Object item)](#addObject-java.lang.Object-) | Lägger till ett XMP-datapost. |
| [removeAt(int index)](#removeAt-int-) | Tar bort objektet på det angivna indexet. |
| [add(IXmpType item)](#add-com.aspose.imaging.xmp.types.IXmpType-) | Lägger till ett objekt i samlingen. |
| [copyTo(IXmpType[] array, int arrayIndex)](#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-) | Kopierar samlingens element till en array, med start vid ett specifikt array-index. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Hämtar XMP-strängvärdet för detta. |
| [getXmlValue()](#getXmlValue--) | Konverterar XMP-värde till XML-representationen. |
| [toString()](#toString--) | Returnerar en XML-sträng som representerar den här instansen. |
### XmpCollection() {#XmpCollection--}
```
public XmpCollection()
```


Initierar en ny instans av klassen [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection).

### addItem(Object item) {#addItem-java.lang.Object-}
```
public final void addItem(Object item)
```


Lägger till ett nytt objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | java.lang.Object | Objektet som ska läggas till i listan med objekt. |

### addObject(Object item) {#addObject-java.lang.Object-}
```
public final void addObject(Object item)
```


Lägger till ett XMP-datapost.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | java.lang.Object | Ett XMP‑objekt. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort objektet på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för objektet som ska tas bort. |

### add(IXmpType item) {#add-com.aspose.imaging.xmp.types.IXmpType-}
```
public final boolean add(IXmpType item)
```


Lägger till ett objekt i samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | Objektet som ska läggas till i samlingen. |

**Returns:**
boolean
### copyTo(IXmpType[] array, int arrayIndex) {#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-}
```
public final void copyTo(IXmpType[] array, int arrayIndex)
```


Kopierar samlingens element till en array, med start vid ett specifikt array-index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IXmpType\[\]](../../com.aspose.imaging.xmp.types/ixmptype) | Den endimensionella arrayen som är destinationen för elementen som kopierats från samlingen. Arrayen måste ha nollbaserad indexering. |
| arrayIndex | int | Det nollbaserade indexet i arrayen där kopieringen börjar. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Hämtar XMP-strängvärdet för detta.

**Returns:**
java.lang.String - Returnerar det stränginnehållande värdet i XMP-format.
### getXmlValue() {#getXmlValue--}
```
public final String getXmlValue()
```


Konverterar XMP-värde till XML-representationen.

**Returns:**
java.lang.String - Returnerar XMP‑värdet konverterat till XML-representationen.
### toString() {#toString--}
```
public String toString()
```


Returnerar en XML-sträng som representerar den här instansen.

**Returns:**
java.lang.String - En XML‑sträng som representerar detta objekt.
