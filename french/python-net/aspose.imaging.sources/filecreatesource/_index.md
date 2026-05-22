---
title: "Classe FileCreateSource"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.sources/filecreatesource/
---

**Summary:** Represents a file source for creation.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.FileCreateSource

**Inheritance:** FileSource

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileCreateSource(file_path)](#FileCreateSource_file_path_1) | Initialise une nouvelle instance de la classe [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/). |
| [FileCreateSource(file_path, is_temporal)](#FileCreateSource_file_path_is_temporal_2) | Initialise une nouvelle instance de la classe [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| file_path | string | r | Obtient le chemin du fichier à créer. |
| is_temporal | bool | r | Obtient une valeur indiquant si le fichier sera temporaire. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Obtient le conteneur de flux. |


### Constructor: FileCreateSource(file_path) {#FileCreateSource_file_path_1}


```
 FileCreateSource(file_path) 
```

Initialise une nouvelle instance de la classe [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier à créer. |


**See also:**

**[Example # 1](#example_2)**: This example creates a new Image file at some disk location as specified by `...


### Constructor: FileCreateSource(file_path, is_temporal) {#FileCreateSource_file_path_is_temporal_2}


```
 FileCreateSource(file_path, is_temporal) 
```

Initialise une nouvelle instance de la classe [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier à créer. |
| is_temporal | bool | Si défini sur <c>true</c> le fichier créé sera temporaire. |


**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Obtient le conteneur de flux.

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | le conteneur de flux. |


## **Examples**
### This example creates a new Image file at some disk location as specified by `source` property of the `BmpOptions` instance. If second parameter is not passed to the constructor of `FileCreateSource`, then by default the file to be created has property `is_temporal` set to True. With `is_temporal` set to True, no file will be saved on disk at the end of execution. {#example_2}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Crée une instance de BmpOptions et définit ses différentes propriétés
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24
	#Créez une instance de `FileCreateSource` et assignez‑la comme `source` pour l'instance de `BmpOptions`
	#Si le deuxième paramètre n'est pas fourni, le fichier a par défaut `is_temporal` défini sur True
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp")
	#Crée une instance de Image
	with Image.create(bmp_options, 500, 500) as image:
		#effectuer un traitement d'image
		image.save()

```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Créez une instance de `BmpOptions` et définissez ses différentes propriétés
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Créez une instance de `FileCreateSource` et assignez‑la comme `source` pour l'instance de `BmpOptions`
	#Le deuxième paramètre `Boolean` détermine si le fichier à créer est is_temporal ou non
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Créez une instance de Image et initialisez‑la avec une instance de BmpOptions en appelant la méthode Create
	with Image.create(bmp_options, 500, 500) as image:
		#effectuer un traitement d'image
		# enregistrer toutes les modifications
		image.save()


```

