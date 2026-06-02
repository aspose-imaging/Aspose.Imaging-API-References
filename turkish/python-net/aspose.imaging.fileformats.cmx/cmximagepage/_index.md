---
title: "CmxImagePage Sınıfı"
type: docs
weight: 110
url: /tr/python-net/aspose.imaging.fileformats.cmx/cmximagepage/
---

**Summary:** The image of CMX page

**Module:** [aspose.imaging.fileformats.cmx](/imaging/python-net/aspose.imaging.fileformats.cmx/)

**Full Name:** aspose.imaging.fileformats.cmx.CmxImagePage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IObjectWithSizeF, ICmxImage, VectorImage

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CmxImagePage(cmx_page)](#CmxImagePage_cmx_page_1) | Yeni bir [CmxImagePage](/imaging/python-net/aspose.imaging.fileformats.cmx/cmximagepage/) sınıfı örneği başlatır. |
| [CmxImagePage(cmx_page, container)](#CmxImagePage_cmx_page_container_2) | Yeni bir [CmxImagePage](/imaging/python-net/aspose.imaging.fileformats.cmx/cmximagepage/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Arka plan renginin değerini alır veya ayarlar. |
| bits_per_pixel | int | r | Görselin piksel başına bit sayısını alır. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Nesnenin sınırlarını alır. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| cmx_page | [CmxPage](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxpage/) | r | CMX sayfasını alır. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Bu [Image](/imaging/python-net/aspose.imaging/image/) kapsayıcısını alır. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Nesnenin veri akışını alır. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif örneğini alır veya ayarlar. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Dosya formatının bir değerini alır |
| has_background_color | bool | r/w | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| height | int | r | Görüntünün yüksekliğini alır. |
| height_f | float | r | Nesnenin yüksekliğini inç cinsinden alır. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Kesinti izleyicisini alır veya ayarlar. |
| is_cached | bool | r | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değer alır. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Görüntünün meta verilerini alır. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Nesne boyutunu alır. |
| size_f | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Nesnenin boyutunu inç cinsinden alır. |
| use_palette | bool | r | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| width | int | r | Görüntünün genişliğini alır. |
| width_f | float | r | Nesnenin genişliğini inç cinsinden alır. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Xmp verilerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| cache_data() | Önbellek kullanılamaz. |
| [can_load(file_path)](#can_load_file_path_1) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler. |
| [can_load(stream)](#can_load_stream_3) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen _loadOptions_ kullanılarak belirler. |
| [can_load_stream(stream)](#can_load_stream_stream_5) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_6) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen _loadOptions_ kullanılarak belirler. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_7) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler. |
| [can_save(options)](#can_save_options_8) | Geçilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına görüntünün kaydedilip kaydedilemeyeceğini belirler. |
| [create(files)](#create_files_9) | Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_10) | Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur. |
| [create(image_options, width, height)](#create_image_options_width_height_11) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_12) | Sağlanan piksel dizisinden bir [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) örneği oluşturur.<br/>            <br/>            Belirtilen genişlik ve yüksekliğin piksel verisinin boyutlarıyla eşleştiğini doğrular.<br/>            Bu yöntem yalnızca kütüphane Lisanslı modda olduğunda kullanılabilir. |
| [create(images)](#create_images_13) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create(images, dispose_images)](#create_images_dispose_images_14) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create(multipage_create_options)](#create_multipage_create_options_15) | Belirtilen çok sayfalı oluşturma seçeneklerini oluşturur. |
| [create_from_files(files)](#create_from_files_files_16) | Belirtilen dosyaları tembel yükleme sayfaları olarak içeren çok sayfalı bir görüntü oluşturur. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_17) | Belirtilen dosyaları tembel yükleme sayfaları olarak içeren çok sayfalı bir görüntü oluşturur. |
| [create_from_images(images)](#create_from_images_images_18) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_19) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_20) | Kaydırmalarla görüntüyü kırp. |
| [crop(rectangle)](#crop_rectangle_21) | Belirtilen dikdörtgeni kırpar. |
| [get_default_options(args)](#get_default_options_args_22) | Varsayılan seçenekleri alır. |
| [get_embedded_images()](#get_embedded_images__23) | Gömülü görüntüleri alır. |
| [get_file_format(file_path)](#get_file_format_file_path_24) | Dosya biçimini alır. |
| [get_file_format(stream)](#get_file_format_stream_25) | Dosya biçimini alır. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_26) | Dosya biçimini alır. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Mevcut görüntüyü saran dikdörtgeni alır. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Mevcut görüntüyü saran dikdörtgeni alır. |
| [get_original_options()](#get_original_options__29) | Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirilmemiş tutmak için faydalı olabilir.<br/>            Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yüklerseniz ve ardından bunu kullanarak<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) yöntemiyle, 8-bit piksel başına sahip bir çıktı PNG görüntüsü üretilecektir.<br/>            Bunu önlemek ve 1-bit piksel başına PNG görüntüsü kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) yöntemine ikinci parametre olarak geçirin. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_30) | Orantılı bir yükseklik alır. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_31) | Orantılı bir genişlik alır. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_32) | aps'ye dönüştürür. |
| [load(file_path)](#load_file_path_33) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| [load(file_path, load_options)](#load_file_path_load_options_34) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| [load(stream)](#load_stream_35) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(stream, load_options)](#load_stream_load_options_36) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_stream(stream)](#load_stream_stream_37) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_38) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_39) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| remove_background() | Arka planı kaldırır. |
| [remove_background(settings)](#remove_background_settings_40) | Arka planı kaldırır. |
| remove_metadata() | Meta verileri kaldırır. |
| [resize(new_width, new_height)](#resize_new_width_new_height_41) | Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_42) | Belirtilen yeni genişliği yeniden boyutlandırır. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_43) | Genişletilmiş seçeneklerle görüntüyü yeniden boyutlandırır. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_44) | Görüntüyü yeniden boyutlandırır. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_45) | Görüntüyü yeniden boyutlandırır. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_46) | Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_47) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_48) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_49) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_50) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_51) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_52) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_53) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [rotate(angle)](#rotate_angle_54) | Görüntüyü merkezin etrafında döndür. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_55) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| save() | Görüntü verilerini temel akıma kaydeder. |
| [save(file_path)](#save_file_path_56) | Görüntüyü belirtilen dosya konumuna kaydeder. |
| [save(file_path, options)](#save_file_path_options_57) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_58) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save(file_path, over_write)](#save_file_path_over_write_59) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(stream)](#save_stream_60) | Verileri kaydeder. |
| [save(stream, options_base)](#save_stream_options_base_61) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_62) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_to_stream(stream)](#save_to_stream_stream_63) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_64) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_65) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_66) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_67) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_68) | Görüntü paletini ayarlar. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_69) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |


### Constructor: CmxImagePage(cmx_page) {#CmxImagePage_cmx_page_1}


```
 CmxImagePage(cmx_page) 
```

Yeni bir [CmxImagePage](/imaging/python-net/aspose.imaging.fileformats.cmx/cmximagepage/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmx_page | [CmxPage](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxpage/) | CMX sayfası. |

### Constructor: CmxImagePage(cmx_page, container) {#CmxImagePage_cmx_page_container_2}


```
 CmxImagePage(cmx_page, container) 
```

Yeni bir [CmxImagePage](/imaging/python-net/aspose.imaging.fileformats.cmx/cmximagepage/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| cmx_page | [CmxPage](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxpage/) | CMX sayfası. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | Kapsayıcı. |

### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_5}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_6}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_7}


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


### Method: can_save(options) {#can_save_options_8}


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


### Method: create(files)  [static] {#create_files_9}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_10}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_11}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_12}


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


### Method: create(images)  [static] {#create_images_13}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_14}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_15}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_16}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_17}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_18}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_19}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_20}


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

### Method: crop(rectangle) {#crop_rectangle_21}


```
 crop(rectangle) 
```

Belirtilen dikdörtgeni kırpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dikdörtgen. |

### Method: get_default_options(args) {#get_default_options_args_22}


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


### Method: get_embedded_images() {#get_embedded_images__23}


```
 get_embedded_images() 
```

Gömülü görüntüleri alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [EmbeddedImage[]](/imaging/python-net/aspose.imaging/embeddedimage/) | Görüntü dizisi |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_24}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_25}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_original_options() {#get_original_options__29}


```
 get_original_options() 
```

Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirilmemiş tutmak için faydalı olabilir.<br/>            Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yüklerseniz ve ardından bunu kullanarak<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) yöntemiyle, 8-bit piksel başına sahip bir çıktı PNG görüntüsü üretilecektir.<br/>            Bunu önlemek ve 1-bit piksel başına PNG görüntüsü kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) yöntemine ikinci parametre olarak geçirin.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Orijinal dosya ayarlarına dayalı seçenekler. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_30}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_31}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_32}


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


### Method: load(file_path)  [static] {#load_file_path_33}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_34}


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


### Method: load(stream)  [static] {#load_stream_35}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_36}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_37}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_38}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_39}


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


### Method: remove_background(settings) {#remove_background_settings_40}


```
 remove_background(settings) 
```

Arka planı kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| settings | [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Ayarlar. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_41}


```
 resize(new_width, new_height) 
```

Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_42}


```
 resize(new_width, new_height, resize_type) 
```

Belirtilen yeni genişliği yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırmanın türü. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_43}


```
 resize(new_width, new_height, settings) 
```

Genişletilmiş seçeneklerle görüntüyü yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Yeniden boyutlandırma ayarları. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_44}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_45}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_46}


```
 resize_height_proportionally(new_height) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_47}


```
 resize_height_proportionally(new_height, resize_type) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırmanın türü. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_48}


```
 resize_height_proportionally(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_49}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_50}


```
 resize_width_proportionally(new_width) 
```

Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_51}


```
 resize_width_proportionally(new_width, resize_type) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırmanın türü. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_52}


```
 resize_width_proportionally(new_width, settings) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_53}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: rotate(angle) {#rotate_angle_54}


```
 rotate(angle) 
```

Görüntüyü merkezin etrafında döndür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_55}


```
 rotate_flip(rotate_flip_type) 
```

Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | rotate flip'in türü. |

### Method: save(file_path) {#save_file_path_56}


```
 save(file_path) 
```

Görüntüyü belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Görüntünün kaydedileceği dosya yolu. |

### Method: save(file_path, options) {#save_file_path_options_57}


```
 save(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_58}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_59}


```
 save(file_path, over_write) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verilerinin kaydedileceği dosya yolu. |
| over_write | bool | Eğer <c>true</c> olarak ayarlanırsa dosya içeriği üzerine yazılır, aksi takdirde ekleme yapılır. |

### Method: save(stream) {#save_stream_60}


```
 save(stream) 
```

Verileri kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Verinin kaydedileceği akış. |

### Method: save(stream, options_base) {#save_stream_options_base_61}


```
 save(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_62}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_63}


```
 save_to_stream(stream) 
```

Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Nesnenin verisinin kaydedileceği akış. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_64}


```
 save_to_stream_with_options(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_65}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_66}


```
 save_with_options(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_67}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_68}


```
 set_palette(palette, update_colors) 
```

Görüntü paletini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Ayarlanacak palet. |
| update_colors | bool | eğer <c>true</c> olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri yoksa, görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_69}


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


