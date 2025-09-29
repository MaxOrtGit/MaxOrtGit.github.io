---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---

# Code Samples
### [C++26: Reflection extension for JSON for Modern C++ library](https://github.com/MaxOrtGit/RandomStuff/blob/main/cpp/cpp26/Cpp26reflection/AttributesModernJsonExtension.cpp)
A [Godbolt](https://godbolt.org/z/7zq1je6jT) link is provided, though it may not work due to frequent changes in the proposals
I created the project as more of a proof of concept for an upcoming C++ reflection feature. It aims to add an attribute like system to the language using reflection and template arguments. 
### [Python: Machine Learning to predict esports games](https://nbviewer.org/github/MaxOrtGit/ValorantEsportsAI/blob/main/EsportsAI.ipynb)
This is the primary file in the Valorant Esports AI project detailed below.

# [Code Friend](https://drive.google.com/file/d/130O7AJwsxGJ8wKpA7m0lJtsNVrEJKyXT/view?usp=sharing)
Coding assistant that generates code and documentation using an LLM
- Stores project details in a database for the LLM to reference
- Generates code snippets using relevant functions/classes in context
- Works with Local LLMs or OpenAI
- Specialized agents for specific tasks
- Supports centralized host allowing for different devices to work on the same project simultaneously
- Parallelized requests to LLM for faster responses

# [Cosmic Cargo](https://youtu.be/RrCWfwklU7A)
[Steam Page](https://store.steampowered.com/app/4056230/Cosmic_Cargo)\
This is a video game I worked on for my sophomore year game project. I was the tech lead of an 8-person team. The game is programmed in C++ and uses a custom engine built on top of OpenGL. It is a space ship building battler / roguelike. I built the core of the engine, most of the gameplay features like the ships and projectiles, editor tools, optimizations, and coordination with the designers. Some of the notable things I did include:
- Created the entity component system the engine is built on
- Serialization with Modern JSON for C++
- Created a debug editor system that generates a GUI from the JSON of an entity while also allowing for overriding different aspects of the UI
- Built a library so serialization, editors, and config / saves can all be added in just two lines of code
- Created a variety of editors for the designers to use like a ship and turret editor
- Made the tiled ship system to allow for easy ship creation, modification, and turret placement
- Built the collision detection and resolution that supports both thousands of projectiles and dozens of ships
- Created a particle system that can render thousands of particles with no performance drop and millions with 60+ fps

### Trailer
<iframe width="560" height="315" src="https://youtube.com/embed/RrCWfwklU7A" frameborder="0" allowfullscreen></iframe>

### Editor
Any Entity can be created, edited, and saved. \
All configs can be edited in the editor. \
Interface is generated from the members of the objects and not hand coded.
![Editor](https://maxortgit.github.io/assets/FullEditor.png)

### Adding any object to editor
The editor works by converting an object to JSON and generating a GUI from the resulting JSON. \
Below is adding a new component to the editor. \
Because it works recursively the Texture inside is also included in the interface. \
For the image in the texture, I added a button to open a file explorer.
![Adding a component](https://maxortgit.github.io/assets/EditorSample.png)

### Creating a config / save
All values in a config consist of name-value pairs. \
As long as all the values are serializable they can be added to the config. \
Used for both saves and settings. \
File and editor interface are synced.
![Adding a config](https://maxortgit.github.io/assets/ConfigSample.png)

# [Valorant Esports AI](https://github.com/MaxOrtGit/ValorantEsportsAI)
This was a final project for a Machine Learning class. It uses data I collected from [vlr](https://www.vlr.gg/) about a team and its players. The project both trains and tests a model to predict the outcome of a match. 
- Uses a variety of Traditional Machine Learning models like Random Forest
- Built with Python and uses Pandas, Numpy, and Scikit-learn for the ML and Selenium and BeautifulSoup for the web scraping
- Achieved a 62% accuracy on the test data, matching the accuracy of the betting sites I used for the data


# [VCT Predictions Bot](https://github.com/MaxOrtGit/VCT-Predictions-Bot)
This was my personal project for nearly two years total. It is a Python-based discord bot made with Pycord for making fake bets on Valorant matches. 
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