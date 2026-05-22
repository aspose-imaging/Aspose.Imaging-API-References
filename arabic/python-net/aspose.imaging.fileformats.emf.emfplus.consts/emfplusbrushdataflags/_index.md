---
title: "EmfPlusBrushDataFlags Enumeration"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---

علامات BrushData تحدد خصائص فرش الرسومات، بما في ذلك وجود حقول بيانات اختيارية. يمكن دمج هذه العلامات لتحديد خيارات متعددة.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusBrushDataFlags

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| BRUSH_DATA_BLEND_FACTORS_H | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData.<br/>            إذا تم تعيينها، يجب تحديد كائن [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) (القسم 2.2.2.5) الذي يحدد نمط المزج على طول تدرج أفقي في حقل OptionalData لكائن بيانات الفرشاة. |
| BRUSH_DATA_BLEND_FACTORS_V | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData.<br/>            إذا تم تعيينها، يجب تحديد كائن EmfPlusBlendFactors الذي يحدد نمط المزج على طول تدرج عمودي في حقل OptionalData لكائن بيانات الفرشاة. |
| BRUSH_DATA_DO_NOT_TRANSFORM | هذه العلامة ذات معنى في كائنات EmfPlusTextureBrushData.<br/>            إذا تم تعيينها، يجب عدم تطبيق تحويل من مساحة العالم إلى مساحة الجهاز على فرشاة النسيج. |
| BRUSH_DATA_FOCUS_SCALES | هذه العلامة ذات معنى في كائنات EmfPlusPathGradientBrushData.<br/>            إذا تم تعيينها، يجب تحديد كائن[EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) (القسم 2.2.2.18) في حقل OptionalData لكائن بيانات الفرشاة. |
| BRUSH_DATA_IS_GAMMA_CORRECTED | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData و EmfPlusTextureBrushData.<br/>            إذا تم تعيينها، يجب أن تكون الفرشاة مُصححة غاما بالفعل؛ أي أن سطوع وإشعاع الإخراج قد تم تصحيحهما لتطابق صورة الإدخال. |
| BRUSH_DATA_PATH | هذه العلامة ذات معنى في كائنات [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) (القسم 2.2.2.29).<br/>            إذا تم تعيينها، يجب تحديد كائن [EmfPlusBoundaryPathData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/) (القسم 2.2.2.6) في حقل BoundaryData لكائن بيانات الفرشاة.<br/>            إذا لم يتم تعيينها، يجب تحديد كائن [EmfPlusBoundaryPointData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/) (القسم 2.2.2.7) في حقل BoundaryData لكائن بيانات الفرشاة. |
| BRUSH_DATA_PRESET_COLORS | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData.<br/>            إذا تم تعيينها، يجب تحديد كائن [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) (القسم 2.2.2.4) في حقل OptionalData لكائن بيانات الفرشاة. |
| BRUSH_DATA_TRANSFORM | هذه العلامة ذات معنى في كائنات [EmfPlusLinearGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) (القسم 2.2.2.24)، وكائنات [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/)، وكائنات [EmfPlusTextureBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) (القسم 2.2.2.45).<br/>            إذا تم تعيينها، يجب تحديد مصفوفة تحويل من مساحة العالم إلى مساحة الجهاز بحجم 2x3 في حقل OptionalData لكائن بيانات الفرشاة. |
