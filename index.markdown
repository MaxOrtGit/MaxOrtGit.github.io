---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---

# Code Samples
### [C++26: Reflection extension for JSON for Modern C++ library](https://github.com/MaxOrtGit/RandomStuff/blob/main/cpp/cpp26/Cpp26reflection/AttributesModernJsonExtension.cpp)
[Godbolt](https://godbolt.org/z/7zq1je6jT) link but because the proposals change so often it may not work. Output is in the github link. 
I created the project as more a proof of concept for an upcoming C++ refection feature. It aims to add an attribute like system to the language using refection and template arguments. This project uses attributes and CTAD for 
### [Python: Machine Learning to predict esports games](https://nbviewer.org/github/MaxOrtGit/ValorantEsportsAI/blob/main/EsportsAI.ipynb)
This is the primary file in the Valorant Esports AI project detailed below.

# Cosmic Cargo
This is a Video Game I worked on for my sophomore year game project. I am the tech lead of a team of 8. The game is programmed in C++ and uses a custom engine built on top of OpenGL. It is a space ship building battler / roguelike. I built the core of the engine, most of the gameplay features like the ships and projectiles, editor tools, optimizations, and coordination with the designers. Some of the notable things I did are:
- Created the entity component system the engine is built on
- Serialization with Modern JSON for C++
- Created a debug editor system that generates a GUI from the JSON of an entity while also allowing for overriding different aspects of the UI
- Built a library so serialization, editors, and config / saves can all be added in just two lines of code
- Created a variety of editors for the designers to use like a ship and turret editor
- Made the tiled ship system to allow for easy ship creation, modification, and turret placement
- Did the collision detection and resolution that supports both thousands projectiles and dozens of ships
- Created a particle system that can render thousands of particles with no performance drop and millions with 60+ fps

<iframe width="560" height="315" src="https://youtube.com/embed/RrCWfwklU7A" frameborder="0" allowfullscreen></iframe>

# [Valorant Esports AI](https://github.com/MaxOrtGit/ValorantEsportsAI)
This was a final project for a Machine Learning class. It uses data I collected from [vlr](https://www.vlr.gg/) about a team and it's players. The project both trains and tests a model to predict the outcome of a match. 
- Uses a variety of Traditional Machine Learning models like Random Forest
- Built with Python and uses Pandas, Numpy, and Scikit-learn for the ML and Selenium and BeautifulSoup for the web scraping
- Achieved a 62% accuracy on the test data tying the accuracy of the betting sites I used for the data


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


# [Resume](https://maxortgit.github.io/Files/MaxOrtmanResume.pdf)