---
title: "EmfPlusLanguageIdentifier"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusLanguageIdentifier‑Objekt gibt einen Sprachbezeichner an, der der natürlichen Sprache in einer Gebietseinstellung entspricht, einschließlich Ländern, geografischen Regionen und Verwaltungsbezirken."
type: docs
weight: 50
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLanguageIdentifier extends EmfPlusStructureObjectType
```

Das EmfPlusLanguageIdentifier‑Objekt gibt einen Sprachbezeichner an, der der natürlichen Sprache in einer Gebietseinstellung entspricht, einschließlich Ländern, geografischen Regionen und Verwaltungsbezirken. Jeder Sprachbezeichner ist eine Kodierung eines Primärsprachenwerts und eines Untersprachenwerts.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValue()](#getValue--) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 Bits): Das Land, die geografische Region oder der Verwaltungsbezirk für die in dem PrimaryLanguageId‑Feld angegebene natürliche Sprache. |
| [setValue(short value)](#setValue-short-) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 Bits): Das Land, die geografische Region oder der Verwaltungsbezirk für die in dem PrimaryLanguageId‑Feld angegebene natürliche Sprache. |
### EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier--}
```
public EmfPlusLanguageIdentifier()
```


### getValue() {#getValue--}
```
public short getValue()
```


Liest oder schreibt den Wert des Feldes 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 Bits): Das Land, die geografische Region oder der Verwaltungsbezirk für die in dem PrimaryLanguageId‑Feld angegebene natürliche Sprache. Sublanguage‑Bezeichner sind herstellererweiterbar. Vom Hersteller definierte Sublanguage‑Bezeichner MÜSSEN im Bereich 0x20 bis 0x3F liegen, einschließlich. PrimaryLanguageId (10 Bits): Die natürliche Sprache. Primary‑Language‑Bezeichner sind herstellererweiterbar. Vom Hersteller definierte Primary‑Language‑Bezeichner MÜSSEN im Bereich 0x0200 bis 0x03FF liegen, einschließlich.

**Returns:**
short
### setValue(short value) {#setValue-short-}
```
public void setValue(short value)
```


Liest oder schreibt den Wert des Feldes 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 Bits): Das Land, die geografische Region oder der Verwaltungsbezirk für die in dem PrimaryLanguageId‑Feld angegebene natürliche Sprache. Sublanguage‑Bezeichner sind herstellererweiterbar. Vom Hersteller definierte Sublanguage‑Bezeichner MÜSSEN im Bereich 0x20 bis 0x3F liegen, einschließlich. PrimaryLanguageId (10 Bits): Die natürliche Sprache. Primary‑Language‑Bezeichner sind herstellererweiterbar. Vom Hersteller definierte Primary‑Language‑Bezeichner MÜSSEN im Bereich 0x0200 bis 0x03FF liegen, einschließlich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

