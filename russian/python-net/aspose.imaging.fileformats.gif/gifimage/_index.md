---
title: "Класс GifImage"
type: docs
weight: 70
url: /ru/python-net/aspose.imaging.fileformats.gif/gifimage/
---

**Summary:** The API for Graphical Interchange Format (GIF) image file provides<br/>            developers with versatile tools for processing compressed raster images and<br/>            animated GIFs. Offering features like XMP metadata handling, color palette<br/>            settings, background and transparent color control, opacity settings, resize,<br/>            crop, filter application, gamma corrections, contrast adjustment, grayscale<br/>            transformation, and conversion to other formats. This API empowers seamless<br/>            manipulation and enhancement of GIF images for a wide range of applications.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifImage(first_frame)](#GifImage_first_frame_1) | Создание GIF‑изображений становится простым с помощью конструктора [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) <br/>            конструктора. С лишь параметром firstFrame вы погружаетесь в мир динамичной <br/>            визуальной коммуникации. |
| [GifImage(first_frame, global_palette)](#GifImage_first_frame_global_palette_2) | Инициализируйте новый объект [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) с указанными параметрами для <br/>            первого кадра и глобальной палитры. Начните быстро управлять GIF‑изображениями, обеспечивая <br/>            точное представление с настраиваемыми параметрами для оптимальных результатов. |
| [GifImage(first_frame, global_palette, is_palette_sorted, palette_color_resolution, palette_background_color_index, aspect_ratio, has_trailer)](#GifImage_first_frame_global_palette_is_palette_sorted_palette_color_resolution_palette_background_color_index_aspect_ratio_has_trailer_3) | Начните без усилий с конструктором [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/). С помощью этого <br/>            простого метода вы можете легко приступить к созданию анимированных GIF‑файлов. Просто укажите <br/>            firstFrame, globalPalette, paletteColorResolution, aspectRatio и другие <br/>            параметры, и вы будете готовы оживить свои визуальные материалы. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [active_frame](#active_frame1) | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | r/w | Управляйте и изменяйте кадры с помощью этого свойства, обеспечивая плавную навигацию и <br/>            модификацию активного кадра в GIF‑изображении. |
| auto_adjust_palette | bool | r/w | Получает или задает значение, указывающее, следует ли автоматически корректировать палитру. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Управляйте цветом фона GIF‑изображения с помощью этого свойства. Вы можете установить или <br/>            получить цвет фона, чтобы обеспечить согласованность и улучшить визуальную привлекательность. |
| background_color_index | System.Byte | r/w | Контролируйте индекс цвета фона GIF‑изображения с помощью этого свойства. Установите или <br/>            получите индекс, чтобы поддерживать согласованность или достичь желаемых визуальных эффектов. |
| bits_per_pixel | int | r | Получает количество бит на пиксель изображения. |
| blocks | [IGifBlock[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | r | Получайте беспрепятственный доступ к GIF‑блокам с помощью этого свойства, облегчая простое <br/>            извлечение и изменение базовых структур данных изображения. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Получает границы объекта. |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Получает контейнер [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Получает поток данных объекта. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Получает или задаёт экземпляр Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Получайте формат файла без усилий с помощью этого свойства. Это ваш основной источник <br/>            для определения формата ваших файлов. Бесшовно интегрированный в ваш рабочий процесс, <br/>            он предоставляет важную информацию без каких‑либо затруднений. |
| has_alpha | bool | r | Получает значение, указывающее, имеет ли этот экземпляр альфа-канал. |
| has_background_color | bool | r/w | Это свойство определяет, содержит ли GIF‑изображение цвет фона. Если <br/>            true, это указывает, что изображение включает цвет фона. |
| has_trailer | bool | r/w | Управляйте наличием трейлера в ваших GIF‑файлах с помощью этого свойства. Независимо от того, <br/>            нужно ли вам проверить наличие трейлера или установить его присутствие, это свойство упрощает <br/>            процесс. Держите ваши GIF‑файлы структурированными и соответствующими требованиям с этой интуитивной функцией. |
| has_transparent_color | bool | r/w | Определите, включает ли активный кадр GIF‑изображения прозрачный цвет. <br/>            Это свойство предоставляет удобный способ проверить наличие прозрачности в изображении. |
| height | int | r | Получает высоту изображения. |
| horizontal_resolution | float | r/w | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Получите непрозрачность активного кадра в изображении, получая представление о <br/>            уровне его прозрачности. Это свойство особенно полезно для понимания степени <br/>            прозрачности или непрозрачности активного кадра в изображении. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Получает или задает монитор прерываний. |
| is_cached | bool | r | Получает значение, указывающее, кэшируются ли данные изображения в данный момент. |
| is_interlaced | bool | r | Определяет, является ли изображение чересстрочным, влияя на его отображение во время загрузки. Это <br/> свойство предоставляет информацию о поведении рендеринга изображения, что необходимо для <br/> оптимизации стратегий загрузки и улучшения общего качества просмотра. |
| is_palette_sorted | bool | r/w | Управляйте сортировкой палитры в ваших GIF‑изображениях с помощью этого свойства. Независимо от того, нужно ли вам проверить, отсортирована ли палитра, или задать поведение сортировки, это <br/> свойство предоставляет простой способ управлять организацией палитры в ваших <br/> GIF‑файлах. |
| is_raw_data_available | bool | r | Получает значение, указывающее, поддерживается ли загрузка необработанных данных. |
| loops_count | int | r/w | Получите количество повторов без усилий с помощью этого свойства. Если ваше GIF‑изображение содержит информацию о повторениях, это <br/> свойство предоставляет быстрый доступ к количеству повторов, позволяя <br/> беспрепятственно управлять поведением циклов в ваших GIF‑файлах. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Получает или задает XMP‑данные из кадра. |
| page_count | int | r | Получите общее количество страниц, содержащихся в изображении, с помощью этого <br/> простого свойства. Идеально подходит для быстрого оценки объёма содержимого изображения. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Получите доступ к страницам изображения через это удобное свойство, <br/> позволяющее бесшовно перемещаться и манипулировать отдельными страницами по мере необходимости. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| palette_color_resolution_bits | System.Byte | r/w | Управляйте разрешением цветов палитры ваших GIF‑изображений с помощью этого свойства. Регулируйте <br/> количество бит, используемых для представления цветов в палитре, обеспечивая точный контроль <br/> над глубиной цвета и качеством изображения. |
| pixel_aspect_ratio | System.Byte | r/w | Управляйте соотношением сторон пикселя GIF‑изображения с помощью этого свойства. Устанавливайте или получайте <br/> соотношение сторон, чтобы обеспечить точный рендеринг и сохранить визуальную достоверность. |
| premultiply_components | bool | r/w | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умножены. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Получает или задает пользовательский конвертер цветов |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Получает формат необработанных данных. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без конвертации. |
| raw_fallback_index | int | r/w | Получает или задает резервный индекс, используемый, когда индекс палитры выходит за пределы. |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Получает или задает индексированный конвертер цветов |
| raw_line_size | int | r | Получает размер необработанной строки в байтах. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Получает размер объекта. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получите прозрачный цвет активного кадра в GIF‑изображении. Это свойство <br/> позволяет вам получить доступ к конкретному цвету, назначенному как прозрачный <br/> в текущем активном кадре. |
| update_xmp_data | bool | r/w | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| use_palette | bool | r | Получает значение, указывающее, используется ли палитра изображения. |
| use_raw_data | bool | r/w | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда такая загрузка доступна. |
| vertical_resolution | float | r/w | Получает или задает вертикальное разрешение в пикселях на дюйм для этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Получает ширину изображения. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Получает или задает данные Xmp. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_block(block)](#add_block_block_1) | Добавление нового GIF‑блока позволяет включить дополнительные данные в изображение. <br/> Этот метод позволяет вам добавлять пользовательские блоки в GIF‑изображение, которые могут <br/> содержать различные типы информации. |
| [add_page(page)](#add_page_page_2) | Бесшовно интегрируйте новую страницу в существующее изображение, улучшая его содержимое <br/> и расширяя его охват. Этот метод дополняет коллекции изображений дополнительным <br/> контентом, способствуя креативности и гибкости в управлении и композиции изображений. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Регулирует яркость изображения в соответствии с указанным параметром<br/> _brightness_. Этот метод изменяет яркость <br/> всего изображения равномерно, усиливая или уменьшая общую светимость для достижения <br/> желаемого эффекта. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Регулирует контраст изображения, усиливая или уменьшая разницу в <br/> яркости между пикселями. Этот метод изменяет общий тональный диапазон изображения, <br/> делая тёмные области темнее, а светлые — светлее, чтобы улучшить визуальную чёткость <br/> и детали. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Повышайте качество изображения, применяя гамма‑коррекцию. Этот метод регулирует гамму цвета <br/> изображения для достижения оптимальной визуальной чёткости. Он изменяет значение гаммы <br/> каждого пикселя, что приводит к улучшенной цветопередаче и общему виду изображения. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Гамма‑коррекция изображения применяет нелинейную настройку значений пикселей, <br/> усиливая или уменьшая яркость в зависимости от указанных коэффициентов для красного, <br/> зелёного и синего каналов. Этот метод помогает точно настроить цветовой баланс и <br/> светимость изображения, улучшая его общий внешний вид и визуальное качество. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | Вычисляет процентное сходство между извлечёнными данными и оригинальным паролем. |
| auto_brightness_contrast() | Выполняет автоматическую адаптивную нормализацию яркости и контраста для всего изображения. |
| auto_rotate() | Автоматически вращает изображение на основе данных ориентации, извлечённых из Exif <br/> метаданных. Этот метод гарантирует, что изображения отображаются в правильной ориентации, <br/> улучшая пользовательский опыт и устраняя необходимость ручных корректировок. Путём <br/> анализа информации Exif изображение вращается соответствующим образом, обеспечивая бесшовный <br/> просмотр на разных платформах и устройствах. Этот автоматизированный процесс вращения <br/> упрощает работу с изображениями и повышает общую удобность, особенно при <br/> работе с большими партиями изображений с различными ориентациями. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли с <br/> интегральным порогом изображения — это метод преобразования градаций серого в <br/> бинарное изображение. Этот алгоритм вычисляет локальный порог для каждого пикселя на основе <br/> средней интенсивности окружающих пикселей в заданном окне. Путём <br/> адаптивной настройки порога в зависимости от локальной интенсивности пикселей, метод Брэдли <br/> эффективно справляется с вариациями освещения и контраста по всему изображению. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном порогировании изображения |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | Бинаризация изображения с предустановленным порогом преобразует изображение в градациях серого или цветное <br/> изображение в бинарное, где каждый пиксель классифицируется как чёрный или белый <br/> в зависимости от того, превышает ли его значение интенсивности заданный порог. |
| binarize_otsu() | Бинаризация изображения с порогом Оцу — это метод, используемый для автоматического <br/> определения оптимального порогового значения при преобразовании градаций серого в <br/> бинарное изображение. Алгоритм пороговой обработки Оцу вычисляет порог, который <br/> минимизирует внутриклассовую дисперсию интенсивностей пикселей в двух полученных <br/> классах (фон и объект). Эта техника особенно полезна, когда <br/> оптимальное пороговое значение неизвестно и должно определяться адаптивно на основе <br/> гистограммы изображения. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | Смешивает этот экземпляр изображения с изображением _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | Смешивает этот экземпляр изображения с изображением _overlay_. |
| cache_data() | Кеширует данные приватно. |
| [can_load(file_path)](#can_load_file_path_13) | Определяет, можно ли загрузить изображение из указанного пути к файлу. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [can_load(stream)](#can_load_stream_15) | Определяет, можно ли загрузить изображение из указанного потока. |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_17) | Определяет, можно ли загрузить изображение из указанного потока. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [can_save(options)](#can_save_options_20) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| clear_blocks() | Очистка всех GIF‑блоков удаляет любые существующие данные, хранящиеся в изображении. <br/> Эта операция эффективно сбрасывает изображение в пустое состояние, удаляя любые <br/> ранее добавленные блоки. Используйте этот метод, когда необходимо начать с чистого листа для создания или изменения GIF‑изображения. |
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
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_32) | Обрезать изображение со смещениями. |
| [crop(rectangle)](#crop_rectangle_33) | Обрежьте изображение, используя заданную прямоугольную область. Эта операция удаляет внешнюю <br/> часть изображения, оставляя только выбранный регион, определённый прямоугольником. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_34) | Выполняет дизеринг текущего изображения. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_35) | Примените дизеринг к текущему изображению. Этот процесс повышает качество изображения, <br/>            уменьшая цветовые полосы и улучшая переходы цветов, что приводит к более плавному <br/>            внешнему виду. |
| [embed_digital_signature(password)](#embed_digital_signature_password_36) | Вставьте цифровую подпись, основанную на предоставленном пароле, в каждую страницу изображения. |
| [filter(rectangle, options)](#filter_rectangle_options_37) | Примените конкретный фильтр к указанной области изображения, улучшая его визуальное <br/>            качество или изменяя внешний вид по желанию. Этот метод избирательно обрабатывает <br/>            пиксели внутри заданного прямоугольника, позволяя выполнять целевые корректировки <br/>            при сохранении целостности окружающих данных изображения. |
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
| [get_original_options()](#get_original_options__50) | Получите параметры, основанные на настройках оригинального файла, что важно для поддержания точности <br/>            и согласованности при обработке и манипуляции изображениями. Этот метод обеспечивает бесшовную <br/>            интеграцию параметров, специфичных для файла, в последующие операции, гарантируя <br/>            точное воспроизведение и соблюдение присущих изображению характеристик.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений.<br/>            Например, если мы загружаем черно-белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) метода, будет получено PNG‑изображение с 8‑битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            в метод [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) в качестве второго параметра. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Получает пиксель изображения. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Получает пропорциональную высоту. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Получает пропорциональную ширину. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_54) | Преобразует в aps. |
| [get_skew_angle()](#get_skew_angle__55) | Получает угол наклона.<br/>            Этот метод применим к отсканированным текстовым документам для определения угла наклона при сканировании. |
| grayscale() | Преобразование изображения в его градационную (оттенки серого) форму переводит цветное <br/>            изображение в черно‑серую версию, удаляя цветовую информацию при сохранении <br/>            яркости. Этот процесс упрощает изображение до оттенков серого, делая его подходящим <br/>            для различных применений, таких как печать, обработка документов и анализ в градациях серого. |
| [insert_block(index, block)](#insert_block_index_block_56) | Вставка нового блока GIF позволяет добавить пользовательские данные в определённую позицию <br/>            внутри изображения. Этот метод дает возможность разместить пользовательские блоки в нужном <br/>            месте GIF‑изображения, обеспечивая гибкость в организации и структуре <br/>            данных изображения. |
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
| order_blocks() | Упорядочивание блоков GIF в соответствии со спецификацией GIF обеспечивает правильную <br/>            структуру GIF и соответствие стандарту. Этот процесс включает размещение <br/>            блоков в корректной последовательности, определённой спецификацией. Кроме того, он <br/>            может включать удаление некоторых экземпляров [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) , которые <br/>            не необходимы для окончательной структуры. Соблюдая спецификацию GIF, <br/>            полученное изображение будет правильно построено и совместимо с приложениями для просмотра GIF. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_76) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_77) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [remove_block(block)](#remove_block_block_78) | Удаление блока GIF удаляет определённые данные из изображения, предоставляя возможность <br/>            очистить или изменить структуру изображения. Этот метод позволяет удалить нежелательные <br/>            или лишние блоки, оптимизируя GIF‑изображение для эффективного хранения. Используйте эту <br/>            функциональность для устранения устаревшей информации из изображения, сохраняя <br/>            его целостность и качество. |
| remove_metadata() | Удаляет метаданные этого экземпляра изображения, устанавливая значение [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) в **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа‑значение для сохранения плавных краёв. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа‑значение для сохранения плавных краёв.<br/>                Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа‑значение для сохранения плавных краёв.<br/>                Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | Изменяет размер изображения. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | Изменяет размер этого экземпляра [Image](/imaging/python-net/aspose.imaging/image/). |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | Изменяет размер этого экземпляра [Image](/imaging/python-net/aspose.imaging/image/). |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | Изменяет размер изображения. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | Изменяет размер изображения. |
| [resize_full_frame(new_width, new_height, resize_type)](#resize_full_frame_new_width_new_height_resize_type_89) | Изменение размера изображения с учётом всех кадров каждой страницы в <br/>            GIF, тем самым предотвращая появление потенциальных артефактов. Этот метод необходим <br/>            для поддержания целостности и качества изображения, особенно при работе с <br/>            анимированными GIF или последовательностями кадров. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_90) | Пропорционально изменяет высоту. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_91) | Пропорционально изменяет ширину. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_92) | Пропорционально изменяет высоту. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_93) | Пропорционально изменяет высоту. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_94) | Пропорциональное изменение размера сохраняет соотношение сторон изображения при корректировке его <br/>            размеров, гарантируя, что изображение не будет выглядеть растянутым или искажённым. Этот метод <br/>            изменяет размер изображения пропорционально, масштабируя как ширину, так и высоту одинаковым коэффициентом.<br/>            Пропорциональное изменение размера будет применяться к каждому кадру согласно соотношению _newWidth_/width и _newHeight_/height. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_95) | Пропорционально изменяет ширину. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_96) | Пропорционально изменяет ширину. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_97) | Пропорционально изменяет ширину. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_98) | Пропорционально изменяет ширину. |
| [rotate(angle)](#rotate_angle_99) | Повернуть изображение вокруг центра. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_100) | Этот метод вращает изображение вокруг его центральной точки. Указывая угол вращения, вы можете вращать изображение по часовой стрелке или против неё, чтобы достичь <br/>            желаемой ориентации. Это вращение помогает скорректировать представление изображения или <br/>            выравнивание без искажения его содержимого. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_101) | Выполняет вращение, отражение или оба действия только над активным кадром. Эта операция <br/>            применяет преобразования исключительно к текущему активному кадру изображения, <br/>            сохраняя целостность остальных кадров в последовательности. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_102) | Выполняет вращение и отражение всех. |
| save() | Сохраняет данные изображения в базовый поток. |
| [save(file_path)](#save_file_path_103) | Сохраняет изображение в указанное расположение файла. |
| [save(file_path, options)](#save_file_path_options_104) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_105) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save(file_path, over_write)](#save_file_path_over_write_106) | Сохраняет данные объекта в указанное расположение файла. |
| [save(stream)](#save_stream_107) | Сохраняет данные объекта в указанный поток. |
| [save(stream, options_base)](#save_stream_options_base_108) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_109) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_110) | Сохраняет 32-битные ARGB‑пиксели. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_111) | Сохраняет пиксели. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_112) | Сохраняет пиксели.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_113) | Сохраняет основные внутренние пиксели. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_114) | Сохраняет необработанные данные. |
| [save_to_stream(stream)](#save_to_stream_stream_115) | Сохраняет данные объекта в указанный поток. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_116) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117) | Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_118) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_119) | Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_120) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| [set_frame_time(time)](#set_frame_time_time_121) | Настраивает длительность каждого кадра в миллисекундах, обеспечивая согласованное время <br/>            воспроизведения по всей последовательности изображений. Этот метод единообразно задаёт время отображения <br/>            для каждого кадра, позволяя точно контролировать скорость анимации.<br/>            Изменение этого значения сбросит задержку для всех кадров. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_122) | Устанавливает палитру изображения. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_123) | Устанавливает пиксель изображения для указанной позиции. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_124) | Устанавливает разрешение для этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_125) | Пытается установить экземпляр _metadata_, если этот экземпляр [Image](/imaging/python-net/aspose.imaging/image/) поддерживает и реализует экземпляр [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_126) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_127) | Записывает всю строку сканирования в указанный индекс строки сканирования. |


### Constructor: GifImage(first_frame) {#GifImage_first_frame_1}


```
 GifImage(first_frame) 
```

Создание GIF‑изображений становится простым с помощью конструктора [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) <br/>            конструктора. С лишь параметром firstFrame вы погружаетесь в мир динамичной <br/>            визуальной коммуникации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| first_frame | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | Первый кадр, с которым инициализируется GIF‑изображение. |


**See also:**

**[Example # 1](#example_93)**: This example shows how to create a GIF image and save it to a file.

**[Example # 2](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Constructor: GifImage(first_frame, global_palette) {#GifImage_first_frame_global_palette_2}


```
 GifImage(first_frame, global_palette) 
```

Инициализируйте новый объект [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) с указанными параметрами для <br/>            первого кадра и глобальной палитры. Начните быстро управлять GIF‑изображениями, обеспечивая <br/>            точное представление с настраиваемыми параметрами для оптимальных результатов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| first_frame | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | Первый кадр, с которым инициализируется GIF‑изображение. |
| global_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Глобальная палитра, которую следует использовать. Обратите внимание, что если оба _firstFrame_ и _globalPalette_ равны null, будет использована палитра по умолчанию. |


**See also:**

**[Example # 1](#example_94)**: This example shows how to create a GIF image with a custom palette and save i...


### Constructor: GifImage(first_frame, global_palette, is_palette_sorted, palette_color_resolution, palette_background_color_index, aspect_ratio, has_trailer) {#GifImage_first_frame_global_palette_is_palette_sorted_palette_color_resolution_palette_background_color_index_aspect_ratio_has_trailer_3}


```
 GifImage(first_frame, global_palette, is_palette_sorted, palette_color_resolution, palette_background_color_index, aspect_ratio, has_trailer) 
```

Начните без усилий с конструктором [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/). С помощью этого <br/>            простого метода вы можете легко приступить к созданию анимированных GIF‑файлов. Просто укажите <br/>            firstFrame, globalPalette, paletteColorResolution, aspectRatio и другие <br/>            параметры, и вы будете готовы оживить свои визуальные материалы.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| first_frame | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | Первый кадр, с которым инициализируется GIF‑изображение. |
| global_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Глобальная палитра, которую следует использовать. Обратите внимание, что если оба _firstFrame_ и _globalPalette_ равны null, будет использована палитра по умолчанию. |
| is_palette_sorted | bool | если установить в <c>true</c>, палитра будет отсортирована. Обратите внимание, что параметр используется, когда _globalPalette_ не равен null. |
| palette_color_resolution | System.Byte | Разрешение цвета палитры. Обратите внимание, что параметр используется, когда _globalPalette_ не равен null. |
| palette_background_color_index | System.Byte | Индекс фонового цвета палитры. |
| aspect_ratio | System.Byte | Соотношение сторон. |
| has_trailer | bool | если установить в <c>true</c>, у GIF‑изображения будет трейлер, иначе в конце потока трейлер не будет записан. |

### Property: active_frame {#active_frame1}

Управляйте и изменяйте кадры с помощью этого свойства, обеспечивая плавную навигацию и <br/>            модификацию активного кадра в GIF‑изображении.

**See also:**

**[Example # 1](#example_96)**: The following example shows how to remove all blocks from a GIF image.


### Method: add_block(block) {#add_block_block_1}


```
 add_block(block) 
```

Добавление нового GIF‑блока позволяет включить дополнительные данные в изображение. <br/> Этот метод позволяет вам добавлять пользовательские блоки в GIF‑изображение, которые могут <br/> содержать различные типы информации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Блок GIF для добавления. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Бесшовно интегрируйте новую страницу в существующее изображение, улучшая его содержимое <br/> и расширяя его охват. Этот метод дополняет коллекции изображений дополнительным <br/> контентом, способствуя креативности и гибкости в управлении и композиции изображений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Страница для добавления. |


**See also:**

**[Example # 1](#example_217)**: Create multipage GIF image using single page raster images.


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Регулирует яркость изображения в соответствии с указанным параметром<br/> _brightness_. Этот метод изменяет яркость <br/> всего изображения равномерно, усиливая или уменьшая общую светимость для достижения <br/> желаемого эффекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| яркость | int | Значение яркости. |


**See also:**

**[Example # 1](#example_104)**: The following example performs brightness correction of a GIF image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Регулирует контраст изображения, усиливая или уменьшая разницу в <br/> яркости между пикселями. Этот метод изменяет общий тональный диапазон изображения, <br/> делая тёмные области темнее, а светлые — светлее, чтобы улучшить визуальную чёткость <br/> и детали.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| контраст | float | Значение контраста (в диапазоне [-100; 100]) |


**See also:**

**[Example # 1](#example_105)**: The following example performs contrast correction of a GIF image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Повышайте качество изображения, применяя гамма‑коррекцию. Этот метод регулирует гамму цвета <br/> изображения для достижения оптимальной визуальной чёткости. Он изменяет значение гаммы <br/> каждого пикселя, что приводит к улучшенной цветопередаче и общему виду изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |


**See also:**

**[Example # 1](#example_102)**: The following example performs gamma-correction of a GIF image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Гамма‑коррекция изображения применяет нелинейную настройку значений пикселей, <br/> усиливая или уменьшая яркость в зависимости от указанных коэффициентов для красного, <br/> зелёного и синего каналов. Этот метод помогает точно настроить цветовой баланс и <br/> светимость изображения, улучшая его общий внешний вид и визуальное качество.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| gamma_red | float | Коэффициент гаммы для красного канала |
| gamma_green | float | Коэффициент гаммы для зелёного канала |
| gamma_blue | float | Коэффициент гаммы для синего канала |


**See also:**

**[Example # 1](#example_103)**: The following example performs gamma-correction of a GIF image applying diffe...


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

Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли с <br/> интегральным порогом изображения — это метод преобразования градаций серого в <br/> бинарное изображение. Этот алгоритм вычисляет локальный порог для каждого пикселя на основе <br/> средней интенсивности окружающих пикселей в заданном окне. Путём <br/> адаптивной настройки порога в зависимости от локальной интенсивности пикселей, метод Брэдли <br/> эффективно справляется с вариациями освещения и контраста по всему изображению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brightness_difference | float | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном порогировании изображения

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brightness_difference | float | Разница яркости между пикселем и средним значением окна s × s пикселей<br/>                центрированного вокруг этого пикселя. |
| window_size | int | Размер окна s × s пикселей, центрированного вокруг этого пикселя |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

Бинаризация изображения с предустановленным порогом преобразует изображение в градациях серого или цветное <br/> изображение в бинарное, где каждый пиксель классифицируется как чёрный или белый <br/> в зависимости от того, превышает ли его значение интенсивности заданный порог.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| порог | System.Byte | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе — 0. |


**See also:**

**[Example # 1](#example_99)**: The following example binarizes a GIF image with the predefined threshold. Bi...


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

Обрезать изображение со смещениями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| left_shift | int | Сдвиг влево. |
| right_shift | int | Сдвиг вправо. |
| top_shift | int | Сдвиг вверх. |
| bottom_shift | int | Сдвиг вниз. |

### Method: crop(rectangle) {#crop_rectangle_33}


```
 crop(rectangle) 
```

Обрежьте изображение, используя заданную прямоугольную область. Эта операция удаляет внешнюю <br/> часть изображения, оставляя только выбранный регион, определённый прямоугольником.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |


**See also:**

**[Example # 1](#example_98)**: The following example crops a GIF image. The cropping area is be specified vi...


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

Примените дизеринг к текущему изображению. Этот процесс повышает качество изображения, <br/>            уменьшая цветовые полосы и улучшая переходы цветов, что приводит к более плавному <br/>            внешнему виду.

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

Примените конкретный фильтр к указанной области изображения, улучшая его визуальное <br/>            качество или изменяя внешний вид по желанию. Этот метод избирательно обрабатывает <br/>            пиксели внутри заданного прямоугольника, позволяя выполнять целевые корректировки <br/>            при сохранении целостности окружающих данных изображения.

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

Получите параметры, основанные на настройках оригинального файла, что важно для поддержания точности <br/>            и согласованности при обработке и манипуляции изображениями. Этот метод обеспечивает бесшовную <br/>            интеграцию параметров, специфичных для файла, в последующие операции, гарантируя <br/>            точное воспроизведение и соблюдение присущих изображению характеристик.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений.<br/>            Например, если мы загружаем черно-белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) метода, будет получено PNG‑изображение с 8‑битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            в метод [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) в качестве второго параметра.

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


### Method: insert_block(index, block) {#insert_block_index_block_56}


```
 insert_block(index, block) 
```

Вставка нового блока GIF позволяет добавить пользовательские данные в определённую позицию <br/>            внутри изображения. Этот метод дает возможность разместить пользовательские блоки в нужном <br/>            месте GIF‑изображения, обеспечивая гибкость в организации и структуре <br/>            данных изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Элемент с нулевой индексацией, в котором будет вставлен блок. |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Блок GIF для добавления. |

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


### Method: remove_block(block) {#remove_block_block_78}


```
 remove_block(block) 
```

Удаление блока GIF удаляет определённые данные из изображения, предоставляя возможность <br/>            очистить или изменить структуру изображения. Этот метод позволяет удалить нежелательные <br/>            или лишние блоки, оптимизируя GIF‑изображение для эффективного хранения. Используйте эту <br/>            функциональность для устранения устаревшей информации из изображения, сохраняя <br/>            его целостность и качество.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Блок для удаления. |

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

Изменяет размер этого экземпляра [Image](/imaging/python-net/aspose.imaging/image/).

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

Изменяет размер этого экземпляра [Image](/imaging/python-net/aspose.imaging/image/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Настройки. |

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

### Method: resize_full_frame(new_width, new_height, resize_type) {#resize_full_frame_new_width_new_height_resize_type_89}


```
 resize_full_frame(new_width, new_height, resize_type) 
```

Изменение размера изображения с учётом всех кадров каждой страницы в <br/>            GIF, тем самым предотвращая появление потенциальных артефактов. Этот метод необходим <br/>            для поддержания целостности и качества изображения, особенно при работе с <br/>            анимированными GIF или последовательностями кадров.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_90}


```
 resize_height_proportionally(new_height) 
```

Пропорционально изменяет высоту. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_91}


```
 resize_height_proportionally(new_height, resize_type) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_92}


```
 resize_height_proportionally(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_93}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_94}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Пропорциональное изменение размера сохраняет соотношение сторон изображения при корректировке его <br/>            размеров, гарантируя, что изображение не будет выглядеть растянутым или искажённым. Этот метод <br/>            изменяет размер изображения пропорционально, масштабируя как ширину, так и высоту одинаковым коэффициентом.<br/>            Пропорциональное изменение размера будет применяться к каждому кадру согласно соотношению _newWidth_/width и _newHeight_/height.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_95}


```
 resize_width_proportionally(new_width) 
```

Пропорционально изменяет ширину. По умолчанию используется [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_96}


```
 resize_width_proportionally(new_width, resize_type) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_97}


```
 resize_width_proportionally(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_98}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_99}


```
 rotate(angle) 
```

Повернуть изображение вокруг центра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_100}


```
 rotate(angle, resize_proportionally, background_color) 
```

Этот метод вращает изображение вокруг его центральной точки. Указывая угол вращения, вы можете вращать изображение по часовой стрелке или против неё, чтобы достичь <br/>            желаемой ориентации. Это вращение помогает скорректировать представление изображения или <br/>            выравнивание без искажения его содержимого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resize_proportionally | bool | если установлено <c>true</c>, размер вашего изображения будет изменён<br/>
            в соответствии с проекциями повернутого прямоугольника (угловых точек) в остальных
            случаях, когда размеры остаются нетронутыми, и только
            __internal__ содержимое изображения вращается. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет фона. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_101}


```
 rotate_flip(rotate_flip_type) 
```

Выполняет вращение, отражение или оба действия только над активным кадром. Эта операция <br/>            применяет преобразования исключительно к текущему активному кадру изображения, <br/>            сохраняя целостность остальных кадров в последовательности.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | The rotate flip type. |


**See also:**

**[Example # 1](#example_97)**: This example loads a GIF image, rotates it by 90 degrees clockwise and option...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_102}


```
 rotate_flip_all(rotate_flip) 
```

Выполняет вращение и отражение всех.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | The rotate flip. |

### Method: save(file_path) {#save_file_path_103}


```
 save(file_path) 
```

Сохраняет изображение в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_104}


```
 save(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Параметры. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_105}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_106}


```
 save(file_path, over_write) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | если установлено <c>true</c>, перезаписать содержимое файла, иначе будет выполнено добавление. |

### Method: save(stream) {#save_stream_107}


```
 save(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, в который сохраняются данные объекта. |

### Method: save(stream, options_base) {#save_stream_options_base_108}


```
 save(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в заданном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_109}


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

Сохраняет основные внутренние пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Пиксели. |

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

### Method: set_frame_time(time) {#set_frame_time_time_121}


```
 set_frame_time(time) 
```

Настраивает длительность каждого кадра в миллисекундах, обеспечивая согласованное время <br/>            воспроизведения по всей последовательности изображений. Этот метод единообразно задаёт время отображения <br/>            для каждого кадра, позволяя точно контролировать скорость анимации.<br/>            Изменение этого значения сбросит задержку для всех кадров.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| время | int | Время длительности кадра в миллисекундах. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_122}


```
 set_palette(palette, update_colors) 
```

Устанавливает палитру изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Палитра для установки. |
| update_colors | bool | Если установить значение <c>true</c>, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою загрузки изображения, если некоторые индексы не имеют соответствующих записей в палитре. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_123}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_124}


```
 set_resolution(dpi_x, dpi_y) 
```

Устанавливает разрешение для этого [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dpi_x | float | Горизонтальное разрешение в точках на дюйм для [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Вертикальное разрешение в точках на дюйм для [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_125}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_126}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Индекс строки сканирования, начинающийся с нуля. |
| argb_32_pixels | int[] | Массив 32‑битных ARGB‑цветов для записи. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_127}


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
### This example shows how to create a GIF image and save it to a file. {#example_93}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color


# Создать блок кадра GIF размером 100×100 пикселей.
with GifFrameBlock(100, 100) as firstBlock:
	# Заполнить весь блок красным цветом.
	gr = Graphics(firstBlock)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, firstBlock.bounds)

	with GifImage(firstBlock) as gifImage:
		gifImage.save("output.gif")


```

### This example shows how to create a GIF image with a custom palette and save it to a file. {#example_94}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color, ColorPaletteHelper


# Создать блок кадра GIF размером 100×100 пикселей.
with GifFrameBlock(100, 100) as firstBlock:
	# Заполнить весь блок красным цветом.
	gr = Graphics(firstBlock)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, firstBlock.bounds)

	# Использовать 4-битную палитру для уменьшения размера изображения. Качество может ухудшиться.
	palette = ColorPaletteHelper.create_4_bit()

	with GifImage(firstBlock, palette) as gifImage:
		gifImage.save("output.gif")


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# Создать GIF‑изображение 100 × 100 px.
# Первый блок по умолчанию полностью чёрный.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# Первый круг красный
		brush1 = SolidBrush(Color.red)

		# Второй круг чёрный
		brush2 = SolidBrush(Color.black)

		# Постепенно увеличивать угол красной дуги.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Постепенно увеличивать угол чёрной дуги и стирать красную дугу.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush2, block.bounds, 0, angle)
			gr.fill_pie(brush1, block.bounds, angle, 360 - angle)
			gifImage.add_block(block)

		gifImage.save("animated_radar.gif")


```

### The following example shows how to remove all blocks from a GIF image. {#example_96}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 

# Создать GIF‑изображение 100 × 100 px.
# Первый блок по умолчанию полностью чёрный.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		if gifImage.active_frame is not None:
			print(f"Active frame size: {gifImage.active_frame.size}")
		else:
			print("Active frame is not set")

		print("Clear all the blocks")
		gifImage.clear_blocks()

		if gifImage.active_frame is not None:
			print(f"Active frame size: {gifImage.active_frame.size}")
		else:
			print("Active frame is not set")

# Вывод выглядит так:
# Размер активного кадра: { Width = 100, Height = 100}
# Очистить все блоки
# Активный кадр не установлен

```

### This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_97}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# Повернуть, отразить и сохранить в выходной файл.
	with aspycore.as_of(Image.load(join(dir_, "sample.gif")), GifImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example crops a GIF image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_98}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.gif import GifImage
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Обрезать изображение. Область обрезки — прямоугольная центральная часть изображения.
	area = Rectangle(gif_image.width // 4, gif_image.height // 4, gif_image.width // 2,
					 gif_image.height // 2)
	gif_image.crop(area)
	# Сохранить обрезанное изображение в PNG.
	gif_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example binarizes a GIF image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_99}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	djvu_image = aspycore.as_of(image, GifImage)
	# Бинаризовать изображение с пороговым значением 127.
	# Если соответствующее серое значение пикселя больше 127, ему будет присвоено значение 255, иначе 0.
	djvu_image.binarize_fixed(127)
	djvu_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example performs gamma-correction of a GIF image. {#example_102}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp\\"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Установить коэффициент гаммы для красного, зелёного и синего каналов.
	gif_image.adjust_gamma(2.5)
	gif_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a GIF image applying different coefficients for color components. {#example_103}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Установить отдельные коэффициенты гаммы для красного, зелёного и синего каналов.
	gif_image.adjust_gamma(1.5, 2.5, 3.5)
	gif_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a GIF image. {#example_104}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Установить значение яркости. Допустимые значения яркости находятся в диапазоне [-255, 255].
	gif_image.adjust_brightness(50)
	gif_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a GIF image. {#example_105}
``` python


import aspose.pycore as aspycore

from aspose.imaging import Image

from aspose.imaging.fileformats.gif import GifImage

from aspose.imaging.imageoptions import PngOptions

from os.path import join



dir_ = "c:\\temp"

with Image.load(join(dir_, "sample.gif")) as image:

	gif_image = aspycore.as_of(image, GifImage)

	# Установить значение контрастности. Допустимые значения контрастности находятся в диапазоне [-100f, 100f].

	gif_image.adjust_contrast(50.0)

	gif_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())



# ExEnd

```

### Create multipage GIF image using single page raster images. {#example_217}
``` python
from aspose.imaging import Image, RasterImage
from aspose.pycore import as_of
from os import listdir
from os.path import isfile, join

def load_frames(directory):
	for f in listdir(directory):
		full_path = join(directory, f)
		if isfile(full_path):
			yield as_of(Image.load(file_path), RasterImage)


# Загрузить кадры
frames = list(load_frames("Animation frames"))
# Создать GIF‑изображение, используя первый кадр
with GifImage(GifFrameBlock(frames[0])) as image:
	# Добавить кадры в GIF‑изображение с помощью метода AddPage
	for index in range(1, len(frames)):
		image.add_page(frames[index])

	# Сохранить GIF‑изображение
	image.save("Multipage.gif")
	
for it in frames:
	with it as _:
		# освободить изображения
		pass


```

### Export of part of animation from GIF image based on time interval. {#example_223}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import GifOptions, MultiPageOptions, MultiPageMode, TimeInterval

with Image.load("Animation.gif") as image:
	obj_init = MultiPageOptions()
	obj_init.mode = MultiPageMode.TIME_INTERVAL
	obj_init.time_interval = TimeInterval(0, 400)
	options = GifOptions()
	options.full_frame = True
	options.multi_page_options = obj_init
	image.save("PartOfAnimation.gif", options)


```

