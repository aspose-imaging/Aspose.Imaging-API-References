---
title: "XmpRdfRoot فئة"
type: docs
weight: 490
url: /ar/python-net/aspose.imaging.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | يُنشئ مثيلاً جديداً من الفئة [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | يضيف السمة. |
| clear_attributes() | يزيل جميع السمات. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | يحصل على السمة. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | يحصل على URI للمساحة الاسمية بواسطة بادئة محددة. قد تبدأ البادئة بدون xmlns. |
| [get_xml_value()](#get_xml_value__4) | يحوّل قيمة xmp إلى تمثيل xml. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | يضيف URI للمساحة الاسمية بواسطة البادئة. قد تبدأ البادئة بدون xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

يُنشئ مثيلاً جديداً من الفئة [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/).

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

يضيف السمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| السمة | string | السمة. |
| القيمة | string | القيمة. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

يحصل على السمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| السمة | string | السمة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| string | يرجع السمة للاسم المحدد للخاصية. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

يحصل على URI للمساحة الاسمية بواسطة بادئة محددة. قد تبدأ البادئة بدون xmlns.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| prefix | string | البادئة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| string | يعيد URI لمخطط الحزمة. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

يحوّل قيمة xmp إلى تمثيل xml.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | يعيد قيمة XMP محوّلة إلى سلسلة XML. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

يضيف URI للمساحة الاسمية بواسطة البادئة. قد تبدأ البادئة بدون xmlns.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| prefix | string | البادئة. |
| namespace_uri | string | مسار مخطط الحزمة URI. |

