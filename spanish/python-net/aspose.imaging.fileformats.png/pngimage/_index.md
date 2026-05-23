---
title: "Clase PngImage"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.fileformats.png/pngimage/
---

**Summary:** Manipulate Portable Network Graphics (PNG) raster images with our versatile API,<br/>            featuring support for compression levels and various color depths including<br/>            Grayscale, Indexed Color, TrueColor, and alpha channels. Seamlessly process XMP metadata,<br/>            enabling comprehensive image metadata management, while easily loading PNG images,<br/>            performing diverse manipulations, applying filters, and converting images to other file<br/>            formats for optimal versatility and customization.

**Module:** [aspose.imaging.fileformats.png](/imaging/python-net/aspose.imaging.fileformats.png/)

**Full Name:** aspose.imaging.fileformats.png.PngImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PngImage(path)](#PngImage_path_1) | Construye una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) utilizando el parámetro path <br/>            para especificar la ubicación del archivo de imagen a cargar. Este constructor <br/>            permite a los desarrolladores crear imágenes PNG de forma cómoda cargándolas desde un archivo, <br/>            simplificando el proceso de trabajo con imágenes PNG en sus aplicaciones. |
| [PngImage(path, color_type)](#PngImage_path_color_type_2) | Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) especificando el <br/>            path al archivo de imagen y el tipo de color. Este constructor permite una creación <br/>            cómoda de imágenes PNG a partir de archivos con diferentes tipos de color, proporcionando <br/>            flexibilidad en el manejo de varios formatos de imagen. |
| [PngImage(png_options, width, height)](#PngImage_png_options_width_height_3) | Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) incorporando <br/>            opciones PNG junto con los parámetros de ancho y alto. Este constructor permite <br/>            a los desarrolladores crear imágenes PNG con configuraciones y dimensiones personalizables, <br/>            ofreciendo flexibilidad en la generación de imágenes para diversos casos de uso. |
| [PngImage(raster_image)](#PngImage_raster_image_4) | Crea una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) proporcionando una imagen raster <br/>            como parámetro. Este constructor permite a los desarrolladores inicializar directamente un <br/>            objeto de imagen PNG usando una imagen raster existente, agilizando el proceso de <br/>            trabajo con imágenes PNG en sus aplicaciones. |
| [PngImage(raster_image, color_type)](#PngImage_raster_image_color_type_5) | Crea una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) especificando una <br/>            imagen raster y un tipo de color. Este constructor permite a los desarrolladores convertir directamente <br/>            imágenes raster al formato PNG mientras se especifica el tipo de color deseado, <br/>            ofreciendo flexibilidad en la representación de colores. |
| [PngImage(stream)](#PngImage_stream_6) | Crea una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) inicializándola <br/>            con un flujo. Este constructor permite a los desarrolladores cargar imágenes PNG directamente <br/>            desde un flujo, proporcionando flexibilidad en la obtención de imágenes desde diferentes fuentes. |
| [PngImage(width, height)](#PngImage_width_height_7) | Inicializa un nuevo objeto de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) proporcionando los parámetros de <br/>            ancho y alto. Este constructor simplifica la creación de imágenes PNG al permitir a los desarrolladores especificar las dimensiones directamente, facilitando <br/>            la gestión eficiente de los datos de imágenes PNG dentro de sus aplicaciones. |
| [PngImage(width, height, color_type)](#PngImage_width_height_color_type_8) | Instancia una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) especificando <br/>            los parámetros deseados de ancho, alto y tipo de color. Este constructor permite <br/>            una creación rápida de imágenes PNG con dimensiones y configuraciones de color adaptadas, <br/>            facilitando una generación de imágenes optimizada para diversas aplicaciones y flujos de trabajo. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Obtiene o establece un valor que indica si se ajusta automáticamente la paleta. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene el color de fondo de la imagen, si se ha especificado uno. Esta propiedad <br/>            es útil para aplicaciones que necesitan identificar y potencialmente manipular <br/>            el color de fondo de una imagen. |
| bits_per_pixel | int | r | Recupera el valor de bits por píxel de la imagen. Esta propiedad brinda información crucial <br/>            sobre la profundidad de color de la imagen, permitiendo a los desarrolladores <br/>            comprender el nivel de detalle y precisión de color presente en los datos de la imagen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtiene los límites del objeto. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtiene el contenedor [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Obtiene el flujo de datos del objeto. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece la instancia Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Obtiene el formato del archivo asociado a la instancia de la imagen. Esta <br/>            propiedad proporciona información esencial sobre el tipo de archivo, permitiendo <br/>            un manejo y procesamiento eficientes basados en los requisitos específicos del formato. |
| [has_alpha](#has_alpha1) | bool | r | Devuelve un valor booleano que indica si la imagen tiene un canal alfa, <br/>            lo que determina su transparencia. Esta propiedad es útil para aplicaciones <br/>            que necesitan manejar la transparencia, permitiendo a los desarrolladores determinar si <br/>            se requiere procesamiento adicional para gestionar áreas transparentes en la imagen. |
| has_background_color | bool | r/w | Obtiene un valor booleano que indica si la imagen tiene un color de fondo. <br/>            Esta propiedad es útil para aplicaciones que necesitan determinar si una imagen <br/>            incluye un color de fondo, lo cual puede ser importante para diversas tareas de procesamiento <br/>            como composición, renderizado o exportación. |
| has_transparent_color | bool | r/w | Proporciona un valor booleano que indica si la imagen contiene un color transparente <br/>            . Esta propiedad es crucial para aplicaciones que necesitan manejar <br/>            la transparencia, permitiendo a los desarrolladores determinar si se requiere procesamiento adicional <br/>            para gestionar regiones transparentes en la imagen. |
| height | int | r | Obtenga la altura de la imagen. Esta propiedad devuelve la dimensión vertical de <br/>            la imagen, permitiendo a los desarrolladores determinar su tamaño en píxeles a lo largo del <br/>            eje vertical. |
| horizontal_resolution | float | r/w | Recupere o modifique la resolución horizontal de la imagen. Esta propiedad <br/>            representa el número de píxeles por pulgada a lo largo del eje horizontal de la <br/>            imagen. Ajustar esta resolución puede afectar el tamaño físico de la imagen al <br/>            imprimirse o mostrarse. |
| image_opacity | float | r | Obtiene la opacidad de esta imagen. |
| interlaced | bool | r | Obtiene un valor booleano que indica si el [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) está <br/>            entrelazado, lo que determina si los datos de la imagen se almacenan de forma progresiva <br/>            para una carga o transmisión más rápida. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtiene o establece el monitor de interrupciones. |
| is_cached | bool | r | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| is_interlaced | bool | r | Devuelve un valor booleano que indica si la instancia de la imagen está entrelazada. Esta <br/>            propiedad es crucial para optimizar las estrategias de carga y garantizar un rendimiento eficiente <br/>            durante el procesamiento o la visualización de imágenes. |
| is_raw_data_available | bool | r | Obtiene un valor que indica si se admite la carga de datos sin procesar. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtiene los metadatos de la imagen. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. La paleta de colores no se usa cuando los píxeles se representan directamente. |
| premultiply_components | bool | r/w | Obtiene o establece un valor que indica si los componentes de la imagen deben ser premultiplicados. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Obtiene o establece el convertidor de color personalizado |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Accede al formato de datos sin procesar de la imagen. Esta propiedad brinda información sobre <br/>            cómo se estructuran internamente los datos de la imagen, lo que puede ser útil para tareas avanzadas <br/>            de procesamiento de imágenes o conversión de formatos. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración, los datos se cargan sin conversión. |
| raw_fallback_index | int | r/w | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Obtiene o establece el convertidor de color indexado |
| raw_line_size | int | r | Obtiene el tamaño de línea sin procesar en bytes. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtiene el tamaño del objeto. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene el color transparente de la imagen, si existe. Esta propiedad es <br/>            valiosa para aplicaciones que requieren un manejo preciso de áreas transparentes <br/>            dentro de las imágenes, permitiendo a los desarrolladores acceder y manipular el <br/>            color transparente específico utilizado. |
| update_xmp_data | bool | r/w | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| use_palette | bool | r | Obtiene un valor que indica si se usa la paleta de la imagen. |
| use_raw_data | bool | r/w | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| vertical_resolution | float | r/w | Proporciona acceso a la resolución vertical de la imagen. Los desarrolladores pueden usar <br/>            esta propiedad para obtener o modificar la configuración de resolución, que indica el <br/>            número de píxeles por pulgada (PPI) a lo largo del eje vertical de la imagen. |
| width | int | r | Permite obtener el ancho de la imagen, proporcionando información esencial <br/>            sobre sus dimensiones. Esta propiedad es frecuentemente utilizada por los desarrolladores para <br/>            determinar el ancho de la imagen, permitiéndoles realizar diversas operaciones basadas <br/>            en su tamaño. |
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
| [create_from_file_with_color_type(path, color_type)](#create_from_file_with_color_type_path_color_type_26) | Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_from_files(files)](#create_from_files_files_27) | Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_28) | Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida. |
| [create_from_image(raster_image)](#create_from_image_raster_image_29) | Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_from_image_with_color_type(raster_image, color_type)](#create_from_image_with_color_type_raster_image_color_type_30) | Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_from_images(images)](#create_from_images_images_31) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [create_from_stream(stream)](#create_from_stream_stream_33) | Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_with_width_height(width, height)](#create_with_width_height_width_height_34) | Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_with_width_height_color_type(width, height, color_type)](#create_with_width_height_color_type_width_height_color_type_35) | Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_with_width_height_options(png_options, width, height)](#create_with_width_height_options_png_options_width_height_36) | Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_37) | Recortar la imagen con desplazamientos. |
| [crop(rectangle)](#crop_rectangle_38) | Recortando la imagen. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_39) | Aplica dithering a la imagen actual. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_40) | Aplica dithering a la imagen actual. |
| [embed_digital_signature(password)](#embed_digital_signature_password_41) | Incrustar una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía. |
| [filter(rectangle, options)](#filter_rectangle_options_42) | Filtra el rectángulo especificado. |
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
| [get_modify_date(use_default)](#get_modify_date_use_default_54) | Obtiene la marca de tiempo que indica la modificación más reciente del recurso <br/>            de la imagen. Este método brinda acceso a metadatos vitales, permitiendo a las aplicaciones <br/>            determinar cuándo se modificó por última vez la imagen, facilitando el seguimiento de versiones y <br/>            la gestión de contenido. |
| [get_original_options()](#get_original_options__55) | Obtiene las opciones basadas en la configuración original del archivo.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            método [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al método [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) como segundo parámetro. |
| [get_pixel(x, y)](#get_pixel_x_y_56) | Obtiene un píxel de la imagen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_57) | Obtiene una altura proporcional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_58) | Obtiene un ancho proporcional. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_59) | Convierte a aps. |
| [get_skew_angle()](#get_skew_angle__60) | Obtiene el ángulo de sesgo.<br/>            Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear. |
| grayscale() | Transformación de una imagen a su representación en escala de grises |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_61) | Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral. |
| [load(file_path)](#load_file_path_62) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(file_path, load_options)](#load_file_path_load_options_63) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(stream)](#load_stream_64) | Carga una nueva imagen desde el flujo especificado. |
| [load(stream, load_options)](#load_stream_load_options_65) | Carga una nueva imagen desde el flujo especificado. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_66) | Carga píxeles ARGB de 32 bits. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_67) | Carga píxeles ARGB de 64 bits. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_68) | Carga píxeles en formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_69) | Carga píxeles en formato CMYK.<br/>            Este método está obsoleto. Por favor, use de manera más eficaz el método [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70) | Carga parcialmente píxeles ARGB de 32 bits (por bloques). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71) | Carga parcialmente píxeles ARGB de 64 bits por paquetes. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_72) | Carga píxeles parcialmente por paquetes. |
| [load_pixels(rectangle)](#load_pixels_rectangle_73) | Carga píxeles. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74) | Carga datos sin procesar. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75) | Carga datos sin procesar. |
| [load_stream(stream)](#load_stream_stream_76) | Carga una nueva imagen desde el flujo especificado. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_77) | Carga una nueva imagen desde el flujo especificado. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_78) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| normalize_angle() | Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la distorsión del escaneo.<br/>            Este método utiliza los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_79) | Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo.<br/>            Este método usa los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | Normaliza el histograma de la imagen — ajusta los valores de píxeles para usar todo el rango disponible. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_80) | Lee toda la línea de escaneo según el índice de línea de escaneo especificado. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_81) | Lee toda la línea de escaneo según el índice de línea de escaneo especificado. |
| remove_metadata() | Elimina los metadatos de esta instancia de imagen estableciendo el valor de [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) a **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_82) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_83) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_84) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_85) | Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_86) | Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [resize(new_width, new_height)](#resize_new_width_new_height_87) | Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_88) | Redimensiona la imagen. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_89) | Redimensiona la imagen. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_90) | Redimensiona la imagen. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_91) | Redimensiona la imagen. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_92) | Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_93) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_94) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_95) | Redimensiona la altura proporcionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_96) | Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_97) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_98) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_99) | Redimensiona el ancho proporcionalmente. |
| [rotate(angle)](#rotate_angle_100) | Rotar la imagen alrededor del centro. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_101) | Rotar la imagen alrededor del centro. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_102) | Rota, voltea o rota y voltea la imagen. |
| save() | Guarda los datos de la imagen en el flujo subyacente. |
| [save(file_path)](#save_file_path_103) | Guarda la imagen en la ubicación de archivo especificada. |
| [save(file_path, options)](#save_file_path_options_104) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_105) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, over_write)](#save_file_path_over_write_106) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(stream)](#save_stream_107) | Los datos guardados. |
| [save(stream, options_base)](#save_stream_options_base_108) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_109) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_110) | Guarda los píxeles ARGB de 32 bits. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_111) | Guarda los píxeles. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_112) | Guarda los píxeles.<br/>            Este método está obsoleto. Por favor, utiliza de forma más eficaz el método [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_113) | Guarda píxeles (método específico de formato). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_114) | Guarda los datos sin procesar. |
| [save_to_stream(stream)](#save_to_stream_stream_115) | Guarda los datos del objeto en el flujo especificado. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_116) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_118) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_119) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_120) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_121) | Establece la paleta de la imagen. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_122) | Establece un píxel de la imagen para la posición especificada. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_123) | Establece la resolución para este [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_124) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_126) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |


### Constructor: PngImage(path) {#PngImage_path_1}


```
 PngImage(path) 
```

Construye una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) utilizando el parámetro path <br/>            para especificar la ubicación del archivo de imagen a cargar. Este constructor <br/>            permite a los desarrolladores crear imágenes PNG de forma cómoda cargándolas desde un archivo, <br/>            simplificando el proceso de trabajo con imágenes PNG en sus aplicaciones.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta para cargar una imagen. |


**See also:**

**[Example # 1](#example_109)**: This example shows how to load a PNG image from a file.


### Constructor: PngImage(path, color_type) {#PngImage_path_color_type_2}


```
 PngImage(path, color_type) 
```

Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) especificando el <br/>            path al archivo de imagen y el tipo de color. Este constructor permite una creación <br/>            cómoda de imágenes PNG a partir de archivos con diferentes tipos de color, proporcionando <br/>            flexibilidad en el manejo de varios formatos de imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta para cargar una imagen. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | El tipo de color. |


**See also:**

**[Example # 1](#example_110)**: This example shows how to load a PNG image from a file with the specified col...


### Constructor: PngImage(png_options, width, height) {#PngImage_png_options_width_height_3}


```
 PngImage(png_options, width, height) 
```

Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) incorporando <br/>            opciones PNG junto con los parámetros de ancho y alto. Este constructor permite <br/>            a los desarrolladores crear imágenes PNG con configuraciones y dimensiones personalizables, <br/>            ofreciendo flexibilidad en la generación de imágenes para diversos casos de uso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | Las opciones de PNG. |
| width | int | El ancho. |
| height | int | La altura. |

### Constructor: PngImage(raster_image) {#PngImage_raster_image_4}


```
 PngImage(raster_image) 
```

Crea una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) proporcionando una imagen raster <br/>            como parámetro. Este constructor permite a los desarrolladores inicializar directamente un <br/>            objeto de imagen PNG usando una imagen raster existente, agilizando el proceso de <br/>            trabajo con imágenes PNG en sus aplicaciones.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |


**See also:**

**[Example # 1](#example_112)**: This example shows how to load PNG image from a BMP image.


### Constructor: PngImage(raster_image, color_type) {#PngImage_raster_image_color_type_5}


```
 PngImage(raster_image, color_type) 
```

Crea una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) especificando una <br/>            imagen raster y un tipo de color. Este constructor permite a los desarrolladores convertir directamente <br/>            imágenes raster al formato PNG mientras se especifica el tipo de color deseado, <br/>            ofreciendo flexibilidad en la representación de colores.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | El tipo de color. |


**See also:**

**[Example # 1](#example_113)**: This example shows how to load PNG image from a BMP image with the specified ...


### Constructor: PngImage(stream) {#PngImage_stream_6}


```
 PngImage(stream) 
```

Crea una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) inicializándola <br/>            con un flujo. Este constructor permite a los desarrolladores cargar imágenes PNG directamente <br/>            desde un flujo, proporcionando flexibilidad en la obtención de imágenes desde diferentes fuentes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo para cargar una imagen. |


**See also:**

**[Example # 1](#example_111)**: This example shows how to load a PNG image from a file or a file stream.


### Constructor: PngImage(width, height) {#PngImage_width_height_7}


```
 PngImage(width, height) 
```

Inicializa un nuevo objeto de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) proporcionando los parámetros de <br/>            ancho y alto. Este constructor simplifica la creación de imágenes PNG al permitir a los desarrolladores especificar las dimensiones directamente, facilitando <br/>            la gestión eficiente de los datos de imágenes PNG dentro de sus aplicaciones.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho. |
| height | int | La altura. |


**See also:**

**[Example # 1](#example_114)**: This example shows how to create a PNG image of the specified size, fill it w...


### Constructor: PngImage(width, height, color_type) {#PngImage_width_height_color_type_8}


```
 PngImage(width, height, color_type) 
```

Instancia una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) especificando <br/>            los parámetros deseados de ancho, alto y tipo de color. Este constructor permite <br/>            una creación rápida de imágenes PNG con dimensiones y configuraciones de color adaptadas, <br/>            facilitando una generación de imágenes optimizada para diversas aplicaciones y flujos de trabajo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho. |
| height | int | La altura. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | El tipo de color. |


**See also:**

**[Example # 1](#example_115)**: This example shows how to create a PNG image of the specified size with the s...


### Property: has_alpha {#has_alpha1}

Devuelve un valor booleano que indica si la imagen tiene un canal alfa, <br/>            lo que determina su transparencia. Esta propiedad es útil para aplicaciones <br/>            que necesitan manejar la transparencia, permitiendo a los desarrolladores determinar si <br/>            se requiere procesamiento adicional para gestionar áreas transparentes en la imagen.

**See also:**

**[Example # 1](#example_116)**: The following example shows how to check if a PNG image supports alpha-channel.


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


### Method: create_from_file_with_color_type(path, color_type)  [static] {#create_from_file_with_color_type_path_color_type_26}


```
 create_from_file_with_color_type(path, color_type) 
```

Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta para cargar una imagen. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | El tipo de color. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_27}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_28}


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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_29}


```
 create_from_image(raster_image) 
```

Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_from_image_with_color_type(raster_image, color_type)  [static] {#create_from_image_with_color_type_raster_image_color_type_30}


```
 create_from_image_with_color_type(raster_image, color_type) 
```

Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen raster. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | El tipo de color. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_31}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_32}


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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_33}


```
 create_from_stream(stream) 
```

Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo para cargar una imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_with_width_height(width, height)  [static] {#create_with_width_height_width_height_34}


```
 create_with_width_height(width, height) 
```

Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho. |
| height | int | La altura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_with_width_height_color_type(width, height, color_type)  [static] {#create_with_width_height_color_type_width_height_color_type_35}


```
 create_with_width_height_color_type(width, height, color_type) 
```

Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho. |
| height | int | La altura. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | El tipo de color. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_with_width_height_options(png_options, width, height)  [static] {#create_with_width_height_options_png_options_width_height_36}


```
 create_with_width_height_options(png_options, width, height) 
```

Inicializa una nueva instancia de la clase [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | Las opciones de PNG. |
| width | int | El ancho. |
| height | int | La altura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_37}


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

### Method: crop(rectangle) {#crop_rectangle_38}


```
 crop(rectangle) 
```

Recortando la imagen.

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

Aplica dithering a la imagen actual.

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

Incrustar una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | string | La contraseña utilizada para generar datos de firma digital. |

### Method: filter(rectangle, options) {#filter_rectangle_options_42}


```
 filter(rectangle, options) 
```

Filtra el rectángulo especificado.

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

Obtiene la marca de tiempo que indica la modificación más reciente del recurso <br/>            de la imagen. Este método brinda acceso a metadatos vitales, permitiendo a las aplicaciones <br/>            determinar cuándo se modificó por última vez la imagen, facilitando el seguimiento de versiones y <br/>            la gestión de contenido.

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


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_61}


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


### Method: load(file_path)  [static] {#load_file_path_62}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_63}


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


### Method: load(stream)  [static] {#load_stream_64}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_65}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_66}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_67}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_68}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_69}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carga parcialmente píxeles ARGB de 32 bits (por bloques).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar los píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | El cargador parcial de píxeles. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Carga parcialmente píxeles ARGB de 64 bits por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo deseado. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | El cargador de píxeles ARGB de 64 bits. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_72}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carga píxeles parcialmente por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo deseado. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | El cargador de píxeles. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_73}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_76}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_77}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_78}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_79}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo.<br/>            Este método usa los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| resize_proportionally | bool | si se establece a <c>true</c> el tamaño de su imagen se cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en otro caso, se dejan las dimensiones sin cambios y solo se rotan los contenidos internos de la imagen. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color del fondo. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_80}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_81}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_82}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_83}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_84}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_85}


```
 replace_non_transparent_colors(new_color) 
```

Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nuevo color con el que reemplazar los colores no transparentes. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_86}


```
 replace_non_transparent_colors(new_color_argb) 
```

Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_argb | int | Nuevo valor ARGB de color para reemplazar colores no transparentes. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_87}


```
 resize(new_width, new_height) 
```

Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_88}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_89}


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

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_90}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_91}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_92}


```
 resize_height_proportionally(new_height) 
```

Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_93}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_94}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_95}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_96}


```
 resize_width_proportionally(new_width) 
```

Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_97}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_98}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_99}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: rotate(angle) {#rotate_angle_100}


```
 rotate(angle) 
```

Rotar la imagen alrededor del centro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_101}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_102}


```
 rotate_flip(rotate_flip_type) 
```

Rota, voltea o rota y voltea la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | El tipo de volteo de rotación. |

### Method: save(file_path) {#save_file_path_103}


```
 save(file_path) 
```

Guarda la imagen en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar la imagen. |

### Method: save(file_path, options) {#save_file_path_options_104}


```
 save(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_105}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_106}


```
 save(file_path, over_write) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |
| sobrescribir | bool | si se establece en <c>true</c> sobrescribe el contenido del archivo, de lo contrario se añadirá. |

### Method: save(stream) {#save_stream_107}


```
 save(stream) 
```

Los datos guardados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |

### Method: save(stream, options_base) {#save_stream_options_base_108}


```
 save(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_109}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_110}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Guarda los píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | La matriz de píxeles ARGB de 32 bits. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_111}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Guarda los píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_112}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Guarda los píxeles.<br/>            Este método está obsoleto. Por favor, utiliza de forma más eficaz el método [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | La matriz de píxeles CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_113}


```
 save_pixels(rectangle, pixels) 
```

Guarda píxeles (método específico de formato).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | La matriz de píxeles ARGB de 32 bits. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_114}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_115}


```
 save_to_stream(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos del objeto. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_116}


```
 save_to_stream_with_options(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_118}


```
 save_with_options(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_119}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_120}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_121}


```
 set_palette(palette, update_colors) 
```

Establece la paleta de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta a establecer. |
| update_colors | bool | si se establece en <c>true</c> los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas de paleta correspondientes. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_122}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_123}


```
 set_resolution(dpi_x, dpi_y) 
```

Establece la resolución para este [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dpi_x | float | La resolución horizontal, en puntos por pulgada, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La resolución vertical, en puntos por pulgada, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_124}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| argb_32_pixels | int[] | La matriz de colores ARGB de 32 bits para escribir. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_126}


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
### This example shows how to load a PNG image from a file. {#example_109}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image
from aspose.imaging.fileformats.png import PngImage

