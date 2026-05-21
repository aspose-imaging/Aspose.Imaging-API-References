---
title: "EmfPlusRedEyeCorrectionEffect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto RedEyeCorrectionEffect especifica áreas de una imagen a las que se aplica una corrección de ojos rojos."
type: docs
weight: 67
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusredeyecorrectioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusRedEyeCorrectionEffect extends EmfPlusImageEffectsObjectType
```

El objeto RedEyeCorrectionEffect especifica áreas de una imagen a las que se aplica una corrección de ojos rojos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusRedEyeCorrectionEffect()](#EmfPlusRedEyeCorrectionEffect--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getNumberOfAreas()](#getNumberOfAreas--) | Obtiene o establece el entero con signo de 32 bits que especifica el número de rectángulos en el campo Areas. |
| [setNumberOfAreas(int value)](#setNumberOfAreas-int-) | Obtiene o establece el entero con signo de 32 bits que especifica el número de rectángulos en el campo Areas. |
| [getAreas()](#getAreas--) | Obtiene o establece la matriz de objetos NumberOfAreas WMF RectL, especificada en la sección 2.2.2.19 de [MS-WMF]. |
| [setAreas(Rectangle[] value)](#setAreas-com.aspose.imaging.Rectangle---) | Obtiene o establece la matriz de objetos NumberOfAreas WMF RectL, especificada en la sección 2.2.2.19 de [MS-WMF]. |
### EmfPlusRedEyeCorrectionEffect() {#EmfPlusRedEyeCorrectionEffect--}
```
public EmfPlusRedEyeCorrectionEffect()
```


### getNumberOfAreas() {#getNumberOfAreas--}
```
public int getNumberOfAreas()
```


Obtiene o establece el entero con signo de 32 bits que especifica el número de rectángulos en el campo Areas.

Valor: El número de áreas.

**Returns:**
int
### setNumberOfAreas(int value) {#setNumberOfAreas-int-}
```
public void setNumberOfAreas(int value)
```


Obtiene o establece el entero con signo de 32 bits que especifica el número de rectángulos en el campo Areas.

Valor: El número de áreas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getAreas() {#getAreas--}
```
public Rectangle[] getAreas()
```


Obtiene o establece la matriz de objetos NumberOfAreas WMF RectL, especificada en la sección 2.2.2.19 de [MS-WMF]. Cada rectángulo especifica un área de la imagen bitmap a la que DEBERÍA aplicarse el efecto de corrección de ojos rojos.

Valor: Las áreas.

**Returns:**
com.aspose.imaging.Rectangle[]
### setAreas(Rectangle[] value) {#setAreas-com.aspose.imaging.Rectangle---}
```
public void setAreas(Rectangle[] value)
```


Obtiene o establece la matriz de objetos NumberOfAreas WMF RectL, especificada en la sección 2.2.2.19 de [MS-WMF]. Cada rectángulo especifica un área de la imagen bitmap a la que DEBERÍA aplicarse el efecto de corrección de ojos rojos.

Valor: Las áreas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

