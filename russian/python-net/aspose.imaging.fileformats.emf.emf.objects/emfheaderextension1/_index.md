---
title: "EmfHeaderExtension1 Класс"
type: docs
weight: 90
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---

**Summary:** The HeaderExtension1 object defines the first extension to the EMF metafile header. <br/>            It adds support for a PixelFormatDescriptor object (section 2.2.22) and OpenGL <br/>            [OPENGL] records (section 2.3.9).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1__1) | Инициализирует новый экземпляр класса EmfHeaderExtension1 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| b_open_gl | int | r/w | Получает или задает 32-битное беззнаковое целое, указывающее, присутствуют ли команды OpenGL в метафайле.<br/>            0x00000000 Записи OpenGL отсутствуют в метафайле.<br/>            0x00000001 Записи OpenGL присутствуют в метафайле. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольные включительно-включительные <br/> границы в единицах устройства самого маленького прямоугольника, который может быть нарисован вокруг изображения, хранящегося в <br/> метафайле. |
| байты | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает размер метафайла в байтах. |
| cb_pixel_format | int | r/w | Получает или задает 32-битное беззнаковое целое, указывающее размер объекта PixelFormatDescriptor. <br/>            ДОЛЖНО быть 0x00000000, если формат пикселей не установлен. |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Получает или задает объект WMF SizeL ([MS-WMF] раздел 2.2.2.22), который указывает размер эталонного устройства в пикселях. |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL, который определяет прямоугольные включительно-включительные размеры в .01 миллиметра <br/> единицах прямоугольника, окружающего изображение, хранящееся в метафайле. |
| handles | int | r/w | Получает или задает 16-битное беззнаковое целое, которое указывает количество графических объектов, которые будут использоваться при обработке метафайла. |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Получает или задает объект WMF SizeL, который указывает размер эталонного устройства в миллиметрах. |
| n_desription | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает количество символов в массиве <br/> содержащем описание содержимого метафайла. Это ноль, если строка описания отсутствует. |
| n_pal_entries | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает количество записей в палитре метафайла <br/> . Палитра находится в записи EMR_EOF. |
| off_description | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает смещение от начала этой <br/> записи до массива, содержащего описание содержимого метафайла. |
| off_pixel_format | int | r/w | Получает или задает 32-битное беззнаковое целое, указывающее смещение к объекту PixelFormatDescriptor.<br/>            ДОЛЖНО быть 0x00000000, если формат пикселей не установлен. |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает сигнатуру записи. Это ДОЛЖНО быть ENHMETA_SIGNATURE, <br/> из перечисления FormatSignature (раздел 2.1.14). |
| записи | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает количество записей в метафайле. |
| зарезервировано | int | r/w | Получает или задает 16-битное беззнаковое целое, которое ДОЛЖНО быть 0x0000 и ДОЛЖНО игнорироваться |
| valid | bool | r | Возвращает значение, указывающее, является ли этот [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) действительным. |
| version | int | r/w | Получает или задает Version (4 байта): 32-битное беззнаковое целое, определяющее совместимость EMF метафайла. Это ДОЛЖНО быть 0x00010000 |


### Constructor: EmfHeaderExtension1() {#EmfHeaderExtension1__1}


```
 EmfHeaderExtension1() 
```

Инициализирует новый экземпляр класса EmfHeaderExtension1

