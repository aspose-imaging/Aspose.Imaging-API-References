---
title: PointData
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in punktdata En array av Räknepunkter som anger start- slut- och kontrollpunkter för Bezier-kurvorna. Slutkoordinaten för en Bezier-kurva är startkoordinaten för nästa. Kontrollpunkterna används för att producera Bezier-effekten. Typen av data i denna array specificeras av Flags-fältet enligt följande Data Type Meaning EmfPlusPointR-objekt avsnitt 2.2.2.37 Om P-flaggan är inställd i flaggorna  punkterna anger relativa platser. EmfPlusPointF-objekt avsnitt 2.2.2.36 Om P- och C-bitarna är rena i Flags-fältet anger punkterna absoluta platser. EmfPlusPoint-objekt avsnitt 2.2.2.05d_ If the P. är ren och C-biten är inställd i fältet Flaggor anger punkterna relativa platser. En Bezier-kurva passerar inte genom sina kontrollpunkter. Kontrollpunkterna fungerar som
type: docs
weight: 40
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata/
---
## EmfPlusDrawBeziers.PointData property

Hämtar eller ställer in punktdata En array av Räknepunkter som anger start-, slut- och kontrollpunkter för Bezier-kurvorna. Slutkoordinaten för en Bezier-kurva är startkoordinaten för nästa. Kontrollpunkterna används för att producera Bezier-effekten. Typen av data i denna array specificeras av Flags-fältet, enligt följande: Data Type Meaning EmfPlusPointR-objekt (avsnitt 2.2.2.37) Om P-flaggan är inställd i flaggorna , punkterna anger relativa platser. EmfPlusPointF-objekt (avsnitt 2.2.2.36) Om P- och C-bitarna är rena i Flags-fältet, anger punkterna absoluta platser. EmfPlusPoint-objekt (avsnitt 2.2.2.05d)_ If the P. är ren och C-biten är inställd i fältet Flaggor, anger punkterna relativa platser. En Bezier-kurva passerar inte genom sina kontrollpunkter. Kontrollpunkterna fungerar som

```csharp
public PointF[] PointData { get; set; }
```

### Se även

* struct [PointF](../../../aspose.imaging/pointf)
* class [EmfPlusDrawBeziers](../../emfplusdrawbeziers)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawbeziers)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->