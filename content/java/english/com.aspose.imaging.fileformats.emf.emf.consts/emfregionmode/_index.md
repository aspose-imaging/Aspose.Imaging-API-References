---
title: EmfRegionMode
second_title: Aspose.Imaging for Java API Reference
description: The RegionMode enumeration defines values that are used with EMR_SELECTCLIPPATH and EMR_EXTSELECTCLIPRGN specifying the current path or a new region that is being combined with the current clip region.
type: docs
weight: 39
url: /com.aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRegionMode extends System.Enum
```

The RegionMode enumeration defines values that are used with EMR\_SELECTCLIPPATH and EMR\_EXTSELECTCLIPRGN, specifying the current path or a new region that is being combined with the current clip region.
## Fields

| Field | Description |
| --- | --- |
| [RGN_AND](#RGN-AND) | The new clipping region includes the intersection (overlapping areas) of the current clipping region and the current path (or new region). |
| [RGN_OR](#RGN-OR) | The new clipping region includes the union (combined areas) of the current clipping region and the current path (or new region). |
| [RGN_XOR](#RGN-XOR) | The new clipping region includes the union of the current clipping region and the current path (or new region) but without the overlapping areas |
| [RGN_DIFF](#RGN-DIFF) | The new clipping region includes the areas of the current clipping region with those of the current path (or new region) excluded. |
| [RGN_COPY](#RGN-COPY) | The new clipping region is the current path (or the new region). |
### RGN_AND {#RGN-AND}
```
public static final int RGN_AND
```


The new clipping region includes the intersection (overlapping areas) of the current clipping region and the current path (or new region).

### RGN_OR {#RGN-OR}
```
public static final int RGN_OR
```


The new clipping region includes the union (combined areas) of the current clipping region and the current path (or new region).

### RGN_XOR {#RGN-XOR}
```
public static final int RGN_XOR
```


The new clipping region includes the union of the current clipping region and the current path (or new region) but without the overlapping areas

### RGN_DIFF {#RGN-DIFF}
```
public static final int RGN_DIFF
```


The new clipping region includes the areas of the current clipping region with those of the current path (or new region) excluded.

### RGN_COPY {#RGN-COPY}
```
public static final int RGN_COPY
```


The new clipping region is the current path (or the new region).

