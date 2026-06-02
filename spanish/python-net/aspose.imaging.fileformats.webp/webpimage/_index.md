---
title: "Clase WebPImage"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.fileformats.webp/webpimage/
---

**Summary:** Manipulate WebP raster images with our API, using its modern features for both<br/>            lossless and lossy compression, ensuring optimal image quality with reduced file sizes.<br/>            Seamlessly handle extended file formats, animations, and alpha channels, while easily<br/>            updating dimensions, resizing proportionally, cropping, rotating, applying filters,<br/>            adjusting image parameters, and converting to other image formats for versatile<br/>            web image optimization.

**Module:** [aspose.imaging.fileformats.webp](/imaging/python-net/aspose.imaging.fileformats.webp/)

**Full Name:** aspose.imaging.fileformats.webp.WebPImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [WebPImage(path)](#WebPImage_path_1) | Crea una nueva instancia fresca de la [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) clase, inicializada <br/>            desde una fuente de archivo proporcionada. Utiliza este constructor para crear sin problemas objetos de imagen WebP <br/>            directamente desde archivos, optimizando el proceso de carga y <br/>            manipulación de datos de imágenes WebP dentro de tu aplicación. |
| [WebPImage(path, load_options)](#WebPImage_path_load_options_2) | Crea una nueva instancia de la [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) clase usando un archivo y <br/>            opciones de carga especificadas, facilitando el manejo flexible de datos de imágenes WebP. Utiliza <br/>            este constructor para inicializar sin problemas objetos de imagen WebP desde archivos mientras <br/>            personalizas los parámetros de carga según los requisitos de tu aplicación. |
| [WebPImage(raster_image)](#WebPImage_raster_image_3) | Instancia una nueva instancia de la [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) clase, inicializada <br/>            desde un objeto rasterImage proporcionado. Este constructor permite una conversión sin problemas <br/>            de imágenes raster a formato WebP, habilitando un manejo eficiente y <br/>            manipulación de datos de imagen dentro de tu aplicación. |
| [WebPImage(raster_image, load_options)](#WebPImage_raster_image_load_options_4) | Crea una nueva instancia de la [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) clase usando un objeto rasterImage y <br/>            opciones de carga especificadas, habilitando un manejo flexible de datos de imagen. Utiliza este <br/>            constructor para inicializar sin problemas objetos de imagen WebP desde imágenes raster mientras <br/>            personalizas los parámetros de carga según los requisitos de tu aplicación. |
| [WebPImage(stream)](#WebPImage_stream_5) | Instanciar una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/), inicializada <br/>            a partir de una fuente de flujo proporcionada. Utilice este constructor para crear sin problemas objetos de imagen WebP <br/>            directamente desde flujos, permitiendo un manejo y manipulación eficientes <br/>            de los datos de imagen WebP dentro de su aplicación. |
| [WebPImage(stream, load_options)](#WebPImage_stream_load_options_6) | Crear una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) a partir de un flujo, <br/>            incorporando opciones de carga especificadas y configuraciones de gestión de memoria. Este <br/>            constructor ofrece flexibilidad al cargar imágenes WebP desde flujos mientras <br/>            gestiona eficientemente los recursos de memoria, garantizando un rendimiento óptimo y la utilización <br/>            de recursos dentro de su aplicación. |
| [WebPImage(width, height, options)](#WebPImage_width_height_options_7) | Instanciar una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) con una imagen vacía de ancho y alto especificados. Este constructor permite la <br/>            creación de imágenes WebP en blanco, proporcionando una base para la manipulación posterior de imágenes <br/>            y la generación de contenido dentro de su aplicación. |
| [WebPImage(width, height, options, load_options)](#WebPImage_width_height_options_load_options_8) | Crear una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) con una imagen vacía y opciones de carga especificadas. Este constructor permite la inicialización de imágenes WebP con <br/>            parámetros de carga personalizables, proporcionando flexibilidad en la creación y <br/>            manipulación de imágenes dentro de su aplicación. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Obtiene o establece un valor que indica si se ajusta automáticamente la paleta. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece un valor para el color de fondo. |
| bits_per_pixel | int | r | Obtiene el recuento de bits por píxel de la imagen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtiene los límites del objeto. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtiene el contenedor [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Obtiene el flujo de datos del objeto. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece la instancia Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Acceder al valor del formato de archivo asociado con la imagen, proporcionando información <br/>            sobre el formato en el que se almacena la imagen. Utilice esta propiedad para determinar <br/>            el formato de archivo de la imagen, facilitando verificaciones de compatibilidad y <br/>            procesamiento específico de formato dentro de su aplicación. |
| [has_alpha](#has_alpha1) | bool | r | Obtener si la imagen contiene un canal alfa, lo que indica la presencia de <br/>            información de transparencia. Utilice esta propiedad para determinar si la imagen <br/>            incluye transparencia, permitiendo un manejo y procesamiento adecuados de <br/>            operaciones relacionadas con alfa dentro de su aplicación. |
| has_background_color | bool | r/w | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| has_transparent_color | bool | r/w | Obtiene un valor que indica si la imagen tiene un color transparente. |
| height | int | r | Obtiene la altura de la imagen. |
| horizontal_resolution | float | r/w | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Obtiene la opacidad de esta imagen. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtiene o establece el monitor de interrupciones. |
| is_cached | bool | r | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| is_raw_data_available | bool | r | Obtiene un valor que indica si se admite la carga de datos sin procesar. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtiene o establece los datos XMP del fotograma. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | r | Obtener o modificar las opciones asociadas con la propiedad especificada, permitiendo <br/>            una personalización afinada del comportamiento y la configuración. Utilice esta propiedad para <br/>            acceder y manipular sin problemas los parámetros configurables, facilitando un control versátil <br/>            y la optimización dentro de la funcionalidad de su aplicación. |
| page_count | int | r | Obtener el recuento total de páginas dentro del documento especificado, facilitando <br/>            una navegación y gestión eficientes del contenido multipágina. Incorpore esta <br/>            funcionalidad para mejorar la experiencia del usuario, permitiendo un acceso sin problemas a <br/>            estructuras de documento completas. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Acceder a los bloques WebP dentro de la imagen, permitiendo un examen detallado o <br/>            manipulación de la estructura de bloques subyacente. Utilice esta propiedad para analizar <br/>            o modificar bloques individuales dentro de los datos de imagen WebP, facilitando técnicas avanzadas <br/>            de procesamiento de imágenes dentro de su aplicación. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. La paleta de colores no se usa cuando los píxeles se representan directamente. |
| premultiply_components | bool | r/w | Obtiene o establece un valor que indica si los componentes de la imagen deben ser premultiplicados. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Obtiene o establece el convertidor de color personalizado |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtiene el formato de datos sin procesar. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración, los datos se cargan sin conversión. |
| raw_fallback_index | int | r/w | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Obtiene o establece el convertidor de color indexado |
| raw_line_size | int | r | Obtiene el tamaño de línea sin procesar en bytes. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtiene el tamaño del objeto. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene el color transparente de la imagen. |
| update_xmp_data | bool | r/w | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| use_palette | bool | r | Obtiene un valor que indica si se usa la paleta de la imagen. |
| use_raw_data | bool | r/w | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| vertical_resolution | float | r/w | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Obtiene el ancho de la imagen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtiene o establece los datos Xmp. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_block(block)](#add_block_block_1) | Incorporar un nuevo bloque WebP en la imagen, enriqueciendo su contenido y <br/>            facilitando la manipulación avanzada de imágenes. Integre este método para mejorar dinámicamente <br/>            la estructura y complejidad de los datos de imagen WebP dentro de su <br/>            aplicación, permitiendo un control preciso y la optimización del renderizado de imágenes. |
| [add_page(page)](#add_page_page_2) | Agregar una nueva página a la imagen, ampliando su contenido y acomodando elementos visuales adicionales. Integre este método para facilitar la gestión dinámica de páginas <br/>            dentro de su aplicación, permitiendo la creación y ampliación sin problemas de documentos o imágenes multipágina. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Implementar ajuste de _brightness_ para la imagen, permitiendo la <br/>            modificación de los niveles de luminancia generales. Incorpore este método en su flujo de procesamiento de imágenes para mejorar la visibilidad y la calidad visual de las imágenes <br/>            dentro de su aplicación. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Mejorar el contraste de la [Image](/imaging/python-net/aspose.imaging/image/), amplificando las <br/>            diferencias entre áreas claras y oscuras. Integre este método en su flujo de procesamiento de imágenes para mejorar la claridad visual y la calidad general de la imagen dentro <br/>            de su aplicación. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Aplicar corrección gamma a la imagen, ajustando las intensidades de los píxeles para lograr <br/>            el brillo y el balance de color deseados. Incorpore este método en su flujo de procesamiento de imágenes para mejorar la calidad visual y la precisión de <br/>            los análisis o tareas de visualización posteriores dentro de su aplicación. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Realizar corrección gamma en la imagen usando coeficientes individuales para los canales rojo, <br/>            verde y azul, permitiendo ajustes finos del balance de color y el <br/>            contraste. Integre este método en su canal de procesamiento de imágenes para lograr <br/>            un control preciso sobre la representación del color y mejorar la fidelidad visual dentro de su <br/>            aplicación. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | Calcula el porcentaje de similitud entre los datos extraídos y la contraseña original. |
| auto_brightness_contrast() | Realiza una normalización automática adaptativa de brillo y contraste para toda la imagen. |
| auto_rotate() | Rota automáticamente la imagen basándose en los datos de orientación extraídos de los metadatos Exif <br/> . Este método garantiza que las imágenes se muestren en la orientación correcta, <br/> mejorando la experiencia del usuario y eliminando la necesidad de ajustes manuales. Al <br/> analizar la información Exif, la imagen se rota en consecuencia, proporcionando una experiencia de visualización fluida <br/> en diferentes plataformas y dispositivos. Este proceso de rotación automatizado simplifica la gestión de imágenes y mejora la usabilidad general, especialmente al <br/> trabajar con grandes lotes de imágenes con orientaciones variables. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | Aplicar binarización a la imagen usando el algoritmo de umbral adaptativo de Bradley <br/>            con umbralización de imagen integral. Este método calcula dinámicamente umbrales locales <br/>            basados en el vecindario de la imagen, mejorando la adaptabilidad a condiciones de iluminación variables y garantizando una segmentación robusta para tareas de procesamiento posteriores <br/>            dentro de su aplicación. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | Realizar binarización en la imagen usando un valor de umbral predefinido, convirtiéndola en una imagen binaria donde los píxeles se clasifican como primer plano o fondo <br/>            según su intensidad relativa al umbral. Integre este método en <br/>            su flujo de procesamiento de imágenes para facilitar la segmentación y extracción de características <br/>            , mejorando la precisión y eficiencia del análisis posterior dentro de su <br/>            aplicación. |
| binarize_otsu() | Realizar binarización en la imagen usando el método de umbral de Otsu, determinando automáticamente el valor de umbral óptimo basado en el histograma de la imagen. Integre <br/>            este método en su flujo de procesamiento de imágenes para lograr una segmentación eficaz <br/>            y extracción de características, mejorando la precisión y fiabilidad de las tareas de análisis de imágenes <br/>            dentro de su aplicación. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | Mezcla esta instancia de imagen con la imagen _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | Mezcla esta instancia de imagen con la imagen _overlay_. |
| cache_data() | Cachea los datos de forma privada. |
| [can_load(file_path)](#can_load_file_path_13) | Determina si la imagen puede cargarse desde la ruta de archivo especificada. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas. |
| [can_load(stream)](#can_load_stream_15) | Determina si la imagen puede cargarse desde el flujo especificado. |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando los _loadOptions_ especificados. |
| [can_load_stream(stream)](#can_load_stream_stream_17) | Determina si la imagen puede cargarse desde el flujo especificado. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando los _loadOptions_ especificados. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas. |
| [can_save(options)](#can_save_options_20) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| clear_blocks() | Eliminar todos los bloques WebP existentes de la imagen, facilitando una hoja en blanco para <br/>            modificaciones o adiciones posteriores. Utilice este método para restablecer eficazmente <br/>            la estructura de bloques dentro de los datos de imagen WebP, garantizando una gestión y <br/>            organización óptimas del contenido de la imagen dentro de su aplicación. |
| [create(files)](#create_files_21) | Crea la imagen multipágina que contiene los archivos especificados. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Crea la imagen multipágina que contiene los archivos especificados. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Crea una nueva imagen usando las opciones de creación especificadas. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Crea una instancia de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) a partir del arreglo de píxeles proporcionado.<br/> <br/> Valida que el ancho y alto especificados coincidan con las dimensiones de los datos de píxeles.<br/> Este método solo puede usarse cuando la biblioteca está en modo Licenciado. |
| [create(images)](#create_images_25) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Crea las opciones de creación multipágina especificadas. |
| [create_from_file_with_options(path, load_options)](#create_from_file_with_options_path_load_options_28) | Inicializa una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) a partir de un archivo. |
| [create_from_files(files)](#create_from_files_files_29) | Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_30) | Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida. |
| [create_from_image(raster_image)](#create_from_image_raster_image_31) | Inicializa una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) a partir de rasterImage. |
| [create_from_image_with_options(raster_image, load_options)](#create_from_image_with_options_raster_image_load_options_32) | Inicializa una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) a partir de rasterImage. |
| [create_from_images(images)](#create_from_images_images_33) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_34) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [create_from_stream(stream)](#create_from_stream_stream_35) | Inicializa una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/)<br/>                a partir de un flujo. |
| [create_from_stream_with_options(stream, load_options)](#create_from_stream_with_options_stream_load_options_36) | Inicializa una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) a partir de un flujo. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_37) | Recortar la imagen aplicando desplazamientos izquierda, derecha, superior e inferior, seleccionando efectivamente <br/>            una región de interés dentro de la imagen. Utilice este método para <br/>            extraer dinámicamente las porciones deseadas de la imagen mientras ajusta su composición <br/>            y enfoque según los requisitos de su aplicación. |
| [crop(rectangle)](#crop_rectangle_38) | Recortar la imagen usando una región rectangular especificada, eliminando porciones no deseadas <br/>            mientras se conserva el contenido deseado. Integre este método en su flujo de procesamiento de imágenes <br/>            para extraer y enfocar con precisión áreas específicas de interés <br/>            dentro de la imagen, mejorando la claridad y composición para diversas aplicaciones. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_39) | Aplica dithering a la imagen actual. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_40) | Realice el tramado en la imagen actual para reducir el bandado de color y mejorar la calidad visual <br/> . Integre este método en su flujo de trabajo de procesamiento de imágenes para lograr <br/> transiciones más suaves entre colores y mejorar la apariencia general de la <br/> imagen dentro de su aplicación. |
| [embed_digital_signature(password)](#embed_digital_signature_password_41) | Incrusta una firma digital basada en la contraseña proporcionada en cada página de la imagen. |
| [filter(rectangle, options)](#filter_rectangle_options_42) | Filtre el contenido dentro del rectángulo especificado, aplicando un filtro de procesamiento de imagen <br/> designado para realzar o modificar la región seleccionada. Integre este método <br/> en su flujo de trabajo de manipulación de imágenes para lograr mejoras dirigidas o <br/> transformaciones dentro de su aplicación. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_43) | Obtiene un píxel ARGB de 32 bits de la imagen. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_44) | Obtiene la matriz predeterminada de píxeles ARGB de 32 bits. |
| [get_default_options(args)](#get_default_options_args_45) | Obtiene las opciones predeterminadas. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_46) | Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47) | Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_48) | Obtiene la matriz de datos sin procesar predeterminada. |
| [get_file_format(file_path)](#get_file_format_file_path_49) | Obtiene el formato de archivo. |
| [get_file_format(stream)](#get_file_format_stream_50) | Obtiene el formato de archivo. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_51) | Obtiene el formato de archivo. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_52) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_53) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_modify_date(use_default)](#get_modify_date_use_default_54) | Obtiene la fecha y hora en que la imagen del recurso fue modificada por última vez. |
| [get_original_options()](#get_original_options__55) | Obtiene las opciones basadas en la configuración original del archivo.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            método [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al método [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) como segundo parámetro. |
| [get_pixel(x, y)](#get_pixel_x_y_56) | Obtiene un píxel de la imagen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_57) | Obtiene una altura proporcional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_58) | Obtiene un ancho proporcional. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_59) | Convierte a aps. |
| [get_skew_angle()](#get_skew_angle__60) | Obtiene el ángulo de sesgo.<br/>            Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear. |
| grayscale() | Convierta la imagen a su representación en escala de grises, transformándola en una <br/> imagen de un solo canal donde cada píxel representa intensidad o luminancia. Integre <br/> este método en su canal de procesamiento de imágenes para simplificar el análisis y mejorar <br/> la compatibilidad con algoritmos basados en escala de grises, facilitando diversas tareas de visión <br/> por computadora y análisis de imágenes dentro de su aplicación. |
| [insert_block(index, block)](#insert_block_index_block_61) | Inserte un nuevo bloque WebP en el índice especificado dentro de la imagen, permitiendo un control preciso <br/> sobre la secuencia de bloques. Integre este método para incorporar sin problemas <br/> bloques WebP adicionales en la estructura de datos de la imagen, facilitando el procesamiento avanzado de imágenes <br/> y la optimización dentro de su aplicación. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_62) | Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral. |
| [load(file_path)](#load_file_path_63) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(file_path, load_options)](#load_file_path_load_options_64) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(stream)](#load_stream_65) | Carga una nueva imagen desde el flujo especificado. |
| [load(stream, load_options)](#load_stream_load_options_66) | Carga los datos desde el flujo. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_67) | Carga píxeles ARGB de 32 bits. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_68) | Carga píxeles ARGB de 64 bits. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_69) | Carga píxeles en formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_70) | Carga píxeles en formato CMYK.<br/>            Este método está obsoleto. Por favor, use de manera más eficaz el método [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_71) | Carga parcialmente píxeles ARGB de 32 bits (por bloques). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_72) | Carga parcialmente píxeles ARGB de 64 bits por paquetes. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_73) | Carga píxeles parcialmente por paquetes. |
| [load_pixels(rectangle)](#load_pixels_rectangle_74) | Carga píxeles. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_75) | Carga datos sin procesar. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_76) | Carga datos sin procesar. |
| [load_stream(stream)](#load_stream_stream_77) | Carga una nueva imagen desde el flujo especificado. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_78) | Carga una nueva imagen desde el flujo especificado. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_79) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| normalize_angle() | Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la distorsión del escaneo.<br/>            Este método utiliza los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_80) | Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la distorsión del escaneo.<br/>            Este método utiliza los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/). |
| normalize_histogram() | Normaliza el histograma de la imagen — ajusta los valores de píxeles para usar todo el rango disponible. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_81) | Lee toda la línea de escaneo según el índice de línea de escaneo especificado. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_82) | Lee toda la línea de escaneo según el índice de línea de escaneo especificado. |
| [remove_block(block)](#remove_block_block_83) | Elimine el bloque WebP especificado de la imagen, facilitando una gestión eficiente <br/> de la estructura de datos de la imagen. Utilice este método para optimizar los flujos de trabajo de procesamiento de imágenes <br/> al eliminar bloques o componentes innecesarios dentro de su aplicación. |
| remove_metadata() | Elimina los metadatos de esta instancia de imagen estableciendo el valor de [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) a **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_84) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_85) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_86) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_87) | Reemplaza todos los colores no transparentes con un nuevo color y preserva el valor alfa original para mantener bordes suaves.<br/>                Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_88) | Reemplaza todos los colores no transparentes con un nuevo color y preserva el valor alfa original para mantener bordes suaves.<br/>                Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo. |
| [resize(new_width, new_height)](#resize_new_width_new_height_89) | Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_90) | Redimensione la imagen, ajustando sus dimensiones mientras preserva la relación de aspecto. <br/> Integre este método en su flujo de trabajo de procesamiento de imágenes para escalar dinámicamente <br/> las imágenes y adaptarlas a diversos requisitos de visualización o almacenamiento dentro de su aplicación. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_91) | Redimensione la imagen según la configuración especificada, permitiendo un control preciso sobre <br/> dimensiones, relación de aspecto y comportamiento de escalado. Integre este método en su <br/> flujo de trabajo de procesamiento de imágenes para lograr operaciones de redimensionado personalizadas adaptadas a <br/> los requisitos específicos de su aplicación. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_92) | Redimensiona la imagen. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_93) | Redimensiona la imagen. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_94) | Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_95) | Ajuste la altura de la imagen de forma proporcional, mientras preserva su relación de aspecto <br/> para un redimensionado consistente. Integre este método en su flujo de trabajo de procesamiento de imágenes <br/> para redimensionar dinámicamente las imágenes con proporciones uniformes, garantizando una visualización o <br/> almacenamiento óptimo dentro de su aplicación. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_96) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_97) | Redimensiona la altura proporcionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_98) | Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_99) | Ajuste proporcionalmente el ancho de la imagen mientras mantiene su relación de aspecto. <br/> Integre este método en su flujo de trabajo de procesamiento de imágenes para redimensionar dinámicamente <br/> las imágenes con proporciones consistentes, garantizando una visualización o almacenamiento óptimo dentro de <br/> su aplicación. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_100) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_101) | Redimensiona el ancho proporcionalmente. |
| [rotate(angle)](#rotate_angle_102) | Rotar la imagen alrededor del centro. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_103) | Gire la imagen alrededor de su centro mediante un ángulo especificado, mientras la redimensiona proporcionalmente <br/> y aplica los parámetros de color de fondo especificados. Incorpore este <br/> método en su flujo de trabajo de procesamiento de imágenes para lograr transformaciones precisas con <br/> colores de fondo personalizables, garantizando una presentación visual óptima dentro de su <br/> aplicación. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_104) | Aplique rotación, volteo o ambas operaciones exclusivamente al fotograma activo <br/> dentro de la imagen. Integre este método en su flujo de trabajo de procesamiento de imágenes para <br/> lograr una manipulación precisa de fotogramas individuales, mejorando la flexibilidad y el <br/> control sobre las transformaciones de fotogramas dentro de su aplicación. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_105) | Rota el volteo completo. |
| save() | Guarda los datos de la imagen en el flujo subyacente. |
| [save(file_path)](#save_file_path_106) | Guarda la imagen en la ubicación de archivo especificada. |
| [save(file_path, options)](#save_file_path_options_107) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_108) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, over_write)](#save_file_path_over_write_109) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(stream)](#save_stream_110) | Guarda los datos. |
| [save(stream, options_base)](#save_stream_options_base_111) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_112) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_113) | Guarda los píxeles ARGB de 32 bits. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_114) | Guarda los píxeles. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_115) | Guarda los píxeles.<br/>            Este método está obsoleto. Por favor, utiliza de forma más eficaz el método [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_116) | Guarda los píxeles internos principales. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_117) | Guarda los datos sin procesar. |
| [save_to_stream(stream)](#save_to_stream_stream_118) | Guarda los datos del objeto en el flujo especificado. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_119) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_121) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_122) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_123) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_124) | Establece la paleta de la imagen. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_125) | Establece un píxel de la imagen para la posición especificada. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_126) | Establece la resolución para este [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_127) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_128) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_129) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |


### Constructor: WebPImage(path) {#WebPImage_path_1}


```
 WebPImage(path) 
```

Crea una nueva instancia fresca de la [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) clase, inicializada <br/>            desde una fuente de archivo proporcionada. Utiliza este constructor para crear sin problemas objetos de imagen WebP <br/>            directamente desde archivos, optimizando el proceso de carga y <br/>            manipulación de datos de imágenes WebP dentro de tu aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta al archivo de imagen WebP |


**See also:**

**[Example # 1](#example_164)**: This example shows how to load a WebP image from a file and save it to PNG.


### Constructor: WebPImage(path, load_options) {#WebPImage_path_load_options_2}


```
 WebPImage(path, load_options) 
```

Crea una nueva instancia de la [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) clase usando un archivo y <br/>            opciones de carga especificadas, facilitando el manejo flexible de datos de imágenes WebP. Utiliza <br/>            este constructor para inicializar sin problemas objetos de imagen WebP desde archivos mientras <br/>            personalizas los parámetros de carga según los requisitos de tu aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta al archivo de imagen WebP |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

### Constructor: WebPImage(raster_image) {#WebPImage_raster_image_3}


```
 WebPImage(raster_image) 
```

Instancia una nueva instancia de la [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) clase, inicializada <br/>            desde un objeto rasterImage proporcionado. Este constructor permite una conversión sin problemas <br/>            de imágenes raster a formato WebP, habilitando un manejo eficiente y <br/>            manipulación de datos de imagen dentro de tu aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |


**See also:**

**[Example # 1](#example_166)**: This example shows how to create a WebP image from another raster image.


### Constructor: WebPImage(raster_image, load_options) {#WebPImage_raster_image_load_options_4}


```
 WebPImage(raster_image, load_options) 
```

Crea una nueva instancia de la [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) clase usando un objeto rasterImage y <br/>            opciones de carga especificadas, habilitando un manejo flexible de datos de imagen. Utiliza este <br/>            constructor para inicializar sin problemas objetos de imagen WebP desde imágenes raster mientras <br/>            personalizas los parámetros de carga según los requisitos de tu aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

### Constructor: WebPImage(stream) {#WebPImage_stream_5}


```
 WebPImage(stream) 
```

Instanciar una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/), inicializada <br/>            a partir de una fuente de flujo proporcionada. Utilice este constructor para crear sin problemas objetos de imagen WebP <br/>            directamente desde flujos, permitiendo un manejo y manipulación eficientes <br/>            de los datos de imagen WebP dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo de imagen WebP. |


**See also:**

**[Example # 1](#example_165)**: This example shows how to load a WebP image from a file stream and save it to...


### Constructor: WebPImage(stream, load_options) {#WebPImage_stream_load_options_6}


```
 WebPImage(stream, load_options) 
```

Crear una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) a partir de un flujo, <br/>            incorporando opciones de carga especificadas y configuraciones de gestión de memoria. Este <br/>            constructor ofrece flexibilidad al cargar imágenes WebP desde flujos mientras <br/>            gestiona eficientemente los recursos de memoria, garantizando un rendimiento óptimo y la utilización <br/>            de recursos dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo de imagen WebP. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

### Constructor: WebPImage(width, height, options) {#WebPImage_width_height_options_7}


```
 WebPImage(width, height, options) 
```

Instanciar una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) con una imagen vacía de ancho y alto especificados. Este constructor permite la <br/>            creación de imágenes WebP en blanco, proporcionando una base para la manipulación posterior de imágenes <br/>            y la generación de contenido dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho de la imagen |
| height | int | El alto de la imagen. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | Las opciones. |


**See also:**

**[Example # 1](#example_167)**: This example shows how to create a WebP image with the specified options from...


### Constructor: WebPImage(width, height, options, load_options) {#WebPImage_width_height_options_load_options_8}


```
 WebPImage(width, height, options, load_options) 
```

Crear una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) con una imagen vacía y opciones de carga especificadas. Este constructor permite la inicialización de imágenes WebP con <br/>            parámetros de carga personalizables, proporcionando flexibilidad en la creación y <br/>            manipulación de imágenes dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho de la imagen |
| height | int | El alto de la imagen. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | Las opciones. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

### Property: has_alpha {#has_alpha1}

Obtener si la imagen contiene un canal alfa, lo que indica la presencia de <br/>            información de transparencia. Utilice esta propiedad para determinar si la imagen <br/>            incluye transparencia, permitiendo un manejo y procesamiento adecuados de <br/>            operaciones relacionadas con alfa dentro de su aplicación.

**See also:**

**[Example # 1](#example_168)**: The following example loads a WEBP image and prints information about raw dat...


### Method: add_block(block) {#add_block_block_1}


```
 add_block(block) 
```

Incorporar un nuevo bloque WebP en la imagen, enriqueciendo su contenido y <br/>            facilitando la manipulación avanzada de imágenes. Integre este método para mejorar dinámicamente <br/>            la estructura y complejidad de los datos de imagen WebP dentro de su <br/>            aplicación, permitiendo un control preciso y la optimización del renderizado de imágenes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | El bloque WebP a agregar. |

### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Agregar una nueva página a la imagen, ampliando su contenido y acomodando elementos visuales adicionales. Integre este método para facilitar la gestión dinámica de páginas <br/>            dentro de su aplicación, permitiendo la creación y ampliación sin problemas de documentos o imágenes multipágina.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La página a añadir. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Implementar ajuste de _brightness_ para la imagen, permitiendo la <br/>            modificación de los niveles de luminancia generales. Incorpore este método en su flujo de procesamiento de imágenes para mejorar la visibilidad y la calidad visual de las imágenes <br/>            dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brillo | int | Valor de brillo. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Mejorar el contraste de la [Image](/imaging/python-net/aspose.imaging/image/), amplificando las <br/>            diferencias entre áreas claras y oscuras. Integre este método en su flujo de procesamiento de imágenes para mejorar la claridad visual y la calidad general de la imagen dentro <br/>            de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| contraste | float | Valor de contraste (en el rango [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Aplicar corrección gamma a la imagen, ajustando las intensidades de los píxeles para lograr <br/>            el brillo y el balance de color deseados. Incorpore este método en su flujo de procesamiento de imágenes para mejorar la calidad visual y la precisión de <br/>            los análisis o tareas de visualización posteriores dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Realizar corrección gamma en la imagen usando coeficientes individuales para los canales rojo, <br/>            verde y azul, permitiendo ajustes finos del balance de color y el <br/>            contraste. Integre este método en su canal de procesamiento de imágenes para lograr <br/>            un control preciso sobre la representación del color y mejorar la fidelidad visual dentro de su <br/>            aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| gamma_red | float | Coeficiente gamma para el canal rojo |
| gamma_green | float | Coeficiente gamma para el canal verde |
| gamma_blue | float | Gamma para el coeficiente del canal azul |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_7}


```
 analyze_percentage_digital_signature(password) 
```

Calcula el porcentaje de similitud entre los datos extraídos y la contraseña original.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | string | La contraseña utilizada para extraer los datos incrustados. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor de porcentaje de similitud. |


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_8}


```
 binarize_bradley(brightness_difference) 
```

Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brightness_difference | float | La diferencia de brillo entre el píxel y el promedio de una ventana de píxeles de s x s<br/>                centrada alrededor de este píxel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

Aplicar binarización a la imagen usando el algoritmo de umbral adaptativo de Bradley <br/>            con umbralización de imagen integral. Este método calcula dinámicamente umbrales locales <br/>            basados en el vecindario de la imagen, mejorando la adaptabilidad a condiciones de iluminación variables y garantizando una segmentación robusta para tareas de procesamiento posteriores <br/>            dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brightness_difference | float | La diferencia de brillo entre el píxel y el promedio de una ventana de píxeles de s x s<br/>            centrada alrededor de este píxel. |
| window_size | int | El tamaño de la ventana de píxeles de s x s centrada alrededor de este píxel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

Realizar binarización en la imagen usando un valor de umbral predefinido, convirtiéndola en una imagen binaria donde los píxeles se clasifican como primer plano o fondo <br/>            según su intensidad relativa al umbral. Integre este método en <br/>            su flujo de procesamiento de imágenes para facilitar la segmentación y extracción de características <br/>            , mejorando la precisión y eficiencia del análisis posterior dentro de su <br/>            aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| umbral | System.Byte | Valor de umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se asignará un valor de<br/>            255, de lo contrario 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_11}


```
 blend(origin, overlay, overlay_alpha) 
```

Mezcla esta instancia de imagen con la imagen _overlay_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | El origen de la fusión de la imagen de fondo. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen superpuesta. |
| overlay_alpha | System.Byte | El alfa de la superposición. |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_12}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

Mezcla esta instancia de imagen con la imagen _overlay_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | El origen de la fusión de la imagen de fondo. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen superpuesta. |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El área de superposición. |
| overlay_alpha | System.Byte | El alfa de la superposición. |

### Method: can_load(file_path)  [static] {#can_load_file_path_13}


```
 can_load(file_path) 
```

Determina si la imagen puede cargarse desde la ruta de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el archivo especificado; de lo contrario, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_14}


```
 can_load(file_path, load_options) 
```

Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el archivo especificado; de lo contrario, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_15}


```
 can_load(stream) 
```

Determina si la imagen puede cargarse desde el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el flujo especificado; de lo contrario, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_16}


```
 can_load(stream, load_options) 
```

Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando los _loadOptions_ especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el flujo especificado; de lo contrario, <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_17}


```
 can_load_stream(stream) 
```

Determina si la imagen puede cargarse desde el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el flujo especificado; de lo contrario, <c>false</c>. |


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_18}


```
 can_load_stream_with_options(stream, load_options) 
```

Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando los _loadOptions_ especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el flujo especificado; de lo contrario, <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_19}


```
 can_load_with_options(file_path, load_options) 
```

Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el archivo especificado; de lo contrario, <c>false</c>. |


### Method: can_save(options) {#can_save_options_20}


```
 can_save(options) 
```

Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas; de lo contrario, <c>false</c>. |


### Method: create(files)  [static] {#create_files_21}


```
 create(files) 
```

Crea la imagen multipágina que contiene los archivos especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| files | string[] | Los archivos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen multipágina |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_22}


```
 create(files, throw_exception_on_load_error) 
```

Crea la imagen multipágina que contiene los archivos especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| files | string[] | Los archivos. |
| throw_exception_on_load_error | bool | si se establece en <c>true</c> [lanzar excepción al error de carga]. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen multipágina |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_23}


```
 create(image_options, width, height) 
```

Crea una nueva imagen usando las opciones de creación especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de la imagen. |
| width | int | El ancho. |
| height | int | La altura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen recién creada. |


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_24}


```
 create(image_options, width, height, pixels) 
```

Crea una instancia de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) a partir del arreglo de píxeles proporcionado.<br/> <br/> Valida que el ancho y alto especificados coincidan con las dimensiones de los datos de píxeles.<br/> Este método solo puede usarse cuando la biblioteca está en modo Licenciado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones usadas para crear el [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | El ancho del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| height | int | La altura del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| píxeles | int[] | La matriz de valores de píxeles usada para poblar la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Una [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) poblada con los datos de píxeles proporcionados. |


### Method: create(images)  [static] {#create_images_25}


```
 create(images) 
```

Crea una nueva imagen usando las imágenes especificadas como páginas

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Las imágenes. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La Imagen como IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_26}


```
 create(images, dispose_images) 
```

Crea una nueva imagen con las imágenes especificadas como páginas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Las imágenes. |
| dispose_images | bool | si se establece en <c>true</c> [eliminar imágenes]. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La Imagen como IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_27}


```
 create(multipage_create_options) 
```

Crea las opciones de creación multipágina especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | Las opciones de creación multipágina. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen multipágina |


### Method: create_from_file_with_options(path, load_options)  [static] {#create_from_file_with_options_path_load_options_28}


```
 create_from_file_with_options(path, load_options) 
```

Inicializa una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) a partir de un archivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta al archivo de imagen WebP |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_29}


```
 create_from_files(files) 
```

Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| files | string[] | Los archivos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen multipágina |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_30}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| files | string[] | Los archivos. |
| throw_exception_on_load_error | bool | si se establece en <c>true</c> lanzar excepción al error de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen multipágina |


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_31}


```
 create_from_image(raster_image) 
```

Inicializa una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) a partir de rasterImage.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_image_with_options(raster_image, load_options)  [static] {#create_from_image_with_options_raster_image_load_options_32}


```
 create_from_image_with_options(raster_image, load_options) 
```

Inicializa una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) a partir de rasterImage.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_33}


```
 create_from_images(images) 
```

Crea una nueva imagen usando las imágenes especificadas como páginas

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Las imágenes. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La Imagen como IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_34}


```
 create_from_images(images, dispose_images) 
```

Crea una nueva imagen con las imágenes especificadas como páginas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Las imágenes. |
| dispose_images | bool | si se establece en <c>true</c> [eliminar imágenes]. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La Imagen como IMultipageImage |


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_35}


```
 create_from_stream(stream) 
```

Inicializa una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/)<br/>                a partir de un flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo de imagen WebP. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_stream_with_options(stream, load_options)  [static] {#create_from_stream_with_options_stream_load_options_36}


```
 create_from_stream_with_options(stream, load_options) 
```

Inicializa una nueva instancia de la clase [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) a partir de un flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo de imagen WebP. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_37}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Recortar la imagen aplicando desplazamientos izquierda, derecha, superior e inferior, seleccionando efectivamente <br/>            una región de interés dentro de la imagen. Utilice este método para <br/>            extraer dinámicamente las porciones deseadas de la imagen mientras ajusta su composición <br/>            y enfoque según los requisitos de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| left_shift | int | El desplazamiento a la izquierda. |
| right_shift | int | El desplazamiento a la derecha. |
| top_shift | int | El desplazamiento superior. |
| bottom_shift | int | El desplazamiento inferior. |

### Method: crop(rectangle) {#crop_rectangle_38}


```
 crop(rectangle) 
```

Recortar la imagen usando una región rectangular especificada, eliminando porciones no deseadas <br/>            mientras se conserva el contenido deseado. Integre este método en su flujo de procesamiento de imágenes <br/>            para extraer y enfocar con precisión áreas específicas de interés <br/>            dentro de la imagen, mejorando la claridad y composición para diversas aplicaciones.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_39}


```
 dither(dithering_method, bits_count) 
```

Aplica dithering a la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | El método de tramado. |
| bits_count | int | El recuento final de bits para el tramado. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_40}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Realice el tramado en la imagen actual para reducir el bandado de color y mejorar la calidad visual <br/> . Integre este método en su flujo de trabajo de procesamiento de imágenes para lograr <br/> transiciones más suaves entre colores y mejorar la apariencia general de la <br/> imagen dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | El método de tramado. |
| bits_count | int | El recuento final de bits para el tramado. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta personalizada para el tramado. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_41}


```
 embed_digital_signature(password) 
```

Incrusta una firma digital basada en la contraseña proporcionada en cada página de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | string | La contraseña utilizada para generar datos de firma digital. |

### Method: filter(rectangle, options) {#filter_rectangle_options_42}


```
 filter(rectangle, options) 
```

Filtre el contenido dentro del rectángulo especificado, aplicando un filtro de procesamiento de imagen <br/> designado para realzar o modificar la región seleccionada. Integre este método <br/> en su flujo de trabajo de manipulación de imágenes para lograr mejoras dirigidas o <br/> transformaciones dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Las opciones. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_43}


```
 get_argb_32_pixel(x, y) 
```

Obtiene un píxel ARGB de 32 bits de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El píxel ARGB de 32 bits para la ubicación especificada. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_44}


```
 get_default_argb_32_pixels(rectangle) 
```

Obtiene la matriz predeterminada de píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo del cual obtener píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz predeterminada de píxeles. |


### Method: get_default_options(args) {#get_default_options_args_45}


```
 get_default_options(args) 
```

Obtiene las opciones predeterminadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| args | System.Object | Los argumentos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Opciones predeterminadas |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_46}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo del cual obtener píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | El cargador parcial de píxeles. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo del cual obtener píxeles. |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | El cargador parcial de datos sin procesar. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | La configuración de datos sin procesar. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_48}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Obtiene la matriz de datos sin procesar predeterminada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo del cual obtener datos sin procesar. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | La configuración de datos sin procesar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Byte | La matriz predeterminada de datos sin procesar. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_49}


```
 get_file_format(file_path) 
```

Obtiene el formato de archivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | El formato de archivo determinado. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_50}


```
 get_file_format(stream) 
```

Obtiene el formato de archivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | El formato de archivo determinado. |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_51}


```
 get_file_format_of_stream(stream) 
```

Obtiene el formato de archivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | El formato de archivo determinado. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_52}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Obtiene el rectángulo que se ajusta a la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo para obtener el rectángulo de ajuste. |
| píxeles | int[] | Los píxeles ARGB de 32 bits. |
| width | int | El ancho del objeto. |
| height | int | La altura del objeto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de ajuste o excepción si no se puede encontrar un rectángulo de ajuste. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_53}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Obtiene el rectángulo que se ajusta a la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo para obtener el rectángulo de ajuste. |
| width | int | El ancho del objeto. |
| height | int | La altura del objeto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de ajuste o excepción si no se puede encontrar un rectángulo de ajuste. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_54}


```
 get_modify_date(use_default) 
```

Obtiene la fecha y hora en que la imagen del recurso fue modificada por última vez.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| use_default | bool | si se establece en <c>true</c> utiliza la información de FileInfo como valor predeterminado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.DateTime | La fecha y hora en que la imagen del recurso fue modificada por última vez. |


### Method: get_original_options() {#get_original_options__55}


```
 get_original_options() 
```

Obtiene las opciones basadas en la configuración original del archivo.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            método [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al método [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) como segundo parámetro.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones basadas en la configuración original del archivo. |


### Method: get_pixel(x, y) {#get_pixel_x_y_56}


```
 get_pixel(x, y) 
```

Obtiene un píxel de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | El color del píxel para la ubicación especificada. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_57}


```
 get_proportional_height(width, height, new_width) 
```

Obtiene una altura proporcional.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho. |
| height | int | La altura. |
| new_width | int | El nuevo ancho. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La altura proporcional. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_58}