# Cargar una imagen PNG desde un archivo.
with as_of(Image.load("sample.png"), PngImage) as pngImage:
	# Transformar la imagen a una representación en escala de grises
	pngImage.grayscale()
	# Guarde en un archivo.
	pngImage.save("sample.grayscale.png")


```

### This example shows how to load a PNG image from a file with the specified color type. {#example_110}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.png import PngImage, PngColorType
from os.path import join

dir_ = "c:\\temp"
# Cargar una imagen PNG desde un archivo.
# Tenga en cuenta que la imagen colorida se convertirá a escala de grises automáticamente.
with PngImage(join(dir_, "sample.png"), PngColorType.GRAYSCALE) as png_image:
	# Guarde en un archivo.
	png_image.save(join(dir_, "sample.grayscale.png"))


```

### This example shows how to load a PNG image from a file or a file stream. {#example_111}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.png import PngImage
from os.path import join


dir_: str = "c:\\temp"
# Cargar una imagen PNG desde un flujo de archivo.
with open(join(dir_, "sample.png"), "rb") as stream:
	with PngImage(stream) as png_image:
		# Transformar la imagen a una representación en escala de grises
		png_image.grayscale()
		# Guarde en un archivo.
		png_image.save(join(dir_, "sample.grayscale.png"))


