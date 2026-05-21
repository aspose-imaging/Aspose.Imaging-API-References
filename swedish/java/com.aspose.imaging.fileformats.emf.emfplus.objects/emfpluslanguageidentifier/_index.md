---
title: "EmfPlusLanguageIdentifier"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusLanguageIdentifier‑objektet specificerar en språkidentifierare som motsvarar det naturliga språket i en lokal, inklusive länder, geografiska regioner och administrativa distrikt."
type: docs
weight: 50
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLanguageIdentifier extends EmfPlusStructureObjectType
```

EmfPlusLanguageIdentifier‑objektet specificerar en språkidentifierare som motsvarar det naturliga språket i en lokal, inklusive länder, geografiska regioner och administrativa distrikt. Varje språkidentifierare är en kodning av ett primärt språkvärde och ett underSpråk‑värde.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValue()](#getValue--) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 bitar): Landet, den geografiska regionen eller det administrativa distriktet för det naturliga språket som anges i PrimaryLanguageId‑fältet. |
| [setValue(short value)](#setValue-short-) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 bitar): Landet, den geografiska regionen eller det administrativa distriktet för det naturliga språket som anges i PrimaryLanguageId‑fältet. |
### EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier--}
```
public EmfPlusLanguageIdentifier()
```


### getValue() {#getValue--}
```
public short getValue()
```


Hämtar eller anger värdet för fältet 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 bitar): Landet, den geografiska regionen eller det administrativa distriktet för det naturliga språket som anges i PrimaryLanguageId‑fältet. Sublanguage‑identifierare är leverantörsutbyggbara. Leverantörsdefinierade sublanguage‑identifierare MÅSTE ligga i intervallet 0x20 till 0x3F, inklusive. PrimaryLanguageId (10 bitar): Det naturliga språket. Primära språkidentifierare är leverantörsutbyggbara. Leverantörsdefinierade primära språkidentifierare MÅSTE ligga i intervallet 0x0200 till 0x03FF, inklusive.

**Returns:**
short
### setValue(short value) {#setValue-short-}
```
public void setValue(short value)
```


Hämtar eller anger värdet för fältet 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 bitar): Landet, den geografiska regionen eller det administrativa distriktet för det naturliga språket som anges i PrimaryLanguageId‑fältet. Sublanguage‑identifierare är leverantörsutbyggbara. Leverantörsdefinierade sublanguage‑identifierare MÅSTE ligga i intervallet 0x20 till 0x3F, inklusive. PrimaryLanguageId (10 bitar): Det naturliga språket. Primära språkidentifierare är leverantörsutbyggbara. Leverantörsdefinierade primära språkidentifierare MÅSTE ligga i intervallet 0x0200 till 0x03FF, inklusive.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

