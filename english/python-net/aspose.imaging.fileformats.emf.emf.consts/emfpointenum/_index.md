---
title: EmfPointEnum Enumeration
type: docs
weight: 260
url: /python-net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---

The Point enumeration is used to specify how a point is to be used in a drawing call.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfPointEnum

## **Members**
| **Member name** | **Description** |
| :- | :- |
| BEZIERTO | Specifies that this point is a control point or ending point for a Bezier curve. |
| CLOSEFIGURE | A PT_LINETO or PT_BEZIERTO type can be combined with this value by using the bitwise <br/>            operator OR to indicate that the corresponding point is the last point in a figure <br/>            and the figure is closed |
| LINETO | Specifies that a line is to be drawn from the current position to this point, <br/>            which then becomes the new current position |
| MOVETO | Specifies that this point starts a disjoint figure. This point becomes the new current position. |
