# Unity Dev Weekly
## Issue 11
*16 September 2016*

### News

#### [Unity 5.4.1 released](https://unity3d.com/unity/whats-new/unity-5.4.1)

The first bugfix release of Unity 5.4 is out with a swathe of fixes and some minor improvements around GPU instancing and VR support.

[https://unity3d.com/unity/whats-new/unity-5.4.1](https://unity3d.com/unity/whats-new/unity-5.4.1)

#### [Unity 5.4.1p1 patch release](https://unity3d.com/unity/qa/patch-releases)
Hot on the heels of 5.4.1, the latest patch release provides a load of other fixes and minor improvements. Most notably updating the Oculus SDK to version 1.8, and fixes for Xcode 8 and the newest iOS devices (iPhone 7 and 7 plus).

To quote Unity's patch page:

>We are listening to our users who are demanding that we fix more bugs, and faster, with our ongoing patch build releases. Each patch build is a full release of the editor with all runtimes and contains a number of bug fixes.

[https://unity3d.com/unity/qa/patch-releases](https://unity3d.com/unity/qa/patch-releases)

#### [Unity publishes standalone hardware stats](http://hwstats.unity3d.com/pc/gpu.html)
Useful stats that show the various GPU vendors, shader generations, GPU model, GPU series, and whether the system supports DX10+. Useful to know if you are starting a new project and want to strike the right balance between modern features, and compatibility for potential end users.

[http://hwstats.unity3d.com/pc/gpu.html](http://hwstats.unity3d.com/pc/gpu.html)


#### [A Look Inside: The Quest for Green Automation](https://blogs.unity3d.com/2016/09/08/a-look-inside-the-quest-for-green-automation/)

Interesting behind-the-scenes look at how Unity is now approaching automated testing of both the engine runtime and the editor.

>  In total we have about 60000 automated tests that are being executed tens of millions of times every month, both locally through manual runs and on our build farm.

[https://blogs.unity3d.com/2016/09/08/a-look-inside-the-quest-for-green-automation/](https://blogs.unity3d.com/2016/09/08/a-look-inside-the-quest-for-green-automation/)


### Virtual Reality

#### [How to Design VR Skyboxes](https://medium.com/aol-alpha/how-to-design-vr-skyboxes-d460e9eb5a75)

Great tutorial on the various methods for creating a sybox suitable for use in VR. Cylindrical, spherical and cube maps as well as rendered and realtime skyboxes (which are often useful for simulated weather effects and clouds).

[https://medium.com/aol-alpha/how-to-design-vr-skyboxes-d460e9eb5a75](https://medium.com/aol-alpha/how-to-design-vr-skyboxes-d460e9eb5a75)

#### [Develop Mobile VR w/ Oculus & Gear VR](https://medium.com/@vr_sam/develop-mobile-vr-w-oculus-gear-vr-8f1ce266e179)

Very detailed article on getting started with mobile VR development using Unity and GearVR. Covers both hardware and software setup, SDK integration in Unity, performance considerationg and general best practices all the way through to Oculus Store submission. Really comprehensive.

[https://medium.com/@vr_sam/develop-mobile-vr-w-oculus-gear-vr-8f1ce266e179](https://medium.com/@vr_sam/develop-mobile-vr-w-oculus-gear-vr-8f1ce266e179)



### Graphics

#### [Baking with Unity, 5 easy steps!](https://www.reddit.com/r/Unity3D/comments/52rh7z/tutorial_baking_with_unity_5_easy_steps/)

Animated Gif demonstrating how easy it is to bake lighting in Unity 5. Great if you haven't ever played with this before. [The top comment on Reddit by vertexnormal](https://www.reddit.com/r/Unity3D/comments/52rh7z/tutorial_baking_with_unity_5_easy_steps/d7mnuix) made me laugh:

> Step 4.5 wait 45 minutes while unity gets stuck on Light Transport stage.

The laugh of unconscious acknowlegement and agreement.

[https://www.reddit.com/r/Unity3D/comments/52rh7z/tutorial_baking_with_unity_5_easy_steps/](https://www.reddit.com/r/Unity3D/comments/52rh7z/tutorial_baking_with_unity_5_easy_steps/)

#### [Allegorithmic + Unity = ♥ - A substance Talk](https://www.youtube.com/watch?v=jPmXepihZlI)

> In this livestream we will discuss PBR, the advantages of substance designer and substance painter in production and the integration of sweet sweet materials directly in Unity.

If you're already familiar with PBR principles, the demo of Substance Designer [starts at 23:07 in the video](https://youtu.be/jPmXepihZlI?t=1387) and demonstrates how to incorporate it in your Unity asset workflow. As you'll see from the video, the procedurally generated materials you can create are nothing short of incredible.

The video [also demonstrates Substance Painter](https://youtu.be/jPmXepihZlI?t=2442), which is described as 'Photoshop for painting materials directly on models in 3d'. The video demonstraes how you paint the entire material texture stack in one go (colour, metalness, normals, roughness). You can really see the benefits of using this software, rather than creating all of the textures for an asset individually.

[https://www.youtube.com/watch?v=jPmXepihZlI](https://www.youtube.com/watch?v=jPmXepihZlI)


### Assets

#### [Example Project - Line Renderer & Trail Renderer](http://forum.unity3d.com/threads/example-project-line-renderer-trail-renderer.429781/)

An example project published by Unity as a way to preview their upcoming Line and Trail renderers. To use them you'll need to have the 5.5 beta installed. Nice to see early access to these things being made available for us to test and provide feedback on.

[http://forum.unity3d.com/threads/example-project-line-renderer-trail-renderer.429781/](http://forum.unity3d.com/threads/example-project-line-renderer-trail-renderer.429781/)


### Video

#### [Speed Level Design : Apocalyptic City](https://www.youtube.com/watch?v=tlix0Sb7LLQ)

Amazing video showing how to rapidly construct an environment out of pre-made assets. I particularly like the way the craters in the terrain are done, as well as the fake volumetric lighting effect. Youtube user Maverick makes level design look as easy as building Lego when we were kids. Well worth a watch.

[https://www.youtube.com/watch?v=tlix0Sb7LLQ](https://www.youtube.com/watch?v=tlix0Sb7LLQ)

#### [Getting Started With Steam VR](https://www.youtube.com/watch?v=kAu5gizURZ8)

Short summary video taking you through first steps integrating SteamVR into a Unity project. No coding required. The video demonstrates building a simple scene and deploying it in a way that can be consumed in VR. Ideal if you're looking to dip your toes into the VR waters.

[https://www.youtube.com/watch?v=kAu5gizURZ8](https://www.youtube.com/watch?v=kAu5gizURZ8)


### Game Dev

#### [Animation Bootcamp: An Indie Approach to Procedural Animation](http://www.gdcvault.com/play/1020583/Animation-Bootcamp-An-Indie-Approach)

Mind-blowing video from David Rosen speaking at GDC 2014 on procedural animation. The talk goes in depth on how to achieve realistic, and often hilarious, animations using a procedural approach, combined with constraint systems like ragdolls. For a studio or indie developer that doesn't have millions to spend on artists and animators, this kind of approach has the potential to deliver impressive results with limited resources. 

[http://www.gdcvault.com/play/1020583/Animation-Bootcamp-An-Indie-Approach](http://www.gdcvault.com/play/1020583/Animation-Bootcamp-An-Indie-Approach)


### And Finally...

#### [The Rise And Fall Of The Dreamcast](http://www.gamasutra.com/view/feature/132517/the_rise_and_fall_of_the_dreamcast.php)

The nostalgia. Shenmue - what an experience. Although the Dreamcast was an incredible system - both in terms of available games and technology (it was the first 3d console to used a tiled rendering GPU, which is now commonplace on mobile GPUs), it just wasn't enough to undo the damage to Sega's hardware business started all the way back when the doomed 32X and SegaCD were released.

[http://www.gamasutra.com/view/feature/132517/the_rise_and_fall_of_the_dreamcast.php](http://www.gamasutra.com/view/feature/132517/the_rise_and_fall_of_the_dreamcast.php)
