---
title: "CdrListObjects 类"
type: docs
weight: 160
url: /zh/python-net/aspose.imaging.fileformats.cdr.objects/cdrlistobjects/
---

**Summary:** The cdr list objects

**Module:** [aspose.imaging.fileformats.cdr.objects](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/)

**Full Name:** aspose.imaging.fileformats.cdr.objects.CdrListObjects

**Inheritance:** CdrObjectContainer

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [CdrListObjects()](#CdrListObjects__1) | 初始化 [CdrListObjects](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrlistobjects/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| childs | System.Collections.Generic.List`1[[Aspose.Imaging.FileFormats.Cdr.Objects.CdrObject]] | r | 获取或设置对象。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| document | [CdrDocument](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrdocument/) | r/w | 获取或设置文档。 |
| fill_id | int | r/w | 获取或设置填充标识符。 |
| hidden | bool | r/w | 获取或设置一个值，指示此 [CdrObjectContainer](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer/) 是否可见。 |
| last_child | [CdrObjectContainer](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer/) | r/w | 获取或设置最后一个子对象。 |
| load_to_last_child | bool | r/w | 获取或设置一个值，指示 [load to last child]。 |
| opacity | float | r/w | 获取或设置不透明度。 |
| opacity_fill_id | int | r/w | 获取或设置不透明度填充标识符。 |
| out_line_id | int | r/w | 获取或设置外线标识符。 |
| page_height | float | r/w | 获取或设置页面的高度。 |
| page_width | float | r/w | 获取或设置页面的宽度。 |
| parent | [CdrObjectContainer](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer/) | r/w | 获取或设置父对象。 |
| style_id | int | r/w | 获取或设置样式标识符。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_child_object(cdr_object)](#add_child_object_cdr_object_1) | 添加子对象。 |
| [insert_object(cdr_object)](#insert_object_cdr_object_2) | 插入对象 |


### Constructor: CdrListObjects() {#CdrListObjects__1}


```
 CdrListObjects() 
```

初始化 [CdrListObjects](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrlistobjects/) 类的新实例。

### Method: add_child_object(cdr_object) {#add_child_object_cdr_object_1}


```
 add_child_object(cdr_object) 
```

添加子对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cdr_object | [CdrObject](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobject/) | 该 CDR 对象。 |

### Method: insert_object(cdr_object) {#insert_object_cdr_object_2}


```
 insert_object(cdr_object) 
```

插入对象

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| cdr_object | [CdrObject](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobject/) | 该 CDR 对象。 |

