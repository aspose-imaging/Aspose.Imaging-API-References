---
title: "BmpImage Sınıfı"
type: docs
weight: 50
url: /tr/python-net/aspose.imaging.fileformats.bmp/bmpimage/
---

**Summary:** You can effortlessly handle Bitmap (BMP) and Device Independent Bitmap<br/>            (DIB) files, facilitating efficient manipulation and processing of raster<br/>            images. Performing various operations on images, this API streamlines the<br/>            workflow, offering developers a reliable toolkit for working with BMP and<br/>            DIB formats in their software applications.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BmpImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [BmpImage(path)](#BmpImage_path_1) | Bu yapıcıyı kullanarak BmpImage sınıfını zahmetsizce kullanmaya başlayın<br/>            yeni bir örnek başlatır. Hızlı ve verimli bir şekilde [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) nesnelerini başlatmak ve çalıştırmak isteyen geliştiriciler için mükemmeldir. |
| [BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_2) | Bu yapıcıyı kullanarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini zahmetsizce oluşturun,<br/>            path, bitsPerPixel ve compression gibi belirtilen parametreleri kullanarak. BmpImage nesnelerini hızlı ve verimli bir şekilde başlatmak isteyen geliştiriciler için idealdir,<br/>            görüntü özellikleri üzerinde hassas kontrol sağlayarak. |
| [BmpImage(raster_image)](#BmpImage_raster_image_3) | Bir RasterImage nesnesiyle başlatarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini zahmetsizce oluşturun<br/>            . Mevcut raster görüntülerini BmpImage formatına sorunsuz bir şekilde dönüştürmek isteyen geliştiriciler için mükemmeldir,<br/>            uyumluluk ve projelerine entegrasyon kolaylığı sağlar. |
| [BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_4) | [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın, yeni bir örnek oluşturarak<br/>            bir rasterImage ve bitsPerPixel ile compression gibi belirtilen parametreleri kullanın.<br/>            BmpImage nesnelerini yönetmek için basit bir yol arayan geliştiriciler için mükemmeldir,<br/>            projelerinde esneklik ve verimlilik sağlar. |
| [BmpImage(stream)](#BmpImage_stream_5) | Bu yapıcıyı kullanarak bir akış (stream) girdi olarak vererek yeni bir örnek başlatarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfını zahmetsizce kullanmaya başlayın.<br/>            Çeşitli veri kaynaklarından BmpImage nesneleriyle çalışmak isteyen geliştiriciler için<br/>            uygun bir yol sunar, esneklik ve entegrasyon kolaylığı sağlar. |
| [BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_6) | [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın, bir akış (stream) kullanarak yeni bir örnek oluşturun ve bitsPerPixel ve compression gibi belirtilen parametreleri ekleyin.<br/>            BmpImage nesnelerini yönetmek için basit bir yol arayan geliştiriciler için mükemmeldir,<br/>            projelerinde esneklik ve verimlilik sağlar. |
| [BmpImage(width, height)](#BmpImage_width_height_7) | Belirtilen genişlik ve yükseklik parametreleriyle yeni bir örnek oluşturarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfını zahmetsizce kullanmaya başlayın.<br/>            Özel boyutlarda BmpImage nesneleri oluşturmak isteyen geliştiriciler için idealdir,<br/>            projelerine esneklik ve entegrasyon kolaylığı sağlar. |
| [BmpImage(width, height, bits_per_pixel, palette)](#BmpImage_width_height_bits_per_pixel_palette_8) | Genişlik, yükseklik, bit derinliği ve palet gibi parametrelerle yeni bir örnek başlatarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfını sorunsuz bir şekilde kullanmaya başlayın.<br/>            Özel boyutlar ve renk yapılandırmalarıyla BmpImage nesneleri oluşturmak isteyen geliştiriciler için mükemmeldir,<br/>            projelerinde esneklik ve verimlilik sağlar. |
| [BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution)](#BmpImage_width_height_bits_per_pixel_palette_compression_horizontal_resolution_vertical_resolution_9) | Bu yapıcıyı kullanarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini zahmetsizce oluşturun,<br/>            genişlik, yükseklik, bitsPerPixel ve palet gibi parametreleri belirterek. Özel boyutlar ve renk yapılandırmalarıyla BmpImage nesneleri üretmek isteyen geliştiriciler için mükemmeldir,<br/>            projelerine esneklik ve entegrasyon kolaylığı sağlar. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Arka plan renginin değerini alır veya ayarlar. |
| [bitmap_info_header](#bitmap_info_header1) | [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | r | Bu basit işlevle bitmap görüntünüzle ilgili temel ayrıntılara hızlıca erişin.<br/>            Görüntülerinin başlık bilgilerini almak isteyen geliştiriciler için mükemmeldir. |
| [bits_per_pixel](#bits_per_pixel2) | int | r | Bu özelliği kullanarak görüntünün piksel başına bit sayısına kolayca erişin.<br/>            Görüntü kalitesi ve derinliği hakkında hızlı bilgi arayan geliştiriciler için mükemmeldir. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Nesnenin sınırlarını alır. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [compression](#compression3) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r | Bu özellik ile görüntü için kullanılan sıkıştırma türünü zahmetsizce alın.<br/>            Görüntü sıkıştırması hakkında hızlıca bilgiye ihtiyaç duyan geliştiriciler için mükemmeldir. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Bu [Image](/imaging/python-net/aspose.imaging/image/) kapsayıcısını alır. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Nesnenin veri akışını alır. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif örneğini alır veya ayarlar. |
| [file_format](#file_format4) | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Bu kullanıcı dostu özellik ile dosya formatı değerini kolayca alın.<br/>            Dosya formatı hakkında hızlı bilgiye ihtiyaç duyan geliştiriciler için idealdir. |
| has_alpha | bool | r | Bu örneğin alfa içerip içermediğini gösteren bir değeri alır. |
| has_background_color | bool | r/w | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| has_transparent_color | bool | r/w | Bu [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) örneğinin şeffaf bir renge sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [height](#height5) | int | r | Bu özellik ile görüntünün yüksekliğini zahmetsizce alın.<br/>            Görüntü boyutları hakkında hızlı bilgiye ihtiyaç duyan geliştiriciler için idealdir. |
| [horizontal_resolution](#horizontal_resolution6) | float | r/w | Bu özellik, [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) nesnesinin yatay çözünürlüğünü (inç başına piksel olarak ölçülen) kolayca almanızı veya ayarlamanızı sağlar.<br/>            Hassas görüntü çözünürlüğü kontrolüne ihtiyaç duyan geliştiriciler için idealdir. |
| image_opacity | float | r | Bu görüntünün opaklığını alır. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Kesinti izleyicisini alır veya ayarlar. |
| is_cached | bool | r | Görüntü verisinin şu anda önbelleğe alınıp alınmadığını gösteren bir değeri alır. |
| is_raw_data_available | bool | r | Ham veri yüklemesinin desteklenip desteklenmediğini gösteren bir değeri alır. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Görüntünün meta verilerini alır. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| premultiply_components | bool | r/w | Görüntü bileşenlerinin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Özel renk dönüştürücüyü alır veya ayarlar |
| [raw_data_format](#raw_data_format7) | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Bu kullanıcı dostu işlev ile ham verinizin formatını kolayca elde edin.<br/>            Veri formatı hakkında kritik bilgilere hızlıca erişmek isteyen geliştiriciler için mükemmeldir. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Mevcut ham veri ayarlarını alır. Bu ayarları kullanırken verinin dönüşüm olmadan yüklendiğini unutmayın. |
| raw_fallback_index | int | r/w | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır veya ayarlar |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Dizinli renk dönüştürücüyü alır veya ayarlar |
| [raw_line_size](#raw_line_size8) | int | r | Bu basit özellik ile her ham satırın bayt cinsinden boyutuna hızlıca erişin.<br/>            Ham görüntü verisini verimli bir şekilde işlemek isteyen geliştiriciler için idealdir. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Nesne boyutunu alır. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Görüntünün şeffaf rengini alır. |
| update_xmp_data | bool | r/w | XMP meta verilerini güncelleyip güncellemeyeceğini gösteren bir değeri alır veya ayarlar. |
| use_palette | bool | r | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| use_raw_data | bool | r/w | Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılıp kullanılmayacağını gösteren bir değeri alır veya ayarlar. |
| [vertical_resolution](#vertical_resolution9) | float | r/w | Bu özellik ile bu [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) nesnesinin dikey çözünürlüğünü (inç başına piksel olarak ölçülen) kolayca alabilir veya ayarlayabilirsiniz.<br/>            Uygulamalarında görüntü çözünürlüğü üzerinde hassas kontrol gerektiren geliştiriciler için mükemmeldir. |
| [width](#width10) | int | r | Genişliğe bu özellik ile kolayca erişin.<br/>            Görüntü boyutları hakkında hızlı bilgi arayan geliştiriciler için idealdir. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Xmp verilerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Görüntü için parlaklık ayarı. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Görüntü kontrastı |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Bir görüntünün gama düzeltmesi. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Bir görüntünün gama düzeltmesi. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | Çıkarılan veri ile orijinal şifre arasındaki yüzde benzerliğini hesaplar. |
| auto_brightness_contrast() | Tüm görüntü için otomatik uyarlamalı parlaklık ve kontrast normalizasyonu gerçekleştirir. |
| auto_rotate() | Exif <br/>            meta veriler. Bu yöntem, görüntülerin doğru yönlendirmede gösterilmesini sağlar, <br/>            kullanıcı deneyimini artırır ve manuel ayarlama ihtiyacını ortadan kaldırır. İle <br/>            Exif bilgilerini analiz ederek, görüntü buna göre döndürülür, sorunsuz bir <br/>            farklı platform ve cihazlarda görüntüleme deneyimi sağlar. Bu otomatik döndürme <br/>            süreci, görüntü işlemini basitleştirir ve özellikle <br/>            farklı yönlerdeki büyük görüntü gruplarıyla çalışırken genel kullanılabilirliği artırır. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Bradley'nin uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Bradley'nin uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi |
| binarize_otsu() | Otsu eşikleme ile bir görüntünün ikilileştirilmesi |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_9) | Bu görüntü örneğini _overlay_ görüntüsüyle karıştırır. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_10) | Bu görüntü örneğini _overlay_ görüntüsüyle karıştırır. |
| cache_data() | Verileri önbelleğe alır ve temel [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
| [can_load(file_path)](#can_load_file_path_11) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_12) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler. |
| [can_load(stream)](#can_load_stream_13) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load(stream, load_options)](#can_load_stream_load_options_14) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen _loadOptions_ kullanılarak belirler. |
| [can_load_stream(stream)](#can_load_stream_stream_15) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_16) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen _loadOptions_ kullanılarak belirler. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_17) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler. |
| [can_save(options)](#can_save_options_18) | Geçilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına görüntünün kaydedilip kaydedilemeyeceğini belirler. |
| [create(files)](#create_files_19) | Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_20) | Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur. |
| [create(image_options, width, height)](#create_image_options_width_height_21) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_22) | Sağlanan piksel dizisinden bir [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) örneği oluşturur.<br/>            <br/>            Belirtilen genişlik ve yüksekliğin piksel verisinin boyutlarıyla eşleştiğini doğrular.<br/>            Bu yöntem yalnızca kütüphane Lisanslı modda olduğunda kullanılabilir. |
| [create(images)](#create_images_23) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create(images, dispose_images)](#create_images_dispose_images_24) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create(multipage_create_options)](#create_multipage_create_options_25) | Belirtilen çok sayfalı oluşturma seçeneklerini oluşturur. |
| [create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_file_with_params_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_26) | Bu yapıcı ile BmpImage sınıfını kolayca kullanmaya başlayın, yeni bir örnek başlatma sürecini basitleştirir.<br/>            Projelerine [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) nesnelerini hızlı ve verimli bir şekilde dahil etmek isteyen geliştiriciler için idealdir. |
| [create_from_files(files)](#create_from_files_files_27) | Belirtilen dosyaları tembel yükleme sayfaları olarak içeren çok sayfalı bir görüntü oluşturur. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_28) | Belirtilen dosyaları tembel yükleme sayfaları olarak içeren çok sayfalı bir görüntü oluşturur. |
| [create_from_image(raster_image)](#create_from_image_raster_image_29) | [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini başlatır. |
| [create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_image_with_params_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_30) | [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini başlatır. |
| [create_from_images(images)](#create_from_images_images_31) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create_from_stream(stream)](#create_from_stream_stream_33) | [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini başlatır. |
| [create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_stream_with_params_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_34) | [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini başlatır. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_35) | Kaydırmalarla görüntüyü kırp. |
| [crop(rectangle)](#crop_rectangle_36) | Görüntüyü kırpma. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_37) | Mevcut görüntüde dithering uygular. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_38) | Mevcut görüntüde dithering uygular. |
| [embed_digital_signature(password)](#embed_digital_signature_password_39) | Sağlanan şifreye dayalı dijital imzayı steganografi kullanarak görüntüye göm. |
| [filter(rectangle, options)](#filter_rectangle_options_40) | Belirtilen dikdörtgeni filtreler. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_41) | Bir görüntünün 32-bit ARGB pikselini alır. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_42) | Varsayılan 32-bit ARGB piksel dizisini alır. |
| [get_default_options(args)](#get_default_options_args_43) | Bu basit yöntem ile varsayılan seçenekleri zahmetsizce alın.<br/>            Varsayılan görüntü ayarları veya yapılandırmalarına hızlı erişmek isteyen geliştiriciler için idealdir. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_44) | Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_46) | Varsayılan ham veri dizisini alır. |
| [get_file_format(file_path)](#get_file_format_file_path_47) | Dosya biçimini alır. |
| [get_file_format(stream)](#get_file_format_stream_48) | Dosya biçimini alır. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_49) | Dosya biçimini alır. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_50) | Mevcut görüntüyü saran dikdörtgeni alır. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_51) | Mevcut görüntüyü saran dikdörtgeni alır. |
| [get_modify_date(use_default)](#get_modify_date_use_default_52) | Kaynak görüntünün en son değiştirildiği tarih ve saati alır. |
| [get_original_options()](#get_original_options__53) | Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirilmemiş tutmak için faydalı olabilir.<br/>            Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yüklerseniz ve ardından bunu kullanarak<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) yöntemiyle, 8-bit piksel başına sahip bir çıktı PNG görüntüsü üretilecektir.<br/>            Bunu önlemek ve 1-bit piksel başına PNG görüntüsü kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) yöntemine ikinci parametre olarak geçirin. |
| [get_pixel(x, y)](#get_pixel_x_y_54) | Bir görüntü pikselini alır. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_55) | Orantılı bir yükseklik alır. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_56) | Orantılı bir genişlik alır. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_57) | aps'ye dönüştürür. |
| [get_skew_angle()](#get_skew_angle__58) | Eğim açısını alır.<br/>            Bu yöntem taranmış metin belgelerine uygulanabilir, tarama sırasında eğim açısını belirlemek için. |
| grayscale() | Bir görüntünün gri tonlamalı temsiline dönüşümü |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_59) | Sağlanan şifre ve eşik değeri kullanarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder. |
| [load(file_path)](#load_file_path_60) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| [load(file_path, load_options)](#load_file_path_load_options_61) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| [load(stream)](#load_stream_62) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(stream, load_options)](#load_stream_load_options_63) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_64) | 32-bit ARGB piksellerini yükler. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_65) | 64-bit ARGB piksellerini yükler. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_66) | CMYK formatında pikselleri yükler. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_67) | CMYK formatında pikselleri yükler.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) yöntemini kullanın. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_68) | 32-bit ARGB piksellerini kısmen (bloklar halinde) yükler. |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_69) | 64-bit ARGB piksellerini paketler halinde kısmen yükler. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_70) | Pikselleri paketler halinde kısmen yükler. |
| [load_pixels(rectangle)](#load_pixels_rectangle_71) | Pikselleri yükler. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_72) | Ham veriyi yükler. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_73) | Ham veriyi yükler. |
| [load_stream(stream)](#load_stream_stream_74) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_75) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_76) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| normalize_angle() | Açıyı normalleştirir.<br/>            Bu yöntem, eğik taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir.<br/>            Bu yöntem, [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) ve [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) metodlarını kullanır. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_77) | Açıyı normalleştirir.<br/>            Bu yöntem, taranmış metin belgelerinde eğik taramayı gidermek için uygulanabilir.<br/>            Bu yöntem, [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) ve [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) metodlarını kullanır. |
| normalize_histogram() | Görüntü histogramını normalleştirir — piksel değerlerini tüm kullanılabilir aralığı kapsayacak şekilde ayarlar. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_78) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_79) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| remove_metadata() | Bu görüntü örneğinin meta verilerini, bu [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) değerini **None** olarak ayarlayarak kaldırır. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_80) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_81) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_82) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_83) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak yumuşak kenarları korur.<br/>            Not: şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_84) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak yumuşak kenarları korur.<br/>            Not: şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [resize(new_width, new_height)](#resize_new_width_new_height_85) | Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_86) | Görüntüyü yeniden boyutlandırır. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_87) | Görüntüyü yeniden boyutlandırır. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_88) | Görüntüyü yeniden boyutlandırır. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_89) | Görüntüyü yeniden boyutlandırır. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_90) | Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_91) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_92) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_93) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_94) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_95) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_96) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_97) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [rotate(angle)](#rotate_angle_98) | Görüntüyü merkezin etrafında döndür. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_99) | Görüntüyü merkezin etrafında döndür. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_100) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| save() | Görüntü verilerini temel akıma kaydeder. |
| [save(file_path)](#save_file_path_101) | Görüntüyü belirtilen dosya konumuna kaydeder. |
| [save(file_path, options)](#save_file_path_options_102) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_103) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save(file_path, over_write)](#save_file_path_over_write_104) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(stream)](#save_stream_105) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save(stream, options_base)](#save_stream_options_base_106) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_107) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_108) | 32-bit ARGB piksellerini kaydeder. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_109) | Pikselleri kaydeder. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_110) | Pikselleri kaydeder.<br/>            Bu yöntem artık kullanılmamaktadır. Lütfen daha etkili olan [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) yöntemini kullanın. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_111) | Pikselleri kaydeder (format özel yöntemi). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_112) | Ham veriyi kaydeder. |
| [save_to_stream(stream)](#save_to_stream_stream_113) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_114) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_115) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_116) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_117) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_118) | Belirtilen konum için bir görüntünün 32-bit ARGB pikselini ayarlar. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_119) | Görüntü paletini ayarlar. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_120) | Belirtilen konum için bir görüntü pikselini ayarlar. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_121) | Bu kullanıcı dostu yöntem ile [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) çözünürlüğünüzü zahmetsizce ayarlayın.<br/>            Hassas kontrol arayan geliştiriciler için mükemmeldir.<br/>            Görüntü çözünürlüğü üzerinde hassas kontrol isteyen geliştiriciler için idealdir. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_122) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_123) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_124) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |


### Constructor: BmpImage(path) {#BmpImage_path_1}


```
 BmpImage(path) 
```

Bu yapıcıyı kullanarak BmpImage sınıfını zahmetsizce kullanmaya başlayın<br/>            yeni bir örnek başlatır. Hızlı ve verimli bir şekilde [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) nesnelerini başlatmak ve çalıştırmak isteyen geliştiriciler için mükemmeldir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Görüntünün yükleneceği ve piksel ile palet verilerinin başlatılacağı yol. |


**See also:**

**[Example # 1](#example_77)**: The example shows how to load a BmpImage from a file.


### Constructor: BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_2}


```
 BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Bu yapıcıyı kullanarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini zahmetsizce oluşturun,<br/>            path, bitsPerPixel ve compression gibi belirtilen parametreleri kullanarak. BmpImage nesnelerini hızlı ve verimli bir şekilde başlatmak isteyen geliştiriciler için idealdir,<br/>            görüntü özellikleri üzerinde hassas kontrol sağlayarak.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Görüntünün yükleneceği ve piksel ile palet verilerinin başlatılacağı yol. |
| bits_per_pixel | int | Piksel başına bit. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kullanılacak sıkıştırma. |
| horizontal_resolution | float | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| vertical_resolution | float | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |


**See also:**

**[Example # 1](#example_78)**: The example shows how to load a BmpImage from a file with the specified bit d...


### Constructor: BmpImage(raster_image) {#BmpImage_raster_image_3}


```
 BmpImage(raster_image) 
```

Bir RasterImage nesnesiyle başlatarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini zahmetsizce oluşturun<br/>            . Mevcut raster görüntülerini BmpImage formatına sorunsuz bir şekilde dönüştürmek isteyen geliştiriciler için mükemmeldir,<br/>            uyumluluk ve projelerine entegrasyon kolaylığı sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Piksel ve palet verilerini başlatmak için kullanılacak görüntü. |


**See also:**

**[Example # 1](#example_81)**: The example shows how to load a BmpImage from another instance of RasterImage.


### Constructor: BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_4}


```
 BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

[BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın, yeni bir örnek oluşturarak<br/>            bir rasterImage ve bitsPerPixel ile compression gibi belirtilen parametreleri kullanın.<br/>            BmpImage nesnelerini yönetmek için basit bir yol arayan geliştiriciler için mükemmeldir,<br/>            projelerinde esneklik ve verimlilik sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Piksel ve palet verilerini başlatmak için kullanılacak görüntü. |
| bits_per_pixel | int | Piksel başına bit. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kullanılacak sıkıştırma. |
| horizontal_resolution | float | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| vertical_resolution | float | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |


**See also:**

**[Example # 1](#example_82)**: The example shows how to load a BmpImage from another instance of RasterImage...


### Constructor: BmpImage(stream) {#BmpImage_stream_5}


```
 BmpImage(stream) 
```

Bu yapıcıyı kullanarak bir akış (stream) girdi olarak vererek yeni bir örnek başlatarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfını zahmetsizce kullanmaya başlayın.<br/>            Çeşitli veri kaynaklarından BmpImage nesneleriyle çalışmak isteyen geliştiriciler için<br/>            uygun bir yol sunar, esneklik ve entegrasyon kolaylığı sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün yükleneceği ve piksel ile palet verilerinin başlatılacağı akış. |


**See also:**

**[Example # 1](#example_79)**: The example shows how to load a BmpImage from a file stream.


### Constructor: BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_6}


```
 BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

[BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın, bir akış (stream) kullanarak yeni bir örnek oluşturun ve bitsPerPixel ve compression gibi belirtilen parametreleri ekleyin.<br/>            BmpImage nesnelerini yönetmek için basit bir yol arayan geliştiriciler için mükemmeldir,<br/>            projelerinde esneklik ve verimlilik sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün yükleneceği ve piksel ile palet verilerinin başlatılacağı akış. |
| bits_per_pixel | int | Piksel başına bit. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kullanılacak sıkıştırma. |
| horizontal_resolution | float | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| vertical_resolution | float | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |


**See also:**

**[Example # 1](#example_80)**: The example shows how to load a BmpImage from a file stream with the specifie...


### Constructor: BmpImage(width, height) {#BmpImage_width_height_7}


```
 BmpImage(width, height) 
```

Belirtilen genişlik ve yükseklik parametreleriyle yeni bir örnek oluşturarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfını zahmetsizce kullanmaya başlayın.<br/>            Özel boyutlarda BmpImage nesneleri oluşturmak isteyen geliştiriciler için idealdir,<br/>            projelerine esneklik ve entegrasyon kolaylığı sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | int | Görüntü genişliği. |
| height | int | Görüntü yüksekliği. |


**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_83)**: The example shows how to create a BmpImage of the specified size.


### Constructor: BmpImage(width, height, bits_per_pixel, palette) {#BmpImage_width_height_bits_per_pixel_palette_8}


```
 BmpImage(width, height, bits_per_pixel, palette) 
```

Genişlik, yükseklik, bit derinliği ve palet gibi parametrelerle yeni bir örnek başlatarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfını sorunsuz bir şekilde kullanmaya başlayın.<br/>            Özel boyutlar ve renk yapılandırmalarıyla BmpImage nesneleri oluşturmak isteyen geliştiriciler için mükemmeldir,<br/>            projelerinde esneklik ve verimlilik sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | int | Görüntü genişliği. |
| height | int | Görüntü yüksekliği. |
| bits_per_pixel | int | Piksel başına bit. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Renk paleti. |


**See also:**

**[Example # 1](#example_84)**: The example shows how to create a BmpImage of the specified size with the spe...


### Constructor: BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution) {#BmpImage_width_height_bits_per_pixel_palette_compression_horizontal_resolution_vertical_resolution_9}


```
 BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution) 
```

Bu yapıcıyı kullanarak [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini zahmetsizce oluşturun,<br/>            genişlik, yükseklik, bitsPerPixel ve palet gibi parametreleri belirterek. Özel boyutlar ve renk yapılandırmalarıyla BmpImage nesneleri üretmek isteyen geliştiriciler için mükemmeldir,<br/>            projelerine esneklik ve entegrasyon kolaylığı sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | int | Görüntü genişliği. |
| height | int | Görüntü yüksekliği. |
| bits_per_pixel | int | Piksel başına bit. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Renk paleti. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kullanılacak sıkıştırma. |
| horizontal_resolution | float | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| vertical_resolution | float | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |


**See also:**

**[Example # 1](#example_85)**: The example shows how to create a BmpImage using various options.


### Property: bitmap_info_header {#bitmap_info_header1}

Bu basit işlevle bitmap görüntünüzle ilgili temel ayrıntılara hızlıca erişin.<br/>            Görüntülerinin başlık bilgilerini almak isteyen geliştiriciler için mükemmeldir.

**See also:**

**[Example # 1](#example_89)**: The following example gets the information from the BMP header and prints it ...


### Property: bits_per_pixel {#bits_per_pixel2}

Bu özelliği kullanarak görüntünün piksel başına bit sayısına kolayca erişin.<br/>            Görüntü kalitesi ve derinliği hakkında hızlı bilgi arayan geliştiriciler için mükemmeldir.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: compression {#compression3}

Bu özellik ile görüntü için kullanılan sıkıştırma türünü zahmetsizce alın.<br/>            Görüntü sıkıştırması hakkında hızlıca bilgiye ihtiyaç duyan geliştiriciler için mükemmeldir.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: file_format {#file_format4}

Bu kullanıcı dostu özellik ile dosya formatı değerini kolayca alın.<br/>            Dosya formatı hakkında hızlı bilgiye ihtiyaç duyan geliştiriciler için idealdir.

**See also:**

**[Example # 1](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: height {#height5}

Bu özellik ile görüntünün yüksekliğini zahmetsizce alın.<br/>            Görüntü boyutları hakkında hızlı bilgiye ihtiyaç duyan geliştiriciler için idealdir.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: horizontal_resolution {#horizontal_resolution6}

Bu özellik, [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) nesnesinin yatay çözünürlüğünü (inç başına piksel olarak ölçülen) kolayca almanızı veya ayarlamanızı sağlar.<br/>            Hassas görüntü çözünürlüğü kontrolüne ihtiyaç duyan geliştiriciler için idealdir.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Property: raw_data_format {#raw_data_format7}

Bu kullanıcı dostu işlev ile ham verinizin formatını kolayca elde edin.<br/>            Veri formatı hakkında kritik bilgilere hızlıca erişmek isteyen geliştiriciler için mükemmeldir.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: raw_line_size {#raw_line_size8}

Bu basit özellik ile her ham satırın bayt cinsinden boyutuna hızlıca erişin.<br/>            Ham görüntü verisini verimli bir şekilde işlemek isteyen geliştiriciler için idealdir.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: vertical_resolution {#vertical_resolution9}

Bu özellik ile bu [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) nesnesinin dikey çözünürlüğünü (inç başına piksel olarak ölçülen) kolayca alabilir veya ayarlayabilirsiniz.<br/>            Uygulamalarında görüntü çözünürlüğü üzerinde hassas kontrol gerektiren geliştiriciler için mükemmeldir.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Property: width {#width10}

Genişliğe bu özellik ile kolayca erişin.<br/>            Görüntü boyutları hakkında hızlı bilgi arayan geliştiriciler için idealdir.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Görüntü için parlaklık ayarı.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| parlaklık | int | Parlaklık değeri. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Görüntü kontrastı

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| kontrast | float | Kontrast değeri ([-100; 100] aralığında) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Bir görüntünün gama düzeltmesi.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Bir görüntünün gama düzeltmesi.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| gamma_red | float | Kırmızı kanal için gamma katsayısı |
| gamma_green | float | Yeşil kanal için gamma katsayısı |
| gamma_blue | float | Mavi kanal katsayısı için gamma |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_5}


```
 analyze_percentage_digital_signature(password) 
```

Çıkarılan veri ile orijinal şifre arasındaki yüzde benzerliğini hesaplar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| parola | string | Gömülü verileri çıkarmak için kullanılan parola. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Yüzde benzerlik değeri. |


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Bradley'nin uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brightness_difference | float | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin ortalaması ile piksel arasındaki parlaklık farkı. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Bradley'nin uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brightness_difference | float | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin ortalaması ile piksel arasındaki parlaklık farkı. |
| window_size | int | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin boyutu |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| eşik | System.Byte | Eşik değeri. Bir pikselin karşılık gelen gri değeri eşiği aşarsa, ona 255 değeri atanır, aksi takdirde 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_9}


```
 blend(origin, overlay, overlay_alpha) 
```

Bu görüntü örneğini _overlay_ görüntüsüyle karıştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Arka plan görüntüsü karıştırma kaynağı. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Kaplama görüntüsü. |
| overlay_alpha | System.Byte | Kaplama alfa değeri. |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_10}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

Bu görüntü örneğini _overlay_ görüntüsüyle karıştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Arka plan görüntüsü karıştırma kaynağı. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Kaplama görüntüsü. |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kaplama alanı. |
| overlay_alpha | System.Byte | Kaplama alfa değeri. |

### Method: can_load(file_path)  [static] {#can_load_file_path_11}


```
 can_load(file_path) 
```

Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen dosyadan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_12}


```
 can_load(file_path, load_options) 
```

Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen dosyadan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_13}


```
 can_load(stream) 
```

Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Yükleme yapılacak akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen akıştan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_14}


```
 can_load(stream, load_options) 
```

Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen _loadOptions_ kullanılarak belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Yükleme yapılacak akış. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen akıştan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_15}


```
 can_load_stream(stream) 
```

Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Yükleme yapılacak akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen akıştan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_16}


```
 can_load_stream_with_options(stream, load_options) 
```

Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen _loadOptions_ kullanılarak belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Yükleme yapılacak akış. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen akıştan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_17}


```
 can_load_with_options(file_path, load_options) 
```

Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen dosyadan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_save(options) {#can_save_options_18}


```
 can_save(options) 
```

Geçilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına görüntünün kaydedilip kaydedilemeyeceğini belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kullanılacak kaydetme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına kaydedilebiliyorsa; aksi takdirde <c>false</c>. |


### Method: create(files)  [static] {#create_files_19}


```
 create(files) 
```

Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dosyalar | string[] | Dosyalar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Çok sayfalı görüntü |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_20}


```
 create(files, throw_exception_on_load_error) 
```

Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dosyalar | string[] | Dosyalar. |
| throw_exception_on_load_error | bool | eğer <c>true</c> olarak ayarlanırsa [yükleme hatasında istisna fırlat]. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Çok sayfalı görüntü |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_21}


```
 create(image_options, width, height) 
```

Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Görüntü seçenekleri. |
| width | int | Genişlik. |
| height | int | Yükseklik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Yeni oluşturulan görüntü. |


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_22}


```
 create(image_options, width, height, pixels) 
```

Sağlanan piksel dizisinden bir [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) örneği oluşturur.<br/>            <br/>            Belirtilen genişlik ve yüksekliğin piksel verisinin boyutlarıyla eşleştiğini doğrular.<br/>            Bu yöntem yalnızca kütüphane Lisanslı modda olduğunda kullanılabilir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | RasterImage'i oluşturmak için kullanılan seçenekler [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | RasterImage'in genişliği [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| height | int | RasterImage'in yüksekliği [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| piksel | int[] | Görüntüyü doldurmak için kullanılan piksel değerleri dizisi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Sağlanan piksel verileriyle doldurulmuş bir [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |


### Method: create(images)  [static] {#create_images_23}


```
 create(images) 
```

Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Görüntüler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Görüntü, IMultipageImage olarak |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_24}


```
 create(images, dispose_images) 
```

Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Görüntüler. |
| dispose_images | bool | eğer <c>true</c> olarak ayarlanırsa [görüntüleri temizle]. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Görüntü, IMultipageImage olarak |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_25}


```
 create(multipage_create_options) 
```

Belirtilen çok sayfalı oluşturma seçeneklerini oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | Çok sayfalı oluşturma seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Çok sayfalı görüntü |


### Method: create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_file_with_params_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_26}


```
 create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Bu yapıcı ile BmpImage sınıfını kolayca kullanmaya başlayın, yeni bir örnek başlatma sürecini basitleştirir.<br/>            Projelerine [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) nesnelerini hızlı ve verimli bir şekilde dahil etmek isteyen geliştiriciler için idealdir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Görüntünün yükleneceği ve piksel ile palet verilerinin başlatılacağı yol. |
| bits_per_pixel | int | Piksel başına bit. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kullanılacak sıkıştırma. |
| horizontal_resolution | float | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| vertical_resolution | float | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_27}


```
 create_from_files(files) 
```

Belirtilen dosyaları tembel yükleme sayfaları olarak içeren çok sayfalı bir görüntü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dosyalar | string[] | Dosyalar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Çok sayfalı görüntü |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_28}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Belirtilen dosyaları tembel yükleme sayfaları olarak içeren çok sayfalı bir görüntü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dosyalar | string[] | Dosyalar. |
| throw_exception_on_load_error | bool | eğer <c>true</c> olarak ayarlanırsa yükleme hatasında istisna fırlat. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Çok sayfalı görüntü |


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_29}


```
 create_from_image(raster_image) 
```

[BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Piksel ve palet verilerini başlatmak için kullanılacak görüntü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_image_with_params_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_30}


```
 create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

[BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Piksel ve palet verilerini başlatmak için kullanılacak görüntü. |
| bits_per_pixel | int | Piksel başına bit. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kullanılacak sıkıştırma. |
| horizontal_resolution | float | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| vertical_resolution | float | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_31}


```
 create_from_images(images) 
```

Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Görüntüler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Görüntü, IMultipageImage olarak |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_32}


```
 create_from_images(images, dispose_images) 
```

Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Görüntüler. |
| dispose_images | bool | eğer <c>true</c> olarak ayarlanırsa [görüntüleri temizle]. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Görüntü, IMultipageImage olarak |


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_33}


```
 create_from_stream(stream) 
```

[BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün yükleneceği ve piksel ile palet verilerinin başlatılacağı akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_stream_with_params_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_34}


```
 create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

[BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün yükleneceği ve piksel ile palet verilerinin başlatılacağı akış. |
| bits_per_pixel | int | Piksel başına bit. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kullanılacak sıkıştırma. |
| horizontal_resolution | float | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| vertical_resolution | float | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_35}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Kaydırmalarla görüntüyü kırp.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| left_shift | int | Sol kaydırma. |
| right_shift | int | Sağ kaydırma. |
| top_shift | int | Üst kaydırma. |
| bottom_shift | int | Alt kaydırma. |

### Method: crop(rectangle) {#crop_rectangle_36}


```
 crop(rectangle) 
```

Görüntüyü kırpma.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dikdörtgen. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_37}


```
 dither(dithering_method, bits_count) 
```

Mevcut görüntüde dithering uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithering yöntemi. |
| bits_count | int | Dithering için son bit sayısı. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_38}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Mevcut görüntüde dithering uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithering yöntemi. |
| bits_count | int | Dithering için son bit sayısı. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Dithering için özel palet. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_39}


```
 embed_digital_signature(password) 
```

Sağlanan şifreye dayalı dijital imzayı steganografi kullanarak görüntüye göm.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| parola | string | Dijital imza verisi oluşturmak için kullanılan şifre |

### Method: filter(rectangle, options) {#filter_rectangle_options_40}


```
 filter(rectangle, options) 
```

Belirtilen dikdörtgeni filtreler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dikdörtgen. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Seçenekler. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_41}


```
 get_argb_32_pixel(x, y) 
```

Bir görüntünün 32-bit ARGB pikselini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Belirtilen konum için 32-bit ARGB piksel. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_42}


```
 get_default_argb_32_pixels(rectangle) 
```

Varsayılan 32-bit ARGB piksel dizisini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel alınacak dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | Varsayılan piksel dizisi. |


### Method: get_default_options(args) {#get_default_options_args_43}


```
 get_default_options(args) 
```

Bu basit yöntem ile varsayılan seçenekleri zahmetsizce alın.<br/>            Varsayılan görüntü ayarları veya yapılandırmalarına hızlı erişmek isteyen geliştiriciler için idealdir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| args | System.Object | Argümanlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Varsayılan seçenekler |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_44}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel alınacak dikdörtgen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Kısmi piksel yükleyici. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel alınacak dikdörtgen. |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Kısmi ham veri yükleyici. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Ham veri ayarları. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_46}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Varsayılan ham veri dizisini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ham veri alınacak dikdörtgen. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Ham veri ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | Varsayılan ham veri dizisi. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_47}


```
 get_file_format(file_path) 
```

Dosya biçimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Belirlenen dosya formatı. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_48}


```
 get_file_format(stream) 
```

Dosya biçimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Belirlenen dosya formatı. |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_49}


```
 get_file_format_of_stream(stream) 
```

Dosya biçimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Belirlenen dosya formatı. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_50}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Mevcut görüntüyü saran dikdörtgeni alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Uygun dikdörtgeni elde etmek için dikdörtgen. |
| piksel | int[] | 32 bit ARGB pikselleri. |
| width | int | Nesnenin genişliği. |
| height | int | Nesnenin yüksekliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Uygun dikdörtgen veya uygun bir dikdörtgen bulunamazsa istisna. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_51}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Mevcut görüntüyü saran dikdörtgeni alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Uygun dikdörtgeni elde etmek için dikdörtgen. |
| width | int | Nesnenin genişliği. |
| height | int | Nesnenin yüksekliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Uygun dikdörtgen veya uygun bir dikdörtgen bulunamazsa istisna. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_52}


```
 get_modify_date(use_default) 
```

Kaynak görüntünün en son değiştirildiği tarih ve saati alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| use_default | bool | eğer <c>true</c> olarak ayarlanırsa, FileInfo'dan gelen bilgileri varsayılan değer olarak kullanır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.DateTime | Kaynak görüntünün en son değiştirildiği tarih ve saat. |


### Method: get_original_options() {#get_original_options__53}


```
 get_original_options() 
```

Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirilmemiş tutmak için faydalı olabilir.<br/>            Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yüklerseniz ve ardından bunu kullanarak<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) yöntemiyle, 8-bit piksel başına sahip bir çıktı PNG görüntüsü üretilecektir.<br/>            Bunu önlemek ve 1-bit piksel başına PNG görüntüsü kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) yöntemine ikinci parametre olarak geçirin.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Orijinal dosya ayarlarına dayalı seçenekler. |


### Method: get_pixel(x, y) {#get_pixel_x_y_54}


```
 get_pixel(x, y) 
```

Bir görüntü pikselini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Belirtilen konum için piksel rengi. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_55}


```
 get_proportional_height(width, height, new_width) 
```

Orantılı bir yükseklik alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | int | Genişlik. |
| height | int | Yükseklik. |
| new_width | int | Yeni genişlik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Orantılı yükseklik. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_56}


```
 get_proportional_width(width, height, new_height) 
```

Orantılı bir genişlik alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | int | Genişlik. |
| height | int | Yükseklik. |
| new_height | int | Yeni yükseklik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Orantılı genişlik. |


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_57}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

aps'ye dönüştürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Görüntü seçenekleri. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Kırpma dikdörtgeni. |
| page_number | int[] | Sayfa numarası. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| _io.BufferedRandom | Serileştirilmiş akış |


### Method: get_skew_angle() {#get_skew_angle__58}


```
 get_skew_angle() 
```

Eğim açısını alır.<br/>            Bu yöntem taranmış metin belgelerine uygulanabilir, tarama sırasında eğim açısını belirlemek için.

**Returns**

| Tür | Açıklama |
| :- | :- |
| float | Eğim açısı, derece cinsinden. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_59}


```
 is_digital_signed(password, percentage_threshold) 
```

Sağlanan şifre ve eşik değeri kullanarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| parola | string | İmzayı kontrol etmek için şifre. |
| percentage_threshold | int | İmgenin imzalı kabul edilip edilmediğini belirleyen eşik (yüzde olarak)[0-100].<br/>            Belirtilmezse, varsayılan eşik (<c>75</c>) uygulanacaktır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | İmge imzalıysa doğru, aksi takdirde yanlış. |


### Method: load(file_path)  [static] {#load_file_path_60}


```
 load(file_path) 
```

Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | İmge yüklenecek dosya yolu veya URL. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Yüklenen imge. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_61}


```
 load(file_path, load_options) 
```

Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | İmge yüklenecek dosya yolu veya URL. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Yüklenen imge. |


### Method: load(stream)  [static] {#load_stream_62}


```
 load(stream) 
```

Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | İmge yüklenecek akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Yüklenen imge. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_63}


```
 load(stream, load_options) 
```

Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | İmge yüklenecek akış. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Yüklenen imge. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_64}


```
 load_argb_32_pixels(rectangle) 
```

32-bit ARGB piksellerini yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksellerin yükleneceği dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | Yüklenen 32-bit ARGB piksel dizisi. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_65}


```
 load_argb_64_pixels(rectangle) 
```

64-bit ARGB piksellerini yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksellerin yükleneceği dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | Yüklenen 64-bit ARGB piksel dizisi. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_66}


```
 load_cmyk_32_pixels(rectangle) 
```

CMYK formatında pikselleri yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksellerin yükleneceği dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | Yüklenen CMYK pikseller 32-bit tam sayı değerleri olarak sunulur. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_67}


```
 load_cmyk_pixels(rectangle) 
```

CMYK formatında pikselleri yükler.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) yöntemini kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksellerin yükleneceği dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Yüklenen CMYK piksel dizisi. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_68}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32-bit ARGB piksellerini kısmen (bloklar halinde) yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksellerin yükleneceği dikdörtgen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Kısmi piksel yükleyici. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_69}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

64-bit ARGB piksellerini paketler halinde kısmen yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | İstenen dikdörtgen. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | 64-bit ARGB piksel yükleyicisi. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_70}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Pikselleri paketler halinde kısmen yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | İstenen dikdörtgen. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Piksel yükleyicisi. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_71}


```
 load_pixels(rectangle) 
```

Pikselleri yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksellerin yükleneceği dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Yüklenen piksel dizisi. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_72}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Ham veriyi yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ham verinin yükleneceği dikdörtgen. |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Yüklenen veri için kullanılacak ham veri ayarları. Not: veri belirtilen formatta değilse veri dönüşümü gerçekleştirilecektir. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Ham veri yükleyicisi. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_73}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Ham veriyi yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ham verinin yükleneceği dikdörtgen. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Yüklenen veri için kullanılacak ham veri ayarları. Not: veri belirtilen formatta değilse veri dönüşümü gerçekleştirilecektir. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Ham veri yükleyicisi. |

### Method: load_stream(stream)  [static] {#load_stream_stream_74}


```
 load_stream(stream) 
```

Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | İmge yüklenecek akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Yüklenen imge. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_75}


```
 load_stream_with_options(stream, load_options) 
```

Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | İmge yüklenecek akış. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Yüklenen imge. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_76}


```
 load_with_options(file_path, load_options) 
```

Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | İmge yüklenecek dosya yolu veya URL. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Yüklenen imge. |


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_77}


