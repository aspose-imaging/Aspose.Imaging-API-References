---
title: "Класс GifGraphicsControlBlock"
type: docs
weight: 40
url: /ru/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

**Summary:** Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__1) | Инициализирует новый экземпляр класса [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | Инициализирует новый экземпляр класса [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3) | Инициализирует новый экземпляр класса [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Указывает размер заголовка блока. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Ввод расширения. |
| EXTENSION_LABEL [static] | System.Byte | r | Метка расширения. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | Получает размер субблока. |
| delay_time | int | r/w | Получает или задает время задержки кадра, выраженное в 1/100 секунды. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | r/w | Получает или задает метод утилизации. |
| flags | System.Byte | r/w | Получает или задает флаги. |
| has_transparent_color | bool | r/w | Получает или задает значение, указывающее, имеет ли блок управления графикой прозрачный цвет. |
| is_changed | bool | r/w | Получает или задает значение, указывающее, изменён ли блок и требует ли сохранения. |
| transparent_color_index | System.Byte | r/w | Получает или задает индекс прозрачного цвета. |
| user_input_expected | bool | r/w | Получает или задает значение, указывающее, ожидается ли ввод пользователя. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_1) | Создает флаги. |
| [save(stream)](#save_stream_2) | Сохраняет блок в указанный поток. |


### Constructor: GifGraphicsControlBlock() {#GifGraphicsControlBlock__1}


```
 GifGraphicsControlBlock() 
```

Инициализирует новый экземпляр класса [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

### Constructor: GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

Инициализирует новый экземпляр класса [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| delay_time | int | Время задержки, выраженное в сотых долях секунды. |
| has_transparent_color | bool | если установлено в <c>true</c>, то _transparentColorIndex_ действителен. |
| transparent_color_index | System.Byte | Индекс прозрачного цвета. |
| requires_user_input | bool | если установлено в <c>true</c>, ввод пользователя ожидается. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | Метод утилизации. |

### Constructor: GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

Инициализирует новый экземпляр класса [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| flags | System.Byte | Флаги. |
| delay_time | int | Время задержки, выраженное в сотых долях секунды. |
| transparent_color_index | System.Byte | Индекс прозрачного цвета. |

### Method: create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_1}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

Создает флаги.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| has_transparent_color | bool | если установлено в <c>true</c>, у [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) действителен индекс прозрачного цвета. |
| requires_user_input | bool | если установлено в <c>true</c>, ввод пользователя ожидается. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | Метод утилизации. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Byte | Сгенерированные флаги. |


### Method: save(stream) {#save_stream_2}


```
 save(stream) 
```

Сохраняет блок в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save data to. |