```

### This example shows how to load PNG image from a BMP image. {#example_112}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.fileformats.png import PngImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from os.path import join

dir_: str = "c:\\temp"
# Cargar una imagen PNG TrueColor desde una imagen BMP.
# Primero, cree una imagen BMP temporal que será la base para crear una imagen PNG.
# También puede cargar una imagen BMP desde un archivo o usar una imagen de cualquier otro formato raster.
with BmpImage(100, 100) as bmp_image:
	# Rellene toda la imagen BMP de rojo.
	gr = Graphics(bmp_image)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, bmp_image.bounds)
	with PngImage(bmp_image) as png_image:
		png_image.save(join(dir_, "output.png"))


```

### This example shows how to load PNG image from a BMP image with the specified color type. {#example_113}
``` python

from aspose.imaging import LoadOptions, Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.fileformats.png import PngImage, PngColorType
from os.path import join as path_join


dir_ = "c:\\temp"
# Cargar una imagen PNG en escala de grises desde una imagen BMP a color.
# Primero, cree una imagen BMP temporal que será la base para crear una imagen PNG.
# También puede cargar una imagen BMP desde un archivo o usar una imagen de cualquier otro formato raster.
with BmpImage(100, 100) as bmp_image:
	# Rellene toda la imagen BMP de rojo.
	gr = Graphics(bmp_image)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, bmp_image.bounds)
	# Los colores de los píxeles de la imagen se convertirán a sus equivalentes en escala de grises.
	with PngImage(bmp_image, PngColorType.GRAYSCALE) as png_image:
		png_image.save(path_join(dir_, "output.grayscale.png"))


```

