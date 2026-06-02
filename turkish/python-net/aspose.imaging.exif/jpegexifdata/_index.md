---
title: "JpegExifData Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.JpegExifData

**Inheritance:** IImageMetadataFormat, ExifData

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) sınıfının yeni bir örneğini başlatır. |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) sınıfının yeni bir örneğini dizi verisiyle başlatır. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) sınıfının yeni bir örneğini dizi verisiyle başlatır. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_4) | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) sınıfının yeni bir örneğini dizi verisiyle başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | İzin verilen maksimum EXIF segment boyutu (bayt olarak). |
| aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Diyafram değerini alır veya ayarlar. |
| artist | string | r/w | Sanatçıyı alır veya ayarlar. |
| bits_per_sample | int[] | r/w | Örnek başına bitleri alır veya ayarlar. |
| body_serial_number | string | r/w | Kamera gövdesi seri numarasını alır veya ayarlar. |
| brightness_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Parlaklık değerini alır veya ayarlar. |
| camera_owner_name | string | r/w | Kamera sahibi adını alır veya ayarlar. |
| cfa_pattern | System.Byte | r/w | CFA desenini alır veya ayarlar. |
| color_space | [ExifColorSpace](/imaging/python-net/aspose.imaging.exif.enums/exifcolorspace/) | r/w | Renk uzayını alır veya ayarlar. |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Ortak bölüme ait etiketleri alır veya ayarlar. Bu yalnızca jpeg görüntüler için geçerlidir, tiff formatında ise tiffOptions kullanılmaktadır. |
| components_configuration | System.Byte | r/w | Bileşen yapılandırmasını alır veya ayarlar. |
| compressed_bits_per_pixel | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Piksel başına sıkıştırılmış bit sayısını alır veya ayarlar. |
| compression | int | r/w | Sıkıştırmayı alır veya ayarlar. |
| contrast | [ExifContrast](/imaging/python-net/aspose.imaging.exif.enums/exifcontrast/) | r/w | Kontrastı alır veya ayarlar. |
| copyright | string | r/w | Telif hakkını alır veya ayarlar. |
| custom_rendered | [ExifCustomRendered](/imaging/python-net/aspose.imaging.exif.enums/exifcustomrendered/) | r/w | Özel işlenmiş değeri alır veya ayarlar. |
| date_time | string | r/w | Tarih ve saati alır veya ayarlar. |
| date_time_digitized | string | r/w | Dijitalleştirilmiş tarih ve saati alır veya ayarlar. |
| date_time_original | string | r/w | Orijinal tarih ve saati alır veya ayarlar. |
| device_setting_description | System.Byte | r/w | Cihaz ayarları açıklamasını alır veya ayarlar. |
| digital_zoom_ratio | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Dijital zoom oranını alır veya ayarlar. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | EXIF bölümüne ait etiketleri alır veya ayarlar. |
| exif_version | System.Byte | r/w | EXIF sürümünü alır veya ayarlar. |
| exposure_bias_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Pozlama sapma değerini alır veya ayarlar. |
| exposure_index | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Pozlama indeksini alır veya ayarlar. |
| exposure_mode | [ExifExposureMode](/imaging/python-net/aspose.imaging.exif.enums/exifexposuremode/) | r/w | Pozlama modunu alır veya ayarlar. |
| exposure_program | [ExifExposureProgram](/imaging/python-net/aspose.imaging.exif.enums/exifexposureprogram/) | r/w | Pozlama programını alır veya ayarlar. |
| exposure_time | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Pozlama süresini alır veya ayarlar. |
| f_number | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | F-numarasını alır veya ayarlar. |
| file_source | [ExifFileSource](/imaging/python-net/aspose.imaging.exif.enums/exiffilesource/) | r/w | Dosya kaynağı tipini alır veya ayarlar. |
| flash | [ExifFlash](/imaging/python-net/aspose.imaging.exif.enums/exifflash/) | r/w | Flaşı alır veya ayarlar. |
| flash_energy | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Flaş enerjisini alır veya ayarlar. |
| flashpix_version | System.Byte | r/w | Flaş piksel sürümünü alır veya ayarlar. |
| focal_length | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Odak uzaklığını alır veya ayarlar. |
| focal_length_in_35_mm_film | int | r/w | 35 mm filmde odak uzaklığını alır veya ayarlar. |
| focal_plane_resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Odak düzlemi çözünürlük birimini alır veya ayarlar. |
| focal_plane_x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Odak düzlemi x çözünürlüğünü alır veya ayarlar. |
| focal_plane_y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Odak düzlemi y çözünürlüğünü alır veya ayarlar. |
| gain_control | [ExifGainControl](/imaging/python-net/aspose.imaging.exif.enums/exifgaincontrol/) | r/w | Genel görüntü kazanç ayarının derecesini alır veya ayarlar. |
| gamma | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Gama değerini alır veya ayarlar. |
| gps_altitude | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | GPS yüksekliğini alır veya ayarlar. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/imaging/python-net/aspose.imaging.exif.enums/exifgpsaltituderef/) | r/w | Referans yüksekliği olarak kullanılan GPS yüksekliğini alır veya ayarlar. |
| gps_area_information | System.Byte | r/w | GPS alan bilgilerini alır veya ayarlar. |
| gps_date_stamp | string | r/w | UTC'ye (Eşgüdümlü Evrensel Zaman) göre tarih ve saat bilgisini kaydeden GPS karakter dizisini alır veya ayarlar. |
| gps_dest_bearing | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hedef noktaya olan GPS yönünü alır veya ayarlar. |
| gps_dest_bearing_ref | string | r/w | Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar. |
| gps_dest_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hedef noktaya olan GPS mesafesini alır veya ayarlar. |
| gps_dest_distance_ref | string | r/w | Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar. |
| gps_dest_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hedef noktanın GPS enlemini alır veya ayarlar. |
| gps_dest_latitude_ref | string | r/w | Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değerini alır veya ayarlar. |
| gps_dest_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Hedef noktanın GPS boylamını alır veya ayarlar. |
| gps_dest_longitude_ref | string | r/w | Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değerini alır veya ayarlar. |
| gps_differential | int | r/w | GPS alıcıya diferansiyel düzeltmenin uygulanıp uygulanmadığını gösteren bir GPS değerini alır veya ayarlar. |
| gps_img_direction | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Görüntünün yakalandığı zaman GPS yönünü alır veya ayarlar. |
| gps_img_direction_ref | string | r/w | Görüntünün yakalandığı zaman yönünü vermek için GPS referansını alır veya ayarlar. |
| gps_latitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | GPS enlemini alır veya ayarlar. |
| gps_latitude_ref | string | r/w | GPS enleminin kuzey mi yoksa güney mi olduğunu alır veya ayarlar. |
| gps_longitude | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | GPS boylamını alır veya ayarlar. |
| gps_longitude_ref | string | r/w | GPS boylamının doğu ya da batı olduğunu alır veya ayarlar. |
| gps_map_datum | string | r/w | GPS alıcısı tarafından kullanılan GPS jeodezik ölçüm verilerini alır veya ayarlar. |
| gps_measure_mode | string | r/w | GPS ölçüm modunu alır veya ayarlar. |
| gps_processing_method | System.Byte | r/w | Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizisini alır veya ayarlar. |
| gps_satellites | string | r/w | Ölçümler için kullanılan GPS uydularını alır veya ayarlar. |
| gps_speed | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | GPS alıcısının hareket hızını alır veya ayarlar. |
| gps_speed_ref | string | r/w | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar. |
| gps_status | string | r/w | Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Yalnızca GPS bölümüne ait etiketleri alır veya ayarlar. |
| gps_timestamp | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | GPS zamanını UTC (Eşgüdümlü Evrensel Zaman) olarak alır veya ayarlar. |
| gps_track | string | r/w | GPS alıcısının hareket yönünü alır veya ayarlar. |
| gps_track_ref | string | r/w | GPS alıcısının hareket yönünü vermek için referansı alır veya ayarlar. |
| gps_version_id | System.Byte | r/w | GPS sürüm tanımlayıcısını alır veya ayarlar. |
| gpsdop | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | GPS DOP (veri kesinlik derecesi) değerini alır veya ayarlar. |
| image_description | string | r/w | Görüntü açıklamasını alır veya ayarlar. |
| image_length | int | r/w | Görüntü uzunluğunu alır veya ayarlar. |
| image_unique_id | string | r/w | Görüntünün benzersiz tanımlayıcısını alır veya ayarlar. |
| image_width | int | r/w | Görüntü genişliğini alır veya ayarlar. |
| is_big_endian | bool | r/w | Akış EXIF verisinin büyük endian olup olduğunu gösteren bir değeri alır veya ayarlar. |
| iso_speed | int | r/w | ISO hızını alır veya ayarlar. |
| iso_speed_latitude_yyy | int | r/w | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değerini alır veya ayarlar. |
| iso_speed_latitude_zzz | int | r/w | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değerini alır veya ayarlar. |
| iso_speed_value | int | r/w | ISO hız değerini alır veya ayarlar. |
| lens_make | string | r/w | Lensin üreticisini alır veya ayarlar. |
| lens_model | string | r/w | Lens modelini alır veya ayarlar. |
| lens_serial_number | string | r/w | Lens seri numarasını alır veya ayarlar. |
| lens_specification | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Lens özelliklerini alır veya ayarlar. |
| light_source | [ExifLightSource](/imaging/python-net/aspose.imaging.exif.enums/exiflightsource/) | r/w | Işık kaynağını alır veya ayarlar. |
| make | string | r/w | Kayıt ekipmanının üreticisini alır veya ayarlar. |
| maker_note_data | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r | Üretici not verilerini alır. |
| maker_note_raw_data | System.Byte | r/w | Üretici not ham verisini alır veya ayarlar. |
| maker_notes | [MakerNote[]](/imaging/python-net/aspose.imaging.exif/makernote/) | r | Üretici notlarını alır. |
| max_aperture_value | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Maksimum diyafram değerini alır veya ayarlar. |
| metering_mode | [ExifMeteringMode](/imaging/python-net/aspose.imaging.exif.enums/exifmeteringmode/) | r/w | Ölçüm modunu alır veya ayarlar. |
| model | string | r/w | Modeli alır veya ayarlar. |
| oecf | System.Byte | r/w | ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) alır veya ayarlar. |
| orientation | [ExifOrientation](/imaging/python-net/aspose.imaging.exif.enums/exiforientation/) | r/w | Yönelimini alır veya ayarlar. |
| photographic_sensitivity | int | r/w | Fotoğraf hassasiyetini alır veya ayarlar. |
| photometric_interpretation | int | r/w | Fotometrik yorumlamayı alır veya ayarlar. |
| pixel_x_dimension | int | r/w | Piksel x boyutunu alır veya ayarlar. |
| pixel_y_dimension | int | r/w | Piksel y boyutunu alır veya ayarlar. |
| planar_configuration | int | r/w | Planar yapılandırmayı alır veya ayarlar. |
| primary_chromaticities | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Görüntünün üç ana renginin kromatikliğini alır veya ayarlar. |
| properties | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Tüm EXIF etiketlerini (ortak ve GPS etiketleri dahil) alır veya ayarlar. |
| recommended_exposure_index | int | r/w | Önerilen pozlama indeksini alır veya ayarlar. |
| reference_black_white | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Referans siyah beyazı alır veya ayarlar. |
| related_sound_file | string | r/w | İlgili ses dosyasını alır veya ayarlar. |
| resolution_unit | [ExifUnit](/imaging/python-net/aspose.imaging.exif.enums/exifunit/) | r/w | Çözünürlük birimini alır veya ayarlar. |
| samples_per_pixel | int | r/w | Piksel başına örnekleri alır veya ayarlar. |
| saturation | [ExifSaturation](/imaging/python-net/aspose.imaging.exif.enums/exifsaturation/) | r/w | Doygunluğu alır veya ayarlar. |
| scene_capture_type | [ExifSceneCaptureType](/imaging/python-net/aspose.imaging.exif.enums/exifscenecapturetype/) | r/w | Sahne yakalama türünü alır veya ayarlar. |
| scene_type | System.Byte | r/w | Sahne tipini alır veya ayarlar. |
| sensing_method | [ExifSensingMethod](/imaging/python-net/aspose.imaging.exif.enums/exifsensingmethod/) | r/w | Algılama yöntemini alır veya ayarlar. |
| sensitivity_type | int | r/w | Hassasiyet tipini alır veya ayarlar. |
| sharpness | int | r/w | Keskinliği alır veya ayarlar. |
| shutter_speed_value | [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | r/w | Deklanşör hızı değerini alır veya ayarlar. |
| software | string | r/w | Yazılımı alır veya ayarlar. |
| spatial_frequency_response | System.Byte | r/w | Mekânsal frekans yanıtını alır veya ayarlar. |
| spectral_sensitivity | string | r/w | Spektral duyarlılığı alır veya ayarlar. |
| standard_output_sensitivity | int | r/w | Standart çıktı duyarlılığını alır veya ayarlar |
| subject_area | int[] | r/w | Konu alanını alır veya ayarlar. |
| subject_distance | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Konu mesafesini alır veya ayarlar. |
| subject_distance_range | [ExifSubjectDistanceRange](/imaging/python-net/aspose.imaging.exif.enums/exifsubjectdistancerange/) | r/w | Konu mesafe aralığını alır veya ayarlar. |
| subject_location | int[] | r/w | Konu konumunu alır veya ayarlar. |
| subsec_time | string | r/w | DateTime etiketi için saniyenin kesirlerini alır veya ayarlar. |
| subsec_time_digitized | string | r/w | DateTimeDigitized etiketi için saniyenin kesirlerini alır veya ayarlar. |
| subsec_time_original | string | r/w | DateTimeOriginal etiketi için saniyenin kesirlerini alır veya ayarlar. |
| thumbnail | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r/w | Küçük resim görüntüsünü alır veya ayarlar. |
| transfer_function | int[] | r/w | Transfer fonksiyonunu alır veya ayarlar. |
| user_comment | string | r/w | Kullanıcı yorumunu alır veya ayarlar. |
| white_balance | [ExifWhiteBalance](/imaging/python-net/aspose.imaging.exif.enums/exifwhitebalance/) | r/w | Beyaz dengesini alır veya ayarlar. |
| white_point | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Görüntünün beyaz noktasının kromatikliğini alır veya ayarlar. |
| x_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | x çözünürlüğünü alır veya ayarlar. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | RGB'den YCbCr görüntü verisine dönüşüm için matris katsayılarını alır veya ayarlar. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/imaging/python-net/aspose.imaging.exif.enums/exifycbcrpositioning/) | r/w | Krominans bileşenlerinin parlaklık bileşenine göre konumunu alır veya ayarlar. |
| y_cb_cr_sub_sampling | int[] | r/w | Krominans bileşenlerinin parlaklık bileşenine göre örnekleme oranını alır veya ayarlar. |
| y_resolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | y çözünürlüğünü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_tag_value(key)](#get_tag_value_key_1) | Etiket değerini alır. |
| [load_from_bytes(binary_data)](#load_from_bytes_binary_data_2) | Bayt dizisinden yükleyerek [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) sınıfının yeni bir örneğini oluşturur. |
| [remove_tag(tag)](#remove_tag_tag_3) | Etiketi konteynerden kaldır. |
| [remove_tag(tag_id)](#remove_tag_tag_id_4) | Etiketi konteynerden kaldır. |
| [remove_tag_id(tag_id)](#remove_tag_id_tag_id_5) | Etiketi konteynerden kaldır. |
| [serialize_exif_data()](#serialize_exif_data__6) | EXIF verilerini serileştirir. Etiket değerlerini ve içeriklerini yazar. En çok boyutu etkileyen etiket, Küçük Resim etiketinin içeriğidir. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

[JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) sınıfının yeni bir örneğini başlatır.

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

[JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) sınıfının yeni bir örneğini dizi verisiyle başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Ortak etiketler. |
| exif_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | EXIF etiketleri. |
| gps_tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | GPS etiketleri. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

[JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) sınıfının yeni bir örneğini dizi verisiyle başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Ortak ve GPS etiketleriyle birlikte EXIF etiketlerinin dizisi. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_4}


```
 JpegExifData(exifdata) 
```

[JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) sınıfının yeni bir örneğini dizi verisiyle başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| exifdata | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Ortak ve GPS etiketleriyle birlikte EXIF etiketlerinin dizisi. |

### Method: get_tag_value(key) {#get_tag_value_key_1}


```
 get_tag_value(key) 
```

Etiket değerini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | Etiket anahtarı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | TiffDataType |


### Method: load_from_bytes(binary_data)  [static] {#load_from_bytes_binary_data_2}


```
 load_from_bytes(binary_data) 
```

Bayt dizisinden yükleyerek [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) sınıfının yeni bir örneğini oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| binary_data | System.Byte | İkili veri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | Yüklenen ExifData örneği. |


### Method: remove_tag(tag) {#remove_tag_tag_3}


```
 remove_tag(tag) 
```

Etiketi konteynerden kaldır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag | [ExifProperties](/imaging/python-net/aspose.imaging.exif/exifproperties/) | Kaldırılacak etiket |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_4}


```
 remove_tag(tag_id) 
```

Etiketi konteynerden kaldır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag_id | int | Kaldırılacak etiket tanımlayıcısı. |

### Method: remove_tag_id(tag_id) {#remove_tag_id_tag_id_5}


```
 remove_tag_id(tag_id) 
```

Etiketi konteynerden kaldır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag_id | int | Kaldırılacak etiket tanımlayıcısı. |

### Method: serialize_exif_data() {#serialize_exif_data__6}


```
 serialize_exif_data() 
```

EXIF verilerini serileştirir. Etiket değerlerini ve içeriklerini yazar. En çok boyutu etkileyen etiket, Küçük Resim etiketinin içeriğidir.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | Serileştirilmiş EXIF verileri. |


