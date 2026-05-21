---
title: "EmfPlusImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusImage especifica una imagen gráfica en forma de mapa de bits o metafichero."
type: docs
weight: 47
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImage extends EmfPlusGraphicsObjectType
```

El objeto EmfPlusImage especifica una imagen gráfica en forma de mapa de bits o metafichero.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusImage()](#EmfPlusImage--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getImageData()](#getImageData--) | Obtiene o establece los datos de Imagen de longitud variable que definen los datos de imagen especificados en el campo Type. |
| [setImageData(EmfPlusBaseImageData value)](#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-) | Obtiene o establece los datos de Imagen de longitud variable que definen los datos de imagen especificados en el campo Type. |
| [getType()](#getType--) | Obtiene o establece el tipo de imagen, un entero sin signo de 32 bits que especifica el tipo de datos en el campo ImageData. |
| [setType(int value)](#setType-int-) | Obtiene o establece el tipo de imagen, un entero sin signo de 32 bits que especifica el tipo de datos en el campo ImageData. |
### EmfPlusImage() {#EmfPlusImage--}
```
public EmfPlusImage()
```


### getImageData() {#getImageData--}
```
public EmfPlusBaseImageData getImageData()
```


Obtiene o establece los datos de Imagen de longitud variable que definen los datos de imagen especificados en el campo Type. El contenido y el formato de los datos pueden ser diferentes para cada tipo de imagen.

**Returns:**
[EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
### setImageData(EmfPlusBaseImageData value) {#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-}
```
public void setImageData(EmfPlusBaseImageData value)
```


Obtiene o establece los datos de Imagen de longitud variable que definen los datos de imagen especificados en el campo Type. El contenido y el formato de los datos pueden ser diferentes para cada tipo de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata) |  |

### getType() {#getType--}
```
public int getType()
```


Obtiene o establece el tipo de imagen, un entero sin signo de 32 bits que especifica el tipo de datos en el campo ImageData. Este valor DEBE estar definido en la enumeración ImageDataType (sección 2.1.1.15).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtiene o establece el tipo de imagen, un entero sin signo de 32 bits que especifica el tipo de datos en el campo ImageData. Este valor DEBE estar definido en la enumeración ImageDataType (sección 2.1.1.15).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

