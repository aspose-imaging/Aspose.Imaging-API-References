---
title: EmfPlusLanguageIdentifier
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das EmfPlusLanguageIdentifier-Objekt gibt eine Sprachkennung an die der natürlichen -Sprache in einem Gebietsschema entspricht einschließlich Ländern geografischen Regionen und Verwaltungsbezirken. Jede Sprachkennung ist eine Codierung eines primären Sprachwerts und eines untergeordneten Sprachwerts.
type: docs
weight: 5530
url: /de/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
## EmfPlusLanguageIdentifier class

Das EmfPlusLanguageIdentifier-Objekt gibt eine Sprachkennung an, die der natürlichen -Sprache in einem Gebietsschema entspricht, einschließlich Ländern, geografischen Regionen und Verwaltungsbezirken. Jede Sprachkennung ist eine Codierung eines primären Sprachwerts und eines untergeordneten Sprachwerts.

```csharp
public sealed class EmfPlusLanguageIdentifier : EmfPlusStructureObjectType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusLanguageIdentifier](emfpluslanguageidentifier)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Value](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/value) { get; set; } | Ermittelt oder setzt den Wert des Felds 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId&#x7C; PrimaryLanguageId &#x7C; SubLanguageId (6 Bits): Das Land, die geografische Region oder der Verwaltungsbezirk für die im Feld PrimaryLanguageId angegebene natürliche Sprache. Vom Hersteller definierte Untersprachenkennungen MÜSSEN im Bereich von 0x20 bis einschließlich 0x3F liegen. PrimaryLanguageId (10 Bit): Die natürliche Sprache. Primäre Sprachkennungen sind vom Hersteller erweiterbar. Herstellerdefinierte primäre Sprachkennungen MÜSSEN im Bereich von 0x0200 bis einschließlich 0x03FF liegen. |

### Siehe auch

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
