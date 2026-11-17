---
tags: 
  - GameDev
  - Godot 
  - Game Engine
  - Unity
  - MonoGame
  - Unreal Engine
title: Starting My Game Dev Journey
date: 17.11.2026
---

In game development, you have to be creative. You have to come up with ideas for game mechanics, graphics, and storylines. You also have to be able to think critically about your own work, and make decisions about what works and what doesn’t. These skills are transferable to any creative field, from writing to art to music.  
But game development also teaches you about building your own product. You have to take an idea and turn it into something tangible, something that people can interact with and enjoy. This involves learning about programming, graphic design, and project management. It’s not always easy, but it’s incredibly rewarding to see your vision come to life.

Indie game development is a great way for engineers to express their creativity and make something unique. It’s a process that requires a lot of hard work, dedication, and passion.
### Game as a software

When starting your game dev journey, it’s easy to focus entirely on the 'game' aspect—the art, the story, and the fun mechanics. However, it is vital to remember that a game is, at its core, complex software. To prevent your project from collapsing under its own weight as it grows, you should prioritize standard software engineering principles:

- Maintainability: Write clean, readable code so that your future self can debug and update the game without starting from scratch.
- Scalability: Build systems designed to grow. Your architecture should handle new levels or features without breaking existing ones.
- Reusability: Create modular components (like a universal inventory system or character controller) that can be reused across different parts of your game—or even in future projects.

Treating your game like high-quality software from day one creates a stable foundation, allowing your creativity to flourish without being hindered by technical debt.
### What tools to use?

I had some experience with the libGDX and MonoGame frameworks many years ago. Using libGDX, we even released a game on Android.

Back then, we had far fewer options; however, indie game development has become more accessible than ever before due to advancements in technology and the rise of affordable game engines. Today, there are tons of [tools and engines](https://en.wikipedia.org/wiki/List_of_game_engines) to choose from, and the choice depends on our needs and preferences.

Thinking about building my own game raises questions like:
On what platforms will my game run? What is the price of the software I am going to use? Can it change in the future? What programming language would I like to use? Do I want to use a full-featured game engine or a low-level framework and do things myself? Are there any technical restrictions with the tools I am going to use?

It seems impossible to find software that combines all the benefits with no downsides, so there is always a trade-off to consider.
### So why don't you just use AI and "vibecode" things?

Your goal determines which tool you should use. If your goal is to get a quick result without diving deep into the "boring stuff," AI is a great tool, and I think it should be used in certain cases. However, if the goal is to learn how to build things and learn how to overcome obstacles along the path of indie game dev, AI won't provide that. While AI can give you a result, it takes away the joy of the creation process.

Personally, I believe it is better to spend time learning new skills rather than spending that same amount of time iterating on AI prompts over and over to get it to work as intended. This approach might not be as "efficient" in terms of speed, but it offers more freedom because you don't have to worry about subscriptions or token limits to create something.

Creating things with your own skills, ideas, and imagination makes it possible to truly say, "I made this." After all, we still value "hand-crafted" clothes, books, furniture, and pottery today.
### So, what is my choice then?

I decided to start with a simpler approach: define the parameters that are important to me right now to filter out options, and then take a closer look at what remains. My preferences are:

1. I want something "ready-made." The engine should have a content pipeline, along with an editor or IDE featuring a comprehensive UI (e.g., dragging and dropping objects, easy resource importing, no terminal commands, and no manual resource manipulation).
2. I want full control over my projects. No mandatory accounts, cloud-only services, or access limits.
3. I want my games to run on desktop, mobile, and the web. The web is highly preferred because it can be launched without the complex release processes required by app stores.
4. I prefer a free version if possible - one that is robust enough to do the job so that I won't have to worry about commercial usage restrictions, royalties, or licensing issues in the future.

After researching available options, I was able to shortlist and filter them based on my criteria. Below is a table of full-featured game engines I believe are worth checking out:


| Title         | Link                          | Notes                                                                                                |
| ------------- | ----------------------------- | ---------------------------------------------------------------------------------------------------- |
| Unity         | https://unity.com/            | - ❌ Huge download size<br>- ❌ Requires account, licensing<br>- ✅ Industry standard<br>- ✅ C# Support |
| Unreal Engine | https://www.unrealengine.com/ | - ❌ Requires account and licensing<br>- ❌ Royalties<br>- ✅ Industry standard                         |
| Godot         | https://godotengine.org/      | - ✅❌ Web export support *<br>- ❌ Security issues<br>- ✅ Free and open source<br>- ✅ C# Support        |
| Stride Engine | https://www.stride3d.net/     | - ❌ Windows IDE only<br> - ❌ No web export                                                                  |
| Prowl         | https://prowl.dev/            | - ❌ Desktop only targets                                                                             |
| Construct 3   | https://www.construct.net/    | - ❌ Paid (free version is limited)                                                                   |
| LittleKt      | https://littlekt.com/         | - ❌ No visual editor, no IDE<br>- ❌ No iOS support yet<br>- ✅ Kotlin<br>- ✅ Free and open source     |

\**Note: The Godot 3.6 C# version can export web games; however, more recent versions supporting C# cannot (only GDScript). Therefore, we can say it has "some" web support.*

#### Worth checking out

- PixiJS ([https://pixijs.com/](https://pixijs.com/))
- Phaser ([https://phaser.io/](https://phaser.io/))
- MonoGame ([https://monogame.net/](https://monogame.net/))
- Raylib ([https://www.raylib.com/](https://www.raylib.com/))

I would definitely try LittleKt because it draws inspiration from libGDX, which I have worked with before, and it uses Kotlin - my primary programming language. To me, it looks very promising.

I’ve decided to go with Godot for now; it seems like a good fit for my needs. Lets see what I can do with it and what it is like to use it.

### Why blogging about it?

When I research specific aspects of game development - such as how to build a certain mechanic - I often find tutorials that "do the job." However, their implementations often leave me with questions, or it becomes clear that there are far better solutions for the problem at hand. Most tutorials are too brief, they lack deep explanations and only cover small parts of the dev process, such as how to use tilemaps, how to add shaders, or how to implement character controls for a platformer. It is much harder to find a good example of building a more-or-less complete game - a complex product with fully implemented features.

I decided to start blogging about my experience with gamedev to stay motivated, structure my work, and turn my research into tangible content like playable demos, blog posts, or notes.

In my blog, I will cover various aspects of game development, including design, programming, and graphics. I will also share my experiences with different game engines, my progress in building projects, and the specific challenges I find worth sharing.

### What's next?

I am going to start with a basic Godot game or a mechanic demo - something I can build in a day or two. This will provide a starting point for me to learn more about the engine and its workflow. My first goal is to identify which challenges I should be able to solve to develop my own full game using Godot.

### Links

🗒️ [A game developer compared Godot and Unity by making the same game in both engines, and he's found a clear winner](https://www.pcgamer.com/gaming-industry/game-development/a-game-developer-compared-godot-and-unity-by-making-the-same-game-in-both-engines-and-hes-found-a-clear-winner/)  
[Stride For Unity Developers](https://www.youtube.com/watch?v=u_ksFlHHXYU&t=9s)
