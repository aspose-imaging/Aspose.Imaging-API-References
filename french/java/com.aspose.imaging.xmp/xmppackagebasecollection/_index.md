---
title: "XmpPackageBaseCollection"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une collection de XmpPackage."
type: docs
weight: 20
url: /fr/java/com.aspose.imaging.xmp/xmppackagebasecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class XmpPackageBaseCollection implements System.Collections.Generic.IGenericEnumerable<XmpPackage>
```

Représente une collection de `XmpPackage`.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection--) | Initialise une nouvelle instance de la classe `XmpPackageBaseCollection`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Obtient le nombre d'éléments dans la collection. |
| [add(XmpPackage package_)](#add-com.aspose.imaging.xmp.XmpPackage-) | Ajoute une nouvelle instance de `XmpPackage`. |
| [remove(XmpPackage package_)](#remove-com.aspose.imaging.xmp.XmpPackage-) | Supprime le package XMP spécifié. |
| [getPackages()](#getPackages--) | Obtient le tableau de `XmpPackage`. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Obtient `XmpPackage` par son namespaceURI. |
| [clear()](#clear--) | Efface tous les `XmpPackage` de la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt une collection. |
### XmpPackageBaseCollection() {#XmpPackageBaseCollection--}
```
public XmpPackageBaseCollection()
```


Initialise une nouvelle instance de la classe `XmpPackageBaseCollection`.

### getCount() {#getCount--}
```
public int getCount()
```


Obtient le nombre d'éléments dans la collection.

Valeur : le nombre d'éléments dans la collection.

**Returns:**
int
### add(XmpPackage package_) {#add-com.aspose.imaging.xmp.XmpPackage-}
```
public void add(XmpPackage package_)
```


Ajoute une nouvelle instance de `XmpPackage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Le package XMP\_ à ajouter. |

### remove(XmpPackage package_) {#remove-com.aspose.imaging.xmp.XmpPackage-}
```
public void remove(XmpPackage package_)
```


Supprime le package XMP spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Le package XMP\_ à supprimer. |

### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Obtient le tableau de `XmpPackage`.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - Retourne un tableau de packages XMP.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Obtient `XmpPackage` par son namespaceURI.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | Le namespace URI pour obtenir le package\_. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns XMP package\_ for specified namespace Uri.
### clear() {#clear--}
```
public void clear()
```


Efface tous les `XmpPackage` de la collection.

### iterator() {#iterator--}
```
public System.Collections.Generic.List.Enumerator<XmpPackage> iterator()
```


Renvoie un énumérateur qui parcourt une collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<com.aspose.imaging.xmp.XmpPackage> - Un objet `System.Collections.IEnumerator` qui peut être utilisé pour parcourir la collection.