```
 get_proportional_width(width, height, new_height) 
```

Obtiene un ancho proporcional.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho. |
| height | int | La altura. |
| new_height | int | La nueva altura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El ancho proporcional. |


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_59}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

Convierte a aps.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de la imagen. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de recorte. |
| page_number | int[] | El número de página. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| _io.BufferedRandom | El flujo serializado |


### Method: get_skew_angle() {#get_skew_angle__60}


```
 get_skew_angle() 
```

Obtiene el ángulo de sesgo.<br/>            Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear.

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | El ángulo de sesgo, en grados. |


### Method: insert_block(index, block) {#insert_block_index_block_61}


```
 insert_block(index, block) 
```

Inserte un nuevo bloque WebP en el índice especificado dentro de la imagen, permitiendo un control preciso <br/> sobre la secuencia de bloques. Integre este método para incorporar sin problemas <br/> bloques WebP adicionales en la estructura de datos de la imagen, facilitando el procesamiento avanzado de imágenes <br/> y la optimización dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El elemento basado en cero, en el cual _block_ será<br/> insertado. |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | El bloque WebP a agregar. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_62}


```
 is_digital_signed(password, percentage_threshold) 
```

Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | string | La contraseña para verificar la firma. |
| percentage_threshold | int | El umbral (en porcentaje)[0-100] que determina si la imagen se considera firmada.<br/>            Si no se especifica, se aplicará un umbral predeterminado (<c>75</c>). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero si la imagen está firmada, de lo contrario falso. |


