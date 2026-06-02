---
title: "AvifImage Clase"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.fileformats.avif/avifimage/
---

**Summary:** The Avif image.

**Module:** [aspose.imaging.fileformats.avif](/imaging/python-net/aspose.imaging.fileformats.avif/)

**Full Name:** aspose.imaging.fileformats.avif.AvifImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [AvifImage()](#AvifImage__1) | Inicializa una nueva instancia de la clase AvifImage |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Obtiene o establece un valor que indica si se ajusta automáticamente la paleta. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece un valor para el color de fondo. |
| bits_per_pixel | int | r | Obtiene el valor de bits por píxel. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtiene los límites del objeto. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtiene el contenedor [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Obtiene el flujo de datos del objeto. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece la instancia Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Obtiene un valor del formato de archivo |
| has_alpha | bool | r | Obtiene un valor que indica si esta instancia tiene alfa. |
| has_background_color | bool | r/w | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| has_transparent_color | bool | r/w | Obtiene o establece un valor que indica si esta instancia de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) tiene un color transparente. |
| height | int | r | Obtiene la altura de la imagen AVIF. |
| horizontal_resolution | float | r/w | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Obtiene la opacidad de esta imagen. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtiene o establece el monitor de interrupciones. |
| is_cached | bool | r | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| is_raw_data_available | bool | r | Obtiene un valor que indica si se admite la carga de datos sin procesar. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtiene los metadatos de la imagen. |
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
| width | int | r | Obtiene el ancho de la imagen AVIF. |
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
| [create_from_images(images)](#create_from_images_images_28) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_29) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_30) | Recortar la imagen con desplazamientos. |
| [crop(rectangle)](#crop_rectangle_31) | Recortando la imagen. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_32) | Aplica dithering a la imagen actual. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_33) | Aplica dithering a la imagen actual. |
| [embed_digital_signature(password)](#embed_digital_signature_password_34) | Incrustar una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía. |
| [filter(rectangle, options)](#filter_rectangle_options_35) | Filtra el rectángulo especificado. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_36) | Obtiene un píxel ARGB de 32 bits de la imagen. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_37) | Obtiene la matriz predeterminada de píxeles ARGB de 32 bits. |
| [get_default_options(args)](#get_default_options_args_38) | Obtiene las opciones predeterminadas. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_39) | Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40) | Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_41) | Obtiene la matriz de datos sin procesar predeterminada. |
| [get_file_format(file_path)](#get_file_format_file_path_42) | Obtiene el formato de archivo. |
| [get_file_format(stream)](#get_file_format_stream_43) | Obtiene el formato de archivo. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_44) | Obtiene el formato de archivo. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_45) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_46) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_modify_date(use_default)](#get_modify_date_use_default_47) | Obtiene la fecha y hora en que la imagen del recurso fue modificada por última vez. |
| [get_original_options()](#get_original_options__48) | Obtiene las opciones basadas en la configuración original del archivo.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            método [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al método [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) como segundo parámetro. |
| [get_pixel(x, y)](#get_pixel_x_y_49) | Obtiene un píxel de la imagen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_50) | Obtiene una altura proporcional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_51) | Obtiene un ancho proporcional. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_52) | Convierte a aps. |
| [get_skew_angle()](#get_skew_angle__53) | Obtiene el ángulo de sesgo.<br/>            Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear. |
| grayscale() | Transformación de una imagen a su representación en escala de grises |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_54) | Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral. |
| [load(file_path)](#load_file_path_55) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(stream)](#load_stream_57) | Carga una nueva imagen desde el flujo especificado. |
| [load(stream, load_options)](#load_stream_load_options_58) | Carga una nueva imagen desde el flujo especificado. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | Carga píxeles ARGB de 32 bits. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | Carga píxeles ARGB de 64 bits. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | Carga píxeles en formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | Carga píxeles en formato CMYK.<br/>            Este método está obsoleto. Por favor, use de manera más eficaz el método [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | Carga parcialmente píxeles ARGB de 32 bits (por bloques). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_64) | Carga parcialmente píxeles ARGB de 64 bits por paquetes. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_65) | Carga píxeles parcialmente por paquetes. |
| [load_pixels(rectangle)](#load_pixels_rectangle_66) | Carga píxeles. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_67) | Carga datos sin procesar. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_68) | Carga datos sin procesar. |
| [load_stream(stream)](#load_stream_stream_69) | Carga una nueva imagen desde el flujo especificado. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_70) | Carga una nueva imagen desde el flujo especificado. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_71) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| normalize_angle() | Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la distorsión del escaneo.<br/>            Este método utiliza los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_72) | Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo.<br/>            Este método usa los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | Normaliza el histograma de la imagen — ajusta los valores de píxeles para usar todo el rango disponible. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_73) | Lee toda la línea de escaneo según el índice de línea de escaneo especificado. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_74) | Lee toda la línea de escaneo según el índice de línea de escaneo especificado. |
| remove_metadata() | Elimina los metadatos de esta instancia de imagen estableciendo el valor de [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) a **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_75) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_76) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_77) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para mantener bordes suaves. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_78) | Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_79) | Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [resize(new_width, new_height)](#resize_new_width_new_height_80) | Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_81) | Redimensiona la imagen. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_82) | Redimensiona la imagen. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_83) | Redimensiona la imagen. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_84) | Redimensiona la imagen. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_85) | Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_86) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_87) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_88) | Redimensiona la altura proporcionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_89) | Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_90) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_91) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_92) | Redimensiona el ancho proporcionalmente. |
| [rotate(angle)](#rotate_angle_93) | Rotar la imagen alrededor del centro. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_94) | Rotar la imagen alrededor del centro. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_95) | Rota, voltea o rota y voltea la imagen. |
| save() | Guarda los datos de la imagen en el flujo subyacente. |
| [save(file_path)](#save_file_path_96) | Guarda la imagen en la ubicación de archivo especificada. |
| [save(file_path, options)](#save_file_path_options_97) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_98) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, over_write)](#save_file_path_over_write_99) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(stream)](#save_stream_100) | Guarda los datos. |
| [save(stream, options_base)](#save_stream_options_base_101) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_102) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_103) | Guarda los píxeles ARGB de 32 bits. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_104) | Guarda los píxeles. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_105) | Guarda los píxeles.<br/>            Este método está obsoleto. Por favor, utiliza de forma más eficaz el método [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_106) | Guarda píxeles (método específico de formato). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_107) | Guarda los datos sin procesar. |
| [save_to_stream(stream)](#save_to_stream_stream_108) | Guarda los datos del objeto en el flujo especificado. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_109) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_110) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_111) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_112) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_113) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_114) | Establece la paleta de la imagen. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_115) | Establece un píxel de la imagen para la posición especificada. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_116) | Establece la resolución para este [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_117) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_118) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_119) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |


### Constructor: AvifImage() {#AvifImage__1}


```
 AvifImage() 
```

Inicializa una nueva instancia de la clase AvifImage

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


### Method: create_from_images(images)  [static] {#create_from_images_images_28}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_29}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_30}


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

### Method: crop(rectangle) {#crop_rectangle_31}


```
 crop(rectangle) 
```

Recortando la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_32}


```
 dither(dithering_method, bits_count) 
```

Aplica dithering a la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | El método de tramado. |
| bits_count | int | El recuento final de bits para el tramado. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_33}


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

### Method: embed_digital_signature(password) {#embed_digital_signature_password_34}


```
 embed_digital_signature(password) 
```

Incrustar una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | string | La contraseña utilizada para generar datos de firma digital. |

### Method: filter(rectangle, options) {#filter_rectangle_options_35}


```
 filter(rectangle, options) 
```

Filtra el rectángulo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Las opciones. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_36}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_37}


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


### Method: get_default_options(args) {#get_default_options_args_38}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_39}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo del cual obtener píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | El cargador parcial de píxeles. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_41}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_42}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_43}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_44}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_45}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_46}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_47}


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


### Method: get_original_options() {#get_original_options__48}


```
 get_original_options() 
```

Obtiene las opciones basadas en la configuración original del archivo.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            método [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al método [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) como segundo parámetro.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones basadas en la configuración original del archivo. |


### Method: get_pixel(x, y) {#get_pixel_x_y_49}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_50}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_51}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_52}


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


### Method: get_skew_angle() {#get_skew_angle__53}


```
 get_skew_angle() 
```

Obtiene el ángulo de sesgo.<br/>            Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear.

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | El ángulo de sesgo, en grados. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_54}


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


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carga parcialmente píxeles ARGB de 32 bits (por bloques).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo desde el cual cargar los píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | El cargador parcial de píxeles. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_64}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Carga parcialmente píxeles ARGB de 64 bits por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo deseado. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | El cargador de píxeles ARGB de 64 bits. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_65}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carga píxeles parcialmente por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo deseado. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | El cargador de píxeles. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_66}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_67}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_68}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_69}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_70}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_71}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_72}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normaliza el ángulo.<br/>            Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo.<br/>            Este método usa los métodos [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) y [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| resize_proportionally | bool | si se establece a <c>true</c> el tamaño de su imagen se cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en otro caso, se dejan las dimensiones sin cambios y solo se rotan los contenidos internos de la imagen. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color del fondo. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_73}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_74}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_75}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_76}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_77}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_78}


