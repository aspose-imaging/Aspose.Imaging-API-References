---
title: "GifApplicationExtensionBlock"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Gif 应用扩展块."
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifApplicationExtensionBlock extends GifBlock
```

Gif 应用扩展块.
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock--) | 初始化 `GifApplicationExtensionBlock` 类的新实例。 |
| [GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)](#GifApplicationExtensionBlock-java.lang.String-byte---byte---) | 初始化 `GifApplicationExtensionBlock` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | 指定块头大小。 |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | 扩展标签。 |
| [BLOCK_SIZE](#BLOCK-SIZE) | 扩展名称 + 版本块大小 |
| [APPLICATION_IDENTIFIER_SIZE](#APPLICATION-IDENTIFIER-SIZE) | 指定应用程序标识符大小。 |
| [APPLICATION_AUTHENTICATION_CODE_SIZE](#APPLICATION-AUTHENTICATION-CODE-SIZE) | 指定应用程序身份验证代码大小。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getApplicationAuthenticationCode()](#getApplicationAuthenticationCode--) | 获取或设置应用程序身份验证代码。 |
| [setApplicationAuthenticationCode(byte[] value)](#setApplicationAuthenticationCode-byte---) | 获取或设置应用程序身份验证代码。 |
| [getApplicationIdentifier()](#getApplicationIdentifier--) | 获取或设置应用程序标识符。 |
| [setApplicationIdentifier(String value)](#setApplicationIdentifier-java.lang.String-) | 获取或设置应用程序标识符。 |
| [getApplicationData()](#getApplicationData--) | 获取或设置应用程序数据。 |
| [setApplicationData(byte[] value)](#setApplicationData-byte---) | 获取或设置应用程序数据。 |
### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock--}
```
public GifApplicationExtensionBlock()
```


初始化 `GifApplicationExtensionBlock` 类的新实例。

### GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData) {#GifApplicationExtensionBlock-java.lang.String-byte---byte---}
```
public GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)
```


初始化 `GifApplicationExtensionBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| applicationIdentifier | java.lang.String | 应用程序标识符。 |
| applicationAuthenticationCode | byte[] | 应用程序身份验证代码。 |
| applicationData | byte[] | 应用程序数据。 |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


指定块头大小。

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


扩展标签。

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


扩展名称 + 版本块大小

### APPLICATION_IDENTIFIER_SIZE {#APPLICATION-IDENTIFIER-SIZE}
```
public static final int APPLICATION_IDENTIFIER_SIZE
```


指定应用程序标识符大小。

### APPLICATION_AUTHENTICATION_CODE_SIZE {#APPLICATION-AUTHENTICATION-CODE-SIZE}
```
public static final int APPLICATION_AUTHENTICATION_CODE_SIZE
```


指定应用程序身份验证代码大小。

### getApplicationAuthenticationCode() {#getApplicationAuthenticationCode--}
```
public byte[] getApplicationAuthenticationCode()
```


获取或设置应用程序身份验证代码。

值：应用程序身份验证代码。

**Returns:**
byte[]
### setApplicationAuthenticationCode(byte[] value) {#setApplicationAuthenticationCode-byte---}
```
public void setApplicationAuthenticationCode(byte[] value)
```


获取或设置应用程序身份验证代码。

值：应用程序身份验证代码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getApplicationIdentifier() {#getApplicationIdentifier--}
```
public String getApplicationIdentifier()
```


获取或设置应用程序标识符。

值：应用程序标识符。

**Returns:**
java.lang.String
### setApplicationIdentifier(String value) {#setApplicationIdentifier-java.lang.String-}
```
public void setApplicationIdentifier(String value)
```


获取或设置应用程序标识符。

值：应用程序标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getApplicationData() {#getApplicationData--}
```
public byte[] getApplicationData()
```


获取或设置应用程序数据。

值：应用程序数据。

**Returns:**
byte[]
### setApplicationData(byte[] value) {#setApplicationData-byte---}
```
public void setApplicationData(byte[] value)
```


获取或设置应用程序数据。

值：应用程序数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

