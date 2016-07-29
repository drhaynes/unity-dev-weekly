# Unity Dev Weekly
## Issue 4

*July 29th 2016*​

### News
#### [Unity 5.4 Has Shipped](https://unity3d.com/unity/whats-new/unity-5.4.0)

After an extended beta period, the latest version of Unity has finally shipped. Hopefully the beta process will mean a more solid release than previous versions, with fewer bugs and regressions. Here's hoping.

Key features:
* Improved multithreaded rendering.
* Motion vector rendering support.
* Android IL2CPP is no longer 'experimental'.
* Transforms now SIMD in the core engine.
* Editor now supports Retina on macOS - finally!
* Editor now has scalable game view - resize a 4k screen to fit into your editor layout.
* Particle system improvements.
* Native cross platform VR support.

[https://unity3d.com/unity/whats-new/unity-5.4.0](https://unity3d.com/unity/whats-new/unity-5.4.0)

#### [John Carmack Calls For 3D Equivalent Of JPEG To Build The Metaverse](http://uploadvr.com/john-carmack-metaverse-gltf/)

Nice to see glTF getting some heavyweight support from key industry players. For anyone in the dark, the GL Transmission Format (glTF) from The Khronos Group aims to provide a lightweight, efficient format meant for 3d scene representation in a way that could be easily streamed, e.g. over the internet.

Quoting Carmack himself, “I think most people hope that the metaverse won’t be built on proprietary media formats.” Agreed.

[http://uploadvr.com/john-carmack-metaverse-gltf/](http://uploadvr.com/john-carmack-metaverse-gltf/)


#### [Unity Roadmap Updated with 5.5 Alpha Features](https://unity3d.com/unity/roadmap)

Along with the release of 5.4, the roadmap page has been updated with all the upcoming features in 5.5. Of particular note is the updated C# compiler and WebGL 2.0 support.

[https://unity3d.com/unity/roadmap](https://unity3d.com/unity/roadmap)

### Unity Tips



### Code


#### [7 Ways to Look at the Values of Variables While Debugging in Visual Studio](https://blogs.msdn.microsoft.com/visualstudioalm/2016/07/15/7-ways-to-look-at-the-values-of-variables-while-debugging-in-visual-studio/)

Debugging doesn't just have to be `Debug.Log` statements. Using the debugger effectively is an essential tool to have at your disposal. This post demonstrates the common ways to use the debugger interface in VS.

[https://blogs.msdn.microsoft.com/visualstudioalm/2016/07/15/7-ways-to-look-at-the-values-of-variables-while-debugging-in-visual-studio/](https://blogs.msdn.microsoft.com/visualstudioalm/2016/07/15/7-ways-to-look-at-the-values-of-variables-while-debugging-in-visual-studio/)




### Game Development


#### [Braid Code Cleanup (part 3)](http://number-none.com/blow/blog//programming/2016/07/18/braid-cleanup-part-3.html)

More fascinating reading from Jonathan Blow on cleaning up the codebase for Braid. This post takes us through the debugging process for some graphical issues encountered whilst removing some legacy image import code.

Imagine a Twitch game dev livestream, but text based - that's what this reads to me like. Fascinating insight into the development and thinking process of the chap behind Braid and The Witness.

[http://number-none.com/blow/blog//programming/2016/07/18/braid-cleanup-part-3.html](http://number-none.com/blow/blog//programming/2016/07/18/braid-cleanup-part-3.html)


#### [Narbacular Drop Technical Design Document pdf](http://nuclearmonkeysoftware.com/documents/narbacular_drop_technical_design_document.pdf)

Narbacular Drop, developed originally by Nuclear Monkey Software, was remade into Portal, and this design document makes for interesting reading. Originally the game included lava as a gameplay element, and you would fight a last boss in the form of a huge demon at the end of the game.

After its released online for free in 2005, Valve noticed the game, hired the entire development team and the rest, as they say, is history.

[http://nuclearmonkeysoftware.com/documents/narbacular_drop_technical_design_document.pdf](http://nuclearmonkeysoftware.com/documents/narbacular_drop_technical_design_document.pdf)


### Graphics


#### [How to Explore Unity 5's Shader System Code - II - Reading the Standard Shader](http://www.shadercat.com/how-to-explore-unity-5s-shader-system-code-ii/](http://www.shadercat.com/how-to-explore-unity-5s-shader-system-code-ii/)

Excellent follow up to the overview in [part I](http://www.shadercat.com/how-to-explore-unity-5s-shader-system-code-i-overview/) of the ShaderCat series on the Unity Standard Shader.

This post delves into the forward rendering path shader code, and demonstrates the lighting functions that comprise this simpler rendering path.

tl;dr:

> As you could see shader is pretty light on lighting calculations, just using a lambert, and look up tables. It doesn't look like Physically Based shading is being used much, it's probably the cheapest version of the standard shader.

[http://www.shadercat.com/how-to-explore-unity-5s-shader-system-code-ii/](http://www.shadercat.com/how-to-explore-unity-5s-shader-system-code-ii/)


#### [Volumetric Rendering: Signed Distance Functions](http://www.alanzucconi.com/2016/07/01/signed-distance-functions/)

The latest part in the series by Alan Zucconi, this article covers signed distance fields, which are mathematical constructs used to describe geometry without using triangles, and with essentially unlimited resolution.

The post covers how to create primitive shapes using SDF, and how to combine them with operations such as blending and boolean union.

[http://www.alanzucconi.com/2016/07/01/signed-distance-functions/](http://www.alanzucconi.com/2016/07/01/signed-distance-functions/)


#### [OTOY and Imagination unveil breakthrough PowerVR Ray Tracing hardware platform for cinematic real time rendering](https://imgtec.com/news/press-release/otoy-imagination-unveil-breakthrough-powervr-ray-tracing-hardware-platform-cinematic-real-time-rendering/)

> OTOY is merging Brigade and OctaneRender 4 next year, which will bring real time cinematic path tracing to both Unity and Unreal Engine.

Very interesting technology from PowerVR. Could it be we will see the holy grail of realtime ray tracing become mainstream within the next couple of years? All the signs point to that being a distinct possibility.

[https://imgtec.com/news/press-release/otoy-imagination-unveil-breakthrough-powervr-ray-tracing-hardware-platform-cinematic-real-time-rendering/](https://imgtec.com/news/press-release/otoy-imagination-unveil-breakthrough-powervr-ray-tracing-hardware-platform-cinematic-real-time-rendering/)


### Tools


#### [In Development – Unity Splash Screen tools  –  Unity Blog](http://blogs.unity3d.com/2016/07/22/in-development-unity-splash-screen-tools/)

Preview of the upcoming splash screen design tools, coming in Unity 5.5. This is a really welcome change, and should help everyone make their Unity offering more polished and professional. It almost looks like a serious engine now!

[http://blogs.unity3d.com/2016/07/22/in-development-unity-splash-screen-tools/](http://blogs.unity3d.com/2016/07/22/in-development-unity-splash-screen-tools/)


#### [Intel Graphics Performance Analyzers](https://software.intel.com/en-us/gpa)

Keijiro Takahashi [tweeted](https://twitter.com/_kzr/status/755991263103426561) about this Powerful GPU analyser from Intel and how it is useful for profiling graphics performance on Android.

[https://software.intel.com/en-us/gpa](https://software.intel.com/en-us/gpa)

### Video


#### [Shaders Case Study - Stealth Games' XRay Vision](https://www.youtube.com/watch?v=OJkGGuudm38)

Nice video from [@DanielJMoran](https://twitter.com/danieljmoran) on building an x-ray effect that you often see in 3rd person stealth games when a character is obscured by part of the scene.

The end result is impressive, and in my opinion more visually pleasing than a lot of implementations in popular titles.

[https://www.youtube.com/watch?v=OJkGGuudm38](https://www.youtube.com/watch?v=OJkGGuudm38)


#### [Physically Based Shading in Theory and Practice](https://www.youtube.com/watch?v=zs0oYjwjNEo)

Long and in-depth video from SIGGRAPH 2016 on Physically Based Shading from a number of different speakers. This gets well and truly into the weeds of the technology behind Unity's Standard Shader model. Some sections of video are missing due to permissions from the various speakers involved, so just skip ahead on those parts.

[https://www.youtube.com/watch?v=zs0oYjwjNEo](https://www.youtube.com/watch?v=zs0oYjwjNEo)


### And Finally...

#### [PokemonGo clone using OpenStreetMap, Mapzen Api and Unity3D](http://barankahyaoglu.com/dev/pokemongo-clone-using-mapzen-api-unity3d/)

You know you want to...

[http://barankahyaoglu.com/dev/pokemongo-clone-using-mapzen-api-unity3d/](http://barankahyaoglu.com/dev/pokemongo-clone-using-mapzen-api-unity3d/)
