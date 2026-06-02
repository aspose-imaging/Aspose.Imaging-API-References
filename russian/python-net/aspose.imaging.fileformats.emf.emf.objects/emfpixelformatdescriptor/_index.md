---
title: "Класс EmfPixelFormatDescriptor"
type: docs
weight: 220
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---

**Summary:** The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor__1) | Инициализирует новый экземпляр класса EmfPixelFormatDescriptor |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| b_reserved | System.Byte | r/w | Получает или задает количество наложенных и подложенных плоскостей. Биты 0‑3 указывают <br/>            до 15 наложенных плоскостей, а биты 4‑7 указывают до 15 подложенных плоскостей. |
| c_accum_alpha_bits | System.Byte | r/w | Получает или задает количество альфа‑битовых плоскостей в буфере накопления. |
| c_accum_bits | System.Byte | r/w | Получает или задает общее количество битовых плоскостей в буфере накопления. |
| c_accum_blue_bits | System.Byte | r/w | Получает или задает количество синих битовых плоскостей в буфере накопления. |
| c_accum_green_bits | System.Byte | r/w | Получает или задает количество зеленых битовых плоскостей в накоплении. |
| c_accum_red_bits | System.Byte | r/w | Получает или задает количество красных битовых плоскостей в буфере накопления. |
| c_alpha_bits | System.Byte | r/w | Получает или задает количество альфа-битовых плоскостей в каждом цветном буфере RGBA. |
| c_alpha_shift | System.Byte | r/w | Получает или задает количество сдвигов для альфа-битовых плоскостей в каждом цветном буфере RGBA. |
| c_aux_buffers | System.Byte | r/w | Получает или задает количество вспомогательных буферов. Вспомогательные буферы не поддерживаются. |
| c_blue_bits | System.Byte | r/w | Получает или задает количество синих битовых плоскостей в каждом цветном буфере RGBA. |
| c_blue_shift | System.Byte | r/w | Получает или задает количество сдвигов для синих битовых плоскостей в каждом цветном буфере RGBA. |
| c_color_bits | System.Byte | r/w | Получает или задает количество бит на пиксель для типов пикселей RGBA, исключая альфа-битовые плоскости. Для пикселей цветовой таблицы это размер каждого индекса цветовой таблицы. |
| c_depth_bits | System.Byte | r/w | Получает или задает глубину буфера глубины (ось Z). |
| c_green_bits | System.Byte | r/w | Получает или задает количество зеленых битовых плоскостей в каждом цветном буфере RGBA. |
| c_green_shift | System.Byte | r/w | Получает или задает  Указывает количество сдвигов для зеленых битовых плоскостей в каждом буфере цвета RGBA. |
| c_red_bits | System.Byte | r/w | Получает или задает  Указывает количество красных битовых плоскостей в каждом буфере цвета RGBA |
| c_red_shift | System.Byte | r/w | Получает или задает  Указывает количество сдвигов в битах для красных битовых плоскостей в каждом буфере цвета RGBA. |
| c_stencil_bits | System.Byte | r/w | Получает или задает указывает глубину буфера трафарета. |
| dw_damage_mask | int | r/w | Получает или задает Это поле МОЖЕТ быть проигнорировано |
| dw_flags | int | r/w | Получает или задает битовые флаги, которые указывают свойства пиксельного буфера, используемого <br/>            для вывода на поверхность рисования. Эти свойства не все взаимно <br/>            исключающие; комбинации флагов допускаются, за исключением указанных иначе. |
| dw_layer_mask | int | r/w | Получает или задает Это поле МОЖЕТ быть проигнорировано. |
| dw_visible_mask | int | r/w | Получает или задает указывает прозрачный цвет или индекс подложечного плана. Когда тип пикселя <br/>            RGBA, dwVisibleMask является прозрачным значением цвета RGB. Когда тип пикселя <br/>            — индекс цвета, это прозрачное значение индекса. |
| layer_type | System.Byte | r/w | Получает или задает Это поле МОЖЕТ быть проигнорировано |
| n_size | int | r/w | Получает или задает 16-битное целое, которое указывает размер, в байтах, этой структуры данных. |
| n_version | int | r/w | Получает или задает 16-битное целое, которое ДОЛЖНО быть установлено в 0x0001. |
| pixel_type | System.Byte | r/w | Получает или задает тип данных пикселя<br/>            PFD_TYPE_RGBA       0x00 Формат пикселя — RGBA.<br/>            PFD_TYPE_COLORINDEX 0x01 Каждый пиксель — индекс в таблице цветов. |


### Constructor: EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor__1}


```
 EmfPixelFormatDescriptor() 
```

Инициализирует новый экземпляр класса EmfPixelFormatDescriptor

