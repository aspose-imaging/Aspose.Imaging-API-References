---
title: "EmfPlusCustomLineCapOptionalData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusCustomLineCapOptionalData-objektet specificerar valfri fyllnings- och konturdata för en anpassad linjekapsling."
type: docs
weight: 37
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCustomLineCapOptionalData extends EmfPlusStructureObjectType
```

EmfPlusCustomLineCapOptionalData-objektet specificerar valfri fyllnings- och konturdata för en anpassad linjekapsling.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillData()](#getFillData--) | Hämtar eller anger ett valfritt EmfPlusFillPath-objekt (sektion 2.2.2.17) som specificerar sökvägen för fyllning av en anpassad grafiklinjekappa. |
| [setFillData(EmfPlusFillPath value)](#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-) | Hämtar eller anger ett valfritt EmfPlusFillPath-objekt (sektion 2.2.2.17) som specificerar sökvägen för fyllning av en anpassad grafiklinjekappa. |
| [getOutlineData()](#getOutlineData--) | Hämtar eller anger ett valfritt EmfPlusLinePath-objekt (sektion 2.2.2.26) som specificerar sökvägen för konturering av en anpassad grafiklinjekappa. |
| [setOutlineData(EmfPlusLinePath value)](#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-) | Hämtar eller anger ett valfritt EmfPlusLinePath-objekt (sektion 2.2.2.26) som specificerar sökvägen för konturering av en anpassad grafiklinjekappa. |
### EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData--}
```
public EmfPlusCustomLineCapOptionalData()
```


### getFillData() {#getFillData--}
```
public EmfPlusFillPath getFillData()
```


Hämtar eller anger ett valfritt EmfPlusFillPath-objekt (sektion 2.2.2.17) som specificerar sökvägen för fyllning av en anpassad grafiklinjekappa. Detta fält MÅSTE finnas om flaggan CustomLineCapDataFillPath är satt i CustomLineCapDataFlags‑fältet för EmfPlusCustomLineCapData‑objektet.

**Returns:**
[EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath)
### setFillData(EmfPlusFillPath value) {#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-}
```
public void setFillData(EmfPlusFillPath value)
```


Hämtar eller anger ett valfritt EmfPlusFillPath-objekt (sektion 2.2.2.17) som specificerar sökvägen för fyllning av en anpassad grafiklinjekappa. Detta fält MÅSTE finnas om flaggan CustomLineCapDataFillPath är satt i CustomLineCapDataFlags‑fältet för EmfPlusCustomLineCapData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath) |  |

### getOutlineData() {#getOutlineData--}
```
public EmfPlusLinePath getOutlineData()
```


Hämtar eller anger ett valfritt EmfPlusLinePath-objekt (sektion 2.2.2.26) som specificerar sökvägen för konturering av en anpassad grafiklinjekappa. Detta fält MÅSTE finnas om flaggan CustomLineCapDataLinePath är satt i CustomLineCapDataFlags‑fältet för EmfPlusCustomLineCapData‑objektet.

**Returns:**
[EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath)
### setOutlineData(EmfPlusLinePath value) {#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-}
```
public void setOutlineData(EmfPlusLinePath value)
```


Hämtar eller anger ett valfritt EmfPlusLinePath-objekt (sektion 2.2.2.26) som specificerar sökvägen för konturering av en anpassad grafiklinjekappa. Detta fält MÅSTE finnas om flaggan CustomLineCapDataLinePath är satt i CustomLineCapDataFlags‑fältet för EmfPlusCustomLineCapData‑objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath) |  |

