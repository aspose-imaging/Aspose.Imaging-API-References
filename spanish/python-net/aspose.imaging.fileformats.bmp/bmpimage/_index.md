---
title: "Clase BmpImage"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.fileformats.bmp/bmpimage/
---

**Summary:** You can effortlessly handle Bitmap (BMP) and Device Independent Bitmap<br/>            (DIB) files, facilitating efficient manipulation and processing of raster<br/>            images. Performing various operations on images, this API streamlines the<br/>            workflow, offering developers a reliable toolkit for working with BMP and<br/>            DIB formats in their software applications.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BmpImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [BmpImage(path)](#BmpImage_path_1) | Comienza a usar la clase BmpImage sin esfuerzo con este constructor que<br/>            inicializa una nueva instancia. Perfecto para desarrolladores que desean ponerse en marcha y<br/>            trabajar con objetos [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) rápidamente y de manera eficiente. |
| [BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_2) | Crea sin esfuerzo una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) con este constructor,<br/>            usando parámetros especificados como ruta, bitsPerPixel y compresión. Ideal para desarrolladores<br/>            que buscan inicializar objetos BmpImage rápida y eficientemente, con control preciso<br/>            sobre las características de la imagen. |
| [BmpImage(raster_image)](#BmpImage_raster_image_3) | Crear sin esfuerzo una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) <br/>            inicializándola con un objeto RasterImage. Perfecto para desarrolladores que buscan convertir sin problemas imágenes raster existentes al formato BmpImage, garantizando<br/>            compatibilidad y facilidad de integración en sus proyectos. |
| [BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_4) | Comienza a trabajar con la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) de forma fluida creando una nueva instancia<br/>            usando un rasterImage junto con parámetros especificados como bitsPerPixel y compresión.<br/>            Perfecto para desarrolladores que buscan una manera directa de manejar objetos BmpImage,<br/>            garantizando flexibilidad y eficiencia en sus proyectos. |
| [BmpImage(stream)](#BmpImage_stream_5) | Comienza a usar la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sin esfuerzo inicializando una nueva instancia<br/>            con este constructor, usando un flujo como entrada. Perfecto para desarrolladores que buscan<br/>            una forma conveniente de trabajar con objetos BmpImage desde diversas fuentes de datos,<br/>            garantizando flexibilidad y facilidad de integración. |
| [BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_6) | Comienza a trabajar con la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) de forma fluida creando<br/>            una nueva instancia usando un flujo, junto con parámetros especificados como bitsPerPixel<br/>            y compresión. Perfecto para desarrolladores que buscan una manera directa de manejar<br/>            objetos BmpImage, garantizando flexibilidad y eficiencia en sus proyectos. |
| [BmpImage(width, height)](#BmpImage_width_height_7) | Comienza a usar la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sin esfuerzo creando una nueva instancia<br/>            con parámetros de ancho y alto especificados. Ideal para desarrolladores que buscan<br/>            una forma conveniente de generar objetos BmpImage con dimensiones personalizadas, garantizando<br/>            flexibilidad y facilidad de integración en sus proyectos. |
| [BmpImage(width, height, bits_per_pixel, palette)](#BmpImage_width_height_bits_per_pixel_palette_8) | Comienza a usar la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) de forma fluida inicializando una nueva instancia<br/>            con parámetros como ancho, alto, profundidad de bits y paleta. Perfecto para<br/>            desarrolladores que buscan una manera directa de crear objetos BmpImage con<br/>            dimensiones personalizadas y configuraciones de color, garantizando flexibilidad y eficiencia en sus proyectos. |
| [BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution)](#BmpImage_width_height_bits_per_pixel_palette_compression_horizontal_resolution_vertical_resolution_9) | Crea sin esfuerzo una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) con este constructor,<br/>            especificando parámetros como ancho, alto, bitsPerPixel y paleta. Perfecto para desarrolladores<br/>            que buscan una forma conveniente de generar objetos BmpImage con dimensiones personalizadas<br/>            y configuraciones de color, garantizando flexibilidad y facilidad de integración en sus proyectos. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Obtiene o establece un valor que indica si se ajusta automáticamente la paleta. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece un valor para el color de fondo. |
| [bitmap_info_header](#bitmap_info_header1) | [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | r | Accede rápidamente a los detalles esenciales de tu imagen bitmap con esta función directa.<br/>            Perfecto para desarrolladores que necesitan obtener información del encabezado de sus imágenes. |
| [bits_per_pixel](#bits_per_pixel2) | int | r | Accede fácilmente al número de bits por píxel de la imagen usando esta propiedad.<br/>            Perfecto para desarrolladores que buscan información rápida sobre la calidad y profundidad de la imagen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtiene los límites del objeto. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| [compression](#compression3) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r | Recupere el tipo de compresión usado para la imagen sin esfuerzo con esta propiedad.<br/>            Perfecto para desarrolladores que necesitan acceder rápidamente a información sobre la compresión de imágenes. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtiene el contenedor [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Obtiene el flujo de datos del objeto. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece la instancia Exif. |
| [file_format](#file_format4) | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Recupere fácilmente el valor del formato de archivo con esta propiedad fácil de usar.<br/>            Ideal para desarrolladores que buscan acceso rápido a información sobre el formato de archivo. |
| has_alpha | bool | r | Obtiene un valor que indica si esta instancia tiene alfa. |
| has_background_color | bool | r/w | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| has_transparent_color | bool | r/w | Obtiene o establece un valor que indica si esta instancia de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) tiene un color transparente. |
| [height](#height5) | int | r | Recupere la altura de la imagen sin esfuerzo con esta propiedad. Ideal para desarrolladores<br/>            que necesitan acceso rápido a información sobre las dimensiones de la imagen. |
| [horizontal_resolution](#horizontal_resolution6) | float | r/w | Esta propiedad le permite obtener o establecer fácilmente la resolución horizontal,<br/>            medida en píxeles por pulgada, del objeto [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). Ideal para<br/>            desarrolladores que necesitan un control preciso sobre la resolución de la imagen para sus aplicaciones. |
| image_opacity | float | r | Obtiene la opacidad de esta imagen. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtiene o establece el monitor de interrupciones. |
| is_cached | bool | r | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| is_raw_data_available | bool | r | Obtiene un valor que indica si se admite la carga de datos sin procesar. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtiene los metadatos de la imagen. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. La paleta de colores no se usa cuando los píxeles se representan directamente. |
| premultiply_components | bool | r/w | Obtiene o establece un valor que indica si los componentes de la imagen deben ser premultiplicados. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Obtiene o establece el convertidor de color personalizado |
| [raw_data_format](#raw_data_format7) | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtenga fácilmente el formato de sus datos sin procesar con esta función fácil de usar.<br/>            Perfecto para desarrolladores que desean acceder rápidamente a información crucial sobre el formato de sus datos. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración, los datos se cargan sin conversión. |
| raw_fallback_index | int | r/w | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Obtiene o establece el convertidor de color indexado |
| [raw_line_size](#raw_line_size8) | int | r | Acceda rápidamente al tamaño de cada línea sin procesar en bytes con esta propiedad directa.<br/>            Ideal para desarrolladores que necesitan manejar eficientemente datos de imagen sin procesar. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtiene el tamaño del objeto. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene el color transparente de la imagen. |
| update_xmp_data | bool | r/w | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| use_palette | bool | r | Obtiene un valor que indica si se usa la paleta de la imagen. |
| use_raw_data | bool | r/w | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| [vertical_resolution](#vertical_resolution9) | float | r/w | Recupere o establezca fácilmente la resolución vertical, medida en píxeles por pulgada,<br/>            de este objeto [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) con esta propiedad. Perfecto para desarrolladores que requieren<br/>            un control preciso sobre la resolución de la imagen en sus aplicaciones. |
| [width](#width10) | int | r | Acceda al ancho de la imagen fácilmente con esta propiedad. Ideal para desarrolladores<br/>            que buscan información rápida sobre las dimensiones de la imagen. |
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
| [create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_file_with_params_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_26) | Comience a usar la clase BmpImage fácilmente con este constructor, simplificando<br/>            el proceso de inicializar una nueva instancia. Ideal para desarrolladores que buscan<br/>            una forma rápida y eficiente de incorporar objetos [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) en sus proyectos. |
| [create_from_files(files)](#create_from_files_files_27) | Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_28) | Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida. |
| [create_from_image(raster_image)](#create_from_image_raster_image_29) | Inicializa una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_image_with_params_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_30) | Inicializa una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [create_from_images(images)](#create_from_images_images_31) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [create_from_stream(stream)](#create_from_stream_stream_33) | Inicializa una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_stream_with_params_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_34) | Inicializa una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_35) | Recortar la imagen con desplazamientos. |
| [crop(rectangle)](#crop_rectangle_36) | Recortando la imagen. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_37) | Aplica dithering a la imagen actual. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_38) | Aplica dithering a la imagen actual. |
| [embed_digital_signature(password)](#embed_digital_signature_password_39) | Incrustar una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía. |
| [filter(rectangle, options)](#filter_rectangle_options_40) | Filtra el rectángulo especificado. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_41) | Obtiene un píxel ARGB de 32 bits de la imagen. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_42) | Obtiene la matriz predeterminada de píxeles ARGB de 32 bits. |
| [get_default_options(args)](#get_default_options_args_43) | Recupere las opciones predeterminadas sin esfuerzo con este método directo.<br/>            Ideal para desarrolladores que buscan acceso rápido a la configuración o configuraciones predeterminadas de la imagen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_44) | Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45) | Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_46) | Obtiene la matriz de datos sin procesar predeterminada. |
| [get_file_format(file_path)](#get_file_format_file_path_47) | Obtiene el formato de archivo. |
| [get_file_format(stream)](#get_file_format_stream_48) | Obtiene el formato de archivo. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_49) | Obtiene el formato de archivo. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_50) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_51) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_modify_date(use_default)](#get_modify_date_use_default_52) | Obtiene la fecha y hora en que la imagen del recurso fue modificada por última vez. |
| [get_original_options()](#get_original_options__53) | Obtiene las opciones basadas en la configuración original del archivo.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            método [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al método [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) como segundo parámetro. |
| [get_pixel(x, y)](#get_pixel_x_y_54) | Obtiene un píxel de la imagen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_55) | Obtiene una altura proporcional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_56) | Obtiene un ancho proporcional. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_57) | Convierte a aps. |
| [get_skew_angle()](#get_skew_angle__58) | Obtiene el ángulo de sesgo.<br/>            Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear. |
| grayscale() | Transformación de una imagen a su representación en escala de grises |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_59) | Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral. |
| [load(file_path)](#load_file_path_60) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(file_path, load_options)](#load_file_path_load_options_61) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(stream)](#load_stream_62) | Carga una nueva imagen desde el flujo especificado. |
| [load(stream, load_options)](#load_stream_load_options_63) | Carga una nueva imagen desde el flujo especificado. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_64) | Carga píxeles ARGB de 32 bits. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_65) | Carga píxeles ARGB de 64 bits. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_66) | Carga píxeles en formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_67) | Carga píxeles en formato CMYK.<br/>            Este método está obsoleto. Por favor, use de manera más eficaz el método [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_68) | Carga parcialmente píxeles ARGB de 32 bits (por bloques). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_69) | Carga parcialmente píxeles ARGB de 64 bits por paquetes. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_70) | Carga píxeles parcialmente por paquetes. |
| [load_pixels(rectangle)](#load_pixels_rectangle_71) | Carga píxeles. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_72) | Carga datos sin procesar. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_73) | Carga datos sin procesar. |
| [load_stream(stream)](#load_stream_stream_74) | Carga una nueva imagen desde el flujo especificado. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_75) | Carga una nueva imagen desde el flujo especificado. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_76) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| normalize_angle() | Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la distorsión del escaneo.<br/>            Este método utiliza los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_77) | Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo.<br/>            Este método usa los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | Normaliza el histograma de la imagen — ajusta los valores de píxeles para usar todo el rango disponible. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_78) | Lee toda la línea de escaneo según el índice de línea de escaneo especificado. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_79) | Lee toda la línea de escaneo según el índice de línea de escaneo especificado. |
| remove_metadata() | Elimina los metadatos de esta instancia de imagen estableciendo el valor de [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) a **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_80) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_81) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_82) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_83) | Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_84) | Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [resize(new_width, new_height)](#resize_new_width_new_height_85) | Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_86) | Redimensiona la imagen. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_87) | Redimensiona la imagen. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_88) | Redimensiona la imagen. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_89) | Redimensiona la imagen. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_90) | Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_91) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_92) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_93) | Redimensiona la altura proporcionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_94) | Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_95) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_96) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_97) | Redimensiona el ancho proporcionalmente. |
| [rotate(angle)](#rotate_angle_98) | Rotar la imagen alrededor del centro. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_99) | Rotar la imagen alrededor del centro. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_100) | Rota, voltea o rota y voltea la imagen. |
| save() | Guarda los datos de la imagen en el flujo subyacente. |
| [save(file_path)](#save_file_path_101) | Guarda la imagen en la ubicación de archivo especificada. |
| [save(file_path, options)](#save_file_path_options_102) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_103) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, over_write)](#save_file_path_over_write_104) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(stream)](#save_stream_105) | Guarda los datos del objeto en el flujo especificado. |
| [save(stream, options_base)](#save_stream_options_base_106) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_107) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_108) | Guarda los píxeles ARGB de 32 bits. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_109) | Guarda los píxeles. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_110) | Guarda los píxeles.<br/>            Este método está obsoleto. Por favor, utiliza de forma más eficaz el método [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_111) | Guarda píxeles (método específico de formato). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_112) | Guarda los datos sin procesar. |
| [save_to_stream(stream)](#save_to_stream_stream_113) | Guarda los datos del objeto en el flujo especificado. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_114) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_115) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_116) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_117) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_118) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_119) | Establece la paleta de la imagen. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_120) | Establece un píxel de la imagen para la posición especificada. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_121) | Ajuste la resolución de su [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) sin esfuerzo con este<br/>            método fácil de usar. Perfecto para desarrolladores que buscan un control preciso sobre<br/>            la resolución de la imagen en sus aplicaciones. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_122) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_123) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_124) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |


### Constructor: BmpImage(path) {#BmpImage_path_1}


```
 BmpImage(path) 
```

Comienza a usar la clase BmpImage sin esfuerzo con este constructor que<br/>            inicializa una nueva instancia. Perfecto para desarrolladores que desean ponerse en marcha y<br/>            trabajar con objetos [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) rápidamente y de manera eficiente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta desde la cual cargar la imagen e inicializar los datos de píxeles y paleta. |


**See also:**

**[Example # 1](#example_77)**: The example shows how to load a BmpImage from a file.


### Constructor: BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_2}


```
 BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Crea sin esfuerzo una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) con este constructor,<br/>            usando parámetros especificados como ruta, bitsPerPixel y compresión. Ideal para desarrolladores<br/>            que buscan inicializar objetos BmpImage rápida y eficientemente, con control preciso<br/>            sobre las características de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta desde la cual cargar la imagen e inicializar los datos de píxeles y paleta. |
| bits_per_pixel | int | Los bits por píxel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | La compresión a usar. |
| horizontal_resolution | float | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| vertical_resolution | float | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |


**See also:**

**[Example # 1](#example_78)**: The example shows how to load a BmpImage from a file with the specified bit d...


### Constructor: BmpImage(raster_image) {#BmpImage_raster_image_3}


```
 BmpImage(raster_image) 
```

Crear sin esfuerzo una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) <br/>            inicializándola con un objeto RasterImage. Perfecto para desarrolladores que buscan convertir sin problemas imágenes raster existentes al formato BmpImage, garantizando<br/>            compatibilidad y facilidad de integración en sus proyectos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen con la que inicializar los datos de píxeles y paleta. |


**See also:**

**[Example # 1](#example_81)**: The example shows how to load a BmpImage from another instance of RasterImage.


### Constructor: BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_4}


```
 BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Comienza a trabajar con la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) de forma fluida creando una nueva instancia<br/>            usando un rasterImage junto con parámetros especificados como bitsPerPixel y compresión.<br/>            Perfecto para desarrolladores que buscan una manera directa de manejar objetos BmpImage,<br/>            garantizando flexibilidad y eficiencia en sus proyectos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen con la que inicializar los datos de píxeles y paleta. |
| bits_per_pixel | int | Los bits por píxel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | La compresión a usar. |
| horizontal_resolution | float | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| vertical_resolution | float | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |


**See also:**

**[Example # 1](#example_82)**: The example shows how to load a BmpImage from another instance of RasterImage...


### Constructor: BmpImage(stream) {#BmpImage_stream_5}


```
 BmpImage(stream) 
```

Comienza a usar la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sin esfuerzo inicializando una nueva instancia<br/>            con este constructor, usando un flujo como entrada. Perfecto para desarrolladores que buscan<br/>            una forma conveniente de trabajar con objetos BmpImage desde diversas fuentes de datos,<br/>            garantizando flexibilidad y facilidad de integración.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |


**See also:**

**[Example # 1](#example_79)**: The example shows how to load a BmpImage from a file stream.


### Constructor: BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_6}


```
 BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Comienza a trabajar con la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) de forma fluida creando<br/>            una nueva instancia usando un flujo, junto con parámetros especificados como bitsPerPixel<br/>            y compresión. Perfecto para desarrolladores que buscan una manera directa de manejar<br/>            objetos BmpImage, garantizando flexibilidad y eficiencia en sus proyectos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |
| bits_per_pixel | int | Los bits por píxel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | La compresión a usar. |
| horizontal_resolution | float | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| vertical_resolution | float | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |


**See also:**

**[Example # 1](#example_80)**: The example shows how to load a BmpImage from a file stream with the specifie...


### Constructor: BmpImage(width, height) {#BmpImage_width_height_7}


```
 BmpImage(width, height) 
```

Comienza a usar la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sin esfuerzo creando una nueva instancia<br/>            con parámetros de ancho y alto especificados. Ideal para desarrolladores que buscan<br/>            una forma conveniente de generar objetos BmpImage con dimensiones personalizadas, garantizando<br/>            flexibilidad y facilidad de integración en sus proyectos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho de la imagen. |
| height | int | El alto de la imagen. |


**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_83)**: The example shows how to create a BmpImage of the specified size.


### Constructor: BmpImage(width, height, bits_per_pixel, palette) {#BmpImage_width_height_bits_per_pixel_palette_8}


```
 BmpImage(width, height, bits_per_pixel, palette) 
```

Comienza a usar la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) de forma fluida inicializando una nueva instancia<br/>            con parámetros como ancho, alto, profundidad de bits y paleta. Perfecto para<br/>            desarrolladores que buscan una manera directa de crear objetos BmpImage con<br/>            dimensiones personalizadas y configuraciones de color, garantizando flexibilidad y eficiencia en sus proyectos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho de la imagen. |
| height | int | El alto de la imagen. |
| bits_per_pixel | int | Los bits por píxel. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores. |


**See also:**

**[Example # 1](#example_84)**: The example shows how to create a BmpImage of the specified size with the spe...


### Constructor: BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution) {#BmpImage_width_height_bits_per_pixel_palette_compression_horizontal_resolution_vertical_resolution_9}


```
 BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution) 
```

Crea sin esfuerzo una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) con este constructor,<br/>            especificando parámetros como ancho, alto, bitsPerPixel y paleta. Perfecto para desarrolladores<br/>            que buscan una forma conveniente de generar objetos BmpImage con dimensiones personalizadas<br/>            y configuraciones de color, garantizando flexibilidad y facilidad de integración en sus proyectos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho de la imagen. |
| height | int | El alto de la imagen. |
| bits_per_pixel | int | Los bits por píxel. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta de colores. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | La compresión a usar. |
| horizontal_resolution | float | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| vertical_resolution | float | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |


**See also:**

**[Example # 1](#example_85)**: The example shows how to create a BmpImage using various options.


### Property: bitmap_info_header {#bitmap_info_header1}

Accede rápidamente a los detalles esenciales de tu imagen bitmap con esta función directa.<br/>            Perfecto para desarrolladores que necesitan obtener información del encabezado de sus imágenes.

**See also:**

**[Example # 1](#example_89)**: The following example gets the information from the BMP header and prints it ...


### Property: bits_per_pixel {#bits_per_pixel2}

Accede fácilmente al número de bits por píxel de la imagen usando esta propiedad.<br/>            Perfecto para desarrolladores que buscan información rápida sobre la calidad y profundidad de la imagen.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: compression {#compression3}

Recupere el tipo de compresión usado para la imagen sin esfuerzo con esta propiedad.<br/>            Perfecto para desarrolladores que necesitan acceder rápidamente a información sobre la compresión de imágenes.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: file_format {#file_format4}

Recupere fácilmente el valor del formato de archivo con esta propiedad fácil de usar.<br/>            Ideal para desarrolladores que buscan acceso rápido a información sobre el formato de archivo.

**See also:**

**[Example # 1](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: height {#height5}

Recupere la altura de la imagen sin esfuerzo con esta propiedad. Ideal para desarrolladores<br/>            que necesitan acceso rápido a información sobre las dimensiones de la imagen.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: horizontal_resolution {#horizontal_resolution6}

Esta propiedad le permite obtener o establecer fácilmente la resolución horizontal,<br/>            medida en píxeles por pulgada, del objeto [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). Ideal para<br/>            desarrolladores que necesitan un control preciso sobre la resolución de la imagen para sus aplicaciones.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Property: raw_data_format {#raw_data_format7}

Obtenga fácilmente el formato de sus datos sin procesar con esta función fácil de usar.<br/>            Perfecto para desarrolladores que desean acceder rápidamente a información crucial sobre el formato de sus datos.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: raw_line_size {#raw_line_size8}

Acceda rápidamente al tamaño de cada línea sin procesar en bytes con esta propiedad directa.<br/>            Ideal para desarrolladores que necesitan manejar eficientemente datos de imagen sin procesar.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: vertical_resolution {#vertical_resolution9}

Recupere o establezca fácilmente la resolución vertical, medida en píxeles por pulgada,<br/>            de este objeto [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) con esta propiedad. Perfecto para desarrolladores que requieren<br/>            un control preciso sobre la resolución de la imagen en sus aplicaciones.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Property: width {#width10}

Acceda al ancho de la imagen fácilmente con esta propiedad. Ideal para desarrolladores<br/>            que buscan información rápida sobre las dimensiones de la imagen.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


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


### Method: create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_file_with_params_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_26}


```
 create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Comience a usar la clase BmpImage fácilmente con este constructor, simplificando<br/>            el proceso de inicializar una nueva instancia. Ideal para desarrolladores que buscan<br/>            una forma rápida y eficiente de incorporar objetos [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) en sus proyectos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ruta | string | La ruta desde la cual cargar la imagen e inicializar los datos de píxeles y paleta. |
| bits_per_pixel | int | Los bits por píxel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | La compresión a usar. |
| horizontal_resolution | float | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| vertical_resolution | float | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


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

Inicializa una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen con la que inicializar los datos de píxeles y paleta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_image_with_params_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_30}


```
 create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Inicializa una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La imagen con la que inicializar los datos de píxeles y paleta. |
| bits_per_pixel | int | Los bits por píxel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | La compresión a usar. |
| horizontal_resolution | float | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| vertical_resolution | float | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


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

Inicializa una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_stream_with_params_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_34}


```
 create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Inicializa una nueva instancia de la clase [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |
| bits_per_pixel | int | Los bits por píxel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | La compresión a usar. |
| horizontal_resolution | float | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| vertical_resolution | float | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_35}


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

### Method: crop(rectangle) {#crop_rectangle_36}


```
 crop(rectangle) 
```

Recortando la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_37}


```
 dither(dithering_method, bits_count) 
```

Aplica dithering a la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | El método de tramado. |
| bits_count | int | El recuento final de bits para el tramado. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_38}


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

### Method: embed_digital_signature(password) {#embed_digital_signature_password_39}


```
 embed_digital_signature(password) 
```

Incrustar una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | string | La contraseña utilizada para generar datos de firma digital. |

### Method: filter(rectangle, options) {#filter_rectangle_options_40}


```
 filter(rectangle, options) 
```

Filtra el rectángulo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Las opciones. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_41}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_42}


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


### Method: get_default_options(args) {#get_default_options_args_43}


```
 get_default_options(args) 
```

Recupere las opciones predeterminadas sin esfuerzo con este método directo.<br/>            Ideal para desarrolladores que buscan acceso rápido a la configuración o configuraciones predeterminadas de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| args | System.Object | Los argumentos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Opciones predeterminadas |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_44}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo del cual obtener píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | El cargador parcial de píxeles. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_46}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_47}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_48}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_49}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_50}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_51}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_52}


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


### Method: get_original_options() {#get_original_options__53}


```
 get_original_options() 
```

Obtiene las opciones basadas en la configuración original del archivo.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            método [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al método [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) como segundo parámetro.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones basadas en la configuración original del archivo. |


### Method: get_pixel(x, y) {#get_pixel_x_y_54}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_55}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_56}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_57}


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


### Method: get_skew_angle() {#get_skew_angle__58}


```
 get_skew_angle() 
```

Obtiene el ángulo de sesgo.<br/>            Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear.

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | El ángulo de sesgo, en grados. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_59}


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


### Method: load(file_path)  [static] {#load_file_path_60}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_61}


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


### Method: load(stream)  [static] {#load_stream_62}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_63}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_64}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_65}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_66}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_67}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_68}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carga parcialmente píxeles ARGB de 32 bits (por bloques).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar los píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | El cargador parcial de píxeles. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_69}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Carga parcialmente píxeles ARGB de 64 bits por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo deseado. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | El cargador de píxeles ARGB de 64 bits. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_70}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carga píxeles parcialmente por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo deseado. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | El cargador de píxeles. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_71}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_72}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_73}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_74}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_75}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_76}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_77}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo.<br/>            Este método usa los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| resize_proportionally | bool | si se establece a <c>true</c> el tamaño de su imagen se cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en otro caso, se dejan las dimensiones sin cambios y solo se rotan los contenidos internos de la imagen. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color del fondo. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_78}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_79}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_80}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_81}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_82}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_83}


```
 replace_non_transparent_colors(new_color) 
```

Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nuevo color con el que reemplazar los colores no transparentes. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_84}


```
 replace_non_transparent_colors(new_color_argb) 
```

Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_argb | int | Nuevo valor ARGB de color para reemplazar colores no transparentes. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_85}


```
 resize(new_width, new_height) 
```

Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_86}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_87}


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

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_88}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_89}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_90}


```
 resize_height_proportionally(new_height) 
```

Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_91}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_92}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_93}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_94}


```
 resize_width_proportionally(new_width) 
```

Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_95}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_96}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_97}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: rotate(angle) {#rotate_angle_98}


```
 rotate(angle) 
```

Rotar la imagen alrededor del centro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_99}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_100}


