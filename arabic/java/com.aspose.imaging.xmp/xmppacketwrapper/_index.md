---
title: "XmpPacketWrapper"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحتوي على حزمة XMP مُسلسلة تشمل الرأس والذيل."
type: docs
weight: 21
url: /ar/java/com.aspose.imaging.xmp/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), [com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class XmpPacketWrapper implements IXmlValue, IImageMetadataFormat
```

يحتوي على حزمة XMP مُسلسلة تشمل الرأس والذيل.

غلاف يتكوّن من زوج من تعليمات معالجة XML (PIs) يمكن وضعه حول عنصر rdf:RDF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-) | ينشئ مثيلاً جديدًا للفئة `XmpPacketWrapper`. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | ينشئ مثيلاً جديدًا للفئة `XmpPacketWrapper`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHeaderPi()](#getHeaderPi--) | يحصل على تعليمات معالجة الرأس. |
| [getMeta()](#getMeta--) | يحصل على بيانات XMP الوصفيّة. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.imaging.xmp.XmpMeta-) | يضبط بيانات XMP الوصفيّة. |
| [getTrailerPi()](#getTrailerPi--) | يحصل على تعليمات معالجة الذيل. |
| [getPackages()](#getPackages--) | يحصل على مصفوفة من `XmpPackage` داخل XMP. |
| [getPackagesCount()](#getPackagesCount--) | يحصل على عدد الحزم داخل بنية XMP. |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.imaging.xmp.XmpPackage-) | يضيف الحزمة. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | يحصل على الحزمة بواسطة مساحة الاسم URI. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | يحدد ما إذا كانت الحزمة موجودة في غلاف xmp. |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.imaging.xmp.XmpPackage-) | يزيل حزمة XMP. |
| [clearPackages()](#clearPackages--) | يزيل جميع `XmpPackage` داخل XMP. |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة XMP إلى تمثيل XML. |
| [toString()](#toString--) | يرجع سلسلة XML تمثل الكائن الحالي. |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


ينشئ مثيلاً جديدًا للفئة `XmpPacketWrapper`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | رأس XMP لتعليمات المعالجة. |
| trailer | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | ذيل XMP لتعليمات المعالجة. |
| xmpMeta | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | بيانات XMP الوصفية. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


ينشئ مثيلاً جديدًا للفئة `XmpPacketWrapper`.

### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


يحصل على تعليمات معالجة الرأس.

**Returns:**
[XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


يحصل على بيانات XMP الوصفية. اختياري.

**Returns:**
[XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) - The XMP meta. Optional.
### setMeta(XmpMeta value) {#setMeta-com.aspose.imaging.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


يضبط بيانات XMP الوصفية. اختياري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | بيانات XMP الوصفية. اختياري. |

### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


يحصل على تعليمات معالجة الذيل.

**Returns:**
[XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) - Trailer processing instruction.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


يحصل على مصفوفة من `XmpPackage` داخل XMP.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - مصفوفة `XmpPackage` داخل XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


يحصل على عدد الحزم داخل بنية XMP.

**Returns:**
int - عدد الحزم داخل بنية XMP.
### addPackage(XmpPackage package_) {#addPackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


يضيف الحزمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | الحزمة. |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


يحصل على الحزمة بواسطة مساحة الاسم URI.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI مخطط الحزمة. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


يحدد ما إذا كانت الحزمة موجودة في غلاف xmp.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| namespaceUri | java.lang.String | مخطط الحزمة uri. |

**Returns:**
boolean - يرجع true إذا كانت الحزمة ذات مساحة الاسم المحددة موجودة في غلاف XMP.
### removePackage(XmpPackage package_) {#removePackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


يزيل حزمة XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | الحزمة. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


يزيل جميع `XmpPackage` داخل XMP.

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يحوّل قيمة XMP إلى تمثيل XML.

**Returns:**
java.lang.String - يرجع قيمة XMP المحولة إلى XML.
### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة XML تمثل الكائن الحالي.

**Returns:**
java.lang.String - سلسلة XML تمثل الكائن الحالي.