### This example shows how to create a PNG image of the specified size, fill it with a solid color and save it to a file. {#example_114}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.fileformats.png import PngImage
from os.path import join


dir_ = "c:\\temp"
# Cree una imagen PNG de 100x100 px.
with PngImage(100, 100) as png_image:
	# Realice algo de procesamiento de imágenes, p. ej., rellene toda la imagen de rojo.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Guarde en un archivo.
	png_image.save(join(dir_, "output.png"))


```

### This example shows how to create a PNG image of the specified size with the specified color type, fill it with a solid color and save it to a file. {#example_115}
``` python
from aspose.imaging.fileformats.png import PngImage, PngColorType
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from os.path import join

dir_: str = "c:\\temp"
# Crear una imagen PNG en escala de grises de 100x100 px.
# Todos los colores se convertirán automáticamente al formato de escala de grises.
with PngImage(100, 100, PngColorType.GRAYSCALE) as png_image:
	# Realice algo de procesamiento de imágenes, p. ej., rellene toda la imagen de rojo.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Guarde en un archivo.
	png_image.save(join(dir_, "output.grayscale.png"))


```

### The following example shows how to check if a PNG image supports alpha-channel. {#example_116}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.png import PngColorType, PngImage


# Obtener todos los tipos de color PNG compatibles.
color_types = [it for it in PngColorType]
for color_type in color_types:
	create_options = PngOptions()
	create_options.color_type = color_type
	with Image.create(create_options, 100, 100) as image:
		png_image = aspycore.as_of(image, PngImage)
		if png_image.has_alpha:
			print("A {0} PNG image supports alpha channel".format(create_options.color_type))
		else:
			print("A {0} PNG image doesn't support alpha channel".format(create_options.color_type))

# La salida se ve así:
# Una imagen PNG en escala de grises no admite canal alfa
# Una imagen PNG Truecolor no admite canal alfa
# Una imagen PNG IndexedColor no admite canal alfa
# Una imagen PNG GrayscaleWithAlpha admite canal alfa
# Una imagen PNG TruecolorWithAlpha admite canal alfa


```

