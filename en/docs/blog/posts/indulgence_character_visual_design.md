---
date: 2025-11-17
title: Indulgence Character Visual Design
authors:
- loomi
---
Character visual design is the part closest to players’ hearts in a game. When iterating on our characters, I decided to focus almost entirely on one foundational element: body proportions. Once proportions are set, they dictate everything that comes after—clothing, facial expressions, animation style, and even the overall art direction. <!--more-->

# Phase 1: Five-Head Realistic Proportions

We began with a relatively standard five-head body (head-to-body ratio common in semi-realistic games), with limb lengths close to real human anatomy.

Issues appeared immediately in the sketch stage: 
- Clothing and accessory details had to be extremely fine, otherwise they felt cluttered and small.
- Two-layer outfits (inner base clothing + outer functional gear) had almost no visual separation; the canvas was too cramped. 
The result was clean and understandable, but it lacked any memorable personality. It just felt… ordinary.

![](http://jing.games/assets/blog/devlog-2025-11-25/4_types.png)

# Phase 2: Extremely Elongated Limbs ("Comedy" Version)

![](http://jing.games/assets/blog/devlog-2025-11-25/thin_leg.png)

Next, I pushed the limbs to an extreme—very long and thin, with the torso remaining relatively normal. This instantly gave the characters a distinct comedic tone: 
- Large gestures became naturally humorous.
- Quick animation tests (walking, waving) turned out surprisingly charming and full of life.

![](http://jing.games/assets/blog/devlog-2025-11-25/complain.gif)

But the drawbacks were severe: 
- Clothing had to be drastically simplified, causing us to lose most of the cultural and functional storytelling we wanted to convey through outfits. 
- Adding armor, tools, pouches, or any hanging accessories became nearly impossible without breaking the silhouette. 
- It created hard limitations for future systems like equipment customization and class differentiation.

It was fun and cute, but it sacrificed too many things we actually needed. We had to let it go.

# Phase 3: The "Chonky Lego/Plushie" Proportion – Final Direction

![](http://jing.games/assets/blog/devlog-2025-11-25/lego_body.png)

After many rounds of trial and error, I turned to the proportions of Lego minifigures: short, thick limbs + a rounded, prominent belly, deliberately styled with a soft "ragdoll" or plush-toy texture.

This change solved almost everything: 
- The compact body provided plenty of surface area for clothing, gear, and accessories. 
- Layering became clear and readable: inner garments, outer armor, capes, belts, and tools all had room to breathe and be seen. 
- Most importantly, our four distinct cultural origins finally had space to express themselves without clashing: - Indigenous woven capes and patterns 
- Old-world leather coats from colonizer descendants - Corporate-issued protective suits and uniforms …all coexist cleanly on the same proportion system.

Initially the faces felt a bit too generic (leaning toward standard Western cartoon styles). To fix that, I referenced Romanesque frescoes and medieval manuscript illustrations: 
- Flattened, minimalist facial features.
- Almost all emotion conveyed through eye shape alone (wide open, narrowed, half-lidded, blank stare, etc.) This gave us expressive yet stylized faces that fit perfectly with the body proportions.

With this, the core visual language of our characters was finally locked in.

![](http://jing.games/assets/blog/devlog-2025-11-25/romansque.jpg)

# Production-Ready: Procedural Character Generation
At the same time we finalized the proportions, I built a generation pipeline: Biome → Cultural origin (one of four) → Role/archetype → Automatically assembles layered clothing, color palette, accessories, and modifications.

To test it, I recreated two Firefly characters last night: 

- Kaylee: Indigenous + colonizer mixed heritage → warm orange-red tones, lots of handmade modifications and patchwork 
- Wash: Former corporate employee → still wearing remnants of the standard shirt, now buried under a self-modified pilot jacket and loud Hawaiian shirts

Both read completely differently in personality, yet they feel like they belong to the same world. The system works.

![](http://jing.games/assets/blog/devlog-2025-11-25/keylee_and_wash.png)

# Current Final Direction

A plush-toy-like, Lego-minifig-inspired proportion that looks simple and approachable at first glance, but has enough canvas and structure to carry rich cultural details, deep clothing layering, and strong visual identity.

It’s cute without being childish.
It’s stylized without being limiting.
It’s finally ours.

That’s where we are now. More updates as we start animating and putting them into the world. Thanks for reading.