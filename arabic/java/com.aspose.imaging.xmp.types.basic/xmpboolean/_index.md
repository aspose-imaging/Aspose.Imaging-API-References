---
title: "XmpBoolean"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل النوع الأساسي Boolean في XMP."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.xmp.types.basic/xmpboolean/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpBoolean extends XmpTypeBase
```

يمثل النوع الأساسي Boolean في XMP.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpBoolean(boolean value)](#XmpBoolean-boolean-) | ينشئ مثيلاً جديداً من الفئة `XmpBoolean` بناءً على قيمة منطقية. |
| [XmpBoolean()](#XmpBoolean--) | يُنشئ مثيلاً جديدًا من الفئة `XmpBoolean` بالقيمة الافتراضية. |
| [XmpBoolean(String value)](#XmpBoolean-java.lang.String-) | يُنشئ مثيلاً جديدًا من الفئة `XmpBoolean`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValue()](#getValue--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `XmpBoolean` قيمة. |
| [setValue(boolean value)](#setValue-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `XmpBoolean` قيمة. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يرجع القيمة المحتواة كسلسلة بصيغة XMP. |
### XmpBoolean(boolean value) {#XmpBoolean-boolean-}
```
public XmpBoolean(boolean value)
```


ينشئ مثيلاً جديداً من الفئة `XmpBoolean` بناءً على قيمة منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | القيمة المنطقية. القيم المسموح بها هي True أو False. |

### XmpBoolean() {#XmpBoolean--}
```
public XmpBoolean()
```


يُنشئ مثيلاً جديدًا من الفئة `XmpBoolean` بالقيمة الافتراضية.

### XmpBoolean(String value) {#XmpBoolean-java.lang.String-}
```
public XmpBoolean(String value)
```


يُنشئ مثيلاً جديدًا من الفئة `XmpBoolean`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | القيمة. |

### getValue() {#getValue--}
```
public boolean getValue()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `XmpBoolean` قيمة.

القيمة: `true` إذا كانت القيمة؛ وإلا `false`.

**Returns:**
boolean
### setValue(boolean value) {#setValue-boolean-}
```
public void setValue(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `XmpBoolean` قيمة.

القيمة: `true` إذا كانت القيمة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يرجع القيمة المحتواة كسلسلة بصيغة XMP.

**Returns:**
java.lang.String - يُعيد سلسلة تحتوي على تمثيل xmp.
