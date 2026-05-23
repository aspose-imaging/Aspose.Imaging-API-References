---
title: "Classe FileCreateSource"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.sources/filecreatesource/
---

**Summary:** Represents a file source for creation.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.FileCreateSource

**Inheritance:** FileSource

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [FileCreateSource(file_path)](#FileCreateSource_file_path_1) | Inizializza una nuova istanza della classe [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) |
| [FileCreateSource(file_path, is_temporal)](#FileCreateSource_file_path_is_temporal_2) | Inizializza una nuova istanza della classe [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/) |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| file_path | string | r | Ottiene il percorso del file da creare |
| is_temporal | bool | r | Ottiene un valore che indica se il file sarà temporaneo |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Ottiene il contenitore di flusso. |


### Constructor: FileCreateSource(file_path) {#FileCreateSource_file_path_1}


```
 FileCreateSource(file_path) 
```

Inizializza una nuova istanza della classe [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/)

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file da creare |


**See also:**

**[Example # 1](#example_2)**: This example creates a new Image file at some disk location as specified by `...


### Constructor: FileCreateSource(file_path, is_temporal) {#FileCreateSource_file_path_is_temporal_2}


```
 FileCreateSource(file_path, is_temporal) 
```

Inizializza una nuova istanza della classe [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/)

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file da creare |
| is_temporal | bool | Se impostato su <c>true</c> il file creato sarà temporaneo |


**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Ottiene il contenitore di flusso.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | il contenitore di flusso. |


## **Examples**
### This example creates a new Image file at some disk location as specified by `source` property of the `BmpOptions` instance. If second parameter is not passed to the constructor of `FileCreateSource`, then by default the file to be created has property `is_temporal` set to True. With `is_temporal` set to True, no file will be saved on disk at the end of execution. {#example_2}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Crea un'istanza di BmpOptions e imposta le sue varie proprietà
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24
	#Crea un'istanza di `FileCreateSource` e assegnala come `source` per l'istanza di `BmpOptions`
	#Se il secondo parametro non è fornito, per impostazione predefinita il file ha `is_temporal` impostato su True
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp")
	#Crea un'istanza di Image
	with Image.create(bmp_options, 500, 500) as image:
		#esegui qualche elaborazione dell'immagine
		image.save()

```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Crea un'istanza di `BmpOptions` e imposta le sue varie proprietà
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Crea un'istanza di `FileCreateSource` e assegnala come `source` per l'istanza di `BmpOptions`
	#Il secondo parametro `Boolean` determina se il file da creare è_temporal o meno
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Crea un'istanza di Image e inizializzala con l'istanza di BmpOptions chiamando il metodo Create
	with Image.create(bmp_options, 500, 500) as image:
		#esegui qualche elaborazione dell'immagine
		# salva tutte le modifiche
		image.save()


```

