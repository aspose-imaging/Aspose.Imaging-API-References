---
title: "Cache-klass"
type: docs
weight: 360
url: /sv/python-net/aspose.imaging/cache/
---

**Summary:** Contains cache settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Cache

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [allocated_disk_bytes_count](#allocated_disk_bytes_count1) [static] | int | r | Hämtar antalet tilldelade diskbyte. |
| [allocated_memory_bytes_count](#allocated_memory_bytes_count2) [static] | int | r | Hämtar antalet tilldelade minnesbyte. |
| cache_folder [static] | string | r/w | Hämtar eller anger cache-mappen. |
| [cache_type](#cache_type3) [static] | [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | r/w | Hämtar eller anger det använda cache-schemat. |
| [exact_reallocate_only](#exact_reallocate_only4) [static] | bool | r/w | Hämtar eller anger ett värde som indikerar om omallokering ska vara exakt eller inte. Om omallokeringen inte är exakt bör prestandan vara högre. |
| [max_disk_space_for_cache](#max_disk_space_for_cache5) [static] | int | r/w | Hämtar eller anger det maximala tillgängliga diskutrymmet för cache. Det angivna värdet är antalet megabyte. |
| [max_memory_for_cache](#max_memory_for_cache6) [static] | int | r/w | Hämtar eller anger det maximala tillgängliga minnet för cache i minnet. Det angivna värdet är antalet megabyte. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| set_defaults() | Ställer in [Cache](/imaging/python-net/aspose.imaging/cache/) inställningarna till standardvärden. |


### Property: allocated_disk_bytes_count {#allocated_disk_bytes_count1}

Hämtar antalet tilldelade diskbyte.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: allocated_memory_bytes_count {#allocated_memory_bytes_count2}

Hämtar antalet tilldelade minnesbyte.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: cache_type {#cache_type3}

Hämtar eller anger det använda cache-schemat.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: exact_reallocate_only {#exact_reallocate_only4}

Hämtar eller anger ett värde som indikerar om omallokering ska vara exakt eller inte. Om omallokeringen inte är exakt bör prestandan vara högre.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_disk_space_for_cache {#max_disk_space_for_cache5}

Hämtar eller anger det maximala tillgängliga diskutrymmet för cache. Det angivna värdet är antalet megabyte.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_memory_for_cache {#max_memory_for_cache6}

Hämtar eller anger det maximala tillgängliga minnet för cache i minnet. Det angivna värdet är antalet megabyte.

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

# Som standard är cache-mappen inställd på den lokala temp-katalogen.  Du kan ange en annan cache-mapp än standard på detta sätt:
Cache.set_cache_folder("C:\\Temp")
# Automatiskt läge är flexibelt och effektivt
Cache.set_cache_type(CacheType.AUTO)
# Standardvärdet för cache max är 0, vilket betyder att det inte finns någon övre gräns
Cache.set_max_disk_space_for_cache(1073741824)
Cache.set_max_memory_for_cache(1073741824)
# Vi rekommenderar inte att du ändrar följande egenskap eftersom den kan påverka prestandan kraftigt
Cache.set_exact_reallocate_only(False)

# När som helst kan du kontrollera hur många byte som för närvarande är allokerade för cachen i minnet eller på disk genom att undersöka följande egenskaper
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)

options = GifOptions()
options.palette = ColorPalette.create_with_colors([Color.red, Color.blue, Color.black, Color.white])
options.source = FileCreateSource(os.path.join(data_dir, "temp_image"), True)
with aspycore.as_of(Image.create(options, 100, 100), RasterImage) as image:
	pixels = [Color.white] * 10000
	image.save_pixels(image.bounds, pixels)
	# Efter att ha kört koden ovan är 40000 byte allokerade till minnet.
	disk_bytes = Cache.allocated_disk_bytes_count
	memory_bytes = Cache.allocated_memory_bytes_count
	print("disk_bytes", disk_bytes, "memory_bytes", memory_bytes)

# Allokeringsegenskaperna kan användas för att kontrollera om alla Aspose.Imaging-objekt har frigjorts korrekt. Om du har glömt att anropa dispose på ett objekt kommer cachevärdena inte att vara 0.
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)
Cache.set_cache_type(CacheType.AUTO)

```

