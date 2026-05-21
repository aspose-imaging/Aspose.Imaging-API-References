---
title: "BitmapV5Header"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La estructura BitmapV5Header es el archivo de encabezado de información de mapa de bits."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.bmp/bitmapv5header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader), [com.aspose.imaging.fileformats.bmp.BitmapV4Header](../../com.aspose.imaging.fileformats.bmp/bitmapv4header)
```
public class BitmapV5Header extends BitmapV4Header
```

La estructura BitmapV5Header es el archivo de encabezado de información de mapa de bits. Es una versión ampliada de la estructura BITMAPINFOHEADER.

Si bV5Height es negativo, lo que indica un DIB de arriba hacia abajo, bV5Compression debe ser BI\_RGB o BI\_BITFIELDS. Los DIB de arriba hacia abajo no pueden comprimirse. La interfaz Independent Color Management (ICM) 2.0 permite que los perfiles de color International Color Consortium (ICC) se enlacen o incrusten en los DIB (DIB). Consulte Using Structures para obtener más información. Cuando un DIB se carga en memoria, los datos del perfil (si están presentes) deben seguir a la tabla de colores, y bV5ProfileData debe proporcionar el desplazamiento de los datos del perfil desde el comienzo de la estructura BITMAPV5HEADER. El valor almacenado en bV5ProfileData será diferente del valor devuelto por el operador sizeof dado el argumento BITMAPV5HEADER, porque bV5ProfileData es el desplazamiento en bytes desde el comienzo de la estructura BITMAPV5HEADER hasta el inicio de los datos del perfil. (Los bits del mapa de bits no siguen a la tabla de colores en memoria). Las aplicaciones deben modificar el miembro bV5ProfileData después de cargar el DIB en memoria. Para DIB empaquetados, los datos del perfil deben seguir a los bits del mapa de bits de forma similar al formato de archivo. El miembro bV5ProfileData debe seguir proporcionando el desplazamiento de los datos del perfil desde el comienzo de BITMAPV5HEADER. Las aplicaciones deben acceder a los datos del perfil solo cuando bV5Size sea igual al tamaño de BITMAPV5HEADER y bV5CSType sea PROFILE\_EMBEDDED o PROFILE\_LINKED.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BitmapV5Header()](#BitmapV5Header--) | Inicializa una nueva instancia de la clase `BitmapV5Header`. |
| [BitmapV5Header(byte[] bytes)](#BitmapV5Header-byte---) | Inicializa una nueva instancia de la clase `BitmapV5Header`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIntent()](#getIntent--) | Obtiene la intención de renderizado para el mapa de bits. |
| [setIntent(long value)](#setIntent-long-) | Establece la intención de renderizado para el mapa de bits. |
| [getProfileData()](#getProfileData--) | Obtiene los datos del perfil. |
| [setProfileData(long value)](#setProfileData-long-) | Establece los datos del perfil. |
| [getProfileSize()](#getProfileSize--) | Obtiene el tamaño del perfil. |
| [setProfileSize(long value)](#setProfileSize-long-) | Establece el tamaño del perfil. |
| [getReserved()](#getReserved--) | Obtiene el miembro reservado. |
| [setReserved(long value)](#setReserved-long-) | Establece el miembro reservado. |
### BitmapV5Header() {#BitmapV5Header--}
```
public BitmapV5Header()
```


Inicializa una nueva instancia de la clase `BitmapV5Header`.

### BitmapV5Header(byte[] bytes) {#BitmapV5Header-byte---}
```
public BitmapV5Header(byte[] bytes)
```


Inicializa una nueva instancia de la clase `BitmapV5Header`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | byte[] | Los bytes. |

### getIntent() {#getIntent--}
```
public long getIntent()
```


Obtiene la intención de renderizado para el mapa de bits.

**Returns:**
long - La intención.
### setIntent(long value) {#setIntent-long-}
```
public void setIntent(long value)
```


Establece la intención de renderizado para el mapa de bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | La intención. |

### getProfileData() {#getProfileData--}
```
public long getProfileData()
```


Obtiene los datos del perfil.

**Returns:**
long - Los datos del perfil.
### setProfileData(long value) {#setProfileData-long-}
```
public void setProfileData(long value)
```


Establece los datos del perfil.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | Los datos del perfil. |

### getProfileSize() {#getProfileSize--}
```
public long getProfileSize()
```


Obtiene el tamaño del perfil.

**Returns:**
long - El tamaño del perfil.
### setProfileSize(long value) {#setProfileSize-long-}
```
public void setProfileSize(long value)
```


Establece el tamaño del perfil.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | El tamaño del perfil. |

### getReserved() {#getReserved--}
```
public long getReserved()
```


Obtiene el miembro reservado.

**Returns:**
long - El valor reservado.
### setReserved(long value) {#setReserved-long-}
```
public void setReserved(long value)
```


Establece el miembro reservado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | El valor reservado. |