```
 rotate_flip(rotate_flip_type) 
```

Rota, voltea o rota y voltea la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | El tipo de volteo de rotación. |

### Method: save(file_path) {#save_file_path_101}


```
 save(file_path) 
```

Guarda la imagen en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar la imagen. |

### Method: save(file_path, options) {#save_file_path_options_102}


```
 save(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_103}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_104}


```
 save(file_path, over_write) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |
| sobrescribir | bool | si se establece en <c>true</c> sobrescribe el contenido del archivo, de lo contrario se añadirá. |

### Method: save(stream) {#save_stream_105}


```
 save(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos del objeto. |

### Method: save(stream, options_base) {#save_stream_options_base_106}


```
 save(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_107}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_108}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Guarda los píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | La matriz de píxeles ARGB de 32 bits. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_109}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Guarda los píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_110}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Guarda los píxeles.<br/>            Este método está obsoleto. Por favor, utiliza de forma más eficaz el método [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | La matriz de píxeles CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_111}


```
 save_pixels(rectangle, pixels) 
```

Guarda píxeles (método específico de formato).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | La matriz de píxeles ARGB de 32 bits. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_112}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_113}


```
 save_to_stream(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos del objeto. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_114}


```
 save_to_stream_with_options(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_115}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_116}


```
 save_with_options(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_117}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_118}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_119}


```
 set_palette(palette, update_colors) 
