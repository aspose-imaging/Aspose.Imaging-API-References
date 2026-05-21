---
title: "EmfHeaderExtension1"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto HeaderExtension1 define la primera extensión al encabezado del metarchivo EMF."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
```
public final class EmfHeaderExtension1 extends EmfHeaderObject
```

El objeto HeaderExtension1 define la primera extensión del encabezado del metafile EMF. Añade soporte para un objeto PixelFormatDescriptor (sección 2.2.22) y registros OpenGL [OPENGL] (sección 2.3.9).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del objeto PixelFormatDescriptor. |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del objeto PixelFormatDescriptor. |
| [getOffPixelFormat()](#getOffPixelFormat--) | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento al objeto PixelFormatDescriptor. |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento al objeto PixelFormatDescriptor. |
| [getBOpenGl()](#getBOpenGl--) | Obtiene o establece un entero sin signo de 32 bits que indica si los comandos OpenGL están presentes en el metafile. |
| [setBOpenGl(int value)](#setBOpenGl-int-) | Obtiene o establece un entero sin signo de 32 bits que indica si los comandos OpenGL están presentes en el metafile. |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del objeto PixelFormatDescriptor. Esto DEBE ser 0x00000000 si no se ha establecido ningún formato de píxel.

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del objeto PixelFormatDescriptor. Esto DEBE ser 0x00000000 si no se ha establecido ningún formato de píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento al objeto PixelFormatDescriptor. Esto DEBE ser 0x00000000 si no se ha establecido ningún formato de píxel.

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento al objeto PixelFormatDescriptor. Esto DEBE ser 0x00000000 si no se ha establecido ningún formato de píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


Obtiene o establece un entero sin signo de 32 bits que indica si los comandos OpenGL están presentes en el metafile. 0x00000000 Los registros OpenGL no están presentes en el metafile. 0x00000001 Los registros OpenGL están presentes en el metafile.

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


Obtiene o establece un entero sin signo de 32 bits que indica si los comandos OpenGL están presentes en el metafile. 0x00000000 Los registros OpenGL no están presentes en el metafile. 0x00000001 Los registros OpenGL están presentes en el metafile.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