### Method: load(file_path)  [static] {#load_file_path_63}


```
 load(file_path) 
```

Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo o URL desde la cual cargar la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen cargada. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_64}


```
 load(file_path, load_options) 
```

Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo o URL desde la cual cargar la imagen. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen cargada. |


### Method: load(stream)  [static] {#load_stream_65}


```
 load(stream) 
```

Carga una nueva imagen desde el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen cargada. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_66}


```
 load(stream, load_options) 
```

Carga los datos desde el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo de imagen WebP. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_67}


```
 load_argb_32_pixels(rectangle) 
```

Carga píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar los píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz de píxeles ARGB de 32 bits cargada. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_68}


```
 load_argb_64_pixels(rectangle) 
```

Carga píxeles ARGB de 64 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar los píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz de píxeles ARGB de 64 bits cargada. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_69}


```
 load_cmyk_32_pixels(rectangle) 
```

Carga píxeles en formato CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar los píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz de píxeles CMYK cargada presentada como valores enteros de 32 bits. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_70}


```
 load_cmyk_pixels(rectangle) 
```

Carga píxeles en formato CMYK.<br/>            Este método está obsoleto. Por favor, use de manera más eficaz el método [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar los píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | La matriz de píxeles CMYK cargada. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carga parcialmente píxeles ARGB de 32 bits (por bloques).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar los píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | El cargador parcial de píxeles. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_72}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Carga parcialmente píxeles ARGB de 64 bits por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo deseado. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | El cargador de píxeles ARGB de 64 bits. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_73}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carga píxeles parcialmente por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo deseado. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | El cargador de píxeles. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_74}


