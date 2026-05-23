---
title: "EmfPlusInterpolationMode Enumeration"
type: docs
weight: 200
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---

InterpolationMode‑uppräkningen definierar sätt att utföra skalning, inklusive sträckning och krympning.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusInterpolationMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| INTERPOLATION_MODE_BICUBIC | Anger bikubisk interpolering, som använder det närmaste 4x4‑grannskapet av kända pixlar kring den interpolerade pixeln. Det viktade genomsnittet av dessa 16 kända pixelvärden bestämmer värdet som ska tilldelas den interpolerade pixeln. Eftersom de kända pixlarna sannolikt befinner sig på olika avstånd från den interpolerade pixeln, får närmare pixlar en högre vikt i beräkningen. Resultatet ser jämnare ut än InterpolationModeBilinear. |
| INTERPOLATION_MODE_BILINEAR | Anger bilinjär interpolering, som använder det närmaste 2x2‑grannskapet av kända pixlar kring den interpolerade pixeln. Det viktade genomsnittet av dessa 4 kända pixelvärden bestämmer värdet som ska tilldelas den interpolerade pixeln. Resultatet ser jämnare ut än InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_DEFAULT | Anger standardinterpoleringsläget, som definieras som InterpolationModeBilinear. |
| INTERPOLATION_MODE_HIGH_QUALITY | Anger ett högkvalitativt interpolationsläge, som definieras som InterpolationModeHighQualityBicubic. |
| INTERPOLATION_MODE_HIGH_QUALITY_BICUBIC | Anger bikubisk interpolation med förfiltrering, vilket ger det högsta kvalitetsresultatet bland dessa alternativ. |
| INTERPOLATION_MODE_HIGH_QUALITY_BILINEAR | Anger bilinjär interpolation med förfiltrering. |
| INTERPOLATION_MODE_LOW_QUALITY | Anger ett lågkvalitativt interpolationsläge, som definieras som InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_NEAREST_NEIGHBOR | Anger närmaste-granne-interpolation, som endast använder värdet på den pixel som ligger närmast den interpolerade pixeln. Detta läge duplicerar eller tar bort pixlar, vilket ger det lägsta kvalitetsresultatet bland dessa alternativ. |
