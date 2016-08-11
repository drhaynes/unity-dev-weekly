# Unity Dev Weekly

## Issue 6
*11th August 2016*

### News

#### [MadeWithUnity Submissions Now Open for Unite '16 LA](http://madewith.unity.com/event/made-with-unity-showcase)

If you've got a recently finished project that you want to show off then it might be worth submitting.

> Unite 16 in Los Angeles is this year’s most important gathering of artists, developers, publishers, training providers and enthusiasts interested in Unity.  The Made with Unity Showcase is a place to display projects of all sizes, platforms, and styles to industry peers, professionals and journalists.

It's free to apply, and if successful you'll get free Unite tickets, and more exposure and promotion than you can shake a stick at.

[http://madewith.unity.com/event/made-with-unity-showcase](http://madewith.unity.com/event/made-with-unity-showcase)

### Unity Tips

#### [Timesteps and Achieving Smooth Motion in Unity](http://www.kinematicsoup.com/news/2016/8/9/rrypp5tkubynjwxhxjzd42s3o034o8)
If you've ever seen stuttering motion in your scenes (everyone then...) this is the post for you. Should you use `Update()` or `FixedUpdate()`? Follow this method and wave goodbye to jerky motion forever.
[http://www.kinematicsoup.com/news/2016/8/9/rrypp5tkubynjwxhxjzd42s3o034o8](http://www.kinematicsoup.com/news/2016/8/9/rrypp5tkubynjwxhxjzd42s3o034o8)

### Code

#### [Real-Time Image Capture in Unity — Google Developers](https://medium.com/google-developers/real-time-image-capture-in-unity-458de1364a4c#.qnalhs15d)

In-depth post from the dev team at Google behind TiltBrush, going into detail on how they managed to get realtime video capture and still hit the solid 90fps required for VR.

[https://medium.com/google-developers/real-time-image-capture-in-unity-458de1364a4c#.qnalhs15d](https://medium.com/google-developers/real-time-image-capture-in-unity-458de1364a4c#.qnalhs15d)

#### [Unity Builds Scripting: Basic and advanced possibilities](http://www.gamasutra.com/blogs/EnriqueJGil/20160808/278440/Unity_Builds_Scripting_Basic_and_advanced_possibilities.php)

An English translation of two posts previously in Spanish on the blog MareaIndie, this article  goes into how to script your builds in Unity. Do away with the multi-step manual process and replace it with a single method, that can be invoked from the editor menu. Also contains a great tip on executing from your CI system such as Jenkins or Travis, that looks a little something like this:

`$ unity -quit -batchmode -executeMethod BuildAllMyAwesomeStuff`

[http://www.gamasutra.com/blogs/EnriqueJGil/20160808/278440/Unity_Builds_Scripting_Basic_and_advanced_possibilities.php](http://www.gamasutra.com/blogs/EnriqueJGil/20160808/278440/Unity_Builds_Scripting_Basic_and_advanced_possibilities.php)

### Tools

#### [Using Landscape Auto Material with Unity](http://80.lv/articles/using-landscape-auto-material-with-unity/)

Port of the phenomenal UE4 tool to Unity. Check out the incredible AAA quality terrains that can be created with this. Some early 1.0 niggles but along with the like of GAIA and Relief Terrain Pack, it looks like this plugin has what it takes to be one of the go-to solutions for serious high-end terrain creation in Unity.

[http://80.lv/articles/using-landscape-auto-material-with-unity/](http://80.lv/articles/using-landscape-auto-material-with-unity/)

#### [PlayCanvas versus Unity WebGL](http://blog.playcanvas.com/playcanvas-versus-unity-webgl/)

Fairly damning performance comparison between Unity WebGL and the pure JavaScript WebGL based PlayCanvas. The benchmark is a simple 'textured cube' hello world 3d app. Key points:

* The Unity app is over 21 times larger than the PlayCanvas app.
* The PlayCanvas app’s load times are up to 43 times faster than the Unity app.
* PlayCanvas frame rates are up to 4 times greater than Unity

Seems the C# -> IL2CPP -> Emscripten -> .js / WebGL pipeline really hurts Unity, with Safari on iOS particularly badly hit.

WebGL support is still in early stages for Unity, and they certainly have a lot of work to do to make that a compelling target platform. Perhaps a stripped-down pure JavaScript runtime is a viable option?

[http://blog.playcanvas.com/playcanvas-versus-unity-webgl/](http://blog.playcanvas.com/playcanvas-versus-unity-webgl/)

### Assets

#### [Many sprites and tiles for RTS (city building) games](https://www.reddit.com/r/gamedev/comments/4x2dt3/many_sprites_and_tiles_for_rts_city_building/)

Posted on reddit /r/gamedev. CC0, public domain assets ideal for sketching out a RTS prototype.

[https://www.reddit.com/r/gamedev/comments/4x2dt3/many_sprites_and_tiles_for_rts_city_building/](https://www.reddit.com/r/gamedev/comments/4x2dt3/many_sprites_and_tiles_for_rts_city_building/)

### Graphics

#### [Circle projector shader](https://www.reddit.com/r/Unity3D/comments/4x229i/i_made_a_circle_projector_shader_now_i_have_no/)

Another gem from reddit, this time from the /r/Unity3d subreddit. If you've ever needed a perfect circle then you soon realise that getting it pixel perfect is rather challenging, and the larger the circle, the larger the texture you'll need (doing it naively). Circle projector shader to the rescue. Great results and a much smaller texture required.

[https://www.reddit.com/r/Unity3D/comments/4x229i/i_made_a_circle_projector_shader_now_i_have_no/](https://www.reddit.com/r/Unity3D/comments/4x229i/i_made_a_circle_projector_shader_now_i_have_no/)

### Video

#### [Unite Europe 2016 - Gearboxes and Gas Pedals - Vehicle Physics in Unity](https://youtu.be/RWPFGw9xyAI)

Useful video from the recent Unite Europe 2016 event convering some of the new vehicle physics features in Unity 5.

[https://youtu.be/RWPFGw9xyAI](https://youtu.be/RWPFGw9xyAI)


#### [Let's Try Shooting via RayCasts](http://unity3d.com/learn/tutorials/lets-try/shooting-with-raycasts)

There are essentially three ways to implement a shooting mechanism in Unity - 1.) Use the built in physics engine and spawn a projectile with a large forward velocity at the site of your muzzle; 2.) Raycast in the direction the muzzle is facing at the moment of the shot being taken, or 3.) Implement your own ballistics physics solver.

While option 3 is certainly fun for any physics geek (like yours truly), unless you are doing military-grade accurate ballistic simulation it is almost certainly overkill. Raycasting provides a happy medium, giving great results for the vast majority of cases. And to that end, this official Unity video tutorial has you covered:

[http://unity3d.com/learn/tutorials/lets-try/shooting-with-raycasts](http://unity3d.com/learn/tutorials/lets-try/shooting-with-raycasts)

