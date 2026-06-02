---
title: "Enumeración EmfPointEnum"
type: docs
weight: 260
url: /es/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---

La enumeración Point se utiliza para especificar cómo se debe usar un punto en una llamada de dibujo.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfPointEnum

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| BEZIERTO | Especifica que este punto es un punto de control o punto final para una curva Bézier. |
| CLOSEFIGURE | Un tipo PT_LINETO o PT_BEZIERTO puede combinarse con este valor usando el operador bit a bit <br/>            OR para indicar que el punto correspondiente es el último punto de una figura <br/>            y la figura está cerrada |
| LINETO | Especifica que se debe dibujar una línea desde la posición actual hasta este punto, <br/>            que luego se convierte en la nueva posición actual |
| MOVETO | Especifica que este punto inicia una figura discontinua. Este punto se convierte en la nueva posición actual. |
