---
title: Concept Stage
description: Looking Into the Initial Ideas, Learning, and Testing
slug: concept-stage
weight: 2
---

I knew before I even chose my project what game engine I wanted to use:

![](/logo_vertical_color_dark.webp)

# Initial Ideas
I quickly had my basic idea down. As you saw in the introduction, I took inspiration from various games. Among these were Valorant and Team Fortress 2, and I basically wanted to copy the functionality of satchel jumping and rocket jumping that we see in both games.

You may be wondering, why would I need both of these when just one would do? Well, the main reason is that requiring the player to switch between 2 different methods of movement adds difficulty, which is part of the goal of this game. Also, they do both have their own use cases, which you will see more on in a later post.

As for my interaction ideas, they changed multiple times throughout the project, but near the end I settled on a simple system of picking up key pieces scattered across the scene and using the key to end the game. I will show more of this in the implementation section.

First though, I need to pick a game engine. Before this project started, I spent a lot of time learning Unity, a bit of time messing with Unreal Engine 4, and finally had a bit of experience with Godot. It had been about a year since I had touched any game development tools, but I remembered liking Godot due to how easy it was to learn, use, and get started with. 

# Use Godot
A quick advertisement for why you should consider Godot too:
- It's open source and has no fees or royalties
- It's super quick and easy to set up, you download a single zip file containing 2 executables. You just extract and run. It's that easy. ![Screenshot of the < 48MiB zip I Downloaded Straight From Godot's Website](/godot-zip-folder.png)
-- the zip file was less than 50 MiB, and contains the entire game engine including documentation, compilation tools, and a built-in marketplace where you can download extensions for the engine quickly and easily
- There's tons of documentation and tutorials available online
- Godot can compile for almost any platform, though compiling for consoles will give you some trouble, since Godot is open source and consoles are relatively closed off so including code for them in the engine isn't possible  
-- This isn't a problem for Quest headsets though, since they are Android based

# Learning
With that out of the way, I needed to actually learn how to use Godot, since I bascially forgot everything about it and it also had a major version upgrade from 3.x to 4.x since I had last used it. I decided that creating a physics based grabbing system would be a good way to learn, since I had some plans for a VR game I wanted to make after Rocket Jump, but chose not to use for this semester project since it was so far out of scope. This custom grabbing system caused far more trouble than it was worth, and I won't dig too deep into it until the implementation stage. 

# Testing
After a couple of months, I felt comfortable with Godot, and needed something to show for it. For our first presentation, I made a very simple scene with joystick-based movement and jumping. This scene outlined some of my basic plans, and allowed me to test if I felt any motion sickness from the rapid and jumpy movement. 

![Note - was not actually this laggy in VR](/rocket-jump.gif)