```

Establece la paleta de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta a establecer. |
| update_colors | bool | si se establece en <c>true</c> los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas de paleta correspondientes. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_120}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_121}


```
 set_resolution(dpi_x, dpi_y) 
```

Ajuste la resolución de su [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) sin esfuerzo con este<br/>            método fácil de usar. Perfecto para desarrolladores que buscan un control preciso sobre<br/>            la resolución de la imagen en sus aplicaciones.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dpi_x | float | La resolución horizontal, en puntos por pulgada, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La resolución vertical, en puntos por pulgada, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |


**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_122}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_123}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| argb_32_pixels | int[] | La matriz de colores ARGB de 32 bits para escribir. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_124}


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
### The following example shows how to create a BMP image of the specified size. {#example_18}
``` python
from aspose.imaging import Color
from aspose.imaging.fileformats.bmp import BmpImage
from os.path import join as path_join

directory = "c:\\temp\\"

# Crea una imagen BMP de 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# Rellene la imagen con un simple degradado lineal rojo-negro.
	width = bmpImage.width
	height = bmpImage.height
	for y in range(height):
		for x in range(width):
			hue = (255 * x) // width
			bmpImage.set_pixel(x, y, Color.from_argb(255, hue, 0, 0))

	with open(path_join(directory, "output.bmp"), "w+b") as stream:
		bmpImage.save(stream)


