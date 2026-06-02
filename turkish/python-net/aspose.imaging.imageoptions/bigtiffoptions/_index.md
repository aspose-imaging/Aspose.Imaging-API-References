---
title: "BigTiffOptions Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.imageoptions/bigtiffoptions/
---

**Summary:** The API for BigTIFF raster image format creation is specifically designed<br/>            to serve to the unique requirements of applications utilizing large-scale<br/>            imaging data from scanners. This API facilitates the seamless generation<br/>            of BigTIFF format, which combines multiple TIFF images into a single,<br/>            comprehensive image. It ensures efficient processing of extensive image<br/>            data, providing developers with a powerful tool for creating and<br/>            manipulating high-resolution, multi-image formats.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BigTiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, TiffOptions

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [BigTiffOptions(expected_format)](#BigTiffOptions_expected_format_1) | Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır. Varsayılan olarak küçük endian kuralı kullanılır. |
| [BigTiffOptions(expected_format, byte_order)](#BigTiffOptions_expected_format_byte_order_2) | Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır. |
| [BigTiffOptions(options)](#BigTiffOptions_options_3) | Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır. |
| [BigTiffOptions(tags)](#BigTiffOptions_tags_4) | Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) | r/w | Alfa depolama seçeneğini alır veya ayarlar. [TiffAlphaStorage.UNSPECIFIED](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) dışındaki seçenekler,<br/>            tanımlı 3'ten fazla [TiffOptions.samples_per_pixel](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) olduğunda kullanılır. |
| artist | string | r/w | Sanatçıyı alır veya ayarlar. |
| bits_per_pixel | int | r | Piksel başına bit sayısını alır. |
| bits_per_sample | int[] | r/w | Örnek başına bitleri alır veya ayarlar. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Tiff bayt sırasını gösteren bir değeri alır veya ayarlar. |
| color_map | int[] | r/w | Renk haritasını alır veya ayarlar. |
| compressed_quality | int | r/w | Sıkıştırılmış görüntü kalitesini alır veya ayarlar.<br/>            Jpeg sıkıştırmasıyla kullanılır. |
| compression | [TiffCompressions](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffcompressions/) | r/w | Sıkıştırmayı alır veya ayarlar. |
| copyright | string | r/w | Telif hakkını alır veya ayarlar. |
| date_time | string | r/w | Tarih ve saati alır veya ayarlar. |
| default_memory_allocation_limit | int | r/w | Varsayılan bellek tahsis sınırını alır veya ayarlar. |
| disable_icc_export | bool | r/w | ICC profil dışa aktarımının devre dışı bırakılıp bırakılmadığını gösteren bir değeri alır veya ayarlar (ICC profili önceden kaynak piksellere uygulanır). |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| document_name | string | r/w | Belgenin adını alır veya ayarlar. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif verilerini alır veya ayarlar. |
| exif_ifd | [TiffExifIfd](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffexififd/) | r | EXIF IFD'ye işaretçiyi alır veya ayarlar. |
| extra_samples | int[] | r | Ek örnek değerlerini alır. |
| fax_t4_options | [Group3Options](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/group3options/) | r/w | Fax t4 seçeneklerini alır veya ayarlar. |
| file_standard | [TiffFileStandards](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffilestandards/) | r/w | TIFF dosya standardını alır veya ayarlar. |
| fill_order | [TiffFillOrders](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffillorders/) | r/w | Bayt bitlerinin doldurma sırasını alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve [full frame] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| half_tone_hints | int[] | r/w | Yarı ton ipuçlarını alır veya ayarlar. |
| image_description | string | r/w | Görüntü açıklamasını alır veya ayarlar. |
| image_length | int | r/w | Görüntü uzunluğunu alır veya ayarlar. |
| image_width | int | r/w | Görüntü genişliğini alır veya ayarlar. |
| ink_names | string | r/w | Mürekkep adlarını alır veya ayarlar. |
| is_extra_samples_present | bool | r | Ek örneklerin mevcut olup olmadığını gösteren bir değer alır. |
| is_tiled | bool | r | Görüntünün döşenmiş olup olmadığını gösteren bir değer alır. |
| is_valid | bool | r | Doğru şekilde yapılandırılıp yapılandırıldığını gösteren bir değer alır. Hata nedenini bulmak için Validate yöntemini kullanın. |
| keep_metadata | bool | r/w | Dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağını gösteren bir değeri alır. |
| max_sample_value | int[] | r/w | Maksimum örnek değerini alır veya ayarlar. |
| min_sample_value | int[] | r/w | Minimum örnek değerini alır veya ayarlar. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Çok sayfalı seçenekler |
| orientation | [TiffOrientations](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifforientations/) | r/w | Yönelimini alır veya ayarlar. |
| page_name | string | r/w | Sayfa adını alır veya ayarlar. |
| page_number | int[] | r/w | Sayfa numarası etiketini alır veya ayarlar. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. |
| photometric | [TiffPhotometrics](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffphotometrics/) | r/w | Fotometrik değerini alır veya ayarlar. |
| planar_configuration | [TiffPlanarConfigs](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Planar yapılandırmayı alır veya ayarlar. |
| predictor | [TiffPredictor](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffpredictor/) | r/w | LZW sıkıştırması için öngörücüyü alır veya ayarlar. |
| premultiply_components | bool | r/w | Bileşenlerin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| resolution_unit | [TiffResolutionUnits](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Çözünürlük birimini alır veya ayarlar. |
| rows_per_strip | int | r/w | Şerit başına satır sayısını alır veya ayarlar. |
| sample_format | [TiffSampleFormats[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffsampleformats/) | r/w | Örnek formatını alır veya ayarlar. |
| samples_per_pixel | int | r | Piksel başına örnek sayısını alır. Bu özellik değerini değiştirmek için [TiffOptions.bits_per_sample](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) özellik ayarlayıcısını kullanın. |
| scanner_manufacturer | string | r/w | Tarayıcı üreticisini alır veya ayarlar. |
| scanner_model | string | r/w | Tarayıcı modelini alır veya ayarlar. |
| smax_sample_value | int[] | r/w | Maksimum örnek değerini alır veya ayarlar. Değer, örnek veriye en uygun alan tipine sahiptir (Byte, Short veya Long tipi). |
| smin_sample_value | int[] | r/w | Minimum örnek değerini alır veya ayarlar. Değer, örnek veriye en uygun alan tipine sahiptir (Byte, Short veya Long tipi). |
| software_type | string | r/w | Yazılım tipini alır veya ayarlar. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| strip_byte_counts | int[] | r/w | Şerit bayt sayılarını alır veya ayarlar. |
| strip_offsets | int[] | r/w | Şerit ofsetlerini alır veya ayarlar. |
| sub_file_type | [TiffNewSubFileTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Bu alt dosyada bulunan veri türünün genel bir göstergesini alır veya ayarlar. |
| tag_count | int | r | Etiket sayısını alır. |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Etiketleri alır veya ayarlar. |
| target_printer | string | r/w | Hedef yazıcıyı alır veya ayarlar. |
| threshholding | [TiffThresholds](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffthresholds/) | r/w | Eşikleme değerini alır veya ayarlar. |
| tile_byte_counts | int[] | r/w | Döşeme bayt sayılarını alır veya ayarlar. |
| tile_length | int | r/w | Döşeme uzunluğunu alır veya ayarlar. |
| tile_offsets | int[] | r/w | Döşeme ofsetlerini alır veya ayarlar. |
| tile_width | int | r/w | Döşeme genişliğini alır veya ayarlar. |
| total_pages | int | r | Toplam sayfaları alır. |
| valid_tag_count | int | r | Geçerli etiket sayısını alır. Bu, toplam etiket sayısı değil, korunabilecek etiketlerin sayısıdır. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Xmp verilerini alır veya ayarlar. |
| xp_author | string | r/w | Görüntü yazarını alır veya ayarlar, Windows Gezgini tarafından kullanılır. |
| xp_comment | string | r/w | Görüntü yorumunu alır veya ayarlar, Windows Gezgini tarafından kullanılır. |
| xp_keywords | string | r/w | Görüntü konusunu alır veya ayarlar, Windows Gezgini tarafından kullanılır. |
| xp_subject | string | r/w | Görüntü hakkında bilgiyi alır veya ayarlar, Windows Gezgini tarafından kullanılır. |
| xp_title | string | r/w | Görüntü hakkında bilgiyi alır veya ayarlar, Windows Gezgini tarafından kullanılır. |
| xposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | X konumunu alır veya ayarlar. |
| xresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | x çözünürlüğünü alır veya ayarlar. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | YCbCr katsayılarını alır veya ayarlar. |
| y_cb_cr_subsampling | int[] | r/w | YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar. |
| yposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Y konumunu alır veya ayarlar. |
| yresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | y çözünürlüğünü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Yeni bir etiket ekler. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Etiketleri ekler. |
| [clone()](#clone__3) | Bu örneği klonlar. |
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır. Varsayılan olarak küçük endian kuralı kullanılır. |
| [create_with_options(options)](#create_with_options_options_5) | Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır. |
| [create_with_tags(tags)](#create_with_tags_tags_6) | Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | Etiketin örneğini türe göre alır. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | Geçerli etiket sayısını alır. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | Etiketin seçeneklerde bulunup bulunmadığını belirler. |
| [remove_tag(tag)](#remove_tag_tag_10) | Etiketi kaldırır. |
| [remove_tags(tags)](#remove_tags_tags_11) | Etiketleri kaldırır. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |
| validate() | Seçeneklerin geçerli bir etiket kombinasyonuna sahip olup olmadığını doğrular |


### Constructor: BigTiffOptions(expected_format) {#BigTiffOptions_expected_format_1}


```
 BigTiffOptions(expected_format) 
```

Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır. Varsayılan olarak küçük endian kuralı kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Beklenen Tiff dosya biçimi. |

### Constructor: BigTiffOptions(expected_format, byte_order) {#BigTiffOptions_expected_format_byte_order_2}


```
 BigTiffOptions(expected_format, byte_order) 
```

Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Beklenen Tiff dosya biçimi. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | Kullanılacak tiff dosya biçimi bayt sırası. |

### Constructor: BigTiffOptions(options) {#BigTiffOptions_options_3}


```
 BigTiffOptions(options) 
```

Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Seçenek kaynağı. |

### Constructor: BigTiffOptions(tags) {#BigTiffOptions_tags_4}


```
 BigTiffOptions(tags) 
```

Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Seçenek başlatma için etiketler. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Yeni bir etiket ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Eklenecek etiket. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Etiketleri ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Eklenecek etiketler. |

### Method: clone() {#clone__3}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Derin bir kopya döndürür. |


### Method: create_with_format(expected_format)  [static] {#create_with_format_expected_format_4}


```
 create_with_format(expected_format) 
```

Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır. Varsayılan olarak küçük endian kuralı kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | Beklenen Tiff dosya biçimi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | Yeni bir BigTiffOptions nesnesi. |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | Seçenek kaynağı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | Seçeneklerin bir kopyası. |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

Yeni bir [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Seçenek başlatma için etiketler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | Etiketli yeni bir BigTiffOptions nesnesi. |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_7}


```
 get_tag_by_type(tag_key) 
```

Etiketin örneğini türe göre alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag_key | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Etiket anahtarı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Etiket mevcutsa örneği, aksi takdirde null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_8}


```
 get_valid_tags_count(tags) 
```

Geçerli etiket sayısını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Doğrulanacak etiketler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Geçerli etiket sayısı. |


### Method: is_tag_present(tag) {#is_tag_present_tag_9}


```
 is_tag_present(tag) 
```

Etiketin seçeneklerde bulunup bulunmadığını belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Kontrol edilecek etiket kimliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer etiket mevcutsa; aksi takdirde <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_10}


```
 remove_tag(tag) 
```

Etiketi kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Kaldırılacak etiket. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | başarıyla kaldırıldıysa true |


### Method: remove_tags(tags) {#remove_tags_tags_11}


```
 remove_tags(tags) 
```

Etiketleri kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tags | [TiffTags[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Kaldırılacak etiketler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | **True** eğer etiket koleksiyonu boyutu değiştiyse. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_12}


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


