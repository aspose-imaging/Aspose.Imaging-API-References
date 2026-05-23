---
title: "Image Sınıfı"
type: docs
weight: 5650
url: /tr/python-net/aspose.imaging/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Image

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, DataStreamSupporter

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Arka plan renginin değerini alır veya ayarlar. |
| bits_per_pixel | int | r | Görselin piksel başına bit sayısını alır. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Görüntünün sınırlarını alır. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Bu [Image](/imaging/python-net/aspose.imaging/image/) kapsayıcısını alır. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Nesnenin veri akışını alır. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif verilerini alır veya ayarlar. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Dosya formatının bir değerini alır |
| has_background_color | bool | r/w | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| height | int | r | Görüntünün yüksekliğini alır. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Kesinti izleyicisini alır veya ayarlar. |
| is_cached | bool | r | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değer alır. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Görüntünün meta verilerini alır. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Görüntünün boyutunu alır. |
| [use_palette](#use_palette1) | bool | r | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| width | int | r | Görüntünün genişliğini alır. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Xmp verilerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| cache_data() | Verileri önbelleğe alır ve temel [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
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
| [get_file_format(file_path)](#get_file_format_file_path_23) | Dosya biçimini alır. |
| [get_file_format(stream)](#get_file_format_stream_24) | Dosya biçimini alır. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_25) | Dosya biçimini alır. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_26) | Mevcut görüntüyü saran dikdörtgeni alır. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_27) | Mevcut görüntüyü saran dikdörtgeni alır. |
| [get_original_options()](#get_original_options__28) | Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirilmemiş tutmak için faydalı olabilir.<br/>            Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yüklerseniz ve ardından bunu kullanarak<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) yöntemiyle, 8-bit piksel başına sahip bir çıktı PNG görüntüsü üretilecektir.<br/>            Bunu önlemek ve 1-bit piksel başına PNG görüntüsü kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) yöntemine ikinci parametre olarak geçirin. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_29) | Orantılı bir yükseklik alır. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_30) | Orantılı bir genişlik alır. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_31) | aps'ye dönüştürür. |
| [load(file_path)](#load_file_path_32) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| [load(file_path, load_options)](#load_file_path_load_options_33) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| [load(stream)](#load_stream_34) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(stream, load_options)](#load_stream_load_options_35) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_stream(stream)](#load_stream_stream_36) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_37) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_38) | Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler.<br/>            _filePath_ bir dosya yolu ise yöntem sadece dosyayı açar.<br/>            _filePath_ bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak saklar ve açar. |
| remove_metadata() | Meta verileri kaldırır. |
| [resize(new_width, new_height)](#resize_new_width_new_height_39) | Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_40) | Görüntüyü yeniden boyutlandırır. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_41) | Görüntüyü yeniden boyutlandırır. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_42) | Görüntüyü yeniden boyutlandırır. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_43) | Görüntüyü yeniden boyutlandırır. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_44) | Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_45) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_46) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_47) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_48) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_49) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_50) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_51) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [rotate(angle)](#rotate_angle_52) | Görüntüyü merkezin etrafında döndür. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_53) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| save() | Görüntü verilerini temel akıma kaydeder. |
| [save(file_path)](#save_file_path_54) | Görüntüyü belirtilen dosya konumuna kaydeder. |
| [save(file_path, options)](#save_file_path_options_55) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_56) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save(file_path, over_write)](#save_file_path_over_write_57) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(stream)](#save_stream_58) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save(stream, options_base)](#save_stream_options_base_59) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_60) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_to_stream(stream)](#save_to_stream_stream_61) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_62) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_63) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_64) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_65) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_66) | Görüntü paletini ayarlar. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_67) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) türünü destekliyor ve uyguluyorsa bir _metadata_ örneği ayarlamayı dener. |


### Property: use_palette {#use_palette1}

Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır.

**See also:**

**[Example # 1](#example_221)**: Determine if the palette is used by the image.


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



**See also:**

**[Example # 1](#example_22)**: This example determines whether image can be loaded from a file.


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



**See also:**

**[Example # 1](#example_23)**: This example determines whether image can be loaded from a file stream.


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



**See also:**

**[Example # 1](#example_26)**: This example shows how to determine whether image can be saved to the specifi...


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



**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_23}


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



**See also:**

**[Example # 1](#example_24)**: This example shows how to determine the image format without loading the enti...


### Method: get_file_format(stream)  [static] {#get_file_format_stream_24}


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



**See also:**

**[Example # 1](#example_25)**: This example shows how to determine the image format without loading the enti...


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_25}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_26}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_27}


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


### Method: get_original_options() {#get_original_options__28}


```
 get_original_options() 
```

Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirilmemiş tutmak için faydalı olabilir.<br/>            Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yüklerseniz ve ardından bunu kullanarak<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) yöntemiyle, 8-bit piksel başına sahip bir çıktı PNG görüntüsü üretilecektir.<br/>            Bunu önlemek ve 1-bit piksel başına PNG görüntüsü kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) yöntemine ikinci parametre olarak geçirin.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Orijinal dosya ayarlarına dayalı seçenekler. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_29}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_30}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_31}


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


### Method: load(file_path)  [static] {#load_file_path_32}


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



**See also:**

**[Example # 1](#example_1)**: This example demonstrates the loading of an existing Image file into an insta...


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_33}


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


### Method: load(stream)  [static] {#load_stream_34}


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



**See also:**

**[Example # 1](#example_6)**: This example demonstrates the use of a file stream objects to load an existin...


### Method: load(stream, load_options)  [static] {#load_stream_load_options_35}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_36}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_37}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_38}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_39}


```
 resize(new_width, new_height) 
```

Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |


**See also:**

**[Example # 1](#example_182)**: The following example shows how to resize a metafile (WMF and EMF).

**[Example # 2](#example_185)**: The following example shows how to resize SVG image and save it to PNG.


### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_40}


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


**See also:**

**[Example # 1](#example_209)**: Resize image using specific Resize Type.


### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_41}


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


**See also:**

**[Example # 1](#example_28)**: This example loads an image and resizes it using various resizing settings.

**[Example # 2](#example_209)**: Resize image using specific Resize Type.


### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_42}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_43}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_44}


```
 resize_height_proportionally(new_height) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_45}


```
 resize_height_proportionally(new_height, resize_type) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırmanın türü. |


**See also:**

**[Example # 1](#example_30)**: This example loads an image and resizes it proportionally using various resiz...


### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_46}


```
 resize_height_proportionally(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_47}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_48}


```
 resize_width_proportionally(new_width) 
```

Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_49}


```
 resize_width_proportionally(new_width, resize_type) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Yeniden boyutlandırmanın türü. |


**See also:**

**[Example # 1](#example_29)**: This example loads an image and resizes it proportionally using various resiz...


### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_50}


```
 resize_width_proportionally(new_width, settings) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_51}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Görüntü yeniden boyutlandırma ayarları. |

### Method: rotate(angle) {#rotate_angle_52}


```
 rotate(angle) 
```

Görüntüyü merkezin etrafında döndür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_53}


```
 rotate_flip(rotate_flip_type) 
```

Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | rotate flip'in türü. |


**See also:**

**[Example # 1](#example_8)**: This example demonstrates the use of Rotate operation on an image. Example lo...

**[Example # 2](#example_31)**: This example loads an image, rotates it by 90 degrees clockwise and optionall...


### Method: save(file_path) {#save_file_path_54}


```
 save(file_path) 
```

Görüntüyü belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Görüntünün kaydedileceği dosya yolu. |

### Method: save(file_path, options) {#save_file_path_options_55}


```
 save(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |


**See also:**

**[Example # 1](#example_9)**: This example shows the simple steps to save an Image. To demonstrate this ope...

**[Example # 2](#example_32)**: The following example loads a BMP image from a file, then saves the image to ...

**[Example # 3](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_56}


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


**See also:**

**[Example # 1](#example_33)**: The following example loads a BMP image from a file, then saves a rectangular...

**[Example # 2](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(file_path, over_write) {#save_file_path_over_write_57}


```
 save(file_path, over_write) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verilerinin kaydedileceği dosya yolu. |
| over_write | bool | Eğer <c>true</c> olarak ayarlanırsa dosya içeriği üzerine yazılır, aksi takdirde ekleme yapılır. |

### Method: save(stream) {#save_stream_58}


```
 save(stream) 
```

Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Nesnenin verisinin kaydedileceği akış. |

### Method: save(stream, options_base) {#save_stream_options_base_59}


```
 save(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |


**See also:**

**[Example # 1](#example_10)**: This example shows the process of saving an Image to MemoryStream. To demonst...

**[Example # 2](#example_34)**: The following example loads an image from a file, then saves the image to a P...

**[Example # 3](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_60}


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


**See also:**

**[Example # 1](#example_35)**: The following example loads an image from a file, then saves a rectangular pa...

**[Example # 2](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save_to_stream(stream) {#save_to_stream_stream_61}


```
 save_to_stream(stream) 
```

Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Nesnenin verisinin kaydedileceği akış. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_62}


```
 save_to_stream_with_options(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen akışa ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Kaydetme seçenekleri. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_63}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_64}


```
 save_with_options(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya konumunda ve belirtilen dosya formatında kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Seçenekler. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_65}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_66}


```
 set_palette(palette, update_colors) 
```

Görüntü paletini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Ayarlanacak palet. |
| update_colors | bool | eğer <c>true</c> olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri yoksa, görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_67}


```
 try_set_metadata(metadata) 
```

Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) türünü destekliyor ve uyguluyorsa bir _metadata_ örneği ayarlamayı dener.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Meta veriler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Doğru, eğer [Image](/imaging/python-net/aspose.imaging/image/) örneği [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) türünü destekliyor ve uyguluyorsa; aksi takdirde, yanlış. |


## **Examples**
### This example demonstrates the loading of an existing Image file into an instance of aspose.imaging.Image using file path specified {#example_1}
``` python

from aspose.imaging import Image
# Image örneği oluştur ve diskteki mevcut bir görüntü dosyasıyla başlat.
with Image.load(r"C:\temp\sample.bmp") as image:
	# bazı görüntü işleme yap
	pass


```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#`BmpOptions` bir örnek oluştur ve çeşitli özelliklerini ayarla
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#`FileCreateSource` bir örnek oluştur ve `BmpOptions` örneği için `source` olarak ata
	#İkinci `Boolean` parametre, oluşturulacak dosyanın geçici olup olmadığını belirler
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Image bir örnek oluştur ve Create metodunu çağırarak BmpOptions örneğiyle başlat
	with Image.create(bmp_options, 500, 500) as image:
		#bazı görüntü işleme yap
		# tüm değişiklikleri kaydet
		image.save()


```

### This example demonstrates the use of a file stream objects to load an existing Image file {#example_6}
``` python

from aspose.imaging import Image

# FileStream bir örnek oluştur
with open(r"C:\temp\sample.bmp", "rb"):
	#Image sınıfının bir örneğini oluştur ve Load metodunu çağırarak FileStream nesnesiyle mevcut bir dosyayı yükle
	with Image.load(stream) as image:
		#bazı görüntü işleme yapın.
		pass

```

### This example demonstrates the use of Rotate operation on an image. Example loads an existing image file from some disk location and performs the `Rotate` operation on the image according to the value of enumeration `aspose.imaging.RotateFlipType` {#example_8}
``` python

from aspose.imaging import Image, RotateFlipType
#Image sınıfının bir örneğini oluşturun ve mevcut bir görüntü dosyasını Dosya yolu aracılığıyla başlatın
with Image.load(r"C:\temp\sample.bmp") as image:
	# görüntüyü X ekseni etrafında 180 derece döndürün
	image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
	# Tüm değişiklikleri kaydedin.
	image.save()


```

### This example shows the simple steps to save an Image. To demonstrate this operation, we load an existing file from some disk location, performs `rotate` operation on the image and save the image in PSD format using file path {#example_9}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from os.path import join as path_join

directory = "c:\\temp"

#Image sınıfının bir örneğini oluşturun ve mevcut bir dosyayı Dosya yolu aracılığıyla başlatın
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Görüntüyü X ekseni etrafında 180 derece döndürün
	image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
	#Görüntüyü PSD olarak Dosya Yolu'na varsayılan PsdOptions ayarlarıyla kaydedin
	image.save(path_join(directory, "output.psd"), PsdOptions())


```

### This example shows the process of saving an Image to MemoryStream. To demonstrate this operation, example loads an existing file from some disk location, performs `rotate` operation on the image and save the image in PSD format {#example_10}
``` python
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.extensions import StreamExtensions as stream_ext

#MemoryStream'in bir örneğini oluşturun
with stream_ext.create_memory_stream() as stream:
	#Image sınıfının bir örneğini oluşturun ve mevcut bir dosyayı Dosya yolu aracılığıyla başlatın
	with Image.load(r"C:\temp\sample.bmp") as image:
		#Görüntüyü X ekseni etrafında 180 derece döndürün
		image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
		#Görüntüyü PSD olarak MemoryStream'e varsayılan PsdOptions ayarlarıyla kaydedin
		image.save(stream, PsdOptions())


```

### This example determines whether image can be loaded from a file. {#example_22}
``` python

from aspose.imaging import Image

# Dosyaya mutlak bir yol kullanın
can_load: bool = Image.can_load(r"c:\temp\sample.gif")


```

### This example determines whether image can be loaded from a file stream. {#example_23}
``` python

from aspose.imaging import Image
from aspose.imaging.extensions import StreamExtensions as strm_ext
import os.path import join

directory = r"c:\temp"

canLoad = False

# Bir dosya akışı kullanın
with open(join(directory, "sample.bmp"), "rb"):
	canLoad = Image.can_load(stream)

print(f"Can load the file: {canLoad}")

# Aşağıdaki veri geçerli bir görüntü akışı değildir, bu yüzden CanLoad false döndürür.
imageData = [0, 0, 0, 0, 0, 0, 0, 0]
with strm_ext.create_memory_stream_from_bytes(imageData) as stream:
	canLoad = Image.can_load(stream)

print(f"Can load the byte buffer: {canLoad}")


```

### This example shows how to determine the image format without loading the entire image from a file. {#example_24}
``` python

from aspose.imaging import Image
from os.path import join as path_join

directory = "c:\\temp\\"

# Dosyaya mutlak bir yol kullanın
file_format = Image.get_file_format(path_join(directory, "sample.gif"))
print(f"The file format is {file_format}")


```

### This example shows how to determine the image format without loading the entire image from a file stream. {#example_25}
``` python

from aspose.imaging import Image
from aspose.imaging.extensions import StreamExtensions as strm_ex
from os.path import join as path_join

directory = "c:\\temp\\"

# Bir dosya akışı kullanın
with open(path_join(directory, "sample.bmp"), "rb") as stream:
	file_format = Image.get_file_format(stream)
	print(f"The file format is {file_format}")

# Aşağıdaki veri geçerli bir görüntü akışı değildir, bu yüzden get_file_format FileFormat.UNKNOWN döndürür.
imageData = bytearray([0, 0, 0, 0, 0, 0, 0, 0])
with strm_ex.create_memory_stream_from_bytes(imageData) as stream:
	file_format = Image.get_file_format(stream)
	print(f"The file format is {file_format}")


```

### This example shows how to determine whether image can be saved to the specified file format represented by the passed save options. {#example_26}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import JpegOptions
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	saveOptions = JpegOptions()
	saveOptions.quality = 50
	# Görüntünün jpeg olarak kaydedilip kaydedilemeyeceğini belirleyin
	canSave: bool = image.can_save(saveOptions)
	print(canSave)


```

### This example loads an image and resizes it using various resizing settings. {#example_28}
``` python
from aspose.imaging import Image, ImageResizeSettings, ResizeType, ImageFilterType,\
	ColorQuantizationMethod
from os.path import join as path_join

directory = "c:\\temp\\"

resizeSettings = ImageResizeSettings()

# Ağırlıklı ve karıştırılmış rasyonel fonksiyon ve lanczos3 interpolasyonuna dayalı uyarlamalı algoritma.
resizeSettings.mode = ResizeType.ADAPTIVE_RESAMPLE
# Küçük dikdörtgen filtre
resizeSettings.filter_type = ImageFilterType.SMALL_RECTANGULAR
# Palet içindeki renk sayısı.
resizeSettings.entries_count = 256
# Renk kantitatizasyonu kullanılmaz
resizeSettings.color_quantization_method = ColorQuantizationMethod.NONE

# Öklid yöntemi
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

with Image.load(path_join(directory, "sample.gif")) as image:
	# Uyarlamalı yeniden örnekleme kullanarak 2 kat küçült.
	image.resize(image.width // 2, image.height // 2, resizeSettings)
	image.save(path_join(directory, "downsample.adaptive.gif"))


```

### This example loads an image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically. {#example_29}
``` python
from aspose.imaging import Image, ResizeType
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	# En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
	image.resize_width_proportionally(image.width * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "upsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
	image.resize_width_proportionally(image.width // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "downsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Bilinear yeniden örnekleme kullanarak 2 kat büyüt.
	image.resize_width_proportionally(image.width * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "upsample.bilinear.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Bilinear yeniden örnekleme kullanarak 2 kat küçült.
	image.resize_width_proportionally(image.width // 2, ResizeType.BILINEAR_RESAMPLE);
	image.save(path_join(directory, "downsample.bilinear.gif"))


```

### This example loads an image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically. {#example_30}
``` python

from aspose.imaging import Image, ResizeType
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	# En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
	image.resize_height_proportionally(image.height * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "upsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
	image.resize_height_proportionally(image.height // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "downsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Bilinear yeniden örnekleme kullanarak 2 kat büyüt.
	image.resize_height_proportionally(image.height * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "upsample.bilinear.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Bilinear yeniden örnekleme kullanarak 2 kat küçült.
	image.resize_height_proportionally(image.height // 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "downsample.bilinear.gif"))


```

### This example loads an image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_31}
``` python

from aspose.imaging import Image, RotateFlipType
from os.path import join as path_join

directory = "c:\\temp\\"

rotateFlipTypes = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X,
				   RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]

for rotateFlipType in rotateFlipTypes:
	# Döndür, çevir ve çıktı dosyasına kaydet.
	with Image.Load(path_join(directory, "sample.bmp")) as image:
		image.rotate_flip(rotateFlipType)
		image.save(path_join(directory, f"sample.{rotateFlipType}.bmp"))


```

### The following example loads a BMP image from a file, then saves the image to a PNG file. {#example_32}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	# Tüm görüntüyü PNG dosyasına kaydedin.
	save_options = PngOptions()
	image.save(path_join(dir, "output.png"), save_options)

```

### The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file. {#example_33}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	# Görüntünün üst yarısını PNG dosyasına kaydedin.
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width, image.height // 2)
	image.save(path_join(dir, "output.png"), save_options, bounds)

```

### The following example loads an image from a file, then saves the image to a PNG file stream. {#example_34}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	save_options = PngOptions()
	with open(path_join(dir, "output.png"), "w+b") as output_stream:
		# Tüm görüntüyü bir dosya akışına kaydedin.
		image.save(output_stream, save_options)

```

### The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream. {#example_35}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width, image.height // 2)
	with open(path_join(dir, "output.png"), "w+b") as output_stream:
		# Görüntünün üst yarısını bir dosya akışına kaydedin.
		image.save(output_stream, save_options, bounds)


```

### The following example shows how to save an entire BMP image or part of it to a file or stream. {#example_90}
``` python

from os.path import join as path_join
from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.extensions import StreamExtensions as strm_ext

directory = "c:\\temp\\"
with Image.load(path_join(directory, "sample.bmp")) as image:
	bmpImage = as_of(image, BmpImage)
		
	# Siyah-beyaz bir görüntüye dönüştürün
	bmpImage.binarize_otsu()

	# Aynı konuma varsayılan seçeneklerle kaydedin.
	image.save()

	saveOptions = BmpOptions()

	# Bu durumda bir palet yalnızca iki renk içerir: Siyah ve Beyaz.
	saveOptions.palette = ColorPaletteHelper.create_monochrome()

	# Tüm tek renkli görüntüler için (siyah-beyaz olanlar dahil) piksel başına 1 bit ayırmak yeterlidir.
	saveOptions.bits_per_pixel = 1

	# Belirtilen seçeneklerle başka bir konuma kaydedin.
	image.save(path_join(directory, "sample.bw.palettized.bmp"), saveOptions)

	# Yalnızca görüntünün merkez kısmını kaydedin.
	bounds = Rectangle(image.width // 4, image.height // 4, image.width // 2, image.height // 2)
	image.save(path_join(directory, "sample.bw.palettized.part.bmp"), saveOptions, bounds)

	# Tüm görüntüyü bir bellek akışına kaydedin
	with strm_ext.create_memory_stream() as stream:
		image.save(stream, saveOptions);
		print("The size of the whole image in bytes:", stream.tell())

	# Görüntünün merkezi bölümünü bir bellek akışına kaydedin
	with strm_ext.create_memory_stream() as stream:
		image.save(stream, saveOptions, bounds)
		print("The size of the central part of the image in bytes: ", stream.tell())

#Çıktı şu şekilde görünebilir:
#Tam görüntünün bayt cinsinden boyutu: 24062
#Görüntünün merkezi bölümünün bayt cinsinden boyutu: 6046

```

### The following example shows how to resize a metafile (WMF and EMF). {#example_182}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.emf import MetaImage
from os.path import join

dir_ = "c:\\temp"
file_names = ["image3.emf", "image4.wmf"]
for file_name in file_names:
	input_file_path = join(dir_, file_name)
	output_file_path = join(dir_, "Downscale_" + file_name)
	with aspycore.as_of(Image.load(input_file_path), MetaImage) as image:
		image.resize(image.width // 4, image.height // 4)
		image.save(output_file_path)


```

### The following example shows how to resize SVG image and save it to PNG. {#example_185}
``` python

from aspose.imaging import PointF, Image
from aspose.imaging.imageoptions import PngOptions
from os import path

dir_ = "c:\\aspose.imaging\\net\\issues\\3549"
file_names = ["Logotype.svg", "sample_car.svg", "rg1024_green_grapes.svg", "MidMarkerFigure.svg", "embeddedFonts.svg"]
scales = [PointF(0.5, 0.5), PointF(1.0, 1.0), PointF(2.0, 2.0), PointF(3.5, 9.2)]
for input_file in file_names:
	for scale in scales:
		output_file = "{0}_{1}_{2}.png".format(input_file, str(scale.x), str(scale.y))
		with Image.load(path.join(dir_, input_file)) as image:
			image.resize(int(image.width * scale.x), int(image.height * scale.y))
			image.save(path.join(dir_, output_file), PngOptions())


```

### Resize image using specific Resize Type. {#example_209}
``` python
from aspose.imaging import Image, ResizeType, ImageResizeSettings, ImageFilterType

with Image.load("Photo.jpg") as image:
	image.resize(640, 480, ResizeType.CATMULL_ROM)
	image.save("ResizedPhoto.jpg")
	image.resize(1024, 768, ResizeType.CUBIC_CONVOLUTION)
	image.save("ResizedPhoto2.jpg")
	resize_settings = ImageResizeSettings()
	resize_settings.mode = ResizeType.CUBIC_BSPLINE
	resize_settings.filter_type = ImageFilterType.SMALL_RECTANGULAR
	image.resize(800, 800, resize_settings)
	image.save("ResizedPhoto3.jpg")


```

### Determine if the palette is used by the image. {#example_221}
``` python

from aspose.imaging import Image

with Image.load("Sample.bmp") as image:
	if image.use_palette:
		print("The palette is used by the image")

```