```
 load_pixels(rectangle) 
```

Carga píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar los píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | La matriz de píxeles cargada. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_75}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Carga datos sin procesar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar datos sin procesar. |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Los límites de la imagen de destino. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | La configuración de datos sin procesar a usar para los datos cargados. Nota: si los datos no están en el formato especificado, se realizará una conversión de datos. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | El cargador de datos sin procesar. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_76}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Carga datos sin procesar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar datos sin procesar. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | La configuración de datos sin procesar a usar para los datos cargados. Nota: si los datos no están en el formato especificado, se realizará una conversión de datos. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | El cargador de datos sin procesar. |

### Method: load_stream(stream)  [static] {#load_stream_stream_77}


```
 load_stream(stream) 
```

Carga una nueva imagen desde el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen cargada. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_78}


```
 load_stream_with_options(stream, load_options) 
```

Carga una nueva imagen desde el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar la imagen. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen cargada. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_79}


```
 load_with_options(file_path, load_options) 
```

Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo o URL desde la cual cargar la imagen. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen cargada. |


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_80}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la distorsión del escaneo.<br/>            Este método utiliza los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| resize_proportionally | bool | si se establece a <c>true</c> el tamaño de su imagen se cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en otro caso, se dejan las dimensiones sin cambios y solo se rotan los contenidos internos de la imagen. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color del fondo. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_81}


