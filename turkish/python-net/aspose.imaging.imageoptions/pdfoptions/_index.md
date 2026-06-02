---
title: "PdfOptions Sınıfı"
type: docs
weight: 240
url: /tr/python-net/aspose.imaging.imageoptions/pdfoptions/
---

**Summary:** The PDF options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PdfOptions()](#PdfOptions__1) | Yeni bir [PdfOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif verilerini alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve [full frame] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| keep_metadata | bool | r/w | Dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağını gösteren bir değeri alır. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Çok sayfalı seçenekler |
| page_size | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r/w | Sayfanın boyutunu alır veya ayarlar. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. |
| pdf_core_options | [PdfCoreOptions](/imaging/python-net/aspose.imaging.fileformats.pdf/pdfcoreoptions/) | r/w | PDF çekirdek seçenekleri |
| pdf_document_info | [PdfDocumentInfo](/imaging/python-net/aspose.imaging.fileformats.pdf/pdfdocumentinfo/) | r/w | Belge için meta verileri alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| use_original_image_resolution | bool | r/w | Orijinal görüntü DPI çözünürlüğünün kullanılacağını belirten bir değeri alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | XMP meta veri kapsayıcısını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneğin üye bazlı bir klonunu oluşturur. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |


### Constructor: PdfOptions() {#PdfOptions__1}


```
 PdfOptions() 
```

Yeni bir [PdfOptions](/imaging/python-net/aspose.imaging.imageoptions/pdfoptions/) sınıfı örneği başlatır.

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


