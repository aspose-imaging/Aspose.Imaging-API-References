---
title: "EmfPlusColorCurveEffect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto ColorCurveEffect especifica uno de ocho ajustes a la curva de color de una imagen."
type: docs
weight: 27
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorCurveEffect extends EmfPlusImageEffectsObjectType
```

El objeto ColorCurveEffect especifica uno de ocho ajustes a la curva de color de una imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCurveAdjustment()](#getCurveAdjustment--) | Obtiene o establece un entero sin signo de 32 bits que especifica el ajuste de curva a aplicar a los colores en el mapa de bits. |
| [setCurveAdjustment(int value)](#setCurveAdjustment-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el ajuste de curva a aplicar a los colores en el mapa de bits. |
| [getCurveChannel()](#getCurveChannel--) | Obtiene o establece un entero sin signo de 32 bits que especifica el canal de color al que se aplica el ajuste de curva. |
| [setCurveChannel(int value)](#setCurveChannel-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el canal de color al que se aplica el ajuste de curva. |
| [getAdjustmentIntensity()](#getAdjustmentIntensity--) | Obtiene o establece un entero con signo de 32 bits que especifica la intensidad del ajuste de curva al canal de color especificado por CurveChannel. |
| [setAdjustmentIntensity(int value)](#setAdjustmentIntensity-int-) | Obtiene o establece un entero con signo de 32 bits que especifica la intensidad del ajuste de curva al canal de color especificado por CurveChannel. |
### EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect--}
```
public EmfPlusColorCurveEffect()
```


### getCurveAdjustment() {#getCurveAdjustment--}
```
public int getCurveAdjustment()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el ajuste de curva a aplicar a los colores en el mapa de bits. Este valor DEBE estar definido en la enumeración CurveAdjustments (sección 2.1.1.7).

**Returns:**
int
### setCurveAdjustment(int value) {#setCurveAdjustment-int-}
```
public void setCurveAdjustment(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el ajuste de curva a aplicar a los colores en el mapa de bits. Este valor DEBE estar definido en la enumeración CurveAdjustments (sección 2.1.1.7).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCurveChannel() {#getCurveChannel--}
```
public int getCurveChannel()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el canal de color al que se aplica el ajuste de curva. Este valor DEBE estar definido en la enumeración CurveChannel (sección 2.1.1.8).

**Returns:**
int
### setCurveChannel(int value) {#setCurveChannel-int-}
```
public void setCurveChannel(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el canal de color al que se aplica el ajuste de curva. Este valor DEBE estar definido en la enumeración CurveChannel (sección 2.1.1.8).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getAdjustmentIntensity() {#getAdjustmentIntensity--}
```
public int getAdjustmentIntensity()
```


Obtiene o establece un entero con signo de 32 bits que especifica la intensidad del ajuste de curva al canal de color especificado por CurveChannel. Los rangos de valores significativos para este campo varían según el valor de CurveAdjustment, como sigue: Rango de ajuste de exposición: -255 \\u2264 value < 0 A medida que el valor disminuye, la exposición de la imagen DEBERÁ disminuir. 0 Un valor de 0 especifica que la exposición NO DEBE cambiar. 0 < value \\u2264 255 A medida que el valor aumenta, la exposición de la imagen DEBERÁ aumentar. Rango de ajuste de densidad: -255 \\u2264 value < 0 A medida que el valor disminuye, la densidad de la imagen DEBERÁ disminuir, lo que produce una imagen más oscura. 0 Un valor de 0 especifica que la densidad NO DEBE cambiar. 0 < value \\u2264 255 A medida que el valor aumenta, la densidad de la imagen DEBERÁ aumentar. Rango de ajuste de contraste: -100 \\u2264 value < 0 A medida que el valor disminuye, el contraste de la imagen DEBERÁ disminuir. 0 Un valor de 0 especifica que el contraste NO DEBE cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, el contraste de la imagen DEBERÁ aumentar. Rango de ajuste de reflejos: -100 \\u2264 value < 0 A medida que el valor disminuye, las áreas claras de la imagen DEBERÁN aparecer más oscuras. 0 Un valor de 0 especifica que los reflejos NO DEBEN cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, las áreas claras de la imagen DEBERÁN aparecer más claras. Rango de ajuste de sombras: -100 \\u2264 value < 0 A medida que el valor disminuye, las áreas oscuras de la imagen DEBERÁN aparecer más oscuras. 0 Un valor de 0 especifica que las sombras NO DEBEN cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, las áreas oscuras de la imagen DEBERÁN aparecer más claras. Rango de ajuste de saturación blanca: 0 \\u2014 255 A medida que el valor aumenta, el límite superior del rango de intensidades del canal de color aumenta. Rango de ajuste de saturación negra: 0 \\u2014 255 A medida que el valor aumenta, el límite inferior del rango de intensidades del canal de color aumenta.

**Returns:**
int
### setAdjustmentIntensity(int value) {#setAdjustmentIntensity-int-}
```
public void setAdjustmentIntensity(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica la intensidad del ajuste de curva al canal de color especificado por CurveChannel. Los rangos de valores significativos para este campo varían según el valor de CurveAdjustment, como sigue: Rango de ajuste de exposición: -255 \\u2264 value < 0 A medida que el valor disminuye, la exposición de la imagen DEBERÁ disminuir. 0 Un valor de 0 especifica que la exposición NO DEBE cambiar. 0 < value \\u2264 255 A medida que el valor aumenta, la exposición de la imagen DEBERÁ aumentar. Rango de ajuste de densidad: -255 \\u2264 value < 0 A medida que el valor disminuye, la densidad de la imagen DEBERÁ disminuir, lo que produce una imagen más oscura. 0 Un valor de 0 especifica que la densidad NO DEBE cambiar. 0 < value \\u2264 255 A medida que el valor aumenta, la densidad de la imagen DEBERÁ aumentar. Rango de ajuste de contraste: -100 \\u2264 value < 0 A medida que el valor disminuye, el contraste de la imagen DEBERÁ disminuir. 0 Un valor de 0 especifica que el contraste NO DEBE cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, el contraste de la imagen DEBERÁ aumentar. Rango de ajuste de reflejos: -100 \\u2264 value < 0 A medida que el valor disminuye, las áreas claras de la imagen DEBERÁN aparecer más oscuras. 0 Un valor de 0 especifica que los reflejos NO DEBEN cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, las áreas claras de la imagen DEBERÁN aparecer más claras. Rango de ajuste de sombras: -100 \\u2264 value < 0 A medida que el valor disminuye, las áreas oscuras de la imagen DEBERÁN aparecer más oscuras. 0 Un valor de 0 especifica que las sombras NO DEBEN cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, las áreas oscuras de la imagen DEBERÁN aparecer más claras. Rango de ajuste de saturación blanca: 0 \\u2014 255 A medida que el valor aumenta, el límite superior del rango de intensidades del canal de color aumenta. Rango de ajuste de saturación negra: 0 \\u2014 255 A medida que el valor aumenta, el límite inferior del rango de intensidades del canal de color aumenta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

