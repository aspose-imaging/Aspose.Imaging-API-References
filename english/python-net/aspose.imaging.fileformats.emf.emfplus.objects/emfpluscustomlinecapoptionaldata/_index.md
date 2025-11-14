---
title: EmfPlusCustomLineCapOptionalData Class
type: docs
weight: 280
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---

**Summary:** The EmfPlusCustomLineCapOptionalData object specifies optional fill and outline data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData__1) | Initializes a new instance of the EmfPlusCustomLineCapOptionalData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| fill_data | [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath/) | r/w | Gets or sets optional EmfPlusFillPath object (section 2.2.2.17) that specifies the path for filling a custom<br/>            graphics line cap. This field MUST be present if the CustomLineCapDataFillPath flag is set in the CustomLineCapDataFlags<br/>             field of the EmfPlusCustomLineCapData object. |
| outline_data | [EmfPlusLinePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath/) | r/w | Gets or sets optional EmfPlusLinePath object (section 2.2.2.26) <br/>            that specifies the path for outlining a custom graphics line cap. This field MUST be present if the CustomLineCapDataLinePath flag is set in the CustomLineCapDataFlags <br/>            field of the EmfPlusCustomLineCapData object. |


### Constructor: EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData__1}


```
 EmfPlusCustomLineCapOptionalData() 
```

Initializes a new instance of the EmfPlusCustomLineCapOptionalData class

