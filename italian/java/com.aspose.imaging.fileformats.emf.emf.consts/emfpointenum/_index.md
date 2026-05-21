---
title: "EmfPointEnum"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione Point viene utilizzata per specificare come un punto deve essere usato in una chiamata di disegno."
type: docs
weight: 35
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPointEnum extends System.Enum
```

L'enumerazione Point viene utilizzata per specificare come un punto deve essere usato in una chiamata di disegno.
## Campi

| Campo | Descrizione |
| --- | --- |
| [PT_CLOSEFIGURE](#PT-CLOSEFIGURE) | Un tipo PT\_LINETO o PT\_BEZIERTO può essere combinato con questo valore usando l'operatore bitwise OR per indicare che il punto corrispondente è l'ultimo punto in una figura e che la figura è chiusa |
| [PT_LINETO](#PT-LINETO) | Specifica che una linea deve essere disegnata dalla posizione corrente a questo punto, che poi diventa la nuova posizione corrente |
| [PT_BEZIERTO](#PT-BEZIERTO) | Specifica che questo punto è un punto di controllo o punto finale per una curva Bézier. |
| [PT_MOVETO](#PT-MOVETO) | Specifica che questo punto avvia una figura disgiunta. |
### PT_CLOSEFIGURE {#PT-CLOSEFIGURE}
```
public static final byte PT_CLOSEFIGURE
```


Un tipo PT\_LINETO o PT\_BEZIERTO può essere combinato con questo valore usando l'operatore bitwise OR per indicare che il punto corrispondente è l'ultimo punto in una figura e che la figura è chiusa

### PT_LINETO {#PT-LINETO}
```
public static final byte PT_LINETO
```


Specifica che una linea deve essere disegnata dalla posizione corrente a questo punto, che poi diventa la nuova posizione corrente

### PT_BEZIERTO {#PT-BEZIERTO}
```
public static final byte PT_BEZIERTO
```


Specifica che questo punto è un punto di controllo o punto finale per una curva Bézier.

### PT_MOVETO {#PT-MOVETO}
```
public static final byte PT_MOVETO
```


Specifica che questo punto avvia una figura disgiunta. Questo punto diventa la nuova posizione corrente.

