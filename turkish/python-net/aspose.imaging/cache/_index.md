---
title: "Cache Sınıfı"
type: docs
weight: 360
url: /tr/python-net/aspose.imaging/cache/
---

**Summary:** Contains cache settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Cache

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| [allocated_disk_bytes_count](#allocated_disk_bytes_count1) [static] | int | r | Ayrılan disk bayt sayısını alır. |
| [allocated_memory_bytes_count](#allocated_memory_bytes_count2) [static] | int | r | Ayrılan bellek içi bayt sayısını alır. |
| cache_folder [static] | string | r/w | Cache klasörünü alır veya ayarlar. |
| [cache_type](#cache_type3) [static] | [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | r/w | Kullanılan cache şemasını alır veya ayarlar. |
| [exact_reallocate_only](#exact_reallocate_only4) [static] | bool | r/w | Yeniden tahsisatın tam olup olmayacağını gösteren bir değeri alır veya ayarlar. Yeniden tahsisat tam değilse performans daha yüksek olmalıdır. |
| [max_disk_space_for_cache](#max_disk_space_for_cache5) [static] | int | r/w | Cache için kullanılabilir maksimum disk alanını alır veya ayarlar. Belirtilen değer megabayt sayısıdır. |
| [max_memory_for_cache](#max_memory_for_cache6) [static] | int | r/w | Cache için bellek içinde kullanılabilir maksimum belleği alır veya ayarlar. Belirtilen değer megabayt sayısıdır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| set_defaults() | Önbellek [Cache](/imaging/python-net/aspose.imaging/cache/) ayarlarını varsayılanlara ayarlar. |


### Property: allocated_disk_bytes_count {#allocated_disk_bytes_count1}

Ayrılan disk bayt sayısını alır.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: allocated_memory_bytes_count {#allocated_memory_bytes_count2}

Ayrılan bellek içi bayt sayısını alır.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: cache_type {#cache_type3}

Kullanılan cache şemasını alır veya ayarlar.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: exact_reallocate_only {#exact_reallocate_only4}

Yeniden tahsisatın tam olup olmayacağını gösteren bir değeri alır veya ayarlar. Yeniden tahsisat tam değilse performans daha yüksek olmalıdır.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_disk_space_for_cache {#max_disk_space_for_cache5}

Cache için kullanılabilir maksimum disk alanını alır veya ayarlar. Belirtilen değer megabayt sayısıdır.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_memory_for_cache {#max_memory_for_cache6}

Cache için bellek içinde kullanılabilir maksimum belleği alır veya ayarlar. Belirtilen değer megabayt sayısıdır.

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

# Varsayılan olarak önbellek klasörü yerel geçici dizine ayarlanır.  Varsayılandan farklı bir önbellek klasörü bu şekilde belirtebilirsiniz:
Cache.set_cache_folder("C:\\Temp")
# Otomatik mod esnek ve verimlidir
Cache.set_cache_type(CacheType.AUTO)
# Varsayılan önbellek maksimum değeri 0'dır, bu da üst bir sınır olmadığı anlamına gelir
Cache.set_max_disk_space_for_cache(1073741824)
Cache.set_max_memory_for_cache(1073741824)
# Aşağıdaki özelliği değiştirmenizi önermiyoruz çünkü bu performansı büyük ölçüde etkileyebilir
Cache.set_exact_reallocate_only(False)

# Herhangi bir zamanda önbellek için bellekte veya diskte şu anda tahsis edilen bayt sayısını aşağıdaki özellikleri inceleyerek kontrol edebilirsiniz
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)

options = GifOptions()
options.palette = ColorPalette.create_with_colors([Color.red, Color.blue, Color.black, Color.white])
options.source = FileCreateSource(os.path.join(data_dir, "temp_image"), True)
with aspycore.as_of(Image.create(options, 100, 100), RasterImage) as image:
	pixels = [Color.white] * 10000
	image.save_pixels(image.bounds, pixels)
	# Yukarıdaki kod çalıştırıldıktan sonra 40000 bayt belleğe tahsis edilir.
	disk_bytes = Cache.allocated_disk_bytes_count
	memory_bytes = Cache.allocated_memory_bytes_count
	print("disk_bytes", disk_bytes, "memory_bytes", memory_bytes)

# Tahsis özellikleri, tüm Aspose.Imaging nesnelerinin doğru bir şekilde serbest bırakılıp bırakılmadığını kontrol etmek için kullanılabilir. Bir nesnede dispose çağırmayı unuttuysanız önbellek değerleri 0 olmayacaktır.
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)
Cache.set_cache_type(CacheType.AUTO)

```

