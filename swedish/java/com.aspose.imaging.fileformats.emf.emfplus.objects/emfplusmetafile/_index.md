---
title: "EmfPlusMetafile"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusMetafileData-objektet specificerar en metafil som innehåller en grafikbild"
type: docs
weight: 55
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusMetafile extends EmfPlusBaseImageData
```

EmfPlusMetafileData-objektet specificerar en metafil som innehåller en grafikbild
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusMetafile()](#EmfPlusMetafile--) | Initierar en ny instans av `EmfPlusMetafile`-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar typen av metafil som är inbäddad i MetafileData-fältet. |
| [setType(int value)](#setType-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar typen av metafil som är inbäddad i MetafileData-fältet. |
| [getMetafileDataSize()](#getMetafileDataSize--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken i byte för metafildata i MetafileData-fältet. |
| [setMetafileDataSize(int value)](#setMetafileDataSize-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken i byte för metafildata i MetafileData-fältet. |
| [getMetafileData()](#getMetafileData--) | Hämtar eller anger variabel‑längdsdata som specificerar den inbäddade metafilen. |
| [setMetafileData(byte[] value)](#setMetafileData-byte---) | Hämtar eller anger variabel‑längdsdata som specificerar den inbäddade metafilen. |
### EmfPlusMetafile() {#EmfPlusMetafile--}
```
public EmfPlusMetafile()
```


Initierar en ny instans av `EmfPlusMetafile`-klassen.

### getType() {#getType--}
```
public int getType()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar typen av metafil som är inbäddad i MetafileData-fältet. Detta värde MÅSTE vara definierat i MetafileDataType‑enumerationen (avsnitt 2.1.1.21).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar typen av metafil som är inbäddad i MetafileData-fältet. Detta värde MÅSTE vara definierat i MetafileDataType‑enumerationen (avsnitt 2.1.1.21).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getMetafileDataSize() {#getMetafileDataSize--}
```
public int getMetafileDataSize()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken i byte för metafildata i MetafileData-fältet.

**Returns:**
int
### setMetafileDataSize(int value) {#setMetafileDataSize-int-}
```
public void setMetafileDataSize(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken i byte för metafildata i MetafileData-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getMetafileData() {#getMetafileData--}
```
public byte[] getMetafileData()
```


Hämtar eller anger variabel‑längdsdata som specificerar den inbäddade metafilen. Innehållet och formatet på data kan variera för varje metafiltyp.

Grafikbilder specificeras av EmfPlusImage-objekt (avsnitt 2.2.1.4). Ett EmfPlusMetafile-objekt MÅSTE finnas i ImageData-fältet för ett EmfPlusImage-objekt om ImageTypeMetafile är angivet i dess Type-fält. Detta objekt är generiskt och används för olika datatyper, inklusive: En WMF-metafil [MS-WMF]; WMF-metafil som kan placeras; En EMF-metafil [MS-EMF]; En EMF+-metafil som specificerar grafikoperationer endast med EMF+-poster; och En EMF+-metafil som specificerar grafikoperationer med både EMF+- och EMF-poster. Se avsnitt 2.2.2 för specifikationen av ytterligare strukturobjekt.

**Returns:**
byte[]
### setMetafileData(byte[] value) {#setMetafileData-byte---}
```
public void setMetafileData(byte[] value)
```


Hämtar eller anger variabel‑längdsdata som specificerar den inbäddade metafilen. Innehållet och formatet på data kan variera för varje metafiltyp.

Grafikbilder specificeras av EmfPlusImage-objekt (avsnitt 2.2.1.4). Ett EmfPlusMetafile-objekt MÅSTE finnas i ImageData-fältet för ett EmfPlusImage-objekt om ImageTypeMetafile är angivet i dess Type-fält. Detta objekt är generiskt och används för olika datatyper, inklusive: En WMF-metafil [MS-WMF]; WMF-metafil som kan placeras; En EMF-metafil [MS-EMF]; En EMF+-metafil som specificerar grafikoperationer endast med EMF+-poster; och En EMF+-metafil som specificerar grafikoperationer med både EMF+- och EMF-poster. Se avsnitt 2.2.2 för specifikationen av ytterligare strukturobjekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

