---
title: Cache Class
type: docs
weight: 360
url: /python-net/aspose.imaging/cache/
---

**Summary:** Contains cache settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Cache

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [allocated_disk_bytes_count](#allocated_disk_bytes_count1) [static] | int | r | Gets the allocated disk bytes count. |
| [allocated_memory_bytes_count](#allocated_memory_bytes_count2) [static] | int | r | Gets the allocated in-memory bytes count. |
| cache_folder [static] | string | r/w | Gets or sets the cache folder. |
| [cache_type](#cache_type3) [static] | [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | r/w | Gets or sets the cache scheme used. |
| [exact_reallocate_only](#exact_reallocate_only4) [static] | bool | r/w | Gets or sets a value indicating whether reallocation should be exact or not. If reallocation is non exact the performance should be higher. |
| [max_disk_space_for_cache](#max_disk_space_for_cache5) [static] | int | r/w | Gets or sets the maximum available disk space for cache. The value specified is megabytes count. |
| [max_memory_for_cache](#max_memory_for_cache6) [static] | int | r/w | Gets or sets the maximum available memory for cache in memory. The value specified is megabytes count. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| set_defaults() | Sets the [Cache](/imaging/python-net/aspose.imaging/cache/) settings to defaults. |


### Property: allocated_disk_bytes_count {#allocated_disk_bytes_count1}

Gets the allocated disk bytes count.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: allocated_memory_bytes_count {#allocated_memory_bytes_count2}

Gets the allocated in-memory bytes count.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: cache_type {#cache_type3}

Gets or sets the cache scheme used.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: exact_reallocate_only {#exact_reallocate_only4}

Gets or sets a value indicating whether reallocation should be exact or not. If reallocation is non exact the performance should be higher.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_disk_space_for_cache {#max_disk_space_for_cache5}

Gets or sets the maximum available disk space for cache. The value specified is megabytes count.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_memory_for_cache {#max_memory_for_cache6}

Gets or sets the maximum available memory for cache in memory. The value specified is megabytes count.

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

# By default the cache folder is set to the local temp directory.  You can specify a different cache folder from the default this way:
Cache.set_cache_folder("C:\\Temp")
# Auto mode is flexible and efficient
Cache.set_cache_type(CacheType.AUTO)
# The default cache max value is 0, which means that there is no upper limit
Cache.set_max_disk_space_for_cache(1073741824)
Cache.set_max_memory_for_cache(1073741824)
# We do not recommend that you change the following property because it may greatly affect performance
Cache.set_exact_reallocate_only(False)

# At any time you can check how many bytes are currently allocated for the cache in memory or on disk By examining the following properties
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)

options = GifOptions()
options.palette = ColorPalette.create_with_colors([Color.red, Color.blue, Color.black, Color.white])
options.source = FileCreateSource(os.path.join(data_dir, "temp_image"), True)
with aspycore.as_of(Image.create(options, 100, 100), RasterImage) as image:
	pixels = [Color.white] * 10000
	image.save_pixels(image.bounds, pixels)
	# After executing the code above 40000 bytes are allocated to memory.
	disk_bytes = Cache.allocated_disk_bytes_count
	memory_bytes = Cache.allocated_memory_bytes_count
	print("disk_bytes", disk_bytes, "memory_bytes", memory_bytes)

# The allocation properties may be used to check whether all Aspose.Imaging objects were properly disposed. If you've forgotten to call dispose on an object the cache values will not be 0.
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)
Cache.set_cache_type(CacheType.AUTO)

```

