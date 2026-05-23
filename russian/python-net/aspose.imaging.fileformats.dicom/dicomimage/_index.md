---
title: "Класс DicomImage"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.fileformats.dicom/dicomimage/
---

**Summary:** This Class implements Digital Imaging and Communications in Medicine<br/>            (DICOM) raster image format support and offers a comprehensive solution for<br/>            processing DICOM images with precision and flexibility. You can seamlessly<br/>            manipulate image pages, including operations to get, add, or remove pages, and<br/>            control the default and active pages. With capabilities to work with alpha channels,<br/>            embed XMP metadata, resize, rotate, crop, binarize, adjust, apply filters,<br/>            and convert to other raster formats. This API empowers developers to handle<br/>            DICOM images effectively while meeting diverse application requirements in<br/>            medical imaging contexts.

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DicomImage(dicom_options, width, height)](#DicomImage_dicom_options_width_height_1) | Инициализируйте новый экземпляр класса DicomImage без усилий с помощью этого<br/>            конструктора, используя параметры dicomOptions. Идеально для разработчиков, желающих<br/>            быстро и эффективно погрузиться в объекты [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) в своих проектах. |
| [DicomImage(stream)](#DicomImage_stream_2) | Создайте новый экземпляр класса DicomImage, используя параметр потока<br/>            в этом конструкторе. Идеально для разработчиков, ищущих упрощённый способ инициализировать<br/>            объекты [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) из существующих потоков данных в своих проектах. |
| [DicomImage(stream, load_options)](#DicomImage_stream_load_options_3) | Запустите новый экземпляр класса DicomImage плавно, используя параметры потока и<br/>            loadOptions в этом конструкторе. Идеально для разработчиков, желающих быстро и эффективно приступить<br/>            к работе с объектами [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) в своих проектах. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| active_page | [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | r/w | Управляйте активной страницей изображения с помощью этого интуитивного свойства. Идеально для разработчиков,<br/>            желающих динамически переключаться между страницами в многостраничных изображениях, обеспечивая эффективную<br/>            навигацию и обработку. |
| active_page_index | int | r | Получите индекс активной страницы без усилий с помощью этого интуитивного свойства.<br/>            Идеально для разработчиков, желающих быстро получить доступ к текущему индексу страницы в многостраничных<br/>            изображениях, обеспечивая эффективную навигацию и обработку. |
| auto_adjust_palette | bool | r/w | Получает или задает значение, указывающее, следует ли автоматически корректировать палитру. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает значение цвета фона. |
| bits_per_pixel | int | r | Получает количество бит на пиксель изображения. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Получает границы объекта. |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Получает контейнер [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Получает поток данных объекта. |
| dicom_pages | [DicomPage[]](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | r | Получите доступ к страницам изображения с помощью этого интуитивного свойства. Идеально для разработчиков<br/>            желающих взаимодействовать с отдельными страницами изображения, обеспечивая бесшовную<br/>            навигацию и манипуляцию. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задаёт экземпляр Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Получите значение формата файла без усилий с помощью этого интуитивного свойства. Идеально для<br/>            разработчиков, желающих быстрый доступ к формату файла изображения, обеспечивая эффективную<br/>            обработку и работу в зависимости от типа файла. |
| file_info | [DicomImageInfo](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/) | r | Получите ценную информацию заголовка из DICOM‑файла без усилий с помощью этого<br/>            интуитивного свойства. Идеально для разработчиков, желающих быстрый доступ к важным деталям,<br/>            содержащимся в DICOM‑файле, обеспечивая эффективное извлечение данных и анализ. |
| has_alpha | bool | r | Получите информацию о том, имеет ли изображение альфа‑канал, без усилий с помощью этого интуитивного<br/>            свойства. Идеально для разработчиков, желающих определить, содержит ли изображение данные о прозрачности,<br/>            обеспечивая точную работу с данными альфа‑канала в задачах обработки изображений. |
| has_background_color | bool | r/w | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| has_transparent_color | bool | r/w | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| height | int | r | Получает высоту изображения. |
| horizontal_resolution | float | r/w | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Получает непрозрачность этого изображения. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Получает или задает монитор прерываний. |
| is_cached | bool | r | Получает значение, указывающее, кэшируются ли данные изображения в данный момент. |
| is_raw_data_available | bool | r | Получает значение, указывающее, поддерживается ли загрузка необработанных данных. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Получает или задает XMP‑данные из кадра. |
| page_count | int | r | Получите общее количество страниц изображения с помощью этого интуитивного свойства. Идеально для<br/>            разработчиков, желающих быстрый доступ к числу страниц в изображении, обеспечивая<br/>            эффективную навигацию и управление. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Получите доступ к страницам изображения с помощью этого интуитивного свойства. Идеально для разработчиков<br/>            желающих взаимодействовать с отдельными страницами изображения, обеспечивая бесшовную навигацию<br/>            и манипуляцию. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| premultiply_components | bool | r/w | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умножены. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Получает или задает пользовательский конвертер цветов |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает формат необработанных данных. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без конвертации. |
| raw_fallback_index | int | r/w | Получает или задает резервный индекс, используемый, когда индекс палитры выходит за пределы. |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Получает или задает индексированный конвертер цветов |
| raw_line_size | int | r | Получает размер необработанной строки в байтах. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Получает размер объекта. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает прозрачный цвет изображения. |
| update_xmp_data | bool | r/w | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| use_palette | bool | r | Получает значение, указывающее, используется ли палитра изображения. |
| use_raw_data | bool | r/w | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда такая загрузка доступна. |
| vertical_resolution | float | r/w | Получает или задает вертикальное разрешение в пикселях на дюйм для этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Получает ширину изображения. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Получает или задает данные Xmp. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_page()](#add_page__1) | Добавьте новую страницу в конец списка страниц изображения с помощью этого простого метода.<br/>            Идеально подходит для разработчиков, желающих динамически расширять многостраничные изображения, обеспечивая бесшовную<br/>            интеграцию и организацию содержимого изображения. |
| [add_page(page)](#add_page_page_2) | Расширьте свою коллекцию изображений, добавив новую страницу с помощью этого интуитивного метода.<br/>            Идеально подходит для разработчиков, желающих динамически добавлять страницы к многостраничным изображениям,<br/>            обеспечивая бесшовное расширение и организацию содержимого изображения. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Улучшите яркость изображения с помощью регулировки _brightness_,<br/>            параметризованного метода, позволяющего разработчикам точно настраивать светимость изображений.<br/>            Эта удобная функция дает разработчикам возможность бесшовно управлять яркостью изображения,<br/>            предоставляя гибкость и контроль над визуальной эстетикой. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Улучшите контраст [Image](/imaging/python-net/aspose.imaging/image/) с помощью этого удобного метода,<br/> который регулирует различие между светлыми и тёмными областями. Улучшайте визуальную чёткость и<br/> определённость без усилий, предоставляя разработчикам интуитивный контроль над<br/> контрастом изображения для оптимального рендеринга. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Повышайте качество изображения и регулируйте его с помощью гамма‑коррекции, мощной техники<br/> для тонкой настройки визуального вида. Идеально подходит для разработчиков, стремящихся оптимизировать представление изображения, регулировать цветовой баланс и обеспечивать согласованный рендеринг на разных<br/> устройствах и в разных средах. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Добейтесь точной настройки цветов, применяя гамма‑коррекцию независимо<br/> к красному, зелёному и синему компонентам изображения. Этот метод обеспечивает точный<br/> цветовой баланс и оптимальный визуальный результат, удовлетворяя разработчиков, ищущих детальный<br/> контроль над рендерингом изображения и точностью цветов. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | Вычисляет процентное сходство между извлечёнными данными и оригинальным паролем. |
| auto_brightness_contrast() | Выполняет автоматическую адаптивную нормализацию яркости и контраста для всего изображения. |
| auto_rotate() | Автоматически вращает изображение на основе данных ориентации, извлечённых из Exif <br/> метаданных. Этот метод гарантирует, что изображения отображаются в правильной ориентации, <br/> улучшая пользовательский опыт и устраняя необходимость ручных корректировок. Путём <br/> анализа информации Exif изображение вращается соответствующим образом, обеспечивая бесшовный <br/> просмотр на разных платформах и устройствах. Этот автоматизированный процесс вращения <br/> упрощает работу с изображениями и повышает общую удобность, особенно при <br/> работе с большими партиями изображений с различными ориентациями. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном порогировании изображения |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | Бинаризуйте изображения с помощью адаптивного порогового алгоритма Брэдли, используя интегральное<br/> порогирование изображения для повышения производительности. Идеально подходит для разработчиков, желающих<br/> автоматически сегментировать изображения на основе локальных вариаций яркости, обеспечивая<br/> точное обнаружение и извлечение объектов при разных условиях освещения. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | Легко преобразуйте изображение в бинарный формат с помощью заранее заданного порога<br/> используя этот простой метод. Идеально подходит для разработчиков, желающих упростить задачи обработки изображений, сегментируя их на передний план и фон<br/> на основе указанных уровней интенсивности. |
| binarize_otsu() | Примените порог Оцу для бинаризации изображения, автоматически определяя оптимальное<br/> значение порога на основе гистограммы изображения. Идеально подходит для разработчиков, ищущих<br/> надёжный метод сегментации изображений на области переднего плана и фона с<br/> минимальным вмешательством вручную. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | Смешивает этот экземпляр изображения с изображением _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | Смешивает этот экземпляр изображения с изображением _overlay_. |
| cache_data() | Этот метод эффективно кэширует данные, оптимизируя производительность и обеспечивая быстрый доступ<br/> при необходимости. Идеально подходит для разработчиков, стремящихся повысить скорость и эффективность своих<br/> приложений за счёт интеллектуального управления ресурсами данных. |
| [can_load(file_path)](#can_load_file_path_13) | Определяет, можно ли загрузить изображение из указанного пути к файлу. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [can_load(stream)](#can_load_stream_15) | Определяет, можно ли загрузить изображение из указанного потока. |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_17) | Определяет, можно ли загрузить изображение из указанного потока. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [can_save(options)](#can_save_options_20) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| [create(files)](#create_files_21) | Создаёт многостраничное изображение, содержащее указанные файлы. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Создаёт многостраничное изображение, содержащее указанные файлы. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Создаёт новое изображение с использованием указанных параметров создания. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Создаёт экземпляр [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) из предоставленного массива пикселей.<br/> <br/> Проверяет, что указанные ширина и высота соответствуют размерам пиксельных данных.<br/> Этот метод может использоваться только в лицензированном режиме библиотеки. |
| [create(images)](#create_images_25) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Создает новое изображение из указанных изображений в виде страниц. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Создает указанные параметры создания многостраничного изображения. |
| [create_from_files(files)](#create_from_files_files_28) | Создает многостраничное изображение, содержащее указанные файлы в виде страниц с отложенной загрузкой. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | Создает многостраничное изображение, содержащее указанные файлы в виде страниц с отложенной загрузкой. |
| [create_from_images(images)](#create_from_images_images_30) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_31) | Создает новое изображение из указанных изображений в виде страниц. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_32) | Отрегулируйте область обрезки изображения, применяя смещения с помощью этого универсального метода.<br/>            Идеально подходит разработчикам, которым нужен точный контроль над процессом обрезки, гарантируя<br/>            сохранение важных деталей при удалении ненужных элементов. |
| [crop(rectangle)](#crop_rectangle_33) | Обрежьте изображение, чтобы удалить нежелательные области и сосредоточиться на важном содержании с помощью этого<br/>            простого метода. Идеально подходит разработчикам, желающим настроить визуальную композицию<br/>            изображений, гарантируя эффективную передачу желаемого сообщения. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_34) | Выполняет дизеринг текущего изображения. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_35) | Улучшите текущее изображение, применяя эффекты дизеринга с помощью этого простого<br/>            метода. Идеально подходит разработчикам, стремящимся добавить текстуру и глубину изображениям,<br/>            улучшая их визуальное качество и общую привлекательность. |
| [embed_digital_signature(password)](#embed_digital_signature_password_36) | Вставьте цифровую подпись, основанную на предоставленном пароле, в каждую страницу изображения. |
| [filter(rectangle, options)](#filter_rectangle_options_37) | Легко улучшайте отдельные области вашего изображения, применяя фильтры к заданным<br/>            прямоугольникам. Этот метод предоставляет разработчикам точный контроль над<br/>            манипуляцией изображением, позволяя выполнять целенаправленные настройки для достижения желаемых<br/>            визуальных эффектов без труда. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_38) | Получает 32-битный ARGB‑пиксель изображения. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_39) | Получает массив пикселей по умолчанию в формате 32‑бит ARGB. |
| [get_default_options(args)](#get_default_options_args_40) | Получает параметры по умолчанию. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_41) | Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42) | Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_43) | Получает массив необработанных данных по умолчанию. |
| [get_file_format(file_path)](#get_file_format_file_path_44) | Получает формат файла. |
| [get_file_format(stream)](#get_file_format_stream_45) | Получает формат файла. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_46) | Получает формат файла. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Получает прямоугольник, соответствующий текущему изображению. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Получает прямоугольник, соответствующий текущему изображению. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Получает дату и время последнего изменения ресурса изображения. |
| [get_original_options()](#get_original_options__50) | Получает параметры на основе настроек оригинального файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений.<br/>            Например, если мы загружаем черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) метода, будет получено PNG‑изображение с 8‑битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            в метод [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) в качестве второго параметра. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Получает пиксель изображения. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Получает пропорциональную высоту. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Получает пропорциональную ширину. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_54) | Преобразует в aps. |
| [get_skew_angle()](#get_skew_angle__55) | Получает угол наклона.<br/>            Этот метод применим к отсканированным текстовым документам для определения угла наклона при сканировании. |
| grayscale() | Легко преобразовать изображения в их градации серого, упрощая визуальный<br/>            анализ и задачи обработки. Идеально для разработчиков, желающих улучшить четкость изображений,<br/>            снизить сложность и облегчить эффективные алгоритмы, основанные на градациях серого,<br/>            для различных приложений. |
| [insert_page(page_index)](#insert_page_page_index_56) | Вставьте новую страницу в список страниц изображения в указанном индексе с помощью этого интуитивного<br/>            метода. Идеально для разработчиков, желающих точно контролировать расположение страниц в<br/>            многостраничных изображениях, обеспечивая бесшовную организацию и настройку содержимого изображения. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_57) | Выполняет быструю проверку, чтобы определить, подписано ли изображение цифровой подписью, используя предоставленный пароль и пороговое значение. |
| [load(file_path)](#load_file_path_58) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| [load(file_path, load_options)](#load_file_path_load_options_59) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| [load(stream)](#load_stream_60) | Загружает новое изображение из указанного потока. |
| [load(stream, load_options)](#load_stream_load_options_61) | Загружает новое изображение из указанного потока. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_62) | Загружает 32‑битные ARGB‑пиксели. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_63) | Загружает 64‑битные ARGB‑пиксели. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_64) | Загружает пиксели в формате CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_65) | Загружает пиксели в формате CMYK.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66) | Частично загружает 32‑битные ARGB‑пиксели (по блокам). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67) | Частично загружает 64‑битные ARGB‑пиксели пакетами. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_68) | Частично загружает пиксели пакетами. |
| [load_pixels(rectangle)](#load_pixels_rectangle_69) | Загружает пиксели. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70) | Загружает необработанные данные. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71) | Загружает необработанные данные. |
| [load_stream(stream)](#load_stream_stream_72) | Загружает новое изображение из указанного потока. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_73) | Загружает новое изображение из указанного потока. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_74) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| normalize_angle() | Нормализует угол.<br/>            Этот метод применим к отсканированным текстовым документам для устранения наклона сканирования.<br/>            Метод использует функции [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) и [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_75) | Нормализует угол.<br/>            Этот метод применим к отсканированным текстовым документам для устранения наклона сканирования.<br/>            Метод использует функции [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) и [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/). |
| normalize_histogram() | Нормализует гистограмму изображения — корректирует значения пикселей, чтобы использовать весь доступный диапазон. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_76) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_77) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| remove_metadata() | Удаляет метаданные этого экземпляра изображения, устанавливая значение [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) в **None**. |
| [remove_page(page_index)](#remove_page_page_index_78) | Удалите страницу с указанным индексом из списка страниц с помощью этого удобного метода.<br/>            Идеально для разработчиков, желающих точно контролировать управление многостраничными изображениями,<br/>            обеспечивая бесшовную организацию и настройку содержимого изображения. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа‑значение для сохранения плавных краёв.<br/>                Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа‑значение для сохранения плавных краёв.<br/>                Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | Изменяет размер изображения. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | Измените размер изображения, сохраняя его пропорции, с помощью этого удобного метода. Идеально<br/>            для разработчиков, желающих пропорционально изменить размеры изображения, обеспечивая<br/>            согласованность и сохраняя пропорции оригинального содержимого.<br/>            Пропорциональное изменение размера будет масштабировать каждый кадр согласно соотношению _newWidth_/width и _newHeight_/height. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | Отрегулируйте размер вашего изображения с помощью этого простого метода изменения размера. Независимо от того, нужно ли вам<br/>            уменьшить или увеличить изображение, эта функция гарантирует, что ваши требования к изменению размера будут выполнены<br/>            эффективно и точно, что делает её идеальной для разработчиков, ищущих быстрые и простые<br/>            корректировки размеров изображения. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | Изменяет размер изображения. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | Изменяет размер изображения. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_89) | Пропорционально изменяет высоту. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_90) | Отрегулируйте высоту изображения, сохраняя его соотношение сторон, с помощью этого<br/>            удобного метода. Идеально подходит для разработчиков, желающих динамически изменять размер изображений<br/>            при сохранении их пропорций, обеспечивая оптимальное отображение и удобство<br/>            использования в их приложениях. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_91) | Пропорционально изменяет высоту. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_92) | Пропорционально изменяет высоту. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_93) | Измените размер изображения, сохраняя его пропорции, с помощью этого удобного метода. Идеально<br/>            для разработчиков, желающих пропорционально изменить размеры изображения, обеспечивая<br/>            согласованность и сохраняя пропорции оригинального содержимого.<br/>            Пропорциональное изменение размера будет масштабировать каждый кадр согласно соотношению _newWidth_/width и _newHeight_/height. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_94) | Пропорционально изменяет ширину. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_95) | Отрегулируйте ширину изображения, сохраняя его соотношение сторон, с помощью этого удобного<br/>            метода. Идеально подходит для разработчиков, желающих пропорционально изменять размер изображений, обеспечивая<br/>            согласованные и визуально привлекательные результаты в разных средах отображения. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_96) | Пропорционально изменяет ширину. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_97) | Пропорционально изменяет ширину. |
| [rotate(angle)](#rotate_angle_98) | Повернуть изображение вокруг центра. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_99) | Поверните изображение вокруг его центра с помощью этого удобного метода. Идеально подходит для разработчиков<br/>            желающих динамически регулировать ориентацию изображения, обеспечивая оптимальное представление и<br/>            выравнивание в их приложениях. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_100) | Легко манипулируйте активным кадром, вращая, отражая или выполняя оба действия<br/>            одновременно с помощью этого простого метода. Идеально подходит для разработчиков, которым необходимо<br/>            динамически регулировать ориентацию конкретных кадров в их последовательностях изображений,<br/>            обеспечивая оптимальное представление и выравнивание. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_101) | Выполняет вращение и отражение всех. |
| save() | Сохраняет данные изображения в базовый поток. |
| [save(file_path)](#save_file_path_102) | Сохраняет изображение в указанное расположение файла. |
| [save(file_path, options)](#save_file_path_options_103) | Сохраняет данные объекта, записывая их в назначенный файл (индексатор + имя файла)<br/>            в указанном месте вместе с заданным форматом файла и параметрами. Идеально подходит для разработчиков, желающих<br/>            безопасно хранить данные в различных форматах, сохраняя гибкость и контроль над<br/>            параметрами сохранения. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_104) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save(file_path, over_write)](#save_file_path_over_write_105) | Сохраняет данные объекта в указанное расположение файла. |
| [save(stream)](#save_stream_106) | Сохраняет данные. |
| [save(stream, options_base)](#save_stream_options_base_107) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_108) | Легко сохраняйте данные вашего изображения в указанный поток в нужном формате файла<br/>            с помощью этого удобного метода. Независимо от того, работаете ли вы с JPEG, PNG или другим форматом,<br/>            эта функция гарантирует эффективное и точное сохранение данных изображения,<br/>            делая её идеальной для разработчиков, желающих оптимизировать процессы сохранения файлов. |
| [save_all(file_path, options)](#save_all_file_path_options_109) | Сохраняет данные объекта, записывая их в назначенный файл (индексатор + имя файла)<br/>            в указанном месте вместе с заданным форматом файла и параметрами. Идеально подходит для разработчиков, желающих<br/>            безопасно хранить данные в различных форматах, сохраняя гибкость и контроль над<br/>            параметрами сохранения. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_110) | Сохраняет 32-битные ARGB‑пиксели. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_111) | Сохраняет пиксели. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_112) | Сохраняет пиксели.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_113) | Сохраняет пиксели (метод, специфичный для формата). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_114) | Сохраняет необработанные данные. |
| [save_to_stream(stream)](#save_to_stream_stream_115) | Сохраняет данные объекта в указанный поток. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_116) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_118) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_119) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_120) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_121) | Устанавливает палитру изображения. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_122) | Устанавливает пиксель изображения для указанной позиции. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_123) | Отрегулируйте разрешение этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) с точностью, используя этот<br/>            простой метод. Идеально подходит для разработчиков, желающих настроить разрешение изображения под<br/>            конкретные требования, обеспечивая оптимальное качество отображения и управление размером файла. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_124) | Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_126) | Записывает всю строку сканирования в указанный индекс строки сканирования. |


### Constructor: DicomImage(dicom_options, width, height) {#DicomImage_dicom_options_width_height_1}


```
 DicomImage(dicom_options, width, height) 
```

Инициализируйте новый экземпляр класса DicomImage без усилий с помощью этого<br/>            конструктора, используя параметры dicomOptions. Идеально для разработчиков, желающих<br/>            быстро и эффективно погрузиться в объекты [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) в своих проектах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dicom_options | [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) | Опции dicom. |
| width | int | Ширина. |
| height | int | Высота. |

### Constructor: DicomImage(stream) {#DicomImage_stream_2}


```
 DicomImage(stream) 
```

Создайте новый экземпляр класса DicomImage, используя параметр потока<br/>            в этом конструкторе. Идеально для разработчиков, ищущих упрощённый способ инициализировать<br/>            объекты [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) из существующих потоков данных в своих проектах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |


**See also:**

**[Example # 1](#example_130)**: This example shows how to load a DICOM image from a file stream.


### Constructor: DicomImage(stream, load_options) {#DicomImage_stream_load_options_3}


```
 DicomImage(stream, load_options) 
```

Запустите новый экземпляр класса DicomImage плавно, используя параметры потока и<br/>            loadOptions в этом конструкторе. Идеально для разработчиков, желающих быстро и эффективно приступить<br/>            к работе с объектами [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) в своих проектах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Опции загрузки. |


**See also:**

**[Example # 1](#example_131)**: This example shows how to load a DICOM image from a file stream to stay withi...


### Method: add_page() {#add_page__1}


```
 add_page() 
```

Добавьте новую страницу в конец списка страниц изображения с помощью этого простого метода.<br/>            Идеально подходит для разработчиков, желающих динамически расширять многостраничные изображения, обеспечивая бесшовную<br/>            интеграцию и организацию содержимого изображения.

**Returns**

| Тип | Описание |
| :- | :- |
| [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | Недавно созданный [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/). |


### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Расширьте свою коллекцию изображений, добавив новую страницу с помощью этого интуитивного метода.<br/>            Идеально подходит для разработчиков, желающих динамически добавлять страницы к многостраничным изображениям,<br/>            обеспечивая бесшовное расширение и организацию содержимого изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Страница для добавления. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Улучшите яркость изображения с помощью регулировки _brightness_,<br/>            параметризованного метода, позволяющего разработчикам точно настраивать светимость изображений.<br/>            Эта удобная функция дает разработчикам возможность бесшовно управлять яркостью изображения,<br/>            предоставляя гибкость и контроль над визуальной эстетикой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| яркость | int | Значение яркости. |


**See also:**

**[Example # 1](#example_143)**: The following example performs brightness correction of a DICOM image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Улучшите контраст [Image](/imaging/python-net/aspose.imaging/image/) с помощью этого удобного метода,<br/> который регулирует различие между светлыми и тёмными областями. Улучшайте визуальную чёткость и<br/> определённость без усилий, предоставляя разработчикам интуитивный контроль над<br/> контрастом изображения для оптимального рендеринга.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| контраст | float | Значение контраста (в диапазоне [-100; 100]) |


**See also:**

**[Example # 1](#example_144)**: The following example performs contrast correction of a DICOM image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Повышайте качество изображения и регулируйте его с помощью гамма‑коррекции, мощной техники<br/> для тонкой настройки визуального вида. Идеально подходит для разработчиков, стремящихся оптимизировать представление изображения, регулировать цветовой баланс и обеспечивать согласованный рендеринг на разных<br/> устройствах и в разных средах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |


**See also:**

**[Example # 1](#example_141)**: The following example performs gamma-correction of a DICOM image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Добейтесь точной настройки цветов, применяя гамма‑коррекцию независимо<br/> к красному, зелёному и синему компонентам изображения. Этот метод обеспечивает точный<br/> цветовой баланс и оптимальный визуальный результат, удовлетворяя разработчиков, ищущих детальный<br/> контроль над рендерингом изображения и точностью цветов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| gamma_red | float | Коэффициент гаммы для красного канала |
| gamma_green | float | Коэффициент гаммы для зелёного канала |
| gamma_blue | float | Коэффициент гаммы для синего канала |


**See also:**

**[Example # 1](#example_142)**: The following example performs gamma-correction of a DICOM image applying dif...


### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_7}


```
 analyze_percentage_digital_signature(password) 
```

Вычисляет процентное сходство между извлечёнными данными и оригинальным паролем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пароль | string | Пароль, используемый для извлечения встроенных данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение процента сходства. |


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_8}


```
 binarize_bradley(brightness_difference) 
```

Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном порогировании изображения

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brightness_difference | float | Разница яркости между пикселем и средним значением окна s × s пикселей<br/>                центрированного вокруг этого пикселя. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

Бинаризуйте изображения с помощью адаптивного порогового алгоритма Брэдли, используя интегральное<br/> порогирование изображения для повышения производительности. Идеально подходит для разработчиков, желающих<br/> автоматически сегментировать изображения на основе локальных вариаций яркости, обеспечивая<br/> точное обнаружение и извлечение объектов при разных условиях освещения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brightness_difference | float | Разница яркости между пикселем и средним значением окна s × s пикселей<br/>            центрированного вокруг этого пикселя. |
| window_size | int | Размер окна s × s пикселей, центрированного вокруг этого пикселя |


**See also:**

**[Example # 1](#example_139)**: The following example binarizes a DICOM image with Bradley's adaptive thresho...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

Легко преобразуйте изображение в бинарный формат с помощью заранее заданного порога<br/> используя этот простой метод. Идеально подходит для разработчиков, желающих упростить задачи обработки изображений, сегментируя их на передний план и фон<br/> на основе указанных уровней интенсивности.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| порог | System.Byte | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение<br/>            255, иначе 0. |


**See also:**

**[Example # 1](#example_137)**: The following example binarizes a DICOM image with the predefined threshold. ...


### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_11}


```
 blend(origin, overlay, overlay_alpha) 
```

Смешивает этот экземпляр изображения с изображением _overlay_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Источник наложения фонового изображения. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение наложения. |
| overlay_alpha | System.Byte | Прозрачность наложения. |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_12}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

Смешивает этот экземпляр изображения с изображением _overlay_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Источник наложения фонового изображения. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение наложения. |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Область наложения. |
| overlay_alpha | System.Byte | Прозрачность наложения. |

### Method: can_load(file_path)  [static] {#can_load_file_path_13}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_14}


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


### Method: can_load(stream)  [static] {#can_load_stream_15}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_16}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_17}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_18}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_19}


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


### Method: can_save(options) {#can_save_options_20}


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


### Method: create(files)  [static] {#create_files_21}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_22}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_23}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_24}


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


### Method: create(images)  [static] {#create_images_25}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_26}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_27}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_28}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_29}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_30}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_31}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_32}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Отрегулируйте область обрезки изображения, применяя смещения с помощью этого универсального метода.<br/>            Идеально подходит разработчикам, которым нужен точный контроль над процессом обрезки, гарантируя<br/>            сохранение важных деталей при удалении ненужных элементов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| left_shift | int | Сдвиг влево. |
| right_shift | int | Сдвиг вправо. |
| top_shift | int | Сдвиг вверх. |
| bottom_shift | int | Сдвиг вниз. |


**See also:**

**[Example # 1](#example_136)**: The following example crops a DICOM image. The cropping area is specified via...


### Method: crop(rectangle) {#crop_rectangle_33}


```
 crop(rectangle) 
```

Обрежьте изображение, чтобы удалить нежелательные области и сосредоточиться на важном содержании с помощью этого<br/>            простого метода. Идеально подходит разработчикам, желающим настроить визуальную композицию<br/>            изображений, гарантируя эффективную передачу желаемого сообщения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |


**See also:**

**[Example # 1](#example_135)**: The following example crops a DICOM image. The cropping area is be specified ...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_34}


```
 dither(dithering_method, bits_count) 
```

Выполняет дизеринг текущего изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Метод дизеринга. |
| bits_count | int | Окончательное количество бит для дизеринга. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_35}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Улучшите текущее изображение, применяя эффекты дизеринга с помощью этого простого<br/>            метода. Идеально подходит разработчикам, стремящимся добавить текстуру и глубину изображениям,<br/>            улучшая их визуальное качество и общую привлекательность.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Метод дизеринга. |
| bits_count | int | Окончательное количество бит для дизеринга. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Пользовательская палитра для дизеринга. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_36}


```
 embed_digital_signature(password) 
```

Вставьте цифровую подпись, основанную на предоставленном пароле, в каждую страницу изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пароль | string | Пароль, используемый для генерации данных цифровой подписи. |

### Method: filter(rectangle, options) {#filter_rectangle_options_37}


```
 filter(rectangle, options) 
```

Легко улучшайте отдельные области вашего изображения, применяя фильтры к заданным<br/>            прямоугольникам. Этот метод предоставляет разработчикам точный контроль над<br/>            манипуляцией изображением, позволяя выполнять целенаправленные настройки для достижения желаемых<br/>            визуальных эффектов без труда.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Параметры. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_38}


```
 get_argb_32_pixel(x, y) 
```

Получает 32-битный ARGB‑пиксель изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | 32-битный ARGB‑пиксель для указанного местоположения. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_39}


```
 get_default_argb_32_pixels(rectangle) 
```

Получает массив пикселей по умолчанию в формате 32‑бит ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, для которого получаются пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Массив пикселей по умолчанию |


### Method: get_default_options(args) {#get_default_options_args_40}


```
 get_default_options(args) 
```

Получает параметры по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| args | System.Object | Аргументы. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры по умолчанию |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_41}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, для которого получаются пиксели. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Частичный загрузчик пикселей. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, для которого получаются пиксели. |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Частичный загрузчик необработанных данных. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Настройки необработанных данных. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_43}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Получает массив необработанных данных по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, для которого получаются необработанные данные. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Настройки необработанных данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Массив необработанных данных по умолчанию |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_44}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_45}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


```
 get_modify_date(use_default) 
```

Получает дату и время последнего изменения ресурса изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| use_default | bool | если установлено в <c>true</c>, использует информацию из FileInfo в качестве значения по умолчанию. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.DateTime | Дата и время последнего изменения изображения ресурса. |


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Получает параметры на основе настроек оригинального файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений.<br/>            Например, если мы загружаем черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) метода, будет получено PNG‑изображение с 8‑битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            в метод [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) в качестве второго параметра.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры, основанные на настройках исходного файла. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


```
 get_pixel(x, y) 
```

Получает пиксель изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Цвет пикселя для указанного местоположения. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_54}


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


### Method: get_skew_angle() {#get_skew_angle__55}


```
 get_skew_angle() 
```

Получает угол наклона.<br/>            Этот метод применим к отсканированным текстовым документам для определения угла наклона при сканировании.

**Returns**

| Тип | Описание |
| :- | :- |
| float | Угол наклона в градусах. |


### Method: insert_page(page_index) {#insert_page_page_index_56}


```
 insert_page(page_index) 
```

Вставьте новую страницу в список страниц изображения в указанном индексе с помощью этого интуитивного<br/>            метода. Идеально для разработчиков, желающих точно контролировать расположение страниц в<br/>            многостраничных изображениях, обеспечивая бесшовную организацию и настройку содержимого изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_index | int | Индекс страницы. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | Недавно созданный [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/). |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_57}


```
 is_digital_signed(password, percentage_threshold) 
```

Выполняет быструю проверку, чтобы определить, подписано ли изображение цифровой подписью, используя предоставленный пароль и пороговое значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пароль | string | Пароль для проверки подписи. |
| percentage_threshold | int | Порог (в процентах)[0-100], определяющий, считается ли изображение подписанным.<br/>            Если не указано, будет применён порог по умолчанию (<c>75</c>). |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, если изображение подписано, иначе false. |


### Method: load(file_path)  [static] {#load_file_path_58}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_59}


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


### Method: load(stream)  [static] {#load_stream_60}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_61}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_62}


```
 load_argb_32_pixels(rectangle) 
```

Загружает 32‑битные ARGB‑пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Загруженный массив 32‑битных ARGB пикселей. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_63}


```
 load_argb_64_pixels(rectangle) 
```

Загружает 64‑битные ARGB‑пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Загруженный массив пикселей ARGB 64‑бит. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_64}


```
 load_cmyk_32_pixels(rectangle) 
```

Загружает пиксели в формате CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Загруженный массив пикселей CMYK, представленных как 32‑битные целочисленные значения. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_65}


```
 load_cmyk_pixels(rectangle) 
```

Загружает пиксели в формате CMYK.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Загруженный массив пикселей CMYK. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Частично загружает 32‑битные ARGB‑пиксели (по блокам).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, из которого загружать пиксели. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Частичный загрузчик пикселей. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Частично загружает 64‑битные ARGB‑пиксели пакетами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Желаемый прямоугольник. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Загрузчик пикселей ARGB 64‑бит. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_68}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Частично загружает пиксели пакетами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Желаемый прямоугольник. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Загрузчик пикселей. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_69}


```
 load_pixels(rectangle) 
```

Загружает пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Загруженный массив пикселей. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Загружает необработанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, из которого загружать необработанные данные. |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы целевого изображения. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Настройки необработанных данных, используемые для загруженных данных. Обратите внимание, что если данные не в указанном формате, будет выполнено их преобразование. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Загрузчик необработанных данных. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Загружает необработанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, из которого загружать необработанные данные. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Настройки необработанных данных, используемые для загруженных данных. Обратите внимание, что если данные не в указанном формате, будет выполнено их преобразование. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Загрузчик необработанных данных. |

### Method: load_stream(stream)  [static] {#load_stream_stream_72}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_73}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_74}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_75}


```
 normalize_angle(resize_proportionally, background_color) 
```

Нормализует угол.<br/>            Этот метод применим к отсканированным текстовым документам для устранения наклона сканирования.<br/>            Метод использует функции [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) и [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| resize_proportionally | bool | если установить значение <c>true</c>, размер изображения будет изменён в соответствии с проекциями повернутого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только внутреннее содержимое изображения. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет фона. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_76}


```
 read_argb_32_scan_line(scan_line_index) 
```

Считывает всю строку сканирования по указанному индексу строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Индекс строки сканирования, начинающийся с нуля. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Массив 32‑битных значений цветов ARGB строки сканирования. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_77}


```
 read_scan_line(scan_line_index) 
```

Считывает всю строку сканирования по указанному индексу строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Индекс строки сканирования, начинающийся с нуля. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Массив значений цветов пикселей строки сканирования. |


### Method: remove_page(page_index) {#remove_page_page_index_78}


```
 remove_page(page_index) 
```

Удалите страницу с указанным индексом из списка страниц с помощью этого удобного метода.<br/>            Идеально для разработчиков, желающих точно контролировать управление многостраничными изображениями,<br/>            обеспечивая бесшовную организацию и настройку содержимого изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_index | int | Индекс страницы. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_79}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| old_color_argb | int | Значение ARGB старого цвета, которое будет заменено. |
| old_color_diff | System.Byte | Допустимая разница в старом цвете, позволяющая расширить заменённый тон цвета. |
| new_color_argb | int | Новое значение ARGB цвета для замены старого цвета. |

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_80}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| old_color_diff | System.Byte | Допустимая разница в старом цвете, позволяющая расширить заменённый тон цвета. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_81}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| old_color_argb | int | Значение ARGB старого цвета, которое будет заменено. |
| old_color_diff | System.Byte | Допустимая разница в старом цвете, позволяющая расширить заменённый тон цвета. |
| new_color_argb | int | Новое значение ARGB цвета для замены старого цвета. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_82}


```
 replace_non_transparent_colors(new_color) 
```

Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа‑значение для сохранения плавных краёв.<br/>                Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа‑значение для сохранения плавных краёв.<br/>                Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color_argb | int | Новое значение ARGB цвета для замены непрозрачных цветов. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_84}


```
 resize(new_width, new_height) 
```

Изменяет размер изображения. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_85}


```
 resize(new_width, new_height, resize_type) 
```

Измените размер изображения, сохраняя его пропорции, с помощью этого удобного метода. Идеально<br/>            для разработчиков, желающих пропорционально изменить размеры изображения, обеспечивая<br/>            согласованность и сохраняя пропорции оригинального содержимого.<br/>            Пропорциональное изменение размера будет масштабировать каждый кадр согласно соотношению _newWidth_/width и _newHeight_/height.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_86}


```
 resize(new_width, new_height, settings) 
```

Отрегулируйте размер вашего изображения с помощью этого простого метода изменения размера. Независимо от того, нужно ли вам<br/>            уменьшить или увеличить изображение, эта функция гарантирует, что ваши требования к изменению размера будут выполнены<br/>            эффективно и точно, что делает её идеальной для разработчиков, ищущих быстрые и простые<br/>            корректировки размеров изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The resize settings. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_87}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_88}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_89}


```
 resize_height_proportionally(new_height) 
```

Пропорционально изменяет высоту. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_90}


```
 resize_height_proportionally(new_height, resize_type) 
```

Отрегулируйте высоту изображения, сохраняя его соотношение сторон, с помощью этого<br/>            удобного метода. Идеально подходит для разработчиков, желающих динамически изменять размер изображений<br/>            при сохранении их пропорций, обеспечивая оптимальное отображение и удобство<br/>            использования в их приложениях.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_91}


```
 resize_height_proportionally(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_92}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_93}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Измените размер изображения, сохраняя его пропорции, с помощью этого удобного метода. Идеально<br/>            для разработчиков, желающих пропорционально изменить размеры изображения, обеспечивая<br/>            согласованность и сохраняя пропорции оригинального содержимого.<br/>            Пропорциональное изменение размера будет масштабировать каждый кадр согласно соотношению _newWidth_/width и _newHeight_/height.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_94}


```
 resize_width_proportionally(new_width) 
```

Пропорционально изменяет ширину. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_95}


```
 resize_width_proportionally(new_width, resize_type) 
```

Отрегулируйте ширину изображения, сохраняя его соотношение сторон, с помощью этого удобного<br/>            метода. Идеально подходит для разработчиков, желающих пропорционально изменять размер изображений, обеспечивая<br/>            согласованные и визуально привлекательные результаты в разных средах отображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_96}


```
 resize_width_proportionally(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_97}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_98}


```
 rotate(angle) 
```

Повернуть изображение вокруг центра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_99}


```
 rotate(angle, resize_proportionally, background_color) 
```

Поверните изображение вокруг его центра с помощью этого удобного метода. Идеально подходит для разработчиков<br/>            желающих динамически регулировать ориентацию изображения, обеспечивая оптимальное представление и<br/>            выравнивание в их приложениях.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resize_proportionally | bool | если установлено <c>true</c>, размер вашего изображения будет изменён<br/>
            в соответствии с проекциями повернутого прямоугольника (угловых точек) в остальных
            случаях, когда размеры остаются нетронутыми, и только
            __internal__ содержимое изображения вращается. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет фона. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_100}


```
 rotate_flip(rotate_flip_type) 
```

Легко манипулируйте активным кадром, вращая, отражая или выполняя оба действия<br/>            одновременно с помощью этого простого метода. Идеально подходит для разработчиков, которым необходимо<br/>            динамически регулировать ориентацию конкретных кадров в их последовательностях изображений,<br/>            обеспечивая оптимальное представление и выравнивание.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | The rotate flip type. |


**See also:**

**[Example # 1](#example_132)**: This example loads a DICOM image, rotates it by 90 degrees clockwise and opti...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_101}


```
 rotate_flip_all(rotate_flip) 
```

Выполняет вращение и отражение всех.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | The rotate flip. |

### Method: save(file_path) {#save_file_path_102}


```
 save(file_path) 
```

Сохраняет изображение в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_103}


```
 save(file_path, options) 
```

Сохраняет данные объекта, записывая их в назначенный файл (индексатор + имя файла)<br/>            в указанном месте вместе с заданным форматом файла и параметрами. Идеально подходит для разработчиков, желающих<br/>            безопасно хранить данные в различных форматах, сохраняя гибкость и контроль над<br/>            параметрами сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_104}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_105}


```
 save(file_path, over_write) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | если установлено <c>true</c>, перезаписать содержимое файла, иначе будет выполнено добавление. |

### Method: save(stream) {#save_stream_106}


```
 save(stream) 
```

Сохраняет данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save data to. |

### Method: save(stream, options_base) {#save_stream_options_base_107}


```
 save(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_108}


```
 save(stream, options_base, bounds_rectangle) 
```

Легко сохраняйте данные вашего изображения в указанный поток в нужном формате файла<br/>            с помощью этого удобного метода. Независимо от того, работаете ли вы с JPEG, PNG или другим форматом,<br/>            эта функция гарантирует эффективное и точное сохранение данных изображения,<br/>            делая её идеальной для разработчиков, желающих оптимизировать процессы сохранения файлов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |


**See also:**

**[Example # 1](#example_133)**: The following example loads a DICOM image from a file, then saves the image t...


### Method: save_all(file_path, options) {#save_all_file_path_options_109}


```
 save_all(file_path, options) 
```

Сохраняет данные объекта, записывая их в назначенный файл (индексатор + имя файла)<br/>            в указанном месте вместе с заданным форматом файла и параметрами. Идеально подходит для разработчиков, желающих<br/>            безопасно хранить данные в различных форматах, сохраняя гибкость и контроль над<br/>            параметрами сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_110}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Сохраняет 32-битные ARGB‑пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| пиксели | int[] | The 32-bit ARGB pixels array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_111}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Сохраняет пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| пиксели | int[] | The CMYK pixels presented as the 32-bit integer values. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_112}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Сохраняет пиксели.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The CMYK pixels array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_113}


```
 save_pixels(rectangle, pixels) 
```

Сохраняет пиксели (метод, специфичный для формата).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | The pixels array. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_114}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Сохраняет необработанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | System.Byte | The raw data. |
| data_offset | int | The starting raw data offset. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The raw data rectangle. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Настройки необработанных данных, в которых находятся данные. |

