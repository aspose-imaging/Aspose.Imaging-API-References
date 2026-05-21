---
title: "EmfPlusColorBalanceEffect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto ColorBalanceEffect especifica ajustes a las cantidades relativas de rojo, verde y azul en una imagen."
type: docs
weight: 26
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorBalanceEffect extends EmfPlusImageEffectsObjectType
```

El objeto ColorBalanceEffect especifica ajustes a las cantidades relativas de rojo, verde y azul en una imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCyanRed()](#getCyanRed--) | Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de rojo en la imagen. |
| [setCyanRed(int value)](#setCyanRed-int-) | Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de rojo en la imagen. |
| [getMagentaGreen()](#getMagentaGreen--) | Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de verde en la imagen. |
| [setMagentaGreen(int value)](#setMagentaGreen-int-) | Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de verde en la imagen. |
| [getYellowBlue()](#getYellowBlue--) | Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de azul en la imagen. |
| [setYellowBlue(int value)](#setYellowBlue-int-) | Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de azul en la imagen. |
### EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect--}
```
public EmfPlusColorBalanceEffect()
```


### getCyanRed() {#getCyanRed--}
```
public int getCyanRed()
```


Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de rojo en la imagen. Este valor DEBE estar en el rango -100 a 100, con los siguientes efectos: -100 \\u2264 value < 0 A medida que el valor disminuye, la cantidad de rojo en la imagen DEBERÍA disminuir y la cantidad de cian DEBERÍA aumentar. 0 Un valor de 0 especifica que las cantidades de rojo y cian NO DEBEN cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, la cantidad de rojo en la imagen DEBERÍA aumentar y la cantidad de cian DEBERÍA disminuir.

**Returns:**
int
### setCyanRed(int value) {#setCyanRed-int-}
```
public void setCyanRed(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de rojo en la imagen. Este valor DEBE estar en el rango -100 a 100, con los siguientes efectos: -100 \\u2264 value < 0 A medida que el valor disminuye, la cantidad de rojo en la imagen DEBERÍA disminuir y la cantidad de cian DEBERÍA aumentar. 0 Un valor de 0 especifica que las cantidades de rojo y cian NO DEBEN cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, la cantidad de rojo en la imagen DEBERÍA aumentar y la cantidad de cian DEBERÍA disminuir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMagentaGreen() {#getMagentaGreen--}
```
public int getMagentaGreen()
```


Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de verde en la imagen. Este valor DEBE estar en el rango -100 a 100, con los siguientes efectos: -100 \\u2264 value < 0 A medida que el valor disminuye, la cantidad de verde en la imagen DEBERÍA disminuir y la cantidad de magenta DEBERÍA aumentar. 0 Un valor de 0 especifica que las cantidades de verde y magenta NO DEBEN cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, la cantidad de verde en la imagen DEBERÍA aumentar y la cantidad de magenta DEBERÍA disminuir.

**Returns:**
int
### setMagentaGreen(int value) {#setMagentaGreen-int-}
```
public void setMagentaGreen(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de verde en la imagen. Este valor DEBE estar en el rango -100 a 100, con los siguientes efectos: -100 \\u2264 value < 0 A medida que el valor disminuye, la cantidad de verde en la imagen DEBERÍA disminuir y la cantidad de magenta DEBERÍA aumentar. 0 Un valor de 0 especifica que las cantidades de verde y magenta NO DEBEN cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, la cantidad de verde en la imagen DEBERÍA aumentar y la cantidad de magenta DEBERÍA disminuir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getYellowBlue() {#getYellowBlue--}
```
public int getYellowBlue()
```


Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de azul en la imagen. Este valor DEBE estar en el rango -100 a 100, con los siguientes efectos: -100 \\u2264 value < 0 A medida que el valor disminuye, la cantidad de azul en la imagen DEBERÍA disminuir y la cantidad de amarillo DEBERÍA aumentar. 0 Un valor de 0 especifica que las cantidades de azul y amarillo NO DEBEN cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, la cantidad de azul en la imagen DEBERÍA aumentar y la cantidad de amarillo DEBERÍA disminuir.

**Returns:**
int
### setYellowBlue(int value) {#setYellowBlue-int-}
```
public void setYellowBlue(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica un cambio en la cantidad de azul en la imagen. Este valor DEBE estar en el rango -100 a 100, con los siguientes efectos: -100 \\u2264 value < 0 A medida que el valor disminuye, la cantidad de azul en la imagen DEBERÍA disminuir y la cantidad de amarillo DEBERÍA aumentar. 0 Un valor de 0 especifica que las cantidades de azul y amarillo NO DEBEN cambiar. 0 < value \\u2264 100 A medida que el valor aumenta, la cantidad de azul en la imagen DEBERÍA aumentar y la cantidad de amarillo DEBERÍA disminuir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

