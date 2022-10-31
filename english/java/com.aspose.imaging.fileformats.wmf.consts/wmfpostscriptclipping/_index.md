---
title: WmfPostScriptClipping
second_title: Aspose.Imaging for Java API Reference
description: The PostScriptClipping Enumeration defines functions that can be applied to the clipping path used for PostScript output.
type: docs
weight: 32
url: /java/com.aspose.imaging.fileformats.wmf.consts/wmfpostscriptclipping/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPostScriptClipping extends System.Enum
```

The PostScriptClipping Enumeration defines functions that can be applied to the clipping path used for PostScript output.
## Fields

| Field | Description |
| --- | --- |
| [CLIP_SAVE](#CLIP-SAVE) | Saves the current PostScript clipping path. |
| [CLIP_RESTORE](#CLIP-RESTORE) | Restores the PostScript clipping path to the last clipping path that was saved by a previous CLIP\_SAVE function applied by a CLIP\_TO\_PATH record (section 2.3.6.6). |
| [CLIP_INCLUSIVE](#CLIP-INCLUSIVE) | Intersects the current PostScript clipping path with the current clipping path and saves the result as the new PostScript clipping path. |
### CLIP_SAVE {#CLIP-SAVE}
```
public static final int CLIP_SAVE
```


Saves the current PostScript clipping path.

### CLIP_RESTORE {#CLIP-RESTORE}
```
public static final int CLIP_RESTORE
```


Restores the PostScript clipping path to the last clipping path that was saved by a previous CLIP\_SAVE function applied by a CLIP\_TO\_PATH record (section 2.3.6.6).

### CLIP_INCLUSIVE {#CLIP-INCLUSIVE}
```
public static final int CLIP_INCLUSIVE
```


Intersects the current PostScript clipping path with the current clipping path and saves the result as the new PostScript clipping path.

