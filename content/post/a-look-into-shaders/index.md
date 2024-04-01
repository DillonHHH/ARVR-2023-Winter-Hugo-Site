---
title: A Look Into Shaders
description: Learning Shaders for Our Second Presentation
slug: a-look-into-shaders
weight: 3
---

As part of the class, we all chose a specific subject to learn about and create a presentation to teach other classmates in a reverse classroom. Out of the list of options we were given, I chose shaders. And so did Luis...

Me and Luis didn't know each other much at all, but the only two people in the class using Godot also happened to want to do shaders. Luckily shaders are a complex topic, so after talking to the professor we were able to split it into two parts with each of us getting our own sub-topics. 

I won't get too deep into this, since I didn't end up using shaders in my project, but here is the final result:

vertex shader:
- {{< video "/vertex-example.mp4" >}}
[click me if video doesn't play](/vertex-example.mp4)

post processing vignette shader:
- {{< video "/post-processing.mp4" >}}
[click me if video doesn't play](/post-processing.mp4)

The vignette shader didn't actually work out as intended, which is why I didn't include it in the final project. It looks good in the video, but after trying it out again I noticed it looked strange. The shader was being applied to both of my eyes, but it was as if they were a single screen, which is basically what was happening. I couldn't figure out how to apply a seperate vignette to each eye, so I scrapped the idea.

[You can download the presentation here for shader code and a couple more shader examples](/Presentation2.pptx)