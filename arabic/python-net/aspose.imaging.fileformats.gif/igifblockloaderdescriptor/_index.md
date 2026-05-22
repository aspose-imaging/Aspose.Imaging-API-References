---
title: "IGifBlockLoaderDescriptor فئة"
type: docs
weight: 110
url: /ar/python-net/aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---

**Summary:** Gif block Loader descriptor.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [can_load(stream_container)](#can_load_stream_container_1) | يحدد ما إذا كان المحمّل يمكنه تحميل البيانات المحددة. |
| [load(stream_container, container_palette)](#load_stream_container_container_palette_2) | يقوم بتحميل كتلة الـ gif. |


### Method: can_load(stream_container) {#can_load_stream_container_1}


```
 can_load(stream_container) 
```

يحدد ما إذا كان المحمّل يمكنه تحميل البيانات المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | حاوية الدفق لتحميل البيانات منها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <c>true</c> يمكن للمحمّل تحميل البيانات المحددة؛ وإلا <c>false</c>. |


### Method: load(stream_container, container_palette) {#load_stream_container_container_palette_2}


```
 load(stream_container, container_palette) 
```

يقوم بتحميل كتلة الـ gif.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | حاوية الدفق. |
| container_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | لوحة ألوان الحاوية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | كتلة gif جديدة. |


