---
title: EmfPlusPathPointFlags Enumeration
type: docs
weight: 290
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---

A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object.<br/>            C  (1 bit): If set, the PathPoints array specifies absolute locations in the coordinate space with 16-bit integer coordinates.<br/>             If clear, the PathPoints array specifies absolute locations in the coordinate space with 32-bit floating-point coordinates.<br/>             Note If the P flag (below) is set, this flag MAY be clear and MUST be ignored.<br/>            R (1 bit): If set, the point types in the PathPointTypes array are specified by EmfPlusPathPointTypeRle objects (section 2.2.2.32), <br/>             which use run-length encoding (RLE) compression, and/or EmfPlusPathPointType objects (section 2.2.2.31). See [MS-WMF] section 3.1.6 for more information on RLE compression.<br/>             If clear, the point types in the PathPointTypes array are specified by EmfPlusPathPointType objects.<br/>            P (1 bit): If set, each element in the PathPoints array specifies a location in the coordinate space that is relative to the<br/>             location specified by the previous element in the array. In the case of the first element in PathPoints, a previous location at coordinates (0,0) is assumed.<br/>             If clear, each element in the PathPoints array specifies an absolute location.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPathPointFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| C | The c flag |
| P | The p flag |
| R | The r flag |
