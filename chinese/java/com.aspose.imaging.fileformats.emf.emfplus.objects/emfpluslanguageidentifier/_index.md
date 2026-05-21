---
title: "EmfPlusLanguageIdentifier"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusLanguageIdentifier 对象指定一个语言标识符，该标识符对应于包括国家、地理区域和行政区在内的区域设置中的自然语言。"
type: docs
weight: 50
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLanguageIdentifier extends EmfPlusStructureObjectType
```

EmfPlusLanguageIdentifier 对象指定一个语言标识符，该标识符对应于包括国家、地理区域和行政区在内的区域设置中的自然语言。每个语言标识符都是主语言值和子语言值的编码。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue()](#getValue--) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId（6 位）：在 PrimaryLanguageId 字段中指定的自然语言对应的国家、地理区域或行政区。 |
| [setValue(short value)](#setValue-short-) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId（6 位）：在 PrimaryLanguageId 字段中指定的自然语言对应的国家、地理区域或行政区。 |
### EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier--}
```
public EmfPlusLanguageIdentifier()
```


### getValue() {#getValue--}
```
public short getValue()
```


获取或设置字段的值 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId（6 位）：在 PrimaryLanguageId 字段中指定的自然语言对应的国家、地理区域或行政区。子语言标识符是供应商可扩展的。供应商定义的子语言标识符必须在 0x20 到 0x3F（含）范围内。PrimaryLanguageId（10 位）：自然语言。主语言标识符是供应商可扩展的。供应商定义的主语言标识符必须在 0x0200 到 0x03FF（含）范围内。

**Returns:**
short
### setValue(short value) {#setValue-short-}
```
public void setValue(short value)
```


获取或设置字段的值 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId（6 位）：在 PrimaryLanguageId 字段中指定的自然语言对应的国家、地理区域或行政区。子语言标识符是供应商可扩展的。供应商定义的子语言标识符必须在 0x20 到 0x3F（含）范围内。PrimaryLanguageId（10 位）：自然语言。主语言标识符是供应商可扩展的。供应商定义的主语言标识符必须在 0x0200 到 0x03FF（含）范围内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

