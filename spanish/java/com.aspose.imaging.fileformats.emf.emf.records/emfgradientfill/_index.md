---
title: "EmfGradientFill"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_GRADIENTFILL especifica el relleno de rectángulos o triángulos con degradados de color."
type: docs
weight: 65
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfGradientFill extends EmfDrawingRecordType
```

El registro EMR\_GRADIENTFILL especifica el relleno de rectángulos o triángulos con gradientes de color.

Un registro EMR_GRADIENTFILL que especifica que los tres vértices de un triángulo DEBEN rellenar la figura con degradados suaves de colores.[85] Un registro EMR_GRADIENTFILL que especifica que los vértices superior‑izquierdo e inferior‑derecho de un rectángulo DEBEN rellenar la figura con degradados suaves de color. Existen dos modos de relleno degradado en la enumeración GradientFill que pueden usarse al dibujar un rectángulo. En el modo GRADIENT_FILL_RECT_H, el rectángulo se rellena de izquierda a derecha. En el modo GRADIENT_FILL_RECT_V, el rectángulo se rellena de arriba a abajo. Nota: Un registro EMR_GRADIENTFILL DEBE ignorar los campos Alpha en los objetos TriVertex. Un registro EMR_ALPHABLEND (sección 2.3.1.1) que sigue inmediatamente al registro EMR_GRADIENTFILL puede usarse para aplicar un degradado de transparencia alfa al área rellenada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfGradientFill(EmfRecord source)](#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfGradientFill`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica un rectángulo delimitador, en unidades de dispositivo inclusivas‑inclusivas. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica un rectángulo delimitador, en unidades de dispositivo inclusivas‑inclusivas. |
| [getNVer()](#getNVer--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de vértices. |
| [setNVer(int value)](#setNVer-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de vértices. |
| [getNTri()](#getNTri--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de rectángulos o triángulos a rellenar. |
| [setNTri(int value)](#setNTri-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de rectángulos o triángulos a rellenar. |
| [getUlMode()](#getUlMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de relleno degradado. |
| [setUlMode(int value)](#setUlMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de relleno degradado. |
| [getVertexData()](#getVertexData--) | Obtiene o establece los objetos que especifican los vértices de rectángulos o triángulos y los colores que les corresponden. |
| [setVertexData(EmfVertexData value)](#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-) | Obtiene o establece los objetos que especifican los vértices de rectángulos o triángulos y los colores que les corresponden. |
### EmfGradientFill(EmfRecord source) {#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGradientFill(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfGradientFill`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica un rectángulo delimitador, en unidades de dispositivo inclusivas‑inclusivas.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica un rectángulo delimitador, en unidades de dispositivo inclusivas‑inclusivas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNVer() {#getNVer--}
```
public int getNVer()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de vértices.

**Returns:**
int
### setNVer(int value) {#setNVer-int-}
```
public void setNVer(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de vértices.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getNTri() {#getNTri--}
```
public int getNTri()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de rectángulos o triángulos a rellenar.

**Returns:**
int
### setNTri(int value) {#setNTri-int-}
```
public void setNTri(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de rectángulos o triángulos a rellenar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getUlMode() {#getUlMode--}
```
public int getUlMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo de relleno de degradado. El valor DEBE estar en la enumeración GradientFill (sección 2.1.15).

**Returns:**
int
### setUlMode(int value) {#setUlMode-int-}
```
public void setUlMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo de relleno de degradado. El valor DEBE estar en la enumeración GradientFill (sección 2.1.15).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVertexData() {#getVertexData--}
```
public EmfVertexData getVertexData()
```


Obtiene o establece los objetos que especifican los vértices de rectángulos o triángulos y los colores que les corresponden.

**Returns:**
[EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata)
### setVertexData(EmfVertexData value) {#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-}
```
public void setVertexData(EmfVertexData value)
```


Obtiene o establece los objetos que especifican los vértices de rectángulos o triángulos y los colores que les corresponden.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata) |  |

