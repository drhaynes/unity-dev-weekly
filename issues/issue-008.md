# Unity Dev Weekly

## Issue 8
*26th August 2016*

### News

Fairly quiet on official news this week. Everyone is clearly busy playing No Man's Sky rather than doing actual work.


### Unity Tips

#### [Attaching your project to a bug report  –  Unity Blog](https://blogs.unity3d.com/2016/08/24/attaching-your-project-to-a-bug-report/)

When faced with a bug, a report to Unity that contains a reproducible test case in an example scene helps the team reproduce your issue. This covers best practices on doing that efficiently. Another step forwards for quality.

#### [https://blogs.unity3d.com/2016/08/24/attaching-your-project-to-a-bug-report/](https://blogs.unity3d.com/2016/08/24/attaching-your-project-to-a-bug-report/)


### Tools

#### [GitHub Extension for Visual Studio 2.0 is now available](https://github.com/blog/2232-github-extension-for-visual-studio-2-0)

> This release allows you to list your existing pull requests and create new ones directly from Visual Studio. You can also create gists directly from your code, making it even easier to share your code and collaborate

Useful.

#### [https://github.com/blog/2232-github-extension-for-visual-studio-2-0](https://github.com/blog/2232-github-extension-for-visual-studio-2-0)


#### [Forked Newtonsoft.Json to support Unity3D](https://github.com/SaladLab/Json.Net.Unity3D)

Fork of the best performing C# json serialisation/deserialisation library to provide Unity support. There are paid assets out there on the Asset Store, but you can grab this one from GitHub, courtesy of SaladLab. Note - requires IL2CPP scripting backend for AOT targets, due to its use of generics.

#### [https://github.com/SaladLab/Json.Net.Unity3D](https://github.com/SaladLab/Json.Net.Unity3D)


#### [Procedural Cave Generator](https://github.com/AK-Saigyouji/Procedural-Cave-Generator)

With No Man's Sky doing the rounds, procedural generation is a hot topic at the moment. Here's a really cool cave generator by Reddit user Saigyouji.

> Generate randomized caves usable from either a top-down perspective (with CaveGeneratorIsometric) or completely enclosed caves from a first-person perspective (CaveGeneratorEnclosed).

#### [https://github.com/AK-Saigyouji/Procedural-Cave-Generator](https://github.com/AK-Saigyouji/Procedural-Cave-Generator)


#### [Numberflow - Procedural Texture Editor for Unity](http://catlikecoding.com/numberflow/)

Really powerful node-based procedural texture creator from the folk at Catlike Coding. Free for non-commercial use, and very reasonably priced if you need to use for commercial work.

#### [http://catlikecoding.com/numberflow/](http://catlikecoding.com/numberflow/)


### Assets

#### [Free Asset Pack: Space Shooter Redux](http://kenney.nl/assets/space-shooter-extension)

More great stuff from kenney.nl, this time a bunch of 2d space assets for prototyping or trying out gameplay ideas. Building an asteroids clone or shmup? This could be useful as a starting point.

#### [http://kenney.nl/assets/space-shooter-extension](http://kenney.nl/assets/space-shooter-extension)


### Code

#### [Coroutines in Unity - Encapsulating with Promises Part 1](http://blog.theknightsofunity.com/coroutines-unity-encapsulating-promises-part-1/)

From the Knights of Unity blog, first of a two part in-depth series on coroutines, their limitations, and potential solutions. Part 1 goes into detail on how coroutines are implemented in the Unity runtime, and discusses their limitations when you want to return a value or handle exceptions. [Part 2](http://blog.theknightsofunity.com/coroutines-in-unity-encapsulating-with-promises-part-2/) then presents a solution to these issues, in the form of promises.

#### [http://blog.theknightsofunity.com/coroutines-unity-encapsulating-promises-part-1/](http://blog.theknightsofunity.com/coroutines-unity-encapsulating-promises-part-1/)


#### [Redirect Console.Write to Unity’s Console](http://jacksondunstan.com/articles/2986)

Great tip with example code. Any time you `Console.Write()`, redirect it to Unity's console. Very useful if you are writing C# code that you want to remain decoupled from Unity, so can't use `Debug.Log` during development.

#### [http://jacksondunstan.com/articles/2986](http://jacksondunstan.com/articles/2986)


### Graphics

#### [Unity 5.5 graphics changes and improvements](https://docs.google.com/document/d/1tQAhzp-WOo710DWDHWf94yFUPRjVaCYkemxtCPDaAUs/edit?pref=2&pli=1)

Official document on Google Drive from Unity outlining the major graphics changes coming in Unity 5.5. The improved shadows for large environments looks incredible, only downside is it will be supported only on DX11/12, PS4 and Metal platforms.

#### [https://docs.google.com/document/d/1tQAhzp-WOo710DWDHWf94yFUPRjVaCYkemxtCPDaAUs/edit?pref=2&pli=1](https://docs.google.com/document/d/1tQAhzp-WOo710DWDHWf94yFUPRjVaCYkemxtCPDaAUs/edit?pref=2&pli=1)


### Game Development

#### [How to successfully manage your game on Early Access](http://www.gamasutra.com/blogs/JoshGe/20160816/279339/The_Alpha_Release_Cycle_Running_a_Successful_EA_Program.php)

As the saying goes, "Any fool can learn from their own mistakes, the wise man learns from the mistakes of others." A really great article on Gamasutra journaling the specific details that go into a successful early access program for your game. A must read for anyone planning a release in the near future.

#### [http://www.gamasutra.com/blogs/JoshGe/20160816/279339/The_Alpha_Release_Cycle_Running_a_Successful_EA_Program.php](http://www.gamasutra.com/blogs/JoshGe/20160816/279339/The_Alpha_Release_Cycle_Running_a_Successful_EA_Program.php)



### Videos

#### [Shaders Case Study - No Man's Sky: Topographic Scanner](https://www.youtube.com/watch?v=OKoNp2RqE9A)

Breakdown and reconstruction in Unity of the effect from No Man's Sky where the glowing scanner radiates out from your location across the terrain.

#### [https://www.youtube.com/watch?v=OKoNp2RqE9A](https://www.youtube.com/watch?v=OKoNp2RqE9A)


### And Finally...

#### [I used to love demo discs on the Playstation, so I decided to make one for some of my games.](https://www.reddit.com/r/Unity3D/comments/4ymo4d/i_used_to_love_demo_discs_on_the_playstation_so_i/)

Such a great idea. Would love to see this catch on and become a regular thing.

#### [https://www.reddit.com/r/Unity3D/comments/4ymo4d/i_used_to_love_demo_discs_on_the_playstation_so_i/](https://www.reddit.com/r/Unity3D/comments/4ymo4d/i_used_to_love_demo_discs_on_the_playstation_so_i/)