```
 normalize_angle(resize_proportionally, background_color) 
```

Açıyı normalleştirir.<br/>            Bu yöntem, taranmış metin belgelerinde eğik taramayı gidermek için uygulanabilir.<br/>            Bu yöntem, [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) ve [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) metodlarını kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| resize_proportionally | bool | eğer <c>true</c> olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgene (köşe noktaları) göre projeksiyonlar doğrultusunda değişir; diğer durumda boyutlar aynı kalır ve yalnızca iç görüntü içeriği döndürülür. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Arka plan rengi. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_78}


```
 read_argb_32_scan_line(scan_line_index) 
```

Belirtilen tarama satırı indeksi ile tüm tarama satırını okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int | Tarama satırının sıfır tabanlı indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int[] | Tarama satırının 32-bit ARGB renk değerleri dizisi. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_79}


```
 read_scan_line(scan_line_index) 
```

Belirtilen tarama satırı indeksi ile tüm tarama satırını okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int | Tarama satırının sıfır tabanlı indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Tarama satırının piksel renk değerleri dizisi. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_80}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| old_color_argb | int | Değiştirilecek eski renk ARGB değeri. |
| old_color_diff | System.Byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| new_color_argb | int | Eski rengi değiştirmek için yeni renk ARGB değeri. |

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_81}


