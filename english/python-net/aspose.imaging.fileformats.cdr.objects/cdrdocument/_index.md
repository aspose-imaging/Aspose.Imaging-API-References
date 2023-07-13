---
title: CdrDocument Class
type: docs
weight: 80
url: /python-net/aspose.imaging.fileformats.cdr.objects/cdrdocument/
---

The cdr root object

**Module:** [aspose.imaging.fileformats.cdr.objects](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/)

**Full Name:** aspose.imaging.fileformats.cdr.objects.CdrDocument

**Inheritance:** CdrObjectContainer

**Aspose.Imaging Version:** 23.6

The CdrDocument type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| parent | [CdrObjectContainer](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) | r/w | Gets or sets the parent. |
| document | [CdrDocument](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrdocument) | r/w | Gets or sets the document. |
| childs | System.Collections.Generic.List<CdrObject> | r | Gets or sets the objects. |
| load_to_last_child | bool | r/w | Gets or sets a value indicating whether [load to last child]. |
| last_child | [CdrObjectContainer](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) | r/w | Gets or sets the last child. |
| hidden | bool | r/w | Gets or sets a value indicating whether this [CdrObjectContainer](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer/) is visible. |
| texts | [CdrTextCollection](/imaging/python-net/aspose.imaging.fileformats.cdr.types/cdrtextcollection/) | r | Gets the texts. |
| clip_ids | System.Collections.Generic.List<short> | r/w | Gets or sets the clip ids. |
| last_text_index | int | r/w | Gets the text indexes. |
| version | int | r/w | Gets or sets the version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_child_object(cdr_object)](#add_child_object_cdr_object_0) | Adds the child object. |
| [insert_object(cdr_object)](#insert_object_cdr_object_1) | Inserts the object |

### add_child_object(cdr_object) {#add_child_object_cdr_object_0}


```
 add_child_object(cdr_object) 
```

Adds the child object.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cdr_object | [CdrObject](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobject) | The CDR object. |

### insert_object(cdr_object) {#insert_object_cdr_object_1}


```
 insert_object(cdr_object) 
```

Inserts the object

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| cdr_object | [CdrObject](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobject) | The CDR object. |

