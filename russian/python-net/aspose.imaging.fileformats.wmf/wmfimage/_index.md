---
title: "WmfImage Class"
type: docs
weight: 350
url: /ru/python-net/aspose.imaging.fileformats.wmf/wmfimage/
---

**Summary:** Manipulate Microsoft Windows Metafile (WMF) images with our API, seamlessly<br/>            handling both vector and bitmap data stored within variable-length records.<br/>            Resize, rotate, and flip images with ease while setting custom image palettes.<br/>            Convert WMF files to compressed WMZ formats or save them in raster image formats<br/>            for versatile usage across platforms and applications.

**Module:** [aspose.imaging.fileformats.wmf](/imaging/python-net/aspose.imaging.fileformats.wmf/)

**Full Name:** aspose.imaging.fileformats.wmf.WmfImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IObjectWithSizeF, MetaImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfImage()](#WmfImage__1) | Создайте новый экземпляр класса [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/), инициализируя его для <br/>            дальнейшей манипуляции и обработки данных изображений Windows Metafile (WMF). Этот <br/>            конструктор предоставляет базовый объект для работы с изображениями WMF, позволяя <br/>            бесшовную интеграцию возможностей обработки изображений WMF в функциональность вашего приложения. |
| [WmfImage(width, height)](#WmfImage_width_height_2) | Создайте новый экземпляр класса [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/) с настраиваемыми <br/>            параметрами ширины и высоты, облегчая создание пустых изображений WMF, адаптированных к конкретным размерам. Используйте этот конструктор для динамического создания <br/>            изображений WMF с точными размерами, обеспечивая гибкое создание и <br/>            манипуляцию изображениями в вашем приложении. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Получает или задает значение, указывающее, следует ли автоматически корректировать палитру. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает значение цвета фона. |
| bits_per_pixel | int | r | Получите количество бит на пиксель изображения, указывающее уровень цветовой <br/>            глубины или гранулярности. Используйте это свойство для определения цветового представления и точности изображения, облегчая проверку совместимости и обработку, связанной с цветом, в вашем приложении. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Получает границы объекта. |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Получает контейнер [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Получает поток данных объекта. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задаёт экземпляр Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Получите значение формата файла, связанное с изображением, предоставляя информацию <br/> о формате, в котором хранится изображение. Используйте это свойство для определения <br/> формата файла изображения, облегчая проверки совместимости и <br/> специфическую для формата обработку в вашем приложении. |
| frame_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Получите границы кадра, указывающие его положение и размеры внутри <br/>            изображения. Используйте это свойство для получения подробной информации о пространственном расположении кадра, позволяя точную манипуляцию и рендеринг в вашем приложении. |
| has_background_color | bool | r/w | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| height | int | r | Получает высоту объекта. |
| height_f | float | r | Получите высоту изображения, представляющую количество пикселей по его вертикальной <br/>            оси. Используйте это свойство для определения пространственных размеров и соотношения сторон изображения, обеспечивая точную настройку макета и рендеринга в вашем приложении. |
| дюйм | int | r/w | Получите или измените свойство дюйм, представляющее единицу измерения, обычно <br/>            используемую для указания физических размеров при печати или отображении. Используйте это <br/>            свойство для установки или получения значений дюймов, связанных с изображением, <br/>            обеспечивая точное представление физических размеров в вашем приложении. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Получает или задает монитор прерываний. |
| is_cached | bool | r | Получите логическое значение, указывающее, кэшированы ли данные объекта в данный момент, <br/>            устраняя необходимость дополнительных операций чтения данных. Используйте это свойство <br/>            для оптимизации производительности, определяя, доступны ли данные объекта сразу <br/>            без необходимости затратных процессов получения данных в вашем приложении. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Получает метаданные изображения. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| records | [MetaObjectList](/imaging/python-net/aspose.imaging.fileformats.emf/metaobjectlist/) | r/w | Получает или задает записи. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Получает размер объекта. |
| size_f | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Получает размер объекта в дюймах. |
| use_palette | bool | r | Получает значение, указывающее, используется ли палитра изображения. |
| width | int | r | Получает ширину объекта. |
| width_f | float | r | Получите ширину изображения, указывающую количество пикселей по его <br/>            горизонтальной оси. Используйте это свойство для определения пространственных размеров <br/>            и соотношения сторон изображения, обеспечивая точную настройку макета и рендеринга в вашем <br/>            приложении. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Получает или задает данные Xmp. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_record(record)](#add_record_record_1) | Включите указанный объект записи в изображение, обогащая его содержимое <br/>            дополнительными данными или метаданными. Используйте этот метод для бесшовной интеграции объектов записи <br/>            в изображение, облегчая комплексное хранение и организацию данных в вашем приложении. |
| cache_data() | Эффективно кэшируйте данные, устраняя необходимость дополнительной загрузки из <br/>            базового [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). Используйте этот <br/>            метод для оптимизации производительности и снижения использования ресурсов в вашем приложении <br/>            путем хранения и доступа к локальному кэшу данных. |
| [can_load(file_path)](#can_load_file_path_2) | Определяет, можно ли загрузить изображение из указанного пути к файлу. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_3) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [can_load(stream)](#can_load_stream_4) | Определяет, можно ли загрузить изображение из указанного потока. |
| [can_load(stream, load_options)](#can_load_stream_load_options_5) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_6) | Определяет, можно ли загрузить изображение из указанного потока. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_7) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_8) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [can_save(options)](#can_save_options_9) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| [create(files)](#create_files_10) | Создаёт многостраничное изображение, содержащее указанные файлы. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_11) | Создаёт многостраничное изображение, содержащее указанные файлы. |
| [create(image_options, width, height)](#create_image_options_width_height_12) | Создаёт новое изображение с использованием указанных параметров создания. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_13) | Создаёт экземпляр [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) из предоставленного массива пикселей.<br/> <br/> Проверяет, что указанные ширина и высота соответствуют размерам пиксельных данных.<br/> Этот метод может использоваться только в лицензированном режиме библиотеки. |
| [create(images)](#create_images_14) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create(images, dispose_images)](#create_images_dispose_images_15) | Создает новое изображение из указанных изображений в виде страниц. |
| [create(multipage_create_options)](#create_multipage_create_options_16) | Создает указанные параметры создания многостраничного изображения. |
| [create_from_files(files)](#create_from_files_files_17) | Создает многостраничное изображение, содержащее указанные файлы в виде страниц с отложенной загрузкой. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_18) | Создает многостраничное изображение, содержащее указанные файлы в виде страниц с отложенной загрузкой. |
| [create_from_images(images)](#create_from_images_images_19) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_20) | Создает новое изображение из указанных изображений в виде страниц. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_21) | Обрезать изображение со смещениями. |
| [crop(rectangle)](#crop_rectangle_22) | Обрезает указанный прямоугольник. |
| [get_default_options(args)](#get_default_options_args_23) | Получает параметры изображения по умолчанию. |
| [get_embedded_images()](#get_embedded_images__24) | Получает встроенные изображения. |
| [get_file_format(file_path)](#get_file_format_file_path_25) | Получает формат файла. |
| [get_file_format(stream)](#get_file_format_stream_26) | Получает формат файла. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_27) | Получает формат файла. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_28) | Получает прямоугольник, соответствующий текущему изображению. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_29) | Получает прямоугольник, соответствующий текущему изображению. |
| [get_missed_fonts()](#get_missed_fonts__30) | Возвращает список шрифтов, использованных внутри метафайла, но не найденных. |
| [get_original_options()](#get_original_options__31) | Получает исходные параметры изображения. |
| [get_post_script()](#get_post_script__32) | Получить данные PostScript, связанные с изображением, предоставляя подробную <br/>            информацию о его структуре или содержимом. Используйте этот метод для получения <br/>            данных PostScript для дальнейшего анализа или обработки в вашем приложении, <br/>            позволяя использовать расширенные возможности, связанные с рендерингом или манипуляцией PostScript. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_33) | Получает пропорциональную высоту. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_34) | Получает пропорциональную ширину. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_35) | Преобразует в aps. |
| [get_used_fonts()](#get_used_fonts__36) | Получить список шрифтов, использованных в метафайле, предоставляя информацию о <br/>            ресурсах шрифтов, используемых в изображении. Используйте этот метод для анализа использования шрифтов <br/>            и обеспечения их доступности для рендеринга или дальнейшей обработки в вашем приложении. |
| [load(file_path)](#load_file_path_37) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| [load(file_path, load_options)](#load_file_path_load_options_38) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| [load(stream)](#load_stream_39) | Загружает новое изображение из указанного потока. |
| [load(stream, load_options)](#load_stream_load_options_40) | Загружает новое изображение из указанного потока. |
| [load_stream(stream)](#load_stream_stream_41) | Загружает новое изображение из указанного потока. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_42) | Загружает новое изображение из указанного потока. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_43) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| remove_background() | Удаляет фон. |
| [remove_background(settings)](#remove_background_settings_44) | Удаляет фон. |
| remove_metadata() | Удаляет метаданные. |
| [resize(new_width, new_height)](#resize_new_width_new_height_45) | Изменяет размер изображения. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_46) | Изменяет размер до указанной новой ширины. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_47) | Изменяет размер изображения с расширенными параметрами. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_48) | Изменяет размер изображения. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_49) | Изменяет размер изображения. |
| [resize_canvas(new_rectangle)](#resize_canvas_new_rectangle_50) | Изменить размер холста изображения, корректируя его размеры, сохраняя содержимое изображения <br/>            . Используйте этот метод для изменения размеров холста без изменения <br/>            содержимого, облегчая настройку макета и изменения композиции в вашем <br/>            приложении. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_51) | Пропорционально изменяет высоту. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_52) | Пропорционально изменяет высоту. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_53) | Пропорционально изменяет высоту. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_54) | Пропорционально изменяет высоту. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_55) | Пропорционально изменяет ширину. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_56) | Пропорционально изменяет ширину. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_57) | Пропорционально изменяет ширину. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_58) | Пропорционально изменяет ширину. |
| [rotate(angle)](#rotate_angle_59) | Повернуть изображение вокруг центра. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_60) | Вращает, отражает или вращает и отражает изображение. |
| save() | Сохраняет данные изображения в базовый поток. |
| [save(file_path)](#save_file_path_61) | Сохраняет изображение в указанное расположение файла. |
| [save(file_path, options)](#save_file_path_options_62) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_63) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save(file_path, over_write)](#save_file_path_over_write_64) | Сохраняет данные объекта в указанное расположение файла. |
| [save(stream)](#save_stream_65) | Сохраняет данные в указанный _stream_. |
| [save(stream, options_base)](#save_stream_options_base_66) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_67) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_to_stream(stream)](#save_to_stream_stream_68) | Сохраняет данные объекта в указанный поток. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_69) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_70) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_71) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_72) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | Применить указанную палитру к изображению, позволяя настраивать представление цветов <br/>            . Используйте этот метод для улучшения визуального рендеринга и достижения <br/>            определённых цветовых эффектов в вашем приложении. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_74) | Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Constructor: WmfImage() {#WmfImage__1}


```
 WmfImage() 
```

Создайте новый экземпляр класса [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/), инициализируя его для <br/>            дальнейшей манипуляции и обработки данных изображений Windows Metafile (WMF). Этот <br/>            конструктор предоставляет базовый объект для работы с изображениями WMF, позволяя <br/>            бесшовную интеграцию возможностей обработки изображений WMF в функциональность вашего приложения.

### Constructor: WmfImage(width, height) {#WmfImage_width_height_2}


```
 WmfImage(width, height) 
```

Создайте новый экземпляр класса [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/) с настраиваемыми <br/>            параметрами ширины и высоты, облегчая создание пустых изображений WMF, адаптированных к конкретным размерам. Используйте этот конструктор для динамического создания <br/>            изображений WMF с точными размерами, обеспечивая гибкое создание и <br/>            манипуляцию изображениями в вашем приложении.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина. |
| height | int | Высота. |

### Method: add_record(record) {#add_record_record_1}


```
 add_record(record) 
```

Включите указанный объект записи в изображение, обогащая его содержимое <br/>            дополнительными данными или метаданными. Используйте этот метод для бесшовной интеграции объектов записи <br/>            в изображение, облегчая комплексное хранение и организацию данных в вашем приложении.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| record | [WmfObject](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfobject/) | Запись. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Количество записей. |


### Method: can_load(file_path)  [static] {#can_load_file_path_2}


```
 can_load(file_path) 
```

Определяет, можно ли загрузить изображение из указанного пути к файлу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного файла; в противном случае <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_3}


```
 can_load(file_path, load_options) 
```

Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного файла; в противном случае <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_4}


```
 can_load(stream) 
```

Определяет, можно ли загрузить изображение из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного потока; в противном случае <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_5}


```
 can_load(stream, load_options) 
```

Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного потока; в противном случае <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_6}


```
 can_load_stream(stream) 
```

Определяет, можно ли загрузить изображение из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного потока; в противном случае <c>false</c>. |


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_7}


```
 can_load_stream_with_options(stream, load_options) 
```

Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного потока; в противном случае <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_8}


```
 can_load_with_options(file_path, load_options) 
```

Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного файла; в противном случае <c>false</c>. |


### Method: can_save(options) {#can_save_options_9}


```
 can_save(options) 
```

Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры сохранения, которые следует использовать. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть сохранено в указанный формат файла, представленный переданными параметрами сохранения; в противном случае <c>false</c>. |


### Method: create(files)  [static] {#create_files_10}


```
 create(files) 
```

Создаёт многостраничное изображение, содержащее указанные файлы.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| файлы | string[] | Файлы. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Многостраничное изображение |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_11}


```
 create(files, throw_exception_on_load_error) 
```

Создаёт многостраничное изображение, содержащее указанные файлы.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| файлы | string[] | Файлы. |
| throw_exception_on_load_error | bool | если установлено <c>true</c> [выбросить исключение при ошибке загрузки]. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Многостраничное изображение |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_12}


```
 create(image_options, width, height) 
```

Создаёт новое изображение с использованием указанных параметров создания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры изображения. |
| width | int | Ширина. |
| height | int | Высота. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Новосозданное изображение. |


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_13}


```
 create(image_options, width, height, pixels) 
```

Создаёт экземпляр [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) из предоставленного массива пикселей.<br/> <br/> Проверяет, что указанные ширина и высота соответствуют размерам пиксельных данных.<br/> Этот метод может использоваться только в лицензированном режиме библиотеки.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры, используемые для создания [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | Ширина [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| height | int | Высота [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| пиксели | int[] | Массив значений пикселей, используемый для заполнения изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Объект [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) заполненный предоставленными данными пикселей. |


### Method: create(images)  [static] {#create_images_14}


```
 create(images) 
```

Создаёт новое изображение, используя указанные изображения в качестве страниц

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Изображение как IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_15}


```
 create(images, dispose_images) 
```

Создает новое изображение из указанных изображений в виде страниц.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Изображения. |
| dispose_images | bool | если установлено <c>true</c> [освободить изображения]. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Изображение как IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_16}


```
 create(multipage_create_options) 
```

Создает указанные параметры создания многостраничного изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | Параметры создания многостраничного изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Многостраничное изображение |


### Method: create_from_files(files)  [static] {#create_from_files_files_17}


```
 create_from_files(files) 
```

Создает многостраничное изображение, содержащее указанные файлы в виде страниц с отложенной загрузкой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| файлы | string[] | Файлы. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Многостраничное изображение |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_18}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Создает многостраничное изображение, содержащее указанные файлы в виде страниц с отложенной загрузкой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| файлы | string[] | Файлы. |
| throw_exception_on_load_error | bool | если установлено <c>true</c> выбросить исключение при ошибке загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Многостраничное изображение |


### Method: create_from_images(images)  [static] {#create_from_images_images_19}


```
 create_from_images(images) 
```

Создаёт новое изображение, используя указанные изображения в качестве страниц

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Изображение как IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_20}


```
 create_from_images(images, dispose_images) 
```

Создает новое изображение из указанных изображений в виде страниц.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Изображения. |
| dispose_images | bool | если установлено <c>true</c> [освободить изображения]. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Изображение как IMultipageImage |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_21}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Обрезать изображение со смещениями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| left_shift | int | Сдвиг влево. |
| right_shift | int | Сдвиг вправо. |
| top_shift | int | Сдвиг вверх. |
| bottom_shift | int | Сдвиг вниз. |

### Method: crop(rectangle) {#crop_rectangle_22}


```
 crop(rectangle) 
```

Обрезает указанный прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |

### Method: get_default_options(args) {#get_default_options_args_23}


```
 get_default_options(args) 
```

Получает параметры изображения по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| args | System.Object | Аргументы. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры изображения по умолчанию. |


### Method: get_embedded_images() {#get_embedded_images__24}


```
 get_embedded_images() 
```

Получает встроенные изображения.

**Returns**

| Тип | Описание |
| :- | :- |
| [EmbeddedImage[]](/imaging/python-net/aspose.imaging/embeddedimage/) | Массив изображений |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


```
 get_file_format(file_path) 
```

Получает формат файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Определённый формат файла. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


```
 get_file_format(stream) 
```

Получает формат файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Определённый формат файла. |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_27}


```
 get_file_format_of_stream(stream) 
```

Получает формат файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Определённый формат файла. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_28}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Получает прямоугольник, соответствующий текущему изображению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, для которого определяется подходящий прямоугольник. |
| пиксели | int[] | 32‑битные ARGB пиксели. |
| width | int | Ширина объекта. |
| height | int | Высота объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Подходящий прямоугольник или исключение, если подходящий прямоугольник не найден. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_29}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Получает прямоугольник, соответствующий текущему изображению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, для которого определяется подходящий прямоугольник. |
| width | int | Ширина объекта. |
| height | int | Высота объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Подходящий прямоугольник или исключение, если подходящий прямоугольник не найден. |


### Method: get_missed_fonts() {#get_missed_fonts__30}


```
 get_missed_fonts() 
```

Возвращает список шрифтов, использованных внутри метафайла, но не найденных.

**Returns**

| Тип | Описание |
| :- | :- |
| string[] | Список шрифтов |


### Method: get_original_options() {#get_original_options__31}


```
 get_original_options() 
```

Получает исходные параметры изображения.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Исходные параметры изображения. |


### Method: get_post_script() {#get_post_script__32}


```
 get_post_script() 
```

Получить данные PostScript, связанные с изображением, предоставляя подробную <br/>            информацию о его структуре или содержимом. Используйте этот метод для получения <br/>            данных PostScript для дальнейшего анализа или обработки в вашем приложении, <br/>            позволяя использовать расширенные возможности, связанные с рендерингом или манипуляцией PostScript.

**Returns**

| Тип | Описание |
| :- | :- |
| string | PostScript |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_33}


```
 get_proportional_height(width, height, new_width) 
```

Получает пропорциональную высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина. |
| height | int | Высота. |
| new_width | int | Новая ширина. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Пропорциональная высота. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_34}


```
 get_proportional_width(width, height, new_height) 
```

Получает пропорциональную ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина. |
| height | int | Высота. |
| new_height | int | Новая высота. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Пропорциональная ширина. |


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_35}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

Преобразует в aps.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры изображения. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник обрезки. |
| page_number | int[] | Номер страницы. |

**Returns**

| Тип | Описание |
| :- | :- |
| _io.BufferedRandom | Сериализованный поток |


### Method: get_used_fonts() {#get_used_fonts__36}


```
 get_used_fonts() 
```

Получить список шрифтов, использованных в метафайле, предоставляя информацию о <br/>            ресурсах шрифтов, используемых в изображении. Используйте этот метод для анализа использования шрифтов <br/>            и обеспечения их доступности для рендеринга или дальнейшей обработки в вашем приложении.

**Returns**

| Тип | Описание |
| :- | :- |
| string[] | Список шрифтов |


### Method: load(file_path)  [static] {#load_file_path_37}


```
 load(file_path) 
```

Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу или URL для загрузки изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Загруженное изображение. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_38}


```
 load(file_path, load_options) 
```

Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу или URL для загрузки изображения. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Загруженное изображение. |


### Method: load(stream)  [static] {#load_stream_39}


```
 load(stream) 
```

Загружает новое изображение из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для загрузки изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Загруженное изображение. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_40}


```
 load(stream, load_options) 
```

Загружает новое изображение из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для загрузки изображения. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Загруженное изображение. |


### Method: load_stream(stream)  [static] {#load_stream_stream_41}


```
 load_stream(stream) 
```

Загружает новое изображение из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для загрузки изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Загруженное изображение. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_42}


```
 load_stream_with_options(stream, load_options) 
```

Загружает новое изображение из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для загрузки изображения. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Загруженное изображение. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_43}


```
 load_with_options(file_path, load_options) 
```

Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу или URL для загрузки изображения. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Загруженное изображение. |


### Method: remove_background(settings) {#remove_background_settings_44}


```
 remove_background(settings) 
```

Удаляет фон.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| settings | [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Настройки. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_45}


```
 resize(new_width, new_height) 
```

Изменяет размер изображения. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_46}


```
 resize(new_width, new_height, resize_type) 
```

Изменяет размер до указанной новой ширины.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_47}


```
 resize(new_width, new_height, settings) 
```

Изменяет размер изображения с расширенными параметрами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The resize settings. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_48}


```
 resize_by_settings(new_width, new_height, settings) 
```

Изменяет размер изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The resize settings. |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_49}


```
 resize_by_type(new_width, new_height, resize_type) 
```

Изменяет размер изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize_canvas(new_rectangle) {#resize_canvas_new_rectangle_50}


```
 resize_canvas(new_rectangle) 
```

Изменить размер холста изображения, корректируя его размеры, сохраняя содержимое изображения <br/>            . Используйте этот метод для изменения размеров холста без изменения <br/>            содержимого, облегчая настройку макета и изменения композиции в вашем <br/>            приложении.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Новый прямоугольник. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_51}


```
 resize_height_proportionally(new_height) 
```

Пропорционально изменяет высоту. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_52}


```
 resize_height_proportionally(new_height, resize_type) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_53}


```
 resize_height_proportionally(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_54}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_55}


```
 resize_width_proportionally(new_width) 
```

Пропорционально изменяет ширину. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_56}


```
 resize_width_proportionally(new_width, resize_type) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_57}


```
 resize_width_proportionally(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_58}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_59}


```
 rotate(angle) 
```

Повернуть изображение вокруг центра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_60}


