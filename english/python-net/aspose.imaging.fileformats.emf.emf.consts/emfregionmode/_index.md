---
title: EmfRegionMode Enumeration
type: docs
weight: 300
url: /python-net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---

The RegionMode enumeration defines values that are used with EMR_SELECTCLIPPATH and EMR_EXTSELECTCLIPRGN, <br/>            specifying the current path or a new region that is being combined with the current clip region.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfRegionMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| RGN_AND | The new clipping region includes the intersection (overlapping areas) of the current clipping region and the current path (or new region). |
| RGN_COPY | The new clipping region is the current path (or the new region). |
| RGN_DIFF | The new clipping region includes the areas of the current clipping region with those of the current path (or new region) excluded. |
| RGN_OR | The new clipping region includes the union (combined areas) of the current clipping region and the current path (or new region). |
| RGN_XOR | The new clipping region includes the union of the current clipping region and the current path (or new region) but without the overlapping areas |
