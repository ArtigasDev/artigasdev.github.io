---
name: "ANDARA: Rise for Rebellion"
tools: [C++, UE4, Steam]
image: https://i.imgur.com/qgHhG25.gif
description: A Third Person Shooter made with UE4 already released on Steam.
---

{% include elements/video.html id="TCOyx2F5KVM" %}
(Videogame Trailer)

***ANDARA: Rise for Rebellion*** is a third person shooter based on games like "Rachet & Clank" and "Returnal", with mechanics that bring speed to the gameplay similar to shooters like "Doom".

Available for free download on [Steam](https://store.steampowered.com/app/2432470/ANDARA_RISE_FOR_REBELLION/).

# Work Methodology
A multidisciplinary team of 7 programmers, 6 artists, and 3 game designers are working on the development. The progress of the game can be followed on [@AndaraGame](https://twitter.com/AndaraGame).

Our project aims to simulate the work of a video games studio closely. We have set deadlines and milestones, such as the prototype and the first playable version. Our approach is based on the scrum methodology, with weekly sprints that start and end with meetings to review the progress of each department and assess our achievements.

Effective communication is essential for the success any project. We emphasize communication within and between teams. It is vital to keep in constant contact with our fellow designers and artists to ensure the healthy development of the game and improve iteration.

# Story
The game tells the story of Andara, the heir to the throne of an interplanetary alien race led by her father, Ordon. In her attempt to colonise other planets in search of resources, she discovers her father's tyranny first hand, as he is willing to do anything to achieve his goal, including killing Andara's best friend. Andara then begins a revolt to stop her father's tyrannical invasion and save the planet Hailstone.

# What I did
- AI of Special Laser enemy
  - Behavior tree (EQS, BBComp, New BTTasks...).
  - Animations management (NotifyStates, BlendSpaces, StateMachine...).
  - AIController (AI Perception, Set/RemoveFocus...).
- Part of the AI of Putty enemies and Special Shooter enemy.
- Spawner actor used for wave management and state of aggressiveness of enemies in battle arenas.
- Gameplay hazards such as Laser Columns and Damaging platforms.
- Particles implementation in some of the enemy actions, and their corresponding optimisation.
- Usage of Object Pooling for better performance.<br><br>

# How it was implemented
You can see part of the development process of the project in this youtube documentary:
{% include elements/video.html id="W4hbSShLBCk" %}
(Making of documentary)
<br><br>

### Developed by:
- [Chivito Games](https://twitter.com/AndaraGame)

**<br>The repository for this project is not publicly accessible but code snippets may be shared with those who are interested in its implementation. Get in touch with me for futher details.**


<p class="text-center">
{% include elements/button.html link="https://artigasdev.github.io/projects/" text="Back" %}
</p>