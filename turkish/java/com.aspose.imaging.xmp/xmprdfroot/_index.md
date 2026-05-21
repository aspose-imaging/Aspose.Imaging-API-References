---
title: "XmpRdfRoot"
second_title: "Aspose.Imaging for Java API Referansı"
description: "rdfRDF öğesini temsil eder."
type: docs
weight: 22
url: /tr/java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

rdf:RDF öğesini temsil eder. Tek bir XMP paketi, tek bir rdf:RDF XML öğesi kullanılarak serileştirilmelidir. rdf:RDF öğe içeriği yalnızca sıfır veya daha fazla rdf:Description öğesinden oluşmalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Yeni bir `XmpRdfRoot` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Önek ile ad alanı URI'si ekler. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Belirli bir önek ile ad alanı URI'sini alır. |
| [getXmlValue()](#getXmlValue--) | xmp değerini xml temsiline dönüştürür. |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Yeni bir `XmpRdfRoot` sınıfı örneği başlatır.

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Önek ile ad alanı URI'si ekler. Önek, xmlns olmadan başlayabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| önek | java.lang.String | Önek. |
| namespaceUri | java.lang.String | Paket şema uri'si. |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Belirli bir önek ile ad alanı URI'sini alır. Önek, xmlns olmadan başlayabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| önek | java.lang.String | Önek. |

**Returns:**
java.lang.String - Bir paket şema URI'si döndürür.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


xmp değerini xml temsiline dönüştürür.

**Returns:**
java.lang.String - XMP değerini XML dizesine dönüştürülmüş olarak döndürür.