```

### The following example gets the general information about the image including pixel format, image size, resolution, compression etc. {#example_19}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BmpImage
from os.path import join as path_join


with Image.load(r"c:\temp\sample.bmp") as image:
	bmpImage = as_of(image, BmpImage)    

	print("The pixel format:", bmpImage.raw_data_format)
	print("The raw line size in bytes:", bmpImage.raw_line_size)
	print("The bitmap compression:", bmpImage.compression)
	print("The bitmap width", bmpImage.width)
	print("The bitmap height", bmpImage.height)
	print("The number of bits per pixel", bmpImage.bits_per_pixel)

	hres = bmpImage.horizontal_resolution
	vres = bmpImage.vertical_resolution
	print("The horizontal resolution, in pixels per inch:", hres)
	print("The vertical resolution, in pixels per inch:", vres)

	if hres != 96.0 or vres != 96.0:
		# Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
		print("Set resolution values to 96 dpi")
		bmpImage.set_resolution(96.0, 96.0)
		print("The horizontal resolution, in pixels per inch: {0}", bmpImage.horizontal_resolution);
		print("The vertical resolution, in pixels per inch: {0}", bmpImage.vertical_resolution);

	#La salida puede verse así:
	#El formato de píxel: Rgb24Bpp, canales usados: 8,8,8
	#El tamaño de la línea sin procesar en bytes: 1500
	#La compresión del mapa de bits: Rgb
	#El ancho del mapa de bits: 500
	#La altura del mapa de bits: 375
	#El número de bits por píxel: 24
	#La resolución horizontal, en píxeles por pulgada: 0
	#La resolución vertical, en píxeles por pulgada: 0
	#Establecer valores de resolución a 96 dpi
	#La resolución horizontal, en píxeles por pulgada: 96.012
	#La resolución vertical, en píxeles por pulgada: 96.012


```

### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Crea una imagen BMP de 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# El degradado lineal desde la esquina superior izquierda hasta la esquina inferior derecha de la imagen.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Rellena toda la imagen con el pincel de degradado lineal.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Obtén la paleta de colores de 8 bits más cercana que cubra la mayor cantidad posible de píxeles, de modo que una imagen paletizada
	# sea casi indistinguible visualmente de un bmp sin paleta
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# Una paleta de 8 bits contiene como máximo 256 colores.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# La salida se ve así:
# El tamaño de la imagen con paleta es de 11078 bytes.
# El tamaño de la imagen sin paleta es de 40054 bytes.

```

### The example shows how to load a BmpImage from a file. {#example_77}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
import os

directory = r"c:\temp"

# Cargar una imagen BMP desde un archivo.
# Los píxeles de origen se convertirán al formato de 32 bpp si es necesario.
with BmpImage(os.path.join(directory, "sample.bmp")) as bmp_image:
	# Realizar algún procesamiento de imagen.
	# Guardar en otro archivo BMP.
	bmp_image.save(os.path.join(directory, "sample.output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from a file with the specified bit depth and resolution. {#example_78}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
import os

directory = r"c:\temp"

# Cargar una imagen BMP desde un archivo.
# Los píxeles de origen se convertirán al formato de 24 bpp si es necesario.
# La resolución se establecerá en 96 dpi.
with BmpImage(os.path.join(directory, "sample.bmp"), 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
	# Realizar algún procesamiento de imagen.
	# Guardar en otro archivo BMP.
	bmp_image.save(os.path.join(directory, "sample.output.24bpp.96dpi.bmp"))


```