```
 replace_color(old_color, old_color_diff, new_color) 
```

İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | Değiştirilecek eski renk. |
| old_color_diff | System.Byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Eski rengi değiştirecek yeni renk. |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_82}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| old_color_argb | int | Değiştirilecek eski renk ARGB değeri. |
| old_color_diff | System.Byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| new_color_argb | int | Eski rengi değiştirmek için yeni renk ARGB değeri. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_83}


```
 replace_non_transparent_colors(new_color) 
```

Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak yumuşak kenarları korur.<br/>            Not: şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Şeffaf olmayan renkleri değiştirecek yeni renk. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_84}


```
 replace_non_transparent_colors(new_color_argb) 
```

Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak yumuşak kenarları korur.<br/>            Not: şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color_argb | int | Şeffaf olmayan renkleri değiştirmek için yeni renk ARGB değeri. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_85}


```
 resize(new_width, new_height) 
```

Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_86}


```
 resize(new_width, new_height, resize_type) 
```

Görüntüyü yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırma türü. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_87}


```
 resize(new_width, new_height, settings) 
```

Görüntüyü yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Yeniden boyutlandırma ayarları. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_88}


```
 resize_by_settings(new_width, new_height, settings) 
```

Görüntüyü yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Yeniden boyutlandırma ayarları. |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_89}


