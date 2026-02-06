---
title: TextRenderingHint Enumeration
type: docs
weight: 11250
url: /python-net/aspose.imaging/textrenderinghint/
---

Specifies the quality of text rendering.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.TextRenderingHint

## **Members**
| **Member name** | **Description** |
| :- | :- |
| ANTI_ALIAS | Each character is drawn using its antialiased glyph bitmap without hinting. Better quality due to antialiasing. Stem width differences may be noticeable because hinting is turned off. |
| ANTI_ALIAS_GRID_FIT | Each character is drawn using its antialiased glyph bitmap with hinting. Much better quality due to antialiasing, but at a higher performance cost. |
| CLEAR_TYPE_GRID_FIT | Each character is drawn using its glyph ClearType bitmap with hinting. The highest quality setting. Used to take advantage of ClearType font features. |
| SINGLE_BIT_PER_PIXEL | Each character is drawn using its glyph bitmap. Hinting is not used. |
| SINGLE_BIT_PER_PIXEL_GRID_FIT | Each character is drawn using its glyph bitmap. Hinting is used to improve character appearance on stems and curvature. |
| SYSTEM_DEFAULT | Each character is drawn using its glyph bitmap, with the system default rendering hint. The text will be drawn using whatever font-smoothing settings the user has selected for the system. |
