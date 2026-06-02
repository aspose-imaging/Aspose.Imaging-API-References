---
title: "XmpCollection"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Una raccolta di elementi XMP."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.xmp/xmpcollection/
---
**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype)
```
public class XmpCollection extends ArrayList<IXmpType> implements IXmpType
```

Una raccolta di elementi XMP.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpCollection()](#XmpCollection--) | Inizializza una nuova istanza della classe [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addItem(Object item)](#addItem-java.lang.Object-) | Aggiunge un nuovo elemento. |
| [addObject(Object item)](#addObject-java.lang.Object-) | Aggiunge un elemento dati XMP. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato. |
| [add(IXmpType item)](#add-com.aspose.imaging.xmp.types.IXmpType-) | Aggiunge un elemento alla collezione. |
| [copyTo(IXmpType[] array, int arrayIndex)](#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-) | Copia gli elementi della collezione in un array, iniziando da un indice specifico dell'array. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Ottiene il valore stringa XMP di questo. |
| [getXmlValue()](#getXmlValue--) | Converte il valore XMP nella rappresentazione XML. |
| [toString()](#toString--) | Restituisce una stringa XML che rappresenta questa istanza. |
### XmpCollection() {#XmpCollection--}
```
public XmpCollection()
```


Inizializza una nuova istanza della classe [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection).

### addItem(Object item) {#addItem-java.lang.Object-}
```
public final void addItem(Object item)
```


Aggiunge un nuovo elemento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elemento | java.lang.Object | L'elemento da aggiungere all'elenco degli elementi. |

### addObject(Object item) {#addObject-java.lang.Object-}
```
public final void addObject(Object item)
```


Aggiunge un elemento dati XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elemento | java.lang.Object | Un elemento XMP. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove l'elemento all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice a base zero dell'elemento da rimuovere. |

### add(IXmpType item) {#add-com.aspose.imaging.xmp.types.IXmpType-}
```
public final boolean add(IXmpType item)
```


Aggiunge un elemento alla collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | L'oggetto da aggiungere alla raccolta. |

**Returns:**
boolean
### copyTo(IXmpType[] array, int arrayIndex) {#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-}
```
public final void copyTo(IXmpType[] array, int arrayIndex)
```


Copia gli elementi della collezione in un array, iniziando da un indice specifico dell'array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IXmpType\[\]](../../com.aspose.imaging.xmp.types/ixmptype) | L'array monodimensionale che è la destinazione degli elementi copiati dalla raccolta. L'array deve avere un indice basato su zero. |
| arrayIndex | int | L'indice basato su zero nell'array a partire dal quale inizia la copia. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Ottiene il valore stringa XMP di questo.

**Returns:**
java.lang.String - Restituisce il valore della stringa contenuta in formato XMP.
### getXmlValue() {#getXmlValue--}
```
public final String getXmlValue()
```


Converte il valore XMP nella rappresentazione XML.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito nella rappresentazione XML.
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa XML che rappresenta questa istanza.

**Returns:**
java.lang.String - Una stringa XML che rappresenta questa istanza.
