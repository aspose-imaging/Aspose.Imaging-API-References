---
title: "FileCreateSource Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.sources/filecreatesource/
---

**Summary:** Represents a file source for creation.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.FileCreateSource

**Inheritance:** FileSource

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [FileCreateSource(file_path)](#FileCreateSource_file_path_1) | Yeni bir [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) sınıfı örneği başlatır. |
| [FileCreateSource(file_path, is_temporal)](#FileCreateSource_file_path_is_temporal_2) | Yeni bir [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| file_path | string | r | Oluşturulacak dosya yolunu alır. |
| is_temporal | bool | r | Dosyanın geçici olup olmayacağını gösteren bir değer alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Akış kapsayıcısını alır. |


### Constructor: FileCreateSource(file_path) {#FileCreateSource_file_path_1}


```
 FileCreateSource(file_path) 
```

Yeni bir [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Oluşturulacak dosya yolu. |


**See also:**

**[Example # 1](#example_2)**: This example creates a new Image file at some disk location as specified by `...


### Constructor: FileCreateSource(file_path, is_temporal) {#FileCreateSource_file_path_is_temporal_2}


```
 FileCreateSource(file_path, is_temporal) 
```

Yeni bir [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Oluşturulacak dosya yolu. |
| is_temporal | bool | Eğer <c>true</c> olarak ayarlanırsa oluşturulan dosya geçici olacaktır. |


**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Akış kapsayıcısını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | akış kapsayıcısı. |


## **Examples**
### This example creates a new Image file at some disk location as specified by `source` property of the `BmpOptions` instance. If second parameter is not passed to the constructor of `FileCreateSource`, then by default the file to be created has property `is_temporal` set to True. With `is_temporal` set to True, no file will be saved on disk at the end of execution. {#example_2}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#BmpOptions sınıfının bir örneğini oluşturur ve çeşitli özelliklerini ayarlar
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24
	#`FileCreateSource` bir örnek oluştur ve `BmpOptions` örneği için `source` olarak ata
	#İkinci parametre geçirilmezse, varsayılan olarak dosyanın `is_temporal` özelliği True olarak ayarlanır
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp")
	#Image sınıfının bir örneğini oluşturur
	with Image.create(bmp_options, 500, 500) as image:
		#bazı görüntü işleme yap
		image.save()

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

