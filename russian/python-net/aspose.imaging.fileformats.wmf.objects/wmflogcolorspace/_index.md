---
title: "Класс WmfLogColorSpace"
type: docs
weight: 380
url: /ru/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---

**Summary:** The LogColorSpace object specifies a logical color space for the<br/>                playback device context, which can be the name of a color profile in<br/>                ASCII characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfLogColorSpace()](#WmfLogColorSpace__1) | Инициализирует новый экземпляр класса WmfLogColorSpace |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Получает или задает 32‑битное знаковое целое, которое указывает тип цветового пространства<br/>                . Оно ДОЛЖНО быть определено в перечислении LogicalColorSpace<br/>                (section 2.1.1.14). Если это значение равно LCS_sRGB или<br/>                LCS_WINDOWS_COLOR_SPACE, цветовое пространство sRGB ДОЛЖНО использоваться. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | Получает или задает объект CIEXYZTriple (section 2.2.2.7), который определяет<br/>                координаты хроматичности CIE x, y и z трех цветов,<br/>                соответствующих RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) для логического<br/>                цветового пространства, связанного с битмапой. Если поле<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) не указывает<br/>                LCS_CALIBRATED_RGB, это поле ДОЛЖНО игнорироваться. |
| filename | string | r/w | Получает или задает необязательную строку ASCII, которая указывает имя файла, содержащего профиль цвета. Если имя файла указано, и поле<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) установлено в LCS_CALIBRATED_RGB, остальные поля этой структуры ДОЛЖНЫ быть игнорированы. |
| gamma_blue | int | r/w | Получает или задает 32‑битное фиксированное точечное значение, определяющее тональную кривую отклика для синего. Если поле<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) не указывает LCS_CALIBRATED_RGB, это поле ДОЛЖНО игнорироваться. |
| gamma_green | int | r/w | Получает или задает 32‑битное фиксированное точечное значение, определяющее тональную кривую отклика для зеленого. Если поле<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) не указывает LCS_CALIBRATED_RGB, это поле ДОЛЖНО игнорироваться. |
| gamma_red | int | r/w | Получает или задает 32‑битное фиксированное точечное значение, определяющее тональную кривую отклика для красного. Если поле<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) не указывает LCS_CALIBRATED_RGB, это поле ДОЛЖНО игнорироваться. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Получает или задает 32‑битное знаковое целое, определяющее намерение отображения гаммы. Оно ДОЛЖНО быть определено в перечислении GamutMappingIntent<br/>                (section 2.1.1.11). |
| signature | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) объектов цветового пространства; оно ДОЛЖНО быть установлено в значение 0x50534F43, которое является ASCII‑кодировкой строки "PSOC". |
| size | int | r/w | Получает или задает 32‑битное беззнаковое целое, определяющее [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) этого объекта в байтах. |
| version | int | r/w | Получает или задает 32‑битное беззнаковое целое, определяющее [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) число; оно ДОЛЖНО быть 0x00000400. |


### Constructor: WmfLogColorSpace() {#WmfLogColorSpace__1}


```
 WmfLogColorSpace() 
```

Инициализирует новый экземпляр класса WmfLogColorSpace

