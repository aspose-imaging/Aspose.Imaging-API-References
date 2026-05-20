---
title: "XmpGuid"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل معرف XMP العالمي الفريد."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.xmp.types.derived/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

يمثل معرف XMP العالمي الفريد.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | يُنشئ مثيلاً جديدًا للفئة `XmpGuid`. |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | يُنشئ مثيلاً جديدًا للفئة `XmpGuid`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPrefix()](#getPrefix--) | يحصل أو يعيّن البادئة مثل uuid. |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | يحصل أو يعيّن البادئة مثل uuid. |
| [getValue()](#getValue--) | يحصل أو يضبط القيمة. |
| [setValue(UUID value)](#setValue-java.util.UUID-) | يحصل أو يضبط القيمة. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يحصل على القيمة النصية المحتواة بتنسيق XMP. |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


يُنشئ مثيلاً جديدًا للفئة `XmpGuid`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة. |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


يُنشئ مثيلاً جديدًا للفئة `XmpGuid`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| guid | java.util.UUID | المعرف الفريد. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


يحصل أو يعيّن البادئة مثل uuid.

القيمة: البادئة مثل uuid.

**Returns:**
java.lang.String
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


يحصل أو يعيّن البادئة مثل uuid.

القيمة: البادئة مثل uuid.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getValue() {#getValue--}
```
public UUID getValue()
```


يحصل أو يضبط القيمة.

القيمة: القيمة.

**Returns:**
java.util.UUID
### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


يحصل أو يضبط القيمة.

القيمة: القيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.UUID |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يحصل على القيمة النصية المحتواة بتنسيق XMP.

**Returns:**
java.lang.String - يُرجِع القيمة النصية المحتواة بتنسيق XMP.
