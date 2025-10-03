---
title: CompressionMethod Enumeration
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.psd/compressionmethod/
---

Defines the compression method used for image data.

**Module:** [aspose.imaging.fileformats.psd](/imaging/python-net/aspose.imaging.fileformats.psd/)

**Full Name:** aspose.imaging.fileformats.psd.CompressionMethod

## **Members**
| **Member name** | **Description** |
| :- | :- |
| RAW | No compression. The image data stored as raw bytes in RGBA planar order.<br/>            That means that first all R data is written, then all G is written, then all B and finally all A data is written. |
| RLE | RLE compressed the image data starts with the byte counts for all the scan lines (rows * channels), with each<br/>            count stored as a two-byte value. The RLE compressed data follows, with each scan line compressed separately.<br/>            The RLE compression is the same compression algorithm used by the Macintosh ROM routine PackBits and the TIFF standard. |
| ZIP_WITHOUT_PREDICTION | ZIP without prediction. |
| ZIP_WITH_PREDICTION | ZIP with prediction. |
