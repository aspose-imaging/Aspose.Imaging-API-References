---
title: "XmpRightsManagementPackage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示 XMP 权限管理命名空间。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/
---
**Inheritance:**
java.lang.Object，[com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public final class XmpRightsManagementPackage extends XmpPackage
```

表示 XMP 权限管理命名空间。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage--) | 初始化 `XmpRightsManagementPackage` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | 添加字符串属性。 |
| [setCertificate(String certificate)](#setCertificate-java.lang.String-) | 设置证书。 |
| [setMarkedAsRightManagement(boolean value)](#setMarkedAsRightManagement-boolean-) | 标记为版权管理内容 |
| [setOwners(String[] owners)](#setOwners-java.lang.String---) | 设置所有者。 |
| [setUsageTerms(LangAlt usageTerms)](#setUsageTerms-com.aspose.imaging.xmp.LangAlt-) | 设置使用条款。 |
| [setWebStatement(String webStatementUrl)](#setWebStatement-java.lang.String-) | 设置网页声明。 |
### XmpRightsManagementPackage() {#XmpRightsManagementPackage--}
```
public XmpRightsManagementPackage()
```


初始化 `XmpRightsManagementPackage` 类的新实例。

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


添加字符串属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 键的字符串表示形式，用于标识添加的值。 |
| value | java.lang.String | 字符串值。 |

### setCertificate(String certificate) {#setCertificate-java.lang.String-}
```
public void setCertificate(String certificate)
```


设置证书。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 证书 | java.lang.String | 证书。 |

### setMarkedAsRightManagement(boolean value) {#setMarkedAsRightManagement-boolean-}
```
public void setMarkedAsRightManagement(boolean value)
```


标记为版权管理内容

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 如果设置为 `true`，则表示这是受版权管理的资源。 |

### setOwners(String[] owners) {#setOwners-java.lang.String---}
```
public void setOwners(String[] owners)
```


设置所有者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 所有者 | java.lang.String[] | 所有者。 |

### setUsageTerms(LangAlt usageTerms) {#setUsageTerms-com.aspose.imaging.xmp.LangAlt-}
```
public void setUsageTerms(LangAlt usageTerms)
```


设置使用条款。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| usageTerms | [LangAlt](../../com.aspose.imaging.xmp/langalt) | 使用条款。 |

### setWebStatement(String webStatementUrl) {#setWebStatement-java.lang.String-}
```
public void setWebStatement(String webStatementUrl)
```


设置网页声明。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| webStatementUrl | java.lang.String | 网页声明 URL。 |

