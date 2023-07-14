# Unity_ColorCollectionShader

Shader functions to color collection.

## Functions

```hlsl
float4 RgbToHsv(float4 rgb)
float4 HsvToRgb(float4 hsv)
float4 RgbToHsl(float4 rgb)
float4 HslToRgb(float4 hsl)

float4 HsvShift(float4 rgb, float4 shift)
float4 HslShift(float4 rgb, float4 shift)

float4 GrayScale(float4 color)
float4 GrayScaleREC601(float4 color)
float4 GrayScaleREC709(float4 color)

float4 BrightnessSaturationContrast
(float4 color, float brightness, float saturation, float contrast)

float4 ColorCollection
(float4 color, float4 bscPrams, float4 hsvShift)
```

## Importing

You can use Package Manager or import it directly.

```
https://github.com/XJINE/Unity_ColorCollectionShader.git?path=Assets/Packages/ColorCollectionShader
```