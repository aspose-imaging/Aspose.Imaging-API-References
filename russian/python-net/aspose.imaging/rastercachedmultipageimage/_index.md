---
title: "Класс RasterCachedMultipageImage"
type: docs
weight: 7050
url: /ru/python-net/aspose.imaging/rastercachedmultipageimage/
---

**Summary:** The raster multipage image

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RasterCachedMultipageImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, RasterCachedImage

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Получает или задает значение, указывающее, следует ли автоматически корректировать палитру. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает значение цвета фона. |
| bits_per_pixel | int | r | Получает количество бит на пиксель изображения. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Получает границы объекта. |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Получает контейнер [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Получает поток данных объекта. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задаёт экземпляр Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Получает значение формата файла |
| has_alpha | bool | r | Получает значение, указывающее, имеет ли этот экземпляр альфа-канал. |
| has_background_color | bool | r/w | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| has_transparent_color | bool | r/w | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| height | int | r | Получает высоту изображения. |
| horizontal_resolution | float | r/w | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Получает непрозрачность этого изображения. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Получает или задает монитор прерываний. |
| is_cached | bool | r | Получает значение, указывающее, кэшируются ли данные изображения в данный момент. |
| is_raw_data_available | bool | r | Получает значение, указывающее, поддерживается ли загрузка необработанных данных. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Получает или задает XMP‑данные из кадра. |
| page_count | int | r | Получает количество страниц. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Получает страницы. |
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
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Регулировка _яркости_ изображения. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | [Image](/imaging/python-net/aspose.imaging/image/) контрастирование |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Гамма‑коррекция изображения. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Гамма‑коррекция изображения. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | Вычисляет процентное сходство между извлечёнными данными и оригинальным паролем. |
| auto_brightness_contrast() | Выполняет автоматическую адаптивную нормализацию яркости и контраста для всего изображения. |
| auto_rotate() | Автоматически вращает изображение на основе данных ориентации, извлечённых из Exif <br/> метаданных. Этот метод гарантирует, что изображения отображаются в правильной ориентации, <br/> улучшая пользовательский опыт и устраняя необходимость ручных корректировок. Путём <br/> анализа информации Exif изображение вращается соответствующим образом, обеспечивая бесшовный <br/> просмотр на разных платформах и устройствах. Этот автоматизированный процесс вращения <br/> упрощает работу с изображениями и повышает общую удобность, особенно при <br/> работе с большими партиями изображений с различными ориентациями. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном порогировании изображения |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном порогировании изображения |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Бинаризация изображения с предопределённым порогом |
| binarize_otsu() | Бинаризация изображения с порогом Оцу |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_9) | Смешивает этот экземпляр изображения с изображением _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_10) | Смешивает этот экземпляр изображения с изображением _overlay_. |
| cache_data() | Кеширует данные приватно. |
| [can_load(file_path)](#can_load_file_path_11) | Определяет, можно ли загрузить изображение из указанного пути к файлу. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_12) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [can_load(stream)](#can_load_stream_13) | Определяет, можно ли загрузить изображение из указанного потока. |
| [can_load(stream, load_options)](#can_load_stream_load_options_14) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_15) | Определяет, можно ли загрузить изображение из указанного потока. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_16) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_17) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [can_save(options)](#can_save_options_18) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| [create(files)](#create_files_19) | Создаёт многостраничное изображение, содержащее указанные файлы. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_20) | Создаёт многостраничное изображение, содержащее указанные файлы. |
| [create(image_options, width, height)](#create_image_options_width_height_21) | Создаёт новое изображение с использованием указанных параметров создания. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_22) | Создаёт экземпляр [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) из предоставленного массива пикселей.<br/> <br/> Проверяет, что указанные ширина и высота соответствуют размерам пиксельных данных.<br/> Этот метод может использоваться только в лицензированном режиме библиотеки. |
| [create(images)](#create_images_23) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create(images, dispose_images)](#create_images_dispose_images_24) | Создает новое изображение из указанных изображений в виде страниц. |
| [create(multipage_create_options)](#create_multipage_create_options_25) | Создает указанные параметры создания многостраничного изображения. |
| [create_from_files(files)](#create_from_files_files_26) | Создает многостраничное изображение, содержащее указанные файлы в виде страниц с отложенной загрузкой. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_27) | Создает многостраничное изображение, содержащее указанные файлы в виде страниц с отложенной загрузкой. |
| [create_from_images(images)](#create_from_images_images_28) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_29) | Создает новое изображение из указанных изображений в виде страниц. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_30) | Обрезать изображение со смещениями. |
| [crop(rectangle)](#crop_rectangle_31) | Обрезка изображения. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_32) | Выполняет дизеринг текущего изображения. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_33) | Выполняет дизеринг текущего изображения. |
| [embed_digital_signature(password)](#embed_digital_signature_password_34) | Вставьте цифровую подпись, основанную на предоставленном пароле, в каждую страницу изображения. |
| [filter(rectangle, options)](#filter_rectangle_options_35) | Фильтрует указанный прямоугольник. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_36) | Получает 32-битный ARGB‑пиксель изображения. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_37) | Получает массив пикселей по умолчанию в формате 32‑бит ARGB. |
| [get_default_options(args)](#get_default_options_args_38) | Получает параметры по умолчанию. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_39) | Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40) | Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_41) | Получает массив необработанных данных по умолчанию. |
| [get_file_format(file_path)](#get_file_format_file_path_42) | Получает формат файла. |
| [get_file_format(stream)](#get_file_format_stream_43) | Получает формат файла. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_44) | Получает формат файла. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_45) | Получает прямоугольник, соответствующий текущему изображению. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_46) | Получает прямоугольник, соответствующий текущему изображению. |
| [get_modify_date(use_default)](#get_modify_date_use_default_47) | Получает дату и время последнего изменения ресурса изображения. |
| [get_original_options()](#get_original_options__48) | Получает параметры на основе настроек оригинального файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений.<br/>            Например, если мы загружаем черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) метода, будет получено PNG‑изображение с 8‑битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            в метод [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) в качестве второго параметра. |
| [get_pixel(x, y)](#get_pixel_x_y_49) | Получает пиксель изображения. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_50) | Получает пропорциональную высоту. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_51) | Получает пропорциональную ширину. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_52) | Преобразует в aps. |
| [get_skew_angle()](#get_skew_angle__53) | Получает угол наклона.<br/>            Этот метод применим к отсканированным текстовым документам для определения угла наклона при сканировании. |
| grayscale() | Преобразование изображения в его градации серого |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_54) | Выполняет быструю проверку, чтобы определить, подписано ли изображение цифровой подписью, используя предоставленный пароль и пороговое значение. |
| [load(file_path)](#load_file_path_55) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| [load(stream)](#load_stream_57) | Загружает новое изображение из указанного потока. |
| [load(stream, load_options)](#load_stream_load_options_58) | Загружает новое изображение из указанного потока. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | Загружает 32‑битные ARGB‑пиксели. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | Загружает 64‑битные ARGB‑пиксели. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | Загружает пиксели в формате CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | Загружает пиксели в формате CMYK.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | Частично загружает 32‑битные ARGB‑пиксели (по блокам). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_64) | Частично загружает 64‑битные ARGB‑пиксели пакетами. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_65) | Частично загружает пиксели пакетами. |
| [load_pixels(rectangle)](#load_pixels_rectangle_66) | Загружает пиксели. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_67) | Загружает необработанные данные. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_68) | Загружает необработанные данные. |
| [load_stream(stream)](#load_stream_stream_69) | Загружает новое изображение из указанного потока. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_70) | Загружает новое изображение из указанного потока. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_71) | Загружает новое изображение из указанного пути к файлу или URL.<br/>            Если _filePath_ — путь к файлу, метод просто открывает файл.<br/>            Если _filePath_ — URL, метод загружает файл, сохраняет его как временный и открывает. |
| normalize_angle() | Нормализует угол.<br/>            Этот метод применим к отсканированным текстовым документам для устранения наклона сканирования.<br/>            Метод использует функции [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) и [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_72) | Нормализует угол.<br/>            Этот метод применим к отсканированным текстовым документам для устранения наклона сканирования.<br/>            Метод использует функции [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) и [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/). |
| normalize_histogram() | Нормализует гистограмму изображения — корректирует значения пикселей, чтобы использовать весь доступный диапазон. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_73) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_74) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| remove_metadata() | Удаляет метаданные этого экземпляра изображения, устанавливая значение [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) в **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_75) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_76) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_77) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_78) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа‑значение для сохранения плавных краёв.<br/>                Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_79) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа‑значение для сохранения плавных краёв.<br/>                Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним. |
| [resize(new_width, new_height)](#resize_new_width_new_height_80) | Изменяет размер изображения. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_81) | Изменяет размер изображения. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_82) | Изменяет размер изображения. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_83) | Изменяет размер изображения. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_84) | Изменяет размер изображения. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_85) | Пропорционально изменяет высоту. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_86) | Пропорционально изменяет ширину. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_87) | Пропорционально изменяет высоту. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_88) | Пропорционально изменяет высоту. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_89) | Пропорционально изменяет ширину. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_90) | Пропорционально изменяет ширину. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_91) | Пропорционально изменяет ширину. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_92) | Пропорционально изменяет ширину. |
| [rotate(angle)](#rotate_angle_93) | Повернуть изображение вокруг центра. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_94) | [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) изображение вокруг центра. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_95) | Поворачивает, отражает или одновременно поворачивает и отражает все страницы. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_96) | Выполняет вращение и отражение всех. |
| save() | Сохраняет данные изображения в базовый поток. |
| [save(file_path)](#save_file_path_97) | Сохраняет изображение в указанное расположение файла. |
| [save(file_path, options)](#save_file_path_options_98) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_99) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save(file_path, over_write)](#save_file_path_over_write_100) | Сохраняет данные объекта в указанное расположение файла. |
| [save(stream)](#save_stream_101) | Сохраняет данные объекта в указанный поток. |
| [save(stream, options_base)](#save_stream_options_base_102) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_103) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_104) | Сохраняет 32-битные ARGB‑пиксели. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_105) | Сохраняет пиксели. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_106) | Сохраняет пиксели.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_107) | Сохраняет основные внутренние пиксели. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_108) | Сохраняет необработанные данные. |
| [save_to_stream(stream)](#save_to_stream_stream_109) | Сохраняет данные объекта в указанный поток. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_110) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_111) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_112) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_113) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_114) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_115) | Устанавливает палитру изображения. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_116) | Устанавливает пиксель изображения для указанной позиции. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_117) | Устанавливает разрешение для этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_118) | Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_119) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_120) | Записывает всю строку сканирования в указанный индекс строки сканирования. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Регулировка _яркости_ изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| яркость | int | Значение яркости. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

[Image](/imaging/python-net/aspose.imaging/image/) contrasting

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| контраст | float | Значение контраста (в диапазоне [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Гамма‑коррекция изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Гамма‑коррекция изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| gamma_red | float | Коэффициент гаммы для красного канала |
| gamma_green | float | Коэффициент гаммы для зелёного канала |
| gamma_blue | float | Коэффициент гаммы для синего канала |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_5}


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



**See also:**

**[Example # 1](#example_234)**: The example illustrates how to determine the probability (from 0% to 100%) th...


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном порогировании изображения

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brightness_difference | float | Разница яркости между пикселем и средним значением окна s × s пикселей<br/>                центрированного вокруг этого пикселя. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном порогировании изображения

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brightness_difference | float | Разница яркости между пикселем и средним значением окна s × s пикселей<br/>                центрированного вокруг этого пикселя. |
| window_size | int | Размер окна s × s пикселей, центрированного вокруг этого пикселя |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Бинаризация изображения с предопределённым порогом

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| порог | System.Byte | Пороговое значение. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение<br/>                255, иначе 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_9}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_10}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_11}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_12}


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


### Method: can_load(stream)  [static] {#can_load_stream_13}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_14}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_15}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_16}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_17}


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


### Method: can_save(options) {#can_save_options_18}


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


### Method: create(files)  [static] {#create_files_19}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_20}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_21}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_22}


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


### Method: create(images)  [static] {#create_images_23}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_24}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_25}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_26}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_27}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_28}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_29}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_30}


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

### Method: crop(rectangle) {#crop_rectangle_31}


```
 crop(rectangle) 
```

Обрезка изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_32}


```
 dither(dithering_method, bits_count) 
```

Выполняет дизеринг текущего изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Метод дизеринга. |
| bits_count | int | Окончательное количество бит для дизеринга. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_33}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Выполняет дизеринг текущего изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Метод дизеринга. |
| bits_count | int | Окончательное количество бит для дизеринга. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Пользовательская палитра для дизеринга. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_34}


```
 embed_digital_signature(password) 
```

Вставьте цифровую подпись, основанную на предоставленном пароле, в каждую страницу изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| пароль | string | Пароль, используемый для генерации данных цифровой подписи. |


**See also:**

**[Example # 1](#example_232)**: The example shows how to embed digital signature based on provided password i...


### Method: filter(rectangle, options) {#filter_rectangle_options_35}


```
 filter(rectangle, options) 
```

Фильтрует указанный прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Параметры. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_36}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_37}


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


### Method: get_default_options(args) {#get_default_options_args_38}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_39}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, для которого получаются пиксели. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Частичный загрузчик пикселей. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_41}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_42}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_43}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_44}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_45}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_46}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_47}


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


### Method: get_original_options() {#get_original_options__48}


```
 get_original_options() 
```

Получает параметры на основе настроек оригинального файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений.<br/>            Например, если мы загружаем черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) метода, будет получено PNG‑изображение с 8‑битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            в метод [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) в качестве второго параметра.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры, основанные на настройках исходного файла. |


### Method: get_pixel(x, y) {#get_pixel_x_y_49}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_50}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_51}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_52}


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


### Method: get_skew_angle() {#get_skew_angle__53}


```
 get_skew_angle() 
```

Получает угол наклона.<br/>            Этот метод применим к отсканированным текстовым документам для определения угла наклона при сканировании.

**Returns**

| Тип | Описание |
| :- | :- |
| float | Угол наклона в градусах. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_54}


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



**See also:**

**[Example # 1](#example_231)**: The example shows how to validate that the embedded digital signature matches...

**[Example # 2](#example_233)**: The example demonstrates how to verify that the embedded digital signature ma...


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Частично загружает 32‑битные ARGB‑пиксели (по блокам).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник, из которого загружать пиксели. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Частичный загрузчик пикселей. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_64}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Частично загружает 64‑битные ARGB‑пиксели пакетами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Желаемый прямоугольник. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Загрузчик пикселей ARGB 64‑бит. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_65}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Частично загружает пиксели пакетами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Желаемый прямоугольник. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Загрузчик пикселей. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_66}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_67}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_68}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_69}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_70}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_71}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_72}


```
 normalize_angle(resize_proportionally, background_color) 
```

Нормализует угол.<br/>            Этот метод применим к отсканированным текстовым документам для устранения наклона сканирования.<br/>            Метод использует функции [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) и [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| resize_proportionally | bool | если установить значение <c>true</c>, размер изображения будет изменён в соответствии с проекциями повернутого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только внутреннее содержимое изображения. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет фона. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_73}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_74}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_75}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_76}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_77}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_78}