```
 read_argb_32_scan_line(scan_line_index) 
```

Lee toda la línea de escaneo según el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int[] | La matriz de valores de color ARGB de 32 bits de la línea de escaneo. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_82}


```
 read_scan_line(scan_line_index) 
```

Lee toda la línea de escaneo según el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | La matriz de valores de color de píxeles de la línea de escaneo. |


### Method: remove_block(block) {#remove_block_block_83}


```
 remove_block(block) 
```

Elimine el bloque WebP especificado de la imagen, facilitando una gestión eficiente <br/> de la estructura de datos de la imagen. Utilice este método para optimizar los flujos de trabajo de procesamiento de imágenes <br/> al eliminar bloques o componentes innecesarios dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | El bloque a eliminar. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_84}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| old_color_argb | int | Valor ARGB del color antiguo a reemplazar. |
| old_color_diff | System.Byte | Diferencia permitida en el color antiguo para poder ampliar el tono del color reemplazado. |
| new_color_argb | int | Nuevo valor ARGB de color para reemplazar el color antiguo. |

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_85}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| old_color_diff | System.Byte | Diferencia permitida en el color antiguo para poder ampliar el tono del color reemplazado. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_86}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| old_color_argb | int | Valor ARGB del color antiguo a reemplazar. |
| old_color_diff | System.Byte | Diferencia permitida en el color antiguo para poder ampliar el tono del color reemplazado. |
| new_color_argb | int | Nuevo valor ARGB de color para reemplazar el color antiguo. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_87}


