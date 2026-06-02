---
title: "EmfPlusColorCurveEffect Class"
type: docs
weight: 180
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---

**Summary:** The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorCurveEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect__1) | Inicializa una nueva instancia de la clase EmfPlusColorCurveEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| adjustment_intensity | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la intensidad del<br/>            ajuste de curva al canal de color especificado por CurveChannel. Los rangos de valores significativos<br/>            para este campo varían según el valor de CurveAdjustment, como sigue:<br/>            Rango de ajuste de exposición:<br/>            -255 ≤ value &lt; 0 A medida que el valor disminuye, la exposición de la imagen DEBERÍA disminuir.<br/>            0 Un valor de 0 especifica que la exposición NO DEBE cambiar.<br/>            0 &lt; value ≤ 255 A medida que el valor aumenta, la exposición de la imagen DEBERÍA aumentar.<br/>            Rango de ajuste de densidad:<br/>            -255 ≤ value &lt; 0<br/>            A medida que el valor disminuye, la densidad de la imagen DEBERÍA disminuir, lo que resulta en<br/>            una imagen más oscura.<br/>            0 Un valor de 0 especifica que la densidad NO DEBE cambiar.<br/>            0 &lt; value ≤ 255<br/>            A medida que el valor aumenta, la densidad de la imagen DEBERÍA aumentar.<br/>            Rango de ajuste de contraste:<br/>            -100 ≤ value &lt; 0 A medida que el valor disminuye, el contraste de la imagen DEBERÍA disminuir.<br/>            0 Un valor de 0 especifica que el contraste NO DEBE cambiar.<br/>            0 &lt; value ≤ 100 A medida que el valor aumenta, el contraste de la imagen DEBERÍA aumentar.<br/>            Rango de ajuste de reflejos:<br/>            -100 ≤ value &lt; 0 A medida que el valor disminuye, las áreas claras de la imagen DEBERÍAN aparecer más oscuras.<br/>            0 Un valor de 0 especifica que los reflejos NO DEBEN cambiar.<br/>            0 &lt; value ≤ 100 A medida que el valor aumenta, las áreas claras de la imagen DEBERÍAN aparecer más claras.<br/>            Rango de ajuste de sombras:<br/>            -100 ≤ value &lt; 0 A medida que el valor disminuye, las áreas oscuras de la imagen DEBERÍAN aparecer más oscuras.<br/>            0 Un valor de 0 especifica que las sombras NO DEBEN cambiar.<br/>            0 &lt; value ≤ 100 A medida que el valor aumenta, las áreas oscuras de la imagen DEBERÍAN aparecer más claras.<br/>            Rango de ajuste de saturación blanca:<br/>            0 — 255 A medida que el valor aumenta, el límite superior del rango de intensidades del canal de color aumenta.<br/>            Rango de ajuste de saturación negra:<br/>            0 — 255 A medida que el valor aumenta, el límite inferior del rango de intensidades del canal de color aumenta. |
| curve_adjustment | [EmfPlusCurveAdjustments](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el ajuste de curva a<br/>            aplicar a los colores en el mapa de bits. Este valor DEBE estar definido en la enumeración CurveAdjustments<br/>            (sección 2.1.1.7). |
| curve_channel | [EmfPlusCurveChannel](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurvechannel/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el canal de color al que se aplica el ajuste de curva. Este valor DEBE estar definido en la enumeración CurveChannel<br/>            (sección 2.1.1.8). |


### Constructor: EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect__1}


```
 EmfPlusColorCurveEffect() 
```

Inicializa una nueva instancia de la clase EmfPlusColorCurveEffect

