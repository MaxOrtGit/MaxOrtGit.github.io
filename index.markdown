---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---

# Cosmic Cargo
This is my in development project for my sophomore year game project. I am the tech lead of my team of 8. The game is in C++ and uses a custom engine built on top of OpenGL. It is a space ship building battler. I built the core of the engine, most of the gameplay features, tools for the designers, optimizations, and coordination with the designers. Some of the notable things I did are:
- Created the entity component system the engine is built on
- Serialization with Modern JSON for C++
- Created a debug editor system that generates a GUI from the JSON of an entity while also allowing for overriding parts with lambdas
- Built a library so Serialization, Editors, and Config/Saves can all be added in just two lines of code
- Created a ship editor, turret editor, and
- Made the tiled ship system to allow for easy ship creation and modification and turret placement
- Did the collision detection and resolution that supports both thousands projectiles and dozens of ships
- Created particle system that can render millions of particles with textures at 60+ fps

<iframe width="560" height="315" src="https://youtube.com/embed/Fxgdbvw_ZZU" frameborder="0" allowfullscreen></iframe>

# [VCT Predictions Bot](https://github.com/MaxOrtGit/VCT-Predictions-Bot)
This has been my personal project for the past 2 years. It is a Python discord bot made with Pycord for making fake bets on Valorant matches. 
- Has 68 commands that do anything from making a bet to changing a profile's color
- The backend uses SQLAlchemy to store all the data in a SQLite database
- Hosted first on AWS for a year then on a Raspberry Pi
- Web scrapes a site for the match, team, tournament, and odds data
- All matches are generated automatically from just the tournament link
- Has many other small features/details

<iframe width="560" height="315" src="https://youtube.com/embed/TaXZVOtscqM" frameborder="0" allowfullscreen></iframe>
  
# Factory Puzzle Game
This was my second semester freshmen year game project. It was a team of 5. I convinced my team to take the opportunity to make the game in C++ instead of C so we were the only team using C++. The game is a puzzle game where you have to fit in machines in a small area to process foods. I made the machine system that allowed for easy creation of new machines with complicated layouts and multiple recipes. I also made the saving system.

<iframe width="560" height="315" src="https://youtube.com/embed/BWCdsp8-rpM" frameborder="0" allowfullscreen></iframe>
