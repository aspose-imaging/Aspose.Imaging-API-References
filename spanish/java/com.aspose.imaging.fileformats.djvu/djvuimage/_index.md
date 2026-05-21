---
title: "DjvuImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La clase de documento DjVu admite el formato de archivo gráfico y facilita la gestión sin problemas de documentos escaneados y libros, integrando texto, dibujos, imágenes y fotos en un solo formato."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

La clase de documento DjVu admite el formato de archivo gráfico y facilita la gestión sin problemas de documentos escaneados y libros, integrando texto, dibujos, imágenes y fotos en un solo formato. Soportando operaciones multipágina, puedes acceder eficientemente a identificadores únicos de documentos, contar páginas, establecer páginas activas y recuperar páginas específicas del documento. Con funciones para redimensionar, rotar, aplicar dithering, recortar, transformar a escala de grises, correcciones gamma, ajustes y aplicación de filtros, esta clase permite una manipulación y mejora precisas de imágenes DjVu para satisfacer diversas necesidades de aplicación con facilidad y precisión.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | Comienza a trabajar con imágenes DjVu inicializando una nueva instancia de la clase [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) usando un parámetro Stream. |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Comienza a trabajar con imágenes DjVu sin problemas con este constructor, que inicializa una nueva instancia de la clase [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) usando parámetros Stream y LoadOptions. |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Comienza a trabajar con imágenes DjVu sin problemas con este constructor, que inicializa una nueva instancia de la clase [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) usando parámetros Stream y LoadOptions. |
## Campos

| Campo | Descripción |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | Ocurre cuando cambia el valor de una propiedad. |
## Métodos