```
 replace_non_transparent_colors(new_color) 
```

Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа‑значение для сохранения плавных краёв.<br/>                Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_79}


```
 replace_non_transparent_colors(new_color_argb) 
```

Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа‑значение для сохранения плавных краёв.<br/>                Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_color_argb | int | Новое значение ARGB цвета для замены непрозрачных цветов. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_80}


```
 resize(new_width, new_height) 
```

Изменяет размер изображения. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_81}


```
 resize(new_width, new_height, resize_type) 
```

Изменяет размер изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_82}


```
 resize(new_width, new_height, settings) 
```

Изменяет размер изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The resize settings. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_83}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_84}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_85}


```
 resize_height_proportionally(new_height) 
```

Пропорционально изменяет высоту. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_86}


```
 resize_height_proportionally(new_height, resize_type) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_87}


```
 resize_height_proportionally(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_88}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_89}


```
 resize_width_proportionally(new_width) 
```

Пропорционально изменяет ширину. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_90}


```
 resize_width_proportionally(new_width, resize_type) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_91}


```
 resize_width_proportionally(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_92}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_93}


```
 rotate(angle) 
```

Повернуть изображение вокруг центра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_94}


```
 rotate(angle, resize_proportionally, background_color) 
```

[RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) image around the center.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resize_proportionally | bool | если установить в <c>true</c>, размер вашего изображения будет изменён<br/>                в соответствии с проекциями повернутого прямоугольника (угловые точки), в противном случае размеры останутся неизменными, и только<br/>                __internal__ содержимое изображения будет повернуто. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет фона. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_95}


