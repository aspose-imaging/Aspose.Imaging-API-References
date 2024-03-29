---
title: WmfFontQuality
second_title: Aspose.Imaging för .NET API-referens
description: FontQuality Enumeration anger hur nära attributen för det logiska teckensnittet ska matcha de för det fysiska teckensnittet vid rendering av text.
type: docs
weight: 8180
url: /sv/net/aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
## WmfFontQuality enumeration

FontQuality Enumeration anger hur nära attributen för det logiska teckensnittet ska matcha de för det fysiska teckensnittet vid rendering av text.

```csharp
public enum WmfFontQuality : byte
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | `0` | Anger att teckenkvaliteten på teckensnittet inte spelar någon roll, så DRAFT kan användas. |
| Draft | `1` | Anger att teckenkvaliteten för teckensnittet är mindre viktig än matchningen av av logiska attribut. För rastrerade teckensnitt SKA skalning vara aktiverad, vilket betyder att fler teckensnittsstorlekar är tillgängliga. |
| Proof | `2` | Anger att teckenkvaliteten för teckensnittet är viktigare än matchningen av logiska attribut. För rastrerade teckensnitt SKA skalning inaktiveras och font närmast i storlek SKA väljas. |
| Nonantialiased | `3` | Anger att kantutjämning INTE SKA användas när rendering text |
| Antialiased | `4` | Anger att kantutjämning SKA användas vid rendering av text, om typsnittet stöder det. |
| Cleartype | `5` | Anger att ClearType kantutjämning SKA användas när renderar text, om typsnittet stöder det. |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
