---
title: "DicomImage Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.fileformats.dicom/dicomimage/
---

**Summary:** This Class implements Digital Imaging and Communications in Medicine<br/>            (DICOM) raster image format support and offers a comprehensive solution for<br/>            processing DICOM images with precision and flexibility. You can seamlessly<br/>            manipulate image pages, including operations to get, add, or remove pages, and<br/>            control the default and active pages. With capabilities to work with alpha channels,<br/>            embed XMP metadata, resize, rotate, crop, binarize, adjust, apply filters,<br/>            and convert to other raster formats. This API empowers developers to handle<br/>            DICOM images effectively while meeting diverse application requirements in<br/>            medical imaging contexts.

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [DicomImage(dicom_options, width, height)](#DicomImage_dicom_options_width_height_1) | Bu <br/>            yapıcıyı kullanarak DicomImage sınıfının yeni bir örneğini zahmetsizce başlatın, dicomOptions parametrelerini kullanarak. Projelerinde [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) nesnelerine hızlı ve verimli bir şekilde dalmak isteyen geliştiriciler için mükemmeldir. |
| [DicomImage(stream)](#DicomImage_stream_2) | Bu yapıcıda bir akış parametresi kullanarak DicomImage sınıfının yeni bir örneğini oluşturun.<br/>            Projelerinde mevcut veri akışlarından [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) nesnelerini başlatmanın basitleştirilmiş bir yolunu arayan geliştiriciler için mükemmeldir. |
| [DicomImage(stream, load_options)](#DicomImage_stream_load_options_3) | Bu yapıcıda bir akış ve<br/>            loadOptions parametrelerini kullanarak DicomImage sınıfının yeni bir örneğini sorunsuz bir şekilde başlatın. Projelerinde [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) nesneleriyle hızlı ve etkili bir şekilde çalışmaya istekli geliştiriciler için idealdir. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| active_page | [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | r/w | Bu sezgisel özellik ile görüntünün aktif sayfasını yönetin. Geliştiriciler için idealdir<br/>            çok sayfalı görüntülerde sayfalar arasında dinatik geçiş yapmayı arayan, verimli gezinme ve işleme sağlayan. |
| active_page_index | int | r | Bu sezgisel özellik ile aktif sayfanın indeksini zahmetsizce alın.<br/>            Çok sayfalı görüntülerde mevcut sayfa indeksine hızlı erişim arayan geliştiriciler için idealdir, verimli gezinme ve işleme sağlar. |
| auto_adjust_palette | bool | r/w | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Arka plan renginin değerini alır veya ayarlar. |
| bits_per_pixel | int | r | Görselin piksel başına bit sayısını alır. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Nesnenin sınırlarını alır. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Bu [Image](/imaging/python-net/aspose.imaging/image/) kapsayıcısını alır. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Nesnenin veri akışını alır. |
| dicom_pages | [DicomPage[]](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | r | Bu sezgisel özellik ile görüntünün sayfalarına erişin. Geliştiriciler için idealdir<br/>            görüntü içinde tek tek sayfalarla etkileşim kurmak isteyen, sorunsuz<br/>            gezinme ve manipülasyon sağlayan. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif örneğini alır veya ayarlar. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Bu sezgisel özellik ile dosya formatı değerini zahmetsizce alın. Geliştiriciler için idealdir<br/>            görüntü dosyasının formatına hızlı erişim isteyen, dosya türüne göre verimli<br/>            işleme ve işleme sağlayan. |
| file_info | [DicomImageInfo](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/) | r | Bu sezgisel özellik ile DICOM dosyasından değerli başlık bilgilerini zahmetsizce alın<br/>            Geliştiriciler için idealdir, DICOM dosyası içinde kapsüllenmiş temel detaylara hızlı erişim isteyen, verimli veri çıkarımı ve analiz sağlar. |
| has_alpha | bool | r | Bu sezgisel özellik ile görüntünün alfa kanalına sahip olup olmadığını zahmetsizce alın<br/>            Geliştiriciler için idealdir, görüntünün şeffaflık bilgisi içerip içermediğini belirlemek isteyen, görüntü işleme görevlerinde alfa kanal verisinin hassas yönetimini sağlar. |
| has_background_color | bool | r/w | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| has_transparent_color | bool | r/w | Görüntünün şeffaf bir renge sahip olup olmadığını gösteren bir değeri alır. |
| height | int | r | Görüntünün yüksekliğini alır. |
| horizontal_resolution | float | r/w | Bu [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) öğesinin inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar. |
| image_opacity | float | r | Bu görüntünün opaklığını alır. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Kesinti izleyicisini alır veya ayarlar. |
| is_cached | bool | r | Görüntü verisinin şu anda önbelleğe alınıp alınmadığını gösteren bir değeri alır. |
| is_raw_data_available | bool | r | Ham veri yüklemesinin desteklenip desteklenmediğini gösteren bir değeri alır. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Kareden XMP verisini alır veya ayarlar. |
| page_count | int | r | Bu sezgisel özellik ile görüntünün toplam sayfa sayısını alın. Geliştiriciler için idealdir<br/>            görüntü içindeki sayfa sayısına hızlı erişim isteyen, verimli gezinme ve yönetim sağlar. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Bu sezgisel özellik ile görüntünün sayfalarına erişin. Geliştiriciler için idealdir<br/>            görüntü içinde tek tek sayfalarla etkileşim kurmak isteyen, sorunsuz gezinme<br/>            ve manipülasyon sağlar. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| premultiply_components | bool | r/w | Görüntü bileşenlerinin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Özel renk dönüştürücüyü alır veya ayarlar |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Ham veri biçimini alır. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Mevcut ham veri ayarlarını alır. Bu ayarları kullanırken verinin dönüşüm olmadan yüklendiğini unutmayın. |
| raw_fallback_index | int | r/w | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır veya ayarlar |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Dizinli renk dönüştürücüyü alır veya ayarlar |
| raw_line_size | int | r | Ham satır boyutunu bayt cinsinden alır. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Nesne boyutunu alır. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Görüntünün şeffaf rengini alır. |
| update_xmp_data | bool | r/w | XMP meta verilerini güncelleyip güncellemeyeceğini gösteren bir değeri alır veya ayarlar. |
| use_palette | bool | r | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| use_raw_data | bool | r/w | Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılıp kullanılmayacağını gösteren bir değeri alır veya ayarlar. |
| vertical_resolution | float | r/w | Bu [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) öğesinin inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| width | int | r | Görüntünün genişliğini alır. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Xmp verilerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_page()](#add_page__1) | Bu basit yöntemle görüntünün sayfa listesine yeni bir sayfa ekleyin.<br/>            Çok sayfalı görüntüleri dinamik olarak genişletmek isteyen geliştiriciler için idealdir, görüntü içeriğinin sorunsuz<br/>            entegrasyonu ve organizasyonunu sağlar. |
| [add_page(page)](#add_page_page_2) | Bu sezgisel yöntemle yeni bir sayfa ekleyerek görüntü koleksiyonunuzu genişletin.<br/>            Çok sayfalı görüntülere dinamik olarak sayfa eklemek isteyen geliştiriciler için idealdir,<br/>            görüntü içeriğinin sorunsuz genişlemesi ve organizasyonunu sağlar. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Görüntü parlaklığını _brightness_ ayarıyla artırın, bu<br/>            parametreli yöntem geliştiricilerin görüntülerin ışık yoğunluğunu hassas bir şekilde ayarlamasına olanak tanır.<br/>            Bu kullanıcı dostu işlev, geliştiricilerin görüntü<br/>            parlaklığını sorunsuz bir şekilde manipüle etmelerini sağlar ve görsel estetik üzerinde esneklik ve kontrol sunar. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Bu kullanıcı dostu yöntemle [Image](/imaging/python-net/aspose.imaging/image/) kontrastını artırın,<br/>            ışık ve karanlık alanlar arasındaki farkı ayarlayarak. Görsel netliği ve<br/>            tanımı zahmetsizce iyileştirir, geliştiricilere görüntü kontrastı üzerinde sezgisel kontrol sağlayarak<br/>            optimal render elde eder. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Görüntü kalitesini artırın ve gama düzeltmesiyle ayarlayın, görsel görünümü ince ayarlamak için güçlü bir teknik<br/>            . Görüntü sunumunu optimize etmeyi, renk dengesini ayarlamayı ve farklı<br/>            cihaz ve ortamlar arasında tutarlı render sağlamayı hedefleyen geliştiriciler için mükemmeldir. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Bir görüntünün kırmızı, yeşil ve mavi bileşenlerine gama düzeltmesini bağımsız olarak uygulayarak kesin renk ayarlamaları elde edin.<br/>            Bu yöntem doğru renk dengesini ve optimal görsel çıktıyı garanti eder, görüntü renderi ve renk doğruluğu üzerinde ayrıntılı<br/>            kontrol arayan geliştiricilere hitap eder. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | Çıkarılan veri ile orijinal şifre arasındaki yüzde benzerliğini hesaplar. |
| auto_brightness_contrast() | Tüm görüntü için otomatik uyarlamalı parlaklık ve kontrast normalizasyonu gerçekleştirir. |
| auto_rotate() | Exif <br/>            meta veriler. Bu yöntem, görüntülerin doğru yönlendirmede gösterilmesini sağlar, <br/>            kullanıcı deneyimini artırır ve manuel ayarlama ihtiyacını ortadan kaldırır. İle <br/>            Exif bilgilerini analiz ederek, görüntü buna göre döndürülür, sorunsuz bir <br/>            farklı platform ve cihazlarda görüntüleme deneyimi sağlar. Bu otomatik döndürme <br/>            süreci, görüntü işlemini basitleştirir ve özellikle <br/>            farklı yönlerdeki büyük görüntü gruplarıyla çalışırken genel kullanılabilirliği artırır. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | Bradley'nin uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | Bradley'nin uyarlamalı eşikleme algoritmasıyla görüntüleri ikilileştirin, geliştirilmiş performans için integral<br/>            görüntü eşiklemeyi kullanarak. Parlaklıkta yerel değişikliklere dayalı olarak görüntüleri otomatik olarak bölmek isteyen geliştiriciler için idealdir, <br/>            doğru nesne tespiti ve <br/>            değişen aydınlatma koşullarında çıkarımı sağlar. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | Bu basit yöntemle önceden tanımlı bir eşik kullanarak görüntüyü kolayca ikili formata dönüştürün<br/>            . Görüntüyü ön plan ve arka plan bileşenlerine bölerek görsel<br/>            işleme görevlerini basitleştirmek isteyen geliştiriciler için idealdir, <br/>            belirtilen yoğunluk seviyelerine göre. |
| binarize_otsu() | Otsu eşikleme uygulayarak görüntüyü ikilileştirin, görüntünün histogramına dayanarak optimal<br/>            eşik değerini otomatik olarak belirler. Geliştiriciler için mükemmeldir, <br/>            güvenilir bir yöntemle görüntüleri ön plan ve arka plan bölgelerine bölmek isteyen, <br/>            minimum manuel müdahale ile. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | Bu görüntü örneğini _overlay_ görüntüsüyle karıştırır. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | Bu görüntü örneğini _overlay_ görüntüsüyle karıştırır. |
| cache_data() | Bu yöntem verileri verimli bir şekilde önbelleğe alır, performansı optimize eder ve gerektiğinde hızlı erişim sağlar<br/>            . Hız ve verimliliği artırmak isteyen geliştiriciler için idealdir, <br/>            veri kaynaklarını akıllıca yöneterek uygulamalarını geliştirmek isteyenler için. |
| [can_load(file_path)](#can_load_file_path_13) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler. |
| [can_load(stream)](#can_load_stream_15) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen _loadOptions_ kullanılarak belirler. |
| [can_load_stream(stream)](#can_load_stream_stream_17) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen _loadOptions_ kullanılarak belirler. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler. |
| [can_save(options)](#can_save_options_20) | Geçilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına görüntünün kaydedilip kaydedilemeyeceğini belirler. |
| [create(files)](#create_files_21) | Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Sağlanan piksel dizisinden bir [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) örneği oluşturur.<br/>            <br/>            Belirtilen genişlik ve yüksekliğin piksel verisinin boyutlarıyla eşleştiğini doğrular.<br/>            Bu yöntem yalnızca kütüphane Lisanslı modda olduğunda kullanılabilir. |
| [create(images)](#create_images_25) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Belirtilen çok sayfalı oluşturma seçeneklerini oluşturur. |
| [create_from_files(files)](#create_from_files_files_28) | Belirtilen dosyaları tembel yükleme sayfaları olarak içeren çok sayfalı bir görüntü oluşturur. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | Belirtilen dosyaları tembel yükleme sayfaları olarak içeren çok sayfalı bir görüntü oluşturur. |
| [create_from_images(images)](#create_from_images_images_30) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_31) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_32) | Bu çok yönlü yöntemle kaydırmalar uygulayarak görüntünün kırpma alanını ayarlayın.<br/>            Kesme sürecinde hassas kontrol gerektiren geliştiriciler için mükemmeldir, önemli detayların korunmasını sağlarken gereksiz öğeleri ortadan kaldırır. |
| [crop(rectangle)](#crop_rectangle_33) | Bu basit yöntemle istenmeyen alanları kaldırmak ve temel içeriğe odaklanmak için görüntüyü kırpın.<br/>            Görüntülerin görsel kompozisyonunu özelleştirmek isteyen geliştiriciler için idealdir, görüntüler, istenen mesajı etkili bir şekilde iletmelerini sağlar. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_34) | Mevcut görüntüde dithering uygular. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_35) | Bu basit<br/>            yöntemle dithering etkileri uygulayarak mevcut görüntüyü iyileştirin. Görüntülere doku ve derinlik eklemek isteyen geliştiriciler için mükemmeldir,<br/>            görsel kalitesini ve genel çekiciliğini artırır. |
| [embed_digital_signature(password)](#embed_digital_signature_password_36) | Sağlanan şifreye dayalı dijital imzayı görüntünün her sayfasına yerleştirin. |
| [filter(rectangle, options)](#filter_rectangle_options_37) | Belirlenmiş<br/>            dikdörtgenlere filtreler uygulayarak görüntünüzün belirli alanlarını zahmetsizce iyileştirin. Bu yöntem geliştiricilere görüntü manipülasyonu üzerinde hassas kontrol sağlar,<br/>            hedeflenmiş ayarlamalar yaparak istenen<br/>            görsel efektlere kolayca ulaşmalarını mümkün kılar. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_38) | Bir görüntünün 32-bit ARGB pikselini alır. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_39) | Varsayılan 32-bit ARGB piksel dizisini alır. |
| [get_default_options(args)](#get_default_options_args_40) | Varsayılan seçenekleri alır. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_41) | Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_43) | Varsayılan ham veri dizisini alır. |
| [get_file_format(file_path)](#get_file_format_file_path_44) | Dosya biçimini alır. |
| [get_file_format(stream)](#get_file_format_stream_45) | Dosya biçimini alır. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_46) | Dosya biçimini alır. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Mevcut görüntüyü saran dikdörtgeni alır. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Mevcut görüntüyü saran dikdörtgeni alır. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Kaynak görüntünün en son değiştirildiği tarih ve saati alır. |
| [get_original_options()](#get_original_options__50) | Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirilmemiş tutmak için faydalı olabilir.<br/>            Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yüklerseniz ve ardından bunu kullanarak<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) yöntemiyle, 8-bit piksel başına sahip bir çıktı PNG görüntüsü üretilecektir.<br/>            Bunu önlemek ve 1-bit piksel başına PNG görüntüsü kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) yöntemine ikinci parametre olarak geçirin. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Bir görüntü pikselini alır. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Orantılı bir yükseklik alır. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Orantılı bir genişlik alır. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_54) | aps'ye dönüştürür. |
| [get_skew_angle()](#get_skew_angle__55) | Eğim açısını alır.<br/>            Bu yöntem taranmış metin belgelerine uygulanabilir, tarama sırasında eğim açısını belirlemek için. |
| grayscale() | Görüntüleri kolayca gri tonlamalı temsillerine dönüştürerek görsel<br/>            analiz ve işleme görevlerini basitleştirir. Görüntü netliğini artırmak, karmaşıklığı azaltmak ve çeşitli uygulamalar için verimli gri tonlamalı algoritmaları kolaylaştırmak isteyen geliştiriciler için mükemmeldir. |
| [insert_page(page_index)](#insert_page_page_index_56) | Bu sezgisel<br/>            yöntemle görüntünün sayfa listesine belirtilen bir indeksde yeni bir sayfa ekleyin. Çok sayfalı görüntülerde sayfaların düzenlenmesi üzerinde hassas kontrol sağlamak isteyen geliştiriciler için idealdir, görüntü içeriğinin sorunsuz organizasyonu ve özelleştirilmesini garantiler. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_57) | Sağlanan şifre ve eşik değeri kullanarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder. |
| [load(file_path)](#load_file_path_58) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| [load(file_path, load_options)](#load_file_path_load_options_59) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| [load(stream)](#load_stream_60) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(stream, load_options)](#load_stream_load_options_61) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_62) | 32-bit ARGB piksellerini yükler. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_63) | 64-bit ARGB piksellerini yükler. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_64) | CMYK formatında pikselleri yükler. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_65) | CMYK formatında pikselleri yükler.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) yöntemini kullanın. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66) | 32-bit ARGB piksellerini kısmen (bloklar halinde) yükler. |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67) | 64-bit ARGB piksellerini paketler halinde kısmen yükler. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_68) | Pikselleri paketler halinde kısmen yükler. |
| [load_pixels(rectangle)](#load_pixels_rectangle_69) | Pikselleri yükler. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70) | Ham veriyi yükler. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71) | Ham veriyi yükler. |
| [load_stream(stream)](#load_stream_stream_72) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_73) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_74) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| normalize_angle() | Açıyı normalleştirir.<br/>            Bu yöntem, eğik taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir.<br/>            Bu yöntem, [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) ve [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) metodlarını kullanır. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_75) | Açıyı normalleştirir.<br/>            Bu yöntem, eğik taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir.<br/>            Bu yöntem, [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) ve [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) metodlarını kullanır. |
| normalize_histogram() | Görüntü histogramını normalleştirir — piksel değerlerini tüm kullanılabilir aralığı kapsayacak şekilde ayarlar. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_76) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_77) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| remove_metadata() | Bu görüntü örneğinin meta verilerini, bu [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) değerini **None** olarak ayarlayarak kaldırır. |
| [remove_page(page_index)](#remove_page_page_index_78) | Bu kullanışlı yöntemle sayfa listesinden belirtilen indeksdeki sayfayı kaldırın.<br/>            Çok sayfalı görüntülerin yönetimi üzerinde hassas kontrol sağlamak isteyen geliştiriciler için idealdir, görüntü içeriğinin sorunsuz organizasyonu ve özelleştirilmesini garantiler. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.<br/>                Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.<br/>                Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | Bu kullanışlı yöntemle görüntüyü en boy oranını koruyarak yeniden boyutlandırın. Görüntü boyutlarını orantılı olarak ayarlamak isteyen geliştiriciler için idealdir, tutarlılığı sağlar ve orijinal içeriğin oranlarını korur.<br/>            Orantılı yeniden boyutlandırma, her çerçeveyi _newWidth_/width ve _newHeight_/height oranına göre yeniden boyutlandırır. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | Bu basit yeniden boyutlandırma yöntemiyle görüntünüzün boyutunu ayarlayın. Görüntünüzü küçültmeniz ya da büyütmeniz gerekse,<br/>            bu işlev yeniden boyutlandırma ihtiyaçlarınızı verimli ve doğru bir şekilde karşılar,<br/>            hızlı ve kolay görüntü boyutu ayarlamaları arayan geliştiriciler için mükemmeldir. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | Görüntüyü yeniden boyutlandırır. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | Görüntüyü yeniden boyutlandırır. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_89) | Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_90) | Bu kullanıcı dostu yöntemle görüntünün yüksekliğini en boy oranını koruyarak ayarlayın.<br/>            Dinamik olarak görüntüleri yeniden boyutlandırmak ve oranlarını korumak isteyen geliştiriciler için mükemmeldir,<br/>            uygulamalarında optimal görüntüleme ve kullanılabilirliği sağlar. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_91) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_92) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_93) | Bu kullanışlı yöntemle görüntüyü en boy oranını koruyarak yeniden boyutlandırın. Görüntü boyutlarını orantılı olarak ayarlamak isteyen geliştiriciler için idealdir, tutarlılığı sağlar ve orijinal içeriğin oranlarını korur.<br/>            Orantılı yeniden boyutlandırma, her çerçeveyi _newWidth_/width ve _newHeight_/height oranına göre yeniden boyutlandırır. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_94) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_95) | Bu kullanışlı yöntemle görüntünün genişliğini en boy oranını koruyarak ayarlayın.<br/>            Orantılı olarak görüntüleri yeniden boyutlandırmak isteyen geliştiriciler için idealdir, <br/>            tutarlı ve görsel açıdan çekici sonuçlar farklı görüntü ortamlarında sağlanır. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_96) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_97) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [rotate(angle)](#rotate_angle_98) | Görüntüyü merkezin etrafında döndür. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_99) | Bu kullanışlı yöntemle görüntüyü merkez etrafında döndürün. <br/>            Dinamik olarak görüntü yönünü ayarlamak isteyen geliştiriciler için idealdir, optimal sunum ve <br/>            uygulamalar içinde hizalama sağlar. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_100) | Bu basit yöntemle aktif çerçeveyi döndürerek, çevirerek veya her iki işlemi aynı anda yaparak kolayca manipüle edin.<br/>            Dinamik olarak görüntü dizilerinde belirli çerçevelerin yönünü ayarlaması gereken geliştiriciler için idealdir,<br/>            optimal sunum ve hizalama sağlar. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_101) | Tüm çevirme işlemlerini döndürür. |
| save() | Görüntü verilerini temel akıma kaydeder. |
| [save(file_path)](#save_file_path_102) | Görüntüyü belirtilen dosya konumuna kaydeder. |
| [save(file_path, options)](#save_file_path_options_103) | Nesnenin verilerini, belirlenen dosyaya (indeks + dosya adı)<br/>            konumunda ve belirtilen dosya formatı ve seçeneklerle kaydederek koruyun. Farklı formatlarda verileri güvenli bir şekilde depolamak isteyen geliştiriciler için idealdir, <br/>            esneklik ve <br/>            kaydetme parametreleri üzerinde kontrol sağlar. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_104) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save(file_path, over_write)](#save_file_path_over_write_105) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(stream)](#save_stream_106) | Verileri kaydeder. |
| [save(stream, options_base)](#save_stream_options_base_107) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_108) | Bu kullanışlı yöntemle görüntü verilerinizi istenen dosya formatında belirli bir akışa kolayca kaydedin.<br/>            JPEG, PNG veya başka bir formatla çalışıyor olun,<br/>            bu işlev görüntü verilerinizin verimli ve doğru bir şekilde kaydedilmesini sağlar,<br/>            dosya kaydetme süreçlerini basitleştirmek isteyen geliştiriciler için idealdir. |
| [save_all(file_path, options)](#save_all_file_path_options_109) | Nesnenin verilerini, belirlenen dosyaya (indeks + dosya adı)<br/>            konumunda ve belirtilen dosya formatı ve seçeneklerle kaydederek koruyun. Farklı formatlarda verileri güvenli bir şekilde depolamak isteyen geliştiriciler için idealdir, <br/>            esneklik ve <br/>            kaydetme parametreleri üzerinde kontrol sağlar. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_110) | 32-bit ARGB piksellerini kaydeder. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_111) | Pikselleri kaydeder. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_112) | Pikselleri kaydeder.<br/>            Bu yöntem artık kullanılmamaktadır. Lütfen daha etkili olan [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) yöntemini kullanın. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_113) | Pikselleri kaydeder (format özel yöntemi). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_114) | Ham veriyi kaydeder. |
| [save_to_stream(stream)](#save_to_stream_stream_115) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_116) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_118) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_119) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_120) | Belirtilen konum için bir görüntünün 32-bit ARGB pikselini ayarlar. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_121) | Görüntü paletini ayarlar. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_122) | Belirtilen konum için bir görüntü pikselini ayarlar. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_123) | Bu [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) çözünürlüğünü bu<br/>            basit yöntemi kullanarak hassas bir şekilde ayarlayın. Görüntü çözünürlüğünü belirli gereksinimlere göre özelleştirmek isteyen geliştiriciler için idealdir, optimal görüntü kalitesi ve dosya boyutu yönetimini sağlar. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_124) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_126) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |


### Constructor: DicomImage(dicom_options, width, height) {#DicomImage_dicom_options_width_height_1}


```
 DicomImage(dicom_options, width, height) 
```

Bu <br/>            yapıcıyı kullanarak DicomImage sınıfının yeni bir örneğini zahmetsizce başlatın, dicomOptions parametrelerini kullanarak. Projelerinde [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) nesnelerine hızlı ve verimli bir şekilde dalmak isteyen geliştiriciler için mükemmeldir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dicom_options | [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) | Dicom seçenekleri. |
| width | int | Genişlik. |
| height | int | Yükseklik. |

### Constructor: DicomImage(stream) {#DicomImage_stream_2}


```
 DicomImage(stream) 
```

Bu yapıcıda bir akış parametresi kullanarak DicomImage sınıfının yeni bir örneğini oluşturun.<br/>            Projelerinde mevcut veri akışlarından [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) nesnelerini başlatmanın basitleştirilmiş bir yolunu arayan geliştiriciler için mükemmeldir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |


**See also:**

**[Example # 1](#example_130)**: This example shows how to load a DICOM image from a file stream.


### Constructor: DicomImage(stream, load_options) {#DicomImage_stream_load_options_3}


```
 DicomImage(stream, load_options) 
```

Bu yapıcıda bir akış ve<br/>            loadOptions parametrelerini kullanarak DicomImage sınıfının yeni bir örneğini sorunsuz bir şekilde başlatın. Projelerinde [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) nesneleriyle hızlı ve etkili bir şekilde çalışmaya istekli geliştiriciler için idealdir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Yükleme seçenekleri. |


**See also:**

**[Example # 1](#example_131)**: This example shows how to load a DICOM image from a file stream to stay withi...


### Method: add_page() {#add_page__1}


```
 add_page() 
```

Bu basit yöntemle görüntünün sayfa listesine yeni bir sayfa ekleyin.<br/>            Çok sayfalı görüntüleri dinamik olarak genişletmek isteyen geliştiriciler için idealdir, görüntü içeriğinin sorunsuz<br/>            entegrasyonu ve organizasyonunu sağlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | Yeni oluşturulan [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/). |


### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Bu sezgisel yöntemle yeni bir sayfa ekleyerek görüntü koleksiyonunuzu genişletin.<br/>            Çok sayfalı görüntülere dinamik olarak sayfa eklemek isteyen geliştiriciler için idealdir,<br/>            görüntü içeriğinin sorunsuz genişlemesi ve organizasyonunu sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Eklenecek sayfa. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Görüntü parlaklığını _brightness_ ayarıyla artırın, bu<br/>            parametreli yöntem geliştiricilerin görüntülerin ışık yoğunluğunu hassas bir şekilde ayarlamasına olanak tanır.<br/>            Bu kullanıcı dostu işlev, geliştiricilerin görüntü<br/>            parlaklığını sorunsuz bir şekilde manipüle etmelerini sağlar ve görsel estetik üzerinde esneklik ve kontrol sunar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| parlaklık | int | Parlaklık değeri. |


**See also:**

**[Example # 1](#example_143)**: The following example performs brightness correction of a DICOM image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Bu kullanıcı dostu yöntemle [Image](/imaging/python-net/aspose.imaging/image/) kontrastını artırın,<br/>            ışık ve karanlık alanlar arasındaki farkı ayarlayarak. Görsel netliği ve<br/>            tanımı zahmetsizce iyileştirir, geliştiricilere görüntü kontrastı üzerinde sezgisel kontrol sağlayarak<br/>            optimal render elde eder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| kontrast | float | Kontrast değeri ([-100; 100] aralığında) |


**See also:**

**[Example # 1](#example_144)**: The following example performs contrast correction of a DICOM image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Görüntü kalitesini artırın ve gama düzeltmesiyle ayarlayın, görsel görünümü ince ayarlamak için güçlü bir teknik<br/>            . Görüntü sunumunu optimize etmeyi, renk dengesini ayarlamayı ve farklı<br/>            cihaz ve ortamlar arasında tutarlı render sağlamayı hedefleyen geliştiriciler için mükemmeldir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |


**See also:**

**[Example # 1](#example_141)**: The following example performs gamma-correction of a DICOM image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Bir görüntünün kırmızı, yeşil ve mavi bileşenlerine gama düzeltmesini bağımsız olarak uygulayarak kesin renk ayarlamaları elde edin.<br/>            Bu yöntem doğru renk dengesini ve optimal görsel çıktıyı garanti eder, görüntü renderi ve renk doğruluğu üzerinde ayrıntılı<br/>            kontrol arayan geliştiricilere hitap eder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| gamma_red | float | Kırmızı kanal için gamma katsayısı |
| gamma_green | float | Yeşil kanal için gamma katsayısı |
| gamma_blue | float | Mavi kanal katsayısı için gamma |


**See also:**

**[Example # 1](#example_142)**: The following example performs gamma-correction of a DICOM image applying dif...


### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_7}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_8}


```
 binarize_bradley(brightness_difference) 
```

Bradley'nin uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brightness_difference | float | Piksel ile bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin ortalaması arasındaki parlaklık farkı.<br/>                 |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

Bradley'nin uyarlamalı eşikleme algoritmasıyla görüntüleri ikilileştirin, geliştirilmiş performans için integral<br/>            görüntü eşiklemeyi kullanarak. Parlaklıkta yerel değişikliklere dayalı olarak görüntüleri otomatik olarak bölmek isteyen geliştiriciler için idealdir, <br/>            doğru nesne tespiti ve <br/>            değişen aydınlatma koşullarında çıkarımı sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brightness_difference | float | Piksel ile bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin ortalaması arasındaki parlaklık farkı.<br/>             |
| window_size | int | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin boyutu |


**See also:**

**[Example # 1](#example_139)**: The following example binarizes a DICOM image with Bradley's adaptive thresho...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

Bu basit yöntemle önceden tanımlı bir eşik kullanarak görüntüyü kolayca ikili formata dönüştürün<br/>            . Görüntüyü ön plan ve arka plan bileşenlerine bölerek görsel<br/>            işleme görevlerini basitleştirmek isteyen geliştiriciler için idealdir, <br/>            belirtilen yoğunluk seviyelerine göre.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| eşik | System.Byte | Eşik değeri. Bir pikselin ilgili gri değeri eşikten büyükse, ona <br/>            255 değeri atanır, aksi takdirde 0. |


**See also:**

**[Example # 1](#example_137)**: The following example binarizes a DICOM image with the predefined threshold. ...


### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_11}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_12}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_13}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_14}


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


### Method: can_load(stream)  [static] {#can_load_stream_15}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_16}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_17}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_18}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_19}


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


### Method: can_save(options) {#can_save_options_20}


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


### Method: create(files)  [static] {#create_files_21}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_22}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_23}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_24}


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


### Method: create(images)  [static] {#create_images_25}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_26}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_27}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_28}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_29}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_30}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_31}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_32}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Bu çok yönlü yöntemle kaydırmalar uygulayarak görüntünün kırpma alanını ayarlayın.<br/>            Kesme sürecinde hassas kontrol gerektiren geliştiriciler için mükemmeldir, önemli detayların korunmasını sağlarken gereksiz öğeleri ortadan kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| left_shift | int | Sol kaydırma. |
| right_shift | int | Sağ kaydırma. |
| top_shift | int | Üst kaydırma. |
| bottom_shift | int | Alt kaydırma. |


**See also:**

**[Example # 1](#example_136)**: The following example crops a DICOM image. The cropping area is specified via...


### Method: crop(rectangle) {#crop_rectangle_33}


```
 crop(rectangle) 
```

Bu basit yöntemle istenmeyen alanları kaldırmak ve temel içeriğe odaklanmak için görüntüyü kırpın.<br/>            Görüntülerin görsel kompozisyonunu özelleştirmek isteyen geliştiriciler için idealdir, görüntüler, istenen mesajı etkili bir şekilde iletmelerini sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dikdörtgen. |


**See also:**

**[Example # 1](#example_135)**: The following example crops a DICOM image. The cropping area is be specified ...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_34}


```
 dither(dithering_method, bits_count) 
```

Mevcut görüntüde dithering uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithering yöntemi. |
| bits_count | int | Dithering için son bit sayısı. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_35}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Bu basit<br/>            yöntemle dithering etkileri uygulayarak mevcut görüntüyü iyileştirin. Görüntülere doku ve derinlik eklemek isteyen geliştiriciler için mükemmeldir,<br/>            görsel kalitesini ve genel çekiciliğini artırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithering yöntemi. |
| bits_count | int | Dithering için son bit sayısı. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Dithering için özel palet. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_36}


```
 embed_digital_signature(password) 
```

Sağlanan şifreye dayalı dijital imzayı görüntünün her sayfasına yerleştirin.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| parola | string | Dijital imza verisi oluşturmak için kullanılan şifre |

### Method: filter(rectangle, options) {#filter_rectangle_options_37}


```
 filter(rectangle, options) 
```

Belirlenmiş<br/>            dikdörtgenlere filtreler uygulayarak görüntünüzün belirli alanlarını zahmetsizce iyileştirin. Bu yöntem geliştiricilere görüntü manipülasyonu üzerinde hassas kontrol sağlar,<br/>            hedeflenmiş ayarlamalar yaparak istenen<br/>            görsel efektlere kolayca ulaşmalarını mümkün kılar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dikdörtgen. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Seçenekler. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_38}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_39}


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


### Method: get_default_options(args) {#get_default_options_args_40}


```
 get_default_options(args) 
```

Varsayılan seçenekleri alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| args | System.Object | Argümanlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Varsayılan seçenekler |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_41}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel alınacak dikdörtgen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Kısmi piksel yükleyici. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_43}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_44}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_45}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirilmemiş tutmak için faydalı olabilir.<br/>            Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yüklerseniz ve ardından bunu kullanarak<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) yöntemiyle, 8-bit piksel başına sahip bir çıktı PNG görüntüsü üretilecektir.<br/>            Bunu önlemek ve 1-bit piksel başına PNG görüntüsü kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) yöntemine ikinci parametre olarak geçirin.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Orijinal dosya ayarlarına dayalı seçenekler. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_54}


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


### Method: get_skew_angle() {#get_skew_angle__55}


```
 get_skew_angle() 
```

Eğim açısını alır.<br/>            Bu yöntem taranmış metin belgelerine uygulanabilir, tarama sırasında eğim açısını belirlemek için.

**Returns**

| Tür | Açıklama |
| :- | :- |
| float | Eğim açısı, derece cinsinden. |


### Method: insert_page(page_index) {#insert_page_page_index_56}


```
 insert_page(page_index) 
```

Bu sezgisel<br/>            yöntemle görüntünün sayfa listesine belirtilen bir indeksde yeni bir sayfa ekleyin. Çok sayfalı görüntülerde sayfaların düzenlenmesi üzerinde hassas kontrol sağlamak isteyen geliştiriciler için idealdir, görüntü içeriğinin sorunsuz organizasyonu ve özelleştirilmesini garantiler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| page_index | int | Sayfanın indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | Yeni oluşturulan [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/). |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_57}


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


### Method: load(file_path)  [static] {#load_file_path_58}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_59}


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


### Method: load(stream)  [static] {#load_stream_60}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_61}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_62}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_63}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_64}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_65}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32-bit ARGB piksellerini kısmen (bloklar halinde) yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksellerin yükleneceği dikdörtgen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Kısmi piksel yükleyici. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

64-bit ARGB piksellerini paketler halinde kısmen yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | İstenen dikdörtgen. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | 64-bit ARGB piksel yükleyicisi. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_68}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Pikselleri paketler halinde kısmen yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | İstenen dikdörtgen. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Piksel yükleyicisi. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_69}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_72}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_73}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_74}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_75}


```
 normalize_angle(resize_proportionally, background_color) 
```

Açıyı normalleştirir.<br/>            Bu yöntem, eğik taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir.<br/>            Bu yöntem, [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) ve [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) metodlarını kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| resize_proportionally | bool | eğer <c>true</c> olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgene (köşe noktaları) göre projeksiyonlar doğrultusunda değişir; diğer durumda boyutlar aynı kalır ve yalnızca iç görüntü içeriği döndürülür. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Arka plan rengi. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_76}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_77}


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


### Method: remove_page(page_index) {#remove_page_page_index_78}


```
 remove_page(page_index) 
```

Bu kullanışlı yöntemle sayfa listesinden belirtilen indeksdeki sayfayı kaldırın.<br/>            Çok sayfalı görüntülerin yönetimi üzerinde hassas kontrol sağlamak isteyen geliştiriciler için idealdir, görüntü içeriğinin sorunsuz organizasyonu ve özelleştirilmesini garantiler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| page_index | int | Sayfanın indeksi. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_79}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_80}


```
 replace_color(old_color, old_color_diff, new_color) 
```

İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| old_color_diff | System.Byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_81}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_82}


```
 replace_non_transparent_colors(new_color) 
```

Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.<br/>                Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.<br/>                Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color_argb | int | Şeffaf olmayan renkleri değiştirmek için yeni renk ARGB değeri. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_84}


```
 resize(new_width, new_height) 
```

Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_85}


```
 resize(new_width, new_height, resize_type) 
```

Bu kullanışlı yöntemle görüntüyü en boy oranını koruyarak yeniden boyutlandırın. Görüntü boyutlarını orantılı olarak ayarlamak isteyen geliştiriciler için idealdir, tutarlılığı sağlar ve orijinal içeriğin oranlarını korur.<br/>            Orantılı yeniden boyutlandırma, her çerçeveyi _newWidth_/width ve _newHeight_/height oranına göre yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırma türü. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_86}


```
 resize(new_width, new_height, settings) 
```

Bu basit yeniden boyutlandırma yöntemiyle görüntünüzün boyutunu ayarlayın. Görüntünüzü küçültmeniz ya da büyütmeniz gerekse,<br/>            bu işlev yeniden boyutlandırma ihtiyaçlarınızı verimli ve doğru bir şekilde karşılar,<br/>            hızlı ve kolay görüntü boyutu ayarlamaları arayan geliştiriciler için mükemmeldir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Yeniden boyutlandırma ayarları. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_87}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_88}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_89}


```
 resize_height_proportionally(new_height) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_90}


```
 resize_height_proportionally(new_height, resize_type) 
```

Bu kullanıcı dostu yöntemle görüntünün yüksekliğini en boy oranını koruyarak ayarlayın.<br/>            Dinamik olarak görüntüleri yeniden boyutlandırmak ve oranlarını korumak isteyen geliştiriciler için mükemmeldir,<br/>            uygulamalarında optimal görüntüleme ve kullanılabilirliği sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırmanın türü. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_91}


```
 resize_height_proportionally(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_92}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_93}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Bu kullanışlı yöntemle görüntüyü en boy oranını koruyarak yeniden boyutlandırın. Görüntü boyutlarını orantılı olarak ayarlamak isteyen geliştiriciler için idealdir, tutarlılığı sağlar ve orijinal içeriğin oranlarını korur.<br/>            Orantılı yeniden boyutlandırma, her çerçeveyi _newWidth_/width ve _newHeight_/height oranına göre yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırma türü. |

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

Bu kullanışlı yöntemle görüntünün genişliğini en boy oranını koruyarak ayarlayın.<br/>            Orantılı olarak görüntüleri yeniden boyutlandırmak isteyen geliştiriciler için idealdir, <br/>            tutarlı ve görsel açıdan çekici sonuçlar farklı görüntü ortamlarında sağlanır.

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

Bu kullanışlı yöntemle görüntüyü merkez etrafında döndürün. <br/>            Dinamik olarak görüntü yönünü ayarlamak isteyen geliştiriciler için idealdir, optimal sunum ve <br/>            uygulamalar içinde hizalama sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |
| resize_proportionally | bool | Eğer <c>true</c> olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgen (köşe noktaları) projeksiyonlarına göre değişir<br/>            aksi takdirde boyutlar dokunulmaz kalır ve yalnızca<br/>            __internal__ görüntü içeriği döndürülür. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Arka plan rengi. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_100}


```
 rotate_flip(rotate_flip_type) 
```

Bu basit yöntemle aktif çerçeveyi döndürerek, çevirerek veya her iki işlemi aynı anda yaparak kolayca manipüle edin.<br/>            Dinamik olarak görüntü dizilerinde belirli çerçevelerin yönünü ayarlaması gereken geliştiriciler için idealdir,<br/>            optimal sunum ve hizalama sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Döndürme çevirme türü. |


**See also:**

**[Example # 1](#example_132)**: This example loads a DICOM image, rotates it by 90 degrees clockwise and opti...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_101}


```
 rotate_flip_all(rotate_flip) 
```

Tüm çevirme işlemlerini döndürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Döndürme çevirme. |

### Method: save(file_path) {#save_file_path_102}


```
 save(file_path) 
```

Görüntüyü belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Görüntünün kaydedileceği dosya yolu. |

### Method: save(file_path, options) {#save_file_path_options_103}


```
 save(file_path, options) 
```

Nesnenin verilerini, belirlenen dosyaya (indeks + dosya adı)<br/>            konumunda ve belirtilen dosya formatı ve seçeneklerle kaydederek koruyun. Farklı formatlarda verileri güvenli bir şekilde depolamak isteyen geliştiriciler için idealdir, <br/>            esneklik ve <br/>            kaydetme parametreleri üzerinde kontrol sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_104}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_105}


```
 save(file_path, over_write) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verilerinin kaydedileceği dosya yolu. |
| over_write | bool | Eğer <c>true</c> olarak ayarlanırsa dosya içeriği üzerine yazılır, aksi takdirde ekleme yapılır. |

### Method: save(stream) {#save_stream_106}


```
 save(stream) 
```

Verileri kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Verinin kaydedileceği akış. |

### Method: save(stream, options_base) {#save_stream_options_base_107}


```
 save(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_108}


```
 save(stream, options_base, bounds_rectangle) 
```

Bu kullanışlı yöntemle görüntü verilerinizi istenen dosya formatında belirli bir akışa kolayca kaydedin.<br/>            JPEG, PNG veya başka bir formatla çalışıyor olun,<br/>            bu işlev görüntü verilerinizin verimli ve doğru bir şekilde kaydedilmesini sağlar,<br/>            dosya kaydetme süreçlerini basitleştirmek isteyen geliştiriciler için idealdir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş dikdörtgen ayarlayın. |


**See also:**

**[Example # 1](#example_133)**: The following example loads a DICOM image from a file, then saves the image t...


### Method: save_all(file_path, options) {#save_all_file_path_options_109}


```
 save_all(file_path, options) 
```

Nesnenin verilerini, belirlenen dosyaya (indeks + dosya adı)<br/>            konumunda ve belirtilen dosya formatı ve seçeneklerle kaydederek koruyun. Farklı formatlarda verileri güvenli bir şekilde depolamak isteyen geliştiriciler için idealdir, <br/>            esneklik ve <br/>            kaydetme parametreleri üzerinde kontrol sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_110}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32-bit ARGB piksellerini kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| piksel | int[] | 32 bitlik ARGB piksel dizisi. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_111}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Pikselleri kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| piksel | int[] | 32 bitlik tam sayı değerleri olarak sunulan CMYK pikseller. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_112}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Pikselleri kaydeder.<br/>            Bu yöntem artık kullanılmamaktadır. Lütfen daha etkili olan [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) yöntemini kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK piksel dizisi. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_113}


```
 save_pixels(rectangle, pixels) 
```

Pikselleri kaydeder (format özel yöntemi).

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Piksel dizisi. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_114}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_115}


```
 save_to_stream(stream) 
```

Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Nesnenin verisinin kaydedileceği akış. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_116}


