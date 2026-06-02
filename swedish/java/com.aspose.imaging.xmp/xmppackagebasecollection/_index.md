---
title: "XmpPackageBaseCollection"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en samling av XmpPackage."
type: docs
weight: 20
url: /sv/java/com.aspose.imaging.xmp/xmppackagebasecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class XmpPackageBaseCollection implements System.Collections.Generic.IGenericEnumerable<XmpPackage>
```

Representerar samling av `XmpPackage`.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection--) | Initierar en ny instans av klassen `XmpPackageBaseCollection`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Hämtar antalet element i samlingen. |
| [add(XmpPackage package_)](#add-com.aspose.imaging.xmp.XmpPackage-) | Lägger till en ny instans av `XmpPackage`. |
| [remove(XmpPackage package_)](#remove-com.aspose.imaging.xmp.XmpPackage-) | Tar bort det angivna XMP‑paketet. |
| [getPackages()](#getPackages--) | Hämta en array av `XmpPackage`. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Hämtar `XmpPackage` via dess namespaceURI. |
| [clear()](#clear--) | Rensa alla `XmpPackage` i samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom en samling. |
### XmpPackageBaseCollection() {#XmpPackageBaseCollection--}
```
public XmpPackageBaseCollection()
```


Initierar en ny instans av klassen `XmpPackageBaseCollection`.

### getCount() {#getCount--}
```
public int getCount()
```


Hämtar antalet element i samlingen.

Värde: Antalet element i samlingen.

**Returns:**
int
### add(XmpPackage package_) {#add-com.aspose.imaging.xmp.XmpPackage-}
```
public void add(XmpPackage package_)
```


Lägger till en ny instans av `XmpPackage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | XMP‑paketet\\_ att lägga till. |

### remove(XmpPackage package_) {#remove-com.aspose.imaging.xmp.XmpPackage-}
```
public void remove(XmpPackage package_)
```


Tar bort det angivna XMP‑paketet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | XMP‑paketet\\_ att ta bort. |

### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Hämta en array av `XmpPackage`.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - Returnerar en array av XMP‑paket.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Hämtar `XmpPackage` via dess namespaceURI.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceUri | java.lang.String | Namespace‑URI:n för att hämta paket\\_. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns XMP package\_ for specified namespace Uri.
### clear() {#clear--}
```
public void clear()
```


Rensa alla `XmpPackage` i samlingen.

### iterator() {#iterator--}
```
public System.Collections.Generic.List.Enumerator<XmpPackage> iterator()
```


Returnerar en enumerator som itererar genom en samling.

**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<com.aspose.imaging.xmp.XmpPackage> - Ett `System.Collections.IEnumerator`‑objekt som kan användas för att iterera genom samlingen.
