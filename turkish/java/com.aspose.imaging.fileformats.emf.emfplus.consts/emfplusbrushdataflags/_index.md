---
title: "EmfPlusBrushDataFlags"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BrushData bayrakları, isteğe bağlı veri alanlarının varlığı dahil olmak üzere grafik fırçalarının özelliklerini belirtir."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

BrushData bayrakları, isteğe bağlı veri alanlarının varlığı dahil olmak üzere grafik fırçalarının özelliklerini belirtir. Bu bayraklar birden fazla seçeneği belirtmek için birleştirilebilir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | Bu bayrak, [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) nesnelerinde (bölüm 2.2.2.29) anlamlıdır. |
| [BrushDataTransform](#BrushDataTransform) | Bu bayrak, [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) nesnelerinde (bölüm 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) nesnelerinde ve `EmfPlusTextureBrushData` nesnelerinde (bölüm 2.2.2.45) anlamlıdır. |
| [BrushDataPresetColors](#BrushDataPresetColors) | Bu bayrak, EmfPlusLinearGradientBrushData ve EmfPlusPathGradientBrushData nesnelerinde anlamlıdır. |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | Bu bayrak, EmfPlusLinearGradientBrushData ve EmfPlusPathGradientBrushData nesnelerinde anlamlıdır. |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | Bu bayrak, EmfPlusLinearGradientBrushData nesnelerinde anlamlıdır. |
| [BrushDataFocusScales](#BrushDataFocusScales) | Bu bayrak, EmfPlusPathGradientBrushData nesnelerinde anlamlıdır. |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | Bu bayrak, EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData ve EmfPlusTextureBrushData nesnelerinde anlamlıdır. |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | Bu bayrak, EmfPlusTextureBrushData nesnelerinde anlamlıdır. |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


Bu bayrak, [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) nesnelerinde (bölüm 2.2.2.29) anlamlıdır. Ayarlanmışsa, bir [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) nesnesi (bölüm 2.2.2.6) fırça veri nesnesinin BoundaryData alanında belirtilmelidir. Temizlenmişse, bir [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) nesnesi (bölüm 2.2.2.7) fırça veri nesnesinin BoundaryData alanında belirtilmelidir.

--------------------

Grafik fırçaları, [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush) nesneleri tarafından belirtilir.

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


Bu bayrak, [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) nesnelerinde (bölüm 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) nesnelerinde ve `EmfPlusTextureBrushData` nesnelerinde (bölüm 2.2.2.45) anlamlıdır. Ayarlanmışsa, 2x3 dünya uzayından aygıt uzayına dönüşüm matrisi, fırça veri nesnesinin OptionalData alanında belirtilmelidir.

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


Bu bayrak, EmfPlusLinearGradientBrushData ve EmfPlusPathGradientBrushData nesnelerinde anlamlıdır. Ayarlanmışsa, bir [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) nesnesi (bölüm 2.2.2.4) fırça veri nesnesinin OptionalData alanında belirtilmelidir.

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


Bu bayrak, EmfPlusLinearGradientBrushData ve EmfPlusPathGradientBrushData nesnelerinde anlamlıdır. Ayarlanmışsa, yatay bir degrade boyunca bir karışım deseni belirten bir [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) nesnesi (bölüm 2.2.2.5) fırça veri nesnesinin OptionalData alanında belirtilmelidir.

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


Bu bayrak, EmfPlusLinearGradientBrushData nesnelerinde anlamlıdır. Ayarlanmışsa, dikey bir degrade boyunca bir karışım deseni belirten bir EmfPlusBlendFactors nesnesi fırça veri nesnesinin OptionalData alanında belirtilmelidir.

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


Bu bayrak, EmfPlusPathGradientBrushData nesnelerinde anlamlıdır. Ayarlanmışsa, bir[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) nesnesi (bölüm 2.2.2.18) fırça veri nesnesinin OptionalData alanında belirtilmelidir.

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


Bu bayrak, EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData ve EmfPlusTextureBrushData nesnelerinde anlamlıdır. Ayarlanmışsa, fırça zaten gama düzeltmesi yapılmış olmalıdır; yani çıkış parlaklığı ve yoğunluğu giriş görüntüsüyle eşleşecek şekilde düzeltilmiştir.

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


Bu bayrak, EmfPlusTextureBrushData nesnelerinde anlamlıdır. Ayarlanmışsa, bir dünya uzayından aygıt uzayına dönüşüm doku fırçasına uygulanmamalıdır.

