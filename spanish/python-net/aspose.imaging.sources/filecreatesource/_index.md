---
title: "Clase FileCreateSource"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.sources/filecreatesource/
---

**Summary:** Represents a file source for creation.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.FileCreateSource

**Inheritance:** FileSource

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [FileCreateSource(file_path)](#FileCreateSource_file_path_1) | Inicializa una nueva instancia de la clase [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/). |
| [FileCreateSource(file_path, is_temporal)](#FileCreateSource_file_path_is_temporal_2) | Inicializa una nueva instancia de la clase [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| file_path | string | r | Obtiene la ruta del archivo a crear. |
| is_temporal | bool | r | Obtiene un valor que indica si el archivo será temporal. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Obtiene el contenedor de flujo. |


### Constructor: FileCreateSource(file_path) {#FileCreateSource_file_path_1}


```
 FileCreateSource(file_path) 
```

Inicializa una nueva instancia de la clase [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo a crear. |


**See also:**

**[Example # 1](#example_2)**: This example creates a new Image file at some disk location as specified by `...


### Constructor: FileCreateSource(file_path, is_temporal) {#FileCreateSource_file_path_is_temporal_2}


```
 FileCreateSource(file_path, is_temporal) 
```

Inicializa una nueva instancia de la clase [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo a crear. |
| is_temporal | bool | Si se establece en <c>true</c> el archivo creado será temporal. |


**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Obtiene el contenedor de flujo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | el contenedor de flujo. |


## **Examples**
### This example creates a new Image file at some disk location as specified by `source` property of the `BmpOptions` instance. If second parameter is not passed to the constructor of `FileCreateSource`, then by default the file to be created has property `is_temporal` set to True. With `is_temporal` set to True, no file will be saved on disk at the end of execution. {#example_2}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Crea una instancia de BmpOptions y establece sus diversas propiedades
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24
	#Crea una instancia de `FileCreateSource` y asígnala como `source` para la instancia de `BmpOptions`
	#Si no se pasa el segundo parámetro, entonces por defecto el archivo tiene `is_temporal` establecido en True
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp")
	#Crea una instancia de Image
	with Image.create(bmp_options, 500, 500) as image:
		#realiza algún procesamiento de imagen
		image.save()

```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Crea una instancia de `BmpOptions` y establece sus diversas propiedades
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Crea una instancia de `FileCreateSource` y asígnala como `source` para la instancia de `BmpOptions`
	#El segundo parámetro `Boolean` determina si el archivo a crear es_temporal o no
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Crea una instancia de Image e inicialízala con una instancia de BmpOptions llamando al método Create
	with Image.create(bmp_options, 500, 500) as image:
		#realiza algún procesamiento de imagen
		# guarda todos los cambios
		image.save()


```

