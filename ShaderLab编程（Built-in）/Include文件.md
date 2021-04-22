# 内置着色器 include 文件

Unity 提供了若干文件供[着色器程序](file://E:\Unity\UnityDocumentation\Manual\SL-ShaderPrograms.html)用于引入预定义的变量和 实用函数。这可以通过标准 `#include` 指令来完成，例如：

```
CGPROGRAM
// ...
#include"UnityCG.cginc"
// ...
ENDCG
```

Unity 中的着色器 include 文件采用 `.cginc` 扩展名，内置的着色器 include 文件包括：

- `HLSLSupport.cginc` -_（自动包含）_用于跨平台着色器编译的 实用宏和定义。
- `UnityShaderVariables.cginc` -_（自动包含）_常用的全局变量。
- `UnityCG.cginc` - 常用的 [实用函数](实用函数.md)。
- `AutoLight.cginc` - 光照和阴影功能，例如==表面着色器==在内部使用此文件。
- `Lighting.cginc` - 标准==表面着色器==光照模型；当您编写表面着色器时会自动包含。
- `TerrainEngine.cginc` - 地形和植被着色器的 实用函数。

如果您要查看任何 实用代码具体执行的操作，可在 Unity 应用程序中找到这些文件（Windows 上位于 **{unity 安装路径}/Data/CGIncludes/UnityCG.cginc__，Mac 上位于** /Applications/Unity/Unity.app/Contents/CGIncludes/UnityCG.cginc__）。

## HLSLSupport.cginc

编译 CGPROGRAM 着色器时会自动包含此文件（但不会对 HLSLPROGRAM 着色器包含此文件）。此文件声明各种[预处理器宏](宏定义.md)以帮助进行多平台着色器开发。

## UnityShaderVariables.cginc

编译 CGPROGRAM 着色器时会自动包含此文件（但不会对 HLSLPROGRAM 着色器包含此文件）。此文件声明着色器中常用的各种[内置全局变量](变量.md)。

## UnityCG.cginc

Unity 着色器中通常会包含此文件。此文件声明大量[内置 实用函数](实用函数.md)和数据结构。

#### UnityCG.cginc 中的数据结构

- struct `appdata_base`：顶点着色器输入，包含位置、法线和一个纹理坐标。
- struct `appdata_tan`：顶点着色器输入，包含位置、法线、切线和一个纹理坐标。
- struct `appdata_full`：顶点着色器输入，包含位置、法线、切线、顶点颜色和两个纹理坐标。
- struct `appdata_img`: 顶点着色器输入，包含位置和一个纹理坐标。