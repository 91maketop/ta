下表列出了 HLSL 中可用的内部函数。 每个函数都有简短说明，并提供指向有关输入参数和返回类型的更多详细信息的参考页的链接。

| 名称                                                         | 说明                                                         |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [**abort**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/abort) | 终止正在执行的当前绘图或调度调用。                           |
| [**abs**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-abs) | 每个组件) (绝对值。                                          |
| [**acos**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-acos) | 返回 x 的每个分量的反余弦。                                  |
| [**all**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-all) | 测试 x 的所有组件是否为非零。                                |
| [**AllMemoryBarrier**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/allmemorybarrier) | 阻止组中所有线程的执行，直到所有内存访问都完成。             |
| [**AllMemoryBarrierWithGroupSync**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/allmemorybarrierwithgroupsync) | 阻止组中所有线程的执行，直到所有内存访问都完成并且组中的所有线程都达到此调用。 |
| [**any**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-any) | 测试 x 的任何组件是否为非零。                                |
| [**asdouble**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/asdouble) | 重新解释将转换值转换为双精度值。                             |
| [**asfloat**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-asfloat) | 将输入类型转换为 float。                                     |
| [**asin**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-asin) | 返回 x 的每个分量的反正弦。                                  |
| [**asint**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-asint) | 将输入类型转换为整数。                                       |
| [**asuint**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/asuint) | 将64位类型的位模式重新解释为 uint。                          |
| [**asuint**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-asuint) | 将输入类型转换为无符号整数。                                 |
| [**atan**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-atan) | 返回 x 的反正切值。                                          |
| [**atan2**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-atan2) | 返回两个值的反正切值 (x，y) 。                               |
| [**ceil**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-ceil) | 返回大于或等于 x 的最小整数。                                |
| [**CheckAccessFullyMapped**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/checkaccessfullymapped) | 确定 **示例** 或 **加载** 操作中的所有值是否都访问了 [平铺资源](https://docs.microsoft.com/zh-cn/windows/desktop/direct3d11/direct3d-11-2-features)中的映射磁贴。 |
| [**clamp**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-clamp) | 夹紧 x 到最 [ 小值，最大值 ] 。                              |
| [**clip**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-clip) | 如果 x 的任何分量小于零，则放弃当前像素。                    |
| [**cos**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-cos) | 返回 x 的余弦值。                                            |
| [**cosh**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-cosh) | 返回 x 的双曲余弦值。                                        |
| [**countbits**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/countbits) | 计算输入整数中每个组件) (的位数。                            |
| [**cross**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-cross) | 返回两个三维向量的叉积。                                     |
| [**D3DCOLORtoUBYTE4**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-d3dcolortoubyte4) | Swizzles 和缩放4D 向量 xto 的组件补偿某些硬件中是否缺少 UBYTE4 支持。 |
| [**ddx**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-ddx) | 返回 x 的部分导数，相对于屏幕空间 x 坐标。                   |
| [**ddy**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-ddy) | 返回 x 的部分导数，与屏幕空间的 y 坐标有关。                 |
| [**degrees**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-degrees) | 将 x 从弧度转换为度。                                        |
| [**diterminant**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-determinant) | 返回正方形 matrix m 的行列式。                               |
| [**DeviceMemoryBarrier**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/devicememorybarrier) | 阻止组中所有线程的执行，直到所有设备内存访问都完成。         |
| [**DeviceMemoryBarrierWithGroupSync**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/devicememorybarrierwithgroupsync) | 阻止组中所有线程的执行，直到所有设备内存访问完成并且组中的所有线程都达到此调用。 |
| [**distance**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-distance) | 返回两个点之间的距离。                                       |
| [**dot**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-dot) | 返回两个向量的点积。                                         |
| [**dst**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dst) | 计算距离向量。                                               |
| [**errorf**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/errorf) | 向信息队列提交一条错误消息。                                 |
| [**EvaluateAttributeAtCentroid**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/evaluateattributeatcentroid) | 计算像素质心。                                               |
| [**EvaluateAttributeAtSample**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/evaluateattributeatsample) | 在索引样本位置计算。                                         |
| [**EvaluateAttributeSnapped**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/evaluateattributesnapped) | 计算带有偏移量的质心的像素。                                 |
| [**.exp**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-exp) | 返回以 e 为底的指数。                                        |
| [**exp2**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-exp2) | 每个组件) 以2为底的指数 (。                                  |
| [**f16tof32**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/f16tof32) | 将在 uint 的下半部分中存储的 float16 转换为 float。          |
| [**f32tof16**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/f32tof16) | 将输入转换为 float16 类型。                                  |
| [**faceforward**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-faceforward) | 返回-n * 符号 (点 (i，ng) ) 。                               |
| [**firstbithigh**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/firstbithigh) | 获取第一组位的位置，从最高顺序位开始，按组件向下移动。       |
| [**firstbitlow**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/firstbitlow) | 返回第一组位的位置（从最低顺序位开始，按组件向上处理）。     |
| [**floor**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-floor) | 返回小于或等于 x 的最大整数。                                |
| [**fma**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-fma) | 返回一个与 b + c 的双精度的带外乘法 * 。                     |
| [**fmod**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-fmod) | 返回 x/y 的浮点余数。                                        |
| [**frac**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-frac) | 返回 x 的小数部分。                                          |
| [**frexp**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-frexp) | 返回 x 的尾数和指数。                                        |
| [**fwidth**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-fwidth) | 返回 abs (ddx (x) ) + abs (ddy (x) )                         |
| [**GetRenderTargetSampleCount**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-getrendertargetsamplecount) | 返回呈现器目标样本的数目。                                   |
| [**GetRenderTargetSamplePosition**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-getrendertargetsampleposition) | 返回给定示例索引 (x，y) 的位置。                             |
| [**GroupMemoryBarrier**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/groupmemorybarrier) | 阻止组中所有线程的执行，直到所有组共享访问都完成。           |
| [**GroupMemoryBarrierWithGroupSync**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/groupmemorybarrierwithgroupsync) | 阻止组中所有线程的执行，直到所有组共享访问完成并且组中的所有线程都达到此调用。 |
| [**InterlockedAdd**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/interlockedadd) | 执行保证的原子值向目标资源变量的原子性。                     |
| [**InterlockedAnd**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/interlockedand) | 执行保证的原子和。                                           |
| [**InterlockedCompareExchange**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/interlockedcompareexchange) | 以原子方式将输入与比较值进行比较并交换结果。                 |
| [**InterlockedCompareStore**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/interlockedcomparestore) | 以原子方式将输入与比较值进行比较。                           |
| [**InterlockedExchange**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/interlockedexchange) | 将值分配给 dest 并返回原始值。                               |
| [**InterlockedMax**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/interlockedmax) | 执行保证的原子最大值。                                       |
| [**InterlockedMin**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/interlockedmin) | 执行保证的原子最小值。                                       |
| [**InterlockedOr**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/interlockedor) | 执行保证的原子或。                                           |
| [**InterlockedXor**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/interlockedxor) | 执行保证的原子 xor。                                         |
| [**isfinite**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-isfinite) | 如果 x 是有限的，则返回 true，否则返回 false。               |
| [**isinf**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-isinf) | 如果 x 为 + INF 或-INF，则返回 true，否则返回 false。        |
| [**isnan**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-isnan) | 如果 x 为 NAN 或 QNAN，则返回 true，否则返回 false。         |
| [**ldexp**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-ldexp) | 返回 x * 2exp                                                |
| [**length**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-length) | 返回向量 v 的长度。                                          |
| [**lerp**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-lerp) | 返回 (y-x) 的 x + s。                                        |
| [**lit**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-lit) | 返回光源向量 (环境、漫射、镜面、1)                           |
| [**log**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-log) | 返回 x 的以 e 为底的对数。                                   |
| [**log10**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-log10) | 返回 x 的以10为底的对数。                                    |
| [**log2**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-log2) | 返回 x 的以2为底的对数。                                     |
| [**mad**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/mad) | 对三个值执行算术乘/加法运算。                                |
| [**max**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-max) | 选择 x 和 y 的较大。                                         |
| [**min**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-min) | 选择 x 和 y 中的较小者。                                     |
| [**modf**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-modf) | 将值 x 拆分为小数部分和整数部分。                            |
| [**msad4**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-msad4) | 比较4个字节的引用值和8个字节的源值，并累计4个和的向量。      |
| [**mul**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-mul) | 使用 x 和 y 执行矩阵乘法。                                   |
| [**noise**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-noise) | 使用 Perlin-干扰算法生成随机值。                             |
| [**normalize**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-normalize) | 返回规范化向量。                                             |
| [**pow**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-pow) | 返回 xy。                                                    |
| [**printf**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/printf) | 将自定义着色器消息提交到信息队列。                           |
| [**Process2DQuadTessFactorsAvg**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/process2dquadtessfactorsavg) | 为四个修补程序生成已更正的分割系数。                         |
| [**Process2DQuadTessFactorsMax**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/process2dquadtessfactorsmax) | 为四个修补程序生成已更正的分割系数。                         |
| [**Process2DQuadTessFactorsMin**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/process2dquadtessfactorsmin) | 为四个修补程序生成已更正的分割系数。                         |
| [**ProcessIsolineTessFactors**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/processisolinetessfactors) | 生成等值线的舍入分割系数。                                   |
| [**ProcessQuadTessFactorsAvg**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/processquadtessfactorsavg) | 为四个修补程序生成已更正的分割系数。                         |
| [**ProcessQuadTessFactorsMax**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/processquadtessfactorsmax) | 为四个修补程序生成已更正的分割系数。                         |
| [**ProcessQuadTessFactorsMin**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/processquadtessfactorsmin) | 为四个修补程序生成已更正的分割系数。                         |
| [**ProcessTriTessFactorsAvg**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/processtritessfactorsavg) | 生成适用于三个修补程序的已更正分割系数。                     |
| [**ProcessTriTessFactorsMax**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/processtritessfactorsmax) | 生成适用于三个修补程序的已更正分割系数。                     |
| [**ProcessTriTessFactorsMin**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/processtritessfactorsmin) | 生成适用于三个修补程序的已更正分割系数。                     |
| [**radians**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-radians) | 将 x 转换为弧度。                                            |
| [**rcp**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/rcp) | 计算快速、近似、按分量的倒数。                               |
| [**reflect**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-reflect) | 返回反射向量。                                               |
| [**refract**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-refract) | 返回折射向量。                                               |
| [**reversebits**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/reversebits) | 为每个分量反转位的顺序。                                     |
| [**round**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-round) | 将 x 舍入到最接近的整数                                      |
| [**rsqrt**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-rsqrt) | 返回 1/sqrt (x)                                              |
| [**saturate**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-saturate) | 夹紧 x 到 [ 0，1]                                            |
| [**sign**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-sign) | 计算 x 的符号。                                              |
| [**sin**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-sin) | 返回 x 的正弦值                                              |
| [**sincos**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-sincos) | 返回 x 的正弦和余弦值。                                      |
| [**sinh**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-sinh) | 返回 x 的双曲正弦值                                          |
| [**smoothstep**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-smoothstep) | 返回介于0和1之间的平滑 Hermite 内插。                        |
| [**sqrt**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-sqrt) | 每个组件 (平方根)                                            |
| [**step**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-step) | 返回 (x >=) ？ 1 : 0                                         |
| [**tan**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tan) | 返回 x 的正切值                                              |
| [**tanh**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tanh) | 返回 x 的双曲正切值                                          |
| [**tex1D (s，t)**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex1d) | 1D 纹理查找。                                                |
| [**tex1D (s、t、ddx、ddy)**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex1d-s-t-ddx-ddy) | 1D 纹理查找。                                                |
| [**tex1Dbias**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex1dbias) | 带有偏移的一维纹理查找。                                     |
| [**tex1Dgrad**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex1dgrad) | 使用渐变的一维纹理查找。                                     |
| [**tex1Dlod**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex1dlod) | 用 LOD 的一维纹理查找。                                      |
| [**tex1Dproj**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex1dproj) | 用 projective 相除的1D 纹理查找。                            |
| [**tex2D (s，t)**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex2d) | 2D 纹理查找。                                                |
| [**tex2D (s、t、ddx、ddy)**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex2d-s-t-ddx-ddy) | 2D 纹理查找。                                                |
| [**tex2Dbias**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex2dbias) | 带有偏移的2D 纹理查找。                                      |
| [**tex2Dgrad**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex2dgrad) | 使用渐变的2D 纹理查找。                                      |
| [**tex2Dlod**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex2dlod) | 2D 纹理查找和 LOD。                                          |
| [**tex2Dproj**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex2dproj) | projective 相除的2D 纹理查找。                               |
| [**tex3D (s，t)**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex3d) | 3D 纹理查找。                                                |
| [**tex3D (s、t、ddx、ddy)**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex3d-s-t-ddx-ddy) | 3D 纹理查找。                                                |
| [**tex3Dbias**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex3dbias) | 带有偏置的3D 纹理查找。                                      |
| [**tex3Dgrad**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex3dgrad) | 使用渐变的3D 纹理查找。                                      |
| [**tex3Dlod**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex3dlod) | 用 LOD 的3D 纹理查找。                                       |
| [**tex3Dproj**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-tex3dproj) | 带有 projective 除法的3D 纹理查找。                          |
| [**texCUBE (s，t)**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-texcube) | 多维数据集纹理查找。                                         |
| [**texCUBE (s、t、ddx、ddy)**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-texcube-s-t-ddx-ddy) | 多维数据集纹理查找。                                         |
| [**texCUBEbias**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-texcubebias) | 带有偏移的多维数据集纹理查找。                               |
| [**texCUBEgrad**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-texcubegrad) | 使用渐变的多维数据集纹理查找。                               |
| [**texCUBElod**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-texcubelod) | LOD 的多维数据集纹理查找。                                   |
| [**texCUBEproj**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-texcubeproj) | Projective 相除的多维数据集纹理查找。                        |
| [**transpose**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-transpose) | 返回矩阵 m 的转置。                                          |
| [**trunc**](https://docs.microsoft.com/zh-cn/windows/win32/direct3dhlsl/dx-graphics-hlsl-trunc) | 将) (的浮点值截断到整数值 (s)                                |