---
title: "Enumerazione EmfPointEnum"
type: docs
weight: 260
url: /it/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---

L'enumerazione Point è usata per specificare come un punto deve essere utilizzato in una chiamata di disegno.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfPointEnum

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| BEZIERTO | Specifica che questo punto è un punto di controllo o un punto finale per una curva Bezier. |
| CLOSEFIGURE | Un tipo PT_LINETO o PT_BEZIERTO può essere combinato con questo valore usando l'operatore bitwise <br/>            OR per indicare che il punto corrispondente è l'ultimo punto in una figura <br/>            e la figura è chiusa. |
| LINETO | Specifica che una linea deve essere disegnata dalla posizione corrente a questo punto, <br/>            che poi diventa la nuova posizione corrente. |
| MOVETO | Specifica che questo punto avvia una figura disgiunta. Questo punto diventa la nuova posizione corrente. |
