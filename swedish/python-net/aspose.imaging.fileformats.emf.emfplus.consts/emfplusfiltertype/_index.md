---
title: "EmfPlusFilterType Enumeration"
type: docs
weight: 140
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---

FilterType‑uppräkningen definierar typer av filtreringsalgoritmer som kan användas för förbättring av text- och grafikens kvalitet samt bildrendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusFilterType

## **Members**
| **Member name** | **Description** |
| :- | :- |
| FILTER_TYPE_BOX | Anger en box‑filteralgoritm där varje destinationspixel beräknas genom att medelvärdesbilda en rektangel av källpixlar. Denna algoritm är endast användbar när bildens storlek minskas. |
| FILTER_TYPE_GAUSSIAN_QUAD | Anger att ett 4‑samples Gauss‑filter används, vilket skapar en suddig effekt på bilden. |
| FILTER_TYPE_LINEAR | Anger att linjär interpolation utförs med hjälp av ett viktat medelvärde av ett 2×2‑område av pixlar kring källpixeln. |
| FILTER_TYPE_NONE | Anger att filtrering inte utförs. |
| FILTER_TYPE_POINT | Anger att varje destinationspixel beräknas genom att sampla den närmaste pixeln från källbilden. |
| FILTER_TYPE_PYRAMIDAL_QUAD | Anger att ett 4‑samples tältfilter används. |
| FILTER_TYPE_TRIANGLE | Anger att varje pixel i källbilden bidrar lika mycket till destinationsbilden. Detta är den långsammaste av filtreringsalgoritmerna. |
