---
title: EmfPlusTextRenderingHint Enumeration
type: docs
weight: 430
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---

The TextRenderingHint enumeration defines types of text hinting and anti-aliasing, which affects the quality of text rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusTextRenderingHint

## **Members**
| **Member name** | **Description** |
| :- | :- |
| TEXT_RENDERING_HINT_ANTIALIAS | Specifies that each text character is drawn using its anti-aliased glyph bitmap without hinting. Better quality results from anti-aliasing, but stem width differences MAY be noticeable because hinting is turned off. |
| TEXT_RENDERING_HINT_ANTIALIAS_GRID_FIT | Specifies that each text character SHOULD be drawn using its anti-aliased glyph bitmap with smoothing. The rendering is high quality because of anti-aliasing, but at a higher performance cost. |
| TEXT_RENDERING_HINT_CLEAR_TYPE_GRID_FIT | Specifies that each text character SHOULD be drawn using its ClearType glyph bitmap with smoothing. This is the highest-quality text hinting setting, which is used to take advantage of ClearType font features. |
| TEXT_RENDERING_HINT_SINGLE_BIT_PER_PIXEL | Specifies that each text character SHOULD be drawn using its glyph bitmap. Smoothing is not used. |
| TEXT_RENDERING_HINT_SINGLE_BIT_PER_PIXEL_GRID_FIT | Specifies that each text character SHOULD be drawn using its glyph bitmap. Smoothing MAY be used to improve the appearance of character glyph stems and curvature. |
| TEXT_RENDERING_HINT_SYSTEM_DEFAULT | Specifies that each text character SHOULD be drawn using whatever font-smoothing settings have been configured on the operating system. |
