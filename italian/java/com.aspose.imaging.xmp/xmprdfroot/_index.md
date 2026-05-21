---
title: "XmpRdfRoot"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta l'elemento rdfRDF."
type: docs
weight: 22
url: /it/java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Rappresenta l'elemento rdf:RDF. Un singolo pacchetto XMP deve essere serializzato utilizzando un unico elemento XML rdf:RDF. Il contenuto dell'elemento rdf:RDF deve consistere solo di zero o più elementi rdf:Description.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Inizializza una nuova istanza della classe `XmpRdfRoot`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Aggiunge l'URI dello spazio dei nomi tramite prefisso. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Ottiene l'URI dello spazio dei nomi per un prefisso specifico. |
| [getXmlValue()](#getXmlValue--) | Converte il valore xmp nella rappresentazione xml. |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Inizializza una nuova istanza della classe `XmpRdfRoot`.

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Aggiunge l'URI dello spazio dei nomi tramite prefisso. Il prefisso può iniziare senza xmlns.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefisso | java.lang.String | Il prefisso. |
| namespaceUri | java.lang.String | URI dello schema del pacchetto. |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Ottiene l'URI dello spazio dei nomi per un prefisso specifico. Il prefisso può iniziare senza xmlns.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefisso | java.lang.String | Il prefisso. |

**Returns:**
java.lang.String - Restituisce l'URI dello schema del pacchetto.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converte il valore xmp nella rappresentazione xml.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito in stringa XML.