### The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm. {#example_227}
``` python
from aspose.imaging import Image, Figure, GraphicsPath, RectangleF
from aspose.imaging.shapes import EllipseShape
from aspose.imaging.watermark import WatermarkRemover
from aspose.imaging.watermark.options import ContentAwareFillWatermarkOptions
from aspose.imaging.fileformats.png import PngImage
import aspose.pycore import as_of

image_file_path = "ball.png"; 
with Image.load(image_file_path) as image:
	pngImage = as_of(image, PngImage)
	mask = GraphicsPath()
	firstFigure = Figure()
	firstFigure.add_shape(EllipseShape(RectangleF(350, 170, 570 - 350, 400 - 170)))
	mask.add_figure(firstFigure)

	options = ContentAwareFillWatermarkOptions(mask)
	options.max_painting_attempts = 4
	with WatermarkRemover.paint_over(pngImage, options) as result:
		result.save(outputPath)


```

### The example shows how to remove any object from the image using Graphics Path with Telea algorithm. {#example_228}
``` python
from aspose.imaging import Image, Figure, GraphicsPath, RectangleF
from aspose.imaging.shapes import EllipseShape
from aspose.imaging.watermark import WatermarkRemover
from aspose.imaging.watermark.options import TeleaWatermarkOptions
from aspose.imaging.fileformats.png import PngImage
import aspose.pycore import as_of

image_file_path = "ball.png"; 
with Image.load(image_file_path) as image:
	pngImage = as_of(image, PngImage)
	mask = GraphicsPath()
	firstFigure = Figure()
	firstFigure.add_shape(EllipseShape(RectangleF(350, 170, 570 - 350, 400 - 170)))
	mask.add_figure(firstFigure);
	options = TeleaWatermarkOptions(mask)
	with WatermarkRemover.paint_over(pngImage, options) as result:
		result.save(outputPath)


```

