# Unity Dev Weekly
## Issue 9
*2nd September 2016*

### News

#### [Unity 5.5 Beta Released](https://unity3d.com/unity/beta)

Hot on the heels of 5.4, Unity has releases 5.5 beta for download. Open to anyone that wants to beta test, it's a good idea to install the beta alongside the regular version of Unity and keep an eye on if things in your project are broken, or will need work to upgrade when the final version is released.

[https://unity3d.com/unity/beta](https://unity3d.com/unity/beta)


### Unity Tips

#### [Official Unity Patch Releases Page](http://unity3d.com/unity/qa/patch-releases)

Unity frequently releases hotfix versions, known as 'patch releases'. This is the official page to grab them from. Good to know this page exists and keep an eye on it, particularly if your project is suffering from a bug or regression in the latest Unity version.

[http://unity3d.com/unity/qa/patch-releases](http://unity3d.com/unity/qa/patch-releases)


#### [Don’t Re-invent Finite State Machines: How to Repurpose Unity’s Animator](https://medium.com/@darrentsung/dont-re-invent-finite-state-machines-how-to-repurpose-unity-s-animator-7c6c421e5785#.c1sqc6eh0)

Another link submitted by [@schoenobates](https://twitter.com/schoenobates). Great example of creative use of the tools available to solve a particular problem.

> There are two main approaches for creating and using FSMs: writing a quick and dirty implementation or buying an asset from the asset store to use. But there is a third option: using Unity’s built-in animator system (Mecanim).

[https://medium.com/@darrentsung/dont-re-invent-finite-state-machines-how-to-repurpose-unity-s-animator-7c6c421e5785#.c1sqc6eh0](https://medium.com/@darrentsung/dont-re-invent-finite-state-machines-how-to-repurpose-unity-s-animator-7c6c421e5785#.c1sqc6eh0)


#### [Graphics debugging Unity games in Visual Studio](http://unity3d.com/learn/tutorials/topics/scripting/graphics-debugging-unity-games-visual-studio)

Posted on the Unity blog this week. This is the first I've heard of the Visual Studio Graphics Diagnistics (VSGD) tool in Visual Studio. For obvious reasons, only works with DirectX. Useful if you're on Windows.

[http://unity3d.com/learn/tutorials/topics/scripting/graphics-debugging-unity-games-visual-studio](http://unity3d.com/learn/tutorials/topics/scripting/graphics-debugging-unity-games-visual-studio)

### Code

#### [Coroutines in Unity – Encapsulating with Promises [Part 3]](http://blog.theknightsofunity.com/coroutines-unity-encapsulating-promises-part-3/)

Final part in the tutorial series on Coroutines and Promises from the Knights of Unity. This post covers how to use the promises from part 2 to write a REST service in Unity that communicates with a backend web API.

[http://blog.theknightsofunity.com/coroutines-unity-encapsulating-promises-part-3/](http://blog.theknightsofunity.com/coroutines-unity-encapsulating-promises-part-3/)

#### [Use Linear Algebra to solve problems in Unity with C#](http://www.habrador.com/tutorials/linear-algebra/)

Nice little series on using linear algebra to achieve common things in a Unity project. FTA:

>You will learn how to solve the following problems:
* How to figure out if an enemy is in front or behind you?
* If you are following a series of waypoints how do you know if you have passed a waypoint?
* If you are steering towards a waypoint, how do you determine if you should steer left or right?
* How can you find the coordinate where a ray intersects with a plane?
* How can you tell if two line segments in 2D space intersect with each other?

[http://www.habrador.com/tutorials/linear-algebra/](http://www.habrador.com/tutorials/linear-algebra/)


### Tools

#### [16 Bit Texture Dithering Algorithm](https://github.com/keijiro/unity-dither4444)

Another hidden gem from the Github repo of Based Keijiro. When using this, you're able to use 16-bit textures in your project with minimal degradation in fidelity. Especially suited to cartoon or anime asset styles. See the readme for visual examples.

[https://github.com/keijiro/unity-dither4444](https://github.com/keijiro/unity-dither4444)


### Graphics

#### [MaxPlay Rendering & Dynamic Lights Comparison ](https://www.youtube.com/watch?v=MlIUw4_h0fM)

Really interesting performance comparison between MaxPlay (the pure JavaScript/WebGL based engine that has an in-browser editor very similar to Unity's), Unreal Engine 4 and Unity.

MaxPlay comes out on top, but the real surprise for me was that Unity was 1.3x the performance of UE4 in this particular scenario.

[https://www.youtube.com/watch?v=MlIUw4_h0fM](https://www.youtube.com/watch?v=MlIUw4_h0fM)


#### [Rendering 7, Shadows, a Unity C# Tutorial](http://catlikecoding.com/unity/tutorials/rendering/part-7/)

Part seven in the Catlike Coding tutorial series on rendering is all about shadowing. It starts with an in-depth overview of the built-in shadowing system in Unity, and then goes on to implementing your own in the custom shader you have been building in the previous parts of the series. The tutorial is really comprehensive, with directional, spotlight and point light shadows covered.

[http://catlikecoding.com/unity/tutorials/rendering/part-7/](http://catlikecoding.com/unity/tutorials/rendering/part-7/)

### Assets

#### [Free low poly home appliances pack](https://www.reddit.com/r/gamedev/comments/4zfxbt/free_low_poly_home_appliances_pack/)

Nice little package of assets suitable for prototyping or sketching out ideas, courtesy of QuaterniusDev on Reddit. Post has a link to all their previous packages also.

[https://www.reddit.com/r/gamedev/comments/4zfxbt/free_low_poly_home_appliances_pack/](https://www.reddit.com/r/gamedev/comments/4zfxbt/free_low_poly_home_appliances_pack/)


### Videos

#### [Let's Learn Unity](https://www.reddit.com/r/Unity3D/comments/4zkdof/i_made_a_series_of_youtube_videos_on_learning/)

Reddit user Wuzseen has created a series of nine videos as a companion to a course on game development he is teaching at his local University. Looks to be a good beginner overview resource.

[https://www.reddit.com/r/Unity3D/comments/4zkdof/i_made_a_series_of_youtube_videos_on_learning/](https://www.reddit.com/r/Unity3D/comments/4zkdof/i_made_a_series_of_youtube_videos_on_learning/)


### Game Design

#### [Blade Runner 9732 In Unity](https://80.lv/articles/blade-runner-9732-in-unity/)

Quentin Lengelé discusses the work and processes that went into creating his phenomenal Deckard’s Apartment from Blade Runner VR experience. The lengths he went to modelling every single prop are truly impressive.

> I watched BR so many times, almost frame by frame, and I found a lot of items on Propsummit and other furnitures websites.

[https://80.lv/articles/blade-runner-9732-in-unity/](https://80.lv/articles/blade-runner-9732-in-unity/)


### Game Dev

#### [Alien Languages: How We Talk About Procedural Generation](http://www.gamasutra.com/blogs/MichaelCook/20160825/279938/Alien_Languages_How_We_Talk_About_Procedural_Generation.php)

Really nice opinion piece from Michael Cook writing for Gamasutra about the expectations when we hear the term 'procedural generation', and how in reality the end result doesn't always live up to the perception. In the context of the recent No Man's Sky release, and people's perhaps outlandish expectations for that game, this article is both timely and insightful.

[http://www.gamasutra.com/blogs/MichaelCook/20160825/279938/Alien_Languages_How_We_Talk_About_Procedural_Generation.php](http://www.gamasutra.com/blogs/MichaelCook/20160825/279938/Alien_Languages_How_We_Talk_About_Procedural_Generation.php)


### And Finally...

#### [Street Fighter 2 - Guile Theme Acapella](https://www.youtube.com/watch?v=4qwKCQ4M2Nw)

Talent.

[https://www.youtube.com/watch?v=4qwKCQ4M2Nw&feature=share](https://www.youtube.com/watch?v=4qwKCQ4M2Nw&feature=share)
