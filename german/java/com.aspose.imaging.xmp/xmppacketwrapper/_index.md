---
title: "XmpPacketWrapper"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Enthält ein serialisiertes XMP-Paket inklusive Header und Trailer."
type: docs
weight: 21
url: /de/java/com.aspose.imaging.xmp/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), [com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class XmpPacketWrapper implements IXmlValue, IImageMetadataFormat
```

Enthält ein serialisiertes XMP-Paket inklusive Header und Trailer.

Ein Wrapper, der aus einem Paar XML-Verarbeitungsanweisungen (PIs) besteht, kann um das rdf:RDF-Element gelegt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-) | Initialisiert eine neue Instanz der Klasse `XmpPacketWrapper`. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Initialisiert eine neue Instanz der Klasse `XmpPacketWrapper`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderPi()](#getHeaderPi--) | Liest die Header-Verarbeitungsanweisung. |
| [getMeta()](#getMeta--) | Liest die XMP-Metadaten. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.imaging.xmp.XmpMeta-) | Setzt die XMP-Metadaten. |
| [getTrailerPi()](#getTrailerPi--) | Liest die Trailer-Verarbeitungsanweisung. |
| [getPackages()](#getPackages--) | Liest das Array von `XmpPackage` innerhalb von XMP. |
| [getPackagesCount()](#getPackagesCount--) | Liest die Anzahl der Pakete innerhalb der XMP-Struktur. |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.imaging.xmp.XmpPackage-) | Fügt das Paket hinzu. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Ermittelt das Paket über die Namespace-URI. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Bestimmt, ob das Paket im XMP-Wrapper existiert. |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.imaging.xmp.XmpPackage-) | Entfernt das XMP-Paket. |
| [clearPackages()](#clearPackages--) | Entfernt alle `XmpPackage` innerhalb von XMP. |
| [getXmlValue()](#getXmlValue--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [toString()](#toString--) | Gibt eine XML-Zeichenkette zurück, die das aktuelle Objekt darstellt. |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Initialisiert eine neue Instanz der Klasse `XmpPacketWrapper`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | Der XMP-Header der Verarbeitungsanweisung. |
| trailer | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Der XMP-Trailer der Verarbeitungsanweisung. |
| xmpMeta | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Die XMP-Metadaten. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Initialisiert eine neue Instanz der Klasse `XmpPacketWrapper`.

### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Liest die Header-Verarbeitungsanweisung.

**Returns:**
[XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Liest die XMP-Metadaten. Optional.

**Returns:**
[XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) - The XMP meta. Optional.
### setMeta(XmpMeta value) {#setMeta-com.aspose.imaging.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Setzt die XMP-Metadaten. Optional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Die XMP-Metadaten. Optional. |

### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Liest die Trailer-Verarbeitungsanweisung.

**Returns:**
[XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) - Trailer processing instruction.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Liest das Array von `XmpPackage` innerhalb von XMP.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - Das Array von `XmpPackage` innerhalb von XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Liest die Anzahl der Pakete innerhalb der XMP-Struktur.

**Returns:**
int - Die Anzahl der Pakete innerhalb der XMP-Struktur.
### addPackage(XmpPackage package_) {#addPackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Fügt das Paket hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Das Paket. |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Ermittelt das Paket über die Namespace-URI.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| namespaceUri | java.lang.String | Die Paket‑Schema‑URI. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Bestimmt, ob das Paket im XMP-Wrapper existiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paket‑Schema‑URI. |

**Returns:**
boolean - Gibt true zurück, wenn ein Paket mit der angegebenen Namespace-URI im XMP-Wrapper existiert.
### removePackage(XmpPackage package_) {#removePackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Entfernt das XMP-Paket.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Das Paket. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Entfernt alle `XmpPackage` innerhalb von XMP.

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den konvertierten XMP-Wert als XML zurück.
### toString() {#toString--}
```
public String toString()
```


Gibt eine XML-Zeichenkette zurück, die das aktuelle Objekt darstellt.

**Returns:**
java.lang.String - Eine XML-Zeichenkette, die das aktuelle Objekt darstellt.
