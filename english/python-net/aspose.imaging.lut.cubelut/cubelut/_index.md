---
title: CubeLut Class
type: docs
weight: 10
url: /python-net/aspose.imaging.lut.cubelut/cubelut/
---

**Summary:** Represents a 3‑dimensional lookup table (LUT) loaded from a .cube file.

**Module:** [aspose.imaging.lut.cubelut](/imaging/python-net/aspose.imaging.lut.cubelut/)

**Full Name:** aspose.imaging.lut.cubelut.CubeLut

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| point_count | int | r | Gets the point count. |
| size | int | r | Gets the size. |
| title | string | r | Gets the title. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [load(file_name)](#load_file_name_1) | Loads a [CubeLut](/imaging/python-net/aspose.imaging.lut.cubelut/cubelut/) from a file. |
| [load(stream)](#load_stream_2) | Loads a [CubeLut](/imaging/python-net/aspose.imaging.lut.cubelut/cubelut/) from the provided stream. |


### Method: load(file_name)  [static] {#load_file_name_1}


```
 load(file_name) 
```

Loads a [CubeLut](/imaging/python-net/aspose.imaging.lut.cubelut/cubelut/) from a file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_name | string | The path to the *.cube file. |

**Returns**

| Type | Description |
| :- | :- |
| [CubeLut](/imaging/python-net/aspose.imaging.lut.cubelut/cubelut/) | A new instance of [CubeLut](/imaging/python-net/aspose.imaging.lut.cubelut/cubelut/). |


### Method: load(stream)  [static] {#load_stream_2}


```
 load(stream) 
```

Loads a [CubeLut](/imaging/python-net/aspose.imaging.lut.cubelut/cubelut/) from the provided stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream containing the LUT data. |

**Returns**

| Type | Description |
| :- | :- |
| [CubeLut](/imaging/python-net/aspose.imaging.lut.cubelut/cubelut/) | A new instance of [CubeLut](/imaging/python-net/aspose.imaging.lut.cubelut/cubelut/). |


