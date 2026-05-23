---
title: "PngLoadOptions Класс"
type: docs
weight: 70
url: /ru/python-net/aspose.imaging.imageloadoptions/pngloadoptions/
---

**Summary:** The png load options.

**Module:** [aspose.imaging.imageloadoptions](/imaging/python-net/aspose.imaging.imageloadoptions/)

**Full Name:** aspose.imaging.imageloadoptions.PngLoadOptions

**Inheritance:** LoadOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PngLoadOptions()](#PngLoadOptions__1) | Инициализирует новый экземпляр класса [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| concurrent_image_processing | bool | r/w | Получает или задает значение, указывающее, включена ли [concurrent image processing]. |
| data_background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Получает или задает фон [Color](/imaging/python-net/aspose.imaging/color/) изображения [Image](/imaging/python-net/aspose.imaging/image/). |
| data_recovery_mode | [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | r/w | Получает или задает режим восстановления данных. |
| [strict_mode](#strict_mode1) | bool | r/w | Получает или задает значение, указывающее, включен ли [strict mode]. |
| use_icc_profile_conversion | bool | r/w | Получает или задает значение, указывающее, следует ли применять преобразование ICC‑профиля. |


### Constructor: PngLoadOptions() {#PngLoadOptions__1}


```
 PngLoadOptions() 
```

Инициализирует новый экземпляр класса [PngLoadOptions](/imaging/python-net/aspose.imaging.imageloadoptions/pngloadoptions/) .

### Property: strict_mode {#strict_mode1}

Получает или задает значение, указывающее, включен ли [strict mode].

**See also:**

**[Example # 1](#example_186)**: The following example shows how to read PNG file in a strict mode. The strict...


## **Examples**
### The following example shows how to read PNG file in a strict mode. The strict mode allows to find potential problems in PNG images, e.g. unrecognized data blocks, unexpected end of file. Such files still can be opened in default (non-strict) mode by `aspose.imaging` and by common viewers as well. However any attempts to open them in the strict mode cause a corresponding exception. {#example_186}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.imageloadoptions import PngLoadOptions
from os.path import join as path_join


dir_ = "c:\\testdata"
input_file_name = path_join(dir_, "FC5F1998104EB92469CB14070628073616BB28F9.png")
output_file_name = input_file_name + ".png"
# Режим по умолчанию (нестрогий) - успешное чтение.
with Image.load(input_file_name) as image:
	image.save(output_file_name, PngOptions())

# Строгий режим - ImageLoadException : Неожиданный конец файла.
obj_init = PngLoadOptions()
obj_init.strict_mode = True
with Image.load(input_file_name, obj_init) as image:
	image.save(output_file_name, PngOptions())


```