```
 replace_non_transparent_colors(new_color) 
```

Reemplaza todos los colores no transparentes con un nuevo color y preserva el valor alfa original para mantener bordes suaves.<br/>                Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_88}


```
 replace_non_transparent_colors(new_color_argb) 
```

Reemplaza todos los colores no transparentes con un nuevo color y preserva el valor alfa original para mantener bordes suaves.<br/>                Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_argb | int | Nuevo valor ARGB de color para reemplazar colores no transparentes. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_89}


```
 resize(new_width, new_height) 
```

Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_90}


```
 resize(new_width, new_height, resize_type) 
```

Redimensione la imagen, ajustando sus dimensiones mientras preserva la relación de aspecto. <br/> Integre este método en su flujo de trabajo de procesamiento de imágenes para escalar dinámicamente <br/> las imágenes y adaptarlas a diversos requisitos de visualización o almacenamiento dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | El tipo de redimensionamiento. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_91}


```
 resize(new_width, new_height, settings) 
```

Redimensione la imagen según la configuración especificada, permitiendo un control preciso sobre <br/> dimensiones, relación de aspecto y comportamiento de escalado. Integre este método en su <br/> flujo de trabajo de procesamiento de imágenes para lograr operaciones de redimensionado personalizadas adaptadas a <br/> los requisitos específicos de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_92}


