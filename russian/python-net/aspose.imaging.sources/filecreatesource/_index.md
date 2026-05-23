---
title: "Класс FileCreateSource"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.sources/filecreatesource/
---

**Summary:** Represents a file source for creation.

**Module:** [aspose.imaging.sources](/imaging/python-net/aspose.imaging.sources/)

**Full Name:** aspose.imaging.sources.FileCreateSource

**Inheritance:** FileSource

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileCreateSource(file_path)](#FileCreateSource_file_path_1) | Инициализирует новый экземпляр класса [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/). |
| [FileCreateSource(file_path, is_temporal)](#FileCreateSource_file_path_is_temporal_2) | Инициализирует новый экземпляр класса [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| file_path | string | r | Возвращает путь к файлу для создания. |
| is_temporal | bool | r | Возвращает значение, указывающее, будет ли файл временным. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stream_container()](#get_stream_container__1) | Получает контейнер потока. |


### Constructor: FileCreateSource(file_path) {#FileCreateSource_file_path_1}


```
 FileCreateSource(file_path) 
```

Инициализирует новый экземпляр класса [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу для создания. |


**See also:**

**[Example # 1](#example_2)**: This example creates a new Image file at some disk location as specified by `...


### Constructor: FileCreateSource(file_path, is_temporal) {#FileCreateSource_file_path_is_temporal_2}


```
 FileCreateSource(file_path, is_temporal) 
```

Инициализирует новый экземпляр класса [FileCreateSource](/imaging/python-net/aspose.imaging.sources/filecreatesource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу для создания. |
| is_temporal | bool | Если установить в <c>true</c>, созданный файл будет временным. |


**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: get_stream_container() {#get_stream_container__1}


```
 get_stream_container() 
```

Получает контейнер потока.

**Returns**

| Тип | Описание |
| :- | :- |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | контейнер потока. |


## **Examples**
### This example creates a new Image file at some disk location as specified by `source` property of the `BmpOptions` instance. If second parameter is not passed to the constructor of `FileCreateSource`, then by default the file to be created has property `is_temporal` set to True. With `is_temporal` set to True, no file will be saved on disk at the end of execution. {#example_2}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Создаёт экземпляр BmpOptions и задаёт его различные свойства
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24
	#Создайте экземпляр `FileCreateSource` и назначьте его в качестве `source` для экземпляра `BmpOptions`.
	#Если второй параметр не передан, то по умолчанию у файла свойство `is_temporal` установлено в True
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp")
	#Создаёт экземпляр Image
	with Image.create(bmp_options, 500, 500) as image:
		#выполнить обработку изображения.
		image.save()

```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Создайте экземпляр `BmpOptions` и задайте его различные свойства.
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Создайте экземпляр `FileCreateSource` и назначьте его в качестве `source` для экземпляра `BmpOptions`.
	#Второй параметр типа `Boolean` определяет, является ли создаваемый файл временным (is_temporal) или нет.
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Создайте экземпляр Image и инициализируйте его экземпляром BmpOptions, вызвав метод Create.
	with Image.create(bmp_options, 500, 500) as image:
		#выполнить обработку изображения.
		# сохранить все изменения.
		image.save()


```