```
 resize_by_type(new_width, new_height, resize_type) 
```

Görüntüyü yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırma türü. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_90}


```
 resize_height_proportionally(new_height) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_91}


```
 resize_height_proportionally(new_height, resize_type) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırmanın türü. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_92}


```
 resize_height_proportionally(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_93}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_94}


```
 resize_width_proportionally(new_width) 
```

Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_95}


```
 resize_width_proportionally(new_width, resize_type) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırmanın türü. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_96}


```
 resize_width_proportionally(new_width, settings) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_97}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: rotate(angle) {#rotate_angle_98}


```
 rotate(angle) 
```

Görüntüyü merkezin etrafında döndür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_99}


```
 rotate(angle, resize_proportionally, background_color) 
```

Görüntüyü merkezin etrafında döndür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |
| resize_proportionally | bool | eğer <c>true</c> olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgene (köşe noktaları) göre projeksiyonlar doğrultusunda değişir; diğer durumda boyutlar aynı kalır ve yalnızca iç görüntü içeriği döndürülür. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Arka plan rengi. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_100}


```
 rotate_flip(rotate_flip_type) 
```

Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Döndürme çevirme türü. |

### Method: save(file_path) {#save_file_path_101}


```
 save(file_path) 
```

Görüntüyü belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Görüntünün kaydedileceği dosya yolu. |

### Method: save(file_path, options) {#save_file_path_options_102}


```
 save(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_103}


