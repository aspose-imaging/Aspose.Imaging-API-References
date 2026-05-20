---
title: "XmpRdfRoot"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt das rdfRDF-Element dar."
type: docs
weight: 22
url: /de/java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Stellt das rdf:RDF-Element dar. Ein einzelnes XMP-Paket muss mit einem einzelnen rdf:RDF-XML-Element serialisiert werden. Der Inhalt des rdf:RDF-Elements darf nur null oder mehr rdf:Description-Elemente enthalten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Initialisiert eine neue Instanz der Klasse `XmpRdfRoot`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Fügt den Namespace-URI anhand des Präfixes hinzu. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Liest den Namespace-URI anhand eines bestimmten Präfixes. |
| [getXmlValue()](#getXmlValue--) | Konvertiert den xmp-Wert in die XML-Darstellung. |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Initialisiert eine neue Instanz der Klasse `XmpRdfRoot`.

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Fügt den Namespace-URI anhand des Präfixes hinzu. Das Präfix kann ohne xmlns beginnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Präfix | java.lang.String | Das Präfix. |
| namespaceUri | java.lang.String | Paket‑Schema‑URI. |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Liest den Namespace-URI anhand eines bestimmten Präfixes. Das Präfix kann ohne xmlns beginnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Präfix | java.lang.String | Das Präfix. |

**Returns:**
java.lang.String - Gibt einen Paket-Schema-URI zurück.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertiert den xmp-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den XMP-Wert als XML-Zeichenfolge zurück.
