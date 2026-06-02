---
title: "XmpPacketWrapper"
second_title: "Aspose.Imaging för Java API-referens"
description: "Innehåller serialiserat xmp‑paket inklusive header och trailer."
type: docs
weight: 21
url: /sv/java/com.aspose.imaging.xmp/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), [com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class XmpPacketWrapper implements IXmlValue, IImageMetadataFormat
```

Innehåller serialiserat xmp‑paket inklusive header och trailer.

En wrapper bestående av ett par XML‑processinstruktioner (PIs) kan placeras runt rdf:RDF‑elementet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-) | Initierar en ny instans av klassen `XmpPacketWrapper`. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Initierar en ny instans av klassen `XmpPacketWrapper`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderPi()](#getHeaderPi--) | Hämtar header‑processinstruktionen. |
| [getMeta()](#getMeta--) | Hämtar XMP‑metadata. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.imaging.xmp.XmpMeta-) | Ställer in XMP‑metadata. |
| [getTrailerPi()](#getTrailerPi--) | Hämtar trailer‑processinstruktionen. |
| [getPackages()](#getPackages--) | Hämtar array av `XmpPackage` i XMP. |
| [getPackagesCount()](#getPackagesCount--) | Hämtar antalet paket i XMP‑strukturen. |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.imaging.xmp.XmpPackage-) | Lägger till paketet. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Hämtar paketet via namnrymds-URI. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Bestämmer om paketet finns i XMP-omslaget. |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.imaging.xmp.XmpPackage-) | Tar bort XMP-paketet. |
| [clearPackages()](#clearPackages--) | Tar bort alla `XmpPackage` i XMP. |
| [getXmlValue()](#getXmlValue--) | Konverterar XMP-värde till XML-representationen. |
| [toString()](#toString--) | Returnerar en XML-sträng som representerar det aktuella objektet. |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Initierar en ny instans av klassen `XmpPacketWrapper`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | XMP-huvudet för bearbetningsinstruktionen. |
| trailer | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | XMP-slutet för bearbetningsinstruktionen. |
| xmpMeta | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | XMP-metadata. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Initierar en ny instans av klassen `XmpPacketWrapper`.

### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Hämtar header‑processinstruktionen.

**Returns:**
[XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Hämtar XMP-metadata. Valfritt.

**Returns:**
[XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) - The XMP meta. Optional.
### setMeta(XmpMeta value) {#setMeta-com.aspose.imaging.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Ställer in XMP-metadata. Valfritt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | XMP-metadata. Valfritt. |

### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Hämtar trailer‑processinstruktionen.

**Returns:**
[XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) - Trailer processing instruction.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Hämtar array av `XmpPackage` i XMP.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - Arrayen av `XmpPackage` i XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Hämtar antalet paket i XMP‑strukturen.

**Returns:**
int - Antalet paket i XMP-strukturen.
### addPackage(XmpPackage package_) {#addPackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Lägger till paketet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Paketet. |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Hämtar paketet via namnrymds-URI.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paketets schemats URI. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Bestämmer om paketet finns i XMP-omslaget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paketets schemats uri. |

**Returns:**
boolean - Returnerar true om paket med angivet namnrymds-URI finns i XMP-omslaget.
### removePackage(XmpPackage package_) {#removePackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Tar bort XMP-paketet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Paketet. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Tar bort alla `XmpPackage` i XMP.

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konverterar XMP-värde till XML-representationen.

**Returns:**
java.lang.String - Returnerar konverterat XMP-värde till XML.
### toString() {#toString--}
```
public String toString()
```


Returnerar en XML-sträng som representerar det aktuella objektet.

**Returns:**
java.lang.String - En XML-sträng som representerar det aktuella objektet.
