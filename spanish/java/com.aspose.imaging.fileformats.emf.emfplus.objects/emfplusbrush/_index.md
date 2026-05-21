---
title: "EmfPlusBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusBrush especifica un pincel gráfico para rellenar regiones."
type: docs
weight: 24
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

El objeto EmfPlusBrush especifica un pincel gráfico para rellenar regiones.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBrushData()](#getBrushData--) | Obtiene o establece los datos del Brush Datos de longitud variable que definen el objeto pincel especificado en el campo Type. |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | Obtiene o establece los datos del Brush Datos de longitud variable que definen el objeto pincel especificado en el campo Type. |
| [getType()](#getType--) | Obtiene o establece el tipo. |
| [setType(int value)](#setType-int-) | Obtiene o establece el tipo. |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


Obtiene o establece los datos del Brush Datos de longitud variable que definen el objeto pincel especificado en el campo Type. El contenido y el formato de los datos pueden ser diferentes para cada tipo de pincel. EmfPlusHatchBrushData (sección 2.2.2.20) (hecho) EmfPlusLinearGradientBrushData object (sección 2.2.2.24) (hecho) EmfPlusPathGradientBrushData object (sección 2.2.2.29) (hecho) EmfPlusSolidBrushData object (sección 2.2.2.43) (hecho) EmfPlusTextureBrushData object (sección 2.2.2.45) (hecho)

Valor: Los datos del brush.

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


Obtiene o establece los datos del Brush Datos de longitud variable que definen el objeto pincel especificado en el campo Type. El contenido y el formato de los datos pueden ser diferentes para cada tipo de pincel. EmfPlusHatchBrushData (sección 2.2.2.20) (hecho) EmfPlusLinearGradientBrushData object (sección 2.2.2.24) (hecho) EmfPlusPathGradientBrushData object (sección 2.2.2.29) (hecho) EmfPlusSolidBrushData object (sección 2.2.2.43) (hecho) EmfPlusTextureBrushData object (sección 2.2.2.45) (hecho)

Valor: Los datos del brush.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


Obtiene o establece el tipo.

Valor: Un entero sin signo de 32 bits que especifica el tipo de brush, lo que determina el contenido del campo BrushData. Este valor DEBE estar definido en la enumeración `EmfPlusBrushType`.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtiene o establece el tipo.

Valor: Un entero sin signo de 32 bits que especifica el tipo de brush, lo que determina el contenido del campo BrushData. Este valor DEBE estar definido en la enumeración `EmfPlusBrushType`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

