---
title: "Класс Cache"
type: docs
weight: 360
url: /ru/python-net/aspose.imaging/cache/
---

**Summary:** Contains cache settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Cache

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [allocated_disk_bytes_count](#allocated_disk_bytes_count1) [static] | int | r | Возвращает количество выделенных байтов на диске. |
| [allocated_memory_bytes_count](#allocated_memory_bytes_count2) [static] | int | r | Возвращает количество выделенных байтов в памяти. |
| cache_folder [static] | string | r/w | Получает или задает папку кэша. |
| [cache_type](#cache_type3) [static] | [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | r/w | Получает или задает используемую схему кэша. |
| [exact_reallocate_only](#exact_reallocate_only4) [static] | bool | r/w | Получает или задает значение, указывающее, должна ли переалокация быть точной или нет. Если переалокация неточная, производительность должна быть выше. |
| [max_disk_space_for_cache](#max_disk_space_for_cache5) [static] | int | r/w | Получает или задает максимальное доступное дисковое пространство для кэша. Указанное значение — количество мегабайт. |
| [max_memory_for_cache](#max_memory_for_cache6) [static] | int | r/w | Получает или задает максимальную доступную память для кэша в оперативной памяти. Указанное значение — количество мегабайт. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| set_defaults() | Устанавливает параметры [Cache](/imaging/python-net/aspose.imaging/cache/) по умолчанию. |


### Property: allocated_disk_bytes_count {#allocated_disk_bytes_count1}

Возвращает количество выделенных байтов на диске.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: allocated_memory_bytes_count {#allocated_memory_bytes_count2}

Возвращает количество выделенных байтов в памяти.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: cache_type {#cache_type3}

Получает или задает используемую схему кэша.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: exact_reallocate_only {#exact_reallocate_only4}

Получает или задает значение, указывающее, должна ли переалокация быть точной или нет. Если переалокация неточная, производительность должна быть выше.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_disk_space_for_cache {#max_disk_space_for_cache5}

Получает или задает максимальное доступное дисковое пространство для кэша. Указанное значение — количество мегабайт.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_memory_for_cache {#max_memory_for_cache6}

Получает или задает максимальную доступную память для кэша в оперативной памяти. Указанное значение — количество мегабайт.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


## **Examples**
### This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.CacheType {#example_0}
``` python

import aspose.pycore as aspycore
from aspose.imaging import *
from aspose.imaging.brushes import *
from aspose.imaging.fileformats.jpeg import *
from aspose.imaging.imageoptions import *
from aspose.imaging.sources import *
import os

# По умолчанию папка кэша устанавливается в локальный временный каталог. Вы можете указать другую папку кэша, отличную от значения по умолчанию, следующим образом:
Cache.set_cache_folder("C:\\Temp")
# Автоматический режим гибок и эффективен
Cache.set_cache_type(CacheType.AUTO)
# Значение максимального размера кэша по умолчанию равно 0, что означает отсутствие верхнего предела
Cache.set_max_disk_space_for_cache(1073741824)
Cache.set_max_memory_for_cache(1073741824)
# Мы не рекомендуем изменять следующее свойство, так как это может сильно повлиять на производительность
Cache.set_exact_reallocate_only(False)

# В любой момент вы можете проверить, сколько байт в настоящее время выделено для кэша в памяти или на диске, изучив следующие свойства
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)

options = GifOptions()
options.palette = ColorPalette.create_with_colors([Color.red, Color.blue, Color.black, Color.white])
options.source = FileCreateSource(os.path.join(data_dir, "temp_image"), True)
with aspycore.as_of(Image.create(options, 100, 100), RasterImage) as image:
	pixels = [Color.white] * 10000
	image.save_pixels(image.bounds, pixels)
	# После выполнения приведённого кода 40000 байт выделяется в память.
	disk_bytes = Cache.allocated_disk_bytes_count
	memory_bytes = Cache.allocated_memory_bytes_count
	print("disk_bytes", disk_bytes, "memory_bytes", memory_bytes)

# Свойства выделения могут использоваться для проверки, были ли все объекты Aspose.Imaging правильно освобождены. Если вы забыли вызвать dispose у объекта, значения кэша не будут равны 0.
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)
Cache.set_cache_type(CacheType.AUTO)

```