```
 replace_non_transparent_colors(new_color) 
```

Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nuevo color con el que reemplazar los colores no transparentes. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_79}


```
 replace_non_transparent_colors(new_color_argb) 
```

Reemplaza todos los colores no transparentes por un nuevo color y conserva el valor alfa original para mantener bordes suaves.<br/>            Nota: si lo usas en imágenes sin transparencia, todos los colores serán reemplazados por uno solo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_color_argb | int | Nuevo valor ARGB de color para reemplazar colores no transparentes. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_80}


```
 resize(new_width, new_height) 
```

Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_81}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_82}


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

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_83}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_84}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_85}


```
 resize_height_proportionally(new_height) 
```

Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_86}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_87}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_88}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_89}


```
 resize_width_proportionally(new_width) 
```

Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_90}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_91}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_92}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: rotate(angle) {#rotate_angle_93}


```
 rotate(angle) 
```

Rotar la imagen alrededor del centro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_94}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_95}


```
 rotate_flip(rotate_flip_type) 
```

Rota, voltea o rota y voltea la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | El tipo de volteo de rotación. |

### Method: save(file_path) {#save_file_path_96}


```
 save(file_path) 
```

Guarda la imagen en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar la imagen. |

### Method: save(file_path, options) {#save_file_path_options_97}


```
 save(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_98}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_99}


```
 save(file_path, over_write) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |
| sobrescribir | bool | si se establece en <c>true</c> sobrescribe el contenido del archivo, de lo contrario se añadirá. |

### Method: save(stream) {#save_stream_100}


```
 save(stream) 
```

Guarda los datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos. |

### Method: save(stream, options_base) {#save_stream_options_base_101}


```
 save(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_102}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_103}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Guarda los píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | La matriz de píxeles ARGB de 32 bits. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_104}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Guarda los píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_105}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Guarda los píxeles.<br/>            Este método está obsoleto. Por favor, utiliza de forma más eficaz el método [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | La matriz de píxeles CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_106}


```
 save_pixels(rectangle, pixels) 
```

Guarda píxeles (método específico de formato).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo donde guardar los píxeles. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | La matriz de píxeles ARGB de 32 bits. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_107}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_108}


```
 save_to_stream(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos del objeto. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_109}


```
 save_to_stream_with_options(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_110}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_111}


```
 save_with_options(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_112}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_113}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_114}


```
 set_palette(palette, update_colors) 
```

Establece la paleta de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta a establecer. |
| update_colors | bool | si se establece en <c>true</c> los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas de paleta correspondientes. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_115}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_116}


```
 set_resolution(dpi_x, dpi_y) 
```

Establece la resolución para este [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dpi_x | float | La resolución horizontal, en puntos por pulgada, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La resolución vertical, en puntos por pulgada, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_117}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_118}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| argb_32_pixels | int[] | La matriz de colores ARGB de 32 bits para escribir. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_119}


```
 write_scan_line(scan_line_index, pixels) 
```

Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | La matriz de colores de píxeles para escribir. |

