---
title: "EmfVertexData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Objetos que especifican los vértices de rectángulos o triángulos y los colores que les corresponden."
type: docs
weight: 155
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
**Inheritance:**
java.lang.Object
```
public final class EmfVertexData
```

Objetos que especifican los vértices de rectángulos o triángulos y los colores que les corresponden.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfVertexData()](#EmfVertexData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getVertexObjects()](#getVertexObjects--) | Obtiene o establece una matriz de objetos nVer TriVertex (sección 2.2.26). |
| [setVertexObjects(EmfTriVertex[] value)](#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---) | Obtiene o establece una matriz de objetos nVer TriVertex (sección 2.2.26). |
| [getVertexIndexes()](#getVertexIndexes--) | Obtiene o establece una matriz de objetos nTri GradientRectangle (sección 2.2.7) o objetos GradientTriangle (sección 2.2.8), dependiendo del valor del campo ulMode. |
| [setVertexIndexes(EmfGradientRectangle[] value)](#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---) | Obtiene o establece una matriz de objetos nTri GradientRectangle (sección 2.2.7) o objetos GradientTriangle (sección 2.2.8), dependiendo del valor del campo ulMode. |
| [getVertexPadding()](#getVertexPadding--) | Obtiene o establece una matriz opcional de longitud variable de nTri multiplicado por cuatro bytes que DEBE estar presente si el valor del campo ulMode indica objetos GradientRectangle (sección 2.2.7). |
| [setVertexPadding(byte[] value)](#setVertexPadding-byte---) | Obtiene o establece una matriz opcional de longitud variable de nTri multiplicado por cuatro bytes que DEBE estar presente si el valor del campo ulMode indica objetos GradientRectangle (sección 2.2.7). |
### EmfVertexData() {#EmfVertexData--}
```
public EmfVertexData()
```


### getVertexObjects() {#getVertexObjects--}
```
public EmfTriVertex[] getVertexObjects()
```


Obtiene o establece una matriz de objetos nVer TriVertex (sección 2.2.26). Cada objeto especifica la posición y el color de un vértice de un rectángulo o un triángulo, dependiendo del valor del campo ulMode.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex[]
### setVertexObjects(EmfTriVertex[] value) {#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---}
```
public void setVertexObjects(EmfTriVertex[] value)
```


Obtiene o establece una matriz de objetos nVer TriVertex (sección 2.2.26). Cada objeto especifica la posición y el color de un vértice de un rectángulo o un triángulo, dependiendo del valor del campo ulMode.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfTriVertex\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftrivertex) |  |

### getVertexIndexes() {#getVertexIndexes--}
```
public EmfGradientRectangle[] getVertexIndexes()
```


Obtiene o establece una matriz de objetos nTri GradientRectangle (sección 2.2.7) o objetos GradientTriangle (sección 2.2.8), dependiendo del valor del campo ulMode. Cada objeto especifica índices en la matriz de objetos TriVertex en el campo VertexObjects.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle[]
### setVertexIndexes(EmfGradientRectangle[] value) {#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---}
```
public void setVertexIndexes(EmfGradientRectangle[] value)
```


Obtiene o establece una matriz de objetos nTri GradientRectangle (sección 2.2.7) o objetos GradientTriangle (sección 2.2.8), dependiendo del valor del campo ulMode. Cada objeto especifica índices en la matriz de objetos TriVertex en el campo VertexObjects.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfGradientRectangle\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle) |  |

### getVertexPadding() {#getVertexPadding--}
```
public byte[] getVertexPadding()
```


Obtiene o establece una matriz opcional de longitud variable de nTri multiplicado por cuatro bytes que DEBE estar presente si el valor del campo ulMode indica objetos GradientRectangle (sección 2.2.7). Si el valor del campo ulMode indica objetos GradientTriangle (sección 2.2.8), no hay VertexPadding presente. Este campo DEBE ser ignorado.

**Returns:**
byte[]
### setVertexPadding(byte[] value) {#setVertexPadding-byte---}
```
public void setVertexPadding(byte[] value)
```


Obtiene o establece una matriz opcional de longitud variable de nTri multiplicado por cuatro bytes que DEBE estar presente si el valor del campo ulMode indica objetos GradientRectangle (sección 2.2.7). Si el valor del campo ulMode indica objetos GradientTriangle (sección 2.2.8), no hay VertexPadding presente. Este campo DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

