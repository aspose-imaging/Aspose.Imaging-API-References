---
title: "EmfBlendFunction Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

**Summary:** A structure that specifies the blending operations for source and destination bitmaps.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfBlendFunction()](#EmfBlendFunction__1) | EmfBlendFunction sınıfının yeni bir örneğini başlatır |
| [EmfBlendFunction(dword_data)](#EmfBlendFunction_dword_data_2) | Yeni bir [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) sınıf örneği başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| alpha_format | [EmfBlendFunction+AlphaFormatEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction+alphaformatenum/) | r | Kaynak ve hedef piksellerin alfa şeffaflığına göre nasıl yorumlanacağını belirten bir yapı alır <br/>            . |
| blend_flags | System.Byte | r | Blend bayraklarını alır.<br/>            Bu değer MUST 0x00 olmalı ve MUST göz ardı edilmelidir. |
| blend_operation | System.Byte | r | Blend işlem kodunu alır. <br/>            Tanımlanmış tek kaynak ve hedef <br/>            karışım işlemi 0x00'dır; bu, kaynak bitmap'in <br/>            MUST alfa şeffaflık değerlerine göre hedef bitmap ile birleştirileceğini belirtir. Ayrıntılar için aşağıdaki denklemlere bakın. |
| src_constant_alpha | System.Byte | r | Alfa şeffaflığını belirten 8 bit işaretsiz tamsayıyı alır, <br/>            bu değer kaynak ve hedef bitmap'lerin karışımını belirler. Bu değer MUST tüm kaynak bitmap üzerinde kullanılmalıdır. Minimum alfa şeffaflık değeri, sıfır, <br/>            tamamen şeffaf, maksimum değer 0xFF ise tamamen opaktır. Aslında, 0xFF değeri, piksel başına alfa değerlerinin <br/>            kaynak ve hedef bitmap'lerin karışımını belirleyeceğini gösterir. Ayrıntılar için bu bölümdeki denklemlere bakın. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [to_int()](#to_int__1) | Bir sayının dize temsilini tam sayıya dönüştürür. |


### Constructor: EmfBlendFunction() {#EmfBlendFunction__1}


```
 EmfBlendFunction() 
```

EmfBlendFunction sınıfının yeni bir örneğini başlatır

### Constructor: EmfBlendFunction(dword_data) {#EmfBlendFunction_dword_data_2}


```
 EmfBlendFunction(dword_data) 
```

Yeni bir [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) sınıf örneği başlatır

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dword_data | int | Dword verisi. |

### Method: to_int() {#to_int__1}


```
 to_int() 
```

Bir sayının dize temsilini tam sayıya dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Yapının DWORD değeri. |


