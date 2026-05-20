---
title: "XmpRdfRoot"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente l'élément rdfRDF."
type: docs
weight: 22
url: /fr/java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Représente l'élément rdf:RDF. Un seul paquet XMP doit être sérialisé en utilisant un seul élément XML rdf:RDF. Le contenu de l'élément rdf:RDF doit se composer de zéro ou plusieurs éléments rdf:Description.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Initialise une nouvelle instance de la classe `XmpRdfRoot`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Ajoute l'URI de l'espace de noms par préfixe. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Obtient l'URI de l'espace de noms par un préfixe spécifique. |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur xmp en représentation xml. |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Initialise une nouvelle instance de la classe `XmpRdfRoot`.

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Ajoute l'URI de l'espace de noms par préfixe. Le préfixe peut commencer sans xmlns.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| préfixe | java.lang.String | Le préfixe. |
| namespaceUri | java.lang.String | URI du schéma du paquet. |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Obtient l'URI de l'espace de noms par un préfixe spécifique. Le préfixe peut commencer sans xmlns.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| préfixe | java.lang.String | Le préfixe. |

**Returns:**
java.lang.String - Retourne l'URI du schéma du package.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convertit la valeur xmp en représentation xml.

**Returns:**
java.lang.String - Retourne la valeur XMP convertie en chaîne XML.
