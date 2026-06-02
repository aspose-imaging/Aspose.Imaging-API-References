---
title: "EmfRegionData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet RegionData spécifie les données qui définissent une région constituée de rectangles qui ne se chevauchent pas."
type: docs
weight: 33
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionData extends EmfObject
```

L'objet RegionData spécifie les données qui définissent une région, composée de rectangles qui ne se chevauchent pas.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfRegionData()](#EmfRegionData--) | Initialise une nouvelle instance de la classe `EmfRegionData`. |
| [EmfRegionData(Rectangle rectangle)](#EmfRegionData-com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe `EmfRegionData`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRegionDataHeader()](#getRegionDataHeader--) | Obtient un objet RegionDataHeader de 256 bits qui décrit les données suivantes. |
| [setRegionDataHeader(EmfRegionDataHeader value)](#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-) | Définit un objet RegionDataHeader de 256 bits qui décrit les données suivantes. |
| [getData()](#getData--) | Obtient un tableau d'objets WMF RectL ([MS-WMF] section 2.2.2.19) ; les objets sont fusionnés pour créer la région |
| [setData(Rectangle[] value)](#setData-com.aspose.imaging.Rectangle---) | Définit un tableau d'objets WMF RectL ([MS-WMF] section 2.2.2.19) ; les objets sont fusionnés pour créer la région |
### EmfRegionData() {#EmfRegionData--}
```
public EmfRegionData()
```


Initialise une nouvelle instance de la classe `EmfRegionData`.

### EmfRegionData(Rectangle rectangle) {#EmfRegionData-com.aspose.imaging.Rectangle-}
```
public EmfRegionData(Rectangle rectangle)
```


Initialise une nouvelle instance de la classe `EmfRegionData`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |

### getRegionDataHeader() {#getRegionDataHeader--}
```
public EmfRegionDataHeader getRegionDataHeader()
```


Obtient un objet RegionDataHeader de 256 bits qui décrit les données suivantes.

**Returns:**
[EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader)
### setRegionDataHeader(EmfRegionDataHeader value) {#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-}
```
public void setRegionDataHeader(EmfRegionDataHeader value)
```


Définit un objet RegionDataHeader de 256 bits qui décrit les données suivantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader) |  |

### getData() {#getData--}
```
public Rectangle[] getData()
```


Obtient un tableau d'objets WMF RectL ([MS-WMF] section 2.2.2.19) ; les objets sont fusionnés pour créer la région

**Returns:**
com.aspose.imaging.Rectangle[]
### setData(Rectangle[] value) {#setData-com.aspose.imaging.Rectangle---}
```
public void setData(Rectangle[] value)
```


Définit un tableau d'objets WMF RectL ([MS-WMF] section 2.2.2.19) ; les objets sont fusionnés pour créer la région

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

