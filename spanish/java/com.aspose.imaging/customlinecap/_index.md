---
title: "CustomLineCap"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Encapsula un extremo de línea personalizado definido por el usuario."
type: docs
weight: 35
url: /es/java/com.aspose.imaging/customlinecap/
---
**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Encapsula un extremo de línea personalizado definido por el usuario.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-) | Inicializa una nueva instancia de la clase `CustomLineCap` con el contorno y relleno especificados. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-) | Inicializa una nueva instancia de la clase `CustomLineCap` a partir de la enumeración `LineCap` existente especificada, con el contorno y relleno especificados. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-) | Inicializa una nueva instancia de la clase `CustomLineCap` a partir de la enumeración `LineCap` existente especificada, con el contorno, relleno y sangrado especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillPath()](#getFillPath--) | Obtiene el objeto que define el relleno para la tapa personalizada. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.imaging.GraphicsPath-) | Establece el objeto que define el relleno para la tapa personalizada. |
| [getStrokePath()](#getStrokePath--) | Obtiene el objeto que define el contorno de la tapa personalizada. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.imaging.GraphicsPath-) | Establece el objeto que define el contorno de la tapa personalizada. |
| [getStrokeJoin()](#getStrokeJoin--) | Obtiene la enumeración `LineJoin` que determina cómo se unen las líneas que componen este objeto `CustomLineCap`. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Establece la enumeración `LineJoin` que determina cómo se unen las líneas que componen este objeto `CustomLineCap`. |
| [getBaseCap()](#getBaseCap--) | Obtiene la enumeración `LineCap` en la que se basa este `CustomLineCap`. |
| [setBaseCap(int value)](#setBaseCap-int-) | Establece la enumeración `LineCap` en la que se basa este `CustomLineCap`. |
| [getBaseInset()](#getBaseInset--) | Obtiene la distancia entre la tapa y la línea. |
| [setBaseInset(float value)](#setBaseInset-float-) | Establece la distancia entre la tapa y la línea. |
| [getWidthScale()](#getWidthScale--) | Obtiene la cantidad por la cual escalar este objeto de clase `CustomLineCap` con respecto al ancho del objeto `System.Drawing.Pen`. |
| [setWidthScale(float value)](#setWidthScale-float-) | Establece la cantidad por la cual escalar este objeto de clase `CustomLineCap` con respecto al ancho del objeto `System.Drawing.Pen`. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Establece las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Obtiene las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Inicializa una nueva instancia de la clase `CustomLineCap` con el contorno y relleno especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objeto `GraphicsPath` que define el relleno para la tapa personalizada. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objeto `GraphicsPath` que define el contorno de la tapa personalizada. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Inicializa una nueva instancia de la clase `CustomLineCap` a partir de la enumeración `LineCap` existente especificada, con el contorno y relleno especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objeto `GraphicsPath` que define el relleno para la tapa personalizada. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objeto `GraphicsPath` que define el contorno de la tapa personalizada. |
| baseCap | int | La tapa de línea a partir de la cual crear la tapa personalizada. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Inicializa una nueva instancia de la clase `CustomLineCap` a partir de la enumeración `LineCap` existente especificada, con el contorno, relleno y sangrado especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objeto `GraphicsPath` que define el relleno para la tapa personalizada. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Un objeto `GraphicsPath` que define el contorno de la tapa personalizada. |
| baseCap | int | La tapa de línea a partir de la cual crear la tapa personalizada. |
| baseInset | float | La distancia entre la tapa y la línea. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Obtiene el objeto que define el relleno para la tapa personalizada.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the fill for the custom cap.
### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.imaging.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Establece el objeto que define el relleno para la tapa personalizada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | El objeto que define el relleno para la tapa personalizada. |

### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Obtiene el objeto que define el contorno de la tapa personalizada.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the outline of the custom cap.
### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.imaging.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Establece el objeto que define el contorno de la tapa personalizada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | El objeto que define el contorno de la tapa personalizada. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Obtiene la enumeración `LineJoin` que determina cómo se unen las líneas que componen este objeto `CustomLineCap`.

**Returns:**
int - La enumeración `LineJoin` que este objeto `CustomLineCap` usa para unir líneas.
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Establece la enumeración `LineJoin` que determina cómo se unen las líneas que componen este objeto `CustomLineCap`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La enumeración `LineJoin` que este objeto `CustomLineCap` usa para unir líneas. |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Obtiene la enumeración `LineCap` en la que se basa este `CustomLineCap`.

**Returns:**
int - La enumeración `LineCap` en la que se basa este `CustomLineCap`.
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Establece la enumeración `LineCap` en la que se basa este `CustomLineCap`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La enumeración `LineCap` en la que se basa este `CustomLineCap`. |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Obtiene la distancia entre la tapa y la línea.

**Returns:**
float - La distancia entre el comienzo del extremo y el final de la línea.
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Establece la distancia entre la tapa y la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | La distancia entre el comienzo del extremo y el final de la línea. |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Obtiene la cantidad por la cual escalar este objeto de clase `CustomLineCap` con respecto al ancho del objeto `System.Drawing.Pen`.

**Returns:**
float - La cantidad por la cual escalar el extremo.
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Establece la cantidad por la cual escalar este objeto de clase `CustomLineCap` con respecto al ancho del objeto `System.Drawing.Pen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | La cantidad por la cual escalar el extremo. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Establece las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startCap | int | La enumeración `LineCap` utilizada al comienzo de una línea dentro de este extremo. |
| endCap | int | La enumeración `LineCap` utilizada al final de una línea dentro de este extremo. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Obtiene las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startCap | int[] | La enumeración `LineCap` utilizada al comienzo de una línea dentro de este extremo. |
| endCap | int[] | La enumeración `LineCap` utilizada al final de una línea dentro de este extremo. |

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