### Method: save_to_stream(stream) {#save_to_stream_stream_115}


```
 save_to_stream(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, в который сохраняются данные объекта. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_116}


```
 save_to_stream_with_options(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_118}


```
 save_with_options(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_119}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_120}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| argb_32_color | int | 32‑битный ARGB‑пиксель для указанной позиции. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_121}


```
 set_palette(palette, update_colors) 
```

Устанавливает палитру изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Палитра для установки. |
| update_colors | bool | Если установить значение <c>true</c>, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою загрузки изображения, если некоторые индексы не имеют соответствующих записей в палитре. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_122}


```
 set_pixel(x, y, color) 
```

Устанавливает пиксель изображения для указанной позиции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет пикселя для указанной позиции. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_123}


```
 set_resolution(dpi_x, dpi_y) 
```

Отрегулируйте разрешение этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) с точностью, используя этот<br/>            простой метод. Идеально подходит для разработчиков, желающих настроить разрешение изображения под<br/>            конкретные требования, обеспечивая оптимальное качество отображения и управление размером файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dpi_x | float | Горизонтальное разрешение в точках на дюйм для [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Вертикальное разрешение в точках на дюйм для [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_124}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Индекс строки сканирования, начинающийся с нуля. |
| argb_32_pixels | int[] | Массив 32‑битных ARGB‑цветов для записи. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_126}


```
 write_scan_line(scan_line_index, pixels) 