```
 save_to_stream_with_options(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_118}


```
 save_with_options(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_119}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_120}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_121}


```
 set_palette(palette, update_colors) 
```

Görüntü paletini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Ayarlanacak palet. |
| update_colors | bool | eğer <c>true</c> olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri yoksa, görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_122}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_123}


```
 set_resolution(dpi_x, dpi_y) 
```

Bu [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) çözünürlüğünü bu<br/>            basit yöntemi kullanarak hassas bir şekilde ayarlayın. Görüntü çözünürlüğünü belirli gereksinimlere göre özelleştirmek isteyen geliştiriciler için idealdir, optimal görüntü kalitesi ve dosya boyutu yönetimini sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dpi_x | float | Yatay çözünürlük, inç başına nokta (dpi) cinsinden, [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) öğesinin. |
| dpi_y | float | Dikey çözünürlük, inç başına nokta (dpi) cinsinden, [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) öğesinin. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_124}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Tüm tarama satırını belirtilen tarama satırı indeksine yazar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int | Tarama satırının sıfır tabanlı indeksi. |
| argb_32_pixels | int[] | Yazılacak 32-bit ARGB renk dizisi. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_126}


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
### This example shows how to load a DICOM image from a file stream. {#example_130}
``` python
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Bir dosya akışından DICOM görüntüsü yükle.
with open(join(dir_, "sample.dicom"), "rb") as stream:
	with DicomImage(stream) as dicom_image:
		# Her sayfayı ayrı bir PNG görüntüsü olarak kaydet.                    
		for dicom_page in dicom_image.dicom_pages:
			# Sayfa indeksine dayalı bir dosya adı oluştur.
			file_name = "sample.{0}.png".format(dicom_page.index)
			# Bir DICOM sayfası bir raster görüntüdür, bu nedenle raster görüntüyle yapılabilecek tüm izin verilen işlemler bir DICOM sayfasına da uygulanabilir.
			dicom_page.save(join(dir_, file_name), PngOptions())


```

