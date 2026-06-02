---
title: "GifApplicationExtensionBlock"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كتلة امتداد تطبيق GIF."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifApplicationExtensionBlock extends GifBlock
```

كتلة امتداد تطبيق GIF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock--) | يُنشئ مثلاً جديداً من الفئة `GifApplicationExtensionBlock`. |
| [GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)](#GifApplicationExtensionBlock-java.lang.String-byte---byte---) | يُنشئ مثلاً جديداً من الفئة `GifApplicationExtensionBlock`. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | يحدد حجم رأس الكتلة. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | تسمية الامتداد. |
| [BLOCK_SIZE](#BLOCK-SIZE) | حجم كتلة اسم الامتداد + الإصدار |
| [APPLICATION_IDENTIFIER_SIZE](#APPLICATION-IDENTIFIER-SIZE) | يحدد حجم معرف التطبيق. |
| [APPLICATION_AUTHENTICATION_CODE_SIZE](#APPLICATION-AUTHENTICATION-CODE-SIZE) | يحدد حجم رمز مصادقة التطبيق. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getApplicationAuthenticationCode()](#getApplicationAuthenticationCode--) | يحصل أو يضبط رمز مصادقة التطبيق. |
| [setApplicationAuthenticationCode(byte[] value)](#setApplicationAuthenticationCode-byte---) | يحصل أو يضبط رمز مصادقة التطبيق. |
| [getApplicationIdentifier()](#getApplicationIdentifier--) | يحصل أو يضبط معرف التطبيق. |
| [setApplicationIdentifier(String value)](#setApplicationIdentifier-java.lang.String-) | يحصل أو يضبط معرف التطبيق. |
| [getApplicationData()](#getApplicationData--) | يحصل أو يضبط بيانات التطبيق. |
| [setApplicationData(byte[] value)](#setApplicationData-byte---) | يحصل أو يضبط بيانات التطبيق. |
### GifApplicationExtensionBlock() {#GifApplicationExtensionBlock--}
```
public GifApplicationExtensionBlock()
```


يُنشئ مثلاً جديداً من الفئة `GifApplicationExtensionBlock`.

### GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData) {#GifApplicationExtensionBlock-java.lang.String-byte---byte---}
```
public GifApplicationExtensionBlock(String applicationIdentifier, byte[] applicationAuthenticationCode, byte[] applicationData)
```


يُنشئ مثلاً جديداً من الفئة `GifApplicationExtensionBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| applicationIdentifier | java.lang.String | معرف التطبيق. |
| applicationAuthenticationCode | byte[] | رمز مصادقة التطبيق. |
| applicationData | byte[] | بيانات التطبيق. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


يحدد حجم رأس الكتلة.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


تسمية الامتداد.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


حجم كتلة اسم الامتداد + الإصدار

### APPLICATION_IDENTIFIER_SIZE {#APPLICATION-IDENTIFIER-SIZE}
```
public static final int APPLICATION_IDENTIFIER_SIZE
```


يحدد حجم معرف التطبيق.

### APPLICATION_AUTHENTICATION_CODE_SIZE {#APPLICATION-AUTHENTICATION-CODE-SIZE}
```
public static final int APPLICATION_AUTHENTICATION_CODE_SIZE
```


يحدد حجم رمز مصادقة التطبيق.

### getApplicationAuthenticationCode() {#getApplicationAuthenticationCode--}
```
public byte[] getApplicationAuthenticationCode()
```


يحصل أو يضبط رمز مصادقة التطبيق.

القيمة: رمز مصادقة التطبيق.

**Returns:**
byte[]
### setApplicationAuthenticationCode(byte[] value) {#setApplicationAuthenticationCode-byte---}
```
public void setApplicationAuthenticationCode(byte[] value)
```


يحصل أو يضبط رمز مصادقة التطبيق.

القيمة: رمز مصادقة التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getApplicationIdentifier() {#getApplicationIdentifier--}
```
public String getApplicationIdentifier()
```


يحصل أو يضبط معرف التطبيق.

القيمة: معرف التطبيق.

**Returns:**
java.lang.String
### setApplicationIdentifier(String value) {#setApplicationIdentifier-java.lang.String-}
```
public void setApplicationIdentifier(String value)
```


يحصل أو يضبط معرف التطبيق.

القيمة: معرف التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getApplicationData() {#getApplicationData--}
```
public byte[] getApplicationData()
```


يحصل أو يضبط بيانات التطبيق.

القيمة: بيانات التطبيق.

**Returns:**
byte[]
### setApplicationData(byte[] value) {#setApplicationData-byte---}
```
public void setApplicationData(byte[] value)
```


يحصل أو يضبط بيانات التطبيق.

القيمة: بيانات التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

