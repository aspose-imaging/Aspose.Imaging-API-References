---
title: "WmfBitmapInfoHeader Класс"
type: docs
weight: 70
url: /ru/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---

**Summary:** The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent<br/>                bitmap (DIB).

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapInfoHeader

**Inheritance:** WmfBitmapBaseHeader

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader__1) | Инициализирует новый экземпляр класса WmfBitmapInfoHeader |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_SIZE [static] | int | r | Размер структуры |
| bit_count | [DibBitCount](/imaging/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/) | r/w | Получает или задает 16-битное беззнаковое целое, определяющее формат<br/>                каждого пикселя и максимальное количество цветов в DIB. Это значение<br/>                ДОЛЖНО находиться в перечислении [WmfBitmapBaseHeader.bit_count](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) (раздел 2.1.1.3). |
| color_important | int | r/w | Получает или задает 32-битное беззнаковое целое, определяющее количество индексов цветов, необходимых для отображения<br/>                DIB.<br/>                Если значение равно нулю, требуются все индексы цветов |
| color_used | int | r/w | Получает или задает 32-битное беззнаковое целое, указывающее количество индексов в таблице цветов, используемой DIB, как<br/>                показано ниже:<br/>                Если значение равно нулю, DIB использует максимальное количество цветов, соответствующее значению BitCount.<br/>                Если значение ненулевое и значение BitCount меньше 16, это значение указывает количество цветов, используемых<br/>                DIB.<br/>                Если значение ненулевое и значение BitCount равно 16 или больше, это значение указывает размер таблицы цветов,<br/>                используемой для оптимизации производительности системной палитры.<br/>                Примечание: если значение ненулевое и превышает максимально возможный размер таблицы цветов, основанный на значении BitCount,<br/>                следует предполагать максимальный размер таблицы цветов. |
| compression | [WmfCompression](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/) | r/w | Получает или задает 32-битное беззнаковое целое, определяющее режим сжатия DIB. Это значение ДОЛЖНО находиться в<br/>                перечислении Compression (раздел 2.1.1.7).<br/>                Это значение НЕ ДОЛЖНО указывать сжатый формат, если DIB является bitmap сверху вниз, как указано значением Height. |
| header_size | int | r/w | Получает или задает 32-битное беззнаковое целое, определяющее размер этого<br/>                объекта в байтах. |
| height | int | r/w | Получает или задает 32-битное знаковое целое, определяющее высоту DIB в пикселях. Это значение НЕ ДОЛЖНО быть нулем.<br/>                Если значение положительно, DIB является bitmap снизу вверх, и его начало находится в левом нижнем углу.<br/>                Если значение отрицательно, DIB является bitmap сверху вниз, и его начало находится в левом верхнем углу. Bitmap сверху вниз<br/>                не поддерживают сжатие.<br/>                Это поле ДОЛЖНО указывать высоту распакованного файла изображения, если значение Compression указывает формат JPEG или PNG. |
| image_size | int | r/w | Получает или задает 32-битное беззнаковое целое, определяющее размер изображения в байтах.<br/>                Если значение Compression равно BI_RGB, это значение ДОЛЖНО быть нулем и ДОЛЖНО игнорироваться.<br/>                Если значение Compression равно BI_JPEG или BI_PNG, это значение ДОЛЖНО указывать размер буфера изображения JPEG или PNG,<br/>                соответственно. |
| planes | int | r/w | Получает или задает 16-битное беззнаковое целое, определяющее количество<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) для целевого устройства. Это значение ДОЛЖНО быть<br/>                0x0001. |
| width | int | r/w | Получает или задает 32-битное знаковое целое, определяющее ширину DIB в пикселях. Это значение ДОЛЖНО быть положительным.<br/>                Это поле ДОЛЖНО указывать ширину распакованного файла изображения, если значение Compression указывает формат JPEG или PNG. |
| x_pels_per_meter | int | r/w | Получает или задает 32-битное знаковое целое, определяющее горизонтальное разрешение в пикселях на метр целевого<br/>                устройства для DIB |
| y_pels_per_meter | int | r/w | Получает или задает 32-битное знаковое целое, определяющее вертикальное разрешение в пикселях на метр целевого<br/>                устройства для DIB |


### Constructor: WmfBitmapInfoHeader() {#WmfBitmapInfoHeader__1}


```
 WmfBitmapInfoHeader() 
```

Инициализирует новый экземпляр класса WmfBitmapInfoHeader

