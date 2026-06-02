---
title: "BitmapInfoHeader Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/
---

**Summary:** Specifies BITMAPINFOHEADER. <br/>                OS Support: Windows NT, 3.1x or later.<br/>                Features: Adds 16 bpp and 32 bpp formats. Adds RLE compression.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapInfoHeader

**Inheritance:** BitmapCoreHeader

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | BITMAPCOREHEADER yani OS21XBITMAPHEADER başlık boyutu |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | Bitmap bilgi başlığı boyutu v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | Bitmap bilgi başlığı boyutu v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | Bitmap bilgi başlığı boyutu v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | Bitmap bilgi başlığı boyutu v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | Bitmap bilgi başlığı boyutu v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | Bitmap çekirdek başlık2 boyutu |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | Bitmap çekirdek başlık2 boyutu |
| bitmap_colors_important | int | r/w | Önemli palet renklerinin sayısını alır veya ayarlar. |
| bitmap_colors_used | int | r/w | Kullanılan palet renklerinin sayısını alır veya ayarlar. |
| bitmap_compression | int | r/w | Bitmap sıkıştırmasını alır veya ayarlar. |
| bitmap_height | int | r/w | Bitmap yüksekliğini alır veya ayarlar. |
| bitmap_image_size | int | r/w | Bitmap ham veri boyutunu bayt olarak alır veya ayarlar. |
| bitmap_planes | int | r/w | Düzlem sayısını alır veya ayarlar. |
| bitmap_width | int | r/w | Bitmap genişliğini alır veya ayarlar. |
| bitmap_x_pels_per_meter | int | r/w | Yatay piksel çözünürlüğünü alır veya ayarlar. |
| bitmap_y_pels_per_meter | int | r/w | Dikey piksel çözünürlüğünü alır veya ayarlar. |
| bits_per_pixel | int | r/w | Piksel başına bit sayısını alır veya ayarlar. |
| extra_bit_masks | int[] | r/w | Ek bit maskelerini alır veya ayarlar.<br/>            Yalnızca DIB başlığı BITMAPINFOHEADER olduğunda ve [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) ya [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) ya da [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA) olarak ayarlandığında bulunur. |
| header_size | int | r/w | Bu yapının bayt cinsinden boyutunu alır veya ayarlar. |


