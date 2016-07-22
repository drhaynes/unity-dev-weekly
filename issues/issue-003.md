# Unity Dev Weekly
## Issue 3
*July 22nd 2016*

### News

#### [Unity Releases Experimental Compiler Upgrade](http://forum.unity3d.com/threads/upgraded-c-compiler-on-5-3-5p8.417363/)
It's happening...
> The upgraded Mono C# compiler (corresponding to Mono 4.4) will be used to compile all your C# scripts
In the words of joncham on the forum: 'This is the first step towards the mythical Mono/.NET Upgrade.'

Very exciting stuff, but why use the upgraded compiler if it doesn't have any newer language feature support yet?

>The new Mono and C# compiler generally runs faster and has many years of bug fixes compared to our previous compiler.

Note that this specifically and deliberately doesn't support C# 6 features yet. It seems like this first release is all about getting a stable upgraded compiler into Unity without anything breaking.

[http://forum.unity3d.com/threads/upgraded-c-compiler-on-5-3-5p8.417363/](http://forum.unity3d.com/threads/upgraded-c-compiler-on-5-3-5p8.417363/)
​
#### [Made With Unity Site Updated](https://madewith.unity.com/)
The Made With Unity site has been update with a fresh design and the ability for anyone to register to showcase their project. Seems like Unity is refreshing much of its online presence in the last few months.

[https://madewith.unity.com/](https://madewith.unity.com/)

### Graphics

#### [Volumetric Rendering: Surface Shading](http://www.alanzucconi.com/2016/07/01/surface-shading/)

Part 3 in Alan Zucconi's series on volumetric rendering. We're starting to get into the nitty-gritty now, as this issue covers surface shading. We take the unlit outline shapes from the last tutorial and add some lighting. It's interesting to be essentially bypassing Unity's existing shader model, so this technique doesn't limit you in any way in terms of what's possible.

[http://www.alanzucconi.com/2016/07/01/surface-shading/](http://www.alanzucconi.com/2016/07/01/surface-shading/)

#### [Fractal Cave](https://www.shadertoy.com/view/Xtt3Wn)

Incredible Shadertoy example showing fractals and 3d path tracing in WebGL. Really useful to see the shader code that goes into this.

[https://www.shadertoy.com/view/Xtt3Wn](https://www.shadertoy.com/view/Xtt3Wn)

#### [Dead Secret Diary: Lightmapping in Unity 5](http://robotinvader.com/blog/?p=516)

A deep dive on the work done in Dead Secret to upgrade their lightmapping solution from Unity 4 to Unity 5. Some really insightful stuff here, and fairly damning criticism of Unity's decision to move from Beast in Unity 4 to Enlighten in Unity 5.

> Therefore my conclusion is that the move from Beast to Enlighten has been, for developers like ourselves, a disaster.

Ouch.

[http://robotinvader.com/blog/?p=516](http://robotinvader.com/blog/?p=516)

#### [Demystifying the Enlighten Precompute Process](http://www.geomerics.com/blogs/demystifying-the-enlighten-precompute/)

And to get an idea why lightmapping seems to take forever, and you're constantly seeing that 'clustering...' progress bar in the bottom right of the Unity Editor window, here's some technical detail from the Enlighten guys themselves on exactly what's going on when the lightmaps are being baked for realtime GI.

[http://www.geomerics.com/blogs/demystifying-the-enlighten-precompute/](http://www.geomerics.com/blogs/demystifying-the-enlighten-precompute/)

#### [Making Terraced Terrain](http://icospheric.com/blog/2016/07/17/making-terraced-terrain/)

Very cool tutorial on making terrain that has a low poly terraced look.

[http://icospheric.com/blog/2016/07/17/making-terraced-terrain/](http://icospheric.com/blog/2016/07/17/making-terraced-terrain/)

### Tools

#### [LevelMerge: Collaborative Game Level Editing by Merging Labeled Graphs](http://pellacini.di.uniroma1.it/publications/levelmerge16/levelmerge16.html)

This is incredible. Realtime collaborative scene editing in Unity. Imagine Google Docs meets the Unity Editor, and that's what you have here. Multiple people working on the same scene in realtime, without conflicts. Surely the future of the way we make games, especially considering the move to immersive VR-based design.

Unity, please buy this tech and incorporate it asap!

[http://pellacini.di.uniroma1.it/publications/levelmerge16/levelmerge16.html](http://pellacini.di.uniroma1.it/publications/levelmerge16/levelmerge16.html)

#### [Unity Hotkeys – keyboard shortcuts in Unity](http://blogs.unity3d.com/2011/08/24/unity-hotkeys-keyboard-shortcuts-in-unity/)

Useful cheat sheet on all the default hotkeys in the Unity Editor. From creating an empty GameObject to building, knowing hotkeys can make you substantially more productive.

[http://blogs.unity3d.com/2011/08/24/unity-hotkeys-keyboard-shortcuts-in-unity/](http://blogs.unity3d.com/2011/08/24/unity-hotkeys-keyboard-shortcuts-in-unity/)

#### [Issue Tracker for Unity Releases](https://issuetracker.unity3d.com/product/unity/issues?category=&page=2&status=1&unity_version=released&utf8=%E2%9C%93&view=hottest)

Useful reference tool to have to evaluate released Unity versions before you install them, or to confirm bugs that you suspect you are running in to. The quality of Unity releases seems to be on an upward trend compared to a year or two ago, but it's far from ideal yet.

[https://issuetracker.unity3d.com/product/unity/issues?category=&page=2&status=1&unity_version=released&utf8=%E2%9C%93&view=hottest](https://issuetracker.unity3d.com/product/unity/issues?category=&page=2&status=1&unity_version=released&utf8=%E2%9C%93&view=hottest)

### Assets

#### [Kenney produces games and game assets, based in Europe (Netherlands)](http://kenney.nl/)

Incredible source of free (and some paid) assets for Unity 3d. Great for prototyping, and have the following very permissive license:

>CC0 1.0 Universal (CC0 1.0)

>You're free to use these game assets in any project, personal or commercial. There's no need to ask permission before using these. Giving attribution is not required, but is greatly appreciated!

Especially cool: [UI Pack](http://kenney.nl/assets/ui-pack)

[http://kenney.nl/](http://kenney.nl/)

#### [Search Engine for Open Source Assets for Unity3D](http://unitylist.com/)

Newly released tool for finding open source assets on the Asset Store. Potentially very useful, though appears to be blocked by some content blockers for being a 'new site' - YMMV.

[http://unitylist.com/](http://unitylist.com/)

### Code

#### [VS 2015 Tooling Update for Unity Game Devs](https://visualstudiomagazine.com/articles/2016/07/14/visual-studio-2015-tools-for-unity-2-3.aspx)

The official Unity VS plugin has been updated. Highlights are fixes for Xamarin users, debugging improvments and the ability to create `MonoBehaviour` classes from the VS wizard. Upgrade now.

[https://visualstudiomagazine.com/articles/2016/07/14/visual-studio-2015-tools-for-unity-2-3.aspx](https://visualstudiomagazine.com/articles/2016/07/14/visual-studio-2015-tools-for-unity-2-3.aspx)

#### [De-Cruft Visual Studio](https://jackmott.github.io/programming/tools/editor/ide/visual/studio/2016/07/11/decruft-visual-studio.html)

Nice post on optimising your Visual Studio layout. It's amazing how much cruft is turned on by default, and how many useful features are hidden away in preferences. Having line numbers visible is a no-brainer for starters.

[https://jackmott.github.io/programming/tools/editor/ide/visual/studio/2016/07/11/decruft-visual-studio.html](https://jackmott.github.io/programming/tools/editor/ide/visual/studio/2016/07/11/decruft-visual-studio.html)

#### [.NET Core Roadmap](https://blogs.msdn.microsoft.com/dotnet/2016/07/15/net-core-roadmap/)

With the move to the new C# compiler, and Unity hiring .NET devs specifically to work on .NET Core integration, it's obvious that the future of Unity lies with the modern .NET platform (finally!). To that end, it's worth keeping abrest of the roadmap for .NET Core - the official cross platform version of the .NET Framework.

[https://blogs.msdn.microsoft.com/dotnet/2016/07/15/net-core-roadmap/](https://blogs.msdn.microsoft.com/dotnet/2016/07/15/net-core-roadmap/)

#### [Braid Code Cleanup (part 1)](http://number-none.com/blow/blog/programming/2016/07/16/braid_code_cleanup_1.html)

Insanely detailed article from the developer of Braid on revisiting the code after some time away and cleaning things up. This post mostly focuses on removing things that aren't used, but touches on some wider issues also.

[http://number-none.com/blow/blog/programming/2016/07/16/braid_code_cleanup_1.html](http://number-none.com/blow/blog/programming/2016/07/16/braid_code_cleanup_1.html)

### Game Design

#### [Prey For The Gods: NextGen Unity Game](http://80.lv/articles/prey-for-gods-unity5-interview/)

Remember when everyone used to say you couldn't make a AAA quality game in Unity? Well, Unity have very much buried that particular hatchet. The work on Prey For The Gods is nothing short of spectacular. One of the best looking titles created in Unity in recent times.

[http://80.lv/articles/prey-for-gods-unity5-interview/](http://80.lv/articles/prey-for-gods-unity5-interview/)

#### [A Pixel Perfect Camera for Unity](http://blog.evilwindowdog.com/post/147292156801/a-pixel-perfect-camera-for-unity)

Evil Window Dog blog post on creating a pixel perfect camera in Unity. If you're making a 2d game or rendering text or other graphics 1:1 on screen, then having pixel perfect rendering is a must. This post goes into detail on the challenges and solutions involved in achieving it.

[http://blog.evilwindowdog.com/post/147292156801/a-pixel-perfect-camera-for-unity](http://blog.evilwindowdog.com/post/147292156801/a-pixel-perfect-camera-for-unity)

### Video

#### [Unite Europe 2016 - Optimising Mobile Applications](https://www.youtube.com/watch?v=j4YAY36xjwE)

Unity are working on some 'Best Practices' documents for optimising things on mobile, and this talk is a preview of that. The speakers cover the Unity Profiler, as well as the tools in the native platform tools, such as Instruments in Xcode. Used with IL2CPP, Instruments is considered the best tool to profile your Unity application, as it will profile both the Unity engine code and your own app-specific code.

If you're looking for a reason to get a Mac, this could finally be the justification you've been searching for!

[https://www.youtube.com/watch?v=j4YAY36xjwE](https://www.youtube.com/watch?v=j4YAY36xjwE)

### And Finally...

#### [The Cutting Room Floor](https://tcrf.net/The_Cutting_Room_Floor)

Fascinating site that catalogues interesting finds in game media that got left out of the final game. If you're interested in people poking around in old cartridge or CD dumps to see what they can find, then this is a site for you. Kind of like Videogame Archeology. Could easily lose a few hours here.

[https://tcrf.net/The_Cutting_Room_Floor](https://tcrf.net/The_Cutting_Room_Floor)

