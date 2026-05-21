---
title: "EmfPlusImageAttributes"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusImageAttributes especifica cómo se manipulan los colores de la imagen de mapa de bits durante el renderizado."
type: docs
weight: 48
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImageAttributes extends EmfPlusGraphicsObjectType
```

El objeto EmfPlusImageAttributes especifica cómo se manipulan los colores de la imagen de mapa de bits durante el renderizado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo manejar las condiciones de borde con un valor de la enumeración WrapMode (sección 2.1.1.34). |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica cómo manejar las condiciones de borde con un valor de la enumeración WrapMode (sección 2.1.1.34). |
| [getClampArgb32Color()](#getClampArgb32Color--) | Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color de borde a usar cuando el valor de WrapMode es WrapModeClamp. |
| [setClampArgb32Color(int value)](#setClampArgb32Color-int-) | Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color de borde a usar cuando el valor de WrapMode es WrapModeClamp. |
| [getObjectClamp()](#getObjectClamp--) | Obtiene o establece un entero con signo de 32 bits que especifica el comportamiento de sujeción del objeto. |
| [setObjectClamp(int value)](#setObjectClamp-int-) | Obtiene o establece un entero con signo de 32 bits que especifica el comportamiento de sujeción del objeto. |
### EmfPlusImageAttributes() {#EmfPlusImageAttributes--}
```
public EmfPlusImageAttributes()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo manejar las condiciones de borde con un valor de la enumeración WrapMode (sección 2.1.1.34).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica cómo manejar las condiciones de borde con un valor de la enumeración WrapMode (sección 2.1.1.34).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getClampArgb32Color() {#getClampArgb32Color--}
```
public int getClampArgb32Color()
```


Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color de borde a usar cuando el valor de WrapMode es WrapModeClamp. Este color es visible cuando el rectángulo de origen procesado por un registro EmfPlusDrawImage (sección 2.3.4.8) es más grande que la propia imagen.

**Returns:**
int
### setClampArgb32Color(int value) {#setClampArgb32Color-int-}
```
public void setClampArgb32Color(int value)
```


Obtiene o establece el objeto EmfPlusARGB (sección 2.2.2.1) que especifica el color de borde a usar cuando el valor de WrapMode es WrapModeClamp. Este color es visible cuando el rectángulo de origen procesado por un registro EmfPlusDrawImage (sección 2.3.4.8) es más grande que la propia imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getObjectClamp() {#getObjectClamp--}
```
public int getObjectClamp()
```


Obtiene o establece un entero con signo de 32 bits que especifica el comportamiento de sujeción del objeto. No se utiliza hasta que este objeto se aplique a una imagen que se está dibujando. Este valor DEBE ser uno de los valores definidos en la tabla siguiente.

**Returns:**
int
### setObjectClamp(int value) {#setObjectClamp-int-}
```
public void setObjectClamp(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica el comportamiento de sujeción del objeto. No se utiliza hasta que este objeto se aplique a una imagen que se está dibujando. Este valor DEBE ser uno de los valores definidos en la tabla siguiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

