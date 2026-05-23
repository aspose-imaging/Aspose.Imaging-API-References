---
title: "FileCreateSource‑klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.sources/filecreatesource/
---

**Summary:** Represents a file source for creation.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.FileCreateSource

**Inheritance:** FileSource

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileCreateSource(file_path)](#FileCreateSource_file_path_1) | Initierar en ny instans av klassen [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/). |
| [FileCreateSource(file_path, is_temporal)](#FileCreateSource_file_path_is_temporal_2) | Initierar en ny instans av klassen [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| file_path | string | r | Hämtar filsökvägen att skapa. |
| is_temporal | bool | r | Hämtar ett värde som indikerar om filen kommer att vara temporär. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Hämtar strömbehållaren. |


### Constructor: FileCreateSource(file_path) {#FileCreateSource_file_path_1}


```
 FileCreateSource(file_path) 
```

Initierar en ny instans av klassen [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att skapa. |


**See also:**

**[Example # 1](#example_2)**: This example creates a new Image file at some disk location as specified by `...


### Constructor: FileCreateSource(file_path, is_temporal) {#FileCreateSource_file_path_is_temporal_2}


```
 FileCreateSource(file_path, is_temporal) 
```

Initierar en ny instans av klassen [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att skapa. |
| is_temporal | bool | Om den är inställd på <c>true</c> kommer den skapade filen att vara temporär. |


**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Hämtar strömbehållaren.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | strömbehållaren. |


## **Examples**
### This example creates a new Image file at some disk location as specified by `source` property of the `BmpOptions` instance. If second parameter is not passed to the constructor of `FileCreateSource`, then by default the file to be created has property `is_temporal` set to True. With `is_temporal` set to True, no file will be saved on disk at the end of execution. {#example_2}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Skapar en instans av BmpOptions och sätter dess olika egenskaper
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24
	#Skapa en instans av `FileCreateSource` och tilldela den som `source` för instansen av `BmpOptions`
	#Om den andra parametern inte anges, har filen som standard `is_temporal` satt till True
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp")
	#Skapar en instans av Image
	with Image.create(bmp_options, 500, 500) as image:
		#utför någon bildbehandling
		image.save()

```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Skapa en instans av `BmpOptions` och ange dess olika egenskaper
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Skapa en instans av `FileCreateSource` och tilldela den som `source` för instansen av `BmpOptions`
	#Den andra `Boolean`-parametern bestämmer om filen som ska skapas är_temporal eller inte
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Skapa en instans av Image och initiera den med en instans av BmpOptions genom att anropa Create-metoden
	with Image.create(bmp_options, 500, 500) as image:
		#utför någon bildbehandling
		# spara alla ändringar
		image.save()


```