```
 rotate_flip(rotate_flip_type) 
```

Поворачивает, отражает или одновременно поворачивает и отражает все страницы.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | The rotate flip type. |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_96}


```
 rotate_flip_all(rotate_flip) 
```

Выполняет вращение и отражение всех.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | The rotate flip. |

### Method: save(file_path) {#save_file_path_97}


```
 save(file_path) 
```

Сохраняет изображение в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_98}


```
 save(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_99}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_100}


```
 save(file_path, over_write) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | если установлено <c>true</c>, перезаписать содержимое файла, иначе будет выполнено добавление. |

### Method: save(stream) {#save_stream_101}


```
 save(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, в который сохраняются данные объекта. |

### Method: save(stream, options_base) {#save_stream_options_base_102}


```
 save(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_103}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_104}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Сохраняет 32-битные ARGB‑пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| пиксели | int[] | The 32-bit ARGB pixels array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_105}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Сохраняет пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| пиксели | int[] | The CMYK pixels presented as the 32-bit integer values. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_106}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Сохраняет пиксели.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The CMYK pixels array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_107}


```
 save_pixels(rectangle, pixels) 
```

Сохраняет основные внутренние пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Пиксели. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_108}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_109}


```
 save_to_stream(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, в который сохраняются данные объекта. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_110}


```
 save_to_stream_with_options(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_111}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_112}


