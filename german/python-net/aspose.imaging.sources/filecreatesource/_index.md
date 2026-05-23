---
title: "FileCreateSource Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.sources/filecreatesource/
---

**Summary:** Represents a file source for creation.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.FileCreateSource

**Inheritance:** FileSource

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [FileCreateSource(file_path)](#FileCreateSource_file_path_1) | Initialisiert eine neue Instanz der [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) Klasse. |
| [FileCreateSource(file_path, is_temporal)](#FileCreateSource_file_path_is_temporal_2) | Initialisiert eine neue Instanz der [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| file_path | string | r | Ermittelt den Dateipfad zum Erstellen. |
| is_temporal | bool | r | Ermittelt einen Wert, der angibt, ob die Datei temporär sein wird. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Ruft den Stream-Container ab. |


### Constructor: FileCreateSource(file_path) {#FileCreateSource_file_path_1}


```
 FileCreateSource(file_path) 
```

Initialisiert eine neue Instanz der [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad zum Erstellen. |


**See also:**

**[Example # 1](#example_2)**: This example creates a new Image file at some disk location as specified by `...


### Constructor: FileCreateSource(file_path, is_temporal) {#FileCreateSource_file_path_is_temporal_2}


```
 FileCreateSource(file_path, is_temporal) 
```

Initialisiert eine neue Instanz der [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad zum Erstellen. |
| is_temporal | bool | Wenn auf <c>true</c> gesetzt, wird die erstellte Datei temporär sein. |


**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Ruft den Stream-Container ab.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | der Stream-Container. |


## **Examples**
### This example creates a new Image file at some disk location as specified by `source` property of the `BmpOptions` instance. If second parameter is not passed to the constructor of `FileCreateSource`, then by default the file to be created has property `is_temporal` set to True. With `is_temporal` set to True, no file will be saved on disk at the end of execution. {#example_2}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Erstellt eine Instanz von BmpOptions und setzt deren verschiedene Eigenschaften
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24
	#Erstelle eine Instanz von `FileCreateSource` und weise sie als `source` für die Instanz von `BmpOptions` zu
	#Wenn der zweite Parameter nicht übergeben wird, hat die Datei standardmäßig `is_temporal` auf True gesetzt.
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp")
	#Erstellt eine Instanz von Image
	with Image.create(bmp_options, 500, 500) as image:
		#Führe einige Bildverarbeitungen durch
		image.save()

```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Erstelle eine Instanz von `BmpOptions` und setze ihre verschiedenen Eigenschaften
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Erstelle eine Instanz von `FileCreateSource` und weise sie als `source` für die Instanz von `BmpOptions` zu
	#Der zweite `Boolean`-Parameter bestimmt, ob die zu erstellende Datei temporär ist oder nicht
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Erstelle eine Instanz von Image und initialisiere sie mit einer Instanz von BmpOptions, indem du die Create-Methode aufrufst
	with Image.create(bmp_options, 500, 500) as image:
		#Führe einige Bildverarbeitungen durch
		# Speichere alle Änderungen
		image.save()


```

