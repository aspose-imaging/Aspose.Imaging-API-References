---
title: "EmfPlusTextureBrushOptionalData"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusTextureBrushOptionalData especifica datos opcionales para un pincel de textura."
type: docs
weight: 78
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

El objeto EmfPlusTextureBrushOptionalData especifica datos opcionales para un pincel de textura.

Nota: Cada campo de este objeto es opcional y puede no estar presente en el campo OptionalData de un objeto EmfPlusTextureBrushData (sección 2.2.2.45), dependiendo de los indicadores BrushData (sección 2.1.2.1) establecidos en su campo BrushDataFlags. Aunque no es práctico representar todas las combinaciones posibles de campos presentes o ausentes, esta sección especifica su orden relativo en el objeto. El implementador es responsable de determinar qué campos están realmente presentes en un registro de metafile dado, y de deserializar los datos de cada campo por separado y de manera adecuada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación del espacio mundial al espacio del dispositivo para el pincel de textura. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación del espacio mundial al espacio del dispositivo para el pincel de textura. |
| [getImageObject()](#getImageObject--) | Obtiene o establece un objeto opcional EmfPlusImage (sección 2.2.1.4) que especifica la textura del pincel. |
| [setImageObject(EmfPlusImage value)](#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-) | Obtiene o establece un objeto opcional EmfPlusImage (sección 2.2.1.4) que especifica la textura del pincel. |
### EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData--}
```
public EmfPlusTextureBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación del espacio mundial al espacio del dispositivo para el pincel de textura. Este campo DEBE estar presente si el indicador BrushDataTransform está establecido en el campo BrushDataFlags del objeto EmfPlusTextureBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Obtiene o establece un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica una transformación del espacio mundial al espacio del dispositivo para el pincel de textura. Este campo DEBE estar presente si el indicador BrushDataTransform está establecido en el campo BrushDataFlags del objeto EmfPlusTextureBrushData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


Obtiene o establece un objeto opcional EmfPlusImage (sección 2.2.1.4) que especifica la textura del pincel. Este campo DEBE estar presente si el tamaño del registro EmfPlusObject (sección 2.3.5.1) que define este pincel de textura es lo suficientemente grande como para acomodar un objeto EmfPlusImage además de los campos obligatorios del objeto EmfPlusTextureBrushData y, opcionalmente, un objeto EmfPlusTransformMatrix.

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


Obtiene o establece un objeto opcional EmfPlusImage (sección 2.2.1.4) que especifica la textura del pincel. Este campo DEBE estar presente si el tamaño del registro EmfPlusObject (sección 2.3.5.1) que define este pincel de textura es lo suficientemente grande como para acomodar un objeto EmfPlusImage además de los campos obligatorios del objeto EmfPlusTextureBrushData y, opcionalmente, un objeto EmfPlusTransformMatrix.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

