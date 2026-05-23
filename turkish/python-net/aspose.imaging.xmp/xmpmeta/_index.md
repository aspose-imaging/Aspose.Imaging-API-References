---
title: "XmpMeta Sınıfı"
type: docs
weight: 440
url: /tr/python-net/aspose.imaging.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Yeni bir [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) sınıfının örneğini başlatır. |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Yeni bir [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Adobe Xmp araç takımı sürümünü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Özelliği ekler. |
| clear_attributes() | Tüm özellikleri kaldırır. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Özelliği alır. |
| [get_xml_value()](#get_xml_value__3) | XMP değerini XML temsiline dönüştürür. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Yeni bir [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) sınıfının örneğini başlatır.

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Yeni bir [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| toolkit_version | string | Adobe XMP araç takımı sürümü. |

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Özelliği ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| attribute | string | Özellik. |
| değer | string | Değer. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Özelliği alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| attribute | string | Özellik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Belirtilen özellik adı için özelliği döndürür. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

XMP değerini XML temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | XMP değerini XML temsiline dönüştürülmüş olarak döndürür. |


