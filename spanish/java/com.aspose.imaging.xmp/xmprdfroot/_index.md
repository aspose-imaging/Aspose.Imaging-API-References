---
title: "XmpRdfRoot"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el elemento rdfRDF."
type: docs
weight: 22
url: /es/java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Representa el elemento rdf:RDF. Un solo paquete XMP debe serializarse usando un único elemento XML rdf:RDF. El contenido del elemento rdf:RDF debe consistir en cero o más elementos rdf:Description.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Inicializa una nueva instancia de la clase `XmpRdfRoot`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Agrega la URI del espacio de nombres por prefijo. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Obtiene la URI del espacio de nombres por un prefijo específico. |
| [getXmlValue()](#getXmlValue--) | Convierte el valor xmp a la representación xml. |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Inicializa una nueva instancia de la clase `XmpRdfRoot`.

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Agrega la URI del espacio de nombres por prefijo. El prefijo puede comenzar sin xmlns.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | java.lang.String | El prefijo. |
| namespaceUri | java.lang.String | URI del esquema del paquete. |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Obtiene la URI del espacio de nombres por un prefijo específico. El prefijo puede comenzar sin xmlns.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | java.lang.String | El prefijo. |

**Returns:**
java.lang.String - Devuelve la URI del esquema del paquete.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convierte el valor xmp a la representación xml.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a cadena XML.