### The example shows how to load a BmpImage from a file stream. {#example_79}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
import os

directory = r"c:\temp"

# Cargar una imagen BMP desde un flujo de archivo.
# Los píxeles de origen se convertirán al formato de 32 bpp si es necesario.
with open(os.path.join(directory, "sample.bmp"), "rb+") as stream:
	with BmpImage(stream) as bmp_image:
		# Realizar algún procesamiento de imagen.
		# Guardar en otro archivo BMP.
		bmp_image.save(os.path.join(directory, "sample.output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from a file stream with the specified bit depth and resolution. {#example_80}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
import os

directory = r"c:\temp"

# Cargar una imagen BMP desde un flujo de archivo.
# Los píxeles de origen se convertirán al formato de 24 bpp si es necesario.
# La resolución se establecerá en 96 dpi.
with open(os.path.join(directory, "sample.bmp"), "rb") as stream:
	with BmpImage(stream, 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
		# Realizar algún procesamiento de imagen.
		# Guardar en otro archivo BMP.
		bmp_image.save(os.path.join(directory, "sample.output.24bpp.96dpi.bmp"))

```

### The example shows how to load a BmpImage from another instance of RasterImage. {#example_81}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.sources import StreamSource
from aspose.imaging import Image, RasterImage, Graphics, Color
from aspose.imaging.brushes import SolidBrush
import os
import aspose.pycore as aspycore

directory = r"c:\temp"

# Crear una nueva imagen PNG.
with PngOptions() as create_options:
	create_options.source = StreamSource()
	with aspycore.as_of(Image.create(create_options, 100, 100), RasterImage) as raster_image:
		# Rellena toda la imagen PNG de rojo.
		gr = Graphics(raster_image)
		brush = SolidBrush(Color.red)
		gr.fill_rectangle(brush, raster_image.bounds)

		# Crear una imagen BMP basada en la imagen PNG.
		# Los píxeles de origen se convertirán al formato de 32 bpp si es necesario.
		with BmpImage(raster_image) as bmp_image:
			# Guardar en un archivo BMP
			bmp_image.save(os.path.join(directory, "output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from another instance of RasterImage with the specified bit depth and compression. {#example_82}
``` python

from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.sources import StreamSource
from aspose.imaging import Image, RasterImage, Graphics, Color
from aspose.imaging.brushes import SolidBrush
import os
import aspose.pycore as aspycore

directory = r"c:\temp"

# Crear una nueva imagen PNG.
with PngOptions() as create_options:
	create_options.source = StreamSource()
	with aspycore.as_of(Image.create(create_options, 100, 100), RasterImage) as raster_image:
		# Rellena toda la imagen PNG de rojo.
		gr = Graphics(raster_image)
		brush = SolidBrush(Color.red)
		gr.fill_rectangle(brush, raster_image.bounds)

		# Crear una imagen BMP basada en la imagen PNG.
		# Los píxeles de origen se convertirán al formato de 24 bpp si es necesario.
		# La resolución se establecerá en 96 dpi.
		with BmpImage(raster_image, 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
			# Guardar en un archivo BMP
			bmp_image.save(os.path.join(directory, "output.24bpp.96dpi.bmp"))

```

### The example shows how to create a BmpImage of the specified size. {#example_83}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
import os

directory = r"c:\temp"

# Crear una imagen BMP de 32 bpp de 100 x 100 px.
with BmpImage(100, 100) as bmp_image:
	# Rellene toda la imagen de rojo.
	Graphics gr = Graphics(bmp_image)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, bmp_image.bounds)
	# Guardar en un archivo BMP
	bmp_image.save(os.path.join(directory, "output.bmp"))


```

### The example shows how to create a BmpImage of the specified size with the specified palette. {#example_84}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging import Graphics, Color, ColorPalette, Rectangle
from aspose.imaging.brushes import SolidBrush
import os

directory = r"c:\temp"

paletterColors = [Color.red, Color.green]

# Crear una paleta monocromática que contenga solo colores rojo y verde.
palette = ColorPalette.create_with_colors(paletterColors)

# Crear una imagen BMP monocromática de 1 bpp de 100 x 100 px.
with BmpImage(100, 100, 1, palette) as bmp_image:
	gr = Graphics(bmp_image)

	# Rellenar la mitad superior de la imagen en rojo.
	redBrush = SolidBrush(Color.red)
	gr.fill_rectangle(redBrush, Rectangle(0, 0, bmp_image.width, bmp_image.height // 2))

	# Rellenar la mitad inferior de la imagen en verde.
	greenBrush = SolidBrush(Color.green)
	gr.fill_rectangle(greenBrush, Rectangle(0, bmp_image.height // 2, bmp_image.width, bmp_image.height // 2))

	# Guardar en BMP
	bmp_image.save(os.path.join(directory, "output.monochrome.bmp"))


```

### The example shows how to create a BmpImage using various options. {#example_85}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
from aspose.imaging import Graphics, Color, ColorPalette, Rectangle
from aspose.imaging.brushes import SolidBrush
import os

directory = r"c:\temp"

paletterColors = [Color.red, Color.green]

# Crear una paleta monocromática que contenga solo colores rojo y verde.
palette = ColorPalette.create_with_colors(paletterColors)

# Crear una imagen BMP monocromática de 1 bpp de 100 x 100 px.
with BmpImage(100, 100, 1, palette, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
	gr = Graphics(bmp_image)

	# Rellenar la mitad superior de la imagen en rojo.
	redBrush = SolidBrush(Color.red)
	gr.fill_rectangle(redBrush, Rectangle(0, 0, bmp_image.width, bmp_image.height // 2))

	# Rellenar la mitad inferior de la imagen en verde.
	greenBrush = SolidBrush(Color.green)
	gr.fill_rectangle(greenBrush, Rectangle(0, bmp_image.height // 2, bmp_image.width, bmp_image.height // 2))

	# Guardar en BMP
	bmp_image.save(os.path.join(directory, "output.monochrome.96dpi.bmp"))


```

### The following example shows how to extract information about raw data format and alpha channel from a BMP image. {#example_86}
``` python
from aspose.imaging.fileformats.bmp import BmpImage

# Crear una imagen BMP de 32 bpp de 100 x 100 px.
with BmpImage(100, 100, 32, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))


# Crear una imagen BMP de 24 bpp de 100 x 100 px.
with BmpImage(100, 100, 24, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))

# Generalmente, BMP no soporta canal alfa, por lo que la salida se verá así:
# FileFormat = BMP, RawDataFormat = Rgb32Bpp, used channels: 8,8,8,8, HasAlpha = False
# FileFormat = BMP, RawDataFormat = Rgb24Bpp, used channels: 8,8,8, HasAlpha = False

```

### The following example shows how the bitmap compression affects the output image size. {#example_87}
``` python

from aspose.imaging import Color, ColorPalette, Graphics
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
from aspose.imaging.extensions import StreamExtensions as strm_ext

compressions = (BitmapCompression.RGB, BitmapCompression.RLE8)

paletterColors = (Color.red, Color.green)

# Crear una paleta monocromática que contenga solo colores rojo y verde.
palette = ColorPalette.create_with_colors(paletterColors)

for compression in compressions:
	# Crear una imagen BMP de 8 bpp de 100 x 100 px.
	with BmpImage(100, 100, 8, palette, compression, 0.0, 0.0) as bmp_image:
		gr = Graphics(bmp_image)
		# Rellene toda la imagen de rojo.
		red_brush = SolidBrush(Color.red)
		gr.fill_rectangle(red_brush, bmp_image.bounds)
		# Guardar la imagen en un flujo de memoria para obtener el tamaño de la imagen de salida.
		with strm_ext.create_memory_stream() as stream:
			bmp_image.save(stream)
			print("---------------------------------------------")
			print("The compression =", bmp_image.compression.name)
			print("The number of bits per pixel =", bmp_image.bits_per_pixel)
			print(f"The image dimensions = {bmp_image.width} x {bmp_image.height}")
			print("The raw line size =", bmp_image.raw_line_size)
			print("The output size in bytes =", stream.tell())

# La salida se ve así:
# ---------------------------------------------
# La compresión = RGB
# El número de bits por píxel = 8
# Las dimensiones de la imagen =100 x 100
# El tamaño de línea sin procesar = 100
# El tamaño de salida en bytes = 1178
# ---------------------------------------------
# La compresión = RLE8
# El número de bits por píxel = 8
# Las dimensiones de la imagen =100 x 100
# El tamaño de línea sin procesar = 100
# El tamaño de salida en bytes = 856

```

### The following example shows how to set horizontal/vertical resolution of a BMP image. {#example_88}
``` python

import os
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BmpImage

directory = r"c:\temp"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	bmp_image = aspycore.as_of(image, BmpImage)
	# Obtener la resolución horizontal y vertical de la BmpImage
	horizontal_resolution = bmp_image.horizontal_resolution
	vertical_resolution = bmp_image.vertical_resolution
	print("The horizontal resolution, in pixels per inch:", horizontal_resolution)
	print("The vertical resolution, in pixels per inch:", vertical_resolution)

	if (horizontal_resolution != 96.0 || vertical_resolution != 96.0)
	{
		# Utilice el método set_resolution para actualizar ambos valores de resolución en una sola llamada.
		print("Set resolution values to 96 dpi")
		bmp_image.set_resolution(96.0, 96.0)
		print("The horizontal resolution, in pixels per inch:", bmp_image.horizontal_resolution);
		print("The vertical resolution, in pixels per inch:", bmp_image.vertical_resolution);
	}

	# La salida puede verse así:
	# La resolución horizontal, en píxeles por pulgada: 0
	# La resolución vertical, en píxeles por pulgada: 0
	# Establecer valores de resolución a 96 dpi
	# La resolución horizontal, en píxeles por pulgada: 96.0
	# La resolución vertical, en píxeles por pulgada: 96.0

```

### The following example gets the information from the BMP header and prints it to the console. {#example_89}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BmpImage

with Image.load(r"c:\temp\sample.bmp") as image:
	bmp_image = aspycore.as_of(image, BmpImage)
	header = bmp_image.bitmap_info_header

	print("The number of palette colors that are required for displaying the bitmap:", header.bitmap_colors_important)
	print("The number of palette colors used in the bitmap:", header.bitmap_colors_used)
	print("The bitmap compression:", header.bitmap_compression)
	print("The bitmap height:", header.bitmap_height)
	print("The bitmap width:", header.bitmap_width)
	print("The bitmap raw data size in bytes:", header.bitmap_image_size)
	print("The number of planes:", header.bitmap_planes)
	print("The horizontal resolution of the bitmap, in pixels-per-meter:", header.bitmap_x_pels_per_meter)
	print("The vertical resolution of the bitmap, in pixels-per-meter:", header.bitmap_y_pels_per_meter)
	print("The number of bits per pixel:", header.bits_per_pixel)
	print("The extra bits masks:", header.extra_bit_masks)
	print("The header size in bytes:", header.header_size)

#La salida puede verse así:
#El número de colores de paleta que se requieren para mostrar el mapa de bits: 0
#El número de colores de paleta usados en el mapa de bits: 0
#La compresión del mapa de bits: 0
#La altura del mapa de bits: 375
#El ancho del mapa de bits: 500
#El tamaño de los datos sin procesar del mapa de bits en bytes: 562500
#El número de planos: 1
#La resolución horizontal del mapa de bits, en píxeles por metro: 0
#La resolución vertical del mapa de bits, en píxeles por metro: 0
#El número de bits por píxel: 24
#Las máscaras de bits extra: 
#El tamaño de la cabecera en bytes: 40

```

### Compress BMP image using DXT1 compression algorithm. {#example_207}
``` python
#cxFor:aspose.imaging.imageoptions.BmpOptions.compression

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression

with Image.load("Tiger.bmp") as image:
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.DXT1
	image.save("CompressedTiger.bmp", bmp_options)

```

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

