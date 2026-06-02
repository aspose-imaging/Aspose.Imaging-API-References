---
title: "EmfPlusBitmap"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusBitmap especifica un mapa de bits que contiene una imagen gráfica."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusBitmap extends EmfPlusBaseImageData
```

El objeto EmfPlusBitmap especifica un mapa de bits que contiene una imagen gráfica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusBitmap()](#EmfPlusBitmap--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitmapData()](#getBitmapData--) | Obtiene o establece los datos de mapa de bits BitmapData (variable): Datos de longitud variable que definen el objeto de datos de mapa de bits especificado en el campo Type. |
| [setBitmapData(EmfPlusBaseBitmapData value)](#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-) | Obtiene o establece los datos de mapa de bits BitmapData (variable): Datos de longitud variable que definen el objeto de datos de mapa de bits especificado en el campo Type. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura del mapa de bits Height (4 bytes): Un entero con signo de 32 bits que especifica la altura en píxeles del área ocupada por el mapa de bits. |
| [setHeight(int value)](#setHeight-int-) | Obtiene o establece la altura del mapa de bits Height (4 bytes): Un entero con signo de 32 bits que especifica la altura en píxeles del área ocupada por el mapa de bits. |
| [getPixelFormat()](#getPixelFormat--) | Obtiene o establece el formato de píxel PixelFormat (4 bytes): Un entero sin signo de 32 bits que especifica el formato de los píxeles que componen la imagen del mapa de bits. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Obtiene o establece el formato de píxel PixelFormat (4 bytes): Un entero sin signo de 32 bits que especifica el formato de los píxeles que componen la imagen del mapa de bits. |
| [getStride()](#getStride--) | Obtiene o establece el paso (stride) de la imagen Stride (4 bytes): Un entero con signo de 32 bits que especifica el desplazamiento en bytes entre el comienzo de una línea de escaneo y la siguiente. |
| [setStride(int value)](#setStride-int-) | Obtiene o establece el paso (stride) de la imagen Stride (4 bytes): Un entero con signo de 32 bits que especifica el desplazamiento en bytes entre el comienzo de una línea de escaneo y la siguiente. |
| [getType()](#getType--) | Obtiene o establece el tipo de la imagen Type (4 bytes): Un entero sin signo de 32 bits que especifica el tipo de datos en el campo BitmapData. |
| [setType(int value)](#setType-int-) | Obtiene o establece el tipo de la imagen Type (4 bytes): Un entero sin signo de 32 bits que especifica el tipo de datos en el campo BitmapData. |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho de la imagen Width (4 bytes): Un entero con signo de 32 bits que especifica el ancho en píxeles del área ocupada por el mapa de bits. |
| [setWidth(int value)](#setWidth-int-) | Obtiene o establece el ancho de la imagen Width (4 bytes): Un entero con signo de 32 bits que especifica el ancho en píxeles del área ocupada por el mapa de bits. |
### EmfPlusBitmap() {#EmfPlusBitmap--}
```
public EmfPlusBitmap()
```


### getBitmapData() {#getBitmapData--}
```
public EmfPlusBaseBitmapData getBitmapData()
```


Obtiene o establece los datos de mapa de bits BitmapData (variable): Datos de longitud variable que definen el objeto de datos de mapa de bits especificado en el campo Type. El contenido y formato de los datos pueden ser diferentes para cada tipo de mapa de bits.

Valor: Los datos del mapa de bits.

**Returns:**
[EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
### setBitmapData(EmfPlusBaseBitmapData value) {#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-}
```
public void setBitmapData(EmfPlusBaseBitmapData value)
```


Obtiene o establece los datos de mapa de bits BitmapData (variable): Datos de longitud variable que definen el objeto de datos de mapa de bits especificado en el campo Type. El contenido y formato de los datos pueden ser diferentes para cada tipo de mapa de bits.

Valor: Los datos del mapa de bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene o establece la altura del mapa de bits Height (4 bytes): Un entero con signo de 32 bits que especifica la altura en píxeles del área ocupada por el mapa de bits. Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado.

Valor: La altura.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtiene o establece la altura del mapa de bits Height (4 bytes): Un entero con signo de 32 bits que especifica la altura en píxeles del área ocupada por el mapa de bits. Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado.

Valor: La altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Obtiene o establece el formato de píxel PixelFormat (4 bytes): Un entero sin signo de 32 bits que especifica el formato de los píxeles que componen la imagen del mapa de bits. Los formatos de píxel compatibles se especifican en la enumeración `EmfPlusPixelFormat` (sección 2.1.1.25). Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado.

Valor: El formato de píxel.

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Obtiene o establece el formato de píxel PixelFormat (4 bytes): Un entero sin signo de 32 bits que especifica el formato de los píxeles que componen la imagen del mapa de bits. Los formatos de píxel compatibles se especifican en la enumeración `EmfPlusPixelFormat` (sección 2.1.1.25). Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado.

Valor: El formato de píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getStride() {#getStride--}
```
public int getStride()
```


Obtiene o establece el paso (stride) de la imagen Stride (4 bytes): Un entero con signo de 32 bits que especifica el desplazamiento en bytes entre el comienzo de una línea de escaneo y la siguiente. Este valor es el número de bytes por píxel, que se especifica en el campo PixelFormat, multiplicado por el ancho en píxeles, que se especifica en el campo Width. El valor de este campo DEBE ser múltiplo de cuatro. Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado.

Valor: El paso.

**Returns:**
int
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Obtiene o establece el paso (stride) de la imagen Stride (4 bytes): Un entero con signo de 32 bits que especifica el desplazamiento en bytes entre el comienzo de una línea de escaneo y la siguiente. Este valor es el número de bytes por píxel, que se especifica en el campo PixelFormat, multiplicado por el ancho en píxeles, que se especifica en el campo Width. El valor de este campo DEBE ser múltiplo de cuatro. Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado.

Valor: El paso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getType() {#getType--}
```
public int getType()
```


Obtiene o establece el tipo de la imagen Type (4 bytes): Un entero sin signo de 32 bits que especifica el tipo de datos en el campo BitmapData. Este valor DEBE estar definido en la enumeración `EmfPlusBitmapDataType` (sección 2.1.1.2).

Valor: El tipo.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtiene o establece el tipo de la imagen Type (4 bytes): Un entero sin signo de 32 bits que especifica el tipo de datos en el campo BitmapData. Este valor DEBE estar definido en la enumeración `EmfPlusBitmapDataType` (sección 2.1.1.2).

Valor: El tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene o establece el ancho de la imagen Width (4 bytes): Un entero con signo de 32 bits que especifica el ancho en píxeles del área ocupada por el mapa de bits. Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado.

Valor: El ancho.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtiene o establece el ancho de la imagen Width (4 bytes): Un entero con signo de 32 bits que especifica el ancho en píxeles del área ocupada por el mapa de bits. Si la imagen está comprimida, según el campo Type, este valor es indefinido y DEBE ser ignorado.

Valor: El ancho.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