```
 save(file_path, options, bounds_rectangle) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş dikdörtgen ayarlayın. |

### Method: save(file_path, over_write) {#save_file_path_over_write_104}


```
 save(file_path, over_write) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verilerinin kaydedileceği dosya yolu. |
| over_write | bool | Eğer <c>true</c> olarak ayarlanırsa dosya içeriği üzerine yazılır, aksi takdirde ekleme yapılır. |

### Method: save(stream) {#save_stream_105}


```
 save(stream) 
```

Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Nesnenin verisinin kaydedileceği akış. |

### Method: save(stream, options_base) {#save_stream_options_base_106}


```
 save(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_107}


```
 save(stream, options_base, bounds_rectangle) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş bir dikdörtgen ayarlayın. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_108}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32-bit ARGB piksellerini kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| piksel | int[] | 32 bitlik ARGB piksel dizisi. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_109}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Pikselleri kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| piksel | int[] | 32 bitlik tam sayı değerleri olarak sunulan CMYK pikseller. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_110}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Pikselleri kaydeder.<br/>            Bu yöntem artık kullanılmamaktadır. Lütfen daha etkili olan [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) yöntemini kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK piksel dizisi. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_111}


```
 save_pixels(rectangle, pixels) 
```

Pikselleri kaydeder (format özel yöntemi).

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | 32 bitlik ARGB piksel dizisi. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_112}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Ham veriyi kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| veri | System.Byte | Ham veri. |
| data_offset | int | Başlangıç ham veri ofseti. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Ham veri dikdörtgeni. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Verinin bulunduğu ham veri ayarları. |

