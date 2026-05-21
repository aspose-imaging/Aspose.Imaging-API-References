---
title: "XmpPackageBaseCollection"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Sammlung von XmpPackage dar."
type: docs
weight: 20
url: /de/java/com.aspose.imaging.xmp/xmppackagebasecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class XmpPackageBaseCollection implements System.Collections.Generic.IGenericEnumerable<XmpPackage>
```

Stellt eine Sammlung von `XmpPackage` dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection--) | Initialisiert eine neue Instanz der Klasse `XmpPackageBaseCollection`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Ermittelt die Anzahl der Elemente in der Sammlung. |
| [add(XmpPackage package_)](#add-com.aspose.imaging.xmp.XmpPackage-) | Fügt eine neue Instanz von `XmpPackage` hinzu. |
| [remove(XmpPackage package_)](#remove-com.aspose.imaging.xmp.XmpPackage-) | Entfernt das angegebene XMP-Paket. |
| [getPackages()](#getPackages--) | Gibt ein Array von `XmpPackage` zurück. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Ruft `XmpPackage` über seine namespaceURI ab. |
| [clear()](#clear--) | Löscht alle `XmpPackage` in der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch eine Sammlung iteriert. |
### XmpPackageBaseCollection() {#XmpPackageBaseCollection--}
```
public XmpPackageBaseCollection()
```


Initialisiert eine neue Instanz der Klasse `XmpPackageBaseCollection`.

### getCount() {#getCount--}
```
public int getCount()
```


Ermittelt die Anzahl der Elemente in der Sammlung.

Wert: Die Anzahl der Elemente in der Sammlung.

**Returns:**
int
### add(XmpPackage package_) {#add-com.aspose.imaging.xmp.XmpPackage-}
```
public void add(XmpPackage package_)
```


Fügt eine neue Instanz von `XmpPackage` hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Das XMP-Paket\_ zum Hinzufügen. |

### remove(XmpPackage package_) {#remove-com.aspose.imaging.xmp.XmpPackage-}
```
public void remove(XmpPackage package_)
```


Entfernt das angegebene XMP-Paket.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Das XMP-Paket\_ zum Entfernen. |

### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Gibt ein Array von `XmpPackage` zurück.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - Gibt ein Array von XMP-Paketen zurück.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Ruft `XmpPackage` über seine namespaceURI ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| namespaceUri | java.lang.String | Der Namespace-URI, um das Paket\_ zu erhalten. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns XMP package\_ for specified namespace Uri.
### clear() {#clear--}
```
public void clear()
```


Löscht alle `XmpPackage` in der Sammlung.

### iterator() {#iterator--}
```
public System.Collections.Generic.List.Enumerator<XmpPackage> iterator()
```


Gibt einen Enumerator zurück, der durch eine Sammlung iteriert.

**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<com.aspose.imaging.xmp.XmpPackage> - Ein `System.Collections.IEnumerator`-Objekt, das zum Durchlaufen der Sammlung verwendet werden kann.