| Método | Descripción |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | Carga tu documento DjVu con este método. |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Carga el documento. |
| [getIdentifier()](#getIdentifier--) | Obtiene el identificador único del documento |
| [getPageCount()](#getPageCount--) | Recupera el número total de páginas en tu colección de imágenes DjVu con esta propiedad. |
| [getPages()](#getPages--) | Accede a las páginas individuales de tu colección de imágenes DjVu con esta propiedad. |
| [getDjvuPages()](#getDjvuPages--) | Recupera rápidamente todas las páginas contenidas en tu documento DjVu usando esta propiedad. |
| [getActivePage()](#getActivePage--) | Navega por tu documento DjVu accediendo o estableciendo la página actualmente activa usando esta propiedad. |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Navega por tu documento DjVu accediendo o estableciendo la página actualmente activa usando esta propiedad. |
| [getFirstPage()](#getFirstPage--) | Accede a la primera página de tu documento DjVu con esta propiedad. |
| [getLastPage()](#getLastPage--) | Recupera la última página de tu documento DjVu usando esta propiedad. |
| [getNextPage()](#getNextPage--) | Navega por tu documento DjVu accediendo a la página siguiente con esta práctica propiedad. |
| [getPreviousPage()](#getPreviousPage--) | Muévete rápidamente hacia atrás en la visualización o procesamiento de tu documento DjVu accediendo a la página anterior con esta práctica propiedad. |
| [getFileFormat()](#getFileFormat--) | Obtén la información del formato de archivo asociada a tu archivo de imagen DjVu. |
| [hasAlpha()](#hasAlpha--) | Determina rápidamente si tu archivo de imagen DjVu contiene un canal alfa. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rota la imagen alrededor de su centro con el método Rotate de la clase RasterCachedMultipageImage. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensiona la imagen usando el método \`Resize\`, proporcionando una forma simple y eficaz de ajustar las dimensiones de tus imágenes según tus requisitos. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | El método \`ResizeWidthProportionally\` ofrece una solución práctica para ajustar el ancho de tu imagen mientras se mantiene su relación de aspecto. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | El método \`ResizeHeightProportionally\` te permite ajustar la altura de tu imagen mientras preservas su relación de aspecto. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | El método \`RotateFlip\` ofrece opciones de manipulación versátiles para tu imagen, permitiéndote rotar, voltear o realizar ambas operaciones en el fotograma activo de forma independiente. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | La función "Dither" aplica un efecto de tramado a tu imagen, mejorando su calidad visual al reducir bandas y mejorar las transiciones de color. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | "Crop" recorta tu imagen para enfocarse en detalles específicos o eliminar elementos no deseados, mejorando su composición e impacto visual. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Crop con desplazamientos te permite ajustar con precisión la posición y dimensiones del área recortada dentro de una imagen. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | La binarización con un umbral predefinido simplifica imágenes complejas en representaciones binarias, donde los píxeles se clasifican como negros o blancos según su intensidad comparada con un valor de umbral especificado. |
| [binarizeOtsu()](#binarizeOtsu--) | La binarización usando el umbral de Otsu es una técnica que calcula automáticamente un valor de umbral óptimo basado en el histograma de la imagen. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | La binarización usando el algoritmo de umbral adaptativo de Bradley con umbralado de imagen integral es un método que calcula un umbral local para cada píxel basado en un vecindario local. |
| [grayscale()](#grayscale--) | La transformación a escala de grises convierte una imagen en una representación en blanco y negro, donde la intensidad de cada píxel se representa con un solo valor que varía de negro a blanco. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | La corrección gamma, específicamente para los canales rojo, verde y azul, implica ajustar el brillo de cada componente de color por separado. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | La corrección gamma se aplica a una imagen con parámetros personalizables para los canales rojo, verde y azul, permitiendo un ajuste preciso del balance de color y el brillo. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajusta el `brightness` de una imagen usando un parámetro especificado, proporcionando control sobre los niveles de luminancia para una claridad visual óptima. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Mejora el contraste de [Image](../../com.aspose.imaging/image) para mejorar la claridad visual y resaltar detalles con este método, que ajusta la diferencia de brillo entre áreas claras y oscuras. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Aplica filtros a un área rectangular especificada dentro de la imagen para mejorar o modificar su apariencia. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensiona la imagen al ancho y alto especificados mientras aplicas configuraciones adicionales según sea necesario. |
| [cacheData()](#cacheData--) | Almacena en caché los datos de forma privada para optimizar el rendimiento y reducir la necesidad de recuperaciones repetidas de datos de fuentes externas. |

## Example: This example shows how to load a DJVU image from a file stream.

``` java
String dir = "c:\\temp\\";

// Cargar una imagen DJVU desde un flujo de archivo.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Guarda cada página como una imagen PNG individual.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Genera un nombre de archivo basado en el número de página.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### DjvuImage(InputStream stream) {#DjvuImage-java.io.InputStream-}
```
public DjvuImage(InputStream stream)
```


Comienza a trabajar con imágenes DjVu inicializando una nueva instancia de la clase [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) usando un parámetro Stream. Perfecto para desarrolladores que desean una integración fluida del procesamiento de imágenes DjVu en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


Comienza a trabajar con imágenes DjVu de forma fluida con este constructor, que inicializa una nueva instancia de la clase [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) usando los parámetros Stream y LoadOptions. Perfecto para desarrolladores que desean un control preciso sobre las opciones de carga de imágenes DjVu manteniendo la simplicidad y la eficiencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo desde el cual cargar. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Comienza a trabajar con imágenes DjVu de forma fluida con este constructor, que inicializa una nueva instancia de la clase [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) usando los parámetros Stream y LoadOptions. Perfecto para desarrolladores que desean un control preciso sobre las opciones de carga de imágenes DjVu manteniendo la simplicidad y la eficiencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | com.aspose.ms.System.IO.Stream | El flujo desde el cual cargar. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Ocurre cuando cambia el valor de una propiedad.

### loadDocument(InputStream stream) {#loadDocument-java.io.InputStream-}
```
public static DjvuImage loadDocument(InputStream stream)
```


Carga tu documento DjVu con este método. Optimiza tu proceso accediendo e importando rápidamente tus archivos DjVu en tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### loadDocument(InputStream stream, LoadOptions loadOptions) {#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static DjvuImage loadDocument(InputStream stream, LoadOptions loadOptions)
```


Carga el documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Obtiene el identificador único del documento

**Returns:**
int - El identificador.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupera el número total de páginas en tu colección de imágenes DjVu con esta propiedad. Ideal para evaluar rápidamente el alcance de tu documento o libro almacenado en formato DjVu. Mejora la eficiencia de tu flujo de trabajo con información precisa del recuento de páginas.

**Returns:**
int - El recuento de páginas.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accede a las páginas individuales de tu colección de imágenes DjVu con esta propiedad. Simplifica la navegación y manipulación de tu documento o libro almacenado en formato DjVu accediendo directamente a cada página. Mejora la eficiencia de tu flujo de trabajo con una recuperación de páginas sencilla.

**Returns:**
com.aspose.imaging.Image[] - Las páginas.

**Example: This example shows how to load a DJVU image from a file stream.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen DJVU desde un flujo de archivo.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Guarda cada página como una imagen PNG individual.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Genera un nombre de archivo basado en el número de página.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### getDjvuPages() {#getDjvuPages--}
```
public DjvuPage[] getDjvuPages()
```


Recupera rápidamente todas las páginas contenidas en tu documento DjVu usando esta propiedad. Simplifica tu flujo de procesamiento de documentos accediendo y gestionando fácilmente páginas individuales dentro de tus archivos DjVu. Mejora la eficiencia y agiliza tus tareas con una recuperación de páginas conveniente.

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] - Las páginas.
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


Navega por tu documento DjVu accediendo o estableciendo la página actualmente activa usando esta propiedad. Cambia sin problemas entre páginas para enfocarte en contenido específico y mejorar tu experiencia de visualización del documento.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage)

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen DJVU desde un flujo de archivo.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//La salida puede verse así:
//El número total de páginas: 2
//El número de página activo:    1
//El número de la primera página:     1
//El número de la última página:      2
//--------------------------------------------------
//Número de página:     1
//Tamaño de página:       { Width = 2481, Height = 3508}
//Formato bruto de página: RgbIndexed1Bpp, canales usados: 1
//--------------------------------------------------
//Número de página:     2
//Tamaño de página:       { Width = 2481, Height = 3508}
//Formato bruto de página: RgbIndexed1Bpp, canales usados: 1
```

### setActivePage(DjvuPage value) {#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public void setActivePage(DjvuPage value)
```


Navega por tu documento DjVu accediendo o estableciendo la página actualmente activa usando esta propiedad. Cambia sin problemas entre páginas para enfocarte en contenido específico y mejorar tu experiencia de visualización del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | La página activa. |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


Accede a la primera página de tu documento DjVu con esta propiedad. Recupera rápidamente la página inicial para comenzar a visualizar o procesar tu documento de manera eficiente.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The first page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen DJVU desde un flujo de archivo.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//La salida puede verse así:
//El número total de páginas: 2
//El número de página activo:    1
//El número de la primera página:     1
//El número de la última página:      2
//--------------------------------------------------
//Número de página:     1
//Tamaño de página:       { Width = 2481, Height = 3508}
//Formato bruto de página: RgbIndexed1Bpp, canales usados: 1
//--------------------------------------------------
//Número de página:     2
//Tamaño de página:       { Width = 2481, Height = 3508}
//Formato bruto de página: RgbIndexed1Bpp, canales usados: 1
```

### getLastPage() {#getLastPage--}
```
public DjvuPage getLastPage()
```


Recupera la última página de tu documento DjVu usando esta propiedad. Accede rápidamente a la página final para propósitos de visualización o procesamiento con facilidad.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The last page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen DJVU desde un flujo de archivo.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//La salida puede verse así:
//El número total de páginas: 2
//El número de página activo:    1
//El número de la primera página:     1
//El número de la última página:      2
//--------------------------------------------------
//Número de página:     1
//Tamaño de página:       { Width = 2481, Height = 3508}
//Formato bruto de página: RgbIndexed1Bpp, canales usados: 1
//--------------------------------------------------
//Número de página:     2
//Tamaño de página:       { Width = 2481, Height = 3508}
//Formato bruto de página: RgbIndexed1Bpp, canales usados: 1
```

### getNextPage() {#getNextPage--}
```
public DjvuPage getNextPage()
```


Navega por tu documento DjVu accediendo a la página siguiente con esta práctica propiedad. Avanza rápidamente en tus tareas de visualización o procesamiento del documento.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


Muévete rápidamente hacia atrás en tus tareas de visualización o procesamiento del documento DjVu accediendo a la página anterior con esta práctica propiedad. Navega eficientemente por tu documento con facilidad.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtén la información del formato de archivo asociada a tu archivo de imagen DjVu. Determina rápidamente el formato de tu archivo para una integración fluida en tu flujo de trabajo.

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Determina rápidamente si tu archivo de imagen DjVu contiene un canal alfa. Simplifica tu flujo de trabajo verificando la presencia de información de transparencia en tus imágenes.

**Returns:**
boolean - El tiene canal alfa.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Gira la imagen alrededor de su centro con el método Rotate de la clase RasterCachedMultipageImage. Esta característica conveniente le permite ajustar fácilmente la orientación de las imágenes mientras mantiene su posición central, mejorando sus capacidades de manipulación de imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resizeProportionally | boolean | si se establece en `true` el tamaño de su imagen cambiará según las proyecciones del rectángulo girado (puntos de esquina); de lo contrario, se dejarán las dimensiones sin cambios y solo `` el contenido de la imagen será rotado. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color del fondo. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensiona la imagen usando el método \`Resize\`, proporcionando una forma simple y eficaz de ajustar las dimensiones de sus imágenes según sus requisitos. Esta funcionalidad versátil le permite escalar fácilmente las imágenes al tamaño deseado, mejorando su usabilidad en diversas plataformas y aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |


**Example: This example loads a DJVU image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


El método \`ResizeWidthProportionally\` ofrece una solución conveniente para ajustar el ancho de su imagen mientras mantiene su relación de aspecto. Al redimensionar proporcionalmente el ancho, puede asegurarse de que sus imágenes sigan siendo visualmente atractivas y consistentes en diferentes dispositivos y tamaños de pantalla, mejorando su versatilidad y usabilidad en varios contextos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| resizeType | int | Tipo de redimensionado. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Este ejemplo carga una imagen DJVU y la redimensiona proporcionalmente usando varios métodos de redimensionado. Sólo se especifica el ancho, la altura se calcula automáticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


El método \`ResizeHeightProportionally\` le permite ajustar la altura de su imagen mientras preserva su relación de aspecto. Esto garantiza que su imagen mantenga sus proporciones, evitando distorsiones y preservando su integridad visual. Ya sea que esté optimizando imágenes para páginas web, aplicaciones móviles o medios impresos, este método asegura que sus imágenes se vean lo mejor posible en diferentes plataformas y dispositivos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newHeight | int | El nuevo alto. |
| resizeType | int | Tipo de redimensionado. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Este ejemplo carga una imagen DJVU y la redimensiona proporcionalmente usando varios métodos de redimensionado. Sólo se especifica la altura, el ancho se calcula automáticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


El método \`RotateFlip\` ofrece opciones de manipulación versátiles para su imagen, permitiéndole rotar, voltear o realizar ambas operaciones en el fotograma activo de forma independiente. Ya sea que esté editando fotos, creando gráficos o mejorando arte digital, este método brinda un control preciso sobre la orientación y composición de sus imágenes, asegurando que cumplan con su visión creativa con facilidad y eficiencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | El tipo de rotación y volteo. |


**Example: This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Rotar, voltear y guardar en el archivo de salida.
    com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


La función "Dither" aplica un efecto de tramado a su imagen, mejorando su calidad visual al reducir bandas y mejorar las transiciones de color. Ya sea que esté trabajando en arte digital, fotografía o proyectos de diseño gráfico, esta característica añade un toque profesional a sus imágenes, haciéndolas parecer más suaves y refinadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ditheringMethod | int | El método de tramado. |
| bitsCount | int | El recuento final de bits para el tramado. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta personalizada para el tramado. |


**Example: The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Realizar dithering por umbral usando una paleta de colores de 4 bits que contiene 16 colores.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Realizar dithering Floyd usando una paleta de colores de 1 bit que contiene solo 2 colores: negro y blanco.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


"Crop" recorta su imagen para enfocarse en detalles específicos o eliminar elementos no deseados, mejorando su composición e impacto visual. Ya sea que esté ajustando fotos para redes sociales, creando banners para sitios web o diseñando material impreso, esta herramienta le ayuda a refinar sus imágenes con precisión y claridad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |


**Example: The following example crops a DJVU image.**
El siguiente ejemplo recorta una imagen DJVU. El área de recorte se especifica a través de Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Recorte la imagen. El área de recorte es la zona rectangular central de la imagen.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            djvuImage.getWidth() / 4, djvuImage.getHeight() / 4, djvuImage.getWidth() / 2, djvuImage.getHeight() / 2);
    djvuImage.crop(area);

    // Guarde la imagen recortada en PNG
    djvuImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Recortar con desplazamientos le permite ajustar con precisión la posición y dimensiones del área recortada dentro de una imagen. Esta característica es invaluable para refinar composiciones, alinear elementos y enfatizar puntos focales en sus visuales. Al incorporar desplazamientos en el proceso de recorte, puede lograr una precisión pixel-perfecta y afinar el encuadre de sus imágenes con facilidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftShift | int | El desplazamiento izquierdo. |
| rightShift | int | El desplazamiento derecho. |
| topShift | int | El desplazamiento superior. |
| bottomShift | int | El desplazamiento inferior. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


La binarización con un umbral predefinido simplifica imágenes complejas en representaciones binarias, donde los píxeles se clasifican como negro o blanco según su intensidad comparada con un valor de umbral especificado. Esta técnica se usa comúnmente en procesamiento de imágenes para mejorar la claridad, simplificar el análisis y preparar imágenes para pasos posteriores como el reconocimiento óptico de caracteres (OCR). Al aplicar un umbral fijo, puede transformar rápidamente imágenes en escala de grises a forma binaria, facilitando su interpretación y extracción de información significativa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | byte | Valor del umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255; de lo contrario, 0. |


**Example: The following example binarizes a DJVU image with the predefined threshold.**
El siguiente ejemplo binariza una imagen DJVU con el umbral predefinido. Las imágenes binarizadas contienen sólo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binariza la imagen con un valor de umbral de 127.
    // Si el valor gris correspondiente de un píxel es mayor que 127, se le asignará un valor de 255, 0 en caso contrario.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


La binarización usando el umbral de Otsu es una técnica que calcula automáticamente un valor de umbral óptimo basado en el histograma de la imagen. Separa la imagen en primer plano y fondo minimizando la varianza intra-clase. El método de Otsu se usa ampliamente para segmentar imágenes en forma binaria, particularmente cuando la distribución de intensidades de píxeles es bimodal o multimodal. Este enfoque es beneficioso para tareas como detección de objetos, segmentación de imágenes y extracción de características, donde la delimitación precisa entre primer plano y fondo es crucial.


**Example: The following example binarizes a DJVU image with Otsu thresholding.**
El siguiente ejemplo binariza una imagen DJVU con el umbral de Otsu. Las imágenes binarizadas contienen sólo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binariza la imagen con umbralización de Otsu.
    djvuImage.binarizeOtsu();
    djvuImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


La binarización usando el algoritmo de umbral adaptativo de Bradley con umbralado por imagen integral es un método que calcula un umbral local para cada píxel basado en un vecindario local. Se adapta a variaciones de iluminación en toda la imagen, lo que lo hace adecuado para imágenes con condiciones de luz desiguales. Al calcular el umbral usando imágenes integrales, maneja eficientemente vecindarios grandes, siendo aplicable a aplicaciones en tiempo real. Esta técnica se usa comúnmente en procesamiento de documentos, OCR (Reconocimiento Óptico de Caracteres) y tareas de segmentación de imágenes donde la binarización precisa es esencial para el análisis posterior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightnessDifference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |
| windowSize | int | El tamaño de la ventana de s x s píxeles centrada en este píxel |


**Example: The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size.**
El siguiente ejemplo binariza una imagen DJVU con el algoritmo de umbral adaptativo de Bradley con el tamaño de ventana especificado. Las imágenes binarizadas contienen sólo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binariza la imagen con una diferencia de brillo de 5. El brillo es la diferencia entre un píxel y el promedio de una ventana de 10 x 10 píxeles centrada en ese píxel.
    djvuImage.binarizeBradley(5, 10);
    djvuImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


La transformación a escala de grises convierte una imagen a una representación en blanco y negro, donde la intensidad de cada píxel se representa con un solo valor que va de negro a blanco. Este proceso elimina la información de color, resultando en una imagen monocromática. Las imágenes en escala de grises se usan comúnmente en aplicaciones donde el color no es necesario o se prefiere la simplicidad, como escaneo de documentos, impresión y ciertos tipos de análisis de imágenes.


**Example: The following example transforms a colored DJVU image to its grayscale representation.**
El siguiente ejemplo transforma una imagen DJVU a color a su representación en escala de grises. Las imágenes en escala de grises están compuestas exclusivamente por tonos de gris y solo contienen información de intensidad.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    djvuImage.grayscale();
    djvuImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


La corrección gamma, específicamente para los canales rojo, verde y azul, implica ajustar el brillo de cada componente de color por separado. Al aplicar diferentes coeficientes gamma a los canales RGB, puede afinar el brillo y contraste general de una imagen. Esta técnica asegura una representación de color precisa y mejora la calidad visual de la imagen en diferentes dispositivos de visualización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |


**Example: The following example performs gamma-correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Establecer el coeficiente gamma para los canales rojo, verde y azul.
    djvuImage.adjustGamma(2.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


La corrección gamma se aplica a una imagen con parámetros personalizables para los canales rojo, verde y azul, permitiendo un ajuste preciso del balance de color y el brillo. Este método mejora la calidad de la imagen afinando la representación del color, asegurando una renderización óptima en diferentes dispositivos de visualización. Ajustar los valores gamma de los canales individuales mejora el balance de color y el atractivo visual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gammaRed | float | Gamma para el coeficiente del canal rojo |
| gammaGreen | float | Gamma para el coeficiente del canal verde |
| gammaBlue | float | Coeficiente gamma para el canal azul |


**Example: The following example performs gamma-correction of a DJVU image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Establecer coeficientes gamma individuales para los canales rojo, verde y azul.
    djvuImage.adjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajuste el `brightness` de una imagen usando un parámetro especificado, proporcionando control sobre los niveles de luminancia para una claridad visual óptima. Este método aumenta o disminuye el brillo general de la imagen, permitiendo ajustes finos para lograr los efectos de iluminación deseados. Al modular el brillo, los usuarios pueden optimizar la visibilidad de la imagen y realzar la reproducción de detalles para una mejor experiencia de visualización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | int | Valor de brillo. |


**Example: The following example performs brightness correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Establece el valor de brillo. Los valores aceptados de brillo están en el rango [-255, 255].
    djvuImage.adjustBrightness(50);
    djvuImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Mejore el contraste de [Image](../../com.aspose.imaging/image) para mejorar la claridad visual y resaltar detalles con este método, que ajusta la diferencia de brillo entre áreas claras y oscuras. Al afinar los niveles de contraste, los usuarios pueden lograr imágenes más vívidas e impactantes, mejorando la calidad general de la imagen y maximizando la visibilidad de los detalles. Este ajuste ayuda a resaltar sutilezas en color y textura, resultando en imágenes más dinámicas y visualmente atractivas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contrast | float | Valor de contraste (en el rango [-100; 100]) |


**Example: The following example performs contrast correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Establece el valor de contraste. Los valores aceptados de contraste están en el rango [-100f, 100f].
    djvuImage.adjustContrast(50f);
    djvuImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Aplique filtros a un área rectangular especificada dentro de la imagen para realzar o modificar su apariencia. Al dirigirse a regiones específicas, este método permite ajustes precisos, como desenfoque, enfoque o aplicación de efectos artísticos, para lograr los resultados visuales deseados. Afinar los filtros en áreas seleccionadas capacita a los usuarios para personalizar la estética de la imagen, mejorar la claridad y crear efectos artísticos adaptados a sus preferencias.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Las opciones. |


**Example: The following example applies various types of filters to a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Aplica un filtro mediano con un tamaño de rectángulo de 5 a toda la imagen.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    djvuImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Aplica un filtro de suavizado bilateral con un tamaño de kernel de 5 a toda la imagen.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    djvuImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Aplica un filtro de desenfoque gaussiano con un radio de 5 y un valor sigma de 4.0 a toda la imagen.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Aplica un filtro Gauss-Wiener con un radio de 5 y un valor de suavizado de 4.0 a toda la imagen.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Aplica un filtro wiener de movimiento con una longitud de 5, un valor de suavizado de 4.0 y un ángulo de 90.0 grados a toda la imagen.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Aplica un filtro de nitidez con un tamaño de kernel de 5 y un valor sigma de 4.0 a toda la imagen.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensiona la imagen al ancho y alto especificados mientras aplicas configuraciones adicionales según sea necesario. Este método permite a los usuarios ajustar las dimensiones de la imagen manteniendo atributos deseados como la relación de aspecto, la calidad de la imagen y los ajustes de compresión. Al proporcionar flexibilidad en las opciones de redimensionado, los usuarios pueden adaptar la imagen a requisitos específicos y optimizar su apariencia para diversas aplicaciones y plataformas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | La configuración de redimensionado. |


**Example: This example loads a DJVU image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// El algoritmo adaptativo basado en una función racional ponderada y combinada y en la interpolación lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// El pequeño filtro rectangular
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// El número de colores en la paleta.
resizeSettings.setEntriesCount(256);

// La cuantización de color no se usa
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// El método euclidiano
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Reducir a la mitad usando remuestreo adaptativo.
    djvuImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Guardar como PNG
    djvuImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Almacena en caché los datos de forma privada para optimizar el rendimiento y reducir la necesidad de recuperaciones repetidas de datos de fuentes externas. Este enfoque también ayuda a conservar recursos, particularmente en escenarios donde el acceso a los datos es frecuente o los recursos son limitados.


**Example: The following example shows how to cache all pages of a DJVU image.**

``` java
String dir = "c:\\temp\\";

// Carga una imagen desde un archivo DJVU.
com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Esta llamada almacena en caché todas las páginas para que no se realice una carga adicional de datos desde el flujo de datos subyacente.
    image.cacheData();

    // O puedes almacenar en caché las páginas individualmente.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