```
 rotate_flip(rotate_flip_type) 
```

Вращает, отражает или вращает и отражает изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Тип поворота и отражения. |

### Method: save(file_path) {#save_file_path_61}


```
 save(file_path) 
```

Сохраняет изображение в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_62}


```
 save(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_63}


```
 save(file_path, options, bounds_rectangle) 
```

Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### Method: save(file_path, over_write) {#save_file_path_over_write_64}


```
 save(file_path, over_write) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | если установлено <c>true</c>, перезаписать содержимое файла, иначе будет выполнено добавление. |

### Method: save(stream) {#save_stream_65}


```
 save(stream) 
```

Сохраняет данные в указанный _stream_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

### Method: save(stream, options_base) {#save_stream_options_base_66}


```
 save(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_67}


```
 save(stream, options_base, bounds_rectangle) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### Method: save_to_stream(stream) {#save_to_stream_stream_68}


```
 save_to_stream(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, в который сохраняются данные объекта. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_69}


```
 save_to_stream_with_options(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_70}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_71}


```
 save_with_options(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_72}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

Применить указанную палитру к изображению, позволяя настраивать представление цветов <br/>            . Используйте этот метод для улучшения визуального рендеринга и достижения <br/>            определённых цветовых эффектов в вашем приложении.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Палитра для установки. |
| update_colors | bool | если установить в <c>true</c>, цвета будут обновлены в соответствии с новой палитрой; иначе индексы цветов останутся без изменений.<br/>
                Обратите внимание, что неизменённые индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют<br/>
                соответствующих записей в палитре. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_74}


```
 try_set_metadata(metadata) 