```

Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Индекс строки сканирования, начинающийся с нуля. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Массив цветов пикселей для записи. |

## **Examples**
### This example shows how to load a DICOM image from a file stream. {#example_130}
``` python
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Загрузить изображение DICOM из файлового потока.
with open(join(dir_, "sample.dicom"), "rb") as stream:
	with DicomImage(stream) as dicom_image:
		# Сохранить каждую страницу как отдельное PNG‑изображение.
		for dicom_page in dicom_image.dicom_pages:
			# Сгенерировать имя файла на основе индекса страницы.
			file_name = "sample.{0}.png".format(dicom_page.index)
			# Страница DICOM является растровым изображением, поэтому все разрешённые операции с растровым изображением применимы к странице DICOM.
			dicom_page.save(join(dir_, file_name), PngOptions())


```

### This example shows how to load a DICOM image from a file stream to stay within the specified memory limit. {#example_131}
``` python
from aspose.imaging import LoadOptions, Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.dicom import DicomImage
from os.path import join as path_join


dir_: str = "c:\\temp"
# Загрузить изображение DICOM из файлового потока.
with open(path_join(dir_, "multiframe.dicom"), "rb") as stream:
	# Максимальный разрешённый размер всех внутренних буферов — 256 КБ.
	load_options = LoadOptions()
	load_options.buffer_size_hint = 256 * 1024
	with DicomImage(stream, load_options) as dicom_image:
		# Сохранить каждую страницу как отдельное PNG‑изображение.
		for dicom_page in dicom_image.dicom_pages:
			# Сгенерировать имя файла на основе индекса страницы.
			file_name = "multiframe.{0}.png".format(dicom_page.index)
			# Страница DICOM является растровым изображением, поэтому все разрешённые операции с растровым изображением применимы к странице DICOM.
			dicom_page.save(path_join(dir_, file_name), PngOptions())


