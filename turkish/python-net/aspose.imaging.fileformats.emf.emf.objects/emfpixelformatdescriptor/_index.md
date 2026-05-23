---
title: "EmfPixelFormatDescriptor Sınıfı"
type: docs
weight: 220
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---

**Summary:** The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor__1) | EmfPixelFormatDescriptor sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| b_reserved | System.Byte | r/w | Alır veya ayarlar, üst üste bindirme ve alt katman düzlemlerinin sayısını belirtir. Bit 0'dan 3'e kadar <br/>            15'e kadar üst üste bindirme düzlemi ve bit 4'ten 7'ye kadar 15'e kadar alt katman düzlemi belirtir. |
| c_accum_alpha_bits | System.Byte | r/w | Alır veya ayarlar, birikim tamponundaki alfa bit düzlemlerinin sayısını belirtir. |
| c_accum_bits | System.Byte | r/w | Alır veya ayarlar, birikim tamponundaki toplam bit düzlemi sayısını belirtir. |
| c_accum_blue_bits | System.Byte | r/w | Alır veya ayarlar, birikim tamponundaki mavi bit düzlemi sayısını belirtir. |
| c_accum_green_bits | System.Byte | r/w | Alır veya ayarlar, birikimdeki yeşil bit düzlemi sayısını belirtir. |
| c_accum_red_bits | System.Byte | r/w | Alır veya ayarlar, birikim tamponundaki kırmızı bit düzlemi sayısını belirtir. |
| c_alpha_bits | System.Byte | r/w | Alır veya ayarlar, her RGBA renk tamponundaki alfa bit düzlemi sayısını belirtir. |
| c_alpha_shift | System.Byte | r/w | Alır veya ayarlar, her RGBA renk tamponundaki alfa bit düzlemleri için kaydırma sayısını belirtir. |
| c_aux_buffers | System.Byte | r/w | Alır veya ayarlar, yardımcı tamponların sayısını belirtir. Yardımcı tamponlar desteklenmez. |
| c_blue_bits | System.Byte | r/w | Alır veya ayarlar, her RGBA renk tamponundaki mavi bit düzlemi sayısını belirtir. |
| c_blue_shift | System.Byte | r/w | Alır veya ayarlar, her RGBA renk tamponundaki mavi bit düzlemleri için kaydırma sayısını belirtir. |
| c_color_bits | System.Byte | r/w | Alır veya ayarlar, alfa bit düzlemleri hariç RGBA piksel türleri için piksel başına bit sayısını. Renk tablo pikselleri için ise her renk tablo indeksinin boyutudur. |
| c_depth_bits | System.Byte | r/w | Alır veya ayarlar, derinlik (z-eksen) tamponunun derinliğini belirtir. |
| c_green_bits | System.Byte | r/w | Alır veya ayarlar, her RGBA renk tamponundaki yeşil bit düzlemi sayısını belirtir. |
| c_green_shift | System.Byte | r/w | Alır veya ayarlar  Her RGBA renk tamponunda yeşil bit düzlemleri için kaydırma sayısını belirtir. |
| c_red_bits | System.Byte | r/w | Alır veya ayarlar  Her RGBA renk tamponunda kırmızı bit düzlemlerinin sayısını belirtir |
| c_red_shift | System.Byte | r/w | Alır veya ayarlar  Her RGBA renk tamponunda kırmızı bit düzlemleri için bit cinsinden kaydırma sayısını belirtir. |
| c_stencil_bits | System.Byte | r/w | Alır veya ayarlar  Şablon tamponunun derinliğini belirtir. |
| dw_damage_mask | int | r/w | Alır veya ayarlar  Bu alan YOK SAYILABİLİR |
| dw_flags | int | r/w | Alır veya ayarlar  Çıktı için kullanılan piksel tamponunun özelliklerini belirten bit bayrakları <br/>            çizim yüzeyine. Bu özelliklerin tümü karşılıklı olarak <br/>            birbirini dışlamaz; bayrak kombinasyonlarına izin verilir, aksi belirtilmedikçe. |
| dw_layer_mask | int | r/w | Alır veya ayarlar  Bu alan YOK SAYILABİLİR. |
| dw_visible_mask | int | r/w | Alır veya ayarlar  Alt katman düzleminin şeffaf rengini veya indeksini belirtir. Piksel <br/>            türü RGBA olduğunda, dwVisibleMask şeffaf bir RGB renk değeridir. Piksel <br/>            türü renk indeksi olduğunda, şeffaf bir indeks değeridir. |
| layer_type | System.Byte | r/w | Alır veya ayarlar  Bu alan YOK SAYILABİLİR |
| n_size | int | r/w | Alır veya ayarlar  Bu veri yapısının boyutunu, bayt cinsinden belirten 16 bitlik bir tam sayı. |
| n_version | int | r/w | Alır veya ayarlar  0x0001 olarak ayarlanması ZORUNLU olan 16 bitlik bir tam sayı. |
| pixel_type | System.Byte | r/w | Alır veya ayarlar  piksel veri tipini<br/>            PFD_TYPE_RGBA       0x00 Piksel formatı RGBA'dır.<br/>            PFD_TYPE_COLORINDEX 0x01 Her piksel bir renk tablosundaki indekstir. |


### Constructor: EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor__1}


```
 EmfPixelFormatDescriptor() 
```

EmfPixelFormatDescriptor sınıfının yeni bir örneğini başlatır

