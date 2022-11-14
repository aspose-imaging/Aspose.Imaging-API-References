---
title: EmfStrokeAndFillPath
second_title: Aspose.Imaging for Java API Reference
description: The EMR_STROKEANDFILLPATH record closes any open figures in a path strokes the outline of the path by using the current pen and fills its interior by using the current brush.
type: docs
weight: 148
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfStrokeAndFillPath extends EmfDrawingRecordType
```

The EMR\_STROKEANDFILLPATH record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfStrokeAndFillPath(EmfRecord source)](#EmfStrokeAndFillPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfStrokeAndFillPath` class. |
| [EmfStrokeAndFillPath()](#EmfStrokeAndFillPath--) | Initializes a new instance of the `EmfStrokeAndFillPath` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
### EmfStrokeAndFillPath(EmfRecord source) {#EmfStrokeAndFillPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfStrokeAndFillPath(EmfRecord source)
```


Initializes a new instance of the `EmfStrokeAndFillPath` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfStrokeAndFillPath() {#EmfStrokeAndFillPath--}
```
public EmfStrokeAndFillPath()
```


Initializes a new instance of the `EmfStrokeAndFillPath` class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

