---
title: "CmxEllipseSpec"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa la información geométrica especificada para una elipse."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxEllipseSpec implements ICmxObjectSpec
```

Representa la información geométrica especificada para una elipse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CmxEllipseSpec()](#CmxEllipseSpec--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getAngle1()](#getAngle1--) | Obtiene el primer ángulo usado para definir el sector de pastel. |
| [setAngle1(float value)](#setAngle1-float-) | Establece el primer ángulo usado para definir el sector de pastel. |
| [getAngle2()](#getAngle2--) | Obtiene el segundo ángulo usado para definir el sector de pastel. |
| [setAngle2(float value)](#setAngle2-float-) | Establece el segundo ángulo usado para definir el sector de pastel. |
| [getRotation()](#getRotation--) | Obtiene el ángulo de rotación de la elipse. |
| [setRotation(float value)](#setRotation-float-) | Establece el ángulo de rotación de la elipse. |
| [getPie()](#getPie--) | Obtiene un valor que indica si este [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) es un pastel. |
| [setPie(boolean value)](#setPie-boolean-) | Establece un valor que indica si este [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) es un pastel. |
| [getCenterX()](#getCenterX--) | Obtiene la coordenada X del centro del rectángulo. |
| [setCenterX(float value)](#setCenterX-float-) | Establece la coordenada X del centro del rectángulo. |
| [getCenterY()](#getCenterY--) | Obtiene la coordenada Y del centro del rectángulo. |
| [setCenterY(float value)](#setCenterY-float-) | Establece la coordenada Y del centro del rectángulo. |
| [getDiameterX()](#getDiameterX--) | Obtiene el diámetro para la dimensión X del rectángulo. |
| [setDiameterX(float value)](#setDiameterX-float-) | Establece el diámetro para la dimensión X del rectángulo. |
| [getDiameterY()](#getDiameterY--) | Obtiene el diámetro para la dimensión Y del rectángulo. |
| [setDiameterY(float value)](#setDiameterY-float-) | Establece el diámetro para la dimensión Y del rectángulo. |
| [getBoundingBox()](#getBoundingBox--) | Obtiene el cuadro delimitador. |
| [setBoundingBox(RectangleF value)](#setBoundingBox-com.aspose.imaging.RectangleF-) | Establece el cuadro delimitador. |
| [toString()](#toString--) | Devuelve una cadena que representa esta instancia. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |
### CmxEllipseSpec() {#CmxEllipseSpec--}
```
public CmxEllipseSpec()
```


### getAngle1() {#getAngle1--}
```
public final float getAngle1()
```


Obtiene el primer ángulo usado para definir el sector de pastel. No afecta si `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) es `false`. Se mide en radianes.

**Returns:**
float - el primer ángulo usado para definir el sector de pastel.
### setAngle1(float value) {#setAngle1-float-}
```
public final void setAngle1(float value)
```


Establece el primer ángulo usado para definir el sector de pastel. No afecta si `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) es `false`. Se mide en radianes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el primer ángulo usado para definir el sector de pastel. |

### getAngle2() {#getAngle2--}
```
public final float getAngle2()
```


Obtiene el segundo ángulo usado para definir el sector de pastel. No afecta si `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) es `false`. Mide en radianes.

**Returns:**
float - el segundo ángulo usado para definir el sector de pastel.
### setAngle2(float value) {#setAngle2-float-}
```
public final void setAngle2(float value)
```


Establece el segundo ángulo usado para definir el sector de pastel. No afecta si `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) es `false`. Mide en radianes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el segundo ángulo usado para definir el sector de pastel. |

### getRotation() {#getRotation--}
```
public final float getRotation()
```


Obtiene el ángulo de rotación de la elipse. Mide en radianes.

**Returns:**
float - el ángulo de rotación de la elipse.
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```


Establece el ángulo de rotación de la elipse. Mide en radianes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el ángulo de rotación de la elipse. |

### getPie() {#getPie--}
```
public final boolean getPie()
```


Obtiene un valor que indica si este [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) es un pastel.

**Returns:**
boolean - un valor que indica si este [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) es un pastel.
### setPie(boolean value) {#setPie-boolean-}
```
public final void setPie(boolean value)
```


Establece un valor que indica si este [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) es un pastel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | un valor que indica si este [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) es un pastel. |

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Obtiene la coordenada X del centro del rectángulo. Mide en unidades de distancia comunes del documento.

**Returns:**
float - la coordenada X del centro del rectángulo.
### setCenterX(float value) {#setCenterX-float-}
```
public final void setCenterX(float value)
```


Establece la coordenada X del centro del rectángulo. Mide en unidades de distancia comunes del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | la coordenada X del centro del rectángulo. |

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Obtiene la coordenada Y del centro del rectángulo. Se mide en unidades de distancia comunes del documento.

**Returns:**
float - la coordenada Y del centro del rectángulo.
### setCenterY(float value) {#setCenterY-float-}
```
public final void setCenterY(float value)
```


Establece la coordenada Y del centro del rectángulo. Se mide en unidades de distancia comunes del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | la coordenada Y del centro del rectángulo. |

### getDiameterX() {#getDiameterX--}
```
public final float getDiameterX()
```


Obtiene el diámetro para la dimensión X del rectángulo. Mide en unidades de distancia comunes del documento.

**Returns:**
float - el diámetro para la dimensión X del rectángulo.
### setDiameterX(float value) {#setDiameterX-float-}
```
public final void setDiameterX(float value)
```


Establece el diámetro para la dimensión X del rectángulo. Mide en unidades de distancia comunes del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el diámetro para la dimensión X del rectángulo. |

### getDiameterY() {#getDiameterY--}
```
public final float getDiameterY()
```


Obtiene el diámetro para la dimensión Y del rectángulo. Mide en unidades de distancia comunes del documento.

**Returns:**
float - el diámetro para la dimensión Y del rectángulo.
### setDiameterY(float value) {#setDiameterY-float-}
```
public final void setDiameterY(float value)
```


Establece el diámetro para la dimensión Y del rectángulo. Mide en unidades de distancia comunes del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el diámetro para la dimensión Y del rectángulo. |

### getBoundingBox() {#getBoundingBox--}
```
public final RectangleF getBoundingBox()
```


Obtiene el cuadro delimitador.

Valor: el cuadro delimitador.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bounding box.
### setBoundingBox(RectangleF value) {#setBoundingBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundingBox(RectangleF value)
```


Establece el cuadro delimitador.

Valor: el cuadro delimitador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | el cuadro delimitador. |

### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa esta instancia.

**Returns:**
java.lang.String - Una cadena que representa esta instancia.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Comprueba si los objetos son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | java.lang.Object | El otro objeto. |

**Returns:**
boolean - El resultado de la comparación de igualdad.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del objeto actual.

**Returns:**
int - El código hash.
