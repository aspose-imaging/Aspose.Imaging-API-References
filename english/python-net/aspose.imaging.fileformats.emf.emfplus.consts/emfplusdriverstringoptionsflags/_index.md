---
title: EmfPlusDriverStringOptionsFlags Enumeration
type: docs
weight: 130
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---

The DriverStringOptions flags specify properties of graphics text positioning and rendering. These flags can be combined to specify multiple options.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusDriverStringOptionsFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| DRIVER_STRING_OPTIONS_CMAP_LOOKUP | If set, the positions of character glyphs SHOULD be specified in a character map lookup table.<br/>            If clear, the glyph positions SHOULD be obtained from an array of coordinates. |
| DRIVER_STRING_OPTIONS_LIMIT_SUBPIXEL | If set, less memory SHOULD be used to cache anti-aliased glyphs, which produces lower quality text rendering.<br/>            If clear, more memory SHOULD be used, which produces higher quality text rendering. |
| DRIVER_STRING_OPTIONS_REALIZED_ADVANCE | If set, character glyph positions SHOULD be calculated relative to the position of the first glyph.<br/>            If clear, the glyph positions SHOULD be obtained from an array of coordinates. |
| DRIVER_STRING_OPTIONS_VERTICAL | If set, the string SHOULD be rendered vertically.<br/>            If clear, the string SHOULD be rendered horizontally. |
