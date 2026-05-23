---
title: "Enumerazione EmfPlusInterpolationMode"
type: docs
weight: 200
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---

L'enumerazione InterpolationMode definisce i metodi per eseguire il ridimensionamento, inclusi l'allungamento e la riduzione.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusInterpolationMode

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| INTERPOLATION_MODE_BICUBIC | Specifica l'interpolazione bicubica, che utilizza il più vicino quartetto 4x4 di pixel noti intorno al pixel interpolato. La media ponderata di questi 16 valori di pixel noti determina il valore da assegnare al pixel interpolato. Poiché i pixel noti possono trovarsi a distanze variabili dal pixel interpolato, i pixel più vicini ricevono un peso maggiore nel calcolo. Il risultato appare più fluido rispetto a InterpolationModeBilinear. |
| INTERPOLATION_MODE_BILINEAR | Specifica l'interpolazione bilineare, che utilizza il più vicino quartetto 2x2 di pixel noti intorno al pixel interpolato. La media ponderata di questi 4 valori di pixel noti determina il valore da assegnare al pixel interpolato. Il risultato appare più fluido rispetto a InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_DEFAULT | Specifica la modalità di interpolazione predefinita, definita come InterpolationModeBilinear. |
| INTERPOLATION_MODE_HIGH_QUALITY | Specifica una modalità di interpolazione ad alta qualità, definita come InterpolationModeHighQualityBicubic. |
| INTERPOLATION_MODE_HIGH_QUALITY_BICUBIC | Specifica l'interpolazione bicubica con prefiltraggio, che produce il risultato di massima qualità tra queste opzioni. |
| INTERPOLATION_MODE_HIGH_QUALITY_BILINEAR | Specifica l'interpolazione bilineare con prefiltraggio. |
| INTERPOLATION_MODE_LOW_QUALITY | Specifica una modalità di interpolazione a bassa qualità, definita come InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_NEAREST_NEIGHBOR | Specifica l'interpolazione nearest-neighbor, che utilizza solo il valore del pixel più vicino al pixel interpolato. Questa modalità duplica o rimuove semplicemente i pixel, producendo il risultato di qualità più bassa tra queste opzioni. |
