---
title: EmfSetPolyFillMode
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETPOLYFILLMODE record defines polygon fill mode.
type: docs
weight: 133
url: /com.aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetPolyFillMode extends EmfStateRecordType
```

The EMR\_SETPOLYFILLMODE record defines polygon fill mode.

In general, the modes differ only in cases where a complex, overlapping polygon MUST be filled; for example, a five-sided polygon that forms a five-pointed star with a pentagon in the center. In such cases, ALTERNATE mode SHOULD fill every other enclosed region within the polygon (the points of the star), but WINDING mode SHOULD fill all regions (the points of the star and the pentagon). When the fill mode is ALTERNATE, the area between odd-numbered and even-numbered polygon sides on each scan line SHOULD be filled. That is, the area between the first and second side SHOULD be filled, and between the third and fourth side, and so on. When the fill mode is WINDING, any region that has a nonzero winding value SHOULD be filled. The winding value is the number of times a pen used to draw the polygon would go around the region. The direction of each edge of the polygon is significant.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetPolyFillMode(EmfRecord source)](#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetPolyFillMode` class. |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode--) | Initializes a new instance of the `EmfSetPolyFillMode` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPolygonFillMode()](#getPolygonFillMode--) | Gets or sets a 32-bit unsigned integer that specifies the polygon fill mode and MUST be in the PolygonFillMode (section 2.1.27) enumeration. |
| [setPolygonFillMode(int value)](#setPolygonFillMode-int-) | Gets or sets a 32-bit unsigned integer that specifies the polygon fill mode and MUST be in the PolygonFillMode (section 2.1.27) enumeration. |
### EmfSetPolyFillMode(EmfRecord source) {#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPolyFillMode(EmfRecord source)
```


Initializes a new instance of the `EmfSetPolyFillMode` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode--}
```
public EmfSetPolyFillMode()
```


Initializes a new instance of the `EmfSetPolyFillMode` class.

### getPolygonFillMode() {#getPolygonFillMode--}
```
public int getPolygonFillMode()
```


Gets or sets a 32-bit unsigned integer that specifies the polygon fill mode and MUST be in the PolygonFillMode (section 2.1.27) enumeration.

**Returns:**
int
### setPolygonFillMode(int value) {#setPolygonFillMode-int-}
```
public void setPolygonFillMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the polygon fill mode and MUST be in the PolygonFillMode (section 2.1.27) enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

