---
title: "ResourceEvent"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحتوي على أبعاد لكائن مرسوم."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

يحتوي على أبعاد لكائن مرسوم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | يقوم بتهيئة نسخة جديدة من الفئة `ResourceEvent`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAction()](#getAction--) | يحصل على الإجراء. |
| [setAction(String value)](#setAction-java.lang.String-) | يضبط الإجراء. |
| [getChanged()](#getChanged--) | يحصل على القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الأحداث السابق. |
| [setChanged(String value)](#setChanged-java.lang.String-) | يضبط القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الأحداث السابق. |
| [getInstanceId()](#getInstanceId--) | يحصل على قيمة xmpMM:InstanceId. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | يحصل أو يضبط قيمة xmpMM:InstanceId. |
| [getParameters()](#getParameters--) | يحصل أو يضبط الوصف الإضافي للإجراء. |
| [setParameters(String value)](#setParameters-java.lang.String-) | يحصل أو يضبط الوصف الإضافي للإجراء. |
| [getSofwareAgentName()](#getSofwareAgentName--) | يحصل أو يضبط اسم وكيل البرنامج. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | يحصل أو يضبط اسم وكيل البرنامج. |
| [getActionDate()](#getActionDate--) | يحصل أو يضبط تاريخ الإجراء. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | يحصل أو يضبط تاريخ الإجراء. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يحصل على القيمة النصية المحتواة بتنسيق XMP. |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


يقوم بتهيئة نسخة جديدة من الفئة `ResourceEvent`.

### getAction() {#getAction--}
```
public String getAction()
```


يحصل على الإجراء.

القيم المعرفة هي: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. يجب أن تكون القيم الجديدة أفعالاً في صيغة الماضي.

**Returns:**
java.lang.String - الإجراء.
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


يضبط الإجراء.

القيم المعرفة هي: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. يجب أن تكون القيم الجديدة أفعالاً في صيغة الماضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | الإجراء. |

### getChanged() {#getChanged--}
```
public String getChanged()
```


يحصل على القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الأحداث السابق.

**Returns:**
java.lang.String - القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الأحداث السابق.
### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


يضبط القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الأحداث السابق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الأحداث السابق. |

### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


يحصل على قيمة xmpMM:InstanceId.

**Returns:**
java.util.UUID - قيمة xmpMM:InstanceId.
### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


يحصل أو يضبط قيمة xmpMM:InstanceId.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.UUID | قيمة xmpMM:InstanceId. |

### getParameters() {#getParameters--}
```
public String getParameters()
```


يحصل أو يضبط الوصف الإضافي للإجراء.

القيمة: الوصف الإضافي للإجراء.

**Returns:**
java.lang.String
### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


يحصل أو يضبط الوصف الإضافي للإجراء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | الوصف الإضافي للإجراء. |

### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


يحصل أو يضبط اسم وكيل البرنامج.

**Returns:**
java.lang.String - اسم وكيل البرنامج.
### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


يحصل أو يضبط اسم وكيل البرنامج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | اسم وكيل البرنامج. |

### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


يحصل أو يضبط تاريخ الإجراء.

**Returns:**
java.util.Date - تاريخ الإجراء.
### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


يحصل أو يضبط تاريخ الإجراء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Date | تاريخ الإجراء. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يحصل على القيمة النصية المحتواة بتنسيق XMP.

**Returns:**
java.lang.String - يُرجِع القيمة النصية المحتواة بتنسيق XMP.
