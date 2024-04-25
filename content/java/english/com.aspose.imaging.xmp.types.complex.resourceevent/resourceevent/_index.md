---
title: ResourceEvent
second_title: Aspose.Imaging for Java API Reference
description: Containing dimensions for a drawn object.
type: docs
weight: 10
url: /com.aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Containing dimensions for a drawn object.
## Constructors

| Constructor | Description |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Initializes a new instance of the `ResourceEvent` class. |
## Methods

| Method | Description |
| --- | --- |
| [getAction()](#getAction--) | Gets action. |
| [setAction(String value)](#setAction-java.lang.String-) | Sets action. |
| [getChanged()](#getChanged--) | Gets the semicolon-delimited list of the parts of the resource that were changed since the previous event history. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Sets the semicolon-delimited list of the parts of the resource that were changed since the previous event history. |
| [getInstanceId()](#getInstanceId--) | Gets value of the xmpMM:InstanceId. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Gets or sets value of the xmpMM:InstanceId. |
| [getParameters()](#getParameters--) | Gets or sets the additional description of the action. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Gets or sets the additional description of the action. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Gets or sets the software agent name. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Gets or sets the software agent name. |
| [getActionDate()](#getActionDate--) | Gets or sets the action date. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Gets or sets the action date. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the string contained value in XMP format. |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Initializes a new instance of the `ResourceEvent` class.

### getAction() {#getAction--}
```
public String getAction()
```


Gets action.

Defined values are: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. New values should be verbs in the past tense.

**Returns:**
java.lang.String - The action.
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Sets action.

Defined values are: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. New values should be verbs in the past tense.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The action. |

### getChanged() {#getChanged--}
```
public String getChanged()
```


Gets the semicolon-delimited list of the parts of the resource that were changed since the previous event history.

**Returns:**
java.lang.String - The semicolon-delimited list of the parts of the resource that were changed since the previous event history.
### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Sets the semicolon-delimited list of the parts of the resource that were changed since the previous event history.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The semicolon-delimited list of the parts of the resource that were changed since the previous event history. |

### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Gets value of the xmpMM:InstanceId.

**Returns:**
java.util.UUID - The value of the xmpMM:InstanceId.
### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Gets or sets value of the xmpMM:InstanceId.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID | The value of the xmpMM:InstanceId. |

### getParameters() {#getParameters--}
```
public String getParameters()
```


Gets or sets the additional description of the action.

Value: The additional description of the action.

**Returns:**
java.lang.String
### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Gets or sets the additional description of the action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The additional description of the action. |

### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Gets or sets the software agent name.

**Returns:**
java.lang.String - The software agent name.
### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Gets or sets the software agent name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The software agent name. |

### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Gets or sets the action date.

**Returns:**
java.util.Date - The action date.
### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Gets or sets the action date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The action date. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gets the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string contained value in XMP format.
