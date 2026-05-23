---
title: "Cache Klasse"
type: docs
weight: 360
url: /de/python-net/aspose.imaging/cache/
---

**Summary:** Contains cache settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Cache

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| [allocated_disk_bytes_count](#allocated_disk_bytes_count1) [static] | int | r | Ermittelt die zugewiesene Anzahl von Festplattenbytes. |
| [allocated_memory_bytes_count](#allocated_memory_bytes_count2) [static] | int | r | Ermittelt die zugewiesene Anzahl von Speicherbytes. |
| cache_folder [static] | string | r/w | Liest oder schreibt den Cache-Ordner. |
| [cache_type](#cache_type3) [static] | [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | r/w | Liest oder schreibt das verwendete Cache-Schema. |
| [exact_reallocate_only](#exact_reallocate_only4) [static] | bool | r/w | Liest oder schreibt einen Wert, der angibt, ob die Neuallokation exakt sein soll oder nicht. Wenn die Neuallokation nicht exakt ist, sollte die Leistung höher sein. |
| [max_disk_space_for_cache](#max_disk_space_for_cache5) [static] | int | r/w | Liest oder schreibt den maximal verfügbaren Festplattenspeicher für den Cache. Der angegebene Wert ist die Megabyte-Anzahl. |
| [max_memory_for_cache](#max_memory_for_cache6) [static] | int | r/w | Liest oder schreibt den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher. Der angegebene Wert ist die Megabyte-Anzahl. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| set_defaults() | Setzt die [Cache](/imaging/python-net/aspose.imaging/cache/) Einstellungen auf die Standardwerte. |


### Property: allocated_disk_bytes_count {#allocated_disk_bytes_count1}

Ermittelt die zugewiesene Anzahl von Festplattenbytes.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: allocated_memory_bytes_count {#allocated_memory_bytes_count2}

Ermittelt die zugewiesene Anzahl von Speicherbytes.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: cache_type {#cache_type3}

Liest oder schreibt das verwendete Cache-Schema.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: exact_reallocate_only {#exact_reallocate_only4}

Liest oder schreibt einen Wert, der angibt, ob die Neuallokation exakt sein soll oder nicht. Wenn die Neuallokation nicht exakt ist, sollte die Leistung höher sein.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_disk_space_for_cache {#max_disk_space_for_cache5}

Liest oder schreibt den maximal verfügbaren Festplattenspeicher für den Cache. Der angegebene Wert ist die Megabyte-Anzahl.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_memory_for_cache {#max_memory_for_cache6}

Liest oder schreibt den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher. Der angegebene Wert ist die Megabyte-Anzahl.

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

# Standardmäßig ist der Cache-Ordner auf das lokale Temp-Verzeichnis gesetzt. Sie können auf diese Weise einen anderen Cache-Ordner als den Standard angeben:
Cache.set_cache_folder("C:\\Temp")
# Der Auto-Modus ist flexibel und effizient
Cache.set_cache_type(CacheType.AUTO)
# Der Standardwert für die maximale Cache-Größe ist 0, was bedeutet, dass es keine Obergrenze gibt
Cache.set_max_disk_space_for_cache(1073741824)
Cache.set_max_memory_for_cache(1073741824)
# Wir empfehlen nicht, die folgende Eigenschaft zu ändern, da sie die Leistung stark beeinflussen kann
Cache.set_exact_reallocate_only(False)

# Sie können jederzeit prüfen, wie viele Bytes derzeit für den Cache im Speicher oder auf der Festplatte zugewiesen sind, indem Sie die folgenden Eigenschaften untersuchen
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)

options = GifOptions()
options.palette = ColorPalette.create_with_colors([Color.red, Color.blue, Color.black, Color.white])
options.source = FileCreateSource(os.path.join(data_dir, "temp_image"), True)
with aspycore.as_of(Image.create(options, 100, 100), RasterImage) as image:
	pixels = [Color.white] * 10000
	image.save_pixels(image.bounds, pixels)
	# Nach der Ausführung des obigen Codes werden 40000 Bytes im Speicher zugewiesen.
	disk_bytes = Cache.allocated_disk_bytes_count
	memory_bytes = Cache.allocated_memory_bytes_count
	print("disk_bytes", disk_bytes, "memory_bytes", memory_bytes)

# Die Zuweisungs‑Eigenschaften können verwendet werden, um zu prüfen, ob alle Aspose.Imaging‑Objekte ordnungsgemäß freigegeben wurden. Wenn Sie vergessen haben, dispose für ein Objekt aufzurufen, werden die Cache‑Werte nicht 0 sein.
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)
Cache.set_cache_type(CacheType.AUTO)

```

