---
title: "PngLoadOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones de carga png."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.imageloadoptions/pngloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

Las opciones de carga png.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Inicializa una nueva instancia de la clase `PngLoadOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | Obtiene o establece un valor que indica si [strict mode]. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Obtiene o establece un valor que indica si [strict mode]. |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Inicializa una nueva instancia de la clase `PngLoadOptions`.

### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Obtiene o establece un valor que indica si [strict mode].

**Returns:**
boolean - un valor que indica si [strict mode].
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Obtiene o establece un valor que indica si [strict mode].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [strict mode]. |


**Example: The following example shows how to read PNG file : a strict mode.**
El siguiente ejemplo muestra cómo leer un archivo PNG : modo estricto. El modo estricto permite encontrar problemas potenciales : imágenes PNG, p. ej. bloques de datos no reconocidos, fin de archivo inesperado. Tales archivos aún pueden abrirse : modo predeterminado (no estricto) por Aspose.Imaging y también por visores comunes. Sin embargo, cualquier intento de abrirlos : el modo estricto provoca una excepción correspondiente.
``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1442\\";
String inputImage = dir + "FC5F1998104EB92469CB14070628073616BB28F9.png";
String outputImage = inputImage + ".png";

// Modo predeterminado (no estricto) - lectura exitosa.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputImage);
try {
    image.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image.close();
}

// Modo estricto - ImageLoadException : Fin de archivo inesperado.
com.aspose.imaging.Image image2 = com.aspose.imaging.Image.load(inputImage, new com.aspose.imaging.imageloadoptions.PngLoadOptions() {{
    setStrictMode(true);
    }});
                
try {
    image2.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image2.close();
}
```

