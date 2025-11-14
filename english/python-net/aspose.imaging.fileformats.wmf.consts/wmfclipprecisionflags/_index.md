---
title: WmfClipPrecisionFlags Enumeration
type: docs
weight: 50
url: /python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---

ClipPrecision Flags specify clipping precision, which defines how to clip characters that are<br/>                partially outside a clipping region. These flags can be combined to specify multiple options.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfClipPrecisionFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| CHARACTER | This value SHOULD NOT be used. |
| DEFAULT | Specifies that default clipping MUST be used. |
| DFA_DISABLE | This value specifies that font association SHOULD [35] be turned off.<br/>                [35] This value is not supported.in Windows 95, Windows 98, and Windows Millennium Edition.<br/>                Font association is turned off in Windows 2000, Windows XP, and Windows Server 2003.<br/>                This value is ignored in these Windows versions:<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
| EMBEDDED | This value specifies that font embedding MUST be used to render document<br/>                content; embedded fonts are read-only. |
| LH_ANGLES | This value is used to control font rotation, as follows:<br/>                - If set, the rotation for all fonts SHOULD be determined by the orientation<br/>                of the coordinate system; that is, whether the orientation is left-handed<br/>                or right-handed.<br/>                - If clear, device fonts SHOULD rotate counterclockwise, but the rotation of<br/>                other fonts SHOULD be determined by the orientation of the coordinate<br/>                system. |
| STROKE | This value MAY be returned when enumerating rasterized, TrueType and<br/>                vector fonts.<br/>                [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0,<br/>                Windows 2000, and Windows XP: This value is always returned when enumerating fonts.) |
| TT_ALWAYS | This value SHOULD NOT [34] be used.<br/>                [34] This value is ignored in the following Windows versions:<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
