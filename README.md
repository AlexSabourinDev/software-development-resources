# software-development-resources

## What?

A collection of links for various fields of software development (Mostlt Graphics). Mainly game related, most have been read and vetted. If you find any dead links, please submit an issue and I will try to address it as soon as possible.

## Table Of Contents

- [Project Management](#project-management)
  * [Estimation](#estimation)
- [Math](#math)
- [Game Design](#game-design)
- [Languages](#languages)
  * [C](#c)
  * [C plus plus](#c-plus-plus)
  * [C Sharp](#c-sharp)
  * [Misc](#misc)
- [AI](#ai)
- [Rendering](#rendering)
  * [Vulkan](#vulkan)
  * [DX12](#dx12)
  * [Textures And Compression](#textures-and-compression)
  * [Colors](#colors)
  * [Forward, Deferred, Visibility, Etc](#forward-deferred-visibility-etc)
  * [Transparency, Blending](#transparency-blending)
  * [GPU Architecture](#gpu-architecture)
  * [Code](#code)
  * [Particles](#particles)
  * [Shadows](#shadows)
  * [Spherical Harmonics](#spherical-harmonics)
  * [Raytracing](#raytracing)
  * [Blue Noise](#blue-noise)
  * [Graphics Codebases](#graphics-codebases)
  * [Normals And Tangent Spaces](#normals-and-tangent-spaces)
  * [Shaders](#shaders)
    + [Compute Shaders](#compute-shaders)
    + [Geometry Shaders](#geometry-shaders)
    + [Tesselation Shaders](#tesselation-shaders)
    + [Mesh Shaders](#mesh-shaders)
  * [Lighting/Shading](#lightingshading)
    + [Lights](#lights)
    + [BRDFs](#brdfs)
  * [Ambient Occlusion](#ambient-occlusion)
  * [Subsurface Scattering](#subsurface-scattering)
  * [Importance Sampling](#importance-sampling)
    + [ReSTIR](#restir)
  * [Cameras, Exposure, Tonemapping](#cameras-exposure-tonemapping)
  * [Misc](#misc-1)
  * [Occlusion](#occlusion)
  * [Sky Lighting](#sky-lighting)
  * [Depth](#depth)
  * [Signed Distance Fields](#signed-distance-fields)
  * [Tutorials](#tutorials)
  * [Shader Editors](#shader-editors)
- [Floating Point](#floating-point)
- [Algorithms](#algorithms)
- [Networking](#networking)
- [CPU Archicture](#cpu-archicture)
  * [Vectorization](#vectorization)
  * [Optimizations](#optimizations)
- [Retro](#retro)
- [Threading](#threading)
- [Sound](#sound)
- [Collision](#collision)
- [Misc](#misc-2)
- [Unity](#unity)
- [Unreal](#unreal)

## Project Management

* [How We Ended Up With Microservices (Blog Post)](https://philcalcado.com/2015/09/08/how_we_ended_up_with_microservices.html)
* [Maker's Schedule, Manager's Schedule (Blog Post)](http://www.paulgraham.com/makersschedule.html)
* [An epic treatise on scheduling, bug tracking, and triage (Blog Post)](https://apenwarr.ca/log/20171213)
* [Characterizing Software Developers by Perceptions of Productivity (Paper)](https://www.researchgate.net/publication/320959053_Characterizing_Software_Developers_by_Perceptions_of_Productivity)
* [When Culture Doesn’t Translate (Blog Post)](https://hbr.org/2015/10/when-culture-doesnt-translate)

### Estimation

* [Why Software Projects Take Longer Than You Think (Blog Post)](https://erikbern.com/2019/04/15/why-software-projects-take-longer-than-you-think-a-statistical-model.html)
* [Evidence Based Scheduling (Blog Post)](https://www.joelonsoftware.com/2007/10/26/evidence-based-scheduling/)
* [Programmer Time Translation Table (Blog Post)](https://coding.abel.nu/2012/06/programmer-time-translation-table/)
* [2015 Chaos Report (Data)](https://www.standishgroup.com/sample_research_files/CHAOSReport2015-Final.pdf)
* [17 theses software estimation (Blog Post)](https://stevemcconnell.com/blog/17-theses-software-estimation/)

## Math

* [Fourier Transform: A Visualization (Video)](https://www.youtube.com/watch?v=spUNpyF58BY)
* [Waveforms: An Introduction (Article)](http://waveforms.surge.sh/waveforms-intro)
* [Faster Quaternion-Vector Multiplication (Blog Post)](https://blog.molecular-matters.com/2013/05/24/a-faster-quaternion-vector-multiplication/)
* [A primer on Bezier Curves (Online Book)](https://pomax.github.io/bezierinfo/)
* [Quaternion Visualization (Resource)](https://eater.net/quaternions)
* [Thin triangle and other tricks (REVEALED!) (Blog Post)](http://marc-b-reynolds.github.io/math/2019/02/06/Posit1.html)
* [Another View on the classic ray-aabb intersection algorithm for BVH traversal](https://medium.com/@bromanz/another-view-on-the-classic-ray-aabb-intersection-algorithm-for-bvh-traversal-41125138b525)
* [Visualizing Variance (Blog Post)](http://perfdynamics.blogspot.com/2013/01/visualizing-variance.html)
* [Implementing Needlets (Blog Post)](https://basesandframes.wordpress.com/2016/05/22/implementing-needlets/)
* [Frames, Quadratures and Global Illumination: New Math for Games (Slides)](https://basesandframes.files.wordpress.com/2016/05/gdc2012-frames-sparsity-and-global-illumination-1.pdf)
* [Don't Use Moving Averages (Blog Post)](https://observablehq.com/d/a51954c61a72e1ef)

## Game Design

* [Extra Creditz (Youtube Channel)](https://www.youtube.com/user/ExtraCreditz)
* [Designing For Coziness (Article)](https://www.gamasutra.com/blogs/TanyaXShort/20180305/315179/Designing_for_Coziness.php)
* [Learning From The Masters: Level Design In The Legend Of Zelda (Article)](https://www.gamasutra.com/view/feature/134949/learning_from_the_masters_level_.php)

## Languages

### C

* [Strict Aliasing (Article)](https://cellperformance.beyond3d.com/articles/2006/06/understanding-strict-aliasing.html)
* [Minimalist Containers in C(P1) (Blog post)](http://ourmachinery.com/post/minimalist-container-library-in-c-part-1/)
* [Minimalist Containers in C(P2) (Blog post)](http://ourmachinery.com/post/minimalist-container-library-in-c-part-2/)
* [BitHacks (Collection?)](https://graphics.stanford.edu/~seander/bithacks.html)
* [Coroutines in less than 20 lines of standard C (Blog Post)](https://fanf.livejournal.com/105413.html)
* [Coroutines in C (Blog Post)](https://www.chiark.greenend.org.uk/~sgtatham/coroutines.html)
* [Demystifying the restrict Keyword (Blog Post)](https://cellperformance.beyond3d.com/articles/2006/05/demystifying-the-restrict-keyword.html)
* [Shared Libraries (Blog Post)](https://www.ibm.com/developerworks/library/l-shlibs/index.html)
* [Linkers (Blog Series)](https://www.airs.com/blog/archives/38)
* [Fast floating point rand (Blog Post)](http://www.iquilezles.org/www/articles/sfrand/sfrand.htm)
* [A Whirlwind Tutorial on Creating Really Teensy ELF Executables for Linux (Blog Post)](http://www.muppetlabs.com/~breadbox/software/tiny/teensy.html)
* [Basics of futexes (Blog Post)](https://eli.thegreenplace.net/2018/basics-of-futexes/)
* [Anybody who writes #pragma pack(1) may as well just wear a sign on their forehead that says “I hate RISC” (Blog Post](https://devblogs.microsoft.com/oldnewthing/20200103-00/?p=103290)
* [Benchmarking Malloc with Doom 3 (Blog Post)](https://www.forrestthewoods.com/blog/benchmarking-malloc-with-doom3/)
* [Undefined behavior, and the Sledgehammer Principle (Blog Post)](https://thephd.dev/c-undefined-behavior-and-the-sledgehammer-guideline)
* [A bit of background on compilers exploiting signed overflow (Blog Post)](https://gist.github.com/rygorous/e0f055bfb74e3d5f0af20690759de5a7)
* [C Isn't A Programming Language Anymore (Blog Post)](https://faultlore.com/blah/c-isnt-a-language/)
* [How can a program survive a corrupted stack? (Blog Post)](https://devblogs.microsoft.com/oldnewthing/20040116-00/?p=41023)
* [To Save C, We Must Save ABI (Blog Post)](https://thephd.dev/to-save-c-we-must-save-abi-fixing-c-function-abi)

### C plus plus

* [Molecular Musings (C++ Blog)](https://blog.molecular-matters.com/)
* [Perfect Forwarding (Article Series)](http://thbecker.net/articles/rvalue_references/section_01.html)
* [DLL Hot Reloading (Article)](http://ourmachinery.com/post/dll-hot-reloading-in-theory-and-practice/)
* [Thunk and its uses (Article)](https://www.codeproject.com/Articles/27908/Thunk-and-its-uses)
* [How to avoid C/C++ runtime on Windows (Article)](https://hero.handmade.network/forums/code-discussion/t/94-guide_-_how_to_avoid_c_c++_runtime_on_windows)
* [Job System Implementation (Article)](http://danglingpointers.com/post/job-system/)
* [Spin Lock Implementation (Article)](http://danglingpointers.com/post/spinlock-implementation/)
* [Mike Acton DoD Workshop](http://danglingpointers.com/post/mike-actons-dod-workshop-2015/)
* [Handles are the better pointer (Blog Post)](http://floooh.github.io/2018/06/17/handles-vs-pointers.html)
* [Efficient Argument Passing in C++11 (Blog Post)](https://www.codesynthesis.com/~boris/blog/2012/06/19/efficient-argument-passing-cxx11-part1/)
* [Peephole Optimizations in C++ and C# (Blog Post)](https://egorbo.com/peephole-optimizations.html)
* [Optimizations in C++ compilers (Article)](https://queue.acm.org/detail.cfm?id=3372264)
* [References - Simply (Blog Post)](https://herbsutter.com/2020/02/23/references-simply/)
* [Linkers (Blog Series)](https://www.airs.com/blog/archives/38)
* [Optimizations in C++ Compilers (Blog Post)](https://queue.acm.org/detail.cfm?id=3372264)
* [How C++ Resolves A Function Call (Blog Post)](https://preshing.com/20210315/how-cpp-resolves-a-function-call/)
* [The Subtle Dangers of Temporaries in for Loops (Blog Post)](https://www.fluentcpp.com/2021/05/22/the-subtle-dangers-of-temporaries-in-for-loops/)
* [Incrementing Vectors (Blog Post)](https://travisdowns.github.io/blog/2019/08/26/vector-inc.html)
* [The C++20 Naughty and Nice List for Game Devs (Blog Post)](https://www.jeremyong.com/c++/2023/12/24/cpp20-gamedev-naughty-nice/)
* [Optimizing the unoptimizable: a journey to faster C++ compile times (Blog Post)](https://vitaut.net/posts/2024/faster-cpp-compile-times/)

### C Sharp

* [Marshaling in C# (Blog)](https://stackoverflow.com/questions/20600380/how-does-marshal-getfunctionpointerfordelegate-work-on-instance-members)
* [Everyone thinks about garbage collection the wrong way (Blog)](https://devblogs.microsoft.com/oldnewthing/20100809-00/?p=13203)
* [The stack is an implementation detail (Blog)](https://blogs.msdn.microsoft.com/ericlippert/2009/04/27/the-stack-is-an-implementation-detail-part-one/)
* [The Truth About Value Types (Blog)](https://blogs.msdn.microsoft.com/ericlippert/2010/09/30/the-truth-about-value-types/)
* [Debunking another myth about value types (Blog)](https://blogs.msdn.microsoft.com/ericlippert/2010/10/11/debunking-another-myth-about-value-types/)
* [How Generics are implemented in C# (Blog Post)](https://github.com/dotnet/corert/issues/7248#issuecomment-508431669)
* [Construction Destruction (Blog Post)](https://ericlippert.com/2013/06/10/construction-destruction/#more-1203)
* [Lock And Exceptions Do Not Mix (Blog Post)](https://ericlippert.com/2009/03/06/locks-and-exceptions-do-not-mix/#more-1873)
* [Atomacity, Volatility and Immutability Are Different (Blog Post)](https://ericlippert.com/2011/06/16/atomicity-volatility-and-immutability-are-different-part-three/#more-2019)
* [Understanding Low Lock Techniques In Multi-threaded Apps (Blog Post)](https://learn.microsoft.com/en-us/archive/msdn-magazine/2005/october/understanding-low-lock-techniques-in-multithreaded-apps)

### Misc

* [How LLVM Optimizes a function (Blog Post)](https://blog.regehr.org/archives/1603)
* [Crafting Interpreters (Online Book)](http://www.craftinginterpreters.com/)
* [How To Speed Up The Rust Compiler (Blog Post)](https://blog.mozilla.org/nnethercote/2020/09/08/how-to-speed-up-the-rust-compiler-one-last-time/)
* [Async Rust Is A Bad Language (Blog Post)](https://bitbashing.io/async-rust.html)

## AI

* [The AI of DOOM 2016](http://www.gamasutra.com/blogs/TommyThompson/20180806/323715/Cyber_Demons__The_AI_of_DOOM_2016.php)
* [AI and Games (Blog)](https://aiandgames.com/)

## Rendering

### Vulkan

* [Single Renderpass Deferred Shading on Mobile](https://www.khronos.org/assets/uploads/developers/library/2017-gdc/GDC_Vulkan-on-Mobile_Vulkan-Multipass-ARM_Mar17.pdf)
* [Vulkan Subpasses](https://www.khronos.org/assets/uploads/developers/library/2016-vulkan-devday-uk/6-Vulkan-subpasses.pdf)
* [Yet another blog explaining Vulkan synchronization](http://themaister.net/blog/2019/08/14/yet-another-blog-explaining-vulkan-synchronization/)
* [A Tour Of Granite's Vulkan Backend (Blog Series)](http://themaister.net/blog/2019/04/14/a-tour-of-granites-vulkan-backend-part-1/)
* [Vulkan Fast Paths (Slides)](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/VulkanFastPaths.pdf)
* [Using Arrays of Textures in Vulkan (Blog Post)](http://kylehalladay.com/blog/tutorial/vulkan/2018/01/28/Textue-Arrays-Vulkan.html)
* [Vulkan Textures Unbound (Blog Post)](http://roar11.com/2019/06/vulkan-textures-unbound/)
* [Binding Bindlessly (Blog Post)](http://alextardif.com/Bindless.html)
* [Render Target APIs (Blog Post)](https://erfan-ahmadi.github.io/blog/Yugen/RenderTargets)
* [Writting An Efficient Vulkan Renderer (Blog Post/Article)](https://zeux.io/2020/02/27/writing-an-efficient-vulkan-renderer/)
* [The Missing Guide to Modern Graphics APIs – 2. PSOs (Blog Post)](https://blog.mecheye.net/2021/06/the-missing-guide-to-modern-graphics-apis-2-psos/)
* [Graphics API secrets: format casting (Blog Post)](https://wickedengine.net/2022/11/08/graphics-api-secrets-format-casting/)
* [VK_EXT_descriptor_buffer (Blog Post)](https://www.khronos.org/blog/vk-ext-descriptor-buffer)
* [Descriptors are hard (Blog Post)](https://www.gfxstrand.net/faith/blog/2022/08/descriptors-are-hard/)
* [Improving shader performance with Vulkan’s specialization constants (Blog Post)](https://blogs.igalia.com/itoral/2018/03/20/improving-shader-performance-with-vulkans-specialization-constants/)
* [Hardcore Vulkan debugging – Digging deep on Linux + AMDGPU (Blog Post)](https://themaister.net/blog/2023/08/20/hardcore-vulkan-debugging-digging-deep-on-linux-amdgpu/)

### DX12

* [Shader Assembly and D3D12 Root Signatures (Blog Post)](https://boogy90.github.io/2021/11/24/root-signatures-assembly.html)
* [GPU Memory Pools in D3D12 (Blog Post)](https://therealmjp.github.io/posts/gpu-memory-pool/)
* [Arkham Quixote (Blog Post)](https://sherief.fyi/post/arkham-quixote/)
* [Managing Memory for Acceleration Structures in DirectX Raytracing (Blog Post)](https://developer.nvidia.com/blog/managing-memory-for-acceleration-structures-in-dxr/)
* [Tips: Acceleration Structure Compaction (Blog Post)](https://developer.nvidia.com/blog/tips-acceleration-structure-compaction/)
* [Advanced Graphics moving to DirectX 12 (GDC slides)](https://www.gdcvault.com/play/1024656/Advanced-Graphics-Tech-Moving-to)
* [In-Game GPU Profiling for DirectX 12 Using SetBackgroundProcessingMode (Blog Post)](https://developer.nvidia.com/blog/in-game-gpu-profiling-for-dx12-using-setbackgroundprocessingmode/)
* [Tier 2 Variable Rate Shading in Gears (Video)](https://www.youtube.com/watch?v=-exWLpgnOJ4)

### Textures And Compression

* [Understanding BCn Texture Compression Formats (Blog Post)](http://reedbeta.com/blog/understanding-bcn-texture-compression-formats/)
* [Compressed GPU Texture Formats - A Review And Comute Shader Decoders Part 1 (Blog Post)](https://themaister.net/blog/2020/08/12/compressed-gpu-texture-formats-a-review-and-compute-shader-decoders-part-1/)
* [Bindless Texturing for Deferred texturing and Decals (Blog Post)](https://mynameismjp.wordpress.com/2016/03/25/bindless-texturing-for-deferred-rendering-and-decals/)
* [Compressing PBR texture sets with sparsity and dictionary learning (Blog Post)](https://bartwronski.com/2020/08/30/compressing-pbr-texture-sets-with-sparsity-and-dictionary-learning/)
* [Texture Compression In 2020 (Blog Post)](https://aras-p.info/blog/2020/12/08/Texture-Compression-in-2020/)
* [GPU BCn Decoding (Blog Post)](https://fgiesen.wordpress.com/2021/10/04/gpu-bcn-decoding/)
* [Texture Tiling And Swizzling (Blog Post)](https://github.com/rygorous/rygblog-src/blob/master/posts/texture-tiling-and-swizzling.md)
* [Lossless Image Compression in O(n) Time (Blog Post)](https://phoboslab.org/log/2021/11/qoi-fast-lossless-image-compression)
* [An Introduction To BCn Texture Compression, Part 1: BC4 (Blog Post)](https://acefanatic02.github.io/posts/intro_bcn_part1/)

### Colors

* [A perceptual color space for image processing (Blog Post)](https://bottosson.github.io/posts/oklab/)
* [How the CIE 1931 RGB Color Matching Functions Were Developed (Blog Post)](https://yzhu.medium.com/how-the-cie-1931-rgb-color-matching-functions-were-developed-from-the-initial-color-matching-a98696d9cf37)
* [RGBM Color Encoding (Blog Post)](http://graphicrants.blogspot.com/2009/04/rgbm-color-encoding.html)
* [The Hitchikers Guide To Digital Color (Website)](https://hg2dc.com/)
* [Color Enhancement And Rendering In Film And Game Production (Slides)](https://renderwonk.com/publications/s2010-color-course/pines/s2010_color_pines_slides.pdf)
* [The Apparent Simplicity of RGB Rendering (Blog Post)](https://thomasmansencal.substack.com/p/the-apparent-simplicity-of-rgb-rendering)

### Forward, Deferred, Visibility, Etc

* [Forward+ Decal Rendering (Blog Post)](https://wickedengine.net/2017/10/12/forward-decal-rendering/)
* [Visibility Buffer Rendering With Material Graphs (Blog Post)](http://filmicworlds.com/blog/visibility-buffer-rendering-with-material-graphs/)
* [The Visibility Buffer: A Cache-Friendly Approach to Deferred Shading (Paper)](http://jcgt.org/published/0002/02/04/)
* [A Primer On Efficient Rendering Algorithms & Clustered Shading. (Blog Post)](http://www.aortiz.me/2018/12/21/CG.html)
* [Non-interleaved Deferred Shading of Interleaved Sample Patterns (Paper)](https://liris.cnrs.fr/Documents/Liris-2476.pdf)
* [Adventures with Deferred Texturing in Horizon Forbidden West (Blog Post)](https://www.guerrilla-games.com/read/adventures-with-deferred-texturing-in-horizon-forbidden-west)

### Transparency, Blending

* [WBOIT in OpenGL: transparency without sorting (Blog Post)](https://habr.com/en/post/457292/)
* [Order Independent Transparency (Slides)](http://developer.download.nvidia.com/assets/gamedev/docs/OrderIndependentTransparency.pdf)
* [Alpha Blending: To Pre or Not To Pre (Blog Post)](https://developer.nvidia.com/content/alpha-blending-pre-or-not-pre)
* [Alpha Compositing (Blog Post)](https://ciechanow.ski/alpha-compositing/)
* [Premultiplied Alpha (Blog Post)](https://blogs.msdn.microsoft.com/shawnhar/2009/11/06/premultiplied-alpha/)
* [Order independent transparency, part 1 (Blog Post)](https://interplayoflight.wordpress.com/2022/06/25/order-independent-transparency-part-1/)
* [Moment-Based Order-Independent Transparency (Paper)](https://momentsingraphics.de/Media/I3D2018/Muenstermann2018-MBOIT.pdf)
* [Channeling Alpha (Blog Post)](https://medium.com/@giz51d/channeling-alpha-bd32afbfadfa)

### GPU Architecture

* [A Trip Through the Graphics Pipeline (Blog Series)](https://fgiesen.wordpress.com/2011/07/01/a-trip-through-the-graphics-pipeline-2011-part-1/)
* [Understanding GPU Context Rolls (Article)](https://gpuopen.com/understanding-gpu-context-rolls/)
* [Revisiting the Vertex Cache (Article)](https://erkaman.github.io/posts/kerbl2018_tldr.html)
* [Zero Driver Overhead (GDC Talk)](https://www.youtube.com/watch?v=K70QbvzB6II)
* [GPU Barriers (Blog Post)](https://mynameismjp.wordpress.com/2018/03/06/breaking-down-barriers-part-1-whats-a-barrier/)
* [Tile Based Renderers](https://developer.samsung.com/game/gpu-framebuffer)
* [Register Spilling](https://developer.download.nvidia.com/CUDA/training/register_spilling.pdf)
* [GPU Resources (Twitter Thread)](https://twitter.com/KostasAAA/status/1213908535039401984?s=20)
* [GPU Architecture Resources (Blog Post)](https://interplayoflight.wordpress.com/2020/05/09/gpu-architecture-resources/)
* [GPU Memory Aliasing (Blog Post)](https://medium.com/@pavlo.muratov/gpu-memory-aliasing-45933681a15e)
* [Rasterization Rules (MSDN)](https://docs.microsoft.com/en-us/windows/win32/direct3d11/d3d10-graphics-programming-guide-rasterizer-stage-rules#triangle-rasterization-rules-without-multisampling)
* [Overdraw in Overdrive (Blog Post)](https://blog.selfshadow.com/publications/overdraw-in-overdrive/)
* [Counting Quads (Blog Post)](https://blog.selfshadow.com/2012/11/12/counting-quads/)
* [How bad are small triangles on GPU and why? (Blog Post)](https://www.g-truc.net/post-0662.html)
* [Understanding Modern GPUs - Part 1 (Blog Post)](https://traxnet.wordpress.com/2011/07/16/understanding-modern-gpus-1/)
* [GPU Processing Budget Approach To Game Development (Blog Post)](https://community.arm.com/developer/tools-software/graphics/b/blog/posts/gpu-processing-budget-approach-to-game-development)
* [The Mali GPU An Abstract Machine - Part 3 (Blog Post)](https://community.arm.com/developer/tools-software/graphics/b/blog/posts/the-mali-gpu-an-abstract-machine-part-3---the-midgard-shader-core)
* [What is shader occupancy and why do we care about it? (Blog Post)](https://interplayoflight.wordpress.com/2020/11/11/what-is-shader-occupancy-and-why-do-we-care-about-it/)
* [What's up with my branch on GPU? (Blog Post)](https://aschrein.github.io/jekyll/update/2019/06/13/whatsup-with-my-branches-on-gpu.html)
* [Intro To GPU Scalarization - Part 1 (Blog Post)](https://flashypixels.wordpress.com/2018/11/10/intro-to-gpu-scalarization-part-1/)
* [Analysis Driven Optimization: Preparing for analysis with NVidia Nsight Compute (Blog Series)](https://developer.nvidia.com/blog/analysis-driven-optimization-preparing-for-analysis-with-nvidia-nsight-compute-part-1/)
* [The AMD GCN Architecture - A Crash Course (Slides)](https://www.slideshare.net/DevCentralAMD/gs4106-the-amd-gcn-architecture-a-crash-course-by-layla-mah) 
* [Gentle Introduction To GPU Inner Workings (Blog Post)](https://vksegfault.github.io/posts/gentle-intro-gpu-inner-workings/)
* [Advanced Shader Programming On GCN (Slides)](https://gpuopen.com/wp-content/uploads/2017/03/GDC2017-Advanced-Shader-Programming-On-GCN.pdf)
* [GPU Architectures Explained (Blog Post)](https://rastergrid.com/blog/gpu-tech/2021/07/gpu-architecture-types-explained/)
* [Triangle Setup And Rasterization For FGPA (Blog Post)](http://js3.maisonikkoku.com/uncategorized/triangle_setup_and_rasterization/)
* [Linear-Speed Vertex Cache Optimisation (Paper)](http://tomforsyth1000.github.io/papers/fast_vert_cache_opt.html)
* [RDNA3 ISA (Paper)](https://developer.amd.com/wp-content/resources/RDNA3_Shader_ISA_December2022.pdf)
* [RDNA Architecture (Paper)](https://www.amd.com/system/files/documents/rdna-whitepaper.pdf)
* [Fine-grained backface culling (Blog Post)](https://zeux.io/2023/04/28/triangle-backface-culling/)
* [GPU Hang Exploration: Splitgate (Blog Post)](https://pixelcluster.github.io/Hang-Exploration-Splitgate/)
* [Explore GPU advancements in M3 and A17 Pro (Video)](https://developer.apple.com/videos/play/tech-talks/111375)
* [Occupancy explained (Blog Post)](https://gpuopen.com/learn/occupancy-explained/)
* [Examining AMD’s RDNA 4 Changes in LLVM (Blog Post)](https://chipsandcheese.com/2024/01/28/examining-amds-rdna-4-changes-in-llvm/)

### Code

* [Path Graph (Codebase)](https://github.com/daseyb/pathgraph/blob/master/README.md)
* [The Forge (Codebase)](https://github.com/ConfettiFX/The-Forge)
* [Single Header Backend Renderer (Codebase)](https://www.gamedev.net/news/px_render-single-header-backend-renderer-r461)

### Particles

* [The New Particle (Article)](http://www.simppa.fi/blog/the-new-particle/)
* [Downsampled Particle Effects (GPUGems)](https://developer.nvidia.com/gpugems/gpugems3/part-iv-image-effects/chapter-23-high-speed-screen-particles)

### Shadows

* [Variance Shadow Maps (Paper)](http://www.punkuser.net/vsm/vsm_paper.pdf)
* [A Sampling of Shadow Techniques (Blog Post)](https://therealmjp.github.io/posts/shadow-maps/)
* [Raytraced Shadows in Call of Duty Modern Warfare (Slides)](https://www.activision.com/cdn/research/Raytraced_Shadows_in_Call_of_Duty_Modern_Warfare.pdf)
* [Combining Analytic Direct Illumination and Stochastic Shadows (Paper)](http://casual-effects.com/research/Heitz2018Shadow/index.html)
* [Experiments in Hybrid Raytraced Shadows (Blog Post)](https://interplayoflight.wordpress.com/2021/05/15/experiments-in-hybrid-raytraced-shadows/)
* [Shadow Techniques from Final Fantasy XVI (Blog Post)](http://www.jp.square-enix.com/tech/library/pdf/2023_FFXVIShadowTechPaper.pdf)

### Spherical Harmonics

* [Spherical Harmonic Gradients for Mid-Range Illumination (Paper)](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.83.1462&rep=rep1&type=pdf)
* [Spherical Harmonic Irradiance Gradients (Slides)](http://chrisoat.com/papers/Oat_GDC2005_IrradianceVolumesForGames.pdf#page=21&zoom=auto,42,-175)
* [Stupid Spherical Harmonic Tricks (Paper)](https://www.ppsloan.org/publications/StupidSH36.pdf#%5B%7B%22num%22%3A229%2C%22gen%22%3A0%7D%2C%7B%22name%22%3A%22XYZ%22%7D%2C70%2C177%2C0%5D)
* [Spherical Harmonic Lighting: The Gritty Details (Paper)](https://3dvar.com/Green2003Spherical.pdf)
* [Spherical Harmonics - Patapom (Blog Post)](https://patapom.com/blog/SHPortal/)
* [Alternative definition of Spherical Harmonics for Lighting (Blog Post)](https://grahamhazel.com/blog/2017/12/18/alternative-definition-of-spherical-harmonics-for-lighting/)
* [Converting SH Radiance to Irradiance (Blog Post)](https://grahamhazel.com/blog/2017/12/22/converting-sh-radiance-to-irradiance/)

### Raytracing

* [Ray Tracing Denoising (Blog Post)](https://alain.xyz/blog/raytracing-denoising)
* [Raytracing Reflection, Refraction, Fresnel, Total Internal Reflection, and Beer's Law (Blog Post)](https://blog.demofox.org/2017/01/09/raytracing-reflection-refraction-fresnel-total-internal-reflection-and-beers-law/)
* [Ray Tracing In A Weekend (Book)](https://www.realtimerendering.com/raytracing/Ray%20Tracing%20in%20a%20Weekend.pdf)
* [Ray Tracing The Rest of Your Life (Book)](https://www.realtimerendering.com/raytracing/Ray%20Tracing_%20the%20Rest%20of%20Your%20Life.pdf)
* [Raytracing a tiny procedural planet (Slides)](https://casual-effects.com/research/McGuire2019ProcGen/McGuire2019ProcGen.pdf)
* [Importance Sampling Visible Wavelengths (Blog Post)](http://simonstechblog.blogspot.com/2021/03/importance-sampling-visible-wavelength.html)
* [Increasing wave coherence with ray binning (Blog Post)](https://interplayoflight.wordpress.com/2022/05/08/increasing-wave-coherence-with-ray-binning/)
* [Spherical Area Light Sampling (Blog Post)](https://schuttejoe.github.io/post/arealightsampling/)
* [Raytracing In Hybrid Real-time Rendering (Slides)](http://h3.gd/raytracing-in-hybrid-real-time-rendering/)
* [Real-Time Path Tracing And Beyond (Slides)](https://research.nvidia.com/publication/2022-07_real-time-path-tracing-and-beyond)
* [STOCHASTIC ALL THE THINGS: RAYTRACING IN HYBRID REAL-TIME RENDERING](https://www.ea.com/seed/news/seed-dd18-presentation-slides-raytracing)
* [Adventures in Hybrid Rendering (Blog Post)](https://diharaw.github.io/post/adventures_in_hybrid_rendering/)
* [RE: 2023 - Advances in Ray Tracing (Video)](https://www.youtube.com/watch?v=X8TvRKRWirE)
* [RE: 2023 - New Rendering Features Rundown, SDFs (Video)](https://www.youtube.com/watch?v=aEpklsGKVmQ)
* [Ray tracing animated crowds (Blog Post)](https://blog.traverseresearch.nl/ray-tracing-animated-crowds-bc0e775c74ad)
* [Beyond SAH — Building Optimal BVHs (Blog Post)](https://blog.traverseresearch.nl/beyond-sah-building-optimal-bvhs-fdef1878d6ed)
* [Improving raytracing performance with the Radeon™ Raytracing Analyzer (RRA) (Blog Post)](https://gpuopen.com/learn/improving-rt-perf-with-rra/)

### Blue Noise

* [Distributing Monte Carlo errors as Blue Noise in Screen Space - Part 1 (Blog Post)](https://gamehacker1999.github.io/posts/bluenoiseerrors/)
* [What the heck is blue noise? (Blog Post)](https://blog.demofox.org/2018/01/30/what-the-heck-is-blue-noise/)
* [Spatio-Temporal Blue Noise (Video)](https://www.youtube.com/watch?v=4nM2FbLnOqQ)

### Graphics Codebases

* [Molecular Matters - Stateless Threaded Rendering Series](https://blog.molecular-matters.com/2014/11/06/stateless-layered-multi-threaded-rendering-part-1/)
* [Molecular Matters - DoD Series](https://blog.molecular-matters.com/2011/11/03/adventures-in-data-oriented-design-part-1-mesh-data-3/)
* [Rendering Abstraction Layers (Blog Post)](http://alextardif.com/RenderingAbstractionLayers.html)
* [How (not) to test graphics code (Blog Post)](https://bartwronski.com/2019/08/14/how-not-to-test-graphics-algorithms/)
* [My toy renderer: Overview (Blog Series)](https://momentsingraphics.de/ToyRendererOverview.html)

### Normals And Tangent Spaces

* [Tangent Spaces and Diamond Encoding (Blog Post)](https://www.jeremyong.com/graphics/2023/01/09/tangent-spaces-and-diamond-encoding/)
* [Improved Normal Reconstruction From Depth (Blog Post)](https://wickedengine.net/2019/09/22/improved-normal-reconstruction-from-depth/)
* [Accurate Normal Reconstruction From Depth Buffer (Blog Post)](https://atyuwen.github.io/posts/normal-reconstruction/)
* [Orthonormal Basis (Paper)](https://graphics.pixar.com/library/OrthonormalB/paper.pdf)
* [Normals revisited (Blog Post)](https://github.com/graphitemaster/normals_revisited/blob/master/README.md)
* [Normal Mapping without Precomputed Tangents (Blog Post)](http://www.thetenthplanet.de/archives/1180)
* [Survey of Efficient Representations for Independent Unit Vectors (Paper)](https://jcgt.org/published/0003/02/01/)

### Shaders

* [The Shader Permutations Problem (Blog Series)](https://therealmjp.github.io/posts/shader-permutations-part1/)
* [Half The Precision, Twice The Fun: Working With FP16 In HLSL (Blog Post)](https://therealmjp.github.io/posts/shader-fp16/)
* [Floating-point in mobile shaders (Blog Post)](https://solidpixel.github.io/2021/11/23/floats_in_shaders.html)
* [Interlocked min/max on HLSL single precision floats (Blog Post)](https://www.jeremyong.com/graphics/2023/09/05/f32-interlocked-min-max-hlsl/)
* [Shader Printf in HLSL and DX12 (Blog Post)](https://therealmjp.github.io/posts/hlsl-printf/)
* [HLSL Constant Buffer Packing Rules (Blog Post)](https://maraneshi.github.io/HLSL-ConstantBufferLayoutVisualizer/)
* [Khronos Releases Maximal Reconvergence and Quad Control Extensions for Vulkan and SPIR-V (Blog Post)](https://www.khronos.org/blog/khronos-releases-maximal-reconvergence-and-quad-control-extensions-for-vulkan-and-spir-v)

#### Compute Shaders

* [Intro To Compute Shaders (Blog Post)](https://anteru.net/blog/2018/intro-to-compute-shaders/index.html)
* [Optimizing the graphics pipeline with compute (Slides)](https://frostbite-wp-prd.s3.amazonaws.com/wp-content/uploads/2016/03/29204330/GDC_2016_Compute.pdf)
* [Optimizing Compute Shaders for L2 Locality (Blog Post)](https://developer.nvidia.com/blog/optimizing-compute-shaders-for-l2-locality-using-thread-group-id-swizzling/)
* [Compute Shader Optimizations for AMD GPUs: Parallel Reduction (Blog Post)](https://diaryofagraphicsprogrammer.blogspot.com/2014/03/compute-shader-optimizations-for-amd.html)
* [Stream compaction using wave intrinsics (Blog Post)](https://interplayoflight.wordpress.com/2022/12/25/stream-compaction-using-wave-intrinsics/)
* [Boosting Application Performance with GPU Memory Prefetching (Blog Post)](https://developer.nvidia.com/blog/boosting-application-performance-with-gpu-memory-prefetching/)

#### Geometry Shaders

* [A Trip Through The Graphics Pipeline 2011, Part 10 (Blog Post)](https://fgiesen.wordpress.com/2011/07/20/a-trip-through-the-graphics-pipeline-2011-part-10/)
* [Geometry Shader - Advanced OpenGL (Blog Post)](https://learnopengl.com/Advanced-OpenGL/Geometry-Shader)
* [My Take On Shaders - Geometry Shaders (Blog Post)](https://halisavakis.com/my-take-on-shaders-geometry-shaders/)
* [Geometry Shader Adventures (Blog Post)](http://vfxmike.blogspot.com/2018/07/geometry-shader-adventures-mesh.html)
* [Geometry Shader Stage (Docs)](https://docs.microsoft.com/en-us/windows/win32/direct3d11/geometry-shader-stage)

#### Tesselation Shaders

* [A Trip Through The Graphics Pipeline 2011, Part 12 (Blog Post)](https://fgiesen.wordpress.com/2011/09/06/a-trip-through-the-graphics-pipeline-2011-part-12/)
* [Tessellation - Catlike Coding (Blog Post)](https://catlikecoding.com/unity/tutorials/advanced-rendering/tessellation/)
* [Surface Displacement (Blog Post)](https://catlikecoding.com/unity/tutorials/advanced-rendering/surface-displacement/)
* [Tesselation Optimizations (Blog Post)](https://erkaman.github.io/posts/tess_opt.html)
* [Tesselation Shaders (Blog Post)](http://ogldev.atspace.co.uk/www/tutorial30/tutorial30.html)
* [Advanced Stages - Tessellation (Docs)](https://docs.microsoft.com/en-us/windows/win32/direct3d11/direct3d-11-advanced-stages-tessellation)

#### Mesh Shaders

* [Mesh Shader Possibilities (Blog Post)](http://reedbeta.com/blog/mesh-shader-possibilities/)
* [Mesh and task shaders intro and basics (Blog Post)](https://timur.hu/blog/2022/mesh-and-task-shaders)
* [How mesh shaders are implemented in an AMD driver (Blog Post)](https://timur.hu/blog/2022/how-mesh-shaders-are-implemented)
* [Task shader driver implementation on AMD HW (Blog Post)](https://timur.hu/blog/2022/how-task-shaders-are-implemented)
* [Performance Comparison of Meshlet Generation Strategies (Paper)](https://jcgt.org/published/0012/02/01/)
* [Mesh Shaders on RDNA™ Graphics Cards (Blog Post)](https://gpuopen.com/learn/mesh-shaders-on-rdna-graphics-cards/?utm_source=mastodon&utm_medium=social&utm_campaign=mesh-shaders-on-rdna)
* [Modernizing Granite’s mesh rendering (Blog Post)](https://themaister.net/blog/2024/01/17/modernizing-granites-mesh-rendering/)
* [Optimization and best practices (Blog Post)](https://gpuopen.com/learn/mesh_shaders/mesh_shaders-optimization_and_best_practices/)

### Lighting/Shading

* [Introduction to Lighting (Blog Post)](http://math.hws.edu/graphicsbook/c4/s1.html)
* [Mathematics of shading (Course Notes)](https://blog.selfshadow.com/publications/s2013-shading-course/hoffman/s2013_pbs_physics_math_notes.pdf)
* [Introduction to shading (Tutorial)](https://www.scratchapixel.com/lessons/3d-basic-rendering/introduction-to-shading/reflection-refraction-fresnel)
* [PI or not to PI in game lighting equation (Blog Post)](https://seblagarde.wordpress.com/2012/01/08/pi-or-not-to-pi-in-game-lighting-equation/)
* [PBR Diffuse Lighting for GGX (Slides)](https://www.gdcvault.com/play/1024478/PBR-Diffuse-Lighting-for-GGX)
* [Physically Based Rendering References At The End of 2019 (Blog Post)](http://lousodrome.net/blog/light/2020/01/04/physically-based-rendering-references-at-the-end-of-2019/)
* [Google Filament PBR (Code base breakdown)](https://google.github.io/filament/Filament.md.html)
* [Game Environments Parta Remember Me Rendering (Blog Post)](https://www.fxguide.com/fxfeatured/game-environments-parta-remember-me-rendering/)
* [Moving Frostbite to Physically Based Rendering V3](https://seblagarde.wordpress.com/tag/physically-based-rendering/)
* [Fresnel Equations Schlick Approximations (Blog Post)](http://psgraphics.blogspot.com/2020/03/fresnel-equations-schlick-approximation.html)
* [Lights And Shadows (Interactive Blog Post)](https://ciechanow.ski/lights-and-shadows/)
* [Adventures In Triangle Sampling Part 1 (Blog Post)](https://pharr.org/matt/blog/2019/02/27/triangle-sampling-1.html)
* [Image Based Lighting With Multiple Scattering](https://bruop.github.io/ibl/)
* [Adventures in Sampling Points on Triangles - Part 1 (Blog Post)](https://pharr.org/matt/blog/2019/02/27/triangle-sampling-1.html)
* [Spherical Gaussians Series (Blog Series)](https://therealmjp.github.io/posts/sg-series-part-1-a-brief-and-incomplete-history-of-baked-lighting-representations/)
* [The Irradiance Volume (Paper)](http://www.sci.utah.edu/~bigler/images/msthesis/The%20irradiance%20volume.pdf)
* [Advances In Rendendering, Graphics Research And Video Game Production (Slides)](https://i3dsymposium.org/2019/keynotes/I3D2019_keynote_StephenMcAuley.pdf)
* [Real Shading in Unreal Engine 4 (Paper)](https://cdn2.unrealengine.com/Resources/files/2013SiggraphPresentationsNotes-26915738.pdf)
* [Discrepancy as a Quality Measure for Sample Distributions (Paper)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.15.1601&rep=rep1&type=pdf)
* [Bias In rendering (Paper)](https://www.cs.cmu.edu/~kmcrane/Projects/Other/BiasInRendering.pdf)
* [Reducing Shading on GPUs using Quad-Fragment Merging (Paper)](http://graphics.stanford.edu/papers/fragmerging/shade_sig10.pdf)
* [An Area-Preserving Parametrization for Spherical Rectangles (Paper)](https://www.arnoldrenderer.com/research/egsr2013_spherical_rectangle.pdf)
* [Stable Geometric Specular Antialiasing with Projected-Space NDF Filtering (Paper)](https://www.jcgt.org/published/0010/02/02/paper-lowres.pdf)
* [Moving Frostbite to PBR (PDF)](https://media.contentapi.ea.com/content/dam/eacom/frostbite/files/course-notes-moving-frostbite-to-pbr-v2.pdf)
* [Real-Time Polygonal-Light Shading with Linearly Transformed Cosines (Article)](https://eheitzresearch.wordpress.com/415-2/)

#### Lights

* [Light Trees And The Many Lights Problem (Blog Post)](https://psychopath.io/post/2020_04_20_light_trees)
* [Light Attenuation (Blog Post)](https://imdoingitwrong.wordpress.com/2011/01/31/light-attenuation/)
* [Light Attenuation Formula Derivation (Stack Exchange)](https://gamedev.stackexchange.com/questions/131372/light-attenuation-formula-derivation)
* [Nonsingular Point Light Attenuation (Video)](http://www.cemyuksel.com/research/pointlightattenuation/)
* [Dynamic Many-Light Sampling for Real-Time Ray Tracing (Paper)](https://pdfs.semanticscholar.org/c201/a72c707d96c9fed65aad5f481443041d9de9.pdf)
* [Importance Sampling of Many Lights with Adaptive Tree Splitting (Paper)](http://www.aconty.com/pdf/many-lights-hpg2018.pdf)
* [Geometric Derivation of the Irradiance of Polygonal Lights (Paper)](https://hal.archives-ouvertes.fr/hal-01458129/document)

#### BRDFs

* [A Reflectance Model For Computer Graphics (Paper)](https://inst.eecs.berkeley.edu/~cs283/sp13/lectures/cookpaper.pdf)
* [How is the NDF defined? (Blog Post)](http://www.reedbeta.com/blog/hows-the-ndf-really-defined/)
* [Sampling Microfacet BRDFs (Blog Post)](https://www.google.com/amp/s/agraphicsguy.wordpress.com/2015/11/01/sampling-microfacet-brdf/amp/)
* [BRDF Definition (Blog Post)](https://patapom.com/blog/BRDF/BRDF%20Definition/)
* [Fresnel Equations Considered Harmful (Slides)](http://renderwonk.com/publications/mam2019/)
* [BRDF Normalization (Q&A)](https://computergraphics.stackexchange.com/questions/7578/brdf-normalization)
* [BRDF Normalization (Forum)](https://www.gamedev.net/forums/topic/600301-normalized-brdf/4802960/)
* [Energy Conservation In Games (Blog Post)](http://www.rorydriscoll.com/2009/01/25/energy-conservation-in-games/)
* [Energy Conserving Wrapped Diffuse (Blog Post)](http://blog.stevemcauley.com/2011/12/03/energy-conserving-wrapped-diffuse/)
* [Phong Normalization Derivation (PDF)](http://www.farbrausch.de/~fg/stuff/phong.pdf)
* [Blinn Phong Normalization Zoo (Blog Post)](http://www.thetenthplanet.de/archives/2550)
* [Crash Course In BRDFs (Doc)](https://boksajak.github.io/files/CrashCourseBRDF.pdf)
* [Multiple Scattering BRDF (Blog Post)](https://patapom.com/blog/BRDF/MSBRDF/)
* [Misunderstanding Multiscattering (Blog Post)](http://c0de517e.blogspot.com/2019/08/misunderstanding-multiscattering.html)
* [Microfacet models for refraction through rough surfaces (Paper)](https://www.cs.cornell.edu/~srm/publications/EGSR07-btdf.pdf)
* [Average irregularity representation of a rough surface for ray reflection (Paper)](https://pharr.org/matt/blog/images/average-irregularity-representation-of-a-rough-surface-for-ray-reflection.pdf)
* [Sampling Visible GGX Normals with Spherical Caps (Paper)](https://arxiv.org/pdf/2306.05044.pdf)
* [A Micrograin BSDF Model for the Rendering of Porous Layers (Paper)](https://hal.science/hal-04220006)

### Ambient Occlusion

* [Screen Space Ambient Occlusion (Doc)](https://developer.download.nvidia.com/SDK/10.5/direct3d/Source/ScreenSpaceAO/doc/ScreenSpaceAO.pdf)
* [Screen Space Ambient Occlusion - OGL Dev (Tutorial)](http://ogldev.atspace.co.uk/www/tutorial45/tutorial45.html)
* [Screen Space Ambient Occlusion - Learn OpenGL (Tutorial)](https://learnopengl.com/Advanced-Lighting/SSAO)
* [Multiresolution Ambient Occlusion (Blog Post)](https://iquilezles.org/articles/multiresaocc/)
* [A Taxonomy of Bidirectional Scattering DistributionFunction Lobes for Rendering Engineers (Paper)](http://casual-effects.com/research/McGuire2020BSDF/McGuire2020BSDF.pdf)
* [Horizon Split Ambient Occlusion (Paper)](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.557.4596&rep=rep1&type=pdf)

### Subsurface Scattering

* [Efficient Screen-space SSS (Paper)](http://advances.realtimerendering.com/s2018/Efficient%20screen%20space%20subsurface%20scattering%20Siggraph%202018.pdf)
* [Real-Time Subsurface Scattering Intro (Blog Post)](https://therealmjp.github.io/posts/sss-intro/)
* [Approximating Translucency for a Fast, Cheap and Convincing Subsurface Scattering Look (Slides)](https://www.ea.com/frostbite/news/approximating-translucency-for-a-fast-cheap-and-convincing-subsurface-scattering-look)

### Importance Sampling

* [Multiple Importance Sampling Techniques for Monte Carlo Rendering (Paper/Coure Notes)](https://graphics.stanford.edu/courses/cs348b-03/papers/veach-chapter9.pdf)
* [Importance Sampling Techniques for GGX with Smith masking-shadowing (Blog Post)](https://schuttejoe.github.io/post/ggximportancesamplingpart1/)
* [Importance Sampling Adventure (Tweets)](https://twitter.com/KostasAAA/status/1246936564556537865?s=20)
* [Multiple Importance Sampling (Blog Post)](https://blog.yiningkarlli.com/2015/02/multiple-importance-sampling.html)
* [Can't invert the CDF? Triangle Cut Parametirzation of the Region Under The Curve (Paper)](https://diglib.eg.org/bitstream/handle/10.1111/cgf14058/v39i4pp121-132.pdf)
* [Optimally Combining Sampling Techniques for Monte Carlo Rendering (Paper)](http://www.cs.jhu.edu/~misha/ReadingSeminar/Papers/Veach95.pdf)
* [BRDF Importance Sampling for Polygonal Lights (Paper)](https://momentsingraphics.de/Siggraph2021.html)

#### ReSTIR

* [Rearchitecting Spatiotemporal Resampling for Production (Paper)](https://d1qx31qr3h6wln.cloudfront.net/publications/hpg21_rearchitectingReSTIR.pdf)
* [Spatiotemporal reservoir resampling for real-time ray tracing with dynamic direct lighting (Paper)](https://cs.dartmouth.edu/wjarosz/publications/bitterli20spatiotemporal.pdf)
* [ReSTIR GI: Path Resampling for Real-Time Path Tracing (Paper)](https://d1qx31qr3h6wln.cloudfront.net/publications/ReSTIR%20GI.pdf)
* [A Gentler Introduction To ReSTIR (Blog Post)](https://interplayoflight.wordpress.com/2023/12/17/a-gentler-introduction-to-restir/)
* [Dynamic diffuse global illumination (Blog Post)](https://blog.traverseresearch.nl/dynamic-diffuse-global-illumination-b56dc0525a0a)

### Cameras, Exposure, Tonemapping

* [Tone Mapping (Blog Post By Bruno Opsenica)](https://bruop.github.io/tonemapping/)
* [Tone Mapping (Blog Post By 64)](https://64.github.io/tonemapping/)
* [Adaptive Exposure from Luminance Histograms (Blog Post)](http://www.alextardif.com/HistogramLuminance.html)
* [Automatic Exposure Using a Luminance Histogram (Blog Post)](https://bruop.github.io/exposure/)
* [Automatic Exposure (Blog Post)](https://knarkowicz.wordpress.com/2016/01/09/automatic-exposure/)
* [Cameras And Lenses (Blog Post)](https://ciechanow.ski/cameras-and-lenses/)
* [Temporal ReprojectionAnti-Aliasing in INSIDE (Slides)](http://s3.amazonaws.com/arena-attachments/655504/c5c71c5507f0f8bf344252958254fb7d.pdf?1468341463)
* [ISO Sensitivity and Exposure Index (Blog Post)](https://www.imatest.com/docs/sensitivity_ei/)
* [Where does 78 come from in exposure calculations? (Forum)](https://www.dpreview.com/forums/thread/4579986?page=2)
* [Exposure Fusion Local Tonemapping For Real-Time Rendering (Blog Post)](https://bartwronski.com/2022/02/28/exposure-fusion-local-tonemapping-for-real-time-rendering/)

### Misc

* [Real-Time Rendering Resources (Holy grail of resources)](http://www.realtimerendering.com/)
* [Walt Disney Datasets (Data)](https://www.disneyanimation.com/technology/datasets)
* [Aras P - Rendering(Blog)](https://aras-p.info/tags/rendering/)
* [Inigo Quilez (Founder of Shadertoy blog)](http://www.iquilezles.org/)
* [The Elusive Frame Timing (GDC Slides)](https://www.gdcvault.com/play/1025407/Advanced-Graphics-Techniques-Tutorial-The)
* [Drawing Points Properly in WebGL](https://charto.net/blog/drawing-points-properly-in-webgl/)
* [Rendering Graphics Studies (Blog)](http://www.adriancourreges.com/blog/)
* [Multi Channel SDF (Codebase)](https://github.com/Chlumsky/msdfgen)
* [Arian Courreges, Game Studies (Blog)](http://www.adriancourreges.com/blog/)
* [Advances in realtime rendering(Courses)](http://advances.realtimerendering.com/)
* [Huge rendering resource repository (Website)](http://kesen.realtimerendering.com/)
* [Fabien Sanglard (Website)](http://fabiensanglard.net/)
* [Shadertoy Discord](https://discord.gg/XtmMN6E)
* [How Unreal Renders A Frame (Blog Post)](https://interplayoflight.wordpress.com/2017/10/25/how-unreal-renders-a-frame/)
* [Doom Eternal Graphics Study (Blog Post)](https://simoncoenen.com/blog/programming/graphics/DoomEternalStudy.html)
* [The Technical Art of The Last of Us Part II (Slides)](http://advances.realtimerendering.com/s2020/index.htm)
* [Why are video games graphics (still) a challenge? Productionizing rendering algorithms (Blog Post)](https://bartwronski.com/2020/12/27/why-are-video-games-graphics-still-a-challenge-productionizing-rendering-algorithms/)
* [Computing Gradients On Grids - Forward, Central and diagonal differences (Blog Post)](https://bartwronski.com/2021/02/28/computing-gradients-on-grids-forward-central-and-diagonal-differences/)
* [Graphics Pipelines For Young Bloods (Blog Post)](https://www.jeremyong.com/cpp/2021/05/20/graphics-pipelines-for-young-bloods/)
* [fma: A faster, more accurate instruction (Blog Post)](https://momentsingraphics.de/FMA.html)
* [Gradients in linear space aren't better (Blog Post)](https://aras-p.info/blog/2021/11/29/Gradients-in-linear-space-arent-better/)
* [Debugging Your Renderer (3/n): Assertions (and on not sweeping things under the rug) (Blog Post)](https://pharr.org/matt/blog/2021/12/02/debugging-renderers-assertions)
* [Frickin Shaders With Frickin Laser Beams (Shader composition framework) (Blog Post)](https://acko.net/blog/frickin-shaders-with-frickin-laser-beams/)
* [Let’s Close the Buffer Zoo (Blog Post)](http://www.joshbarczak.com/blog/?p=1260)
* [Kajiya GI Overview (Blog Post)](https://github.com/EmbarkStudios/kajiya/blob/main/docs/gi-overview.md)
* [Slang Shading Language Advances (Slides)](https://research.nvidia.com/publication/2022-04_slang-shading-language-advances)
* [In defense of NIR (Blog Post)](https://www.jlekstrand.net/jason/blog/2022/01/in-defense-of-nir/)
* [Summed Area Tables (Research Paper)](https://www.google.ca/url?sa=t&source=web&rct=j&url=http://www.florian-oeser.de/wordpress/wp-content/2012/10/crow-1984.pdf&ved=2ahUKEwjEpdHzta3ZAhWDm1kKHQenBXAQFjAAegQIExAB&usg=AOvVaw3k-SJwguBUsBS5x5lX7C1u)
* [Material Pipeline for The Order: 1886 (PDF)](http://blog.selfshadow.com/publications/s2013-shading-course/rad/s2013_pbs_rad_notes.pdf)
* [Checkerboard rendering (Blog Post)](https://bartwronski.com/2018/05/14/checkerboard-rendering-rotated-anti-aliasing-and-grid-frequencies/amp/)
* [Volumetric Light Effects in Killzone: Shadow Fall (Series)](http://what-when-how.com/Tutorial/topic-547pjramj8/GPU-Pro-Advanced-Rendering-Techniques-146.html)
* [Checkerboard Rendering (White Paper)](https://software.intel.com/en-us/articles/checkerboard-rendering-for-real-time-upscaling-on-intel-integrated-graphics-v-12)
* [Advances in Real-time Rendering 2018 (List)](http://advances.realtimerendering.com/s2018/index.htm)
* [A Ray-Box Intersection Algorithm and Efficient Dynamic Voxel Rendering (White Paper)](http://www.jcgt.org/published/0007/03/04/)
* [Dreams - The tech behind the magic (Video)](https://www.youtube.com/watch?v=yZM_Ij9aeOA)
* [GPU... stuff (Slides)](https://drive.google.com/file/d/12ahbqGXNfY3V-1Gj5cvne2AH4BFWZHGD/view)
* [Spectral rendering with bounded MESE and sRGB data (Research Paper)](http://momentsingraphics.de/?page_id=257)
* [Distance Fields (Blog Post)](https://prideout.net/blog/distance_fields/)
* [Text Hates you (Blog Post)](https://gankra.github.io/blah/text-hates-you/)
* [Digesting The Elephant (Paper)](https://ingowald.blog/2020/01/09/digesting-the-elephant/amp/?__twitter_impression=true)
* [Tile Based Optimization for Post Processing (Blog Post)](https://wickedengine.net/2020/01/05/tile-based-optimization-for-post-processing/)
* [Learning From Failure (Blog Post)](http://media.lolrus.mediamolecule.com/AlexEvans_SIGGRAPH-2015-sml.pdf)
* [A Pixel Is Not a Little Square (Paper)](http://alvyray.com/Memos/CG/Microsoft/6_pixel.pdf)
* [Sampling Reconstruction (Slides)](http://graphics.cs.cmu.edu/courses/15-463/2007_fall/Lectures/SamplingReconstruction.pdf)
* [Interpolating Data Over Arbitrary Surfaces (Blog Post)](https://blog.demofox.org/2020/07/11/interpolating-data-over-arbitrary-shapes-with-laplaces-equation-and-walk-on-spheres/)
* [Smoke Lighting And Texture Re-usability in Skull And Bones (Blog Post)](https://realtimevfx.com/t/smoke-lighting-and-texture-re-usability-in-skull-bones/5339)
* [Temporal Anti-Aliasing Starter Pack (Blog Post)](http://alextardif.com/TAA.html)
* [A Gentle Introduction To Fluid Simulation (Blog Post)](https://shahriyarshahrabi.medium.com/gentle-introduction-to-fluid-simulation-for-programmers-and-technical-artists-7c0045c40bac)
* [Doom 2016 - The Devil Is In The Details (Slides)](https://advances.realtimerendering.com/s2016/Siggraph2016_idTech6.pdf)
* [Notes on occlusion and directionality in image based lighting. (Blog Post)](https://interplayoflight.wordpress.com/2021/12/28/notes-on-occlusion-and-directionality-in-image-based-lighting/)
* [Temporal AA and the quest for the Holy Trail (Blog Post)](https://www.elopezr.com/temporal-aa-and-the-quest-for-the-holy-trail/)
* [Removing blur from images – deconvolution and using optimized simple filters (Blog Post)](https://bartwronski.com/2022/05/26/removing-blur-from-images-deconvolution-and-using-optimized-simple-filters/)
* [Physical Units for Lights (Blog Post)](https://www.realtimerendering.com/blog/physical-units-for-lights/)
* [Notes on screenspace reflections with FidelityFX SSSR (Blog Post)](https://interplayoflight.wordpress.com/2022/09/28/notes-on-screenspace-reflections-with-fidelityfx-sssr/)
* [A mathematical take on Premultiplied alpha (Blog Post)](https://iquilezles.org/articles/premultipliedalpha/)
* [Binary Search For SDFs (Blog Post)](https://iquilezles.org/articles/binarysearchsdf/)
* [Meshlet Sizing Theory (Blog Post)](https://cohost.org/zeux/post/659687-meshlet-sizing-theor)
* [A Blend Of GCN Optimization And Color Processing (Slides)](https://gpuopen.com/gdc-presentations/2019/gdc-2019-s5-blend-of-gcn-optimization-and-color-processing.pdf)
* [Constant Time Stateless Shuffling and Grouping (Blog Post)](https://www.ea.com/seed/news/constant-time-stateless-shuffling)
* [Permutation Coding for Vertex-Blend Attribute Compression (Paper)](https://momentsingraphics.de/Media/I3D2022/peters2022_permutation_coding_paper.pdf)
    * Readers note: Interesting insights on approaches to quantization and storing information through permutations of a sorted list.
* [Dynamic Occlusion with Signed Distance Fields (Slides)](https://advances.realtimerendering.com/s2015/DynamicOcclusionWithSignedDistanceFields.pdf)
* [Make Your Game Friendly for Graphics Debugging and Optimization (Slides)](https://gpuopen.com/presentations/2019/digital-dragons-2019-make-your-game-friendly.pdf)
* [GPU driven rendering in AnKi: A high level overview (Blog Post)](https://anki3d.org/gpu-driven-rendering-in-anki-a-high-level-overview/)
* [Rendering God Of War Ragnarok (Slides)](https://sms.playstation.com/media/documents/GOWR_Stephen_Mcauley_RenderingGOWR_GDC23.pdf)
* [Re-inventing The Wheel For Snow Rendering (Slides)](https://www.gdcvault.com/play/1028844/Advanced-Graphics-Summit-Reinventing-the)
* [Hammersley Points on the Hemisphere (Blog Post)](http://holger.dammertz.org/stuff/notes_HammersleyOnHemisphere.html)
* [The Rendering Of The Callisto Protoco (Slides)](https://advances.realtimerendering.com/s2023/SIGGRAPH2023-Advances-The-Rendering-of-The-Callisto-Protocol-JimenezPetersen.pdf)
* [Coverage Bitmasks for Efficient Rendering Algorithms (Slides)](https://www.ea.com/seed/news/coverage-bitmasks)
* [Radiance Cascades: A Novel Approach to Calculating Global Illumination (Paper)](https://drive.google.com/file/d/1L6v1_7HY2X-LV3Ofb6oyTIxgEaP4LOI6/view?pli=1)
* [Efficient GPU Screen-Space Ray Tracing (Paper)](https://jcgt.org/published/0003/04/04/paper.pdf)
* [Creating a Directed Acyclic Graph from a Mesh (Blog Post)](https://blog.traverseresearch.nl/creating-a-directed-acyclic-graph-from-a-mesh-1329e57286e5)
* [Low-level thinking in high-level shading languages 2023 (Blog Post)](https://interplayoflight.wordpress.com/2023/12/29/low-level-thinking-in-high-level-shading-languages-2023/)
* [High Performance Voxel Engine: Vertex Pooling (Blog Post)](https://nickmcd.me/2021/04/04/high-performance-voxel-engine/)
* [Schneider VFX Portfolio (Lots of cloud research) (Blog Post)](https://www.schneidervfx.com/)
* [Recreating Nanite: LOD generation (Blog Post)](https://jglrxavpok.github.io/2024/01/19/recreating-nanite-lod-generation.html)
* [Occluding Contour Breakthroughs (Blog Post)](https://aaronhertzmann.com/2023/07/31/occluding-contours-part-1.html)
* [Dead Space Remake - Environmental Shaders (Blog Post)](https://www.artstation.com/artwork/elPxyw)
* [Breakdown: Syndicate (2012) (Blog Post)](https://www.froyok.fr/blog/2024-01-breakdown-syndicate/)

### Occlusion

* [Half baked: Dynamic Occlusion Culling (Blog Post)](http://c0de517e.blogspot.com/2023/03/half-baked-dynamic-occlusion-culling.html)
* [Two-Pass Occlusion Culling (Blog Post)](https://medium.com/@mil_kru/two-pass-occlusion-culling-4100edcad501)
* [GPU based occlusion culling (Blog Post)](https://interplayoflight.wordpress.com/2017/11/15/experiments-in-gpu-based-occlusion-culling/)

### Sky Lighting

* [Realistic Real-time Sky Dome Rendering in Gran Turismo 7 (Slides)](https://www.gdcvault.com/play/1029434/Advanced-Graphics-Summit-Realistic-Real)
* [Assassin’s Creed 4: Black Flag - Lighting, Weather and Atmospheric Effects (slides)](https://bartwronski.files.wordpress.com/2014/05/assassin_s-creed-4-digital-dragons-2014-no_notes.pdf)
* [Rendering The World Of Far Cry 4 (Slides)](https://ubm-twvideo01.s3.amazonaws.com/o1/vault/gdc2015/presentations/McAuley_Stephen_Rendering_the_World.pdf)

### Depth

* [Linearize the depth buffer (Forum)](https://community.khronos.org/t/linearize-the-depth-buffer/72335/2)
* [Maximizing depth buffer range and precision (Blog Post)](https://outerra.blogspot.com/2012/11/maximizing-depth-buffer-range-and.html)
* [Reversed-Z in OpenGL (Blog Post)](https://nlguillemot.wordpress.com/2016/12/07/reversed-z-in-opengl/)
* [Love your Z buffer (Blog Post)](https://www.sjbaker.org/steve/omniv/love_your_z_buffer.html)
* [Depth Buffer Interpolation (Blog Post)](https://www.scratchapixel.com/lessons/3d-basic-rendering/rasterization-practical-implementation/visibility-problem-depth-buffer-depth-interpolation)
* [Linear Depth Buffer (Stack Overflow)](https://stackoverflow.com/questions/47801957/linear-depth-buffer)
* [A couple of notes about Z (Blog Post)](http://www.humus.name/index.php?ID=255)
* [Depth Precision Visualized (Blog Post)](https://developer.nvidia.com/content/depth-precision-visualized)
* [Depth in-depth (PDF)](http://developer.amd.com/wordpress/media/2012/10/Depth_in-depth.pdf)

### Signed Distance Fields

* [GPU-based clay simulation and ray-tracing tech in Claybook (Slides)](https://ubm-twvideo01.s3.amazonaws.com/o1/vault/gdc2018/presentations/Aaltonen_Sebastian_GPU_Based_Clay.pdf)
* [Ray Tracing of Signed Distance Function Grids (Paper)](https://jcgt.org/published/0011/03/06/paper-lowres.pdf)

### Tutorials

* [Learn OpenGL (Tutorial)](https://learnopengl.com/)
* [Fragment Foundry (Tutorial)](http://hughsk.io/fragment-foundry/chapters/01-hello-world.html)
* [Intro to compute shaders (Blog Post)](https://anteru.net/blog/2018/intro-to-compute-shaders/)
* [Scratchapixel (Tutorial)](https://www.scratchapixel.com/)
* [PBR Theory (Tutorial)](https://learnopengl.com/PBR/Theory)
* [FWidth (Tutorial)](https://www.ronja-tutorials.com/2019/11/29/fwidth.html)

### Shader Editors

* [Shadertoy](https://www.shadertoy.com/)
* [Shdr Editor](http://shdr.bkcore.com/)
* [Shader Frog](https://shaderfrog.com/)

### Render Graphs

* [Render graphs and Vulkan — a deep dive (Blog Post)](https://themaister.net/blog/2017/08/15/render-graphs-and-vulkan-a-deep-dive/)
* [An update to our Render Graph - Traverse Research (Blog Post)](https://blog.traverseresearch.nl/an-update-to-our-render-graph-17ca4154fd23)
* [High-level rendering using render graphs (Blog Post)](https://ourmachinery.com/post/high-level-rendering-using-render-graphs/)
* [Framegraphs extensible render framework in frostbite (Slides)](https://www.ea.com/frostbite/news/framegraph-extensible-rendering-architecture-in-frostbite)

## Floating Point

* [Floating Point Error (Blog Post)](https://matthew-brett.github.io/teaching/floating_error.html)
* [What every computer scientist should know about floating point (Paper)](https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)
* [There are Only Four Billion Floats so Test Them All (Blog Post)](https://randomascii.wordpress.com/2013/07/16/floating-point-determinism/)
* [Floating Point Determinism (Blog Post)](https://randomascii.wordpress.com/2013/07/16/floating-point-determinism/)
* [Floating Point (White Paper)](http://www.cse.hcmut.edu.vn/~hungnq/courses/501120/docthem/Single%20precision%20floating-point%20format%20-%20Wikipedia.pdf)
* [NaNs cause the craziest bugs (Blog Post)](https://cohost.org/tomforsyth/post/1068776-na-ns-cause-the-crazi)

## Algorithms

* [Visualizing Algorithms (Blog Port)](https://bost.ocks.org/mike/algorithms/)
* [Pathfinding with Cellular automota (Blog Post)](https://nullprogram.com/blog/2014/06/22/)
* [QGrep Internals (Blog Post)](https://zeux.io/2019/04/20/qgrep-internals/)

## Networking

* [Gaffer On Games (Blog)](https://gafferongames.com/)
* [VR Networked Physics (Article)](https://developer.oculus.com/blog/networked-physics-in-virtual-reality-networking-a-stack-of-cubes-with-unity-and-physx/)
* [Poor Man's Netcode (Article)](https://www.gamedev.net/articles/programming/networking-and-multiplayer/the-poor-mans-netcode-r4851/)

## CPU Archicture

* [Branch Prediction Rundown (Blog Post)](http://danluu.com/branch-prediction/)
* [Introduction to dataflow graphs (Blog Post)](https://wp.me/pF1Ai-1Qg)
* [Hardware Effects (Repo)](https://github.com/Kobzol/hardware-effects)
* [Write Combining is not your friend (Blog Post)](https://fgiesen.wordpress.com/2013/01/29/write-combining-is-not-your-friend/)
* [Why do CPUs have multiple cache levels? (Blog Post)](https://fgiesen.wordpress.com/2016/08/07/why-do-cpus-have-multiple-cache-levels/)
* [Assembly Intrinsics (Blog Post)](https://danluu.com/assembly-intrinsics/)
* [Cores don't like to share (Blog Post)](https://fgiesen.wordpress.com/2013/01/31/cores-dont-like-to-share/)
* [Modern Microprocessors - A 90-Minute Guide! (Blog Post)](http://www.lighterra.com/papers/modernmicroprocessors/)
* [Memory Disambiguation and Store Forwarding (Blog Post)](http://blog.stuffedcow.net/2014/01/x86-memory-disambiguation/)
* [Henry - StuffedCow (Blog)](http://blog.stuffedcow.net/category/measurements/)
* [Measuring Reorder Buffer Capacity (Blog Post)](http://blog.stuffedcow.net/2013/05/measuring-rob-capacity/)
* [Avoiding Instruction Cache Misses (Blog Post)](https://pdziepak.github.io/2019/06/21/avoiding-icache-misses/)
* [The surprising subtleties of zeroing a register (Blog Post)](https://randomascii.wordpress.com/2012/12/29/the-surprising-subtleties-of-zeroing-a-register/)
* [What is the best way to set a register to zero in x86? (Stack Overflow)](https://stackoverflow.com/questions/33666617/what-is-the-best-way-to-set-a-register-to-zero-in-x86-assembly-xor-mov-or-and/33668295#33668295)
* [Parallel Computer Architecture And Programming (Lectures)](http://15418.courses.cs.cmu.edu/spring2017/lectures)
* [Cache Coherence Implementation (Blog Post)](https://sites.utexas.edu/jdm4372/category/computer-hardware/cache-coherence-implementations/)
* [Notes on non-temporal (aka streaming) stores (Blog Post)](https://sites.utexas.edu/jdm4372/2018/01/01/notes-on-non-temporal-aka-streaming-stores/)
* [Cache Coherence Protocols (Blog Post)](https://sites.utexas.edu/jdm4372/category/computer-architecture/cache-coherence-protocols/)
* [Mutexes Vs Spinlocks (Blog Post)](https://www.realworldtech.com/forum/?threadid=189711&curpostid=189723)
* [The Significance Of The x86 lfence Instruction (Blog Post)](https://hadibrais.wordpress.com/2018/05/14/the-significance-of-the-x86-lfence-instruction/)
* [Why Use LEA instead of ADD (Stack Overflow Answer)](https://stackoverflow.com/a/6328441)
* [Using the LEA instruction for arbitrary arithmetic (Blog Post)](https://handmade.network/forums/articles/t/7111-using_the_lea_instruction_for_arbitrary_arithmetic)

### Optimizations

* [Decreasing the Number of Memory Accesses (Blog Series)](https://johnnysswlab.com/decreasing-the-number-of-memory-accesses-1-2/)
* [Comments on timing short code sections on intel processors (Blog Post)](https://sites.utexas.edu/jdm4372/2018/07/23/comments-on-timing-short-code-sections-on-intel-processors/)
* [Branch/cmove and compiler optimizations (Blog Post)](https://kristerw.github.io/2022/05/24/branchless/)
* [It's done in hardware so it's cheap (Blog Post)](http://yosefk.com/blog/its-done-in-hardware-so-its-cheap.html)
* [Speed Limits (Blog Post) - Recommended](https://travisdowns.github.io/blog/2019/06/11/speed-limits.html)
* [Software Optimization Resources (Guides) - Recommended](https://www.agner.org/optimize/)

### Vectorization

* [SIMD at Insomniac Games (PDF)](https://deplinenoise.files.wordpress.com/2015/03/gdc2015_afredriksson_simd.pdf)
* [SSE Mind the gaps! (Blog Post)](https://fgiesen.wordpress.com/2016/04/03/sse-mind-the-gap/)
* [AVX-512: When and how to use these new instructions](https://lemire.me/blog/2018/09/07/avx-512-when-and-how-to-use-these-new-instructions/)
* [By how much does AVX-512 slow down your CPU?](https://lemire.me/blog/2018/04/19/by-how-much-does-avx-512-slow-down-your-cpu-a-first-experiment/)
* [SMACNI to AVX512 the life cycle of an instruction set (PDF)](http://tomforsyth1000.github.io/papers/LRBNI%20origins%20v4%20full%20fat.pdf)
* [A note on mask registers (Blog Post)](https://travisdowns.github.io/blog/2019/12/05/kreg-facts.html)
* [This Goes To Eleven (Blog Post)](https://bits.houmus.org/2020-01-28/this-goes-to-eleven-pt1)

## Retro

* [Old-School Raycasting Pt1 (Series)](https://lodev.org/cgtutor/raycasting.html)
* [Old-School Raycasting Pt2 (Series)](https://lodev.org/cgtutor/raycasting2.html)
* [Old-School Raycasting Pt3 (Series)](https://lodev.org/cgtutor/raycasting3.html)
* [Old-School Raycasting Pt4 (Series)](https://lodev.org/cgtutor/raycasting4.html)
* [PlayStation 3 Architecture (Blog Post)](https://www.copetti.org/writings/consoles/playstation-3/)
* [Xbox 360 Architecture (Blog Post)](https://www.copetti.org/writings/consoles/xbox-360/)

## Threading

* [Thread Sanitizer A thread debugging tool (Repo)](https://github.com/google/sanitizers/wiki/ThreadSanitizerCppManual)
* [Acquire And Release Semantics (Blog Post)](https://preshing.com/20120913/acquire-and-release-semantics/)
* [Acquire And Release Fences Don't Work The Way You'd Expect (Blog Post)](https://preshing.com/20131125/acquire-and-release-fences-dont-work-the-way-youd-expect/)
* [The Synchronizes With Relation (Blog Post)](https://preshing.com/20130823/the-synchronizes-with-relation/)
* [Memory Reordering Caught In The Act (Blog Post)](https://preshing.com/20120515/memory-reordering-caught-in-the-act/)
* [Memory Barriers Are Like Source Control (Blog Post)](https://preshing.com/20120710/memory-barriers-are-like-source-control-operations/)
* [Who Ordered Memory Fences On An x86? (Blog Post)](https://bartoszmilewski.com/2008/11/05/who-ordered-memory-fences-on-an-x86/)
* [Are Loads And Stores The Only Instructions That Get Reordered? (Stack Overflow)](https://stackoverflow.com/questions/50494658/are-loads-and-stores-the-only-instructions-that-gets-reordered)
* [Why Does A std::atomic Store With Sequential Consistency Use xchg (Stack Overflow)](https://stackoverflow.com/questions/49107683/why-does-a-stdatomic-store-with-sequential-consistency-use-xchg)
* [Does The Intel Memory Model Make sfence and lfence Redundant? (Stack Overflow)](https://stackoverflow.com/questions/32705169/does-the-intel-memory-model-make-sfence-and-lfence-redundant)
* [Why Is A Store Load Barrier Considered Expensive? (Stack Overflow)](https://stackoverflow.com/questions/27475025/why-is-a-store-load-barrier-considered-expensive)
* [Does Lock xchg Have The Same Behaviour As mfence? (Stack Overflow)](https://stackoverflow.com/questions/40409297/does-lock-xchg-have-the-same-behavior-as-mfence)
* [What is RCU? -- "Read, Copy, Update" (Blog Post)](https://www.kernel.org/doc/html/next/RCU/whatisRCU.html)

## Sound

* [Digital Media Primer (Videos)](https://xiph.org/video/)

## Collision

* [Simple Intersection Tests For Games (Blog Post)](https://www.gamasutra.com/view/feature/3383/simple_intersection_tests_for_games.php?page=3)
* [2D AABB vs AABB how to calculate normal (Stack Exchange)](https://gamedev.stackexchange.com/questions/28577/2d-aabb-vs-aabb-sweep-how-to-calculate-hit-normal)
* [What's the fastest way of checking if 2 AABB intersect? (Stack Exchange)](https://gamedev.stackexchange.com/questions/93035/whats-the-fastest-way-checking-if-two-moving-aabbs-intersect)
* [Swept AABB and response (Blog Post)](https://www.gamedev.net/tutorials/_/technical/game-programming/swept-aabb-collision-detection-and-response-r3084/)
* [Axis-Aligned Bounding Dual Simplex (Google Doc)](https://docs.google.com/document/d/15F1ujW8ROTDMtQFkn29_ZybhkvSJcGGzzuyPWcVsToU/edit)

## Misc

* [Aras P (Blog)](https://aras-p.info/blog/)
* [Demo Scene and more (Blog)](https://blog.demofox.org/)
* [Semantic Compression (Blog Post)](https://caseymuratori.com/blog_0015)
* [The blog at the bottom of the sea (Blog - Math, Programming, Graphics)](https://blog.demofox.org/)
* [Digital Signal Processing Guide (PDF Book)](http://www.dspguide.com/pdfbook.htm)
* [Why the way we look at technical debt is wrong](https://www.bigeng.io/why-the-way-we-look-at-technical-debt-is-wrong)
* [The Story behind The Truth: Designing a Data Model](https://ourmachinery.com/post/the-story-behind-the-truth-designing-a-data-model/)
* [A queue of page faults (Blog Post)](https://zeux.io/2014/12/21/page-fault-queue/#fn:1)
* [Profiling: Measurement and Analysis (League Of Legends Blog Post)](https://technology.riotgames.com/news/profiling-measurement-and-analysis)
* [Hidden cost of MemoryAllocation (Blog Post)](https://randomascii.wordpress.com/2014/12/10/hidden-costs-of-memory-allocation/)
* [A question about avoiding page faults the first time newly-allocated memory is accessed (Blog post)](https://devblogs.microsoft.com/oldnewthing/?p=96146)
* [AOSOA (Blog Post)](https://twitter.com/grujicbr/status/1150459559909220352?s=19)
* [Over-engineering (the root of all evil)](http://c0de517e.blogspot.com/2016/10/over-engineering-root-of-all-evil.html)
* [How LLVM optimizes power sums (Article)](https://kristerw.blogspot.com/2019/04/how-llvm-optimizes-geometric-sums.html?m=1)
* [Thinking About Technical Debt (Twitter Thread)](https://twitter.com/RonJeffries/status/1194279406530957312?s=20)
* [Data Compression - Bit Packing 101 (Blog Post)](https://www.kinematicsoup.com/news/2016/9/6/data-compression-bit-packing-101)
* [Fibersunder the magnifying glass (Paper)](http://www.open-std.org/JTC1/SC22/WG21/docs/papers/2018/p1364r0.pdf)
* [Fibers aren’t useful for much any more; there’s just one corner of it that remains useful for a reason unrelated to fibers (Blog Post)](https://devblogs.microsoft.com/oldnewthing/20191011-00/?p=102989)
* [Write comining is not your friend (Blog Post)](https://fgiesen.wordpress.com/2013/01/29/write-combining-is-not-your-friend/)
* [The Size Of Tracing Data (Blog Post)](https://richardstartin.github.io/posts/the-size-of-tracing-data)
* [Reading Research: A Guide For Software Engineers (Blog Post)](https://brooker.co.za/blog/2020/05/25/reading.html)
* [Challenges of Debugging Optimized x64 Code (Blog Post)](https://docs.microsoft.com/en-us/archive/blogs/ntdebugging/challenges-of-debugging-optimized-x64-code)
* [Step By Step Programming (Blog Post)](https://ourmachinery.com/post/step-by-step-programming-incrementally/)
* [Insider guide to tech interviews (Blog Post)](https://bartwronski.com/2022/01/04/insider-guide-to-tech-interviews/)
* [Optimizing astcenc (Blog Post)](https://solidpixel.github.io/2022/04/22/astc_optimization.html)
* [You And Your Research (Blog Post)](https://www.cs.virginia.edu/~robins/YouAndYourResearch.html)
* [X64 Function Hooking by Example (Blog Post)](http://kylehalladay.com/blog/2020/11/13/Hooking-By-Example.html)
* [Mike Acton’s Expectations of Professional Software Engineers (Blog Post)](https://adamj.eu/tech/2022/06/17/mike-actons-expectations-of-professional-software-engineers/)
* [MAKING TOOLS FOR BIG GAMES (Slides)](https://d3d3g8mu99pzk9.cloudfront.net/MichielVanDerLeeuw/CEDEC%202019%20-%20Making%20Tools%20for%20Big%20Games.pdf)
* [A Matter Of Precision (Blog Post)](https://cohost.org/tomforsyth/post/943070-a-matter-of-precisio)
* [The power of asking why, why, why, why, why (Blog Post)](https://rystorm.com/blog/why-why-why-why-why)
* [Efficient Parallel Prefix Sum in Metal for Apple M1 (Blog Post)](https://kieber-emmons.medium.com/efficient-parallel-prefix-sum-in-metal-for-apple-m1-9e60b974d62)
* [Systems design 2: What we hope we know (Blog Post)](https://apenwarr.ca/log/20230415)
* [The Tyranny of structurelessness(Blog Post)](https://www.jofreeman.com/joreen/tyranny.htm)
* [How I made Tracy 30× faster (Blog Post)](https://wolf.nereid.pl/posts/how-tracy-faster/)
* [Learnings As a Graphics Lead (Blog Post)](https://alextardif.com/Leading.html)
* [How I Evaluate Game Engines (Blog Post)](https://www.jeremyong.com/game%20engines/2023/09/15/how-i-evaluate-game-engines/)
* [Anti-Debug: Process Memory (Blog Post)](https://anti-debug.checkpoint.com/techniques/process-memory.html)
* [Recognizing patterns in memory (Blog Post)](https://www.timdbg.com/posts/recognizing-patterns/)
* [Technical debt… or technical weight/burden? (Blog Post)](https://bartwronski.com/2016/06/26/technical-weight/)
* [Making a Mesh: Global Mesh Destruction in First Encounters (Blog Post)](https://developer.oculus.com/blog/scene-mesh-destruction-first-encounters-meta-quest-developers-mixed-reality/)
* [The Grug Brained Developer - A layman's guide to thinking like the self-aware smol brained (Blog Post)](https://grugbrain.dev/)
* [A dive into the making of Immersion (Blog Post)](https://www.ctrl-alt-test.fr/2018/a-dive-into-the-making-of-immersion/)
* [Making floating point numbers smaller (Blog Post)](https://www.ctrl-alt-test.fr/2018/making-floating-point-numbers-smaller/)
* [How can demoscene productions be so small? (Blog Post)](https://www.ctrl-alt-test.fr/2017/how-can-demoscene-productions-be-so-small/)
* [OMBRE Dev-Blog Year 1 (Blog Post)](https://www.froyok.fr/blog/2023-12-ombre-dev-blog-1/)
* [Speed up your code: don't pass structs bigger than 16 bytes on AMD64 (Blog Post)](https://gist.github.com/FeepingCreature/5dff669aad380a123b15659e195fb96c)
* [Handle Lookup Container (Sparse Set) (Blog Post)](https://tomhultonharrop.com/c++/lookup/handle/2024/01/07/handle-lookup-container.html)
* [Micro-optimizations in Kotlin (Blog Series)](https://www.romainguy.dev/posts/2024/micro-optimizations-in-kotlin-1/)
* [The Hiring Post (Blog Post)](https://sockpuppet.org/blog/2015/03/06/the-hiring-post/)
* [No one can teach you to have conviction (Blog Post)](https://www.benkuhn.net/conviction/)
* [My favourite Git commit (Blog Post)](https://dhwthompson.com/2019/my-favourite-git-commit)

## Unity

* [Behind the burst compiler (Slides)](https://onedrive.live.com/View.aspx?resid=9ECC7012112E02DA!46903&wdSlideId=257&wdModeSwitchTime=1561813824914&authkey=!ACA8uHlLshdbrrU)

## Unreal

* [Unreal Engine Game Optimization on a Budget (Blog Post)](https://www.tomlooman.com/unrealengine-optimization-talk/)
* [Journey To Lumen (Blog Post)](https://knarkowicz.wordpress.com/2022/08/18/journey-to-lumen/)
* [Journey To Nanite (Slides)](https://highperformancegraphics.org/slides22/Journey_to_Nanite.pdf)
* [Nanite Overview (Slides)](https://advances.realtimerendering.com/s2021/Karis_Nanite_SIGGRAPH_Advances_2021_final.pdf)
* [Debugging and Optimizing Memory (Blog Post)](https://www.unrealengine.com/en-US/blog/debugging-and-optimizing-memory)
* [Distance Field Ray Tracing Part 1: Volume Textures and Ray Marching Primer (Blog Post)](https://shaderbits.com/blog/distance-field-ray-tracing-part1)
* [Unreal Engine 4 Rendering (Blog Series)](https://medium.com/@lordned/unreal-engine-4-rendering-overview-part-1-c47f2da65346)
* [Lumen, Real-time Global Illumination in Unreal Engine 5 (Slides)](<https://advances.realtimerendering.com/s2022/SIGGRAPH2022-Advances-Lumen-Wright et al.pdf>)
* [Unreal Engine Substrate: Authoring Materials That Matter (Slides)](https://advances.realtimerendering.com/s2023/2023%20Siggraph%20-%20Substrate.pdf)
* [Render Dependency Graph (Documentation)](https://docs.unrealengine.com/5.1/en-US/render-dependency-graph-in-unreal-engine/)
* [Optimizing Shaders in Unreal Engine (Blog Post)](https://calvinatorrtech.art.blog/2023/12/20/optimizing-shaders-in-unreal-engine/)
