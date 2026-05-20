---
title: "ComplexTypeBase"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die Basisabstraktion für den XMP-Komplexwerttyp dar."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.xmp.types.complex/complextypebase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public class ComplexTypeBase extends XmpTypeBase
```

Stellt die Basisabstraktion für den XMP-Komplexwerttyp dar.

Siehe mehr: XMP Specification Part 2, Kapitel 1.2.2
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ComplexTypeBase(String prefix, String namespaceUri)](#ComplexTypeBase-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der `ComplexTypeBase`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPrefix()](#getPrefix--) | Ruft das Präfix ab. |
| [getNamespaceUri()](#getNamespaceUri--) | Gibt die Standard-Namespace-URI zurück. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den enthaltenen Zeichenfolgenwert im XMP‑Format. |
### ComplexTypeBase(String prefix, String namespaceUri) {#ComplexTypeBase-java.lang.String-java.lang.String-}
```
public ComplexTypeBase(String prefix, String namespaceUri)
```


Initialisiert eine neue Instanz der `ComplexTypeBase`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Präfix | java.lang.String | Das Präfix. |
| namespaceUri | java.lang.String | Die Namespace-URI. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ruft das Präfix ab.

**Returns:**
java.lang.String - das Präfix.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Gibt die Standard-Namespace-URI zurück.

**Returns:**
java.lang.String - die Standard-Namespace-URI.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Liest den enthaltenen Zeichenfolgenwert im XMP‑Format.

**Returns:**
java.lang.String - Gibt den im String enthaltenen Wert im XMP-Format zurück.