### This example shows how to load a DICOM image from a file stream to stay within the specified memory limit. {#example_131}
``` python
from aspose.imaging import LoadOptions, Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.dicom import DicomImage
from os.path import join as path_join


dir_: str = "c:\\temp"
# Bir dosya akışından DICOM görüntüsü yükle.
with open(path_join(dir_, "multiframe.dicom"), "rb") as stream:
	# Tüm iç tamponlar için izin verilen maksimum boyut 256KB'dir.
	load_options = LoadOptions()
	load_options.buffer_size_hint = 256 * 1024
	with DicomImage(stream, load_options) as dicom_image:
		# Her sayfayı ayrı bir PNG görüntüsü olarak kaydet.
		for dicom_page in dicom_image.dicom_pages:
			# Sayfa indeksine dayalı bir dosya adı oluştur.
			file_name = "multiframe.{0}.png".format(dicom_page.index)
			# Bir DICOM sayfası bir raster görüntüdür, bu nedenle raster görüntüyle yapılabilecek tüm izin verilen işlemler bir DICOM sayfasına da uygulanabilir.
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
	# Döndür, çevir ve çıktı dosyasına kaydet.
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
		# Görüntünün sol üst çeyreğini bir dosya akışına kaydet.
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
	# Görüntüyü kırp. Kırpma alanı, görüntünün dikdörtgen merkez bölgesidir.
	area = Rectangle(dicom_image.width // 4, dicom_image.height // 4, dicom_image.width // 2, dicom_image.height // 2)
	dicom_image.crop(area)
	# Kırpılmış görüntüyü PNG olarak kaydet.
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
	# Tekrar kırpın. Görüntü boyutunun %10'u kadar bir kenar boşluğu ayarlayın.
	horizontal_margin = dicom_image.width // 10
	vertical_margin = dicom_image.height // 10
	dicom_image.crop(horizontal_margin, horizontal_margin, vertical_margin, vertical_margin)
	# Kırpılmış görüntüyü PNG olarak kaydedin.
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
	# Görüntüyü 127 eşik değeriyle ikilileştirin.
	# Bir pikselin karşılık gelen gri değeri 127'den büyükse, ona 255 değeri atanır, aksi takdirde 0 atanır.
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
	# Görüntüyü 5 parlaklık farkı ile ikilileştirin. Parlaklık, bir piksel ile bu pikselin etrafındaki 10 x 10 piksellik pencerenin ortalaması arasındaki farktır.
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
	# Kırmızı, yeşil ve mavi kanallar için gama katsayısını ayarlayın.
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
	# Kırmızı, yeşil ve mavi kanallar için ayrı ayrı gama katsayılarını ayarlayın.
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
	# Parlaklık değerini ayarlayın. Kabul edilen parlaklık değerleri [-255, 255] aralığındadır.
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
	# Kontrast değerini ayarlayın. Kabul edilen kontrast değerleri [-100f, 100f] aralığındadır.
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

