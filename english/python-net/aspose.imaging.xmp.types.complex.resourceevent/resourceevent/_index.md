---
title: ResourceEvent Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---

Containing dimensions for a drawn object.

**Module:** [aspose.imaging.xmp.types.complex.resourceevent](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceevent/)

**Full Name:** aspose.imaging.xmp.types.complex.resourceevent.ResourceEvent

**Inheritance:** IXmpType, ComplexTypeBase

**Aspose.Imaging Version:** 23.6

The ResourceEvent type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [ResourceEvent()](#ResourceEvent__0) | Initializes a new instance of the [ResourceEvent](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceevent/resourceevent/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| prefix | string | r | Gets the prefix. |
| namespace_uri | string | r | Gets the default namespace URI. |
| action | string | r/w | Gets or sets action. |
| changed | string | r/w | Gets or sets the semicolon-delimited list of the parts of the resource that were changed since the previous event history. |
| instance_id | Guid | r/w | Gets or sets value of the xmpMM:InstanceId. |
| parameters | string | r/w | Gets or sets the additional description of the action. |
| sofware_agent_name | string | r/w | Gets or sets the software agent name. |
| action_date | datetime | r/w | Gets or sets the action date. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | Gets the string contained value in XMP format. |

### ResourceEvent() {#ResourceEvent__0}


```
 ResourceEvent() 
```

Initializes a new instance of the [ResourceEvent](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceevent/resourceevent/) class.

### get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

Gets the string contained value in XMP format.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the string contained value in XMP format. |


