---
title: "MakerNote Class"
type: docs
weight: 50
url: /it/python-net/aspose.imaging.exif/makernote/
---

**Summary:** Represents a single Maker Note record.

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.MakerNote

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| nome | string | r | Ottiene il nome dell'impostazione. |
| valore | string | r | Ottiene il valore dell'impostazione. |


## **Examples**
### Access camera manufacturer maker notes in Jpeg image. {#example_222}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image
from aspose.imaging.fileformats.jpeg import JpegImage

with as_of(Image.load("Sample.jpg"), JpegImage) as image:
	for makerNote in image.exif_data.maker_notes:
		print(f"Name = {makerNote.name}, Value = {makerNote.value}")


```

