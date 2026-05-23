---
title: "Classe Cache"
type: docs
weight: 360
url: /it/python-net/aspose.imaging/cache/
---

**Summary:** Contains cache settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Cache

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| [allocated_disk_bytes_count](#allocated_disk_bytes_count1) [static] | int | r | Ottiene il conteggio dei byte allocati su disco. |
| [allocated_memory_bytes_count](#allocated_memory_bytes_count2) [static] | int | r | Ottiene il conteggio dei byte allocati in memoria. |
| cache_folder [static] | string | r/w | Ottiene o imposta la cartella della cache. |
| [cache_type](#cache_type3) [static] | [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | r/w | Ottiene o imposta lo schema della cache utilizzato. |
| [exact_reallocate_only](#exact_reallocate_only4) [static] | bool | r/w | Ottiene o imposta un valore che indica se la riallocazione deve essere esatta o meno. Se la riallocazione non è esatta, le prestazioni dovrebbero essere superiori. |
| [max_disk_space_for_cache](#max_disk_space_for_cache5) [static] | int | r/w | Ottiene o imposta lo spazio su disco massimo disponibile per la cache. Il valore specificato è il conteggio dei megabyte. |
| [max_memory_for_cache](#max_memory_for_cache6) [static] | int | r/w | Ottiene o imposta la memoria massima disponibile per la cache in memoria. Il valore specificato è il conteggio dei megabyte. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| set_defaults() | Imposta le impostazioni della [Cache](/imaging/python-net/aspose.imaging/cache/) ai valori predefiniti. |


### Property: allocated_disk_bytes_count {#allocated_disk_bytes_count1}

Ottiene il conteggio dei byte allocati su disco.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: allocated_memory_bytes_count {#allocated_memory_bytes_count2}

Ottiene il conteggio dei byte allocati in memoria.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: cache_type {#cache_type3}

Ottiene o imposta lo schema della cache utilizzato.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: exact_reallocate_only {#exact_reallocate_only4}

Ottiene o imposta un valore che indica se la riallocazione deve essere esatta o meno. Se la riallocazione non è esatta, le prestazioni dovrebbero essere superiori.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_disk_space_for_cache {#max_disk_space_for_cache5}

Ottiene o imposta lo spazio su disco massimo disponibile per la cache. Il valore specificato è il conteggio dei megabyte.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_memory_for_cache {#max_memory_for_cache6}

Ottiene o imposta la memoria massima disponibile per la cache in memoria. Il valore specificato è il conteggio dei megabyte.

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

# Per impostazione predefinita la cartella della cache è impostata sulla directory temporanea locale.  È possibile specificare una cartella della cache diversa da quella predefinita in questo modo:
Cache.set_cache_folder("C:\\Temp")
# La modalità automatica è flessibile ed efficiente
Cache.set_cache_type(CacheType.AUTO)
# Il valore massimo predefinito della cache è 0, il che significa che non esiste un limite superiore
Cache.set_max_disk_space_for_cache(1073741824)
Cache.set_max_memory_for_cache(1073741824)
# Non consigliamo di modificare la seguente proprietà perché potrebbe influire notevolmente sulle prestazioni
Cache.set_exact_reallocate_only(False)

# In qualsiasi momento è possibile verificare quanti byte sono attualmente allocati per la cache in memoria o su disco esaminando le seguenti proprietà
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)

options = GifOptions()
options.palette = ColorPalette.create_with_colors([Color.red, Color.blue, Color.black, Color.white])
options.source = FileCreateSource(os.path.join(data_dir, "temp_image"), True)
with aspycore.as_of(Image.create(options, 100, 100), RasterImage) as image:
	pixels = [Color.white] * 10000
	image.save_pixels(image.bounds, pixels)
	# Dopo aver eseguito il codice sopra, 40000 byte sono allocati in memoria.
	disk_bytes = Cache.allocated_disk_bytes_count
	memory_bytes = Cache.allocated_memory_bytes_count
	print("disk_bytes", disk_bytes, "memory_bytes", memory_bytes)

# Le proprietà di allocazione possono essere usate per verificare se tutti gli oggetti Aspose.Imaging sono stati correttamente rilasciati. Se hai dimenticato di chiamare dispose su un oggetto, i valori della cache non saranno 0.
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)
Cache.set_cache_type(CacheType.AUTO)

```

