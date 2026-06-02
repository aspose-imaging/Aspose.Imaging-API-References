---
title: "Classe Cache"
type: docs
weight: 360
url: /fr/python-net/aspose.imaging/cache/
---

**Summary:** Contains cache settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Cache

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [allocated_disk_bytes_count](#allocated_disk_bytes_count1) [static] | int | r | Obtient le nombre d'octets disque alloués. |
| [allocated_memory_bytes_count](#allocated_memory_bytes_count2) [static] | int | r | Obtient le nombre d'octets en mémoire alloués. |
| cache_folder [static] | string | r/w | Obtient ou définit le dossier du cache. |
| [cache_type](#cache_type3) [static] | [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | r/w | Obtient ou définit le schéma de cache utilisé. |
| [exact_reallocate_only](#exact_reallocate_only4) [static] | bool | r/w | Obtient ou définit une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être supérieures. |
| [max_disk_space_for_cache](#max_disk_space_for_cache5) [static] | int | r/w | Obtient ou définit l'espace disque maximal disponible pour le cache. La valeur spécifiée correspond au nombre de mégaoctets. |
| [max_memory_for_cache](#max_memory_for_cache6) [static] | int | r/w | Obtient ou définit la mémoire maximale disponible pour le cache en mémoire. La valeur spécifiée correspond au nombre de mégaoctets. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| set_defaults() | Définit les paramètres du [Cache](/imaging/python-net/aspose.imaging/cache/) aux valeurs par défaut. |


### Property: allocated_disk_bytes_count {#allocated_disk_bytes_count1}

Obtient le nombre d'octets disque alloués.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: allocated_memory_bytes_count {#allocated_memory_bytes_count2}

Obtient le nombre d'octets en mémoire alloués.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: cache_type {#cache_type3}

Obtient ou définit le schéma de cache utilisé.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: exact_reallocate_only {#exact_reallocate_only4}

Obtient ou définit une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être supérieures.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_disk_space_for_cache {#max_disk_space_for_cache5}

Obtient ou définit l'espace disque maximal disponible pour le cache. La valeur spécifiée correspond au nombre de mégaoctets.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_memory_for_cache {#max_memory_for_cache6}

Obtient ou définit la mémoire maximale disponible pour le cache en mémoire. La valeur spécifiée correspond au nombre de mégaoctets.

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

# Par défaut, le dossier du cache est défini sur le répertoire temporaire local. Vous pouvez spécifier un autre dossier de cache que la valeur par défaut de cette manière :
Cache.set_cache_folder("C:\\Temp")
# Le mode automatique est flexible et efficace
Cache.set_cache_type(CacheType.AUTO)
# La valeur maximale du cache par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
Cache.set_max_disk_space_for_cache(1073741824)
Cache.set_max_memory_for_cache(1073741824)
# Nous ne recommandons pas de modifier la propriété suivante car cela pourrait fortement affecter les performances
Cache.set_exact_reallocate_only(False)

# À tout moment, vous pouvez vérifier le nombre d'octets actuellement alloués au cache en mémoire ou sur le disque en examinant les propriétés suivantes
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)

options = GifOptions()
options.palette = ColorPalette.create_with_colors([Color.red, Color.blue, Color.black, Color.white])
options.source = FileCreateSource(os.path.join(data_dir, "temp_image"), True)
with aspycore.as_of(Image.create(options, 100, 100), RasterImage) as image:
	pixels = [Color.white] * 10000
	image.save_pixels(image.bounds, pixels)
	# Après l'exécution du code ci‑dessus, 40000 octets sont alloués en mémoire.
	disk_bytes = Cache.allocated_disk_bytes_count
	memory_bytes = Cache.allocated_memory_bytes_count
	print("disk_bytes", disk_bytes, "memory_bytes", memory_bytes)

# Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.Imaging ont été correctement libérés. Si vous avez oublié d'appeler dispose sur un objet, les valeurs du cache ne seront pas à 0.
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)
Cache.set_cache_type(CacheType.AUTO)

```