```
 save_with_options(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_113}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_114}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_115}


```
 set_palette(palette, update_colors) 
```

Устанавливает палитру изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Палитра для установки. |
| update_colors | bool | Если установить значение <c>true</c>, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою загрузки изображения, если некоторые индексы не имеют соответствующих записей в палитре. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_116}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_117}


```
 set_resolution(dpi_x, dpi_y) 
```

Устанавливает разрешение для этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dpi_x | float | Горизонтальное разрешение в точках на дюйм для [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Вертикальное разрешение в точках на дюйм для [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_118}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_119}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Индекс строки сканирования, начинающийся с нуля. |
| argb_32_pixels | int[] | Массив 32‑битных ARGB‑цветов для записи. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_120}


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
### The example shows how to validate that the embedded digital signature matches the provided password. {#example_231}
``` python

from aspose.imaging import Image

with Image.load(output_path) as image:
	is_signed = image.is_digital_signed(password, -1)


```

### The example shows how to embed digital signature based on provided password into image pixel data. {#example_232}
``` python

from aspose.imaging import Image

image_file_path = "ball.png"
password = "veryStr0ngPassword"
with Image.load(image_file_path) as image:
	image.embed_digital_signature(password)
	image.save(output_path)


```

### The example demonstrates how to verify that the embedded digital signature matches the provided password against the specified probability threshold. {#example_233}
``` python

from aspose.imaging import Image
  
threshold = 100
with Image.load(output_path) as image:
	is_signed = image.is_digital_signed(password, threshold)


```

### The example illustrates how to determine the probability (from 0% to 100%) that an image contains a digital signature created with the specified password. {#example_234}
``` python

from aspose.imaging import Image

with Image.load(output_path) as image:
	signed_percentage = image.analyze_percentage_digital_signature(password)


```

