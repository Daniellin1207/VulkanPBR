# VulkanPBR
基于Vulkan实现PBR的训练  

![](https://img.shields.io/badge/language-Vulkan-green.svg)
![](https://img.shields.io/badge/target-PBR-redgreen.svg)  

**什么是Vulkan:**  

    Vulkan是一个跨平台的2D和3D绘图应用程序接口(API)最早由科纳斯组织在2015年游戏开发者大会(GDC)上发表。
    科纳斯最先把VulkanAPI称为“次世代OpenGL行动”（next generation OpenGL initiative）或“glNext”, 但在正式宣布Vulkan之后这些名字就没有再使用了。
    就像OpenGL，Vulkan针对实时3D程序（如电子游戏）设计，Vulkan并计划提供高性能和低CPU管理负担(overhead)，这也是Direct3D12和AMD的Mantle的目标。
    Vulkan兼容Mantle的一个分支, 并使用了Mantle的一些组件。
    (引用自度娘 url:https://baike.baidu.com/item/Vulkan/17543632?fr=aladdin)

**Vulkan与Opengl的优劣**  

    在高分辨率、高画质、需要GPU发挥的时候，Vulkan、OpenGL的速度基本差不多。
    但是随着分辨率的降低，CPU越来越重要，Vulkan逐渐体现了出来，尤其是看看GTX 980 Ti，最多可以领先OpenGL 33％之多！

    Vulkan 是和 DirectX 12 类似的跨平台底层 API，Vulkan 和 DirectX 12 都是基于 AMD 开源的 Mantle API，
    事实上两者的早期文档就是将 AMD 的 Mantle 文档修改一下名字。

    自1992年问世以来，OpenGL已经成为了PC游戏迄今为止最常用的图形API之一。
    作为一种多语言、跨平台的应用程序编程接口，它已经被广泛用于GPU的交互和硬件加速。

    使用至今，人们当然也发现了它的缺点。因为源代码是90年代的产物，对于目前在市面上大行其道的多核CPU（GPU）利用效率不佳，
    往往只能提供有限的单线程负载，所以帧率、能耗都难取得突破。
    (引用自网址: https://www.cnblogs.com/bluestorm/p/6724367.html)

**什么是PBR:**  

    PBR全称(Physicallly-Based Rendering)。
    笼统的说，就字面含义可以看出，这是一种基于物理规律模拟的一种渲染技术。
    最早用于电影的照片级真实的渲染。
    近几年由于硬件性能的不断提高，已经大量运用于PC游戏与主机游戏的实时渲染。  
    (引用自网址: https://www.jianshu.com/p/d2c97d0646d5?open_source=weibo_search)

**参考:**

    见上。

**结语:**  
    
    祝大家学习愉快，入坑快乐~

