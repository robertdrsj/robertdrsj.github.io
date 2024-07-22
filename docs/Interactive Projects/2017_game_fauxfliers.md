# Faux Fliers (2017)
**Pitch**: A multiplayer party game where you fix your plane as you fly it.

- **Objective**: In a movie film about flying a plane, a pilot can assess a chaotic situation and quickly flip switches-- all while the airplane is about to crash. Create a game that mimics a similar experience, but in a collaborative multiplayer setting.
- **Target Audience**: A gamer who likes rowdy multiplayer games. They want to have friendly competition with friends, but not ruin relationships in the process. They also want to share collectibles with others who can't afford to.

## Contribution
This project aimed to improve my development skills after Partial's production. I designed the user interface, wrote the code for UI usage and flight physics, and created the 3D models of the airplane and game environment.

*Tools: Unity 2017, MS Visual Studio Community, C#, Git/Github, Autodesk Maya*

## Production
### Design and Marketing Strategy
I overhauled the 2D prototype design from a game jam/hackathon for a robust breakage system and adapted into a 3D setting. Since the prototype could be easily cheated, the new breakage system allows the player to focus more on airplane parts and flight maneuvers. I also designed new vehicle types like a sailboat and ferris wheel, and added mini-games that are played in rounds (like Mario Party). I made these design decisions as a response to my target players: a family-friendly audience on the Nintendo Switch Free-To-Start platform. By releasing the game on a F2S platform, competition would be minimal and I could design a more accessible product.

### Aesthetic Strategy
I chose to use colorful 3D models in place of a four-color GameBoy pixel art style to establish a brighter atmosphere while also practicing my 3D modeling ability. Since players didn't notice the visual and audio cues in the prototype when the engine broke, I designed the UI to be more animated in order to get the player's attention. I started with UI concept sketches that would use an interactive dashboard instead of a non-interactive interface. I chose the low-poly route where each airplane and dashboard part were individually modeled; designing them as components would allow breakage to be easily implemented and manipulated. Since I was using Unity 2017.3, shaders were still a bit unwieldy so I used the Toony Colors Pro 2 asset pack as a temporary solution. I designed the environment by modeling toy blocks to promote the color palette, while also ensuring that designing the prototype level would be simpler by mass-replicating the blocks.

### Gameplay Implementation
I assessed how to revise the control input from 2D to 3D by using sketches to visualize input and airplane flight direction. To improve UI readability, I reviewed flight choreography and engine repair. I divided flight into three parts: the engine, the left wing, and the right wing. If one part broke, the dashboard UI and airplane would respond with a noticeable visual signature. I scripted and debugged airplane flight, collision physics, and dashboard interaction. The dashboard is programmed so that if no part needs repair, the dashboard cannot be interacted with. Since Unity's UI system didn't support infinite rotation for the crank turns, I hard-coded them in by tracking the cranks' location on the screen and the mouse's position in relation to the crank. I implemented engine repair by using a transparent button click region, but didn't have time to add a feedback animation.

### Takeaways
I could have better assessed my time and designed a smaller environment, which would give me more time to implement a win/lose condition. Working on the game also helped me better understand where Unity's UI system falls short, which provides a challenge as to how I can improve or augment the Unity UI system. All in all, the project gave me more confidence as a designer and developer.