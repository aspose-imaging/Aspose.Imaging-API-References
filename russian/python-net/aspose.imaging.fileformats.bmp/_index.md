---
title: "aspose.imaging.fileformats.bmp"
type: docs
weight: 140
url: /ru/python-net/aspose.imaging.fileformats.bmp/
---


Модуль обрабатывает обработку файлового формата Bmp.

## **Classes**
| **Class** | **Description** |
| :- | :- |
| [BitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcoreheader/) | Размеры и цветовой формат DIB.<br/>            Имя заголовка BITMAPCOREHEADER, также известное как OS21XBITMAPHEADER. |
| [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | Указывает BITMAPINFOHEADER. <br/>                Поддержка ОС: Windows NT, 3.1x и новее.<br/>                Возможности: Добавляет форматы 16 bpp и 32 bpp. Добавляет RLE‑сжатие. |
| [BitmapV4Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/) | Структура BitmapV4Header является файлом заголовка информации битмапа. Это расширенная версия структуры BITMAPINFOHEADER.<br/>            <br/>Структура BitmapV4Header расширена, чтобы позволить передавать изображение JPEG или PNG в качестве исходного изображения в StretchDIBits.<br/> |
| [BitmapV5Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/) | Структура BitmapV5Header является файлом заголовка информации битмапа. Это расширенная версия структуры BITMAPINFOHEADER.<br/>            <br/>Если bV5Height отрицательно, указывая на DIB с верхним направлением, bV5Compression должен быть либо BI_RGB, либо BI_BITFIELDS. DIB с верхним направлением не могут быть сжаты.<br/>            Интерфейс независимого управления цветом (ICM) 2.0 позволяет профилям цвета International Color Consortium (ICC) быть связанными или встроенными в DIB (DIB). <br/>            См. раздел «Using Structures» для получения дополнительной информации. Когда DIB загружается в память, данные профиля (если они присутствуют) должны следовать за таблицей цветов, <br/>            и поле bV5ProfileData должно указывать смещение данных профиля от начала структуры BITMAPV5HEADER. <br/>            Значение, хранящееся в bV5ProfileData, будет отличаться от значения, возвращаемого оператором sizeof для аргумента BITMAPV5HEADER, <br/>            потому что bV5ProfileData — это смещение в байтах от начала структуры BITMAPV5HEADER до начала данных профиля. <br/>            (Биты битмапа не следуют за таблицей цветов в памяти). Приложения должны изменять член bV5ProfileData после загрузки DIB в память.<br/>            Для упакованных DIB данные профиля должны следовать за битами битмапа, аналогично файловому формату. <br/>            Член bV5ProfileData всё равно должен указывать смещение данных профиля от начала BITMAPV5HEADER.<br/>            Приложения должны обращаться к данным профиля только когда bV5Size равен размеру BITMAPV5HEADER и bV5CSType равен PROFILE_EMBEDDED или PROFILE_LINKED.<br/> |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) | Вы можете без усилий работать с файлами Bitmap (BMP) и Device Independent Bitmap<br/>            (DIB), облегчая эффективную манипуляцию и обработку растровых<br/>            изображений. Выполняя различные операции над изображениями, этот API упрощает<br/>            рабочий процесс, предоставляя разработчикам надёжный набор инструментов для работы с форматами BMP и<br/>            DIB в их программных приложениях. |
| [Os22XBitmapHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/) | OS/2 2.x OS22XBITMAPHEADER, также известный как BITMAPCOREHEADER2. |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Указывает различные методы сжатия битмапа. |
