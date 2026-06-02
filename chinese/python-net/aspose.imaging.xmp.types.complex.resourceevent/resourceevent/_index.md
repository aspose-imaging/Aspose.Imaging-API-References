---
title: "ResourceEvent 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---

**Summary:** Containing dimensions for a drawn object.

**Module:** [aspose.imaging.xmp.types.complex.resourceevent](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceevent/)

**Full Name:** aspose.imaging.xmp.types.complex.resourceevent.ResourceEvent

**Inheritance:** IXmpType, ComplexTypeBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ResourceEvent()](#ResourceEvent__1) | 初始化一个新的 [ResourceEvent](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceevent/resourceevent/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| action | string | r/w | 获取或设置 action。 |
| action_date | System.DateTime | r/w | 获取或设置操作日期。 |
| changed | string | r/w | 获取或设置自上一次事件历史以来已更改的资源部分的分号分隔列表。 |
| instance_id | System.Guid | r/w | 获取或设置 xmpMM:InstanceId 的值。 |
| namespace_uri | string | r | 获取默认命名空间 URI。 |
| 参数 | string | r/w | 获取或设置操作的附加描述。 |
| prefix | string | r | 获取前缀。 |
| sofware_agent_name | string | r/w | 获取或设置软件代理的名称。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |
| [get_xmp_representation()](#get_xmp_representation__2) | 获取 XMP 格式中包含的字符串值。 |


### Constructor: ResourceEvent() {#ResourceEvent__1}


```
 ResourceEvent() 
```

初始化一个新的 [ResourceEvent](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceevent/resourceevent/) 类实例。

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| Type | Description |
| :- | :- |
| System.Object | 成员逐个克隆。 |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

获取 XMP 格式中包含的字符串值。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回 XMP 格式中包含的字符串值。 |