```

### This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_132}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# Повернуть, отразить и сохранить в выходной файл.
	with aspycore.as_of(Image.load(join(dir_, "sample.dicom")), DicomImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example loads a DICOM image from a file, then saves the image to a PNG file stream. {#example_133}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions     

dir_: str = "c:\\temp"
with aspycore.as_of(Image.load(join(dir_, "sample.dicom")), DicomImage) as image:
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width // 2, image.height // 2)
	with open(join(dir_, "output.png"), "wb") as output_stream:
		# Сохранить верхний левый квартал изображения в файловый поток.
		image.save(output_stream, save_options, bounds)


```

### The following example crops a DICOM image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_135}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions    


dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Обрезать изображение. Область обрезки — прямоугольная центральная часть изображения.
	area = Rectangle(dicom_image.width // 4, dicom_image.height // 4, dicom_image.width // 2, dicom_image.height // 2)
	dicom_image.crop(area)
	# Сохранить обрезанное изображение в PNG.
	dicom_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example crops a DICOM image. The cropping area is specified via Left, Top, Right, Bottom margins. {#example_136}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = r"c:\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Обрезать снова. Установить отступ в размере 10 % от размера изображения.
	horizontal_margin = dicom_image.width // 10
	vertical_margin = dicom_image.height // 10
	dicom_image.crop(horizontal_margin, horizontal_margin, vertical_margin, vertical_margin)
	# Сохранить обрезанное изображение в PNG.
	dicom_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example binarizes a DICOM image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_137}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.dicom import DicomImage
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Бинаризовать изображение с пороговым значением 127.
	# Если соответствующее серое значение пикселя больше 127, ему будет присвоено значение 255, иначе 0.
	dicom_image.binarize_fixed(127)
	dicom_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_139}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Бинаризовать изображение с разницей яркости 5. Яркость — это разница между пикселем и средним значением окна 10 × 10 пикселей, центрированного вокруг этого пикселя.
	dicom_image.binarize_bradley(5, 10)
	dicom_image.save(join(dir_, "sample.BinarizeBradley5_10x10.png"), PngOptions())