### Method: save_to_stream(stream) {#save_to_stream_stream_113}


```
 save_to_stream(stream) 
```

Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Nesnenin verisinin kaydedileceği akış. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_114}


```
 save_to_stream_with_options(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_115}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş bir dikdörtgen ayarlayın. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_116}


```
 save_with_options(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_117}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş dikdörtgen ayarlayın. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_118}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Belirtilen konum için bir görüntünün 32-bit ARGB pikselini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |
| argb_32_color | int | Belirtilen konum için 32-bit ARGB piksel. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_119}


```
 set_palette(palette, update_colors) 
```

Görüntü paletini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Ayarlanacak palet. |
| update_colors | bool | eğer <c>true</c> olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri yoksa, görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_120}


```
 set_pixel(x, y, color) 
```

Belirtilen konum için bir görüntü pikselini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Belirtilen konum için piksel rengi. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_121}


```
 set_resolution(dpi_x, dpi_y) 
```

Bu kullanıcı dostu yöntem ile [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) çözünürlüğünüzü zahmetsizce ayarlayın.<br/>            Hassas kontrol arayan geliştiriciler için mükemmeldir.<br/>            Görüntü çözünürlüğü üzerinde hassas kontrol isteyen geliştiriciler için idealdir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dpi_x | float | Yatay çözünürlük, inç başına nokta (dpi) cinsinden, [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) öğesinin. |
| dpi_y | float | Dikey çözünürlük, inç başına nokta (dpi) cinsinden, [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) öğesinin. |


