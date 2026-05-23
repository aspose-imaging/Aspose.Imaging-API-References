---
title: "Enumerazione EmfModifyWorldTransformMode"
type: docs
weight: 240
url: /it/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---

L'enumerazione ModifyWorldTransformMode definisce le modalità per utilizzare i dati di trasformazione specificati<br/>            per modificare la trasformazione dallo spazio mondo allo spazio pagina attualmente definita nel contesto del dispositivo di riproduzione.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfModifyWorldTransformMode

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| MWT_IDENTITY | Reimposta la trasformazione corrente usando la matrice identità. In questa modalità, i dati di trasformazione specificati vengono ignorati |
| MWT_LEFTMULTIPLY | Moltiplica la trasformazione corrente. In questa modalità, i dati di trasformazione specificati sono il moltiplicatore sinistro, e <br/>            la trasformazione attualmente definita nel contesto del dispositivo di riproduzione è il moltiplicatore destro |
| MWT_RIGHTMULTIPLY | Moltiplica la trasformazione corrente. In questa modalità, i dati di trasformazione specificati sono il moltiplicatore destro, <br/>            e la trasformazione attualmente definita nel contesto del dispositivo di riproduzione è il moltiplicatore sinistro |
| MWT_SET | Esegui la funzione di un record EMR_SETWORLDTRANSFORM (sezione 2.3.12.2). |
