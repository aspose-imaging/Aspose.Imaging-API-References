---
title: "EmfPlusLineCapType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración LineCapType define tipos de capuchas de línea para usar en los extremos de líneas que se dibujan con lápices gráficos."
type: docs
weight: 31
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusLineCapType extends System.Enum
```

La enumeración LineCapType define tipos de capuchas de línea para usar en los extremos de líneas que se dibujan con lápices gráficos.

--------------------

Los acabados de línea de Graphics se especifican mediante objetos [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) (sección 2.2.1.7).
## Campos

| Campo | Descripción |
| --- | --- |
| [LineCapTypeFlat](#LineCapTypeFlat) | Especifica un acabado de línea cuadrado. |
| [LineCapTypeSquare](#LineCapTypeSquare) | Especifica una tapa cuadrada. |
| [LineCapTypeRound](#LineCapTypeRound) | Especifica un acabado de línea circular. |
| [LineCapTypeTriangle](#LineCapTypeTriangle) | Especifica una tapa triangular. |
| [LineCapTypeNoAnchor](#LineCapTypeNoAnchor) | Especifica que el extremo de la línea no está anclado. |
| [LineCapTypeSquareAnchor](#LineCapTypeSquareAnchor) | Especifica que el extremo de la línea está anclado con un acabado de línea cuadrado. |
| [LineCapTypeRoundAnchor](#LineCapTypeRoundAnchor) | Especifica que el extremo de la línea está anclado con un acabado de línea circular. |
| [LineCapTypeDiamondAnchor](#LineCapTypeDiamondAnchor) | Especifica que el extremo de la línea está anclado con un acabado de línea en forma de diamante, que es un cuadrado girado 45 grados. |
| [LineCapTypeArrowAnchor](#LineCapTypeArrowAnchor) | Especifica que el extremo de la línea está anclado con una forma de punta de flecha. |
| [LineCapTypeAnchorMask](#LineCapTypeAnchorMask) | Máscara utilizada para comprobar si un acabado de línea es un acabado de anclaje. |
| [LineCapTypeCustom](#LineCapTypeCustom) | Especifica una tapa de línea personalizada. |
### LineCapTypeFlat {#LineCapTypeFlat}
```
public static final int LineCapTypeFlat
```


Especifica un acabado de línea cuadrado. El extremo de la línea MUST ser el último punto de la línea.

### LineCapTypeSquare {#LineCapTypeSquare}
```
public static final int LineCapTypeSquare
```


Especifica un acabado de línea cuadrado. El centro del cuadrado MUST estar ubicado en el último punto de la línea. El ancho del cuadrado es el ancho de la línea.

### LineCapTypeRound {#LineCapTypeRound}
```
public static final int LineCapTypeRound
```


Especifica un acabado de línea circular. El centro del círculo MUST estar ubicado en el último punto de la línea. El diámetro del círculo es el ancho de la línea.

### LineCapTypeTriangle {#LineCapTypeTriangle}
```
public static final int LineCapTypeTriangle
```


Especifica un acabado de línea triangular. La base del triángulo MUST estar ubicada en el último punto de la línea. La base del triángulo es el ancho de la línea.

### LineCapTypeNoAnchor {#LineCapTypeNoAnchor}
```
public static final int LineCapTypeNoAnchor
```


Especifica que el extremo de la línea no está anclado.

### LineCapTypeSquareAnchor {#LineCapTypeSquareAnchor}
```
public static final int LineCapTypeSquareAnchor
```


Especifica que el extremo de la línea está anclado con un acabado de línea cuadrado. El centro del cuadrado MUST estar ubicado en el último punto de la línea. La altura y el ancho del cuadrado son el ancho de la línea.

### LineCapTypeRoundAnchor {#LineCapTypeRoundAnchor}
```
public static final int LineCapTypeRoundAnchor
```


Especifica que el extremo de la línea está anclado con un acabado de línea circular. El centro del círculo MUST estar ubicado en el último punto de la línea. El círculo SHOULD ser más ancho que la línea.

### LineCapTypeDiamondAnchor {#LineCapTypeDiamondAnchor}
```
public static final int LineCapTypeDiamondAnchor
```


Especifica que el extremo de la línea está anclado con un acabado de línea en forma de diamante, que es un cuadrado girado 45 grados. El centro del diamante MUST estar ubicado en el último punto de la línea. El diamante SHOULD ser más ancho que la línea.

### LineCapTypeArrowAnchor {#LineCapTypeArrowAnchor}
```
public static final int LineCapTypeArrowAnchor
```


Especifica que el extremo de la línea está anclado con una forma de punta de flecha. El punto de la punta de flecha MUST estar ubicado en el último punto de la línea. La punta de flecha SHOULD ser más ancha que la línea.

### LineCapTypeAnchorMask {#LineCapTypeAnchorMask}
```
public static final int LineCapTypeAnchorMask
```


Máscara utilizada para comprobar si un acabado de línea es un acabado de anclaje.

### LineCapTypeCustom {#LineCapTypeCustom}
```
public static final int LineCapTypeCustom
```


Especifica una tapa de línea personalizada.

