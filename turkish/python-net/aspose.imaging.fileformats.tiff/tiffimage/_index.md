---
title: "TiffImage Sınıfı"
type: docs
weight: 200
url: /tr/python-net/aspose.imaging.fileformats.tiff/tiffimage/
---

**Summary:** Process Tagged Image File Format (TIFF) raster images with our API, offering<br/>            comprehensive support for various resolutions and advanced editing capabilities<br/>            like EXIF data manipulation and alpha channels. Normalize angles for scanned images,<br/>            resize, transform to grayscale, and apply filters, gamma corrections and image<br/>            parameters adjustments with ease. Seamlessly handle multi-frame TIFF files,<br/>            create graphics paths, add shapes, and effortlessly save images to different formats.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TiffImage(frame)](#TiffImage_frame_1) | Yeni bir nesne başlatır [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) sınıfının, <br/>            frame parametresini belirterek. Bu yapıcı, bir TiffImage <br/>            örneğinin oluşturulmasını kolaylaştırır, geliştiricilerin yüklenecek veya işlenecek çerçeveyi belirtmesine olanak tanır, <br/>            uygulamalarında Tiff görüntü işleme görevlerini sadeleştirir. |
| [TiffImage(frames)](#TiffImage_frames_2) | Yeni bir [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) sınıfının örneğini oluşturur, parametre olarak <br/>            çerçevelerin bir listesini sağlar. Bu yapıcı, bir TiffImage <br/>            nesnesinin birden fazla çerçeve ile başlatılmasını sağlar, yazılım uygulamalarında <br/>            TIFF görüntü dizilerinin verimli işlenmesini ve yönetilmesini kolaylaştırır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| active_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r/w | Aktif çerçeveyi sorunsuz bir şekilde yönetin, belirlenen bağlam içinde dinamik gezinme ve <br/>            manipülasyonu kolaylaştırın. Uygulamanızı çoklu ortam içeriğiyle verimli bir şekilde etkileşime girecek şekilde güçlendirin, kullanıcı katılımını ve verimliliği artırın. |
| auto_adjust_palette | bool | r/w | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Arka plan renginin değerini alır veya ayarlar. |
| bits_per_pixel | int | r | Görselin piksel başına bit sayısını alır. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Nesnenin sınırlarını alır. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | TIFF dosyaları için bayt sırasını sorunsuz bir şekilde değiştirin, veri yorumlaması üzerinde hassas kontrol sağlayın. Uygulamalarınızı çeşitli dosya özelliklerine uyum sağlama esnekliğiyle güçlendirin, uyumluluğu ve veri işleme verimliliğini artırın. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Bu [Image](/imaging/python-net/aspose.imaging/image/) kapsayıcısını alır. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Nesnenin veri akışını alır. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif örneğini alır veya ayarlar. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Görüntüyle ilişkili dosya formatı değerini alır. Bu özellik, <br/>            görüntü meta verisi alımının kritik bir yönü olarak hizmet eder, yazılım uygulamalarının <br/>            görüntü verisinin formatını verimli bir şekilde tanımlamasına ve yorumlamasına olanak tanır. |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) örneklerinin bir dizisini alın, TIFF görüntüsü içindeki bireysel çerçevelere kapsamlı <br/>            erişim ve manipülasyon sağlar. Bu dizinin gücünden yararlanarak görüntü işleme iş akışlarını kolaylaştırın, görsel içeriğin hassas kontrolünü ve optimizasyonunu sağlayın. |
| [has_alpha](#has_alpha1) | bool | r | Görselin alfa kanalı olup olmadığını belirleyin, renderleme ve birleştirme işlemleri için kritik bilgi sağlar. Bu özelliği entegre ederek görsel işleme iş akışlarını optimize edin, şeffaf öğelerin doğru temsili ve manipülasyonunu sağlayın. |
| has_background_color | bool | r/w | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| has_transparent_color | bool | r/w | Görüntünün şeffaf bir renge sahip olup olmadığını gösteren bir değeri alır. |
| height | int | r | Görüntünün yüksekliğini alır. |
| horizontal_resolution | float | r/w | Belirtilen [Image](/imaging/python-net/aspose.imaging/image/) öğesinin yatay çözünürlüğünü inç başına piksel olarak alın, hassas ayar ve renderleme yeteneklerini kolaylaştırır. Temel görüntü meta verilerine zahmetsizce erişin, geliştirilmiş kullanıcı deneyimleri için akıcı görüntü işleme iş akışlarını güçlendirin. |
| image_opacity | float | r | Bu görüntünün opaklığını alır. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Kesinti izleyicisini alır veya ayarlar. |
| is_cached | bool | r | Görüntü verisinin şu anda önbelleğe alınıp alınmadığını gösteren bir değeri alır. |
| is_raw_data_available | bool | r | Ham veri yüklemesinin desteklenip desteklenmediğini gösteren bir değeri alır. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Kareden XMP verisini alır veya ayarlar. |
| page_count | int | r | Belirtilen belgedeki toplam sayfa sayısını alın, çok sayfalı içeriğin verimli gezinmesi ve yönetimini kolaylaştırır. Bu işlevi, kullanıcı deneyimini artırmak için entegre edin; böylece kapsamlı belge yapılarının sorunsuz erişimi sağlanır. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Belgenin sayfalarına sorunsuz bir şekilde erişin, içerik yapısı içinde dinamik gezinme ve <br/>            manipülasyonu mümkün kılar. Uygulamanızı bireysel sayfalara verimli erişimle güçlendirin, belge işleme süreçlerini kolaylaştırın ve kullanıcı etkileşimini artırın. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| premultiply_components | bool | r/w | Bileşenlerin ön çarpım gerektirip gerektirmediğini belirtin, görsel öğelerin verimli işlenmesini sağlar. Bu özelliği değiştirerek renderleme süreçlerini iyileştirin, grafik iş akışlarını optimize edilmiş performans için kolaylaştırın. |
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
| vertical_resolution | float | r/w | Belirtilen [Image](/imaging/python-net/aspose.imaging/image/) öğesinin dikey çözünürlüğünü inç başına piksel olarak alın, hassas ayarlar ve renderleme optimizasyonları sağlar. Temel görüntü verilerini zahmetsizce kullanarak görüntü işleme iş akışlarını kolaylaştırın, uygulamalarınızda üstün kalite ve performans sağlayın. |
| width | int | r | Görüntünün genişliğini alır. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Xmp verilerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(image)](#add_image_1) | Belirtilen görüntüden çerçeveleri sorunsuz bir şekilde mevcut çerçeveye ekleyin, içeriklerini birleştirerek kompozisyon esnekliğini artırın. Bu yöntemi entegre ederek çerçeve yönetimini ve uygulamanız içinde manipülasyonu kolaylaştırın, çoklu çerçeve görüntülerinin verimli işlenmesini sağlayın. |
| [add_frame(frame)](#add_frame_frame_2) | Belirtilen çerçeveyi sorunsuz bir şekilde görüntüye dahil edin, içeriğini ve çok yönlülüğünü genişletin. Bu yöntemi kullanarak görüntü kompozisyonunu ve yönetimini geliştirin, uygulamanız içinde çoklu çerçeve görüntülerinin verimli işlenmesini sağlayın. |
| [add_frames(frames)](#add_frames_frames_3) | Çerçeve dizisini sorunsuz bir şekilde görüntüye entegre edin, içeriğini ve çok yönlülüğünü zenginleştirin. Bu yöntemi kullanarak görüntü kompozisyonunu ve yönetimini geliştirin, uygulamanız içinde çoklu çerçeve görüntülerinin verimli işlenmesini mümkün kılın. |
| [add_page(page)](#add_page_page_4) | Mevcut görüntüye yeni bir sayfayı sorunsuz bir şekilde ekleyerek içeriğini <br/>            ve çok yönlülüğünü genişletir. Bu yöntemi belge oluşturmayı ve <br/>            yönetimini iyileştirmek için kullanın, uygulamanızda çok sayfalı görüntülerin verimli bir şekilde işlenmesini sağlar. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_5) | Görüntü için _brightness_ ayarlamasını uygulayın, genel aydınlık seviyelerinin değiştirilmesine izin verir. Bu yöntemi görüntü işleme iş akışınıza entegre ederek görünürlüğü artırın ve uygulamanızdaki görüntülerin görsel kalitesini iyileştirin. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_6) | [Image](/imaging/python-net/aspose.imaging/image/) örneğinin kontrastını artırın, <br/>            ışık ve karanlık bölgeler arasındaki farkları büyütün. Bu işlevi entegre ederek görüntünün görsel netliğini ve genel kalitesini uygulamanız içinde iyileştirin. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_7) | Görüntüye gama düzeltmesi uygulayarak piksel yoğunluklarını ayarlayın ve istenen renk dengesine ulaşın. <br/>            Bu yöntemi görüntü işleme <br/>            iş akışınıza dahil ederek görsel kaliteyi artırın ve sonraki <br/>            analiz veya görüntüleme görevlerinin doğruluğunu iyileştirin. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_8) | Görüntüye, kırmızı, <br/>            yeşil ve mavi kanallar için ayrı katsayılar kullanarak gama düzeltmesi uygulayın; bu, renk dengesi ve kontrastın ince ayarını sağlar. Bu yöntemi görüntü işleme hattınıza entegre ederek renk render'ı üzerinde hassas kontrol elde edin ve uygulamanızda görsel doğruluğu artırın. |
| align_resolutions() | AlignResolutions yardımcı yöntemini uygulayarak yatay ve <br/>            dikey çözünürlükleri senkronize edin, böylece görüntü boyutlarında tutarlılık sağlanır. Bu işlevsellik, çözünürlük <br/>            parametrelerini uyumlu hale getirerek görüntü işleme iş akışlarını sadeleştirir, görsel kaliteyi ve çeşitli platformlar ile <br/>            cihazlar arasında tutarlılığı optimize eder. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_9) | Çıkarılan veri ile orijinal şifre arasındaki yüzde benzerliğini hesaplar. |
| auto_brightness_contrast() | Tüm görüntü için otomatik uyarlamalı parlaklık ve kontrast normalizasyonu gerçekleştirir. |
| auto_rotate() | Exif <br/>            meta veriler. Bu yöntem, görüntülerin doğru yönlendirmede gösterilmesini sağlar, <br/>            kullanıcı deneyimini artırır ve manuel ayarlama ihtiyacını ortadan kaldırır. İle <br/>            Exif bilgilerini analiz ederek, görüntü buna göre döndürülür, sorunsuz bir <br/>            farklı platform ve cihazlarda görüntüleme deneyimi sağlar. Bu otomatik döndürme <br/>            süreci, görüntü işlemini basitleştirir ve özellikle <br/>            farklı yönlerdeki büyük görüntü gruplarıyla çalışırken genel kullanılabilirliği artırır. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_10) | Bradley'nin uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_11) | Görüntüde Bradley'ın adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak ikileştirme uygulayın. Bu yaklaşım, görüntünün komşuluğuna dayalı olarak yerel eşikleri dinamik olarak hesaplar, değişen ışık koşullarına uyumu artırır ve sonraki <br/>            işleme görevleri için sağlam bir segmentasyon sağlar. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_12) | Önceden tanımlı bir eşik kullanarak görüntüyü ikileştirin ve onu belirgin ön plan ve arka plan bölgelerine sahip bir ikili görüntüye dönüştürün. Bu yöntemi görüntü işleme iş akışınıza dahil ederek segmentasyon ve özellik <br/>            çıkarma görevlerini kolaylaştırın, uygulamanızdaki görüntü analizinin doğruluğunu ve verimliliğini artırın. |
| binarize_otsu() | Görüntüyü ikileştirmek için Otsu eşikleme kullanın; bu, görüntünün histogramına dayanarak optimal eşik değerini otomatik olarak belirler. Bu yöntemi görüntü işleme iş akışınıza entegre ederek etkili segmentasyon ve özellik çıkarma elde edin, uygulamanızdaki görüntü analiz görevlerinin doğruluğunu ve güvenilirliğini artırın. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_13) | Bu görüntü örneğini _overlay_ görüntüsüyle karıştırır. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_14) | Bu görüntü örneğini _overlay_ görüntüsüyle karıştırır. |
| cache_data() | Verileri özel olarak önbelleğe alır. |
| [can_load(file_path)](#can_load_file_path_15) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_16) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler. |
| [can_load(stream)](#can_load_stream_17) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load(stream, load_options)](#can_load_stream_load_options_18) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen _loadOptions_ kullanılarak belirler. |
| [can_load_stream(stream)](#can_load_stream_stream_19) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_20) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen _loadOptions_ kullanılarak belirler. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_21) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler. |
| [can_save(options)](#can_save_options_22) | Geçilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına görüntünün kaydedilip kaydedilemeyeceğini belirler. |
| [create(files)](#create_files_23) | Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_24) | Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur. |
| [create(image_options, width, height)](#create_image_options_width_height_25) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_26) | Sağlanan piksel dizisinden bir [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) örneği oluşturur.<br/>            <br/>            Belirtilen genişlik ve yüksekliğin piksel verisinin boyutlarıyla eşleştiğini doğrular.<br/>            Bu yöntem yalnızca kütüphane Lisanslı modda olduğunda kullanılabilir. |
| [create(images)](#create_images_27) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create(images, dispose_images)](#create_images_dispose_images_28) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create(multipage_create_options)](#create_multipage_create_options_29) | Belirtilen çok sayfalı oluşturma seçeneklerini oluşturur. |
| [create_from_files(files)](#create_from_files_files_30) | Belirtilen dosyaları tembel yükleme sayfaları olarak içeren çok sayfalı bir görüntü oluşturur. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_31) | Belirtilen dosyaları tembel yükleme sayfaları olarak içeren çok sayfalı bir görüntü oluşturur. |
| [create_from_images(images)](#create_from_images_images_32) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_33) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create_with_frame(frame)](#create_with_frame_frame_34) | Yeni bir örnek başlatır [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) sınıfını. |
| [create_with_frames(frames)](#create_with_frames_frames_35) | Yeni bir örnek başlatır [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) sınıfını. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_36) | Görüntüyü, sol, sağ, üst ve <br/>            alt yönlerde kaydırmalar belirterek kırpın. Bu yöntem, görüntünün istenen kısmını hassas bir şekilde seçmenizi sağlar, istenmeyen alanların etkili bir şekilde kaldırılmasını ve temel içeriğe odaklanılmasını kolaylaştırır. Bu işlevi görüntü işleme <br/>            hattınıza entegre ederek uygulamanızda gerektiği gibi netlik ve kompozisyonu artırın. |
| [crop(rectangle)](#crop_rectangle_37) | Belirtilen dikdörtgen bölgeyi kullanarak görüntüyü kırpın, böylece istenen içeriği hassas bir şekilde seçebilirsiniz. Bu yöntemi görüntü işleme iş akışınıza entegre ederek istenmeyen alanları etkili bir şekilde kaldırın ve temel detaylara odaklanın, görüntünün genel netliğini ve kompozisyonunu artırın. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_38) | Mevcut görüntüde dithering uygular. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_39) | Mevcut görüntüde dithering uygulayarak görsel kalitesini artırın ve renk bantlama artefaktlarını azaltın. Bu yöntemi görüntü işleme iş akışınıza entegre ederek renk geçişlerini daha yumuşak hale getirin, böylece genel görüntü görünümü ve netliği iyileşsin. |
| [embed_digital_signature(password)](#embed_digital_signature_password_40) | Sağlanan şifreye dayalı dijital imzayı görüntünün her sayfasına yerleştirin. |
| [filter(rectangle, options)](#filter_rectangle_options_41) | Belirtilen dikdörtgen içindeki içeriği filtreleyin, seçilen bölgeyi geliştirmek veya değiştirmek için belirlenmiş bir görüntü <br/>            işleme filtresi uygulayın. Bu yöntemi görüntü manipülasyonu iş akışınıza entegre ederek hedeflenmiş iyileştirmeler veya <br/>            dönüşümler elde edin. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_42) | Bir görüntünün 32-bit ARGB pikselini alır. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_43) | Varsayılan 32-bit ARGB piksel dizisini alır. |
| [get_default_options(args)](#get_default_options_args_44) | Varsayılan seçenekleri alır. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_45) | Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_46) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_47) | Varsayılan ham veri dizisini alır. |
| [get_file_format(file_path)](#get_file_format_file_path_48) | Dosya biçimini alır. |
| [get_file_format(stream)](#get_file_format_stream_49) | Dosya biçimini alır. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_50) | Dosya biçimini alır. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_51) | Mevcut görüntüyü saran dikdörtgeni alır. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_52) | Mevcut görüntüyü saran dikdörtgeni alır. |
| [get_modify_date(use_default)](#get_modify_date_use_default_53) | Kaynak görüntünün en son değiştirildiği tarih ve saati alır. |
| [get_original_options()](#get_original_options__54) | Orijinal dosya ayarlarından türetilen seçenekleri alın, böylece bit derinliği ve orijinal görüntünün diğer önemli özellikleri gibi temel parametrelerin sorunsuz <br/>            korunması sağlanır. Bu yöntemi görüntü işleme görevlerinde doğruluk ve tutarlılığı sürdürmek için kullanın, gereksiz değişiklikler olmadan optimum sonuçlar elde edin.<br/>            Örneğin, 1 bit/piksel siyah-beyaz bir PNG görüntüsü yükleyip ardından <br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilir.<br/>            Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) yöntemine ikinci parametre olarak geçirin. |
| [get_pixel(x, y)](#get_pixel_x_y_55) | Bir görüntü pikselini alır. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_56) | Orantılı bir yükseklik alır. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_57) | Orantılı bir genişlik alır. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_58) | aps'ye dönüştürür. |
| [get_skew_angle()](#get_skew_angle__59) | Eğim açısını alır.<br/>            Bu yöntem taranmış metin belgelerine uygulanabilir, tarama sırasında eğim açısını belirlemek için. |
| grayscale() | Görüntüyü gri tonlamalı temsiline dönüştürün, böylece her pikselin yoğunluğu temsil ettiği tek kanallı bir görüntü elde edin. Bu yöntemi görüntü işleme hattınıza entegre ederek analizi basitleştirin ve gri tonlamalı algoritmalarla uyumluluğu artırın, uygulamanızda çeşitli bilgisayar <br/>            görüsü ve görüntü analiz görevlerini kolaylaştırın. |
| [insert_frame(index, frame)](#insert_frame_index_frame_60) | Yeni çerçeveyi çerçeve dizisinde belirtilen indekse ekleyin, böylece çerçeve düzeni üzerinde hassas kontrol sağlanır. Bu yöntemi çerçeve dizilerini etkili bir şekilde yönetmek, görüntü içeriğinin dinamik manipülasyonu ve organizasyonunu kolaylaştırmak için kullanın. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_61) | Sağlanan şifre ve eşik değeri kullanarak görüntünün dijital olarak imzalı olup olmadığını hızlı bir şekilde kontrol eder. |
| [load(file_path)](#load_file_path_62) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| [load(file_path, load_options)](#load_file_path_load_options_63) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| [load(stream)](#load_stream_64) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(stream, load_options)](#load_stream_load_options_65) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_66) | 32-bit ARGB piksellerini yükler. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_67) | 64-bit ARGB piksellerini yükler. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_68) | CMYK formatında pikselleri yükler. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_69) | CMYK formatında pikselleri yükler.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) yöntemini kullanın. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70) | 32-bit ARGB piksellerini kısmen (bloklar halinde) yükler. |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71) | 64-bit ARGB piksellerini paketler halinde kısmen yükler. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_72) | Pikselleri paketler halinde kısmen yükler. |
| [load_pixels(rectangle)](#load_pixels_rectangle_73) | Pikselleri yükler. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74) | Ham veriyi yükler. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75) | Ham veriyi yükler. |
| [load_stream(stream)](#load_stream_stream_76) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_77) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_78) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| normalize_angle() | Açıyı normalleştirir.<br/>            Bu yöntem, eğik taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir.<br/>            Bu yöntem, [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) ve [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) metodlarını kullanır. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_79) | Tarama metin belgeleri için özel olarak tasarlanmış NormalizeAngle yöntemini kullanarak eğik taramaları düzeltin, doğru hizalamayı sağlayın. Bu işlevi metin işleme iş akışlarınıza sorunsuz bir şekilde entegre ederek belge okunabilirliğini ve kalitesini artırın, metin tanıma ve analiz görevlerinde genel verimliliği iyileştirin.<br/>            Bu yöntem [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) ve [TiffImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) metodlarını kullanır. |
| normalize_histogram() | Görüntü histogramını normalleştirir — piksel değerlerini tüm kullanılabilir aralığı kapsayacak şekilde ayarlar. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_80) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_81) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| [remove_frame(frame)](#remove_frame_frame_82) | Belirtilen çerçeveyi görüntü dizisinden verimli bir şekilde kaldırın, uygulamanızda çerçeve yönetimini sadeleştirin. Bu işlevi entegre ederek çerçeve manipülasyonunda hassasiyet ve esnekliği artırın, görüntü içeriğinin sorunsuz organizasyonu ve sunumunu sağlayın. |
| [remove_frame(index)](#remove_frame_index_83) | Çerçeveyi indeksine göre kaldırır. |
| [remove_frame_by_index(index)](#remove_frame_by_index_index_84) | Çerçeveyi indeksine göre kaldırır. |
| remove_metadata() | Bu görüntü örneğinin meta verilerini, bu [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) ve [IHasExifData.exif_data](/imaging/python-net/aspose.imaging.exif/ihasexifdata/) değerlerini **None** olarak ayarlayarak kaldırır. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_85) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_86) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_87) | İzin verilen farkla bir rengi başka bir renkle değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur. |
| [replace_frame(index, new_frame)](#replace_frame_index_new_frame_88) | Belirtilen konumdaki çerçeveyi başka bir çerçeve ile sorunsuz bir şekilde değiştirin, <br/>            görüntü dizisinde dinamik çerçeve yönetimini kolaylaştırın. Bu yöntemi entegre ederek çerçeve manipülasyonunda esneklik ve hassasiyeti artırın, uygulamanızda görüntü içeriğinin optimal organizasyonu ve sunumunu sağlayın. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_89) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.<br/>                Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_90) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.<br/>                Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [resize(new_width, new_height)](#resize_new_width_new_height_91) | Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_92) | Görüntü üzerinde oranlı yeniden boyutlandırma işlemi yapın, boyutlarını ayarlarken en-boy oranını koruyun. Bu yöntemi uygulamanızda görüntüleri dinamik olarak ölçeklendirmek için kullanın, içeriğin tutarlılığını görsel olarak tutarlı bir şekilde temsil edin.<br/>            Oranlı yeniden boyutlandırma, her çerçeveyi _newWidth_/width ve _newHeight_/height oranına göre yeniden boyutlandıracaktır. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_93) | Görüntünün boyutunu belirtilen ayarlara göre ayarlayın, böylece boyutlar, en-boy oranı ve ölçekleme davranışı üzerinde hassas kontrol sağlanır. Bu yöntemi görüntü işleme iş akışınıza entegre ederek uygulamanızın özel gereksinimlerine göre özelleştirilmiş yeniden boyutlandırma işlemleri gerçekleştirin. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_94) | Görüntüyü yeniden boyutlandırır. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_95) | Görüntüyü yeniden boyutlandırır. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_96) | Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_97) | Görüntünün yüksekliğini oranlı olarak ayarlayın, en-boy oranını koruyarak tutarlı görsel bütünlük sağlayın. Bu yöntemi uygulamanızda görüntüleri dinamik olarak yeniden boyutlandırmak için kullanın, çeşitli platformlar ve cihazlar arasında içerik kalitesinden ödün vermeden optimal görüntüleme sağlayın. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_98) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_99) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_100) | Görüntü üzerinde oranlı yeniden boyutlandırma işlemi yapın, boyutlarını ayarlarken en-boy oranını koruyun. Bu yöntemi uygulamanızda görüntüleri dinamik olarak ölçeklendirmek için kullanın, içeriğin tutarlılığını görsel olarak tutarlı bir şekilde temsil edin.<br/>            Oranlı yeniden boyutlandırma, her çerçeveyi _newWidth_/width ve _newHeight_/height oranına göre yeniden boyutlandıracaktır. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_101) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_102) | Görüntünün genişliğini, en-boy oranını koruyarak ayarlayın, böylece optimal görsel sunum için oranlı yeniden boyutlandırma sağlanır. Bu yöntemi uygulamanızda görüntüleri dinamik olarak ölçeklendirmek için kullanın, çeşitli görüntüleme bağlamlarında tutarlı ve estetik açıdan hoş bir render elde edin. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_103) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_104) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [rotate(angle)](#rotate_angle_105) | Görüntüyü merkezin etrafında döndür. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_106) | Görüntüyü, merkez noktasının etrafında belirtilen bir açıyla döndürün, böylece hassas yönlendirme ayarlamaları mümkün olur. Bu işlevi görüntü işleme hattınıza entegre ederek doğru dönüşümleri kolaylaştırın, uygulamanızda görsel içeriğin optimal hizalanmasını ve sunumunu sağlayın. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_107) | Yalnızca aktif çerçeve üzerinde döndürme, çevirme veya her ikisinin bir kombinasyonunu gerçekleştirin. Bu yöntem, görüntü dizisindeki tek tek çerçevelerin hassas manipülasyonunu sağlar, uygulamanızda görüntü düzenleme ve kompozisyon esnekliğini artırır. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_108) | Tüm çevirme işlemlerini döndürür. |
| save() | Görüntü verilerini temel akıma kaydeder. |
| [save(file_path)](#save_file_path_109) | Görüntüyü belirtilen dosya konumuna kaydeder. |
| [save(file_path, options)](#save_file_path_options_110) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_111) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save(file_path, over_write)](#save_file_path_over_write_112) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(stream)](#save_stream_113) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save(stream, options_base)](#save_stream_options_base_114) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_115) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_116) | 32-bit ARGB piksellerini kaydeder. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_117) | Pikselleri kaydeder. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_118) | Pikselleri kaydeder.<br/>            Bu yöntem artık kullanılmamaktadır. Lütfen daha etkili olan [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) yöntemini kullanın. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_119) | Piksel verilerini dahili olarak kaydeder. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_120) | Ham veriyi kaydeder. |
| [save_to_stream(stream)](#save_to_stream_stream_121) | Görüntüyü akışa kaydeder |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_122) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_123) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_124) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_125) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_126) | Belirtilen konum için bir görüntünün 32-bit ARGB pikselini ayarlar. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_127) | Görüntü paletini ayarlar. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_128) | Belirtilen konum için bir görüntü pikselini ayarlar. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_129) | Belirtilen [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) için çözünürlüğü ayarlar, <br/>            görüntü işleme ve gösterim özellikleri üzerinde hassas kontrol sağlar. Bu <br/>            işlevi bütünleştirerek görsel çıktıyı optimize edin ve çeşitli <br/>            çıktı cihazları ve platformlarıyla uyumluluğu sağlayın, genel kullanıcı deneyimini artırır. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_130) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_131) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_132) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |


### Constructor: TiffImage(frame) {#TiffImage_frame_1}


```
 TiffImage(frame) 
```

Yeni bir nesne başlatır [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) sınıfının, <br/>            frame parametresini belirterek. Bu yapıcı, bir TiffImage <br/>            örneğinin oluşturulmasını kolaylaştırır, geliştiricilerin yüklenecek veya işlenecek çerçeveyi belirtmesine olanak tanır, <br/>            uygulamalarında Tiff görüntü işleme görevlerini sadeleştirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Görüntüyü başlatmak için kullanılacak tiff çerçevesi. |

### Constructor: TiffImage(frames) {#TiffImage_frames_2}


```
 TiffImage(frames) 
```

Yeni bir [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) sınıfının örneğini oluşturur, parametre olarak <br/>            çerçevelerin bir listesini sağlar. Bu yapıcı, bir TiffImage <br/>            nesnesinin birden fazla çerçeve ile başlatılmasını sağlar, yazılım uygulamalarında <br/>            TIFF görüntü dizilerinin verimli işlenmesini ve yönetilmesini kolaylaştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Çerçeveler. |

### Property: has_alpha {#has_alpha1}

Görselin alfa kanalı olup olmadığını belirleyin, renderleme ve birleştirme işlemleri için kritik bilgi sağlar. Bu özelliği entegre ederek görsel işleme iş akışlarını optimize edin, şeffaf öğelerin doğru temsili ve manipülasyonunu sağlayın.

**See also:**

**[Example # 1](#example_119)**: The following example loads a TIFF image and prints information about raw dat...


### Method: add(image) {#add_image_1}


```
 add(image) 
```

Belirtilen görüntüden çerçeveleri sorunsuz bir şekilde mevcut çerçeveye ekleyin, içeriklerini birleştirerek kompozisyon esnekliğini artırın. Bu yöntemi entegre ederek çerçeve yönetimini ve uygulamanız içinde manipülasyonu kolaylaştırın, çoklu çerçeve görüntülerinin verimli işlenmesini sağlayın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) | Kaynak görüntü. |

### Method: add_frame(frame) {#add_frame_frame_2}


```
 add_frame(frame) 
```

Belirtilen çerçeveyi sorunsuz bir şekilde görüntüye dahil edin, içeriğini ve çok yönlülüğünü genişletin. Bu yöntemi kullanarak görüntü kompozisyonunu ve yönetimini geliştirin, uygulamanız içinde çoklu çerçeve görüntülerinin verimli işlenmesini sağlayın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Eklenecek çerçeve. |

### Method: add_frames(frames) {#add_frames_frames_3}


```
 add_frames(frames) 
```

Çerçeve dizisini sorunsuz bir şekilde görüntüye entegre edin, içeriğini ve çok yönlülüğünü zenginleştirin. Bu yöntemi kullanarak görüntü kompozisyonunu ve yönetimini geliştirin, uygulamanız içinde çoklu çerçeve görüntülerinin verimli işlenmesini mümkün kılın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Eklenecek çerçeve dizisi |

### Method: add_page(page) {#add_page_page_4}


```
 add_page(page) 
```

Mevcut görüntüye yeni bir sayfayı sorunsuz bir şekilde ekleyerek içeriğini <br/>            ve çok yönlülüğünü genişletir. Bu yöntemi belge oluşturmayı ve <br/>            yönetimini iyileştirmek için kullanın, uygulamanızda çok sayfalı görüntülerin verimli bir şekilde işlenmesini sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Eklenecek sayfa. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_5}


```
 adjust_brightness(brightness) 
```

Görüntü için _brightness_ ayarlamasını uygulayın, genel aydınlık seviyelerinin değiştirilmesine izin verir. Bu yöntemi görüntü işleme iş akışınıza entegre ederek görünürlüğü artırın ve uygulamanızdaki görüntülerin görsel kalitesini iyileştirin.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| parlaklık | int | Parlaklık değeri. |


**See also:**

**[Example # 1](#example_128)**: The following example performs brightness correction of a TIFF image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_6}


```
 adjust_contrast(contrast) 
```

[Image](/imaging/python-net/aspose.imaging/image/) örneğinin kontrastını artırın, <br/>            ışık ve karanlık bölgeler arasındaki farkları büyütün. Bu işlevi entegre ederek görüntünün görsel netliğini ve genel kalitesini uygulamanız içinde iyileştirin.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| kontrast | float | Kontrast değeri ([-100; 100] aralığında) |


**See also:**

**[Example # 1](#example_129)**: The following example performs contrast correction of a TIFF image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_7}


```
 adjust_gamma(gamma) 
```

Görüntüye gama düzeltmesi uygulayarak piksel yoğunluklarını ayarlayın ve istenen renk dengesine ulaşın. <br/>            Bu yöntemi görüntü işleme <br/>            iş akışınıza dahil ederek görsel kaliteyi artırın ve sonraki <br/>            analiz veya görüntüleme görevlerinin doğruluğunu iyileştirin.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |


**See also:**

**[Example # 1](#example_126)**: The following example performs gamma-correction of a TIFF image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_8}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Görüntüye, kırmızı, <br/>            yeşil ve mavi kanallar için ayrı katsayılar kullanarak gama düzeltmesi uygulayın; bu, renk dengesi ve kontrastın ince ayarını sağlar. Bu yöntemi görüntü işleme hattınıza entegre ederek renk render'ı üzerinde hassas kontrol elde edin ve uygulamanızda görsel doğruluğu artırın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| gamma_red | float | Kırmızı kanal için gamma katsayısı |
| gamma_green | float | Yeşil kanal için gamma katsayısı |
| gamma_blue | float | Mavi kanal katsayısı için gamma |


**See also:**

**[Example # 1](#example_127)**: The following example performs gamma-correction of a TIFF image applying diff...


### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_9}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_10}


```
 binarize_bradley(brightness_difference) 
```

Bradley'nin uyarlamalı eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brightness_difference | float | Piksel ile bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin ortalaması arasındaki parlaklık farkı.<br/>                 |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_11}


```
 binarize_bradley(brightness_difference, window_size) 
```

Görüntüde Bradley'ın adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak ikileştirme uygulayın. Bu yaklaşım, görüntünün komşuluğuna dayalı olarak yerel eşikleri dinamik olarak hesaplar, değişen ışık koşullarına uyumu artırır ve sonraki <br/>            işleme görevleri için sağlam bir segmentasyon sağlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| brightness_difference | float | Piksel ile bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin ortalaması arasındaki parlaklık farkı.<br/>             |
| window_size | int | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin boyutu |


**See also:**

**[Example # 1](#example_124)**: The following example binarizes a TIFF image with Bradley's adaptive threshol...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_12}


```
 binarize_fixed(threshold) 
```

Önceden tanımlı bir eşik kullanarak görüntüyü ikileştirin ve onu belirgin ön plan ve arka plan bölgelerine sahip bir ikili görüntüye dönüştürün. Bu yöntemi görüntü işleme iş akışınıza dahil ederek segmentasyon ve özellik <br/>            çıkarma görevlerini kolaylaştırın, uygulamanızdaki görüntü analizinin doğruluğunu ve verimliliğini artırın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| eşik | System.Byte | Eşik değeri. Bir pikselin ilgili gri değeri eşikten büyükse, ona <br/>            255 değeri atanır, aksi takdirde 0. |


**See also:**

**[Example # 1](#example_122)**: The following example binarizes a TIFF image with the predefined threshold. B...


### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_13}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_14}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_15}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_16}


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


### Method: can_load(stream)  [static] {#can_load_stream_17}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_18}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_19}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_20}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_21}


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


### Method: can_save(options) {#can_save_options_22}


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


### Method: create(files)  [static] {#create_files_23}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_24}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_25}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_26}


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


### Method: create(images)  [static] {#create_images_27}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_28}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_29}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_30}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_31}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_32}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_33}


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


### Method: create_with_frame(frame)  [static] {#create_with_frame_frame_34}


```
 create_with_frame(frame) 
```

Yeni bir örnek başlatır [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) sınıfını.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Görüntüyü başlatmak için kullanılacak tiff çerçevesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) |  |


### Method: create_with_frames(frames)  [static] {#create_with_frames_frames_35}


```
 create_with_frames(frames) 
```

Yeni bir örnek başlatır [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) sınıfını.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Çerçeveler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_36}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Görüntüyü, sol, sağ, üst ve <br/>            alt yönlerde kaydırmalar belirterek kırpın. Bu yöntem, görüntünün istenen kısmını hassas bir şekilde seçmenizi sağlar, istenmeyen alanların etkili bir şekilde kaldırılmasını ve temel içeriğe odaklanılmasını kolaylaştırır. Bu işlevi görüntü işleme <br/>            hattınıza entegre ederek uygulamanızda gerektiği gibi netlik ve kompozisyonu artırın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| left_shift | int | Sol kaydırma. |
| right_shift | int | Sağ kaydırma. |
| top_shift | int | Üst kaydırma. |
| bottom_shift | int | Alt kaydırma. |


**See also:**

**[Example # 1](#example_121)**: The following example crops a TIFF image. The cropping area is specified via ...


### Method: crop(rectangle) {#crop_rectangle_37}


```
 crop(rectangle) 
```

Belirtilen dikdörtgen bölgeyi kullanarak görüntüyü kırpın, böylece istenen içeriği hassas bir şekilde seçebilirsiniz. Bu yöntemi görüntü işleme iş akışınıza entegre ederek istenmeyen alanları etkili bir şekilde kaldırın ve temel detaylara odaklanın, görüntünün genel netliğini ve kompozisyonunu artırın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dikdörtgen. |


**See also:**

**[Example # 1](#example_120)**: The following example crops a TIFF image. The cropping area is be specified v...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_38}


```
 dither(dithering_method, bits_count) 
```

Mevcut görüntüde dithering uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithering yöntemi. |
| bits_count | int | Dithering için son bit sayısı. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_39}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Mevcut görüntüde dithering uygulayarak görsel kalitesini artırın ve renk bantlama artefaktlarını azaltın. Bu yöntemi görüntü işleme iş akışınıza entegre ederek renk geçişlerini daha yumuşak hale getirin, böylece genel görüntü görünümü ve netliği iyileşsin.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithering yöntemi. |
| bits_count | int | Dithering için son bit sayısı. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Dithering için özel palet. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_40}


```
 embed_digital_signature(password) 
```

Sağlanan şifreye dayalı dijital imzayı görüntünün her sayfasına yerleştirin.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| parola | string | Dijital imza verisi oluşturmak için kullanılan şifre |

### Method: filter(rectangle, options) {#filter_rectangle_options_41}


```
 filter(rectangle, options) 
```

Belirtilen dikdörtgen içindeki içeriği filtreleyin, seçilen bölgeyi geliştirmek veya değiştirmek için belirlenmiş bir görüntü <br/>            işleme filtresi uygulayın. Bu yöntemi görüntü manipülasyonu iş akışınıza entegre ederek hedeflenmiş iyileştirmeler veya <br/>            dönüşümler elde edin.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dikdörtgen. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Seçenekler. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_42}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_43}


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


### Method: get_default_options(args) {#get_default_options_args_44}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_45}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel alınacak dikdörtgen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Kısmi piksel yükleyici. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_46}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_47}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_48}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_49}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_50}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_51}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_52}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_53}


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


### Method: get_original_options() {#get_original_options__54}


```
 get_original_options() 
```

Orijinal dosya ayarlarından türetilen seçenekleri alın, böylece bit derinliği ve orijinal görüntünün diğer önemli özellikleri gibi temel parametrelerin sorunsuz <br/>            korunması sağlanır. Bu yöntemi görüntü işleme görevlerinde doğruluk ve tutarlılığı sürdürmek için kullanın, gereksiz değişiklikler olmadan optimum sonuçlar elde edin.<br/>            Örneğin, 1 bit/piksel siyah-beyaz bir PNG görüntüsü yükleyip ardından <br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilir.<br/>            Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) yöntemine ikinci parametre olarak geçirin.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Orijinal dosya ayarlarına dayalı seçenekler. |


### Method: get_pixel(x, y) {#get_pixel_x_y_55}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_56}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_57}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_58}


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


### Method: get_skew_angle() {#get_skew_angle__59}


```
 get_skew_angle() 
```

Eğim açısını alır.<br/>            Bu yöntem taranmış metin belgelerine uygulanabilir, tarama sırasında eğim açısını belirlemek için.

**Returns**

| Tür | Açıklama |
| :- | :- |
| float | Eğim açısı, derece cinsinden. |


### Method: insert_frame(index, frame) {#insert_frame_index_frame_60}


```
 insert_frame(index, frame) 
```

Yeni çerçeveyi çerçeve dizisinde belirtilen indekse ekleyin, böylece çerçeve düzeni üzerinde hassas kontrol sağlanır. Bu yöntemi çerçeve dizilerini etkili bir şekilde yönetmek, görüntü içeriğinin dinamik manipülasyonu ve organizasyonunu kolaylaştırmak için kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| index | int | _frame_ öğesinin indeksi. |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Ekleme için çerçeve. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_61}


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


### Method: load(file_path)  [static] {#load_file_path_62}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_63}


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


### Method: load(stream)  [static] {#load_stream_64}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_65}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_66}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_67}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_68}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_69}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32-bit ARGB piksellerini kısmen (bloklar halinde) yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksellerin yükleneceği dikdörtgen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Kısmi piksel yükleyici. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

64-bit ARGB piksellerini paketler halinde kısmen yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | İstenen dikdörtgen. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | 64-bit ARGB piksel yükleyicisi. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_72}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Pikselleri paketler halinde kısmen yükler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | İstenen dikdörtgen. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Piksel yükleyicisi. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_73}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_76}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_77}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_78}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_79}


```
 normalize_angle(resize_proportionally, background_color) 
```

Tarama metin belgeleri için özel olarak tasarlanmış NormalizeAngle yöntemini kullanarak eğik taramaları düzeltin, doğru hizalamayı sağlayın. Bu işlevi metin işleme iş akışlarınıza sorunsuz bir şekilde entegre ederek belge okunabilirliğini ve kalitesini artırın, metin tanıma ve analiz görevlerinde genel verimliliği iyileştirin.<br/>            Bu yöntem [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) ve [TiffImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) metodlarını kullanır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| resize_proportionally | bool | eğer <c>true</c> olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgene (köşe noktaları) göre projeksiyonlar doğrultusunda değişir; diğer durumda boyutlar aynı kalır ve yalnızca iç görüntü içeriği döndürülür. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Arka plan rengi. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_80}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_81}


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


### Method: remove_frame(frame) {#remove_frame_frame_82}


```
 remove_frame(frame) 
```

Belirtilen çerçeveyi görüntü dizisinden verimli bir şekilde kaldırın, uygulamanızda çerçeve yönetimini sadeleştirin. Bu işlevi entegre ederek çerçeve manipülasyonunda hassasiyet ve esnekliği artırın, görüntü içeriğinin sorunsuz organizasyonu ve sunumunu sağlayın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Kaldırılacak çerçeve. |

### Method: remove_frame(index) {#remove_frame_index_83}


```
 remove_frame(index) 
```

Çerçeveyi indeksine göre kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| index | int | Kaldırılacak çerçevenin indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Kaldırılan çerçeve. |


### Method: remove_frame_by_index(index) {#remove_frame_by_index_index_84}


```
 remove_frame_by_index(index) 
```

Çerçeveyi indeksine göre kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| index | int | Kaldırılacak çerçevenin indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Kaldırılan çerçeve. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_85}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_86}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_87}


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

### Method: replace_frame(index, new_frame) {#replace_frame_index_new_frame_88}


```
 replace_frame(index, new_frame) 
```

Belirtilen konumdaki çerçeveyi başka bir çerçeve ile sorunsuz bir şekilde değiştirin, <br/>            görüntü dizisinde dinamik çerçeve yönetimini kolaylaştırın. Bu yöntemi entegre ederek çerçeve manipülasyonunda esneklik ve hassasiyeti artırın, uygulamanızda görüntü içeriğinin optimal organizasyonu ve sunumunu sağlayın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| index | int | Sıfır tabanlı çerçeve konumu. |
| new_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Belirtilen _index_ konumundaki çerçeveyi değiştirecek çerçeve. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Kaldırılan çerçeve. |


### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_89}


```
 replace_non_transparent_colors(new_color) 
```

Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.<br/>                Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_90}


```
 replace_non_transparent_colors(new_color_argb) 
```

Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak pürüzsüz kenarları korur.<br/>                Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_color_argb | int | Şeffaf olmayan renkleri değiştirmek için yeni renk ARGB değeri. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_91}


```
 resize(new_width, new_height) 
```

Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_92}


```
 resize(new_width, new_height, resize_type) 
```

Görüntü üzerinde oranlı yeniden boyutlandırma işlemi yapın, boyutlarını ayarlarken en-boy oranını koruyun. Bu yöntemi uygulamanızda görüntüleri dinamik olarak ölçeklendirmek için kullanın, içeriğin tutarlılığını görsel olarak tutarlı bir şekilde temsil edin.<br/>            Oranlı yeniden boyutlandırma, her çerçeveyi _newWidth_/width ve _newHeight_/height oranına göre yeniden boyutlandıracaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırma türü. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_93}


```
 resize(new_width, new_height, settings) 
```

Görüntünün boyutunu belirtilen ayarlara göre ayarlayın, böylece boyutlar, en-boy oranı ve ölçekleme davranışı üzerinde hassas kontrol sağlanır. Bu yöntemi görüntü işleme iş akışınıza entegre ederek uygulamanızın özel gereksinimlerine göre özelleştirilmiş yeniden boyutlandırma işlemleri gerçekleştirin.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Yeniden boyutlandırma ayarları. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_94}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_95}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_96}


```
 resize_height_proportionally(new_height) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_97}


```
 resize_height_proportionally(new_height, resize_type) 
```

Görüntünün yüksekliğini oranlı olarak ayarlayın, en-boy oranını koruyarak tutarlı görsel bütünlük sağlayın. Bu yöntemi uygulamanızda görüntüleri dinamik olarak yeniden boyutlandırmak için kullanın, çeşitli platformlar ve cihazlar arasında içerik kalitesinden ödün vermeden optimal görüntüleme sağlayın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırmanın türü. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_98}


```
 resize_height_proportionally(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_99}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_100}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Görüntü üzerinde oranlı yeniden boyutlandırma işlemi yapın, boyutlarını ayarlarken en-boy oranını koruyun. Bu yöntemi uygulamanızda görüntüleri dinamik olarak ölçeklendirmek için kullanın, içeriğin tutarlılığını görsel olarak tutarlı bir şekilde temsil edin.<br/>            Oranlı yeniden boyutlandırma, her çerçeveyi _newWidth_/width ve _newHeight_/height oranına göre yeniden boyutlandıracaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırma türü. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_101}


```
 resize_width_proportionally(new_width) 
```

Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_102}


```
 resize_width_proportionally(new_width, resize_type) 
```

Görüntünün genişliğini, en-boy oranını koruyarak ayarlayın, böylece optimal görsel sunum için oranlı yeniden boyutlandırma sağlanır. Bu yöntemi uygulamanızda görüntüleri dinamik olarak ölçeklendirmek için kullanın, çeşitli görüntüleme bağlamlarında tutarlı ve estetik açıdan hoş bir render elde edin.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırmanın türü. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_103}


```
 resize_width_proportionally(new_width, settings) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_104}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: rotate(angle) {#rotate_angle_105}


```
 rotate(angle) 
```

Görüntüyü merkezin etrafında döndür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_106}


```
 rotate(angle, resize_proportionally, background_color) 
```

Görüntüyü, merkez noktasının etrafında belirtilen bir açıyla döndürün, böylece hassas yönlendirme ayarlamaları mümkün olur. Bu işlevi görüntü işleme hattınıza entegre ederek doğru dönüşümleri kolaylaştırın, uygulamanızda görsel içeriğin optimal hizalanmasını ve sunumunu sağlayın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |
| resize_proportionally | bool | eğer <c>true</c> olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgene (köşe noktaları) göre projeksiyonlar doğrultusunda değişir; diğer durumda boyutlar aynı kalır ve yalnızca iç görüntü içeriği döndürülür. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Arka plan rengi. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_107}


```
 rotate_flip(rotate_flip_type) 
```

Yalnızca aktif çerçeve üzerinde döndürme, çevirme veya her ikisinin bir kombinasyonunu gerçekleştirin. Bu yöntem, görüntü dizisindeki tek tek çerçevelerin hassas manipülasyonunu sağlar, uygulamanızda görüntü düzenleme ve kompozisyon esnekliğini artırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Döndürme çevirme türü. |


**See also:**

**[Example # 1](#example_118)**: This example loads a TIFF image, rotates it by 90 degrees clockwise and optio...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_108}


```
 rotate_flip_all(rotate_flip) 
```

Tüm çevirme işlemlerini döndürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Döndürme çevirme. |

### Method: save(file_path) {#save_file_path_109}


```
 save(file_path) 
```

Görüntüyü belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Görüntünün kaydedileceği dosya yolu. |

### Method: save(file_path, options) {#save_file_path_options_110}


```
 save(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_111}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_112}


```
 save(file_path, over_write) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verilerinin kaydedileceği dosya yolu. |
| over_write | bool | Eğer <c>true</c> olarak ayarlanırsa dosya içeriği üzerine yazılır, aksi takdirde ekleme yapılır. |

### Method: save(stream) {#save_stream_113}


```
 save(stream) 
```

Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Nesnenin verisinin kaydedileceği akış. |

### Method: save(stream, options_base) {#save_stream_options_base_114}


```
 save(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_115}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_116}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32-bit ARGB piksellerini kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| piksel | int[] | 32 bitlik ARGB piksel dizisi. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_117}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Pikselleri kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| piksel | int[] | 32 bitlik tam sayı değerleri olarak sunulan CMYK pikseller. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_118}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Pikselleri kaydeder.<br/>            Bu yöntem artık kullanılmamaktadır. Lütfen daha etkili olan [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) yöntemini kullanın.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Piksel kaydedilecek dikdörtgen. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK piksel dizisi. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_119}


