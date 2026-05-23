---
title: "Clase Cache"
type: docs
weight: 360
url: /es/python-net/aspose.imaging/cache/
---

**Summary:** Contains cache settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Cache

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| [allocated_disk_bytes_count](#allocated_disk_bytes_count1) [static] | int | r | Obtiene el recuento de bytes asignados en disco. |
| [allocated_memory_bytes_count](#allocated_memory_bytes_count2) [static] | int | r | Obtiene el recuento de bytes asignados en memoria. |
| cache_folder [static] | string | r/w | Obtiene o establece la carpeta de caché. |
| [cache_type](#cache_type3) [static] | [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | r/w | Obtiene o establece el esquema de caché utilizado. |
| [exact_reallocate_only](#exact_reallocate_only4) [static] | bool | r/w | Obtiene o establece un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta, el rendimiento debería ser mayor. |
| [max_disk_space_for_cache](#max_disk_space_for_cache5) [static] | int | r/w | Obtiene o establece el espacio máximo disponible en disco para la caché. El valor especificado es el recuento de megabytes. |
| [max_memory_for_cache](#max_memory_for_cache6) [static] | int | r/w | Obtiene o establece la memoria máxima disponible para la caché en memoria. El valor especificado es el recuento de megabytes. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| set_defaults() | Establece la configuración de la [Cache](/imaging/python-net/aspose.imaging/cache/) a los valores predeterminados. |


### Property: allocated_disk_bytes_count {#allocated_disk_bytes_count1}

Obtiene el recuento de bytes asignados en disco.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: allocated_memory_bytes_count {#allocated_memory_bytes_count2}

Obtiene el recuento de bytes asignados en memoria.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: cache_type {#cache_type3}

Obtiene o establece el esquema de caché utilizado.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: exact_reallocate_only {#exact_reallocate_only4}

Obtiene o establece un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta, el rendimiento debería ser mayor.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_disk_space_for_cache {#max_disk_space_for_cache5}

Obtiene o establece el espacio máximo disponible en disco para la caché. El valor especificado es el recuento de megabytes.

**See also:**

**[Example # 1](#example_0)**: This example demonstrates the use of aspose.imaging.Cache, aspose.imaging.Cac...


### Property: max_memory_for_cache {#max_memory_for_cache6}

Obtiene o establece la memoria máxima disponible para la caché en memoria. El valor especificado es el recuento de megabytes.

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

# Por defecto, la carpeta de caché se establece en el directorio temporal local. Puedes especificar una carpeta de caché diferente a la predeterminada de esta manera:
Cache.set_cache_folder("C:\\Temp")
# El modo automático es flexible y eficiente
Cache.set_cache_type(CacheType.AUTO)
# El valor máximo predeterminado de la caché es 0, lo que significa que no hay límite superior
Cache.set_max_disk_space_for_cache(1073741824)
Cache.set_max_memory_for_cache(1073741824)
# No recomendamos que cambies la siguiente propiedad porque puede afectar significativamente el rendimiento
Cache.set_exact_reallocate_only(False)

# En cualquier momento puedes comprobar cuántos bytes están actualmente asignados a la caché en memoria o en disco examinando las siguientes propiedades
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)

options = GifOptions()
options.palette = ColorPalette.create_with_colors([Color.red, Color.blue, Color.black, Color.white])
options.source = FileCreateSource(os.path.join(data_dir, "temp_image"), True)
with aspycore.as_of(Image.create(options, 100, 100), RasterImage) as image:
	pixels = [Color.white] * 10000
	image.save_pixels(image.bounds, pixels)
	# Después de ejecutar el código anterior, se asignan 40000 bytes a la memoria.
	disk_bytes = Cache.allocated_disk_bytes_count
	memory_bytes = Cache.allocated_memory_bytes_count
	print("disk_bytes", disk_bytes, "memory_bytes", memory_bytes)

# Las propiedades de asignación pueden usarse para comprobar si todos los objetos **Aspose.Imaging** fueron eliminados correctamente. Si has olvidado llamar a dispose en un objeto, los valores de la caché no serán 0.
l1 = Cache.allocated_disk_bytes_count
l2 = Cache.allocated_memory_bytes_count
print("allocated_disk_bytes_count", l1, "allocated_memory_bytes_count", l2)
Cache.set_cache_type(CacheType.AUTO)

```

