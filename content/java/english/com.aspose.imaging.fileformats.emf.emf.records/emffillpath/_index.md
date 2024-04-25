---
title: EmfFillPath
second_title: Aspose.Imaging for Java API Reference
description: The EMR_FILLPATH record closes any open figures in the current path and fills the paths interior by using the current brush and polygon-filling mode.
type: docs
weight: 57
url: /com.aspose.imaging.fileformats.emf.emf.records/emffillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillPath extends EmfDrawingRecordType
```

The EMR\_FILLPATH record closes any open figures in the current path and fills the path's interior by using the current brush and polygon-filling mode.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfFillPath(EmfRecord source)](#EmfFillPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfFillPath` class. |
| [EmfFillPath()](#EmfFillPath--) | Initializes a new instance of the `EmfFillPath` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies bounding rectangle, in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies bounding rectangle, in device units. |
### EmfFillPath(EmfRecord source) {#EmfFillPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillPath(EmfRecord source)
```


Initializes a new instance of the `EmfFillPath` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfFillPath() {#EmfFillPath--}
```
public EmfFillPath()
```


Initializes a new instance of the `EmfFillPath` class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies bounding rectangle, in device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies bounding rectangle, in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

