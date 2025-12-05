---
title: Enum ExifProperties
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Exif.ExifProperties enum. Exif tags list
type: docs
weight: 1090
url: /net/aspose.imaging.exif/exifproperties/
---
## ExifProperties enumeration

Exif tags list

```csharp
public enum ExifProperties : ushort
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ImageWidth | `256` | The number of columns of image data, equal to the number of pixels per row. |
| ImageLength | `257` | The number of rows of image data. |
| BitsPerSample | `258` | The number of bits per image component. In this standard each component of the image is 8 bits, so the value for this tag is 8. |
| Compression | `259` | The compression scheme used for the image data. When a primary image is JPEG compressed, this designation is not necessary and is omitted. |
| PhotometricInterpretation | `262` | The pixel composition. |
| ImageDescription | `270` | A character string giving the title of the image. It may be a comment such as "1988 company picnic" or the like. |
| Make | `271` | The manufacturer of the recording equipment. This is the manufacturer of the DSC, scanner, video digitizer or other equipment that generated the image. When the field is left blank, it is treated as unknown. |
| Model | `272` | The model name or model number of the equipment. This is the model name or number of the DSC, scanner, video digitizer or other equipment that generated the image. When the field is left blank, it is treated as unknown. |
| Orientation | `274` | The image orientation viewed in terms of rows and columns. |
| SamplesPerPixel | `277` | The number of components per pixel. Since this standard applies to RGB and YCbCr images, the value set for this tag is 3. |
| XResolution | `282` | The number of pixels per ResolutionUnit in the ImageWidth direction. When the image resolution is unknown, 72 [dpi] is designated. |
| YResolution | `283` | The number of pixels per ResolutionUnit in the ImageLength direction. The same value as XResolution is designated. |
| PlanarConfiguration | `284` | Indicates whether pixel components are recorded in a chunky or planar format. If this field does not exist, the TIFF default of 1 (chunky) is assumed. |
| ResolutionUnit | `296` | The unit for measuring XResolution and YResolution. The same unit is used for both XResolution and YResolution. If the image resolution is unknown, 2 (inches) is designated. |
| TransferFunction | `301` | A transfer function for the image, described in tabular style. Normally this tag is not necessary, since color space is specified in the color space information ColorSpace tag. |
| Software | `305` | This tag records the name and version of the software or firmware of the camera or image input device used to generate the image. The detailed format is not specified, but it is recommended that the example shown below be followed. When the field is left blank, it is treated as unknown. |
| DateTime | `306` | The date and time of image creation. In Exif standard, it is the date and time the file was changed. |
| Artist | `315` | This tag records the name of the camera owner, photographer or image creator. The detailed format is not specified, but it is recommended that the information be written as in the example below for ease of Interoperability. When the field is left blank, it is treated as unknown. Ex.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| WhitePoint | `318` | The chromaticity of the white point of the image. Normally this tag is not necessary, since color space is specified in the colorspace information ColorSpace tag. |
| PrimaryChromaticities | `319` | The chromaticity of the three primary colors of the image. Normally this tag is not necessary, since colorspace is specified in the colorspace information ColorSpace tag. |
| YCbCrCoefficients | `529` | The matrix coefficients for transformation from RGB to YCbCr image data. |
| YCbCrSubSampling | `530` | The sampling ratio of chrominance components in relation to the luminance component. |
| YCbCrPositioning | `531` | The position of chrominance components in relation to the luminance component. This field is designated only for JPEG compressed data or uncompressed YCbCr data. The TIFF default is 1 (centered); but when Y:Cb:Cr = 4:2:2 it is recommended in this standard that 2 (co-sited) be used to record data, in order to improve the image quality when viewed on TV systems. When this field does not exist, the reader shall assume the TIFF default. In the case of Y:Cb:Cr = 4:2:0, the TIFF default (centered) is recommended. If the reader does not have the capability of supporting both kinds of YCbCrPositioning, it shall follow the TIFF default regardless of the value in this field. It is preferable that readers " be able to support both centered and co-sited positioning. |
| ReferenceBlackWhite | `532` | The reference black point value and reference white point value. No defaults are given in TIFF, but the values below are given as defaults here. The color space is declared in a color space information tag, with the default being the value that gives the optimal image characteristics Interoperability these conditions |
| Copyright | `33432` | Copyright information. In this standard the tag is used to indicate both the photographer and editor copyrights. It is the copyright notice of the person or organization claiming rights to the image. The Interoperability copyright statement including date and rights should be written in this field; e.g., "Copyright, John Smith, 19xx. All rights reserved.". In this standard the field records both the photographer and editor copyrights, with each recorded in a separate part of the statement. When there is a clear distinction between the photographer and editor copyrights, these are to be written in the order of photographer followed by editor copyright, separated by NULL (in this case since the statement also ends with a NULL, there are two NULL codes). When only the photographer copyright is given, it is terminated by one NULL code . When only the editor copyright is given, the photographer copyright part consists of one space followed by a terminating NULL code, then the editor copyright is given. When the field is left blank, it is treated as unknown. |
| ExposureTime | `33434` | Exposure time, given in seconds. |
| FNumber | `33437` | The F number. |
| ExposureProgram | `34850` | The class of the program used by the camera to set exposure when the picture is taken. |
| SpectralSensitivity | `34852` | Indicates the spectral sensitivity of each channel of the camera used. |
| PhotographicSensitivity | `34855` | Indicates the ISO Speed and ISO Latitude of the camera or input device as specified in ISO 12232. |
| OECF | `34856` | Indicates the Opto-Electric Conversion Function (OECF) specified in ISO 14524. |
| ExifVersion | `36864` | The Exif version. |
| DateTimeOriginal | `36867` | The date and time when the original image data was generated. |
| DateTimeDigitized | `36868` | The date time digitized. |
| ComponentsConfiguration | `37121` | The components' configuration. |
| CompressedBitsPerPixel | `37122` | Specific to compressed data; states the compressed bits per pixel. |
| ShutterSpeedValue | `37377` | The shutter speed value. |
| ApertureValue | `37378` | The lens aperture value. |
| BrightnessValue | `37379` | The brightness value. |
| ExposureBiasValue | `37380` | The exposure bias value. |
| MaxApertureValue | `37381` | The max aperture value. |
| SubjectDistance | `37382` | The distance to the subject, given in meters. |
| MeteringMode | `37383` | The metering mode. |
| LightSource | `37384` | The kind light source. |
| Flash | `37385` | Indicates the status of flash when the image was shot. |
| FocalLength | `37386` | The actual focal length of the lens, in mm. |
| SubjectArea | `37396` | This tag indicates the location and area of the main subject in the overall scene. |
| MakerNote | `37500` | A tag for manufacturers of Exif writers to record any desired information. The contents are up to the manufacturer, but this tag should not be used for any other than its intended purpose. |
| UserComment | `37510` | A tag for Exif users to write keywords or comments on the image besides those in ImageDescription, and without the character code limitations of the ImageDescription tag. |
| SubsecTime | `37520` | A tag used to record fractions of seconds for the DateTime tag. |
| SubsecTimeOriginal | `37521` | A tag used to record fractions of seconds for the DateTimeOriginal tag. |
| SubsecTimeDigitized | `37522` | A tag used to record fractions of seconds for the DateTimeDigitized tag. |
| FlashpixVersion | `40960` | The Flashpix format version supported by a FPXR file. |
| ColorSpace | `40961` | The color space information tag (ColorSpace) is always recorded as the color space specifier. |
| RelatedSoundFile | `40964` | The related sound file. |
| FlashEnergy | `41483` | Indicates the strobe energy at the time the image is captured, as measured in Beam Candle Power Seconds(BCPS). |
| SpatialFrequencyResponse | `41484` | This tag records the camera or input device spatial frequency table and SFR values in the direction of image width, image height, and diagonal direction, as specified in ISO 12233. |
| FocalPlaneXResolution | `41486` | Indicates the number of pixels in the image width (X) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| FocalPlaneYResolution | `41487` | Indicates the number of pixels in the image height (Y) direction per FocalPlaneResolutionUnit on the camera focal plane. |
| FocalPlaneResolutionUnit | `41488` | Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. This value is the same as the ResolutionUnit. |
| SubjectLocation | `41492` | Indicates the location of the main subject in the scene. The value of this tag represents the pixel at the center of the main subject relative to the left edge, prior to rotation processing as per the Rotation tag. |
| ExposureIndex | `41493` | Indicates the exposure index selected on the camera or input device at the time the image is captured. |
| SensingMethod | `41495` | Indicates the image sensor type on the camera or input device. |
| FileSource | `41728` | The file source. |
| SceneType | `41729` | Indicates the type of scene. If a DSC recorded the image, this tag value shall always be set to 1, indicating that the image was directly photographed. |
| CFAPattern | `41730` | Indicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. It does not apply to all sensing methods. |
| CustomRendered | `41985` | This tag indicates the use of special processing on image data, such as rendering geared to output. When special processing is performed, the reader is expected to disable or minimize any further processing. |
| ExposureMode | `41986` | This tag indicates the exposure mode set when the image was shot. In auto-bracketing mode, the camera shoots a series of frames of the same scene at different exposure settings. |
| WhiteBalance | `41987` | This tag indicates the white balance mode set when the image was shot. |
| DigitalZoomRatio | `41988` | This tag indicates the digital zoom ratio when the image was shot. If the numerator of the recorded value is 0, this indicates that digital zoom was not used. |
| FocalLengthIn35MmFilm | `41989` | This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. A value of 0 means the focal length is unknown. Note that this tag differs from the FocalLength tag. |
| SceneCaptureType | `41990` | This tag indicates the type of scene that was shot. It can also be used to record the mode in which the image was shot. |
| GainControl | `41991` | This tag indicates the degree of overall image gain adjustment. |
| Contrast | `41992` | This tag indicates the direction of contrast processing applied by the camera when the image was shot. |
| Saturation | `41993` | This tag indicates the direction of saturation processing applied by the camera when the image was shot. |
| Sharpness | `41994` | This tag indicates the direction of sharpness processing applied by the camera when the image was shot |
| DeviceSettingDescription | `41995` | This tag indicates information on the picture-taking conditions of a particular camera model. The tag is used only to indicate the picture-taking conditions in the reader. |
| SubjectDistanceRange | `41996` | This tag indicates the distance to the subject. |
| ImageUniqueID | `42016` | The image unique id. |
| GPSVersionID | `0` | Indicates the version of GPSInfoIFD. |
| GPSLatitudeRef | `1` | Indicates whether the latitude is north or south latitude. |
| GPSLatitude | `2` | Indicates the latitude. The latitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If latitude is expressed as degrees, minutes and seconds, a typical format would be dd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Indicates whether the longitude is east or west longitude. |
| GPSLongitude | `4` | Indicates the longitude. The longitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If longitude is expressed as degrees, minutes and seconds, a typical format would be ddd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Indicates the altitude used as the reference altitude. If the reference is sea level and the altitude is above sea level, 0 is given. If the altitude is below sea level, a value of 1 is given and the altitude is indicated as an absolute value in the GPSAltitude tag. |
| GPSAltitude | `6` | Indicates the altitude based on the reference in GPSAltitudeRef. Altitude is expressed as one RATIONAL value. The reference unit is meters. |
| GPSTimestamp | `7` | Indicates the time as UTC (Coordinated Universal Time). TimeStamp is expressed as three RATIONAL values giving the hour, minute, and second. |
| GPSSatellites | `8` | Indicates the GPS satellites used for measurements. This tag can be used to describe the number of satellites, their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not specified. If the GPS receiver is incapable of taking measurements, value of the tag shall be set to NULL. |
| GPSStatus | `9` | Indicates the status of the GPS receiver when the image is recorded. |
| GPSMeasureMode | `10` | Indicates the GPS measurement mode. - 2- or 3- dimensional. |
| GPSDOP | `11` | Indicates the GPS DOP (data degree of precision). An HDOP value is written during two-dimensional measurement, and PDOP during three-dimensional measurement. |
| GPSSpeedRef | `12` | Indicates the unit used to express the GPS receiver speed of movement. 'K' 'M' and 'N' represents kilometers per hour, miles per hour, and knots. |
| GPSSpeed | `13` | Indicates the speed of GPS receiver movement. |
| GPSTrackRef | `14` | Indicates the reference for giving the direction of GPS receiver movement. 'T' denotes true direction and 'M' is magnetic direction. |
| GPSTrack | `15` | Indicates the direction of GPS receiver movement. The range of values is from 0.00 to 359.99. |
| GPSImgDirectionRef | `16` | Indicates the reference for giving the direction of the image when it is captured. 'T' denotes true direction and 'M' is magnetic direction. |
| GPSImgDirection | `17` | Indicates the direction of the image when it was captured. The range of values is from 0.00 to 359.99. |
| GPSMapDatum | `18` | Indicates the geodetic survey data used by the GPS receiver. |
| GPSDestLatitudeRef | `19` | Indicates whether the latitude of the destination point is north or south latitude. The ASCII value 'N' indicates north latitude, and 'S' is south latitude. |
| GPSDestLatitude | `20` | Indicates the latitude of the destination point. The latitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If latitude is expressed as degrees, minutes and seconds, a typical format would be dd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Indicates whether the longitude of the destination point is east or west longitude. ASCII 'E' indicates east longitude, and 'W' is west longitude. |
| GPSDestLongitude | `22` | Indicates the longitude of the destination point. The longitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If longitude is expressed as degrees, minutes and seconds, a typical format would be ddd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Indicates the reference used for giving the bearing to the destination point. 'T' denotes true direction and 'M' is magnetic direction. |
| GPSDestBearing | `24` | Indicates the bearing to the destination point. The range of values is from 0.00 to 359.99. |
| GPSDestDistanceRef | `25` | Indicates the unit used to express the distance to the destination point. 'K', 'M' and 'N' represent kilometers, miles and knots. |
| GPSDestDistance | `26` | Indicates the distance to the destination point. |
| GPSProcessingMethod | `27` | A character string recording the name of the method used for location finding. The first byte indicates the character code used, and this is followed by the name of the method. |
| GPSAreaInformation | `28` | A character string recording the name of the GPS area. The first byte indicates the character code used, and this is followed by the name of the GPS area. |
| GPSDateStamp | `29` | A character string recording date and time information relative to UTC (Coordinated Universal Time). The format is YYYY:MM:DD. |
| GPSDifferential | `30` | Indicates whether differential correction is applied to the GPS receiver. |
| StripOffsets | `273` | For each strip, the byte offset of that strip. It is recommended that this be selected so the number of strip bytes does not exceed 64 Kbytes. Aux tag. |
| JPEGInterchangeFormat | `513` | The offset to the start byte (SOI) of JPEG compressed thumbnail data. This is not used for primary image JPEG data. |
| JPEGInterchangeFormatLength | `514` | The number of bytes of JPEG compressed thumbnail data. This is not used for primary image JPEG data. JPEG thumbnails are not divided but are recorded as a continuous JPEG bitstream from SOI to EOI. Appn and COM markers should not be recorded. Compressed thumbnails must be recorded in no more than 64 Kbytes, including all other data to be recorded in APP1. |
| ExifIfdPointer | `34665` | A pointer to the Exif IFD. Interoperability, Exif IFD has the same structure as that of the IFD specified in TIFF. ordinarily, however, it does not contain image data as in the case of TIFF. |
| GPSIfdPointer | `34853` | The gps ifd pointer. |
| RowsPerStrip | `278` | The number of rows per strip. This is the number of rows in the image of one strip when an image is divided into strips. |
| StripByteCounts | `279` | The total number of bytes in each strip. |
| PixelXDimension | `40962` | Information specific to compressed data. When a compressed file is recorded, the valid width of the meaningful image shall be recorded in this tag, whether there is padding data or a restart marker. |
| PixelYDimension | `40963` | Information specific to compressed data. When a compressed file is recorded, the valid height of the meaningful image shall be recorded in this tag |
| Gamma | `42240` | Gamma value |
| SensitivityType | `34864` | Type of photographic sensitivity |
| StandardOutputSensitivity | `34865` | Indicates standard output sensitivity of camera |
| RecommendedExposureIndex | `34866` | Indicates recommended exposure index |
| ISOSpeed | `34867` | Information about ISO speed value as defined in ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | This tag indicates ISO speed latitude yyy value as defined in ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | This tag indicates ISO speed latitude zzz value as defined in ISO 12232 |
| CameraOwnerName | `42032` | Contains camera owner name |
| BodySerialNumber | `42033` | Contains camera body serial number |
| LensMake | `42035` | This tag records lens manufacturer |
| LensModel | `42036` | This tag records lens`s model name and model number |
| LensSerialNumber | `42037` | This tag records the serial number of interchangeable lens |
| LensSpecification | `42034` | This tag notes minimum focal length, maximum focal length, minimum F number in the minimum focal length and minimum F number in maximum focal length |

### See Also

* namespace [Aspose.Imaging.Exif](../../aspose.imaging.exif/)
* assembly [Aspose.Imaging](../../)


