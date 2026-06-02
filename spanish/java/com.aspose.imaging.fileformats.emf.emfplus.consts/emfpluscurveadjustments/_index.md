---
title: "EmfPlusCurveAdjustments"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración CurveAdjustments define ajustes que pueden aplicarse a la curva de color de una imagen."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCurveAdjustments extends System.Enum
```

La enumeración CurveAdjustments define ajustes que pueden aplicarse a la curva de color de una imagen.
## Campos

| Campo | Descripción |
| --- | --- |
| [AdjustExposure](#AdjustExposure) | Especifica la simulación de aumentar o disminuir la exposición de una imagen. |
| [AdjustDensity](#AdjustDensity) | Especifica la simulación de aumentar o disminuir la densidad de una imagen. |
| [AdjustContrast](#AdjustContrast) | Especifica un aumento o disminución del contraste de una imagen. |
| [AdjustHighlight](#AdjustHighlight) | Especifica un aumento o disminución del valor de un canal de color de una imagen, si ese canal ya tiene un valor superior a la mitad de la intensidad. |
| [AdjustShadow](#AdjustShadow) | Especifica un aumento o disminución del valor de un canal de color de una imagen, si ese canal ya tiene un valor inferior a la mitad de la intensidad. |
| [AdjustMidtone](#AdjustMidtone) | Especifica un ajuste que aclara o oscurece una imagen. |
| [AdjustWhiteSaturation](#AdjustWhiteSaturation) | Especifica un ajuste a la saturación blanca de una imagen, definido como el valor máximo en el rango de intensidades para un canal de color dado, cuyo rango suele ser de 0 a 255. |
| [AdjustBlackSaturation](#AdjustBlackSaturation) | Especifica un ajuste a la saturación negra de una imagen, que es el valor mínimo en el rango de intensidades para un canal de color dado, que suele ser de 0 a 255. |
### AdjustExposure {#AdjustExposure}
```
public static final int AdjustExposure
```


Especifica la simulación de aumentar o disminuir la exposición de una imagen.

### AdjustDensity {#AdjustDensity}
```
public static final int AdjustDensity
```


Especifica la simulación de aumentar o disminuir la densidad de una imagen.

### AdjustContrast {#AdjustContrast}
```
public static final int AdjustContrast
```


Especifica un aumento o disminución del contraste de una imagen.

### AdjustHighlight {#AdjustHighlight}
```
public static final int AdjustHighlight
```


Especifica un aumento o disminución del valor de un canal de color de una imagen, si ese canal ya tiene un valor superior a la mitad de la intensidad. Este ajuste puede usarse para aumentar la definición en las áreas claras de una imagen sin afectar las áreas oscuras.

### AdjustShadow {#AdjustShadow}
```
public static final int AdjustShadow
```


Especifica un aumento o disminución del valor de un canal de color de una imagen, si ese canal ya tiene un valor inferior a la mitad de la intensidad. Este ajuste puede usarse para aumentar la definición en las áreas oscuras de una imagen sin afectar las áreas claras.

### AdjustMidtone {#AdjustMidtone}
```
public static final int AdjustMidtone
```


Especifica un ajuste que aclara u oscurece una imagen. Los valores de los canales de color en el medio del rango de intensidad se modifican más que los valores de los canales cercanos a los extremos mínimo o máximo de intensidad. Este ajuste puede usarse para aclarar u oscurecer una imagen sin perder el contraste entre las partes más oscuras y más claras de la imagen.

### AdjustWhiteSaturation {#AdjustWhiteSaturation}
```
public static final int AdjustWhiteSaturation
```


Especifica un ajuste a la saturación blanca de una imagen, definido como el valor máximo en el rango de intensidades para un canal de color dado, cuyo rango suele ser de 0 a 255.

--------------------

Por ejemplo, un valor de ajuste de saturación blanca de 240 especifica que los valores de los canales de color en el rango de 0 a 240 se ajustan para que se distribuyan en el rango de 0 a 255, con los valores de los canales superiores a 240 establecidos en 255.

### AdjustBlackSaturation {#AdjustBlackSaturation}
```
public static final int AdjustBlackSaturation
```


Especifica un ajuste a la saturación negra de una imagen, que es el valor mínimo en el rango de intensidades para un canal de color dado, que suele ser de 0 a 255.

--------------------

Por ejemplo, un valor de ajuste de saturación negra de 15 especifica que los valores de los canales de color en el rango de 15 a 255 se ajustan para que se distribuyan en el rango de 0 a 255, con los valores de los canales menores a 15 establecidos en 0.