**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_122}


```
 try_set_metadata(metadata) 
```

Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Meta veriler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Eğer _metadata_ null değilse ve [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) örneği <br/>            destekliyor ve/veya [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa doğru; aksi takdirde yanlış. |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_123}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Tüm tarama satırını belirtilen tarama satırı indeksine yazar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int | Tarama satırının sıfır tabanlı indeksi. |
| argb_32_pixels | int[] | Yazılacak 32-bit ARGB renk dizisi. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_124}


```
 write_scan_line(scan_line_index, pixels) 
```

Tüm tarama satırını belirtilen tarama satırı indeksine yazar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int | Tarama satırının sıfır tabanlı indeksi. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Yazılacak piksel renkleri dizisi. |

## **Examples**
### The following example shows how to create a BMP image of the specified size. {#example_18}
``` python
from aspose.imaging import Color
from aspose.imaging.fileformats.bmp import BmpImage
from os.path import join as path_join

directory = "c:\\temp\\"

# 100 x 100 piksel boyutunda bir BMP görüntüsü oluştur.
with BmpImage(100, 100) as bmpImage:
	# Görüntüyü basit bir lineer kırmızı-siyah degrade ile doldurun.
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
		# Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.
		print("Set resolution values to 96 dpi")
		bmpImage.set_resolution(96.0, 96.0)
		print("The horizontal resolution, in pixels per inch: {0}", bmpImage.horizontal_resolution);
		print("The vertical resolution, in pixels per inch: {0}", bmpImage.vertical_resolution);

	#Çıktı şu şekilde görünebilir:
	#Piksel formatı: Rgb24Bpp, kullanılan kanallar: 8,8,8
	#Ham satır boyutu (bayt cinsinden): 1500
	#Bitmap sıkıştırması: Rgb
	#Bitmap genişliği: 500
	#Bitmap yüksekliği: 375
	#Piksel başına bit sayısı: 24
	#Yatay çözünürlük, inç başına piksel olarak: 0
	#Dikey çözünürlük, inç başına piksel olarak: 0
	#Çözünürlük değerlerini 96 dpi olarak ayarla
	#Yatay çözünürlük, inç başına piksel olarak: 96.012
	#Dikey çözünürlük, inç başına piksel olarak: 96.012


```

### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# 100 x 100 piksel boyutunda bir BMP görüntüsü oluştur.
with BmpImage(100, 100) as bmpImage:
	# Görüntünün sol üst köşesinden sağ alt köşesine uzanan lineer degrade.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Tüm görüntüyü lineer degrade fırçası ile doldur.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Mümkün olduğunca çok pikseli kapsayan en yakın 8-bit renk paletini al, böylece paletli bir görüntü
	# paletsiz bir bmp'den neredeyse görsel olarak ayırt edilemez olur
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8-bit palet en fazla 256 renk içerir.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# Çıktı şu şekilde görünür:
# Paletli görüntünün boyutu 11078 bayttır.
# Paletsiz görüntünün boyutu 40054 bayttır.

```

### The example shows how to load a BmpImage from a file. {#example_77}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
import os

directory = r"c:\temp"

# Bir BMP görüntüsünü dosyadan yükle.
# Gerekirse kaynak pikseller 32-bpp formatına dönüştürülecek.
with BmpImage(os.path.join(directory, "sample.bmp")) as bmp_image:
	# Bazı görüntü işleme işlemleri yap.
	# Başka bir BMP dosyasına kaydet.
	bmp_image.save(os.path.join(directory, "sample.output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from a file with the specified bit depth and resolution. {#example_78}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
import os

directory = r"c:\temp"

# Bir BMP görüntüsünü dosyadan yükle.
# Gerekirse kaynak pikseller 24-bpp formatına dönüştürülecek.
# Çözünürlük 96 dpi olarak ayarlanacak.
with BmpImage(os.path.join(directory, "sample.bmp"), 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
	# Bazı görüntü işleme işlemleri yap.
	# Başka bir BMP dosyasına kaydet.
	bmp_image.save(os.path.join(directory, "sample.output.24bpp.96dpi.bmp"))


```

### The example shows how to load a BmpImage from a file stream. {#example_79}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
import os

directory = r"c:\temp"

