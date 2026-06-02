---
title: "XmpCollection"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Une collection d'éléments XMP."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.xmp/xmpcollection/
---
**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype)
```
public class XmpCollection extends ArrayList<IXmpType> implements IXmpType
```

Une collection d'éléments XMP.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpCollection()](#XmpCollection--) | Initialise une nouvelle instance de la classe [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addItem(Object item)](#addItem-java.lang.Object-) | Ajoute un nouvel élément. |
| [addObject(Object item)](#addObject-java.lang.Object-) | Ajoute un élément de données XMP. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié. |
| [add(IXmpType item)](#add-com.aspose.imaging.xmp.types.IXmpType-) | Ajoute un élément à la collection. |
| [copyTo(IXmpType[] array, int arrayIndex)](#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-) | Copie les éléments de la collection dans un tableau, en commençant à un index de tableau particulier. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtient la valeur chaîne XMP de cet objet. |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur XMP en représentation XML. |
| [toString()](#toString--) | Renvoie une chaîne XML qui représente cette instance. |
### XmpCollection() {#XmpCollection--}
```
public XmpCollection()
```


Initialise une nouvelle instance de la classe [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection).

### addItem(Object item) {#addItem-java.lang.Object-}
```
public final void addItem(Object item)
```


Ajoute un nouvel élément.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| élément | java.lang.Object | L'élément à ajouter à la liste des éléments. |

### addObject(Object item) {#addObject-java.lang.Object-}
```
public final void addObject(Object item)
```


Ajoute un élément de données XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| élément | java.lang.Object | Un élément XMP. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Supprime l'élément à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### add(IXmpType item) {#add-com.aspose.imaging.xmp.types.IXmpType-}
```
public final boolean add(IXmpType item)
```


Ajoute un élément à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | L'objet à ajouter à la collection. |

**Returns:**
boolean
### copyTo(IXmpType[] array, int arrayIndex) {#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-}
```
public final void copyTo(IXmpType[] array, int arrayIndex)
```


Copie les éléments de la collection dans un tableau, en commençant à un index de tableau particulier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IXmpType\[\]](../../com.aspose.imaging.xmp.types/ixmptype) | Le tableau unidimensionnel qui est la destination des éléments copiés depuis la collection. Le tableau doit avoir une indexation à base zéro. |
| arrayIndex | int | L'index à base zéro dans le tableau où commence la copie. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Obtient la valeur chaîne XMP de cet objet.

**Returns:**
java.lang.String - Retourne la valeur de chaîne contenue au format XMP.
### getXmlValue() {#getXmlValue--}
```
public final String getXmlValue()
```


Convertit la valeur XMP en représentation XML.

**Returns:**
java.lang.String - Retourne la valeur XMP convertie en représentation XML.
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne XML qui représente cette instance.

**Returns:**
java.lang.String - Une chaîne XML qui représente cette instance.
