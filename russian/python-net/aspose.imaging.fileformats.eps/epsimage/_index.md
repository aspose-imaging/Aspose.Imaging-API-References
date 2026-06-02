---
title: "Класс EpsImage"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.fileformats.eps/epsimage/
---

**Summary:** The API for Encapsulated PostScript (EPS) image file format support offers<br/>            robust capabilities for manipulating compositions comprising text, graphics,<br/>            and images. With features such as bitmap preview image handling, orientation<br/>            flipping, bounding box retrieval for illustration bounds, resizing, rotating<br/>            images, and adding preview images, this API ensures seamless processing<br/>            and integration of EPS files into various applications with precision and<br/>            versatility.

**Module:** [aspose.imaging.fileformats.eps](/imaging/python-net/aspose.imaging.fileformats.eps/)

**Full Name:** aspose.imaging.fileformats.eps.EpsImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IObjectWithSizeF, VectorImage

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Получает или задает значение, указывающее, следует ли автоматически корректировать палитру. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает значение цвета фона. |
| bits_per_pixel | int | r | Получайте точную глубину цвета изображения без усилий с помощью этого свойства. Извлекайте <br/>            количество бит на пиксель, предоставляя важную информацию о глубине цвета изображения <br/>            и помогая оптимизировать задачи обработки. Идеально подходит для приложений, требующих <br/>            тонкого контроля над манипуляцией и анализом изображений. |
| bounding_box | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Получая оригинальный ограничивающий прямоугольник в независимых от устройства точках, это свойство <br/>            предоставляет важную геометрическую информацию о размерах [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/). <br/>            Извлекая эти данные, пользователи могут точно оценить размер изображения и его соотношение сторон <br/>            , облегчая точную компоновку и позиционирование в различных приложениях. |
| bounding_box_px | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Это свойство возвращает оригинальный ограничивающий прямоугольник [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/) <br/>            экземпляра в пикселях, предоставляя важные геометрические данные для точного рендеринга и <br/>            манипуляций. С этой информацией пользователи могут обеспечить точное размещение и масштабирование /// EPS‑изображений в своих проектах, улучшая общую визуальную презентацию и качество. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Получает границы объекта. |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Получает контейнер [Image](/imaging/python-net/aspose.imaging/image/). |
| creation_date | System.DateTime | r | Извлекая дату создания из комментариев EPS Document Structuring Conventions (DSC) <br/>            это свойство предоставляет важные метаданные, указывающие на момент появления EPS‑файла. Получая эту информацию, пользователи получают представление о происхождении и хронологии файла, улучшая управление и организацию файлов. |
| creator | string | r | Это свойство предоставляет доступ к информации о создателе, полученной из EPS Document <br/>            Structuring Conventions (DSC) комментариев, найденных в файле EPS. Понимание деталей создателя <br/>            предоставляет сведения о программном обеспечении или инструменте, использованном для создания <br/>            файла EPS, облегчая оценку совместимости на различных платформах и <br/>            приложениях. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Получает поток данных объекта. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| eps_type | [EpsType](/imaging/python-net/aspose.imaging.fileformats.eps.consts/epstype/) | r | Получайте доступ и интерпретируйте значение подтипа вашего EPS‑изображения, оптимизируя ваш <br/>            рабочий процесс и повышая совместимость на разных платформах. Идеально подходит для оптимизации получения подтипа EPS <br/>            в ваших проектах с точностью и эффективностью. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задаёт экземпляр Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Получайте формат файла вашего изображения с помощью этого свойства. Извлекайте важную <br/>            информацию о формате файла изображения, обеспечивая совместимость и <br/>            эффективную обработку. Идеально подходит для определения формата файлов изображений для <br/>            бесшовной интеграции в ваши проекты. |
| has_background_color | bool | r/w | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| has_raster_preview | bool | r | Легко определяйте наличие растрового превью с помощью этого свойства. Получайте <br/>            логическое значение, указывающее, содержит ли экземпляр [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/) растровое превью, упрощая задачи обработки изображений с ясностью и эффективностью. <br/>            Идеально подходит для оптимизации решений рабочего процесса на основе наличия или отсутствия <br/>            растровых превью в EPS‑изображениях. |
| height | int | r | Получает высоту изображения. |
| height_f | float | r | Получайте высоту изображения с помощью этого свойства. Получайте высоту изображения <br/>            без труда, позволяя бесшовно настраивать макет, вычислять соотношения сторон и точно <br/>            отображать его на разных разрешениях экранов и в различных средах отображения. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Получает или задает монитор прерываний. |
| is_cached | bool | r | Это свойство предоставляет удобный способ проверить, кэшированы ли данные объекта в данный момент <br/>            , устраняя необходимость дополнительного чтения данных. Оно предлагает быстрый и <br/>            эффективный метод определить, доступна ли необходимая информация, <br/>            оптимизируя производительность и снижая нагрузку на ресурсы в операциях с большими объёмами данных. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Получает метаданные изображения. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| post_script_version | string | r | Это свойство получает версию PostScript, связанную с<br/>            [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/) экземпляром. Оно предоставляет сведения о конкретной версии языка PostScript, используемой в файле EPS, помогая оценить совместимость <br/>            и обеспечивая бесшовную интеграцию с PostScript‑совместимыми средами. |
| preview_image_count | int | r | Получайте количество доступных превью‑изображений без труда. Это свойство позволяет вам <br/>            без усилий получить количество превью‑изображений, связанных с вашим файлом, <br/>            обеспечивая эффективное управление и навигацию по превью изображений. Идеально подходит для <br/>            оптимизации вашего рабочего процесса и эффективной организации ваших графических ресурсов. |
| preview_images | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Получайте превью‑изображения, связанные с вашим файлом. Это свойство обеспечивает <br/>            бесшовный доступ к коллекции превью‑изображений, позволяя эффективно <br/>            просматривать и управлять ими по мере необходимости. Идеально подходит для быстрого просмотра и выбора <br/>            подходящего изображения для вашего проекта. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Получает размер объекта. |
| size_f | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Получает размер объекта в дюймах. |
| title | string | r | Это свойство получает заголовок, извлечённый из EPS Document Structuring <br/>            Conventions (DSC), встроенных в файл EPS. Оно предоставляет ценную <br/>            метаданные о содержимом файла EPS, способствуя организации документов и <br/>            их идентификации в совместимых программных приложениях. |
| use_palette | bool | r | Получает значение, указывающее, используется ли палитра изображения. |
| width | int | r | Получает ширину изображения. |
| width_f | float | r | Получайте ширину изображения с помощью этого удобного свойства. Легко получайте ширину изображения <br/>            без усилий, облегчая точные расчёты макета, операции масштабирования и задачи, связанные с размерами, в вашем приложении. Идеально подходит для обеспечения точного <br/>            отображения и вывода изображений на различных платформах и устройствах. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Получает или задает данные Xmp. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | Этот метод ничего не делает, поскольку текущая реализация класса<br/>            [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/) не использует кэширование данных. Хотя он может не <br/>            выполнять никаких действий, понимание этого поведения критически важно для разработчиков, работающих <br/>            с EPS‑изображениями, обеспечивая эффективное управление ресурсами и оптимальную производительность <br/>            их приложений. |
| [can_load(file_path)](#can_load_file_path_1) | Определяет, можно ли загрузить изображение из указанного пути к файлу. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [can_load(stream)](#can_load_stream_3) | Определяет, можно ли загрузить изображение из указанного потока. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_5) | Определяет, можно ли загрузить изображение из указанного потока. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_6) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_7) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [can_save(options)](#can_save_options_8) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| [create(files)](#create_files_9) | Создаёт многостраничное изображение, содержащее указанные файлы. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_10) | Создаёт многостраничное изображение, содержащее указанные файлы. |
| [create(image_options, width, height)](#create_image_options_width_height_11) | Создаёт новое изображение с использованием указанных параметров создания. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_12) | Создаёт экземпляр [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) из предоставленного массива пикселей.<br/> <br/> Проверяет, что указанные ширина и высота соответствуют размерам пиксельных данных.<br/> Этот метод может использоваться только в лицензированном режиме библиотеки. |
| [create(images)](#create_images_13) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create(images, dispose_images)](#create_images_dispose_images_14) | Создает новое изображение из указанных изображений в виде страниц. |
| [create(multipage_create_options)](#create_multipage_create_options_15) | Создает указанные параметры создания многостраничного изображения. |
| [create_from_files(files)](#create_from_files_files_16) | Создает многостраничное изображение, содержащее указанные файлы в виде страниц с отложенной загрузкой. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_17) | Создает многостраничное изображение, содержащее указанные файлы в виде страниц с отложенной загрузкой. |
| [create_from_images(images)](#create_from_images_images_18) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_19) | Создает новое изображение из указанных изображений в виде страниц. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_20) | Обрезать изображение со смещениями. |
| [crop(rectangle)](#crop_rectangle_21) | Обрезает указанный прямоугольник. |
| [get_default_options(args)](#get_default_options_args_22) | Получает параметры изображения по умолчанию. |
| [get_embedded_images()](#get_embedded_images__23) | Получает встроенные изображения. |
| [get_file_format(file_path)](#get_file_format_file_path_24) | Получает формат файла. |
| [get_file_format(stream)](#get_file_format_stream_25) | Получает формат файла. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_26) | Получает формат файла. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Получает прямоугольник, соответствующий текущему изображению. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Получает прямоугольник, соответствующий текущему изображению. |
| [get_original_options()](#get_original_options__29) | Получает параметры на основе настроек оригинального файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений.<br/>            Например, если мы загружаем черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) метода, будет получено PNG‑изображение с 8‑битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            в метод [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) в качестве второго параметра. |
| [get_preview_image(format)](#get_preview_image_format_30) | Получает существующее превью‑изображение в указанном _format_ или <br/>            возвращает **None**, если оно не найдено. Этот метод обеспечивает гибкость при <br/>            доступе к превью‑изображениям, адаптированным к конкретным форматам, оптимизируя совместимость и <br/>            управление ресурсами в приложениях. |
| [get_preview_images()](#get_preview_images__31) | Получает доступ к превью‑изображениям, связанным с экземпляром [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/), позволяя <br/>            бесшовно извлекать их для проверки или использования в приложениях. Этот метод <br/>            обеспечивает удобный доступ к превью‑изображениям, улучшая взаимодействие пользователя с <br/>            данными изображения. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | Получает пропорциональную высоту. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | Получает пропорциональную ширину. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_34) | Преобразует в aps. |
| [load(file_path)](#load_file_path_35) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| [load(stream)](#load_stream_37) | Загружает новое изображение из указанного потока. |
| [load(stream, load_options)](#load_stream_load_options_38) | Загружает новое изображение из указанного потока. |
| [load_stream(stream)](#load_stream_stream_39) | Загружает новое изображение из указанного потока. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_40) | Загружает новое изображение из указанного потока. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_41) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| remove_background() | Удаляет фон. |
| [remove_background(settings)](#remove_background_settings_42) | Удаляет фон. |
| remove_metadata() | Удаляет метаданные. |
| [resize(new_width, new_height)](#resize_new_width_new_height_43) | Изменяет размер изображения. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_44) | Изменяет размер до указанной новой ширины. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_45) | Изменяет размер изображения с расширенными параметрами. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_46) | Изменяет размер изображения. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_47) | Изменяет размер изображения. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_48) | Пропорционально изменяет высоту. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_49) | Пропорционально изменяет высоту. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_50) | Пропорционально изменяет высоту. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_51) | Пропорционально изменяет высоту. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_52) | Пропорционально изменяет ширину. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_53) | Пропорционально изменяет ширину. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_54) | Пропорционально изменяет ширину. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_55) | Пропорционально изменяет ширину. |
| [rotate(angle)](#rotate_angle_56) | Повернуть изображение вокруг центра. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_57) | Вращает, отражает или вращает и отражает изображение. |
| save() | Сохраняет данные изображения в базовый поток. |
| [save(file_path)](#save_file_path_58) | Сохраняет изображение в указанное расположение файла. |
| [save(file_path, options)](#save_file_path_options_59) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_60) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save(file_path, over_write)](#save_file_path_over_write_61) | Сохраняет данные объекта в указанное расположение файла. |
| [save(stream)](#save_stream_62) | Сохраняет данные. |
| [save(stream, options_base)](#save_stream_options_base_63) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_64) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_to_stream(stream)](#save_to_stream_stream_65) | Сохраняет данные объекта в указанный поток. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_66) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_67) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_68) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_69) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_70) | Настраивайте палитры изображений для создания уникальных цветовых схем и улучшения визуальной привлекательности. <br/>            Подбирайте цвета для конкретных эффектов и легко оптимизируйте качество изображений на разных <br/>            платформах и устройствах. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_71) | Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_5}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_6}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_7}


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


### Method: can_save(options) {#can_save_options_8}


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


### Method: create(files)  [static] {#create_files_9}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_10}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_11}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_12}


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


### Method: create(images)  [static] {#create_images_13}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_14}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_15}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_16}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_17}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_18}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_19}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_20}


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

### Method: crop(rectangle) {#crop_rectangle_21}


```
 crop(rectangle) 
```

Обрезает указанный прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |

### Method: get_default_options(args) {#get_default_options_args_22}


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


### Method: get_embedded_images() {#get_embedded_images__23}


```
 get_embedded_images() 
```

Получает встроенные изображения.

**Returns**

| Тип | Описание |
| :- | :- |
| [EmbeddedImage[]](/imaging/python-net/aspose.imaging/embeddedimage/) | Массив изображений |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_24}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_25}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_original_options() {#get_original_options__29}


```
 get_original_options() 
```

Получает параметры на основе настроек оригинального файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений.<br/>            Например, если мы загружаем черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) метода, будет получено PNG‑изображение с 8‑битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            в метод [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) в качестве второго параметра.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры, основанные на настройках исходного файла. |


### Method: get_preview_image(format) {#get_preview_image_format_30}


```
 get_preview_image(format) 
```

Получает существующее превью‑изображение в указанном _format_ или <br/>            возвращает **None**, если оно не найдено. Этот метод обеспечивает гибкость при <br/>            доступе к превью‑изображениям, адаптированным к конкретным форматам, оптимизируя совместимость и <br/>            управление ресурсами в приложениях.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| format | [EpsPreviewFormat](/imaging/python-net/aspose.imaging.fileformats.eps/epspreviewformat/) | Формат превью‑изображения EPS. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Существующее превью‑изображение или **None**. |


### Method: get_preview_images() {#get_preview_images__31}


```
 get_preview_images() 
```

Получает доступ к превью‑изображениям, связанным с экземпляром [EpsImage](/imaging/python-net/aspose.imaging.fileformats.eps/epsimage/), позволяя <br/>            бесшовно извлекать их для проверки или использования в приложениях. Этот метод <br/>            обеспечивает удобный доступ к превью‑изображениям, улучшая взаимодействие пользователя с <br/>            данными изображения.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable`1[[Aspose.Imaging.Image]] | Превью‑изображения. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_34}


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


### Method: load(file_path)  [static] {#load_file_path_35}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


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


### Method: load(stream)  [static] {#load_stream_37}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_39}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_40}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_41}


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


### Method: remove_background(settings) {#remove_background_settings_42}


```
 remove_background(settings) 
```

Удаляет фон.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| settings | [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Настройки. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_43}


```
 resize(new_width, new_height) 
```

Изменяет размер изображения. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_44}


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


**See also:**

**[Example # 1](#example_218)**: Resize EPS image and export it to PNG format.


### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_45}


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


**See also:**

**[Example # 1](#example_219)**: Resize EPS image using advanced settings.


### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_46}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_47}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_48}


```
 resize_height_proportionally(new_height) 
```

Пропорционально изменяет высоту. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_49}


```
 resize_height_proportionally(new_height, resize_type) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_50}


```
 resize_height_proportionally(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_51}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_52}


```
 resize_width_proportionally(new_width) 
```

Пропорционально изменяет ширину. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_53}


```
 resize_width_proportionally(new_width, resize_type) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_54}


```
 resize_width_proportionally(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_55}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_56}


```
 rotate(angle) 
```

Повернуть изображение вокруг центра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_57}


```
 rotate_flip(rotate_flip_type) 
```

Вращает, отражает или вращает и отражает изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Тип поворота и отражения. |

### Method: save(file_path) {#save_file_path_58}


```
 save(file_path) 
```

Сохраняет изображение в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_59}


```
 save(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_60}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_61}


```
 save(file_path, over_write) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | если установлено <c>true</c>, перезаписать содержимое файла, иначе будет выполнено добавление. |

### Method: save(stream) {#save_stream_62}


```
 save(stream) 
```

Сохраняет данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save data to. |

### Method: save(stream, options_base) {#save_stream_options_base_63}


```
 save(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_64}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_65}


```
 save_to_stream(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, в который сохраняются данные объекта. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_66}


```
 save_to_stream_with_options(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_67}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_68}


```
 save_with_options(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_69}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_70}


```
 set_palette(palette, update_colors) 
```

Настраивайте палитры изображений для создания уникальных цветовых схем и улучшения визуальной привлекательности. <br/>            Подбирайте цвета для конкретных эффектов и легко оптимизируйте качество изображений на разных <br/>            платформах и устройствах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Палитра для установки. |
| update_colors | bool | Если установить значение <c>true</c>, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою загрузки изображения, если некоторые индексы не имеют соответствующих записей в палитре. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_71}


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
	# Отрисовка растрового изображения с использованием PostScript
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

# Загрузить EPS‑изображение
with Image.load("AstrixObelix.eps") as image:
	# Изменить размер изображения с использованием метода кубической интерполяции Митчелла
	image.resize(400, 400, ResizeType.MITCHELL)

	# Экспортировать изображение в формат PNG
	image.save("ExportResult.png", PngOptions())


```

### Resize EPS image using advanced settings. {#example_219}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, ImageResizeSettings, ResizeType, ImageFilterType, ColorCompareMethod, ColorQuantizationMethod
from aspose.imaging.imageoptions import PngOptions

#Загрузить EPS‑изображение
with Image.load("AstrixObelix.eps") as image:
	# Изменить размер изображения с использованием расширенных настроек масштабирования
	obj_init = ImageResizeSettings()
	obj_init.mode = ResizeType.LANCZOS_RESAMPLE
	obj_init.filter_type = ImageFilterType.SMALL_RECTANGULAR
	obj_init.color_compare_method = ColorCompareMethod.EUCLIDIAN
	obj_init.color_quantization_method = ColorQuantizationMethod.POPULARITY
	image.resize(400, 400, obj_init)
	# Экспортировать изображение в формат PNG
	image.save("ExportResult.png", PngOptions())


```

