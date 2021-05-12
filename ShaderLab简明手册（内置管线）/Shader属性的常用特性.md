1. NoScaleOffset（隐藏Tiling和Offset）

`[NoScaleOffset]_MainTex ("Texture", 2D) = "white" {}`


如果不想在InSpector面板上被人修改，可以用这个特性隐藏掉

2. Normal（法线纹理）

`[Normal]_NormalTexture("Normal Texture",2D) = "white" {}`

3. HDR

`[HDR]_MainColor("Main Color",Color) = (1,1,1,1)`

4. HideInInSpector（InSpector面板隐藏）

`[HideInInSpector]_FloatValue("Float Value",Float) = 0`

5. Toggle

`[Toggle]_IsFloat("Is Float",Float) = 0`

6. IntRange（整数滑动条）

`[IntRange]_Alpha("Alpha",Range(0,255)) = 0`

7. Space（垂直间隔）

`[Space]_Prop1("Prop1",Float) = 0`


也可以加数字增大间隔

`[Space(50)]_Prop2("Prop2",Float) = 0`

8. Header（标题头）

`[Header(Title)]_Title("Title",Float) = 0`

9. PowerSlider（指数式的滑动条）

`[PowerSlider(3.0)]_Shininess("Shininess",Range(0,1)) = 0`

10. Enum（枚举）

`[Enum(Zero,0,One,1,Two,2,Three,3)] _Number ("Number", Float) = 0`

11. KeywordEnum（枚举）

`[KeywordEnum(None,Add,Multiply)]_Overlay("OverLay Mode",Float) = 0`


KeywordEnum和Enum使用上有些不同，区别在于KeywordEnum类似于if-else，同时在shader代码中需要处理

定义如下：

![img](Shader%E5%B1%9E%E6%80%A7%E7%9A%84%E5%B8%B8%E7%94%A8%E7%89%B9%E6%80%A7.assets/20200421113212796.png) 

使用如下：

 ![img](Shader%E5%B1%9E%E6%80%A7%E7%9A%84%E5%B8%B8%E7%94%A8%E7%89%B9%E6%80%A7.assets/20200421113507377.png) 