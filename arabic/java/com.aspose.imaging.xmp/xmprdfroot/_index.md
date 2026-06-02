---
title: "XmpRdfRoot"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل عنصر rdfRDF."
type: docs
weight: 22
url: /ar/java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

يمثل عنصر rdf:RDF. يجب تسلسل حزمة XMP واحدة باستخدام عنصر XML rdf:RDF واحد. يجب أن يتكون محتوى عنصر rdf:RDF من صفر أو أكثر من عناصر rdf:Description فقط.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | يُنشئ مثلاً جديداً من الفئة `XmpRdfRoot` class. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | يضيف URI للمساحة الاسمية بالبادئة. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | يحصل على URI للمساحة الاسمية بالبادئة المحددة. |
| [getXmlValue()](#getXmlValue--) | يقوم بتحويل قيمة xmp إلى تمثيل xml. |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


يُنشئ مثلاً جديداً من الفئة `XmpRdfRoot` class.

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


يضيف URI للمساحة الاسمية بالبادئة. قد تبدأ البادئة بدون xmlns.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بادئة | java.lang.String | البادئة. |
| namespaceUri | java.lang.String | مخطط الحزمة uri. |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


يحصل على URI للمساحة الاسمية بالبادئة المحددة. قد تبدأ البادئة بدون xmlns.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بادئة | java.lang.String | البادئة. |

**Returns:**
java.lang.String - يُرجع URI لمخطط الحزمة.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يقوم بتحويل قيمة xmp إلى تمثيل xml.

**Returns:**
java.lang.String - يُرجع قيمة XMP محوّلة إلى سلسلة XML.
