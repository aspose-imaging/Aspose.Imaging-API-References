---
title: EmfPlusSetTsClip
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server.
type: docs
weight: 66
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsClip extends EmfPlusTerminalServerRecordType
```

The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server.

The compression scheme for data in this record uses the following algorithm. Each point of each rectangle is encoded in either a single byte or 2 bytes. If the point is encoded in a single byte, the high bit (0x80) of the byte MUST be set, and the value is a signed number represented by the lower 7 bits. If the high bit is not set, then the value is encoded in 2 bytes, with the high-order byte encoded in the 7 lower bits of the first byte, and the low-order byte value encoded in the second byte. Each point is encoded as the difference between the point in the current rect and the point in the previous rect. The bottom point of the rect is encoded as the difference between the bottom coordinate and the top coordinate on the current rect.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSetTsClip` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Gets a value indicating whether this `EmfPlusSetTsClip` is compressed. |
| [getNumRects()](#getNumRects--) | Gets the number rects. |
| [getRects()](#getRects--) | Gets or sets an array of NumRects rectangles that define clipping areas. |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | Gets or sets an array of NumRects rectangles that define clipping areas. |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSetTsClip` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Gets a value indicating whether this `EmfPlusSetTsClip` is compressed. This bit specifies the format of the rectangle data in the rects field. If set, each rectangle is defined in 4 bytes. If clear, each rectangle is defined in 8 bytes.

Value: `true` if compressed; otherwise, `false`.

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


Gets the number rects. This field specifies the number of rectangles that are defined in the rect field.

Value: The number rects.

**Returns:**
short
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


Gets or sets an array of NumRects rectangles that define clipping areas. The format of this data is determined by the C bit in the Flags field.

Value: The rects.

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


Gets or sets an array of NumRects rectangles that define clipping areas. The format of this data is determined by the C bit in the Flags field.

Value: The rects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

