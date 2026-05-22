---
title: "فئة Cache"
type: docs
weight: 360
url: /ar/python-net/aspose.imaging/cache/
---

**Summary:** Contains cache settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Cache

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| [allocated_disk_bytes_count](#allocated_disk_bytes_count1) [static] | int | r | يحصل على عدد بايتات القرص المخصصة. |
| [allocated_memory_bytes_count](#allocated_memory_bytes_count2) [static] | int | r | يحصل على عدد بايتات الذاكرة المخصصة. |
| cache_folder [static] | string | r/w | يحصل أو يضبط مجلد الذاكرة المؤقتة. |
| [cache_type](#cache_type3) [static] | [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | r/w | يحصل أو يضبط مخطط الذاكرة المؤقتة المستخدم. |
| [exact_reallocate_only](#exact_reallocate_only4) [static] | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان إعادة التخصيص يجب أن تكون دقيقة أم لا. إذا كانت إعادة التخصيص غير دقيقة، يجب أن يكون الأداء أعلى. |
| [max_disk_space_for_cache](#max_disk_space_for_cache5) [static] | int | r/w | يحصل أو يضبط الحد الأقصى المتاح لمساحة القرص للذاكرة المؤقتة. القيمة المحددة هي عدد الميجابايت. |
| [max_memory_for_cache](#max_memory_for_cache6) [static] | int | r/w | يحصل أو يضبط الحد الأقصى المتاح للذاكرة للذاكرة المؤقتة في الذاكرة. القيمة المحددة هي عدد الميجابايت. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| set_defaults() | يضبط إعدادات [Cache](/imaging/python-net/aspose.imaging/cache/) إلى القيم الافتراضية. |


### Property: allocated_disk_bytes_count {#allocated_disk_bytes_count1}

يحصل على عدد بايتات القرص المخصصة.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: allocated_memory_bytes_count {#allocated_memory_bytes_count2}

يحصل على عدد بايتات الذاكرة المخصصة.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: cache_type {#cache_type3}

يحصل أو يضبط مخطط الذاكرة المؤقتة المستخدم.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: exact_reallocate_only {#exact_reallocate_only4}

يحصل أو يضبط قيمة تشير إلى ما إذا كان إعادة التخصيص يجب أن تكون دقيقة أم لا. إذا كانت إعادة التخصيص غير دقيقة، يجب أن يكون الأداء أعلى.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_disk_space_for_cache {#max_disk_space_for_cache5}

يحصل أو يضبط الحد الأقصى المتاح لمساحة القرص للذاكرة المؤقتة. القيمة المحددة هي عدد الميجابايت.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_memory_for_cache {#max_memory_for_cache6}

يحصل أو يضبط الحد الأقصى المتاح للذاكرة للذاكرة المؤقتة في الذاكرة. القيمة المحددة هي عدد الميجابايت.

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

# بشكل افتراضي، يتم تعيين مجلد الذاكرة المؤقتة إلى دليل المؤقت المحلي. يمكنك تحديد مجلد ذاكرة مؤقتة مختلف عن الافتراضي بهذه الطريقة:
Cache.set_cache_folder("C:\\Temp")
# الوضع التلقائي مرن وفعال
Cache.set_cache_type(CacheType.AUTO)
# القيمة القصوى الافتراضية للذاكرة المؤقتة هي 0، مما يعني عدم وجود حد أعلى
Cache.set_max_disk_space_for_cache(1073741824)
Cache.set_max_memory_for_cache(1073741824)
# لا نوصي بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
Cache.set_exact_reallocate_only(False)

# في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة المؤقتة في الذاكرة أو على القرص من خلال فحص الخصائص التالية
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)

options = GifOptions()
options.palette = ColorPalette.create_with_colors([Color.red, Color.blue, Color.black, Color.white])
options.source = FileCreateSource(os.path.join(data_dir, "temp_image"), True)
with aspycore.as_of(Image.create(options, 100, 100), RasterImage) as image:
	pixels = [Color.white] * 10000
	image.save_pixels(image.bounds, pixels)
	# بعد تنفيذ الشيفرة أعلاه، يتم تخصيص 40000 بايت للذاكرة.
	disk_bytes = Cache.allocated_disk_bytes_count
	memory_bytes = Cache.allocated_memory_bytes_count
	print("disk_bytes", disk_bytes, "memory_bytes", memory_bytes)

# يمكن استخدام خصائص التخصيص للتحقق مما إذا كانت جميع كائنات Aspose.Imaging قد تم تحريرها بشكل صحيح. إذا نسيت استدعاء dispose على كائن، فإن قيم الذاكرة المؤقتة لن تكون 0.
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)
Cache.set_cache_type(CacheType.AUTO)

```

