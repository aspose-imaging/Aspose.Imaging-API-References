---
title: EmfPlusFillPath Class
type: docs
weight: 250
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---

Fill path record<br/>            FLAGS:<br/>            16-bit unsigned integer that provides information about how the operation is to be performed,<br/>            and about the structure of the record.<br/>            0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            S X X X X X X X |   ObjectId    |<br/>            S (1 bit): This bit indicates the type of data in the BrushId field.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.<br/>            X (1 bit): Reserved and MUST be ignored.<br/>            ObjectId (1 byte): The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPath

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusFillPath type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusFillPath(source)|Initializes a new instance of the EmfPlusFillPath class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|is_color|Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear,<br/>            BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table|
|object_id|Gets or sets the object identifier.<br/>            The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the<br/>            EMF+ Object Table. The value MUST be zero to 63, inclusive.|
|brush_id|Gets or sets the Brush ID<br/>            A 32-bit unsigned integer that defines the brush, the content of which is determined<br/>            by the S bit in the Flags field.|
