# 100 Days Of Code - Log

### Day 1: 2019 October 19, Saturday

**Today's Progress**: As I just started and I´m unsure about a right project to start I solved a coding challenge from [EntwicklerHeld](https://platform.entwicklerheld.de).

**Thoughts:** Good starting point to warm up my Python knowledge. First struggled on the algorithm / plan I wanted to implement, but not with the language or syntax. Therefore it should be no problem to go for something more challenging / a first project the next days. Maybe something related to [streamlit library](https://github.com/streamlit/streamlit) before I dig deeper into Django.

**Link(s) to work**
1. [Airport Runway Detection Challenge from EntwicklerHeld](https://platform.entwicklerheld.de/challenge/airport-runway-direction)
2. [My solution](https://github.com/p-friedl/coding-challenges/blob/master/EntwicklerHeld_Airport-Runway-Detection.py)

### Day 2: 2019 October 20, Sunday

**Today's Progress**: I started a first project to simulate the german board game "Mensch ärgere dich nicht". Implemented a first draft of the Board class and the Player class with the possibility to roll and place game figures.

**Thoughts:** I chose this to get deeper into the object oriented mindset as my past experiences are mostly related to functional programming. Needed to look up some stuff but basically there are no blockers currently. Let's see how long it takes to finish the full game sim.

**Link(s) to work**
1. [maedn-game-sim Repository](https://github.com/p-friedl/maedn-game-sim)

### Day 3: 2019 October 21, Monday

**Today's Progress**: Added an id attribute and a move_figure method to the Player class of my new "Mensch ärgere dich nicht" project.

**Thoughts:** Could have achieved more but got stuck by a bug. I should consider improving debugging skills / learning more about logging implementation.

**Link(s) to work**
1. [maedn-game-sim Repository](https://github.com/p-friedl/maedn-game-sim)

### Day 4: 2019 October 22, Tuesday

**Today's Progress**: Implemented a logic to ban other player figures into my "Mensch ärgere dich nicht" project.

**Thoughts:** Guess it will take 1-2 days more to finish the main logic. Looking forward to work with the resulting game simulation data then! Read an [article about software design and architecture](https://www.freecodecamp.org/news/software-design/) from freeCodeCamp today. Was very informative and opened my eyes that there are also some theoretical topics which I should look up soon.

**Link(s) to work**
1. [maedn-game-sim Repository](https://github.com/p-friedl/maedn-game-sim)

### Day 5: 2019 October 23, Wednesday

**Today's Progress**: Did some refactoring to implement a Figure class and finished the intelligent figure selection logic for my "Mensch ärgere dich nicht" project.

**Thoughts:** Nearly finished with the main logic. I have the feeling that my mind is now working quicker in regards of OOP, especially the refactoring was smoother than expected at the beginning.

**Link(s) to work**
1. [maedn-game-sim Repository](https://github.com/p-friedl/maedn-game-sim)

### Day 6: 2019 October 24, Thursday

**Today's Progress**: Finished and tested the main logic of my "Mensch ärgere dich nicht" project.

**Thoughts:** Very positive as everything worked as expected and my tests of the main logic passed successfully. No bugs! Tomorrow I can implement the game loop. Then I should start looking out for a new project.

**Link(s) to work**
1. [maedn-game-sim Repository](https://github.com/p-friedl/maedn-game-sim)

### Day 7: 2019 October 25, Friday

**Today's Progress**: Implemented the game simulation loop of my "Mensch ärgere dich nicht" project.

**Thoughts:** Needed to postpone my work for Day 7 to Saturday morning due to timing reasons. Anyway will also do another session for Day 8 later today to compensate and stay on track. The game loop has still a bug with an empty list where I´m removing an item. Guess I will need to implement logging to find the problem more quickly.

**Link(s) to work**
1. [maedn-game-sim Repository](https://github.com/p-friedl/maedn-game-sim)

### Day 8: 2019 October 26, Saturday

**Today's Progress**: Implemented basic logging and fixed the bug that interrupted the game simulation loop of my "Mensch ärgere dich nicht" project.

**Thoughts:** Still need to do more research on the logging topic and implement it in the next project from beginning to find such bugs quicker. Glad that it is fixed now and the loop is running until the win condition is reached. Anyway there are more tests needed to be sure the output data is valid. I might go on with that if no other project comes to my mind.

**Link(s) to work**
1. [maedn-game-sim Repository](https://github.com/p-friedl/maedn-game-sim)

### Day 9: 2019 October 27, Sunday

**Today's Progress**: Interrupted my current project to help a friend on an urgent project with the python [otree framework](https://otree.readthedocs.io/en/latest/).

**Thoughts:** While it's not the best progress to interrupt my work it's still important to share knowledge and explain things to others. Anyway tomorrow I will go on with my project again.

**Link(s) to work**
1. Unfortunately I can't share it as it's in a private Git repo of my friend

### Day 10: 2019 October 28, Monday

**Today's Progress**: Split the code into separate files and implemented a basic UI with the streamlit library for my "Mensch ärgere dich nicht" project.

**Thoughts:** Streamlit is quite easy to handle - convenient for small prototypes or data projects.

**Link(s) to work**
1. [maedn-game-sim Repository](https://github.com/p-friedl/maedn-game-sim)

### Day 11: 2019 October 29, Tuesday

**Today's Progress**: Finished my "Mensch ärgere dich nicht" project by implementing some statistics of the game simulation.

**Thoughts:** Nice to finally see the project in a working state. I have the feeling it's time to go on with another project and it's also a good point to take at least a break from it. For the next project I wish to do something more useful and not only fun related. Let's see.

**Link(s) to work**
1. [maedn-game-sim Repository](https://github.com/p-friedl/maedn-game-sim)

### Intermediate Planning Day: 2019 October 30, Wednesday

**Reason:** As I finished my last project in a time of general high workload I struggled to find the proper time to do research on the question of "what's next?". Therefore I decided to take a one day break of coding to conduct that research. As I still want to do the challenge properly I categorize this as "planning day" and not part of the official challenge. I will resume with the challenge (Day 12) tomorrow.

**Outcome:**
Basically there are two areas of interest I want to tackle next:
1. Learning how to package my future scripts in useful CLI tools
- one interesting library to explore here is [click](https://palletsprojects.com/p/click/)
- as I want to learn by doing for this I envision a project to support meeting moderators
- a minimal outcome would be a tool that allows to create a meeting agenda and then based on the overall schedule shows the time remaining till end
- this could be possibly extended by the possibility to enter protocols (tasks, decisions, information) and the functionality to export them
2. Expanding my Python knowledge to build web apps
- frameworks and libraries to explore here are [Django](https://www.djangoproject.com/start/overview/) and maybe later also [Flask](https://palletsprojects.com/p/flask/)
- regarding Django a good step to start is their very detailed [first app tutorial](https://docs.djangoproject.com/en/2.2/intro/tutorial01/)
- after finishing that introduction to Django it's time to build something own - for this I envision a project to support the game master of a pen & paper game
- a possible minimal outcome is a web app where all entities around a simple p&p framework (eg. [how to be hero](https://howtobeahero.de/index.php?title=Hauptseite)) can be predefined and then based on that executed as an adventure
- as this is already a huge target for a minimal outcome let's see where it leads to :)

### Day 12: 2019 October 31, Thursday

**Today's Progress**: Happy Halloween! I solved the especially for this day released ['Scary Python'](https://platform.entwicklerheld.de/challenge/scary-python) debugging challenge from [EntwicklerHeld](https://entwicklerheld.de/developers/) today.

**Thoughts:** Usually I wanted to start with the outcome of my Intermediate Planning Day but then I recognized that EntwicklerHeld released a special Halloween Python challenge and spontaneously decided to give it a try. As it was related to debug problems from lesser known Python behavior I needed to look up some stuff to solve it. They referenced a very useful repo that provides a big collection of these cases (see links). I think it will serve as great knowledge source in the future too. Therefore I'm glad I went for this small side-step.

**Link(s)**
1. [Scary Python](https://platform.entwicklerheld.de/challenge/scary-python)
2. [wtfpython](https://github.com/satwikkansal/wtfpython)
