---
title: "Cache 类"
type: docs
weight: 360
url: /zh/python-net/aspose.imaging/cache/
---

**Summary:** Contains cache settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Cache

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| [allocated_disk_bytes_count](#allocated_disk_bytes_count1) [static] | int | r | 获取已分配的磁盘字节计数。 |
| [allocated_memory_bytes_count](#allocated_memory_bytes_count2) [static] | int | r | 获取已分配的内存字节计数。 |
| cache_folder [static] | string | r/w | 获取或设置缓存文件夹。 |
| [cache_type](#cache_type3) [static] | [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | r/w | 获取或设置使用的缓存方案。 |
| [exact_reallocate_only](#exact_reallocate_only4) [static] | bool | r/w | 获取或设置一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高。 |
| [max_disk_space_for_cache](#max_disk_space_for_cache5) [static] | int | r/w | 获取或设置缓存的最大可用磁盘空间。指定的值为兆字节数。 |
| [max_memory_for_cache](#max_memory_for_cache6) [static] | int | r/w | 获取或设置缓存在内存中的最大可用内存。指定的值为兆字节数。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| set_defaults() | 将 [Cache](/imaging/python-net/aspose.imaging/cache/) 设置为默认值。 |


### Property: allocated_disk_bytes_count {#allocated_disk_bytes_count1}

获取已分配的磁盘字节计数。

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: allocated_memory_bytes_count {#allocated_memory_bytes_count2}

获取已分配的内存字节计数。

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: cache_type {#cache_type3}

获取或设置使用的缓存方案。

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: exact_reallocate_only {#exact_reallocate_only4}

获取或设置一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高。

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_disk_space_for_cache {#max_disk_space_for_cache5}

获取或设置缓存的最大可用磁盘空间。指定的值为兆字节数。

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_memory_for_cache {#max_memory_for_cache6}

获取或设置缓存在内存中的最大可用内存。指定的值为兆字节数。

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

# 默认情况下，缓存文件夹设置为本地临时目录。您可以通过以下方式指定不同于默认的缓存文件夹：
Cache.set_cache_folder("C:\\Temp")
# 自动模式灵活且高效
Cache.set_cache_type(CacheType.AUTO)
# 默认的缓存最大值为 0，这意味着没有上限
Cache.set_max_disk_space_for_cache(1073741824)
Cache.set_max_memory_for_cache(1073741824)
# 我们不建议更改以下属性，因为它可能会极大影响性能
Cache.set_exact_reallocate_only(False)

# 随时可以通过检查以下属性来查看当前在内存或磁盘上为缓存分配了多少字节
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)

options = GifOptions()
options.palette = ColorPalette.create_with_colors([Color.red, Color.blue, Color.black, Color.white])
options.source = FileCreateSource(os.path.join(data_dir, "temp_image"), True)
with aspycore.as_of(Image.create(options, 100, 100), RasterImage) as image:
	pixels = [Color.white] * 10000
	image.save_pixels(image.bounds, pixels)
	# 执行上述代码后，已在内存中分配了 40000 字节。
	disk_bytes = Cache.allocated_disk_bytes_count
	memory_bytes = Cache.allocated_memory_bytes_count
	print("disk_bytes", disk_bytes, "memory_bytes", memory_bytes)

# 分配属性可用于检查所有 Aspose.Imaging 对象是否已正确释放。如果您忘记对对象调用 dispose，缓存值将不会为 0。
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)
Cache.set_cache_type(CacheType.AUTO)

```

