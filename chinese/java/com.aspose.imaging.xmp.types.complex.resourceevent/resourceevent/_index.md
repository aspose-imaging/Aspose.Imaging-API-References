---
title: "ResourceEvent"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "包含已绘制对象的尺寸。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

包含已绘制对象的尺寸。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | 初始化 `ResourceEvent` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAction()](#getAction--) | 获取动作。 |
| [setAction(String value)](#setAction-java.lang.String-) | 设置动作。 |
| [getChanged()](#getChanged--) | 获取自上一次事件历史以来已更改的资源部分的分号分隔列表。 |
| [setChanged(String value)](#setChanged-java.lang.String-) | 设置自上一次事件历史以来已更改的资源部分的分号分隔列表。 |
| [getInstanceId()](#getInstanceId--) | 获取 xmpMM:InstanceId 的值。 |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | 获取或设置 xmpMM:InstanceId 的值。 |
| [getParameters()](#getParameters--) | 获取或设置操作的附加描述。 |
| [setParameters(String value)](#setParameters-java.lang.String-) | 获取或设置操作的附加描述。 |
| [getSofwareAgentName()](#getSofwareAgentName--) | 获取或设置软件代理名称。 |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | 获取或设置软件代理名称。 |
| [getActionDate()](#getActionDate--) | 获取或设置操作日期。 |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | 获取或设置操作日期。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


初始化 `ResourceEvent` 类的新实例。

### getAction() {#getAction--}
```
public String getAction()
```


获取动作。

定义的值包括：converted、copied、created、cropped、edited、filtered、formatted、version\_updated、printed、published、managed、produced、resized、saved。新值应使用过去式动词。

**Returns:**
java.lang.String - 操作。
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


设置动作。

定义的值包括：converted、copied、created、cropped、edited、filtered、formatted、version\_updated、printed、published、managed、produced、resized、saved。新值应使用过去式动词。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 操作。 |

### getChanged() {#getChanged--}
```
public String getChanged()
```


获取自上一次事件历史以来已更改的资源部分的分号分隔列表。

**Returns:**
java.lang.String - 自上一次事件历史以来已更改的资源部分的分号分隔列表。
### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


设置自上一次事件历史以来已更改的资源部分的分号分隔列表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 自上一次事件历史以来已更改的资源部分的分号分隔列表。 |

### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


获取 xmpMM:InstanceId 的值。

**Returns:**
java.util.UUID - xmpMM:InstanceId 的值。
### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


获取或设置 xmpMM:InstanceId 的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID | xmpMM:InstanceId 的值。 |

### getParameters() {#getParameters--}
```
public String getParameters()
```


获取或设置操作的附加描述。

值：操作的附加描述。

**Returns:**
java.lang.String
### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


获取或设置操作的附加描述。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 操作的附加描述。 |

### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


获取或设置软件代理名称。

**Returns:**
java.lang.String - 软件代理名称。
### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


获取或设置软件代理名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 软件代理名称。 |

### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


获取或设置操作日期。

**Returns:**
java.util.Date - 操作日期。
### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


获取或设置操作日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 操作日期。 |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。