```
 resize_by_settings(new_width, new_height, settings) 
```

Redimensiona la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento. |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_93}


```
 resize_by_type(new_width, new_height, resize_type) 
```

Redimensiona la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | El tipo de redimensionamiento. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_94}


```
 resize_height_proportionally(new_height) 
```

Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_95}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ajuste la altura de la imagen de forma proporcional, mientras preserva su relación de aspecto <br/> para un redimensionado consistente. Integre este método en su flujo de trabajo de procesamiento de imágenes <br/> para redimensionar dinámicamente las imágenes con proporciones uniformes, garantizando una visualización o <br/> almacenamiento óptimo dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_96}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_97}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_98}


```
 resize_width_proportionally(new_width) 
```

Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_99}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ajuste proporcionalmente el ancho de la imagen mientras mantiene su relación de aspecto. <br/> Integre este método en su flujo de trabajo de procesamiento de imágenes para redimensionar dinámicamente <br/> las imágenes con proporciones consistentes, garantizando una visualización o almacenamiento óptimo dentro de <br/> su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_100}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_101}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: rotate(angle) {#rotate_angle_102}


```
 rotate(angle) 
```

Rotar la imagen alrededor del centro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_103}


```
 rotate(angle, resize_proportionally, background_color) 
```

Gire la imagen alrededor de su centro mediante un ángulo especificado, mientras la redimensiona proporcionalmente <br/> y aplica los parámetros de color de fondo especificados. Incorpore este <br/> método en su flujo de trabajo de procesamiento de imágenes para lograr transformaciones precisas con <br/> colores de fondo personalizables, garantizando una presentación visual óptima dentro de su <br/> aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resize_proportionally | bool | si se establece en <c>true</c> el tamaño de su imagen cambiará<br/>            según las proyecciones del rectángulo rotado (puntos de esquina) en otro<br/>            caso, lo que deja las dimensiones sin cambios y solo<br/>            __internal__ el contenido de la imagen se rota. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color del fondo. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_104}


