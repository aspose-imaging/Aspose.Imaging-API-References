---
title: "EmfPointEnum"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración Point se usa para especificar cómo se debe usar un punto en una llamada de dibujo."
type: docs
weight: 35
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPointEnum extends System.Enum
```

La enumeración Point se usa para especificar cómo se debe usar un punto en una llamada de dibujo.
## Campos

| Campo | Descripción |
| --- | --- |
| [PT_CLOSEFIGURE](#PT-CLOSEFIGURE) | Un tipo PT\_LINETO o PT\_BEZIERTO puede combinarse con este valor usando el operador bit a bit OR para indicar que el punto correspondiente es el último punto de una figura y que la figura está cerrada. |
| [PT_LINETO](#PT-LINETO) | Especifica que se debe dibujar una línea desde la posición actual hasta este punto, que luego pasa a ser la nueva posición actual. |
| [PT_BEZIERTO](#PT-BEZIERTO) | Especifica que este punto es un punto de control o punto final para una curva Bézier. |
| [PT_MOVETO](#PT-MOVETO) | Especifica que este punto inicia una figura discontinua. |
### PT_CLOSEFIGURE {#PT-CLOSEFIGURE}
```
public static final byte PT_CLOSEFIGURE
```


Un tipo PT\_LINETO o PT\_BEZIERTO puede combinarse con este valor usando el operador bit a bit OR para indicar que el punto correspondiente es el último punto de una figura y que la figura está cerrada.

### PT_LINETO {#PT-LINETO}
```
public static final byte PT_LINETO
```


Especifica que se debe dibujar una línea desde la posición actual hasta este punto, que luego pasa a ser la nueva posición actual.

### PT_BEZIERTO {#PT-BEZIERTO}
```
public static final byte PT_BEZIERTO
```


Especifica que este punto es un punto de control o punto final para una curva Bézier.

### PT_MOVETO {#PT-MOVETO}
```
public static final byte PT_MOVETO
```


Especifica que este punto inicia una figura discontinua. Este punto pasa a ser la nueva posición actual.