```

Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Метаданные. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Истина, если _metadata_ не равно null и экземпляр [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) <br/> поддерживает и/или реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); в противном случае — ложь. |


## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Использование Aspose.Imaging.Image.Load — единый способ загрузки всех типов изображений, включая WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Текст будет преобразован в фигуры.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# Цвет фона поверхности рисования.
	rasterizationOptions.background_color = Color.white_smoke
	# Размер страницы.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Если встроенный emf существует, то рендерить emf; иначе рендерить wmf.
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

### The following example shows how to convert compressed images (*.emz,*.wmz, *.svgz) to a raster format {#example_190}
``` python
from aspose.imaging import Image, Color
from aspose.imaging.imageoptions import PngOptions, VectorRasterizationOptions
from os.path import join
from aspose.pycore import as_of

files = ["example.emz", "example.wmz", "example.svgz"]
base_folder: str = join("D:", "Compressed")
for file in files:
	input_file: str = join(base_folder, file)
	out_file: str = input_file + ".png"
	with Image.load(input_file) as image:
		vector_rasterization_options = aspycore.as_of(image.get_default_options([Color.white, image.width, image.height]), VectorRasterizationOptions)
		obj_init = PngOptions()
		obj_init.vector_rasterization_options = vector_rasterization_options
		image.save(out_file, obj_init)


```

### The following example shows how to convert a wmz images to wmf fromat {#example_192}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import WmfRasterizationOptions, WmfOptions
from os.path import join

file: str = "example.wmz"
base_folder: str = join("D:", "Compressed")
input_file: str = join(base_folder, file)
out_file: str = input_file + ".wmf"
with Image.load(input_file) as image:
	obj_init = WmfRasterizationOptions()
	obj_init.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = WmfOptions()
	obj_init2.vector_rasterization_options = obj_init
	image.save(out_file, obj_init2)


```

### The following example shows how to convert a wmf images to wmz format {#example_195}
``` python

from os.path import join as path_combine
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import WmfRasterizationOptions, WmfOptions

file = "castle.wmf"
base_folder = path_combine("D:", "Compressed")
input_file = path_combine(base_folder, file)
out_file = input_file + ".wmz"
with Image.load(input_file) as image:
	vector_rasterization_options = WmfRasterizationOptions()
	vector_rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = WmfOptions()
	obj_init2.vector_rasterization_options = vector_rasterization_options
	obj_init2.compress = True
	image.save(out_file, obj_init2)            


```

