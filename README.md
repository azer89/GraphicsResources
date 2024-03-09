A list of graphics/Vulkan/C++ resources that I find interesting.

### General
* [Vulkan Guide](https://github.com/vblanco20-1/vulkan-guide)
* [3D Graphics Rendering Cookbook](https://github.com/PacktPublishing/3D-Graphics-Rendering-Cookbook)
* [Vulkan Discord](https://discord.com/invite/vulkan) *Hightly recommended*
* [AMD - Understanding Vulkan Objects](https://gpuopen.com/learn/understanding-vulkan-objects/)
* [Zeux - Writing an efficient Vulkan renderer](https://zeux.io/2020/02/27/writing-an-efficient-vulkan-renderer/)
* [docs.vulkan.org](https://docs.vulkan.org/)
* Charles G - Common Mistakes When Learning Vulkan [Presentation](https://vulkan.org/user/pages/09.events/vulkanised-2024/vulkanised-2024-charles-giessen-2-lunarg.pdf) [Video](https://www.youtube.com/watch?v=0OqJtPnkfC8)
* [Khronos - Vulkan Samples](https://docs.vulkan.org/samples/latest/README.html)

### Compute Shaders
* [Vulkan Guide - Compute Shaders](https://vkguide.dev/docs/gpudriven/compute_shaders/)
* [Vulkan-Tutorial - Compute Shaders](https://vulkan-tutorial.com/Compute_Shader)

### Synchronization
* [The Maister - Yet another blog explaining Vulkan synchronization](https://themaister.net/blog/2019/08/14/yet-another-blog-explaining-vulkan-synchronization/)
* [AMD - Vulkan Barriers Explained](https://gpuopen.com/learn/vulkan-barriers-explained/)
* [Khronos - Using pipeline barriers efficiently](https://github.com/KhronosGroup/Vulkan-Samples/blob/main/samples/performance/pipeline_barriers/README.adoc)
* [Khronos - Synchronization Examples](https://github.com/KhronosGroup/Vulkan-Docs/wiki/Synchronization-Examples)
* [Khronos - Synchronization Examples (Legacy)](https://github.com/KhronosGroup/Vulkan-Docs/wiki/Synchronization-Examples-(Legacy-synchronization-APIs))
* [Stackoverflow - Why is a single depth buffer sufficient for this vulkan swapchain render loop?](https://stackoverflow.com/questions/62371266/why-is-a-single-depth-buffer-sufficient-for-this-vulkan-swapchain-render-loop)

### Clustered Forward Shading
* [Olsson et al. -  Clustered Deferred and Forward Shading](https://www.cse.chalmers.se/~uffe/clustered_shading_preprint.pdf)
* [Emil Persson - Practical Clustered Shading](https://www.humus.name/Articles/PracticalClusteredShading.pdf)
* [Van Oosten Thesis](https://www.3dgep.com/wp-content/uploads/2017/07/3910539_Jeremiah_van_Oosten_Volume_Tiled_Forward_Shading.pdf)
* [Id - The Devil is in Details](https://advances.realtimerendering.com/s2016/Siggraph2016_idTech6.pdf)
* [Id - Rendering Doom Eternal](https://advances.realtimerendering.com/s2020/RenderingDoomEternal.pdf)
* [Michal Drobot - Improved Culling for Tiled and Clustered Rendering](https://advances.realtimerendering.com/s2017/2017_Sig_Improved_Culling_final.pdf)
* [Aortiz - A Primer On Efficient Rendering Algorithms & Clustered Shading](https://www.aortiz.me/2018/12/21/CG.html)

### Shadow Mapping
* [Nikolas Kasyan - Playing with Real-Time Shadows](https://www.realtimeshadows.com/sites/default/files/Playing%20with%20Real-Time%20Shadows_0.pdf)
* [LearnOpenGL - Cascade Shadow Mapping](https://learnopengl.com/Guest-Articles/2021/CSM)
* [OGLDev - Cascade Shadow Mapping](https://ogldev.org/www/tutorial49/tutorial49.html)
* [MJP - Shadows](https://github.com/TheRealMJP/Shadows)
* [Microsoft - Common Techniques to Improve Shadow Depth Maps](https://learn.microsoft.com/en-us/windows/win32/dxtecharts/common-techniques-to-improve-shadow-depth-maps)
* [Digital Rune - Shadow Mapping](https://digitalrune.github.io/DigitalRune-Documentation/html/3f82c46b-efec-4416-807f-670ac1930117.htm)
* [Louis Bavoil - Advanced Soft Shadow Mapping Techniques](https://developer.download.nvidia.com/presentations/2008/GDC/GDC08_SoftShadowMapping.pdf)

### Raytracing
* [Khronos - Raytracing in Vulkan](https://www.khronos.org/blog/ray-tracing-in-vulkan)
* [Khronos - Vulkan Raytracing Final Specification](https://www.khronos.org/blog/vulkan-ray-tracing-final-specification-release)
* [NVPro](https://nvpro-samples.github.io/vk_raytracing_tutorial_KHR/)
* [NVPro - Samples](https://github.com/nvpro-samples/vk_raytracing_tutorial_KHR)
* [SaschaWillems - VulkanPathTracer](https://github.com/SaschaWillems/VulkanPathTracer)

### ReSTIR
* [Benedikt Bitterli - SIGGRAPH 2020 Paper](https://benedikt-bitterli.me/restir/)
* [ReSTIR Vulkan](https://github.com/lukedan/ReSTIR-Vulkan)

### Vulkan Engines/Backends
* [Niagara](https://github.com/zeux/niagara)
* [Facebook IGL](https://github.com/facebook/igl/tree/main/src/igl/vulkan)
* [lightweightvk](https://github.com/corporateshark/lightweightvk)

### Vulkan Memory Allocator
* [VMA Quick Start](https://gpuopen-librariesandsdks.github.io/VulkanMemoryAllocator/html/quick_start.html)
* [VMA Usage Patterns](https://gpuopen-librariesandsdks.github.io/VulkanMemoryAllocator/html/usage_patterns.html)
* VMA and Volk [Stackoverflow](https://stackoverflow.com/questions/73512602/using-vulkan-memory-allocator-with-volk) [Reddit](https://old.reddit.com/r/vulkan/comments/optef4/vulkan_memory_allocator_cant_load_some_vulkan/)

### Bindless Textures
* [Charles Giessen - Exploration of Bindless Rendering](https://www.youtube.com/watch?v=SVm0HanVTRw)
* [Reddit - How to use texture arrays using descriptor indexing](https://www.reddit.com/r/vulkan/comments/tq6c2v/vulkan_bindless_textures_how_to_deal_with/)
* [Vulkan Guide - GPU Driven Rendering](https://vkguide.dev/docs/gpudriven/gpu_driven_engines/)
* [GPU Rendering and Multi-Draw Indirect](https://docs.vulkan.org/samples/latest/samples/performance/multi_draw_indirect/README.html)
* [Wicked Engine - Bindless Descriptors](https://wickedengine.net/2021/04/06/bindless-descriptors/)

### Dynamic Rendering *(sans VkRenderPass)*
* [Lesley Lai - VK_KHR_dynamic_rendering tutorial](https://lesleylai.info/en/vk-khr-dynamic-rendering/)

### Render Graph
* [FrameGraph: Extensible Rendering Architecture in Frostbite](https://www.gdcvault.com/play/1024045/FrameGraph-Extensible-Rendering-Architecture-in)
* [The Maister - Render Graphs and Vulkan](https://themaister.net/blog/2017/08/15/render-graphs-and-vulkan-a-deep-dive/)

### Miscellaneous
* [glslang API](https://chromium.googlesource.com/external/github.com/KhronosGroup/glslang/)
* [Reddit - What exactly is frames in flight?](https://www.reddit.com/r/vulkan/comments/nbu94q/what_exactly_is_the_definition_of_frames_in_flight/)
* [Intel - Frame resources count when using frames-in-flight](https://www.intel.com/content/www/us/en/developer/articles/training/practical-approach-to-vulkan-part-1.html)
* [Jeremy Ong's Blog](https://www.jeremyong.com/)
* [Flower Engine - Image Layout Transition](https://github.com/qiutang98/flower/blob/0414798840c1c4aef4e742f521696378695e7897/source/engine/rhi/resource.cpp#L237)
* [alain.xyz - Comparison of Modern Graphics APIs](https://alain.xyz/blog/comparison-of-modern-graphics-apis)
* [Shader Occupancy](https://gpuopen.com/learn/occupancy-explained/)
* [Early Depth Test](https://www.khronos.org/opengl/wiki/Early_Fragment_Test)
* [MJP - Shader Permutations](https://therealmjp.github.io/posts/shader-permutations-part1/)
* [David Lettier - 3D Game Shaders For Beginners](https://github.com/lettier/3d-game-shaders-for-beginners)
* [Khronos - Mobile NeRF](https://github.com/KhronosGroup/Vulkan-Samples/blob/8ba37b44a693d165c2ab8b9cfdcf1c8774efd407/samples/general/mobile_nerf/README.adoc)

### C++
* [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-functions)
* [Google C++ Guide](https://google.github.io/styleguide/cppguide.html)

### Job Interview
* [Jeremy Ong - Interviewing Graphics Programmers](https://www.jeremyong.com/graphics/interviewing/2023/08/05/graphics-programmer-interviewing/)
* [Erkaman - Interviewing for your First Job as a Graphics Programmer](https://erkaman.github.io/posts/junior_graphics_programmer_interview.html)
