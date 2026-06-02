---
title: "EmfPlusBrushDataFlags Enumeration"
type: docs
weight: 30
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---

BrushData bayrakları, isteğe bağlı veri alanlarının varlığı dahil olmak üzere grafik fırçalarının özelliklerini belirtir. Bu bayraklar birden fazla seçeneği belirtmek için birleştirilebilir.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusBrushDataFlags

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| BRUSH_DATA_BLEND_FACTORS_H | Bu bayrak, EmfPlusLinearGradientBrushData ve EmfPlusPathGradientBrushData nesnelerinde anlamlıdır.<br/>            Ayarlanırsa, yatay bir degrade boyunca bir karıştırma deseni belirten [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) nesnesi (bölüm 2.2.2.5), fırça veri nesnesinin OptionalData alanında belirtilmelidir. |
| BRUSH_DATA_BLEND_FACTORS_V | Bu bayrak, EmfPlusLinearGradientBrushData nesnelerinde anlamlıdır.<br/>            Ayarlanırsa, dikey bir degrade boyunca bir karıştırma deseni belirten EmfPlusBlendFactors nesnesi, fırça veri nesnesinin OptionalData alanında belirtilmelidir. |
| BRUSH_DATA_DO_NOT_TRANSFORM | Bu bayrak, EmfPlusTextureBrushData nesnelerinde anlamlıdır.<br/>            Ayarlanırsa, dünya uzayından cihaz uzayına dönüşüm doku fırçasına uygulanmamalıdır. |
| BRUSH_DATA_FOCUS_SCALES | Bu bayrak, EmfPlusPathGradientBrushData nesnelerinde anlamlıdır.<br/>            Ayarlanırsa, bir [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) nesnesi (bölüm 2.2.2.18) fırça veri nesnesinin OptionalData alanında belirtilmelidir. |
| BRUSH_DATA_IS_GAMMA_CORRECTED | Bu bayrak, EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData ve EmfPlusTextureBrushData nesnelerinde anlamlıdır.<br/>            Ayarlanırsa, fırça zaten gama düzeltmesi yapılmış olmalıdır; yani çıkış parlaklığı ve yoğunluğu, giriş görüntüsüyle eşleşecek şekilde düzeltilmiştir. |
| BRUSH_DATA_PATH | Bu bayrak, [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) nesnelerinde (bölüm 2.2.2.29) anlamlıdır.<br/>            Ayarlanırsa, bir [EmfPlusBoundaryPathData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/) nesnesi (bölüm 2.2.2.6) fırça veri nesnesinin BoundaryData alanında belirtilmelidir.<br/>            Temizlenirse, bir [EmfPlusBoundaryPointData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/) nesnesi (bölüm 2.2.2.7) fırça veri nesnesinin BoundaryData alanında belirtilmelidir. |
| BRUSH_DATA_PRESET_COLORS | Bu bayrak, EmfPlusLinearGradientBrushData ve EmfPlusPathGradientBrushData nesnelerinde anlamlıdır.<br/>            Ayarlanırsa, bir [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) nesnesi (bölüm 2.2.2.4) fırça veri nesnesinin OptionalData alanında belirtilmelidir. |
| BRUSH_DATA_TRANSFORM | Bu bayrak, [EmfPlusLinearGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) nesnelerinde (bölüm 2.2.2.24), [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) nesnelerinde ve [EmfPlusTextureBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) nesnelerinde (bölüm 2.2.2.45) anlamlıdır.<br/>            Ayarlanırsa, 2x3 bir dünya uzayından cihaz uzayına dönüşüm matrisi fırça veri nesnesinin OptionalData alanında belirtilmelidir. |
