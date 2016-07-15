# Unity Dev Weekly
## Issue 2
*July 15th 2016*

### News

#### [Unity raises $181M monster round at a reported $1.5B valuation](https://techcrunch.com/2016/07/13/unity-announces-181-million-monster-round-led-by-dfj-growth/)

Great to see some big cash being injected into Unity. In terms of what this means for the future of Unity, I think we'll see more features added quicker (like an immersive VR editor mode). They might even hire some devs to work on the Terrain system - we can all dream!

[https://techcrunch.com/2016/07/13/unity-announces-181-million-monster-round-led-by-dfj-growth/](https://techcrunch.com/2016/07/13/unity-announces-181-million-monster-round-led-by-dfj-growth/)

#### [New Unity Forum launch rolled back](https://community.unity.com/t5/Welcome/Forum-Rollback-Save-your-data/td-p/2650974)

Unity released a new forum platform at the start of the week, and it soon became clear that all was not well. Major features like messaging were missing from the new system, and the amount of feedback from the community eventually resulted in the decision to roll back to the previous version of the forums and 'put the bun back in the oven'.

While it's great to see Unity making an effort to resolve some of the issues of the now ancient forums, this is an object lesson in how not to roll out a new application. Even a small amount of alpha testing would have uncovered the gaping holes in functionality in the new system. In fairness, Unity have been very humble and open about the whole affair, so let's hope it's a case of 'lesson learned' and next time will be better.

[https://community.unity.com/t5/Welcome/Forum-Rollback-Save-your-data/td-p/2650974](https://community.unity.com/t5/Welcome/Forum-Rollback-Save-your-data/td-p/2650974)

### Unity Tips

#### [Awesome Unity](https://github.com/RyanNielson/awesome-unity)

Awesome Unity is 'A categorized community-driven collection of high-quality awesome Unity assets, projects, and resources.' curated by a community of contributors and hosted on Github. The links are split into sections for easy navigation. Something for everyone here. I particularly like the [Editor Tips](http://imgur.com/a/2w7zd) in animated gif form.

[https://github.com/RyanNielson/awesome-unity](https://github.com/RyanNielson/awesome-unity)

### Code

#### [Getting Started with C#](https://www.microsoft.com/net/tutorials/csh)

Good intro to C# from Microsoft tailored to your previous experience (or lack of) in programming. Allows you to select which language you have previous developed with (C++, JavaScript, etc.) and tailors the tutorials accordingly.

[https://www.microsoft.com/net/tutorials/csh](https://www.microsoft.com/net/tutorials/csh)

#### [Galaxia: The Basics - Coordinates](https://dexyfex.com/2016/07/11/galaxia-the-basics-coordinates/)

Great article on the limits of using floating point numbers in huge environments (in Galaxia's case spanning multiple galaxies) and how to overcome them. The proposed solution of using nested coordinate systems of 64-bit integers combined with a scaling factor is a very nice solution to the problem.

[https://dexyfex.com/2016/07/11/galaxia-the-basics-coordinates/](https://dexyfex.com/2016/07/11/galaxia-the-basics-coordinates/)

### Graphics

#### [ShaderCat - How to Explore Unity 5's Shader System](http://www.shadercat.com/how-to-explore-unity-5s-shader-system-code-i-overview/)

Start of a great looking series on exploring the lower-levels of Unity's physicall based rendering shader code. The first part gives a broad overview of the various sections and lays out what future posts will cover. Look out for links to subsequent parts in future editions of Unity Dev Weekly.

[http://www.shadercat.com/how-to-explore-unity-5s-shader-system-code-i-overview/](http://www.shadercat.com/how-to-explore-unity-5s-shader-system-code-i-overview/)

#### [Volumetric Rendering: Raymarching](http://www.alanzucconi.com/2016/07/01/raymarching/)

Part two in Alan Zucconi's series on volumetric rendering in Unity. This part covers distance aided raymarching, which is the de-facto optimisation used to cut down the number of steps required when raymarching. As usual with Alan, some great diagrams explain the concept clearly.

[http://www.alanzucconi.com/2016/07/01/raymarching/](http://www.alanzucconi.com/2016/07/01/raymarching/)

### Video

#### [Unite Europe 2016 - Overthrowing the MonoBehaviour tyranny in a glorious ScriptableObject revolution](https://www.youtube.com/watch?v=VBA1QCoEAX4)

Great video on the criminally neglected `ScriptableObject` class, and its uses. `MonoBehaviour`s aren't always a good conceptual fit for some of the things you need to do in Unity.

`ScriptableObject` is like a `MonoBehaviour` but not attached to a GameObject. They are stored in assets and so persist when exiting playmode, and can be referenced from any scene. They also work better with version control. They have fewer callbacks (no Update(), Start(), etc). Useful for storing pure data objects and having pluggable behaviour that can be tweaked and saved at runtime.

The demo in the second half of the video demonstrates some of the really powerful usage patterns. From using it as a simple data storage object for level data, all the way to composable behaviours that are tweakable at runtime.

[https://www.youtube.com/watch?v=VBA1QCoEAX4](https://www.youtube.com/watch?v=VBA1QCoEAX4)

#### [Prototyping in Unity video series](https://www.youtube.com/watch?v=gC0N6ETulv0&list=PL2cNFQAw_ndyKRiobQ2WqVBBBSbAYBobf)

One of Unity's biggest strengths is being a force multiplier when it comes to rapidly prototyping your next big game idea. This 34 part video series takes you through the process of prototyping a 2d side-scrolling game. From parallax scrolling, prefab creation and character animation all the way through to enemy AI, sound and GUIs the series touches most corners of Unity. Well worth a watch.

[https://www.youtube.com/watch?v=gC0N6ETulv0&list=PL2cNFQAw_ndyKRiobQ2WqVBBBSbAYBobf](https://www.youtube.com/watch?v=gC0N6ETulv0&list=PL2cNFQAw_ndyKRiobQ2WqVBBBSbAYBobf)

### Game Design

#### [Sean Edward's Lunar Flight VR Remaster beta Released on Steam](https://m.reddit.com/r/oculus/comments/4s5iod/lunar_flight_vr_remaster_cv1_beta_available_on/)

The original Lunar Flight was one of the first games released for the Oculus Rift, way back in the DK1 days. Great to see this updated and essentially redone from the ground-up for modern VR.

[https://m.reddit.com/r/oculus/comments/4s5iod/lunar_flight_vr_remaster_cv1_beta_available_on/](https://m.reddit.com/r/oculus/comments/4s5iod/lunar_flight_vr_remaster_cv1_beta_available_on/)

#### [How to Choose What Colors to Use in Your Game](https://www.reddit.com/r/gamedev/comments/4s4u7c/how_to_choose_what_colors_to_use_in_your_game/)

Reddit discussion on how to choose a well balanced colour pallette for your game. If you're a coder or game designer and not an artist, it may be a surprise to learn that effective looking colour swatches can be calculated automatically. The thread has links to some useful tools that can do this for you. It's amazing how a good colour pallette can take an otherwise average design and push it into the 'good' zone. Really useful whether you're a seasoned artist or a one-person indie dev.

[https://www.reddit.com/r/gamedev/comments/4s4u7c/how_to_choose_what_colors_to_use_in_your_game/](https://www.reddit.com/r/gamedev/comments/4s4u7c/how_to_choose_what_colors_to_use_in_your_game/)

### And Finally...

#### [Sega Saturn CD - Cracked after 20 years](https://www.youtube.com/watch?v=jOyfZex7B3E)

Inspirational story of hardware hacking and just not giving up in the face of setback after setback. Underdog of the 90s, the Sega Saturn has a special place in my heart. Many of my teenage years were spent playing Virtua Fighter 2 and Guardian Heroes. It's great to know that these devices will be able to play games long after the last CD drive gives up the ghost.

[https://www.youtube.com/watch?v=jOyfZex7B3E](https://www.youtube.com/watch?v=jOyfZex7B3E)
