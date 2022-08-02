---
title: HatchStyle
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Especifica los diferentes patrones disponibles paraHatchBrush../aspose.imaging.brushes/hatchbrush objetos.
type: docs
weight: 9390
url: /es/net/aspose.imaging/hatchstyle/
---
## HatchStyle enumeration

Especifica los diferentes patrones disponibles para[`HatchBrush`](../../aspose.imaging.brushes/hatchbrush) objetos.

```csharp
public enum HatchStyle
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Horizontal | `0` | Un patrón de líneas horizontales. |
| Min | `0` | Especifica el estilo de sombreado Horizontal. |
| Vertical | `1` | Un patrón de líneas verticales. |
| ForwardDiagonal | `2` | Un patrón de líneas en diagonal desde la esquina superior izquierda a la esquina inferior derecha. |
| BackwardDiagonal | `3` | Un patrón de líneas en diagonal desde la esquina superior derecha a la esquina inferior izquierda. |
| Cross | `4` | Especifica líneas horizontales y verticales que se cruzan. |
| LargeGrid | `4` | Especifica el estilo de sombreado Cross. |
| Max | `4` | Especifica el estilo de sombreado SolidDiamond. |
| DiagonalCross | `5` | Un patrón de líneas diagonales entrecruzadas. |
| Percent05 | `6` | Especifica un sombreado del 5 por ciento. La relación entre el color de primer plano y el color de fondo es 5:95. |
| Percent10 | `7` | Especifica un sombreado del 10 por ciento. La relación entre el color de primer plano y el color de fondo es 10:90. |
| Percent20 | `8` | Especifica un sombreado del 20 por ciento. La relación entre el color de primer plano y el color de fondo es 20:80. |
| Percent25 | `9` | Especifica un sombreado del 25 por ciento. La relación entre el color de primer plano y el color de fondo es 25:75. |
| Percent30 | `10` | Especifica un sombreado del 30 por ciento. La relación entre el color de primer plano y el color de fondo es 30:70. |
| Percent40 | `11` | Especifica un sombreado del 40 por ciento. La relación entre el color de primer plano y el color de fondo es 40:60. |
| Percent50 | `12` | Especifica un sombreado del 50 por ciento. La relación entre el color de primer plano y el color de fondo es 50:50. |
| Percent60 | `13` | Especifica un sombreado del 60 por ciento. La relación entre el color de primer plano y el color de fondo es 60:40. |
| Percent70 | `14` | Especifica un sombreado del 70 por ciento. La relación entre el color de primer plano y el color de fondo es 70:30. |
| Percent75 | `15` | Especifica un sombreado del 75 por ciento. La relación entre el color de primer plano y el color de fondo es 75:25. |
| Percent80 | `16` | Especifica un sombreado del 80 por ciento. La relación entre el color de primer plano y el color de fondo es 80:100. |
| Percent90 | `17` | Especifica un sombreado del 90 por ciento. La relación entre el color de primer plano y el color de fondo es 90:10. |
| LightDownwardDiagonal | `18` | Especifica líneas diagonales que se inclinan hacia la derecha desde los puntos superiores a los puntos inferiores y están espaciadas un 50 por ciento más juntas que ForwardDiagonal, pero no tienen suavizado. |
| LightUpwardDiagonal | `19` | Especifica líneas diagonales que se inclinan hacia la izquierda desde los puntos superiores a los puntos inferiores y están espaciadas un 50 por ciento más juntas que BackwardDiagonal, pero no están suavizadas. |
| DarkDownwardDiagonal | `20` | Especifica líneas diagonales que se inclinan hacia la derecha desde los puntos superiores a los puntos inferiores, están espaciadas un 50 por ciento más juntas que y tienen el doble del ancho de ForwardDiagonal. Este patrón de sombreado no está suavizado. |
| DarkUpwardDiagonal | `21` | Especifica líneas diagonales que se inclinan hacia la izquierda desde los puntos superiores a los puntos inferiores, están espaciadas un 50 por ciento más juntas que BackwardDiagonal y tienen el doble de ancho, pero las líneas no tienen suavizado. |
| WideDownwardDiagonal | `22` | Especifica líneas diagonales que se inclinan hacia la derecha desde los puntos superiores a los puntos inferiores, tienen el mismo espaciado que el estilo de sombreado Diagonal hacia adelante y tienen el triple de ancho, pero no tienen antialias. |
| WideUpwardDiagonal | `23` | Especifica líneas diagonales que se inclinan hacia la izquierda desde los puntos superiores a los puntos inferiores, tienen el mismo espaciado que el estilo de sombreado BackwardDiagonal y tienen el triple de ancho, pero no tienen antialias. |
| LightVertical | `24` | Especifica líneas verticales que están espaciadas un 50 por ciento menos juntas que Vertical. |
| LightHorizontal | `25` | Especifica líneas horizontales que están espaciadas un 50 por ciento menos juntas que Horizontal. |
| NarrowVertical | `26` | Especifica líneas verticales que están espaciadas un 75 por ciento más juntas que el estilo de sombreado Vertical (o un 25 por ciento más juntas que LightVertical). |
| NarrowHorizontal | `27` | Especifica líneas horizontales que están espaciadas un 75 por ciento más juntas que el estilo de sombreado Horizontal (o un 25 por ciento más juntas que LightHorizontal). |
| DarkVertical | `28` | Especifica líneas verticales que están espaciadas un 50 por ciento más juntas que las verticales y tienen el doble de su ancho. |
| DarkHorizontal | `29` | Especifica líneas horizontales que están espaciadas un 50 por ciento más juntas que Horizontal y tienen el doble de ancho que Horizontal. |
| DashedDownwardDiagonal | `30` | Especifica líneas diagonales discontinuas, que se inclinan hacia la derecha desde los puntos superiores hasta los puntos inferiores. |
| DashedUpwardDiagonal | `31` | Especifica líneas diagonales discontinuas, que se inclinan hacia la izquierda desde los puntos superiores hasta los puntos inferiores. |
| DashedHorizontal | `32` | Especifica líneas discontinuas horizontales. |
| DashedVertical | `33` | Especifica líneas verticales discontinuas. |
| SmallConfetti | `34` | Especifica un sombreado que tiene la apariencia de confeti. |
| LargeConfetti | `35` | Especifica un sombreado que tiene la apariencia de confeti y está compuesto por piezas más grandes que SmallConfetti. |
| ZigZag | `36` | Especifica líneas horizontales que se componen de zigzags. |
| Wave | `37` | Especifica líneas horizontales que se componen de tildes. |
| DiagonalBrick | `38` | Especifica un sombreado que tiene la apariencia de ladrillos en capas que se inclinan hacia la izquierda desde los puntos superiores hasta los puntos inferiores. |
| HorizontalBrick | `39` | Especifica un sombreado que tiene la apariencia de ladrillos en capas horizontales. |
| Weave | `40` | Especifica un sombreado que tiene la apariencia de un material tejido. |
| Plaid | `41` | Especifica un sombreado que tiene la apariencia de un material escocés. |
| Divot | `42` | Especifica un sombreado que tiene la apariencia de chuletas. |
| DottedGrid | `43` | Especifica líneas horizontales y verticales, cada una de las cuales se compone de puntos, que se cruzan. |
| DottedDiamond | `44` | Especifica líneas diagonales hacia delante y hacia atrás, cada una de las cuales está compuesta por puntos, que se cruzan. |
| Shingle | `45` | Especifica un sombreado que tiene la apariencia de tejas en capas diagonales que se inclinan hacia la derecha desde los puntos superiores hasta los puntos inferiores. |
| Trellis | `46` | Especifica un sombreado que tiene la apariencia de un enrejado. |
| Sphere | `47` | Especifica un sombreado que tiene la apariencia de esferas colocadas una al lado de la otra. |
| SmallGrid | `48` | Especifica líneas horizontales y verticales que se cruzan y están espaciadas un 50 por ciento más juntas que el estilo de sombreado Cross. |
| SmallCheckerBoard | `49` | Especifica un sombreado que tiene la apariencia de un tablero de ajedrez. |
| LargeCheckerBoard | `50` | Especifica un sombreado que tiene la apariencia de un tablero de ajedrez con cuadrados que tienen el doble del tamaño de SmallCheckerBoard. |
| OutlinedDiamond | `51` | Especifica líneas diagonales hacia adelante y diagonales hacia atrás que se cruzan pero no tienen suavizado. |
| SolidDiamond | `52` | Especifica un sombreado que tiene la apariencia de un tablero de ajedrez colocado en diagonal. |

### Ver también

* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
