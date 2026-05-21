---
title: "XmpRdfRoot"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar rdfRDF-elementet."
type: docs
weight: 22
url: /sv/java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Representerar rdf:RDF-elementet. Ett enskilt XMP-paket ska serialiseras med ett enda rdf:RDF XML-element. Innehållet i rdf:RDF-elementet får endast bestå av noll eller fler rdf:Description-element.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Initierar en ny instans av klassen `XmpRdfRoot`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Lägger till namnrymds-URI med prefix. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Hämtar namnrymds-URI med specifikt prefix. |
| [getXmlValue()](#getXmlValue--) | Konvertar xmp‑värde till xml‑representationen. |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Initierar en ny instans av klassen `XmpRdfRoot`.

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Lägger till namnrymds-URI med prefix. Prefix kan börja utan xmlns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | java.lang.String | Prefixet. |
| namespaceUri | java.lang.String | Paketets schemats uri. |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Hämtar namnrymds-URI med specifikt prefix. Prefix kan börja utan xmlns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | java.lang.String | Prefixet. |

**Returns:**
java.lang.String - Returnerar ett paket-schema-URI.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertar xmp‑värde till xml‑representationen.

**Returns:**
java.lang.String - Returnerar XMP-värde konverterat till XML-sträng.