# Bir BMP görüntüsünü dosya akışından yükle.
# Gerekirse kaynak pikseller 32-bpp formatına dönüştürülecek.
with open(os.path.join(directory, "sample.bmp"), "rb+") as stream:
	with BmpImage(stream) as bmp_image:
		# Bazı görüntü işleme işlemleri yap.
		# Başka bir BMP dosyasına kaydet.
		bmp_image.save(os.path.join(directory, "sample.output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from a file stream with the specified bit depth and resolution. {#example_80}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
import os

directory = r"c:\temp"

# Bir BMP görüntüsünü dosya akışından yükle.
# Gerekirse kaynak pikseller 24-bpp formatına dönüştürülecek.
# Çözünürlük 96 dpi olarak ayarlanacak.
with open(os.path.join(directory, "sample.bmp"), "rb") as stream:
	with BmpImage(stream, 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
		# Bazı görüntü işleme işlemleri yap.
		# Başka bir BMP dosyasına kaydet.
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

# Yeni bir PNG görüntüsü oluştur.
with PngOptions() as create_options:
	create_options.source = StreamSource()
	with aspycore.as_of(Image.create(create_options, 100, 100), RasterImage) as raster_image:
		# Tüm PNG resmini kırmızıyla doldurun.
		gr = Graphics(raster_image)
		brush = SolidBrush(Color.red)
		gr.fill_rectangle(brush, raster_image.bounds)

		# PNG görüntüsüne dayanarak bir BMP görüntüsü oluştur.
		# Gerekirse kaynak pikseller 32-bpp formatına dönüştürülecek.
		with BmpImage(raster_image) as bmp_image:
			# Bir BMP dosyasına kaydet
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

# Yeni bir PNG görüntüsü oluştur.
with PngOptions() as create_options:
	create_options.source = StreamSource()
	with aspycore.as_of(Image.create(create_options, 100, 100), RasterImage) as raster_image:
		# Tüm PNG resmini kırmızıyla doldurun.
		gr = Graphics(raster_image)
		brush = SolidBrush(Color.red)
		gr.fill_rectangle(brush, raster_image.bounds)

		# PNG görüntüsüne dayanarak bir BMP görüntüsü oluştur.
		# Gerekirse kaynak pikseller 24-bpp formatına dönüştürülecek.
		# Çözünürlük 96 dpi olarak ayarlanacak.
		with BmpImage(raster_image, 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
			# Bir BMP dosyasına kaydet
			bmp_image.save(os.path.join(directory, "output.24bpp.96dpi.bmp"))

```

### The example shows how to create a BmpImage of the specified size. {#example_83}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
import os

directory = r"c:\temp"

# 100 x 100 piksel boyutunda 32 bpp BMP görüntüsü oluşturun.
with BmpImage(100, 100) as bmp_image:
	# Tüm görüntüyü kırmızıyla doldur.
	Graphics gr = Graphics(bmp_image)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, bmp_image.bounds)
	# Bir BMP dosyasına kaydet
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

# Sadece kırmızı ve yeşil renkleri içeren tek renkli bir palet oluştur.
palette = ColorPalette.create_with_colors(paletterColors)

# 100 x 100 piksel boyutunda tek renkli 1-bpp BMP görüntüsü oluştur.
with BmpImage(100, 100, 1, palette) as bmp_image:
	gr = Graphics(bmp_image)

	# Görüntünün üst yarısını kırmızı ile doldur.
	redBrush = SolidBrush(Color.red)
	gr.fill_rectangle(redBrush, Rectangle(0, 0, bmp_image.width, bmp_image.height // 2))

	# Görüntünün alt yarısını yeşil ile doldur.
	greenBrush = SolidBrush(Color.green)
	gr.fill_rectangle(greenBrush, Rectangle(0, bmp_image.height // 2, bmp_image.width, bmp_image.height // 2))

	# BMP olarak kaydet
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

# Sadece kırmızı ve yeşil renkleri içeren tek renkli bir palet oluştur.
palette = ColorPalette.create_with_colors(paletterColors)

# 100 x 100 piksel boyutunda tek renkli 1-bpp BMP görüntüsü oluştur.
with BmpImage(100, 100, 1, palette, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
	gr = Graphics(bmp_image)

	# Görüntünün üst yarısını kırmızı ile doldur.
	redBrush = SolidBrush(Color.red)
	gr.fill_rectangle(redBrush, Rectangle(0, 0, bmp_image.width, bmp_image.height // 2))

	# Görüntünün alt yarısını yeşil ile doldur.
	greenBrush = SolidBrush(Color.green)
	gr.fill_rectangle(greenBrush, Rectangle(0, bmp_image.height // 2, bmp_image.width, bmp_image.height // 2))

	# BMP olarak kaydet
	bmp_image.save(os.path.join(directory, "output.monochrome.96dpi.bmp"))


```

### The following example shows how to extract information about raw data format and alpha channel from a BMP image. {#example_86}
``` python
from aspose.imaging.fileformats.bmp import BmpImage

# 100 x 100 piksel boyutunda 32 bpp BMP görüntüsü oluşturun.
with BmpImage(100, 100, 32, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))


# 100 x 100 piksel boyutunda 24 bpp BMP görüntüsü oluşturun.
with BmpImage(100, 100, 24, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))

# Genel olarak, BMP alfa kanalını desteklemez, bu yüzden çıktı şöyle görünecektir:
# FileFormat = BMP, RawDataFormat = Rgb32Bpp, kullanılan kanallar: 8,8,8,8, HasAlpha = False
# FileFormat = BMP, RawDataFormat = Rgb24Bpp, kullanılan kanallar: 8,8,8, HasAlpha = False

```

### The following example shows how the bitmap compression affects the output image size. {#example_87}
``` python

from aspose.imaging import Color, ColorPalette, Graphics
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
from aspose.imaging.extensions import StreamExtensions as strm_ext

compressions = (BitmapCompression.RGB, BitmapCompression.RLE8)

paletterColors = (Color.red, Color.green)

# Sadece kırmızı ve yeşil renkleri içeren tek renkli bir palet oluştur.
palette = ColorPalette.create_with_colors(paletterColors)

for compression in compressions:
	# 100 x 100 piksel boyutunda 8-bpp BMP görüntüsü oluştur.
	with BmpImage(100, 100, 8, palette, compression, 0.0, 0.0) as bmp_image:
		gr = Graphics(bmp_image)
		# Tüm görüntüyü kırmızıyla doldur.
		red_brush = SolidBrush(Color.red)
		gr.fill_rectangle(red_brush, bmp_image.bounds)
		# Çıktı görüntü boyutunu elde etmek için görüntüyü bir bellek akışına kaydet.
		with strm_ext.create_memory_stream() as stream:
			bmp_image.save(stream)
			print("---------------------------------------------")
			print("The compression =", bmp_image.compression.name)
			print("The number of bits per pixel =", bmp_image.bits_per_pixel)
			print(f"The image dimensions = {bmp_image.width} x {bmp_image.height}")
			print("The raw line size =", bmp_image.raw_line_size)
			print("The output size in bytes =", stream.tell())

# Çıktı şu şekilde görünür:
# ---------------------------------------------
# Sıkıştırma = RGB
# Piksel başına bit sayısı = 8
# Görüntü boyutları =100 x 100
# Ham satır boyutu = 100
# Çıktı boyutu (bayt) = 1178
# ---------------------------------------------
# Sıkıştırma = RLE8
# Piksel başına bit sayısı = 8
# Görüntü boyutları =100 x 100
# Ham satır boyutu = 100
# Çıktı boyutu bayt cinsinden = 856

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
	# BmpImage'in yatay ve dikey çözünürlüğünü al
	horizontal_resolution = bmp_image.horizontal_resolution
	vertical_resolution = bmp_image.vertical_resolution
	print("The horizontal resolution, in pixels per inch:", horizontal_resolution)
	print("The vertical resolution, in pixels per inch:", vertical_resolution)

	if (horizontal_resolution != 96.0 || vertical_resolution != 96.0)
	{
		# Her iki çözünürlük değerini tek bir çağrıda güncellemek için set_resolution metodunu kullan.
		print("Set resolution values to 96 dpi")
		bmp_image.set_resolution(96.0, 96.0)
		print("The horizontal resolution, in pixels per inch:", bmp_image.horizontal_resolution);
		print("The vertical resolution, in pixels per inch:", bmp_image.vertical_resolution);
	}

	# Çıktı şu şekilde görünebilir:
	# Yatay çözünürlük, inç başına piksel olarak: 0
	# Dikey çözünürlük, inç başına piksel olarak: 0
	# Çözünürlük değerlerini 96 dpi olarak ayarla
	# Yatay çözünürlük, inç başına piksel olarak: 96.0
	# Dikey çözünürlük, inç başına piksel olarak: 96.0

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

#Çıktı şu şekilde görünebilir:
#Bit haritasını görüntülemek için gereken palet renk sayısı: 0
#Bit haritasında kullanılan palet renk sayısı: 0
#Bit haritası sıkıştırması: 0
#Bitmap yüksekliği: 375
#Bitmap genişliği: 500
#Bit haritası ham veri boyutu bayt cinsinden: 562500
#Düzlem sayısı: 1
#Bit haritasının yatay çözünürlüğü, metre başına piksel: 0
#Bit haritasının dikey çözünürlüğü, metre başına piksel: 0
#Piksel başına bit sayısı: 24
#Ekstra bit maskeleri: 
#Başlık boyutu bayt cinsinden: 40

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

