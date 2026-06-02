---
title: "Clase EpsImage"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.fileformats.eps/epsimage/
---

**Summary:** The API for Encapsulated PostScript (EPS) image file format support offers<br/>            robust capabilities for manipulating compositions comprising text, graphics,<br/>            and images. With features such as bitmap preview image handling, orientation<br/>            flipping, bounding box retrieval for illustration bounds, resizing, rotating<br/>            images, and adding preview images, this API ensures seamless processing<br/>            and integration of EPS files into various applications with precision and<br/>            versatility.

**Module:** [aspose.imaging.fileformats.eps](/imaging/python-net/aspose.imaging.fileformats.eps/)

**Full Name:** aspose.imaging.fileformats.eps.EpsImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IObjectWithSizeF, VectorImage

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Obtiene o establece un valor que indica si se ajusta automáticamente la paleta. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece un valor para el color de fondo. |
| bits_per_pixel | int | r | Acceda al preciso nivel de bits de la imagen sin esfuerzo con esta propiedad. Obtenga <br/>            el recuento de bits por píxel, proporcionando información crucial sobre la profundidad de color de la imagen <br/>            y ayudando a optimizar las tareas de procesamiento. Ideal para aplicaciones que requieren <br/>            un control granular sobre la manipulación y el análisis de imágenes. |
| bounding_box | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Al acceder al cuadro delimitador original en puntos independientes del dispositivo, esta propiedad <br/>            proporciona información geométrica crucial sobre las dimensiones del [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/). <br/>            Al recuperar estos datos, los usuarios pueden evaluar con precisión el tamaño y la relación de aspecto de la imagen <br/>            facilitando un diseño y posicionamiento precisos en diversas aplicaciones. |
| bounding_box_px | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Esta propiedad devuelve el cuadro delimitador original de la instancia [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/) <br/>            en píxeles, proporcionando datos geométricos esenciales para una renderización y <br/>            manipulación precisas. Con esta información, los usuarios pueden garantizar una colocación y dimensionado precisos /// de imágenes EPS en sus proyectos, mejorando la presentación visual general y la calidad. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtiene los límites del objeto. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtiene el contenedor [Image](/imaging/python-net/aspose.imaging/image/). |
| creation_date | System.DateTime | r | Obteniendo la fecha de creación de las Convenciones de Estructuración de Documentos (DSC) de EPS <br/>            comentarios, esta propiedad proporciona metadatos esenciales que indican el origen del archivo EPS <br/>            . Al acceder a esta información, los usuarios obtienen información sobre el origen y la cronología del archivo, mejorando la gestión y organización de los archivos. |
| creator | string | r | Esta propiedad ofrece acceso a la información del creador obtenida de los comentarios de las Convenciones de Estructuración de Documentos EPS (DSC) encontrados dentro del archivo EPS. <br/>            Comprender los detalles del creador brinda información sobre el software o herramienta utilizada para generar el archivo EPS, <br/>            facilitando la evaluación de compatibilidad entre diversas plataformas y <br/>            aplicaciones. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Obtiene el flujo de datos del objeto. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| eps_type | [EpsType](/imaging/python-net/aspose.imaging.fileformats.eps.consts/epstype/) | r | Acceda e interprete el valor del subtipo de su imagen EPS, optimizando su <br/>            flujo de trabajo y mejorando la compatibilidad entre plataformas. Ideal para optimizar la recuperación del subtipo EPS en sus proyectos con precisión y eficiencia. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtiene o establece la instancia Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Acceda al formato de archivo de su imagen con esta propiedad. Recupere información esencial <br/>            sobre el formato de su archivo de imagen, facilitando la compatibilidad y <br/>            el procesamiento eficiente. Ideal para identificar el formato de sus archivos de imagen para <br/>            una integración fluida en sus proyectos. |
| has_background_color | bool | r/w | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| has_raster_preview | bool | r | Descubra la presencia de una vista previa raster de forma sencilla con esta propiedad. Acceda <br/>            al valor booleano que indica si la instancia [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/) incluye una <br/>            vista previa raster, potenciando sus tareas de procesamiento de imágenes con claridad y eficiencia. <br/>            Ideal para simplificar decisiones de flujo de trabajo basadas en la presencia o ausencia de <br/>            vistas previas raster en imágenes EPS. |
| height | int | r | Obtiene la altura de la imagen. |
| height_f | float | r | Acceda a la altura de la imagen usando esta propiedad. Obtenga la altura de la imagen con <br/>            facilidad, permitiendo ajustes de diseño sin interrupciones, cálculos de relación de aspecto y renderizado preciso <br/>            en diferentes resoluciones de pantalla y entornos de visualización. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtiene o establece el monitor de interrupciones. |
| is_cached | bool | r | Esta propiedad proporciona una forma conveniente de verificar si los datos del objeto están actualmente <br/>            en caché, eliminando la necesidad de lecturas de datos adicionales. Ofrece un método rápido y <br/>            eficiente para determinar si la información requerida está disponible de inmediato, <br/>            optimizando el rendimiento y reduciendo la sobrecarga de recursos en operaciones intensivas en datos. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtiene los metadatos de la imagen. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtiene o establece la paleta de colores. La paleta de colores no se usa cuando los píxeles se representan directamente. |
| post_script_version | string | r | Esta propiedad recupera la versión de PostScript asociada con el<br/>            [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/) instancia. Proporciona información sobre la versión específica del lenguaje PostScript utilizada dentro del archivo EPS, ayudando en la evaluación de compatibilidad <br/>            y facilitando una integración sin problemas con entornos compatibles con PostScript. |
| preview_image_count | int | r | Acceda al número de imágenes de vista previa disponibles con facilidad. Esta propiedad le permite <br/>            recuperar sin esfuerzo el recuento de imágenes de vista previa asociadas a su archivo, <br/>            facilitando la gestión y navegación eficientes de sus vistas previas de imágenes. Ideal para <br/>            optimizar su flujo de trabajo y organizar sus recursos de imágenes de manera efectiva. |
| preview_images | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Recupere las imágenes de vista previa asociadas a su archivo. Esta propiedad brinda <br/>            acceso sin interrupciones a la colección de imágenes de vista previa, permitiéndole navegar y gestionarlas eficientemente <br/>            según sea necesario. Ideal para previsualizar rápidamente y seleccionar la <br/>            imagen adecuada para su proyecto. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtiene el tamaño del objeto. |
| size_f | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Obtiene el tamaño del objeto, en pulgadas. |
| título | string | r | Esta propiedad recupera el título extraído de los comentarios de las Convenciones de Estructuración <br/>            de Documentos EPS (DSC) incrustados en el archivo EPS. Proporciona metadatos valiosos <br/>            sobre el contenido del archivo EPS, ayudando en la organización del documento y <br/>            la identificación dentro de aplicaciones de software compatibles. |
| use_palette | bool | r | Obtiene un valor que indica si se usa la paleta de la imagen. |
| width | int | r | Obtiene el ancho de la imagen. |
| width_f | float | r | Recupere el ancho de la imagen con esta práctica propiedad. Obtenga el ancho de la imagen sin esfuerzo, facilitando cálculos precisos de diseño, operaciones de escalado <br/>            y tareas relacionadas con dimensiones dentro de su aplicación. Ideal para garantizar un renderizado y visualización precisos <br/>            de imágenes en diversas plataformas y dispositivos. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtiene o establece los datos Xmp. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| cache_data() | Este método no hace nada ya que la implementación actual de la<br/>            [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/) clase no implica el almacenamiento en caché de datos. Aunque puede no <br/>            realizar ninguna acción, comprender este comportamiento es crucial para los desarrolladores que trabajan <br/>            con imágenes EPS, garantizando una gestión eficiente de recursos y un rendimiento óptimo <br/>            dentro de sus aplicaciones. |
| [can_load(file_path)](#can_load_file_path_1) | Determina si la imagen puede cargarse desde la ruta de archivo especificada. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas. |
| [can_load(stream)](#can_load_stream_3) | Determina si la imagen puede cargarse desde el flujo especificado. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando los _loadOptions_ especificados. |
| [can_load_stream(stream)](#can_load_stream_stream_5) | Determina si la imagen puede cargarse desde el flujo especificado. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_6) | Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando los _loadOptions_ especificados. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_7) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas. |
| [can_save(options)](#can_save_options_8) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| [create(files)](#create_files_9) | Crea la imagen multipágina que contiene los archivos especificados. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_10) | Crea la imagen multipágina que contiene los archivos especificados. |
| [create(image_options, width, height)](#create_image_options_width_height_11) | Crea una nueva imagen usando las opciones de creación especificadas. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_12) | Crea una instancia de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) a partir del arreglo de píxeles proporcionado.<br/> <br/> Valida que el ancho y alto especificados coincidan con las dimensiones de los datos de píxeles.<br/> Este método solo puede usarse cuando la biblioteca está en modo Licenciado. |
| [create(images)](#create_images_13) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create(images, dispose_images)](#create_images_dispose_images_14) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [create(multipage_create_options)](#create_multipage_create_options_15) | Crea las opciones de creación multipágina especificadas. |
| [create_from_files(files)](#create_from_files_files_16) | Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_17) | Crea la imagen multipágina que contiene los archivos especificados como páginas de carga diferida. |
| [create_from_images(images)](#create_from_images_images_18) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_19) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_20) | Recortar la imagen con desplazamientos. |
| [crop(rectangle)](#crop_rectangle_21) | Recorta el rectángulo especificado. |
| [get_default_options(args)](#get_default_options_args_22) | Obtiene las opciones de imagen predeterminadas. |
| [get_embedded_images()](#get_embedded_images__23) | Obtiene las imágenes incrustadas. |
| [get_file_format(file_path)](#get_file_format_file_path_24) | Obtiene el formato de archivo. |
| [get_file_format(stream)](#get_file_format_stream_25) | Obtiene el formato de archivo. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_26) | Obtiene el formato de archivo. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_original_options()](#get_original_options__29) | Obtiene las opciones basadas en la configuración original del archivo.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            método [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al método [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) como segundo parámetro. |
| [get_preview_image(format)](#get_preview_image_format_30) | Recupera la imagen de vista previa existente en el _formato_ especificado o <br/>            devuelve **None** si no se encuentra ninguna. Este método ofrece flexibilidad al <br/>            acceder a imágenes de vista previa adaptadas a formatos específicos, optimizando la compatibilidad y <br/>            la gestión de recursos dentro de las aplicaciones. |
| [get_preview_images()](#get_preview_images__31) | Accede a las imágenes de vista previa vinculadas a la instancia [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/), permitiendo <br/>            una recuperación sin interrupciones para inspección o uso en aplicaciones. Este método <br/>            brinda acceso conveniente a las imágenes de vista previa, mejorando la interacción del usuario con los <br/>            datos de la imagen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | Obtiene una altura proporcional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | Obtiene un ancho proporcional. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_34) | Convierte a aps. |
| [load(file_path)](#load_file_path_35) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| [load(stream)](#load_stream_37) | Carga una nueva imagen desde el flujo especificado. |
| [load(stream, load_options)](#load_stream_load_options_38) | Carga una nueva imagen desde el flujo especificado. |
| [load_stream(stream)](#load_stream_stream_39) | Carga una nueva imagen desde el flujo especificado. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_40) | Carga una nueva imagen desde el flujo especificado. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_41) | Carga una nueva imagen desde la ruta de archivo o URL especificada.<br/>            Si _filePath_ es una ruta de archivo, el método simplemente abre el archivo.<br/>            Si _filePath_ es una URL, el método descarga el archivo, lo almacena como uno temporal y lo abre. |
| remove_background() | Elimina el fondo. |
| [remove_background(settings)](#remove_background_settings_42) | Elimina el fondo. |
| remove_metadata() | Elimina los metadatos. |
| [resize(new_width, new_height)](#resize_new_width_new_height_43) | Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_44) | Redimensiona el nuevo ancho especificado. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_45) | Redimensiona la imagen con opciones extendidas. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_46) | Redimensiona la imagen. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_47) | Redimensiona la imagen. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_48) | Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_49) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_50) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_51) | Redimensiona la altura proporcionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_52) | Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_53) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_54) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_55) | Redimensiona el ancho proporcionalmente. |
| [rotate(angle)](#rotate_angle_56) | Rotar la imagen alrededor del centro. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_57) | Rota, voltea o rota y voltea la imagen. |
| save() | Guarda los datos de la imagen en el flujo subyacente. |
| [save(file_path)](#save_file_path_58) | Guarda la imagen en la ubicación de archivo especificada. |
| [save(file_path, options)](#save_file_path_options_59) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_60) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save(file_path, over_write)](#save_file_path_over_write_61) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(stream)](#save_stream_62) | Guarda los datos. |
| [save(stream, options_base)](#save_stream_options_base_63) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_64) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_to_stream(stream)](#save_to_stream_stream_65) | Guarda los datos del objeto en el flujo especificado. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_66) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_67) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_68) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_69) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_70) | Personalice las paletas de imágenes para lograr esquemas de color únicos y mejorar el atractivo visual. <br/>            Ajuste los colores para efectos específicos y optimice la calidad de la imagen en diferentes <br/>            plataformas y dispositivos con facilidad. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_71) | Intenta establecer una instancia de _metadata_, si esta instancia de [Image](/imaging/python-net/aspose.imaging/image/) admite e implementa la instancia [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_5}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_6}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_7}


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


### Method: can_save(options) {#can_save_options_8}


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


### Method: create(files)  [static] {#create_files_9}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_10}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_11}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_12}


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


### Method: create(images)  [static] {#create_images_13}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_14}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_15}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_16}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_17}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_18}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_19}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_20}


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

### Method: crop(rectangle) {#crop_rectangle_21}


```
 crop(rectangle) 
```

Recorta el rectángulo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo. |

### Method: get_default_options(args) {#get_default_options_args_22}


```
 get_default_options(args) 
```

Obtiene las opciones de imagen predeterminadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| args | System.Object | Los argumentos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de imagen predeterminadas. |


### Method: get_embedded_images() {#get_embedded_images__23}


```
 get_embedded_images() 
```

Obtiene las imágenes incrustadas.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmbeddedImage[]](/imaging/python-net/aspose.imaging/embeddedimage/) | Matriz de imágenes |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_24}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_25}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_original_options() {#get_original_options__29}


```
 get_original_options() 
```

Obtiene las opciones basadas en la configuración original del archivo.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            método [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al método [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) como segundo parámetro.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones basadas en la configuración original del archivo. |


### Method: get_preview_image(format) {#get_preview_image_format_30}


```
 get_preview_image(format) 
```

Recupera la imagen de vista previa existente en el _formato_ especificado o <br/>            devuelve **None** si no se encuentra ninguna. Este método ofrece flexibilidad al <br/>            acceder a imágenes de vista previa adaptadas a formatos específicos, optimizando la compatibilidad y <br/>            la gestión de recursos dentro de las aplicaciones.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| format | [EpsPreviewFormat](/imaging/python-net/aspose.imaging.fileformats.eps/epspreviewformat/) | El formato de imagen de vista previa EPS. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | La imagen de vista previa existente o **None**. |


### Method: get_preview_images() {#get_preview_images__31}


```
 get_preview_images() 
```

Accede a las imágenes de vista previa vinculadas a la instancia [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/), permitiendo <br/>            una recuperación sin interrupciones para inspección o uso en aplicaciones. Este método <br/>            brinda acceso conveniente a las imágenes de vista previa, mejorando la interacción del usuario con los <br/>            datos de la imagen.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Image]] | Las imágenes de vista previa. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_34}


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


### Method: load(file_path)  [static] {#load_file_path_35}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


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


### Method: load(stream)  [static] {#load_stream_37}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_39}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_40}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_41}


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


### Method: remove_background(settings) {#remove_background_settings_42}


```
 remove_background(settings) 
```

Elimina el fondo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| settings | [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | La configuración. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_43}


```
 resize(new_width, new_height) 
```

Redimensiona la imagen. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_44}


```
 resize(new_width, new_height, resize_type) 
```

Redimensiona el nuevo ancho especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |


**See also:**

**[Example # 1](#example_218)**: Resize EPS image and export it to PNG format.


### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_45}


```
 resize(new_width, new_height, settings) 
```

Redimensiona la imagen con opciones extendidas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento. |


**See also:**

**[Example # 1](#example_219)**: Resize EPS image using advanced settings.


### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_46}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_47}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_48}


```
 resize_height_proportionally(new_height) 
```

Redimensiona la altura proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_49}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_50}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_51}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_52}


```
 resize_width_proportionally(new_width) 
```

Redimensiona el ancho proporcionalmente. Se utiliza el valor predeterminado [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_53}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo de redimensionamiento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_54}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_55}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Los ajustes de redimensionamiento de la imagen. |

### Method: rotate(angle) {#rotate_angle_56}


```
 rotate(angle) 
```

Rotar la imagen alrededor del centro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_57}


```
 rotate_flip(rotate_flip_type) 
```

Rota, voltea o rota y voltea la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Tipo de rotación y volteo. |

### Method: save(file_path) {#save_file_path_58}


```
 save(file_path) 
```

Guarda la imagen en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar la imagen. |

### Method: save(file_path, options) {#save_file_path_options_59}


```
 save(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_60}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_61}


```
 save(file_path, over_write) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |
| sobrescribir | bool | si se establece en <c>true</c> sobrescribe el contenido del archivo, de lo contrario se añadirá. |

### Method: save(stream) {#save_stream_62}


```
 save(stream) 
```

Guarda los datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos. |

### Method: save(stream, options_base) {#save_stream_options_base_63}


```
 save(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_64}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_65}


```
 save_to_stream(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos del objeto. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_66}


```
 save_to_stream_with_options(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones de guardado. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_67}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_68}


```
 save_with_options(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo indicado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Las opciones. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_69}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_70}


```
 set_palette(palette, update_colors) 
```

Personalice las paletas de imágenes para lograr esquemas de color únicos y mejorar el atractivo visual. <br/>            Ajuste los colores para efectos específicos y optimice la calidad de la imagen en diferentes <br/>            plataformas y dispositivos con facilidad.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La paleta a establecer. |
| update_colors | bool | si se establece en <c>true</c> los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas de paleta correspondientes. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_71}


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


## **Examples**
### Convert EPS image to PNG using PostScript rendering. {#example_205}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.eps import EpsImage, EpsPreviewFormat
from aspose.imaging.imageoptions import PngOptions

with aspycore.as_of(Image.load("Sample.eps"), EpsImage) as image:
	obj_init = EpsRasterizationOptions()
	obj_init.page_width = 500
	obj_init.page_height = 500
	obj_init.preview_to_export = EpsPreviewFormat.POST_SCRIPT_RENDERING
	options = PngOptions()
	obj_init2.vector_rasterization_options = obj_init
	# Renderizar imagen raster usando PostScript
	image.save("Sample.png", options)
	

```

### Convert EPS image to PDF using PostScript rendering. {#example_206}
``` python

from aspose.imaging import Image, PdfComplianceVersion
from aspose.imaging.imageoptions import PdfOptions
from aspose.imaging.fileformats.pdf import PdfCoreOptions

with Image.load("Sample.eps") as image:
	options = PdfOptions()
	options.pdf_core_options = PdfCoreOptions()
	options.pdf_core_options.pdf_compliance = PdfComplianceVersion.PDF_A1B # Set required PDF compliance
	image.save("Sample.pdf", options)


```

### Resize EPS image and export it to PNG format. {#example_218}
``` python

from aspose.imaging import Image, ResizeType
from aspose.imaging.imageoptions import PngOptions

# Cargar imagen EPS
with Image.load("AstrixObelix.eps") as image:
	# Redimensionar la imagen usando el método de interpolación cúbica Mitchell
	image.resize(400, 400, ResizeType.MITCHELL)

	# Exportar imagen al formato PNG
	image.save("ExportResult.png", PngOptions())


```

### Resize EPS image using advanced settings. {#example_219}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, ImageResizeSettings, ResizeType, ImageFilterType, ColorCompareMethod, ColorQuantizationMethod
from aspose.imaging.imageoptions import PngOptions

#Cargar imagen EPS
with Image.load("AstrixObelix.eps") as image:
	# Redimensionar la imagen usando configuraciones avanzadas de redimensionado
	obj_init = ImageResizeSettings()
	obj_init.mode = ResizeType.LANCZOS_RESAMPLE
	obj_init.filter_type = ImageFilterType.SMALL_RECTANGULAR
	obj_init.color_compare_method = ColorCompareMethod.EUCLIDIAN
	obj_init.color_quantization_method = ColorQuantizationMethod.POPULARITY
	image.resize(400, 400, obj_init)
	# Exportar imagen al formato PNG
	image.save("ExportResult.png", PngOptions())


```

