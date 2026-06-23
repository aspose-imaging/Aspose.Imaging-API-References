---
title: "XmpRdfRoot"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل العنصر rdfRDF."
type: docs
weight: 22
url: /ar/java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging/xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

يمثل العنصر rdf:RDF. يجب تسلسل حزمة XMP واحدة باستخدام عنصر XML rdf:RDF واحد. يجب أن يتكون محتوى عنصر rdf:RDF من صفر أو أكثر من عناصر rdf:Description فقط.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | ينشئ مثيلاً جديداً من الفئة `XmpRdfRoot`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | يضيف URI للمساحة الاسمية باستخدام البادئة. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | يحصل على URI للمساحة الاسمية باستخدام بادئة محددة. |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة xmp إلى تمثيل xml. |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


ينشئ مثيلاً جديداً من الفئة `XmpRdfRoot`.

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


يضيف URI للمساحة الاسمية باستخدام البادئة. قد تبدأ البادئة بدون xmlns.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السابقة | java.lang.String | السابقة. |
| namespaceUri | java.lang.String | مسار مخطط الحزمة. |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


يحصل على URI للمساحة الاسمية باستخدام بادئة محددة. قد تبدأ البادئة بدون xmlns.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السابقة | java.lang.String | السابقة. |

**Returns:**
java.lang.String - إرجاع URI لمخطط الحزمة.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يحوّل قيمة xmp إلى تمثيل xml.

**Returns:**
java.lang.String - إرجاع قيمة XMP محوّلة إلى سلسلة XML.