```
 save_pixels(rectangle, pixels) 
```

Piksel verilerini dahili olarak kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dikdörtgen. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Pikseller. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_120}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_121}


```
 save_to_stream(stream) 
```

Görüntüyü akışa kaydeder

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom |  |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_122}


```
 save_to_stream_with_options(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_123}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_124}


```
 save_with_options(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_125}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_126}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_127}


```
 set_palette(palette, update_colors) 
```

Görüntü paletini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Ayarlanacak palet. |
| update_colors | bool | eğer <c>true</c> olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri yoksa, görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_128}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_129}


```
 set_resolution(dpi_x, dpi_y) 
```

Belirtilen [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) için çözünürlüğü ayarlar, <br/>            görüntü işleme ve gösterim özellikleri üzerinde hassas kontrol sağlar. Bu <br/>            işlevi bütünleştirerek görsel çıktıyı optimize edin ve çeşitli <br/>            çıktı cihazları ve platformlarıyla uyumluluğu sağlayın, genel kullanıcı deneyimini artırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dpi_x | float | Yatay çözünürlük, inç başına nokta (dpi) cinsinden, [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) öğesinin. |
| dpi_y | float | Dikey çözünürlük, inç başına nokta (dpi) cinsinden, [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) öğesinin. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_130}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_131}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Tüm tarama satırını belirtilen tarama satırı indeksine yazar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int | Tarama satırının sıfır tabanlı indeksi. |
| argb_32_pixels | int[] | Yazılacak 32-bit ARGB renk dizisi. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_132}


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
### This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_118}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# Döndür, çevir ve çıktı dosyasına kaydet.
	with aspycore.as_of(Image.load(join(dir_, "sample.tif")), TiffImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example loads a TIFF image and prints information about raw data format and alpha channel. {#example_119}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from os.path import join as path_join


dir_ = "c:\\temp"
file_name = path_join(dir_, "sample.tif")
with Image.load(file_name) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Aktif TIFF çerçevesi alfa kanalı içeriyorsa, tüm TIFF görüntüsü alfa kanalı içeriyormuş gibi kabul edilir.
	print("ImageFile={0}, FileFormat={1}, HasAlpha={2}".format(file_name, tiff_image.raw_data_format, tiff_image.has_alpha))
	i = 1
	for frame in tiff_image.frames:
		print("Frame={0}, FileFormat={1}, HasAlpha={2}".format(i, frame.raw_data_format, frame.has_alpha))
		i += 1

# Çıktı şu şekilde görünebilir:
# ImageFile=c:\\temp\\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
# Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
# Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False


```

### The following example crops a TIFF image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_120}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.tiff import TiffImage
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Görüntüyü kırp. Kırpma alanı, görüntünün dikdörtgen merkez bölgesidir.
	area = Rectangle(tiff_image.width // 4, tiff_image.height // 4, tiff_image.width // 2,
					 tiff_image.height // 2)
	tiff_image.crop(area)
	# Kırpılmış görüntüyü PNG olarak kaydet.
	tiff_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example crops a TIFF image. The cropping area is specified via Left, Top, Right, Bottom margins. {#example_121}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image       
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = r"c:\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Tekrar kırpın. Görüntü boyutunun %10'u kadar bir kenar boşluğu ayarlayın.
	horizontal_margin: int = tiff_image.width // 10
	vertical_margin: int = tiff_image.height // 10
	tiff_image.crop(horizontal_margin, horizontal_margin, vertical_margin, vertical_margin)
	# Kırpılmış görüntüyü PNG olarak kaydedin.
	tiff_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example binarizes a TIFF image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_122}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Görüntüyü 127 eşik değeriyle ikilileştirin.
	# Bir pikselin karşılık gelen gri değeri 127'den büyükse, ona 255 değeri atanır, aksi takdirde 0 atanır.
	tiff_image.binarize_fixed(127)
	tiff_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_124}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Görüntüyü 5 parlaklık farkı ile ikilileştirin. Parlaklık, bir piksel ile bu pikselin etrafındaki 10 x 10 piksellik pencerenin ortalaması arasındaki farktır.
	tiff_image.binarize_bradley(5, 10)
	tiff_image.save(join(dir_, "sample.BinarizeBradley5_10x10.png"), PngOptions())


```

### The following example performs gamma-correction of a TIFF image. {#example_126}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Kırmızı, yeşil ve mavi kanallar için gama katsayısını ayarlayın.
	tiff_image.adjust_gamma(2.5)
	tiff_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a TIFF image applying different coefficients for color components. {#example_127}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Kırmızı, yeşil ve mavi kanallar için ayrı ayrı gama katsayılarını ayarlayın.
	tiff_image.adjust_gamma(1.5, 2.5, 3.5)
	tiff_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a TIFF image. {#example_128}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Parlaklık değerini ayarlayın. Kabul edilen parlaklık değerleri [-255, 255] aralığındadır.
	tiff_image.adjust_brightness(50)
	tiff_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a TIFF image. {#example_129}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Kontrast değerini ayarlayın. Kabul edilen kontrast değerleri [-100f, 100f] aralığındadır.
	tiff_image.adjust_contrast(50.0)
	tiff_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())


```

### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# TIFF görüntüsünden PathResources kullanarak GraphicsPath oluştur.
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Kırmızı çizgi çiz ve resmi kaydet
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

