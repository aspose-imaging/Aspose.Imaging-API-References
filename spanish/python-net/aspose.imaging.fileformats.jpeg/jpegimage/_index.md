---
title: "Clase JpegImage"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.fileformats.jpeg/jpegimage/
---

**Summary:** Efficiently manipulate JPEG raster images with our API, offering support<br/>            for various color profiles such as RGB and CMYK, customizable bits per pixel<br/>            resolution, and processing of EXIF, JFIF, and XMP metadata containers.<br/>            Enjoy automated rotation based on orientation data and choose from different<br/>            compression levels, including lossless JPEG, to achieve optimal image quality<br/>            and file size balance for your projects.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.JpegImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IHasJpegExifData, RasterCachedImage

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [JpegImage(jpeg_options, width, height)](#JpegImage_jpeg_options_width_height_1) | Inicializa un nuevo objeto [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) con las opciones JPEG proporcionadas. <br/>            Este constructor le permite personalizar diversas configuraciones para la imagen JPEG, como <br/>            el nivel de compresión, la calidad y parámetros adicionales, otorgando un control preciso <br/>            sobre el formato de imagen resultante. |
| [JpegImage(path)](#JpegImage_path_2) | La clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) se inicia sin esfuerzo al invocar su <br/>            constructor con el parámetro de ruta especificado. Este constructor permite la creación fluida <br/>            de imágenes JPEG, garantizando una integración rápida en sus proyectos con facilidad. |
| [JpegImage(raster_image)](#JpegImage_raster_image_3) | Inicializa una nueva instancia de la clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) con un parámetro de imagen raster <br/>            Este constructor ofrece una forma conveniente de crear imágenes JPEG <br/>            directamente a partir de imágenes raster, optimizando el flujo de trabajo para trabajar con imágenes JPEG <br/>            en sus aplicaciones. |
| [JpegImage(stream)](#JpegImage_stream_4) | Inicializa un objeto de imagen JPEG con la clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) usando un <br/>            parámetro de flujo. Este constructor simplifica el proceso de trabajar con imágenes JPEG <br/>            ofreciendo un enfoque sencillo para integrarlas en sus proyectos <br/>            sin esfuerzo. |
| [JpegImage(width, height)](#JpegImage_width_height_5) | Cree una nueva instancia de la clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) con los parámetros de ancho <br/>            y altura especificados. Este constructor le permite crear imágenes JPEG con <br/>            dimensiones personalizadas, brindándole flexibilidad en la gestión de tamaños de imagen en su aplicación. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Obtiene o establece un valor que indica si se ajusta automáticamente la paleta. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece un valor para el color de fondo. |
| bits_per_pixel | int | r | Recupere la profundidad de píxeles de la imagen sin esfuerzo con esta propiedad, ofreciendo <br/>            información sobre la riqueza de la representación en color o escala de grises. Ya sea una <br/>            fotografía vibrante o una ilustración monocroma, esta propiedad proporciona información crucial <br/>            sobre la complejidad visual de la imagen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtiene los límites del objeto. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | El perfil de color CMYK asociado con imágenes JPEG CMYK y YCCK garantiza una conversión de color precisa <br/>            y fidelidad. Funciona en conjunto con el RGBColorProfile para <br/>            asegurar una representación de color exacta en diversos dispositivos y aplicaciones. <br/>            Esta combinación es crucial para mantener la consistencia en la renderización del color y <br/>            lograr una calidad de imagen óptima. |
| comentario | string | r/w | Gestione los comentarios de archivos JPEG con esta propiedad, permitiéndole agregar o recuperar <br/>            anotaciones descriptivas asociadas a la imagen. Ya sea etiquetando imágenes con <br/>            metadatos o añadiendo contexto adicional, esta propiedad ofrece flexibilidad en <br/>            la organización y categorización de sus archivos JPEG. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtiene el contenedor [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Obtiene el flujo de datos del objeto. |
| destination_cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | El perfil de color CMYK es fundamental para la conversión precisa de color de imágenes JPEG CMYK y YCCK <br/>            durante el proceso de guardado. Funciona en conjunto con el RGBColorProfile <br/>            para garantizar una representación de color correcta, manteniendo la consistencia y calidad en <br/>            diferentes dispositivos y software. Esta sincronización es crucial para lograr <br/>            una renderización de color precisa y fiable en las imágenes finales guardadas. |
| destination_rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | El RGBColorProfile es esencial para la conversión precisa de color de imágenes JPEG CMYK y YCCK <br/>            durante el proceso de guardado. Cuando se combina con el CMYKColorProfile, <br/>            garantiza que los colores se rendericen correctamente y mantiene la consistencia en <br/>            diferentes dispositivos y aplicaciones. Esta combinación es crucial para preservar la <br/>            representación de color prevista y lograr una salida de imagen de alta calidad. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | Gestione los datos EXIF con esta propiedad, permitiéndole agregar o recuperar metadatos <br/>            asociados a la imagen. Ya sea extrayendo información sobre los ajustes de la cámara <br/>            o modificando metadatos existentes, esta propiedad ofrece flexibilidad en <br/>            la gestión del contenedor de datos EXIF. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Recupere el formato de la imagen sin esfuerzo con esta propiedad. Proporciona <br/>            información valiosa sobre el formato de archivo, facilitando la integración fluida y <br/>            las verificaciones de compatibilidad en diversas plataformas y aplicaciones. |
| has_alpha | bool | r | Obtiene un valor que indica si esta instancia tiene alfa. |
| has_background_color | bool | r/w | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| has_transparent_color | bool | r/w | Obtiene o establece un valor que indica si esta instancia de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) tiene un color transparente. |
| height | int | r | Recupere la altura de la imagen sin esfuerzo con esta propiedad. Proporciona acceso rápido <br/>            a la dimensión vertical de la imagen, permitiéndole determinar eficientemente <br/>            su tamaño y relación de aspecto sin necesidad de cálculos complejos o <br/>            métodos adicionales. |
| horizontal_resolution | float | r/w | Esta propiedad le permite acceder a la resolución horizontal del<br/> [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), medida en píxeles por pulgada. Al establecer o recuperar<br/> este valor, puede controlar con precisión la resolución de la imagen, asegurándose de que<br/> cumpla con sus requisitos específicos de calidad y claridad. |
| ignore_embedded_color_profile | bool | r/w | Recupera o modifica la bandera que indica si el perfil de color incrustado es<br/> ignorado. Al establecer esta bandera, los usuarios pueden especificar si se debe usar el perfil de color predeterminado en lugar del incrustado. Esta opción garantiza un mayor<br/> control sobre la gestión del color, facilitando ajustes para la consistencia y<br/> compatibilidad en diversas plataformas y aplicaciones. |
| image_opacity | float | r | Obtiene la opacidad de esta imagen. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtiene o establece el monitor de interrupciones. |
| is_cached | bool | r | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| is_raw_data_available | bool | r | Obtiene un valor que indica si se admite la carga de datos sin procesar. |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata/) | r/w | Esta propiedad le permite acceder o modificar los datos JFIF (Formato de Intercambio de Archivos JPEG)<br/> asociados con la imagen JPEG. JFIF es un formato estándar para<br/> intercambiar imágenes comprimidas en JPEG entre computadoras y otros dispositivos. Al obtener<br/> o establecer esta propiedad, puede interactuar con los datos JFIF, que pueden incluir<br/> información como la resolución de la imagen, la relación de aspecto y la miniatura. |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | r | Obtenga acceso a las opciones JPEG empleadas durante la creación o carga de esta<br/> [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) instancia con facilidad. Esta propiedad ofrece detalles valiosos<br/> sobre la configuración específica utilizada, capacitando a los usuarios para comprender y replicar<br/> flujos de trabajo de procesamiento de imágenes de manera eficaz. Ya sea niveles de compresión, ajustes de calidad<br/> u otros parámetros, esta propiedad proporciona información esencial para<br/> una manipulación de imágenes sin problemas. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtiene los metadatos de la imagen. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. La paleta de colores no se usa cuando los píxeles se representan directamente. |
| premultiply_components | bool | r/w | Obtiene o establece un valor que indica si los componentes de la imagen deben ser premultiplicados. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Obtiene o establece el convertidor de color personalizado |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Esta propiedad recupera el formato de datos sin procesar de la imagen, lo que indica cómo los<br/> datos de la imagen están estructurados y codificados. Comprender el formato de datos sin procesar es<br/> esencial para procesar o manipular los datos de la imagen de manera eficaz. Proporciona<br/> información sobre la representación subyacente de la imagen, como si está<br/> comprimida, codificada en un espacio de color específico o almacenada en un formato de archivo<br/> particular. Acceder a esta propiedad le permite obtener información valiosa sobre la<br/> estructura de datos de la imagen, habilitándole a realizar diversas operaciones u optimizaciones<br/> adaptadas a su formato específico. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración, los datos se cargan sin conversión. |
| raw_fallback_index | int | r/w | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Obtiene o establece el convertidor de color indexado |
| raw_line_size | int | r | Obtiene el tamaño de línea sin procesar en bytes. |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | El perfil de color RGB para imágenes JPEG CMYK y YCCK garantiza una conversión y representación de color precisas. Debe combinarse con el CMYKColorProfile para<br/> mantener la consistencia y fidelidad en la renderización del color. Esta combinación es esencial para<br/> aplicaciones que requieren una gestión de color precisa y la reproducción de imágenes,<br/> asegurando que los datos RGB se interpreten y muestren correctamente. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtiene el tamaño del objeto. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene el color transparente de la imagen. |
| update_xmp_data | bool | r/w | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| use_palette | bool | r | Obtiene un valor que indica si se usa la paleta de la imagen. |
| use_raw_data | bool | r/w | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| vertical_resolution | float | r/w | Esta propiedad gestiona la resolución vertical, expresada en píxeles por pulgada, para<br/> la [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) asociada. Ajustar esta resolución impacta el<br/> tamaño y la calidad de la imagen cuando se imprime o muestra en un tamaño físico fijo.<br/> Al establecer esta propiedad, controla cuán densamente se empaquetan los píxeles de la imagen<br/> verticalmente, afectando su nitidez y claridad generales. |
| width | int | r | Esta propiedad recupera el ancho de la imagen, expresado en píxeles. Proporciona<br/> información esencial sobre las dimensiones de la imagen, permitiendo una renderización precisa,<br/> manipulación o visualización de los datos de la imagen. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtiene o establece los datos Xmp. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Ajuste de brillo para la imagen. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Contraste de imagen |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Corrección gamma de una imagen. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Corrección gamma de una imagen. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | Calcula el porcentaje de similitud entre los datos extraídos y la contraseña original. |
| auto_brightness_contrast() | Realiza una normalización automática adaptativa de brillo y contraste para toda la imagen. |
| auto_rotate() | Rota automáticamente la imagen basándose en los datos de orientación extraídos de los metadatos Exif <br/> . Este método garantiza que las imágenes se muestren en la orientación correcta, <br/> mejorando la experiencia del usuario y eliminando la necesidad de ajustes manuales. Al <br/> analizar la información Exif, la imagen se rota en consecuencia, proporcionando una experiencia de visualización fluida <br/> en diferentes plataformas y dispositivos. Este proceso de rotación automatizado simplifica la gestión de imágenes y mejora la usabilidad general, especialmente al <br/> trabajar con grandes lotes de imágenes con orientaciones variables. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binarización de una imagen con umbral predefinido |
| binarize_otsu() | Binarización de una imagen con umbral de Otsu |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_9) | Mezcla esta instancia de imagen con la imagen _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_10) | Mezcla esta instancia de imagen con la imagen _overlay_. |
| cache_data() | Almacena en caché los datos y garantiza que no se realizará una carga adicional de datos desde el [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) subyacente. |
| [can_load(file_path)](#can_load_file_path_11) | Determina si la imagen puede cargarse desde la ruta de archivo especificada. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_12) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas. |
| [can_load(stream)](#can_load_stream_13) | Determina si la imagen puede cargarse desde el flujo especificado. |
| [can_load(stream, load_options)](#can_load_stream_load_options_14) | Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando los _loadOptions_ especificados. |
| [can_load_stream(stream)](#can_load_stream_stream_15) | Determina si la imagen puede cargarse desde el flujo especificado. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_16) | Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando los _loadOptions_ especificados. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_17) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas. |
| [can_save(options)](#can_save_options_18) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| [create(files)](#create_files_19) | Crea la imagen multipágina que contiene los archivos especificados. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_20) | Crea la imagen multipágina que contiene los archivos especificados. |
| [create(image_options, width, height)](#create_image_options_width_height_21) | Crea una nueva imagen usando las opciones de creación especificadas. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_22) | Crea una instancia de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) a partir del arreglo de píxeles proporcionado.<br/> <br/> Valida que el ancho y alto especificados coincidan con las dimensiones de los datos de píxeles.<br/> Este método solo puede usarse cuando la biblioteca está en modo Licenciado. |
| [create(images)](#create_images_23) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create(images, dispose_images)](#create_images_dispose_images_24) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [create(multipage_create_options)](#create_multipage_create_options_25) | Crea las opciones de creación multipágina especificadas. |
| [create_from_files(files)](#create_from_files_files_26) | Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_27) | Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida. |
| [create_from_image(raster_image)](#create_from_image_raster_image_28) | Inicializa una nueva instancia de la clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/). |
| [create_from_images(images)](#create_from_images_images_29) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_30) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [create_from_stream(stream)](#create_from_stream_stream_31) | Inicializa una nueva instancia de la clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_32) | Recortar la imagen con desplazamientos. |
| [crop(rectangle)](#crop_rectangle_33) | Recortando la imagen. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_34) | Aplica dithering a la imagen actual. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_35) | Aplica dithering a la imagen actual. |
| [embed_digital_signature(password)](#embed_digital_signature_password_36) | Incrustar una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía. |
| [filter(rectangle, options)](#filter_rectangle_options_37) | Filtra el rectángulo especificado. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_38) | Obtiene un píxel ARGB de 32 bits de la imagen. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_39) | Obtiene la matriz predeterminada de píxeles ARGB de 32 bits. |
| [get_default_options(args)](#get_default_options_args_40) | Obtiene las opciones predeterminadas. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_41) | Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42) | Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_43) | Obtiene la matriz de datos sin procesar predeterminada. |
| [get_file_format(file_path)](#get_file_format_file_path_44) | Obtiene el formato de archivo. |
| [get_file_format(stream)](#get_file_format_stream_45) | Obtiene el formato de archivo. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_46) | Obtiene el formato de archivo. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Recupera la fecha y hora en que la imagen del recurso sufrió su última<br/> modificación. Este método proporciona metadatos valiosos, permitiendo a los usuarios rastrear y<br/> gestionar actualizaciones del archivo de imagen de manera eficaz. Al acceder a esta información, los usuarios<br/> pueden asegurar la integridad y actualidad de sus activos de imagen, facilitando la toma de decisiones informada<br/> respecto al uso y mantenimiento de la imagen. |
| [get_original_options()](#get_original_options__50) | Obtiene las opciones originales de la imagen de esta instancia de [Image](/imaging/python-net/aspose.imaging/image/). |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Obtiene un píxel de la imagen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Obtiene una altura proporcional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Obtiene un ancho proporcional. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_54) | Convierte a aps. |
| [get_skew_angle()](#get_skew_angle__55) | Obtiene el ángulo de sesgo.<br/>            Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear. |
| grayscale() | Transformación de una imagen a su representación en escala de grises |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_56) | Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral. |
| [load(file_path)](#load_file_path_57) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(file_path, load_options)](#load_file_path_load_options_58) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(stream)](#load_stream_59) | Carga una nueva imagen desde el flujo especificado. |
| [load(stream, load_options)](#load_stream_load_options_60) | Carga una nueva imagen desde el flujo especificado. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_61) | Carga píxeles ARGB de 32 bits. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_62) | Carga píxeles ARGB de 64 bits. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_63) | Carga píxeles en formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_64) | Carga píxeles en formato CMYK.<br/>            Este método está obsoleto. Por favor, use de manera más eficaz el método [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_65) | Carga parcialmente píxeles ARGB de 32 bits (por bloques). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_66) | Carga parcialmente píxeles ARGB de 64 bits por paquetes. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_67) | Carga píxeles parcialmente por paquetes. |
| [load_pixels(rectangle)](#load_pixels_rectangle_68) | Carga píxeles. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_69) | Carga datos sin procesar. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_70) | Carga datos sin procesar. |
| [load_stream(stream)](#load_stream_stream_71) | Carga una nueva imagen desde el flujo especificado. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_72) | Carga una nueva imagen desde el flujo especificado. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_73) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| normalize_angle() | Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la distorsión del escaneo.<br/>            Este método utiliza los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_74) | Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo.<br/>            Este método usa los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | Normaliza el histograma de la imagen — ajusta los valores de píxeles para usar todo el rango disponible. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_75) | Lee toda la línea de escaneo según el índice de línea de escaneo especificado. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_76) | Lee toda la línea de escaneo según el índice de línea de escaneo especificado. |
| remove_metadata() | Elimina los metadatos de esta instancia de imagen estableciendo los valores de [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) y [IHasExifData.exif_data](/imaging/python-net/aspose.imaging.exif/ihasexifdata/) a **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_77) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_78) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_79) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_80) | Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_81) | Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [resize(new_width, new_height)](#resize_new_width_new_height_82) | Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_83) | Redimensiona la imagen. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_84) | Redimensiona la imagen. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_85) | Redimensiona la imagen. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_86) | Redimensiona la imagen. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_87) | Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_88) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_89) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_90) | Redimensiona la altura proporcionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_91) | Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_92) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_93) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_94) | Redimensiona el ancho proporcionalmente. |
| [rotate(angle)](#rotate_angle_95) | Rotar la imagen alrededor del centro. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_96) | Rotar la imagen alrededor del centro. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_97) | Rota, voltea o rota y voltea la imagen. |
| save() | Guarda los datos de la imagen en el flujo subyacente. |
| [save(file_path)](#save_file_path_98) | Guarda la imagen en la ubicación de archivo especificada. |
| [save(file_path, options)](#save_file_path_options_99) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_100) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, over_write)](#save_file_path_over_write_101) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(stream)](#save_stream_102) | Guarda los datos del objeto en el flujo especificado. |
| [save(stream, options_base)](#save_stream_options_base_103) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_104) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_105) | Guarda los píxeles ARGB de 32 bits. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_106) | Guarda los píxeles. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_107) | Guarda los píxeles.<br/>            Este método está obsoleto. Por favor, utiliza de forma más eficaz el método [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_108) | Guarda píxeles (método específico de formato). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_109) | Guarda los datos sin procesar. |
| [save_to_stream(stream)](#save_to_stream_stream_110) | Guarda los datos del objeto en el flujo especificado. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_111) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_112) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_113) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_114) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_115) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_116) | Establece la paleta de la imagen. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_117) | Establece un píxel de la imagen para la posición especificada. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_118) | Establece la resolución para el [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) especificado, asegurando<br/> un escalado y capacidades de impresión precisas. Este método capacita a los usuarios para adaptar<br/> la resolución de la imagen a sus requisitos específicos, ya sea para visualización digital<br/> o reproducción física. Al establecer la resolución, los usuarios pueden optimizar<br/> la calidad de la imagen y garantizar la compatibilidad con varios dispositivos y medios de salida,<br/> mejorando la experiencia visual general y la usabilidad de la imagen. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_119) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_120) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_121) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |


### Constructor: JpegImage(jpeg_options, width, height) {#JpegImage_jpeg_options_width_height_1}


```
 JpegImage(jpeg_options, width, height) 
```

Inicializa un nuevo objeto [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) con las opciones JPEG proporcionadas. <br/>            Este constructor le permite personalizar diversas configuraciones para la imagen JPEG, como <br/>            el nivel de compresión, la calidad y parámetros adicionales, otorgando un control preciso <br/>            sobre el formato de imagen resultante.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | Las opciones JPEG. |
| width | int | Ancho de la imagen. |
| height | int | Altura de la imagen. |

### Constructor: JpegImage(path) {#JpegImage_path_2}


```
 JpegImage(path) 
```

La clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) se inicia sin esfuerzo al invocar su <br/>            constructor con el parámetro de ruta especificado. Este constructor permite la creación fluida <br/>            de imágenes JPEG, garantizando una integración rápida en sus proyectos con facilidad.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta desde la cual cargar la imagen e inicializar los datos de píxeles y paleta. |


**See also:**

**[Example # 1](#example_106)**: The example shows how to load a JpegImage from a file.


### Constructor: JpegImage(raster_image) {#JpegImage_raster_image_3}


```
 JpegImage(raster_image) 
```

Inicializa una nueva instancia de la clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) con un parámetro de imagen raster <br/>            Este constructor ofrece una forma conveniente de crear imágenes JPEG <br/>            directamente a partir de imágenes raster, optimizando el flujo de trabajo para trabajar con imágenes JPEG <br/>            en sus aplicaciones.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen con la que inicializar los datos de píxeles y paleta. |


**See also:**

**[Example # 1](#example_107)**: The example shows how to load a JpegImage from another RasterImage.


### Constructor: JpegImage(stream) {#JpegImage_stream_4}


```
 JpegImage(stream) 
```

Inicializa un objeto de imagen JPEG con la clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) usando un <br/>            parámetro de flujo. Este constructor simplifica el proceso de trabajar con imágenes JPEG <br/>            ofreciendo un enfoque sencillo para integrarlas en sus proyectos <br/>            sin esfuerzo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |

### Constructor: JpegImage(width, height) {#JpegImage_width_height_5}


```
 JpegImage(width, height) 
```

Cree una nueva instancia de la clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) con los parámetros de ancho <br/>            y altura especificados. Este constructor le permite crear imágenes JPEG con <br/>            dimensiones personalizadas, brindándole flexibilidad en la gestión de tamaños de imagen en su aplicación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho de la imagen. |
| height | int | El alto de la imagen. |


**See also:**

**[Example # 1](#example_108)**: The following example shows how to create JPEG image of the specified size.


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Ajuste de brillo para la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brillo | int | Valor de brillo. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Contraste de imagen

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| contraste | float | Valor de contraste (en el rango [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Corrección gamma de una imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Corrección gamma de una imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| gamma_red | float | Coeficiente gamma para el canal rojo |
| gamma_green | float | Coeficiente gamma para el canal verde |
| gamma_blue | float | Gamma para el coeficiente del canal azul |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_5}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brightness_difference | float | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brightness_difference | float | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |
| window_size | int | El tamaño de la ventana de píxeles de s x s centrada alrededor de este píxel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binarización de una imagen con umbral predefinido

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| umbral | System.Byte | Valor de umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255, de lo contrario 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_9}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_10}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_11}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_12}


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


### Method: can_load(stream)  [static] {#can_load_stream_13}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_14}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_15}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_16}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_17}


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


### Method: can_save(options) {#can_save_options_18}


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


### Method: create(files)  [static] {#create_files_19}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_20}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_21}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_22}


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


### Method: create(images)  [static] {#create_images_23}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_24}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_25}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_26}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_27}


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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_28}


```
 create_from_image(raster_image) 
```

Inicializa una nueva instancia de la clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen con la que inicializar los datos de píxeles y paleta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_29}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_30}


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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_31}


```
 create_from_stream(stream) 
```

Inicializa una nueva instancia de la clase [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_32}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Recortar la imagen con desplazamientos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| left_shift | int | El desplazamiento a la izquierda. |
| right_shift | int | El desplazamiento a la derecha. |
| top_shift | int | El desplazamiento superior. |
| bottom_shift | int | El desplazamiento inferior. |

### Method: crop(rectangle) {#crop_rectangle_33}


```
 crop(rectangle) 
```

Recortando la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_34}


```
 dither(dithering_method, bits_count) 
```

Aplica dithering a la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | El método de tramado. |
| bits_count | int | El recuento final de bits para el tramado. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_35}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Aplica dithering a la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | El método de tramado. |
| bits_count | int | El recuento final de bits para el tramado. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta personalizada para el tramado. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_36}


```
 embed_digital_signature(password) 
```

Incrustar una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | string | La contraseña utilizada para generar datos de firma digital. |

### Method: filter(rectangle, options) {#filter_rectangle_options_37}


```
 filter(rectangle, options) 
```

Filtra el rectángulo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Las opciones. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_38}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_39}


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


### Method: get_default_options(args) {#get_default_options_args_40}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_41}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo del cual obtener píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | El cargador parcial de píxeles. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_43}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_44}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_45}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


```
 get_modify_date(use_default) 
```

Recupera la fecha y hora en que la imagen del recurso sufrió su última<br/> modificación. Este método proporciona metadatos valiosos, permitiendo a los usuarios rastrear y<br/> gestionar actualizaciones del archivo de imagen de manera eficaz. Al acceder a esta información, los usuarios<br/> pueden asegurar la integridad y actualidad de sus activos de imagen, facilitando la toma de decisiones informada<br/> respecto al uso y mantenimiento de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| use_default | bool | si se establece en <c>true</c> utiliza la información de FileInfo como valor predeterminado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.DateTime | La fecha y hora en que la imagen del recurso fue modificada por última vez. |


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Obtiene las opciones originales de la imagen de esta instancia de [Image](/imaging/python-net/aspose.imaging/image/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Una copia de las opciones originales de la imagen. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_54}


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


### Method: get_skew_angle() {#get_skew_angle__55}


```
 get_skew_angle() 
```

Obtiene el ángulo de sesgo.<br/>            Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear.

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | El ángulo de sesgo, en grados. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_56}


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


### Method: load(file_path)  [static] {#load_file_path_57}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_58}


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


### Method: load(stream)  [static] {#load_stream_59}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_60}


```
 load(stream, load_options) 
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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_61}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_62}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_63}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_64}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_65}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carga parcialmente píxeles ARGB de 32 bits (por bloques).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar los píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | El cargador parcial de píxeles. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_66}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Carga parcialmente píxeles ARGB de 64 bits por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo deseado. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | El cargador de píxeles ARGB de 64 bits. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_67}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carga píxeles parcialmente por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo deseado. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | El cargador de píxeles. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_68}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_69}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_70}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_71}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_72}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_73}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_74}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo.<br/>            Este método usa los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| resize_proportionally | bool | si se establece a <c>true</c> el tamaño de su imagen se cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en otro caso, se dejan las dimensiones sin cambios y solo se rotan los contenidos internos de la imagen. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color del fondo. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_75}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_76}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_77}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_78}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color antiguo a ser reemplazado. |
| old_color_diff | System.Byte | Diferencia permitida en el color antiguo para poder ampliar el tono del color reemplazado. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nuevo color con el que reemplazar el color antiguo. |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_79}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_80}


```
 replace_non_transparent_colors(new_color) 
```

Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nuevo color con el que reemplazar los colores no transparentes. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_81}


```
 replace_non_transparent_colors(new_color_argb) 
```

Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_argb | int | Nuevo valor ARGB de color para reemplazar colores no transparentes. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_82}


```
 resize(new_width, new_height) 
```

Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_83}


```
 resize(new_width, new_height, resize_type) 
```

Redimensiona la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | El tipo de redimensionamiento. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_84}


```
 resize(new_width, new_height, settings) 
```

Redimensiona la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_85}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_86}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_87}


```
 resize_height_proportionally(new_height) 
```

Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_88}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_89}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_90}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_91}


```
 resize_width_proportionally(new_width) 
```

Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_92}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_93}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_94}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: rotate(angle) {#rotate_angle_95}


```
 rotate(angle) 
```

Rotar la imagen alrededor del centro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_96}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rotar la imagen alrededor del centro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resize_proportionally | bool | si se establece a <c>true</c> el tamaño de su imagen se cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en otro caso, se dejan las dimensiones sin cambios y solo se rotan los contenidos internos de la imagen. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color del fondo. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_97}


```
 rotate_flip(rotate_flip_type) 
```

Rota, voltea o rota y voltea la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | El tipo de volteo de rotación. |

### Method: save(file_path) {#save_file_path_98}


```
 save(file_path) 
```

Guarda la imagen en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar la imagen. |

### Method: save(file_path, options) {#save_file_path_options_99}


```
 save(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_100}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_101}


```
 save(file_path, over_write) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |
| sobrescribir | bool | si se establece en <c>true</c> sobrescribe el contenido del archivo, de lo contrario se añadirá. |

### Method: save(stream) {#save_stream_102}


```
 save(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos del objeto. |

### Method: save(stream, options_base) {#save_stream_options_base_103}


```
 save(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_104}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_105}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Guarda los píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | La matriz de píxeles ARGB de 32 bits. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_106}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Guarda los píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_107}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Guarda los píxeles.<br/>            Este método está obsoleto. Por favor, utiliza de forma más eficaz el método [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | La matriz de píxeles CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_108}


```
 save_pixels(rectangle, pixels) 
```

Guarda píxeles (método específico de formato).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | La matriz de píxeles ARGB de 32 bits. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_109}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_110}


```
 save_to_stream(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos del objeto. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_111}


```
 save_to_stream_with_options(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_112}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_113}


```
 save_with_options(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_114}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_115}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_116}


```
 set_palette(palette, update_colors) 
```

Establece la paleta de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta a establecer. |
| update_colors | bool | si se establece en <c>true</c> los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas de paleta correspondientes. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_117}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_118}


```
 set_resolution(dpi_x, dpi_y) 
```

Establece la resolución para el [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) especificado, asegurando<br/> un escalado y capacidades de impresión precisas. Este método capacita a los usuarios para adaptar<br/> la resolución de la imagen a sus requisitos específicos, ya sea para visualización digital<br/> o reproducción física. Al establecer la resolución, los usuarios pueden optimizar<br/> la calidad de la imagen y garantizar la compatibilidad con varios dispositivos y medios de salida,<br/> mejorando la experiencia visual general y la usabilidad de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dpi_x | float | La resolución horizontal, en puntos por pulgada, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La resolución vertical, en puntos por pulgada, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_119}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_120}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| argb_32_pixels | int[] | La matriz de colores ARGB de 32 bits para escribir. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_121}


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
### The example shows how to load a JpegImage from a file. {#example_106}
``` python

from aspose.imaging.fileformats.jpeg import JpegImage

# Cargar una imagen JPEG desde un archivo.
with JpegImage("sample.jpg") as jpegImage:
	# Realizar algún procesamiento de imagen.
	# Guardar en otro archivo JPEG.
	jpegImage.save("sample.output.jpg")


```

### The example shows how to load a JpegImage from another RasterImage. {#example_107}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, RasterImage
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.jpeg import JpegImage
from os.path import join as path_join


dir_ = "c:\\temp"
# Cargar una imagen JPEG desde otra imagen raster.
# Primero, crea una imagen PNG temporal que será la base para construir una imagen JPEG.
# También puedes cargar una imagen PNG desde un archivo o usar una imagen de cualquier otro formato raster.
with PngOptions() as create_options:
	with aspycore.as_of(Image.create(create_options, 100, 100), RasterImage) as raster_image:
		# Rellena toda la imagen PNG de rojo.
		graphics = Graphics(raster_image)
		brush = SolidBrush(Color.red)
		graphics.fill_rectangle(brush, raster_image.bounds)
		# Crea una imagen JPEG basada en la imagen PNG.
		with JpegImage(raster_image) as jpeg_image:
			# Guardar en un archivo JPEG
			jpeg_image.save(path_join(dir_, "output.jpg"))


```

### The following example shows how to create JPEG image of the specified size. {#example_108}
``` python

from aspose.imaging.fileformats.jpeg import JpegImage

# Crea una imagen JPEG de 100x100 px.
with JpegImage(100, 100) as jpegImage:
	# Realizar algún procesamiento de imagen.
	# Guarde en un archivo.
	jpegImage.save("output.jpg")


```

### Access camera manufacturer maker notes in Jpeg image. {#example_222}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image
from aspose.imaging.fileformats.jpeg import JpegImage

with as_of(Image.load("Sample.jpg"), JpegImage) as image:
	for makerNote in image.exif_data.maker_notes:
		print(f"Name = {makerNote.name}, Value = {makerNote.value}")


```

