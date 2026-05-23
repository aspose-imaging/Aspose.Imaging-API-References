---
title: "BitmapV4Header Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/
---

**Summary:** The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV4Header

**Inheritance:** BitmapInfoHeader

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
| alpha_mask | int | r/w | Her pikselin alfa bileşenini belirten renk maskesini alır veya ayarlar. |
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
| blue_mask | int | r/w | Her pikselin mavi bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI_BITFIELDS olarak ayarlandığında geçerlidir. |
| cs_type | int | r/w | DIB'in renk uzayını alır veya ayarlar. |
| endpoints | [CieCoordinatesTriple](/imaging/python-net/aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple/) | r/w | CoordinatesTriple sınıfını alır veya ayarlar. |
| extra_bit_masks | int[] | r/w | Ek bit maskelerini alır veya ayarlar.<br/>            Yalnızca DIB başlığı BITMAPINFOHEADER olduğunda ve [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) ya [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) ya da [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA) olarak ayarlandığında bulunur. |
| gamma_blue | int | r/w | Mavi gama değerini alır veya ayarlar. |
| gamma_green | int | r/w | Yeşil gama değerini alır veya ayarlar. |
| gamma_red | int | r/w | Kırmızı gama değerini alır veya ayarlar. |
| green_mask | int | r/w | Her pikselin yeşil bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI_BITFIELDS olarak ayarlandığında geçerlidir. |
| header_size | int | r/w | Bu yapının bayt cinsinden boyutunu alır veya ayarlar. |
| red_mask | int | r/w | Her pikselin kırmızı bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI_BITFIELDS olarak ayarlandığında geçerlidir. |


