---
title: "EmfHeaderExtension1 Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---

**Summary:** The HeaderExtension1 object defines the first extension to the EMF metafile header. <br/>            It adds support for a PixelFormatDescriptor object (section 2.2.22) and OpenGL <br/>            [OPENGL] records (section 2.3.9).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1__1) | EmfHeaderExtension1 sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| b_open_gl | int | r/w | Metafile içinde OpenGL komutlarının bulunup bulunmadığını gösteren 32 bit işaretsiz tamsayıyı alır veya ayarlar.<br/>            0x00000000 OpenGL kayıtları metafilde bulunmaz.<br/>            0x00000001 OpenGL kayıtları metafilde bulunur. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Cihaz birimlerinde, metafilde depolanan görüntünün etrafına çizilebilecek en küçük dikdörtgenin kapsayıcı-kapsayıcı <br/>            sınırlarını belirten WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar <br/>            . |
| baytlar | int | r/w | Metafilenin boyutunu bayt cinsinden belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| cb_pixel_format | int | r/w | PixelFormatDescriptor nesnesinin boyutunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. <br/>            Bu 0x00000000 olmalıdır. |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Referans cihazın boyutunu piksel cinsinden belirten WMF SizeL nesnesini ([MS-WMF] bölüm 2.2.2.22) alır veya ayarlar |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Metafilde depolanan görüntünün etrafını çevreleyen bir dikdörtgenin .01 milimetre <br/>            birimlerinde kapsayıcı-kapsayıcı boyutlarını belirten WMF RectL nesnesini alır veya ayarlar |
| işleyiciler | int | r/w | Metafilenin işlenmesi sırasında kullanılacak grafik nesnelerinin sayısını belirten 16 bit işaretsiz tamsayıyı alır veya ayarlar |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Referans cihazın boyutunu milimetre cinsinden belirten WMF SizeL nesnesini alır veya ayarlar |
| n_desription | int | r/w | Metafilenin içeriğinin açıklamasını içeren dizideki karakter sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar <br/>            . Açıklama dizesi yoksa bu değer sıfırdır. |
| n_pal_entries | int | r/w | Metafildeki palet giriş sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar <br/>            . Palet, EMR_EOF kaydında bulunur. |
| off_description | int | r/w | Bu kaydın başlangıcından, metafilenin içeriğinin açıklamasını içeren diziye olan offseti belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar <br/>            . |
| off_pixel_format | int | r/w | PixelFormatDescriptor nesnesine olan offseti belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar.<br/>            Piksel formatı ayarlanmamışsa bu 0x00000000 olmalıdır. |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Kayıt imzasını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu, ENHMETA_SIGNATURE OLMALIDIR, <br/>            FormatSignature enumarasyonundan (bölüm 2.1.14). |
| kayıtlar | int | r/w | Metafildeki kayıt sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar |
| rezerv | int | r/w | 0x0000 OLMAK ZORUNDA OLAN ve YOK SAYILMASI GEREKEN 16 bit işaretsiz tamsayıyı alır veya ayarlar |
| valid | bool | r | Bu [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) nesnesinin geçerli olup olmadığını gösteren bir değer alır. |
| version | int | r/w | Version (4 bayt) değerini alır veya ayarlar: EMF metafile birlikte çalışabilirliğini belirten 32 bit işaretsiz tam sayı. Bu 0x00010000 olmalıdır. |


### Constructor: EmfHeaderExtension1() {#EmfHeaderExtension1__1}


```
 EmfHeaderExtension1() 
```

EmfHeaderExtension1 sınıfının yeni bir örneğini başlatır.

