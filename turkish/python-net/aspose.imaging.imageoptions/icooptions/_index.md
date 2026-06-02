---
title: "IcoOptions Sınıfı"
type: docs
weight: 140
url: /tr/python-net/aspose.imaging.imageoptions/icooptions/
---

**Summary:** Create custom ICO image files for application icons effortlessly with our API,<br/>            empowering you to represent your software seamlessly. Our API supports PNG and<br/>            BMP image frames with various bits per pixel values, ensuring versatility and<br/>            compatibility for your icon creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.IcoOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [IcoOptions()](#IcoOptions__1) | ICO çerçeve formatı Png ve<br/>            bitsPerPixel değeri 32 olan yeni bir [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) sınıfı örneği başlatır. |
| [IcoOptions(format, bits_per_pixel)](#IcoOptions_format_bits_per_pixel_2) | Yeni bir [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | Bits-per-pixel değerini alır veya ayarlar. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif verilerini alır veya ayarlar. |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r/w | ICO çerçeve formatını alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve [full frame] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| keep_metadata | bool | r/w | Dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağını gösteren bir değeri alır. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Çok sayfalı seçenekler |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | XMP meta veri kapsayıcısını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneğin üye bazlı bir klonunu oluşturur. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |


### Constructor: IcoOptions() {#IcoOptions__1}


```
 IcoOptions() 
```

ICO çerçeve formatı Png ve<br/>            bitsPerPixel değeri 32 olan yeni bir [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) sınıfı örneği başlatır.

### Constructor: IcoOptions(format, bits_per_pixel) {#IcoOptions_format_bits_per_pixel_2}


```
 IcoOptions(format, bits_per_pixel) 
```

Yeni bir [IcoOptions](/imaging/python-net/aspose.imaging.imageoptions/icooptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | ICO çerçeve formatı.<br/>            Not: ICO görüntüsü yalnızca [FileFormat.PNG](/imaging/python-net/aspose.imaging/fileformat/) ve [FileFormat.BMP](/imaging/python-net/aspose.imaging/fileformat/) görüntülerini giriş olarak destekler. |
| bits_per_pixel | int | Bits-per-pixel değeri. |

### Method: clone() {#clone__1}


```
 clone() 
```

Bu örneğin üye bazlı bir klonunu oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Bu örneğin üye bazlı bir klonu. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


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
| bool | Doğru, eğer [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) örneği [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini destekliyor ve/veya uyguluyorsa; aksi takdirde, yanlış. |