```

### The following example performs gamma-correction of a DICOM image. {#example_141}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join


dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Установить коэффициент гаммы для красного, зелёного и синего каналов.
	dicom_image.adjust_gamma(2.5)
	dicom_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a DICOM image applying different coefficients for color components. {#example_142}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Установить отдельные коэффициенты гаммы для красного, зелёного и синего каналов.
	dicom_image.adjust_gamma(1.5, 2.5, 3.5)
	dicom_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a DICOM image. {#example_143}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Установить значение яркости. Допустимые значения яркости находятся в диапазоне [-255, 255].
	dicom_image.adjust_brightness(50)
	dicom_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a DICOM image. {#example_144}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Установить значение контрастности. Допустимые значения контрастности находятся в диапазоне [-100f, 100f].
	dicom_image.adjust_contrast(50.0)
	dicom_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())


```

### Use JPEG compression in DICOM image. {#example_211}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import JpegOptions, DicomOptions
from aspose.imaging.fileformats.jpeg import JpegCompressionMode, SampleRoundingMode
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import Compression, ColorType, CompressionType

with Image.load("original.jpg") as input_image:
	obj_init = JpegOptions()
	obj_init.compression_type = JpegCompressionMode.BASELINE
	obj_init.sample_rounding_mode = SampleRoundingMode.TRUNCATE
	obj_init.quality = 50
	obj_init2 = Compression()
	obj_init2.type = CompressionType.JPEG
	obj_init2.jpeg = obj_init
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = obj_init2
	input_image.save("original_JPEG.dcm", options)


```

### Use JPEG 2000 compression in DICOM image. {#example_212}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import Jpeg2000Options, DicomOptions
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Compression, CompressionType, ColorType

with Image.load("original.jpg") as input_image:
	obj_init = Jpeg2000Options()
	obj_init.codec = Jpeg2000Codec.JP2
	obj_init.irreversible = False
	obj_init2 = Compression()
	obj_init2.type_ = CompressionType.JPEG2000
	obj_init2.jpeg2000 = obj_init
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = obj_init2
	input_image.save("original_JPEG2000.dcm", options)


```

### Use RLE compression in DICOM image. {#example_213}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import Compression, CompressionType, ColorType
from aspose.imaging.imageoptions import DicomOptions

with Image.load("original.jpg") as input_image:
	compr = Compression()
	compr.type_ = CompressionType.RLE
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = compr
	input_image.save("original_RLE.dcm", options)


```

### Change the color type in DICOM compression. {#example_214}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import ColorType

with Image.load("original.jpg") as inputImage:
	options = DicomOptions()
	options.color_type = ColorType.GRAYSCALE_8_BIT
	inputImage.save("original_8Bit.dcm", options)


```

