---
title: "XmpCollection"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Una colección de elementos XMP."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.xmp/xmpcollection/
---
**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype)
```
public class XmpCollection extends ArrayList<IXmpType> implements IXmpType
```

Una colección de elementos XMP.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpCollection()](#XmpCollection--) | Inicializa una nueva instancia de la clase [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection). |
## Métodos

| Método | Descripción |
| --- | --- |
| [addItem(Object item)](#addItem-java.lang.Object-) | Agrega un nuevo elemento. |
| [addObject(Object item)](#addObject-java.lang.Object-) | Agrega un elemento de datos XMP. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado. |
| [add(IXmpType item)](#add-com.aspose.imaging.xmp.types.IXmpType-) | Agrega un elemento a la colección. |
| [copyTo(IXmpType[] array, int arrayIndex)](#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-) | Copia los elementos de la colección a una matriz, comenzando en un índice de matriz específico. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtiene el valor de cadena XMP de esto. |
| [getXmlValue()](#getXmlValue--) | Convierte el valor XMP a la representación XML. |
| [toString()](#toString--) | Devuelve una cadena XML que representa esta instancia. |
### XmpCollection() {#XmpCollection--}
```
public XmpCollection()
```


Inicializa una nueva instancia de la clase [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection).

### addItem(Object item) {#addItem-java.lang.Object-}
```
public final void addItem(Object item)
```


Agrega un nuevo elemento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elemento | java.lang.Object | El elemento que se añadirá a la lista de elementos. |

### addObject(Object item) {#addObject-java.lang.Object-}
```
public final void addObject(Object item)
```


Agrega un elemento de datos XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elemento | java.lang.Object | Un elemento XMP. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina el elemento en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### add(IXmpType item) {#add-com.aspose.imaging.xmp.types.IXmpType-}
```
public final boolean add(IXmpType item)
```


Agrega un elemento a la colección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | El objeto que se añadirá a la colección. |

**Returns:**
boolean
### copyTo(IXmpType[] array, int arrayIndex) {#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-}
```
public final void copyTo(IXmpType[] array, int arrayIndex)
```


Copia los elementos de la colección a una matriz, comenzando en un índice de matriz específico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [IXmpType\[\]](../../com.aspose.imaging.xmp.types/ixmptype) | El arreglo unidimensional que es el destino de los elementos copiados de la colección. El arreglo debe tener indexación basada en cero. |
| arrayIndex | int | El índice basado en cero en el arreglo donde comienza la copia. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Obtiene el valor de cadena XMP de esto.

**Returns:**
java.lang.String - Devuelve el valor de cadena contenido en formato XMP.
### getXmlValue() {#getXmlValue--}
```
public final String getXmlValue()
```


Convierte el valor XMP a la representación XML.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a la representación XML.
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena XML que representa esta instancia.

**Returns:**
java.lang.String - Una cadena XML que representa esta instancia.
