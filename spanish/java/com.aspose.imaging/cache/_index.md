---
title: "Cache"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Contiene la configuración de caché."
type: docs
weight: 15
url: /es/java/com.aspose.imaging/cache/
---
**Inheritance:**
java.lang.Object
```
public final class Cache
```

Contiene la configuración de caché.
## Métodos

| Método | Descripción |
| --- | --- |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Obtiene un valor que indica si la reasignación debe ser exacta o no. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Establece un valor que indica si la reasignación debe ser exacta o no. |
| [getCacheFolder()](#getCacheFolder--) | Obtiene la carpeta de caché. |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Establece la carpeta de caché. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Obtiene el recuento de bytes asignados en memoria. |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Obtiene el recuento de bytes asignados en disco. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Obtiene la memoria máxima disponible para la caché en memoria. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Establece la memoria máxima disponible para la caché en memoria. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Obtiene el espacio máximo disponible en disco para la caché. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Establece el espacio máximo disponible en disco para la caché. |
| [getCacheType()](#getCacheType--) | Obtiene o establece el esquema de caché utilizado. |
| [setCacheType(int value)](#setCacheType-int-) | Establece el esquema de caché utilizado. |
| [setDefaults()](#setDefaults--) | Establece la configuración de `Cache` a los valores predeterminados. |

## Example: This example demonstrates how to use com.aspose.imaging.Cache

``` java
// Por defecto, la carpeta de caché se establece en el directorio temporal local del usuario.
// También puedes especificar otra carpeta de caché diferente a la predeterminada como se muestra a continuación:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// El modo automático es flexible y eficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// El valor predeterminado es 0, lo que significa que no hay límite superior
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// No se recomienda cambiar la siguiente propiedad ya que puede afectar mucho el rendimiento
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// En cualquier momento puedes comprobar cuántos bytes están actualmente asignados para memoria o disco
// caché al examinar las siguientes propiedades
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Realiza algún procesamiento de imágenes como se muestra a continuación
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Después de ejecutar el código anterior se asignarán 40000 bytes en memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Las propiedades de asignación pueden usarse para comprobar si todos los objetos Aspose.Imaging fueron eliminados correctamente.
// En caso de que hayas olvidado llamar a dispose en algún objeto, los valores de caché serán diferentes de 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getExactReallocateOnly() {#getExactReallocateOnly--}
```
public static boolean getExactReallocateOnly()
```


Obtiene un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta, el rendimiento debería ser mayor.

**Returns:**
boolean - `true` si la reasignación es exacta; de lo contrario, `false`.

La reasignación exacta realizará la reasignación de memoria adicional solo hasta el límite superior especificado. Al proporcionar un límite superior para la memoria en RAM durante la reasignación, los datos en caché se copiarán al disco si es posible. Al proporcionar un límite superior para la memoria en disco durante la reasignación, se lanzará la excepción correspondiente. El rendimiento debería ser mayor si esta opción está desactivada, ya que no se realizará copia adicional si es posible; sin embargo, esto también puede provocar que se superen los límites superiores especificados para memoria o disco.
### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Establece un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta, el rendimiento debería ser mayor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | `true` si la reasignación es exacta; de lo contrario, `false`. |

La reasignación exacta realizará la reasignación de memoria adicional solo hasta el límite superior especificado. Al proporcionar un límite superior para la memoria en RAM durante la reasignación, los datos en caché se copiarán al disco si es posible. Al proporcionar un límite superior para la memoria en disco durante la reasignación, se lanzará la excepción correspondiente. El rendimiento debería ser mayor si esta opción está desactivada, ya que no se realizará copia adicional si es posible; sin embargo, esto también puede provocar que se superen los límites superiores especificados para memoria o disco. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Por defecto, la carpeta de caché se establece en el directorio temporal local del usuario.
// También puedes especificar otra carpeta de caché diferente a la predeterminada como se muestra a continuación:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// El modo automático es flexible y eficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// El valor predeterminado es 0, lo que significa que no hay límite superior
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// No se recomienda cambiar la siguiente propiedad ya que puede afectar mucho el rendimiento
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// En cualquier momento puedes comprobar cuántos bytes están actualmente asignados para memoria o disco
// caché al examinar las siguientes propiedades
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Realiza algún procesamiento de imágenes como se muestra a continuación
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Después de ejecutar el código anterior se asignarán 40000 bytes en memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Las propiedades de asignación pueden usarse para comprobar si todos los objetos Aspose.Imaging fueron eliminados correctamente.
// En caso de que hayas olvidado llamar a dispose en algún objeto, los valores de caché serán diferentes de 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Obtiene la carpeta de caché.

**Returns:**
java.lang.String - La carpeta de caché.
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Establece la carpeta de caché.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La carpeta de caché. |

### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Obtiene el recuento de bytes asignados en memoria.

**Returns:**
long - El recuento de bytes asignados en memoria.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Por defecto, la carpeta de caché se establece en el directorio temporal local del usuario.
// También puedes especificar otra carpeta de caché diferente a la predeterminada como se muestra a continuación:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// El modo automático es flexible y eficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// El valor predeterminado es 0, lo que significa que no hay límite superior
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// No se recomienda cambiar la siguiente propiedad ya que puede afectar mucho el rendimiento
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// En cualquier momento puedes comprobar cuántos bytes están actualmente asignados para memoria o disco
// caché al examinar las siguientes propiedades
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Realiza algún procesamiento de imágenes como se muestra a continuación
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Después de ejecutar el código anterior se asignarán 40000 bytes en memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Las propiedades de asignación pueden usarse para comprobar si todos los objetos Aspose.Imaging fueron eliminados correctamente.
// En caso de que hayas olvidado llamar a dispose en algún objeto, los valores de caché serán diferentes de 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Obtiene el recuento de bytes asignados en disco.

**Returns:**
long - El recuento de bytes asignados en disco.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Por defecto, la carpeta de caché se establece en el directorio temporal local del usuario.
// También puedes especificar otra carpeta de caché diferente a la predeterminada como se muestra a continuación:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// El modo automático es flexible y eficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// El valor predeterminado es 0, lo que significa que no hay límite superior
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// No se recomienda cambiar la siguiente propiedad ya que puede afectar mucho el rendimiento
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// En cualquier momento puedes comprobar cuántos bytes están actualmente asignados para memoria o disco
// caché al examinar las siguientes propiedades
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Realiza algún procesamiento de imágenes como se muestra a continuación
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Después de ejecutar el código anterior se asignarán 40000 bytes en memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Las propiedades de asignación pueden usarse para comprobar si todos los objetos Aspose.Imaging fueron eliminados correctamente.
// En caso de que hayas olvidado llamar a dispose en algún objeto, los valores de caché serán diferentes de 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Obtiene la memoria máxima disponible para la caché en memoria. El valor especificado es la cantidad en megabytes.

**Returns:**
int - La memoria máxima para la caché.

Un valor de 0 consumirá toda la memoria disponible y sirve como sin límite superior.
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Establece la memoria máxima disponible para la caché en memoria. El valor especificado es la cantidad en megabytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La memoria máxima para la caché. |

Un valor de 0 consumirá toda la memoria disponible y sirve como sin límite superior. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Por defecto, la carpeta de caché se establece en el directorio temporal local del usuario.
// También puedes especificar otra carpeta de caché diferente a la predeterminada como se muestra a continuación:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// El modo automático es flexible y eficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// El valor predeterminado es 0, lo que significa que no hay límite superior
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// No se recomienda cambiar la siguiente propiedad ya que puede afectar mucho el rendimiento
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// En cualquier momento puedes comprobar cuántos bytes están actualmente asignados para memoria o disco
// caché al examinar las siguientes propiedades
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Realiza algún procesamiento de imágenes como se muestra a continuación
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Después de ejecutar el código anterior se asignarán 40000 bytes en memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Las propiedades de asignación pueden usarse para comprobar si todos los objetos Aspose.Imaging fueron eliminados correctamente.
// En caso de que hayas olvidado llamar a dispose en algún objeto, los valores de caché serán diferentes de 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Obtiene el espacio en disco máximo disponible para la caché. El valor especificado es la cantidad de megabytes.

**Returns:**
int - El espacio en disco máximo disponible para la caché.

Un valor de 0 consumirá toda la memoria disponible y sirve como sin límite superior.
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Establece el espacio en disco máximo disponible para la caché. El valor especificado es la cantidad de megabytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El espacio en disco máximo disponible para la caché. |

Un valor de 0 consumirá toda la memoria disponible y sirve como sin límite superior. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Por defecto, la carpeta de caché se establece en el directorio temporal local del usuario.
// También puedes especificar otra carpeta de caché diferente a la predeterminada como se muestra a continuación:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// El modo automático es flexible y eficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// El valor predeterminado es 0, lo que significa que no hay límite superior
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// No se recomienda cambiar la siguiente propiedad ya que puede afectar mucho el rendimiento
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// En cualquier momento puedes comprobar cuántos bytes están actualmente asignados para memoria o disco
// caché al examinar las siguientes propiedades
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Realiza algún procesamiento de imágenes como se muestra a continuación
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Después de ejecutar el código anterior se asignarán 40000 bytes en memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Las propiedades de asignación pueden usarse para comprobar si todos los objetos Aspose.Imaging fueron eliminados correctamente.
// En caso de que hayas olvidado llamar a dispose en algún objeto, los valores de caché serán diferentes de 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Obtiene o establece el esquema de caché utilizado.

**Returns:**
int - El esquema de caché utilizado.
### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Establece el esquema de caché utilizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El esquema de caché utilizado. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Por defecto, la carpeta de caché se establece en el directorio temporal local del usuario.
// También puedes especificar otra carpeta de caché diferente a la predeterminada como se muestra a continuación:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// El modo automático es flexible y eficiente
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// El valor predeterminado es 0, lo que significa que no hay límite superior
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// No se recomienda cambiar la siguiente propiedad ya que puede afectar mucho el rendimiento
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// En cualquier momento puedes comprobar cuántos bytes están actualmente asignados para memoria o disco
// caché al examinar las siguientes propiedades
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Realiza algún procesamiento de imágenes como se muestra a continuación
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // Después de ejecutar el código anterior se asignarán 40000 bytes en memoria.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Las propiedades de asignación pueden usarse para comprobar si todos los objetos Aspose.Imaging fueron eliminados correctamente.
// En caso de que hayas olvidado llamar a dispose en algún objeto, los valores de caché serán diferentes de 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Establece la configuración de `Cache` a los valores predeterminados.

