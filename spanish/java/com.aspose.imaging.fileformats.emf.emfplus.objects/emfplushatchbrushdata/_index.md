---
title: "EmfPlusHatchBrushData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusHatchBrushData especifica un patrón de trama para un pincel gráfico."
type: docs
weight: 45
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusHatchBrushData extends EmfPlusBaseBrushData
```

El objeto EmfPlusHatchBrushData especifica un patrón de trama para un pincel gráfico.

Los pinceles gráficos se especifican mediante objetos `EmfPlusBrush` (sección 2.2.1.1). Un pincel de trama pinta un fondo y dibuja un patrón de líneas, puntos, guiones, cuadrados y líneas cruzadas sobre ese fondo. El pincel de trama define dos colores: uno para el fondo y otro para el patrón sobre el fondo. El color del fondo se llama color de fondo, y el color del patrón se llama color de primer plano.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusHatchBrushData()](#EmfPlusHatchBrushData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBackArgb32Color()](#getBackArgb32Color--) | Obtiene o establece un objeto EmfPlusArgb de 32 bits que especifica el color utilizado para pintar el fondo del patrón de trama. |
| [setBackArgb32Color(int value)](#setBackArgb32Color-int-) | Obtiene o establece un objeto EmfPlusArgb de 32 bits que especifica el color utilizado para pintar el fondo del patrón de trama. |
| [getForeArgb32Color()](#getForeArgb32Color--) | Obtiene o establece un objeto EmfPlusArgb de 32 bits que especifica el color utilizado para dibujar las líneas del patrón de trama. |
| [setForeArgb32Color(int value)](#setForeArgb32Color-int-) | Obtiene o establece un objeto EmfPlusArgb de 32 bits que especifica el color utilizado para dibujar las líneas del patrón de trama. |
| [getHatchStyle()](#getHatchStyle--) | Obtiene o establece un entero sin signo de 32 bits que especifica el estilo de trama del pincel. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el estilo de trama del pincel. |
### EmfPlusHatchBrushData() {#EmfPlusHatchBrushData--}
```
public EmfPlusHatchBrushData()
```


### getBackArgb32Color() {#getBackArgb32Color--}
```
public int getBackArgb32Color()
```


Obtiene o establece un objeto EmfPlusArgb de 32 bits que especifica el color utilizado para pintar el fondo del patrón de trama.

**Returns:**
int
### setBackArgb32Color(int value) {#setBackArgb32Color-int-}
```
public void setBackArgb32Color(int value)
```


Obtiene o establece un objeto EmfPlusArgb de 32 bits que especifica el color utilizado para pintar el fondo del patrón de trama.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getForeArgb32Color() {#getForeArgb32Color--}
```
public int getForeArgb32Color()
```


Obtiene o establece un objeto EmfPlusArgb de 32 bits que especifica el color utilizado para dibujar las líneas del patrón de trama.

**Returns:**
int
### setForeArgb32Color(int value) {#setForeArgb32Color-int-}
```
public void setForeArgb32Color(int value)
```


Obtiene o establece un objeto EmfPlusArgb de 32 bits que especifica el color utilizado para dibujar las líneas del patrón de trama.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el estilo de trama del pincel. DEBE estar definido en la enumeración `EmfPlusHatchStyle`.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el estilo de trama del pincel. DEBE estar definido en la enumeración `EmfPlusHatchStyle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

