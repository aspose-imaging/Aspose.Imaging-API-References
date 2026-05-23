---
title: "Класс CdrListObjects"
type: docs
weight: 160
url: /ru/python-net/aspose.imaging.fileformats.cdr.objects/cdrlistobjects/
---

**Summary:** The cdr list objects

**Module:** [aspose.imaging.fileformats.cdr.objects](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/)

**Full Name:** aspose.imaging.fileformats.cdr.objects.CdrListObjects

**Inheritance:** CdrObjectContainer

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CdrListObjects()](#CdrListObjects__1) | Инициализирует новый экземпляр класса [CdrListObjects](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrlistobjects/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| дочерние | System.Collections.Generic.List`1[[Aspose.Imaging.FileFormats.Cdr.Objects.CdrObject]] | r | Получает или задаёт объекты. |
| disposed | bool | r | Получает значение, указывающее, удалён ли этот экземпляр. |
| document | [CdrDocument](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrdocument/) | r/w | Получает или задаёт документ. |
| fill_id | int | r/w | Получает или задает идентификатор заливки. |
| hidden | bool | r/w | Получает или задает значение, указывающее, видим ли этот [CdrObjectContainer](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer/). |
| last_child | [CdrObjectContainer](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer/) | r/w | Получает или задает последний дочерний элемент. |
| load_to_last_child | bool | r/w | Получает или задает значение, указывающее, [load to last child]. |
| opacity | float | r/w | Получает или задает непрозрачность. |
| opacity_fill_id | int | r/w | Получает или задает идентификатор заливки непрозрачности. |
| out_line_id | int | r/w | Получает или задает идентификатор внешней линии. |
| page_height | float | r/w | Получает или задает высоту страницы. |
| page_width | float | r/w | Получает или задает ширину страницы. |
| parent | [CdrObjectContainer](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer/) | r/w | Получает или задает родительский элемент. |
| style_id | int | r/w | Получает или задает идентификатор стиля. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_child_object(cdr_object)](#add_child_object_cdr_object_1) | Добавляет дочерний объект. |
| [insert_object(cdr_object)](#insert_object_cdr_object_2) | Вставляет объект |


### Constructor: CdrListObjects() {#CdrListObjects__1}


```
 CdrListObjects() 
```

Инициализирует новый экземпляр класса [CdrListObjects](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrlistobjects/).

### Method: add_child_object(cdr_object) {#add_child_object_cdr_object_1}


```
 add_child_object(cdr_object) 
```

Добавляет дочерний объект.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cdr_object | [CdrObject](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobject/) | Объект CDR. |

### Method: insert_object(cdr_object) {#insert_object_cdr_object_2}


```
 insert_object(cdr_object) 
```

Вставляет объект

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cdr_object | [CdrObject](/imaging/python-net/aspose.imaging.fileformats.cdr.objects/cdrobject/) | Объект CDR. |

