---
title: PointData
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in punktdata En matris med Räknepunkter som anger ändpunkterna för linjerna som definierar spline. I en sluten kardinal spline fortsätter kurvan genom den sista punkten i PointData-matrisen och ansluter till den första punkten i matrisen. Typen av data i denna matris specificeras av Flags-fältet enligt följande Data Type Meaning EmfPlusPointR objekt avsnitt 2.2.2.37 Om P-flaggan är inställd i flaggorna anger punkterna relativa platser. EmfPlusPointF-objekt avsnitt 2.2.2.36 Om P- och C-bitarna är inställda i fältet Flaggor anger punkterna absolute locations. EmfPlusPoint-objekt avsnitt 2.2.2.35 Om P-biten är ren och C-biten är inställd i fältet Flags anger punkterna relativa platser.
type: docs
weight: 40
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata/
---
## EmfPlusDrawClosedCurve.PointData property

Hämtar eller ställer in punktdata En matris med Räknepunkter som anger ändpunkterna för linjerna som definierar spline. I en sluten kardinal spline, fortsätter kurvan genom den sista punkten i PointData-matrisen och ansluter till den första punkten i matrisen. Typen av data i denna matris specificeras av Flags-fältet, enligt följande: Data Type Meaning EmfPlusPointR objekt (avsnitt 2.2.2.37) Om P-flaggan är inställd i flaggorna anger punkterna relativa platser. EmfPlusPointF-objekt (avsnitt 2.2.2.36) Om P- och C-bitarna är inställda i fältet Flaggor anger punkterna absolute locations. EmfPlusPoint-objekt (avsnitt 2.2.2.35) Om P-biten är ren och C-biten är inställd i fältet Flags, anger punkterna relativa platser.

```csharp
public PointF[] PointData { get; set; }
```

### Se även

* struct [PointF](../../../aspose.imaging/pointf)
* class [EmfPlusDrawClosedCurve](../../emfplusdrawclosedcurve)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawclosedcurve)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->