```
 rotate_flip(rotate_flip_type) 
```

Aplique rotación, volteo o ambas operaciones exclusivamente al fotograma activo <br/> dentro de la imagen. Integre este método en su flujo de trabajo de procesamiento de imágenes para <br/> lograr una manipulación precisa de fotogramas individuales, mejorando la flexibilidad y el <br/> control sobre las transformaciones de fotogramas dentro de su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | El tipo de volteo de rotación. |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_105}


```
 rotate_flip_all(rotate_flip) 
```

Rota el volteo completo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | El volteo de rotación. |

### Method: save(file_path) {#save_file_path_106}


```
 save(file_path) 
```

Guarda la imagen en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar la imagen. |

### Method: save(file_path, options) {#save_file_path_options_107}


```
 save(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_108}


```
 save(file_path, options, bounds_rectangle) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### Method: save(file_path, over_write) {#save_file_path_over_write_109}


```
 save(file_path, over_write) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |
| sobrescribir | bool | si se establece en <c>true</c> sobrescribe el contenido del archivo, de lo contrario se añadirá. |

### Method: save(stream) {#save_stream_110}


```
 save(stream) 
```

Guarda los datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |

### Method: save(stream, options_base) {#save_stream_options_base_111}


```
 save(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_112}


```
 save(stream, options_base, bounds_rectangle) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_113}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Guarda los píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | La matriz de píxeles ARGB de 32 bits. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_114}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Guarda los píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_115}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Guarda los píxeles.<br/>            Este método está obsoleto. Por favor, utiliza de forma más eficaz el método [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | La matriz de píxeles CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_116}


```
 save_pixels(rectangle, pixels) 
```

Guarda los píxeles internos principales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Los píxeles. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_117}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Guarda los datos sin procesar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | System.Byte | Los datos sin procesar. |
| data_offset | int | El desplazamiento inicial de los datos sin procesar. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de datos sin procesar. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | La configuración de datos sin procesar en la que se encuentran los datos. |

### Method: save_to_stream(stream) {#save_to_stream_stream_118}


```
 save_to_stream(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos del objeto. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_119}


```
 save_to_stream_with_options(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_121}


```
 save_with_options(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_122}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_123}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Establece un píxel ARGB de 32 bits de la imagen para la posición especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |
| argb_32_color | int | El píxel ARGB de 32 bits para la posición especificada. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_124}


```
 set_palette(palette, update_colors) 
```

Establece la paleta de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta a establecer. |
| update_colors | bool | si se establece en <c>true</c> los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas de paleta correspondientes. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_125}


```
 set_pixel(x, y, color) 
```

Establece un píxel de la imagen para la posición especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | El color del píxel para la posición especificada. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_126}


```
 set_resolution(dpi_x, dpi_y) 
```

Establece la resolución para este [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dpi_x | float | La resolución horizontal, en puntos por pulgada, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La resolución vertical, en puntos por pulgada, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_127}


```
 try_set_metadata(metadata) 
```

Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Los metadatos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero si _metadata_ no es nulo y la instancia de [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) <br/>            admite y/o implementa la instancia de [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); de lo contrario, falso. |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_128}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| argb_32_pixels | int[] | La matriz de colores ARGB de 32 bits para escribir. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_129}


```
 write_scan_line(scan_line_index, pixels) 
```

Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | La matriz de colores de píxeles para escribir. |

## **Examples**
### This example shows how to load a WebP image from a file and save it to PNG. {#example_164}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
# Cargue una imagen WebP desde un archivo.
with WebPImage(join(dir_, "test.webp")) as web_pimage:
	# Guardar como PNG
	# Tenga en cuenta que solo el fotograma activo se almacenará en PNG, ya que PNG no es un formato multipágina.
	web_pimage.save(join(dir_, "test.output.png"), PngOptions())


```

### This example shows how to load a WebP image from a file stream and save it to PNG. {#example_165}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Cargue una imagen WebP desde un flujo de archivo.
with open(join(dir_, "test.webp"), "w+b") as stream:
	with WebPImage(stream) as web_pimage:
		# Guardar como PNG
		# Tenga en cuenta que solo el fotograma activo se almacenará en PNG, ya que PNG no es un formato multipágina.
		web_pimage.save(join(dir_, "test.output.png"), PngOptions())


```

### This example shows how to create a WebP image from another raster image. {#example_166}
``` python
from os.path import join
from aspose.imaging import Graphics, Color
from aspose.imaging.fileformats.png import PngImage
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import WebPOptions      

dir_: str = "c:\\temp"
# Cargue una imagen PNG de 100x100 px.
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# Rellene toda la imagen de rojo.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Cree una imagen WebP basada en la imagen PNG.
	with WebPImage(png_image) as web_pimage:
		# Guardar en un archivo WebP con opciones predeterminadas
		web_pimage.save(join(dir_, "output.webp"), WebPOptions())


```

### This example shows how to create a WebP image with the specified options from scratch. {#example_167}
``` python
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import WebPOptions
from os.path import join


dir_: str = "c:\\temp"
create_options = WebPOptions()
create_options.lossless = True
create_options.quality = 100.0

# Crear una imagen WebP de 100x100 px.
with WebPImage(100, 100, create_options) as web_pimage:
	graphics = Graphics(web_pimage)
	# Rellene toda la imagen de rojo.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, web_pimage.bounds)
	# Guardar en un archivo WebP
	web_pimage.save(join(dir_, "output.webp"))


```

### The following example loads a WEBP image and prints information about raw data format and alpha channel. {#example_168}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.webp import WebPImage, WebPFrameBlock

dir_ = "c:\\temp"
file_name = dir_ + "sample.webp"
with Image.load(file_name) as image:
	webp_image = aspycore.as_of(image, WebPImage)
	# Si el fotograma TIFF activo tiene canal alfa, entonces se considera que toda la imagen TIFF tiene canal alfa.
	print(f"ImageFile={file_name}, FileFormat={webp_image.raw_data_format}, HasAlpha={webp_image.has_alpha}")
	i: int = 0
	for frame in webp_image.blocks:
		if aspycore.is_assignable(frame, WebPFrameBlock):
			frame_block = aspycore.as_of(frame, WebPFrameBlock)
			print(f"Frame={i}, FileFormat={frame_block.raw_data_format}, HasAlpha={frame_block.has_alpha}")
			i += 1

# La salida puede verse así:
# ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, canales usados: 1, HasAlpha=False
# Frame=0, FileFormat=RgbIndexed1Bpp, canales usados: 1, HasAlpha=False


```

