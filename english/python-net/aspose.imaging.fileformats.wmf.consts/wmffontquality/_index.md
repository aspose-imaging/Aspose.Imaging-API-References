---
title: WmfFontQuality Enumeration
type: docs
weight: 100
url: /python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/
---

The FontQuality Enumeration specifies how closely the attributes of the logical font should match<br/>                those of the physical font when rendering text.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfFontQuality

**Aspose.Imaging Version:** 23.6

## **Members**
| **Member name** | **Description** |
| :- | :- |
| DEFAULT | Specifies that the character quality of the font does not matter, so<br/>                DRAFT can be used. |
| DRAFT | Specifies that the character quality of the font is less important than the<br/>                matching of logical attribuetes. For rasterized fonts, scaling SHOULD be enabled, which<br/>                means that more font sizes are available. |
| PROOF | Specifies that the character quality of the font is more important than the<br/>                matching of logical attributes. For rasterized fonts, scaling SHOULD be disabled, and the font<br/>                closest in size SHOULD be chosen. |
| NONANTIALIASED | Specifies that anti-aliasing SHOULD NOT be used when<br/>                rendering text |
| ANTIALIASED | Specifies that anti-aliasing SHOULD be used when rendering text, if<br/>                the font supports it. |
| CLEARTYPE | Specifies that ClearType anti-aliasing SHOULD be used when<br/>                rendering text, if the font supports it. |
