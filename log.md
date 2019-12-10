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
- a possible minimal outcome is a web app where all entities around a simple p&p framework (eg. [how to be a hero](https://howtobeahero.de/index.php?title=Hauptseite)) can be predefined and then based on that executed as an adventure
- as this is already a huge target for a minimal outcome let's see where it leads to :)

### Day 12: 2019 October 31, Thursday

**Today's Progress**: Happy Halloween! I solved the especially for this day released ['Scary Python'](https://platform.entwicklerheld.de/challenge/scary-python) debugging challenge from [EntwicklerHeld](https://entwicklerheld.de/developers/) today.

**Thoughts:** Usually I wanted to start with the outcome of my Intermediate Planning Day but then I recognized that EntwicklerHeld released a special Halloween Python challenge and spontaneously decided to give it a try. As it was related to debug problems from lesser known Python behavior I needed to look up some stuff to solve it. They referenced a very useful repo that provides a big collection of these cases (see links). I think it will serve as great knowledge source in the future too. Therefore I'm glad I went for this small side-step.

**Link(s)**
1. [Scary Python](https://platform.entwicklerheld.de/challenge/scary-python)
2. [wtfpython](https://github.com/satwikkansal/wtfpython)

### Day 13: 2019 November 1, Friday

**Today's Progress**: I familiarized myself with the [click](https://palletsprojects.com/p/click/) python library as a basis to start the next project.

**Thoughts:** The library seems to be really easy to use and covers a nice set of functionality.

**Link(s) to work**
1. [cli-tools Repository](https://github.com/p-friedl/cli-tools)

### Day 14: 2019 November 2, Saturday

**Today's Progress**: I started the planned new CLI project. Implemented a command to add Information, Decision and Task protocol items with different metadata. Additionally implemented a command to list these items. A local CSV file serves as datasource for these simple operations.

**Thoughts:** The start was a little rough cause I forgot to think about a proper datasource in my planning. After this was solved I was able to implement the needed classes and main flow smoothly apart from some small bugs which I fixed on the fly.

**Link(s) to work**
1. [cli-tools Repository](https://github.com/p-friedl/cli-tools) (meetmaster folder)

### Day 15: 2019 November 3, Sunday

**Today's Progress**: Extended my CLI meeting protocol tool project. Implemented a command to only list items matching a certain type. Additionally implemented a command to remove single items or delete the whole protocol.

**Thoughts:** It was a straightforward implementation without big problems. I could extend and improve the tool now but I already achieved my goal to learn the click library. Therefore I will most likely move forward to my first Django project tomorrow.

**Link(s) to work**
1. [cli-tools Repository](https://github.com/p-friedl/cli-tools) (meetmaster folder)

### Day 16: 2019 November 4, Monday

**Today's Progress**: Started with the official [Django tutorial](https://docs.djangoproject.com/en/2.2/intro/tutorial01/) to create a basic poll application.

**Thoughts:** The documentation is very rich and well written. Unfortunately I got interrupted by a heroku deployment emergency from a friend. As this took quite long I was not able to finish a significant part of the tutorial yet. Hope I can compensate that tomorrow.

**Link(s) to work**
1. [polling app tutorial](https://github.com/p-friedl/polling-app-tutorial)

### Day 17: 2019 November 5, Tuesday

**Today's Progress**: Going on with the official [Django tutorial](https://docs.djangoproject.com/en/2.2/intro/tutorial01/) to create a basic poll application. Learned about how to create and use models.

**Thoughts:** Step by step I see how powerful Django really is making things easier. Looking forward to finish the tutorial soon as I'm motivated to start my own project with it.

**Link(s) to work**
1. [polling app tutorial](https://github.com/p-friedl/polling-app-tutorial)

### Day 18: 2019 November 6, Wednesday

**Today's Progress**: Continued the official [Django tutorial](https://docs.djangoproject.com/en/2.2/intro/tutorial01/) regarding Django admin, the database API, and how to build basic views and templates.

**Thoughts:** Everything is well described and understandable in the official tutorial. Only problem: I'm starting to get impatient just reading and reproducing / playing with the results.

**Link(s) to work**
1. [polling app tutorial](https://github.com/p-friedl/polling-app-tutorial)

### Day 19: 2019 November 7, Thursday

**Today's Progress**: Still working on the official [Django tutorial](https://docs.djangoproject.com/en/2.2/intro/tutorial01/). Today was about forms and Django's generic views.

**Thoughts:** No special thoughts today. :)

**Link(s) to work**
1. [polling app tutorial](https://github.com/p-friedl/polling-app-tutorial)

### Day 20: 2019 November 8, Friday

**Today's Progress**: Needed to interrupt my initially planned progress on the official Django tutorial and support a friend again with the Python otree framework for social experiments.

**Thoughts:** It's always a good feeling to share some knowledge and I'm glad I was able to help out especially with some knowledge I recently acquired via 100 Days Of Code.

**Link(s) to work**
1. not available as it's a private repo

### Day 21: 2019 November 9, Saturday

**Today's Progress**: Returned back to the official [Django tutorial](https://docs.djangoproject.com/en/2.2/intro/tutorial01/) and learned about basic testing in Django.

**Thoughts:** It was a great introduction to testing and I have the feeling I can adapt some points also for other future projects outside of Django as I haven't applied testing yet to any of my projects. Some further readings / learnings related to this topic which I should consider are [Code coverage](https://docs.djangoproject.com/en/2.2/topics/testing/advanced/#topics-testing-code-coverage) and [Selenium](https://www.seleniumhq.org/).

**Link(s) to work**
1. [polling app tutorial](https://github.com/p-friedl/polling-app-tutorial)

### Day 22: 2019 November 11, Monday

**Today's Progress**: Finished the official [Django tutorial](https://docs.djangoproject.com/en/2.2/intro/tutorial01/) by learning about static file management and admin template customization.

**Thoughts:** Yes it's the correct date. Needed to pause and move Day 22 from 10th to the 11th of November. Anyway glad that the Django tutorial is done and I can go on with private projects now. I have an idea what I want to do (refer to the log of 30th October) but on the other hand I want to do some paper planning beforehand. Therefore it could be that I push some smaller project in between. We will see tomorrow!

**Link(s) to work**
1. [polling app tutorial](https://github.com/p-friedl/polling-app-tutorial)

### Intermediate Planning Days: 2019 November 12-15

**Reason:** I'm facing my first big Django project. I want to build a web app which supports a game / dungeon master in the preparation and execution of a pen & paper adventure. For that reason and also due to high workload in my job I decided to invest some time in planning.

**Outcome:**
1. I decided to build the game based on the [how to be a hero](https://howtobeahero.de/index.php?title=Hauptseite) framework.
- But maybe I find also an architectural style to keep it open to have easily new frameworks added in future.
- As it is mainly driven by a german community I want to check out if I can directly internationalization to support German and English language especially for the UI. For sure this will need a little more research as it was not part of the official Django tutorial. But I know they have documentation for it.
2. I will give the project the working title "How to be a Dungeon Master" as it fits somehow the name of the to be used framework.
3. Having a good idea about the data model is crucial for that web app as there are lot of entities with different relationships and attributes.
- The model feature of Django should anyway work fine to build it.
- It will make sense to properly structure the project into several apps which can live on their own too.
- A good starting point would be the Character model which I scribbled on some paper already
4. I had a look on some existing apps out there serving a similar purpose
- [Fantasy Grounds](https://www.fantasygrounds.com/home/home.php) and [Roll20](https://roll20.net/) are very mature in that area
- the first target is not to rebuild them but rather use the simplicity of the how to be a hero framework to build a toolset to make the life of the dungeon master easier
- the [dungeon revealer](https://github.com/dungeon-revealer/dungeon-revealer) is more focused on maps which I don't want to support at the beginning. But for the future it might be interesting to integrate such tools or extend the web app.
5. I want to build up a basic backend first and then start with UI topics which can be continuously improved.
- But of course I have already some UI ideas in my mind as it also has effect on the data model

### Day 23: 2019 November 16, Saturday

**Today's Progress**: After taking a planning pause, D23 is there and I started my new project with working title "How to be a Game Master". The purpose is to build a web app which supports game masters of the pen & paper framework "How to be a Hero". Started with the character model.

**Thoughts:** The character model is not finished yet as I got stuck with an error in the Django DB migration. I don't know what is the problem, need to investigate on that tomorrow.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 24: 2019 November 17, Sunday

**Today's Progress**: I fixed the bug from yesterday (turned out to be just a wrongly set comma), enhanced the Character model and added a Skill, Bin, Inventory and Item model.

**Thoughts:** While I was stuck yesterday the progress from today is quite good. While creating the different models the Django documentation was of great help.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 25: 2019 November 18, Monday

**Today's Progress**: I improved the existing models by adding new fields and adjusting old ones. Additionally I implemented a character admin view.

**Thoughts:** I should reconsider the item and bin model as they don't fit in the character app. Would be better to put them in the future game app. Overall I currently plan to have 3-4 apps: character, story, (opt: item) and game (which basically combines the other apps). Via Twitter I received the link to a free eBook related to Test Driven Development. I should consider having a look inside as I want to start implementing tests early and not too late.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 26: 2019 November 19, Tuesday

**Today's Progress**: Read about Test Driven Development in Django. Apart from this I restructured my project folders and implemented a creator field in the Character model.

**Thoughts:** I got a little stuck by trying too hard to implement TDD. Currently struggling to adapt my mindset to it. I guess it's related that I'm unsure where to start and how deep it should go. It doesn't make sense to me for example to write a test to check if a certain field gets validated right as this is basic Django functionality and not my code (apart from handling over the right argument for it). Therefore I better focus on writing tests for functions I implement on models. If certain validations get important later I can include their tests at the right time.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 27: 2019 November 20, Wednesday

**Today's Progress**: Wrote some tests and practiced my first test driven implementation by extending the Character model with a calculate_talents method. All tests runs smoothly.

**Thoughts:** I made the best out of my problems yesterday and TDD is now clearer to me. It still slows my progress down but that should be just a matter of time.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 28: 2019 November 21, Thursday

**Today's Progress**: Expanded the Character model by finishing the calculate_talents method and adding a calculate_rescue_points method. Additionally implemented an add_talent_markup method in the Skill model.

**Thoughts:** TDD starts to help in my workflow, which is good. I think I have all the basics in the Backend now to start a first view for Character Sheet creation in the next session.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 29 - 30: 2019 November 23, Saturday - 2019 November 24, Sunday

**Today's Progress**: Paused my Django project cause I helped a friend on some Data cleaning tasks with the Python pandas library. Additionally did some research and experiments on Screen Streaming, Capturing and HTML Canvas manipulation via Javascript as this is needed for another project which came to my mind recently.

**Thoughts:** It was a chaotic weekend and I got distracted too much by future ideas and helping out. But it's important to stay hungry. Anyway looking forward to follow up with my Django project soon.

**Worth to explore further:**
1. [Screen Capture API](https://developer.mozilla.org/en-US/docs/Web/API/Screen_Capture_API/Using_Screen_Capture)
2. [tui image editor](https://www.cssscript.com/canvas-image-editor-tui/)
3. [fabric.js Canvas manipulation library](http://fabricjs.com/)

### Day 31: 2019 November 25, Monday

**Today's Progress**: Resuming my Django Project - started to implement a Form for the Character Creation view.

**Thoughts:** My progress was already quite advanced doing the form manually. Then I realized there is a much more convenient way to implement forms via Django. Could have saved some time with that knowledge. Anyway we learn from our faults! :)

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 32: 2019 November 26, Tuesday

**Today's Progress**: No big progress as I got stuck on the implementation of the Character form.

**Thoughts:** First I misunderstood the purpose of MultiValue Form Fields and spent some time get them working until I realized they will not solve my problem. Then I learned about there are also ModelForms which might be a solution. But I need to do more research on that topic.
Turns out I started too early with a solution as the intended form needs to be dynamic which of course is no standard implementation.
The following resources might be useful:
- [Django Model Forms Docs](https://docs.djangoproject.com/en/2.2/topics/forms/modelforms/)
- [Django Dynamic Forms Tutorial](https://www.caktusgroup.com/blog/2018/05/07/creating-dynamic-forms-django/)

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 33: 2019 November 28, Thursday

**Today's Progress**: I made some progress on implementing the dynamic Character form and it works to create a Character.

**Thoughts:** I followed the [Django Dynamic Forms Tutorial](https://www.caktusgroup.com/blog/2018/05/07/creating-dynamic-forms-django/) but it needed adaptions from my side as my case is more complicated (not adding only one dynamic field, but a set of three dynamic fields) and the used Django versions are different (the article is from 2018). Finally I needed to revert some of my implemented code (character creator relation) as I have no authentication except on the admin views and therefore I couldn't save the Character based on the form input as this is missing. The character creation via the new form works now, but I also need to implement the Frontend part to add and remove skills as well a view to edit existing Characters to really check if the new code is working properly.
Apart from that I'm still unsure if my solution is the best one for that case, as I found new resources to check related to the problem:
- [Django Dynamic Forms app](https://github.com/MarkusH/django-dynamic-forms)
- [Medium Article related to Django formsets and formset_factory](https://medium.com/all-about-django/adding-forms-dynamically-to-a-django-formset-375f1090c2b0)
Let's see how I follow up on this.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 34: 2019 November 29, Friday

**Today's Progress**: I investigated and experimented with Django formset factories. Not fully finished, need to go on with this in the next session.

**Thoughts:** I researched and tried out especially the modelformset_factory and the inlineformset_factory which might be an easier alternative to improve my character creation form with dynamic skills in the current Django project.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 35: 2019 November 30, Saturday

**Today's Progress**: Finished my investigation on Django formset factories (especially inlineformset_factory) and now I clearly can say that this is the best way to achieve what I want.

**Thoughts:** My code is messed up now due to my experimentation so I need to refactor to the final solution in the next session. Glad that I did that research though it took some extra time it reduces the complexity of my code: From initial 100+ lines down to only a couple of lines!  Thats a real Django moment. :)

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 36: 2019 December 1, Sunday

**Today's Progress**: Finally the dynamic form topic is history as I finished the Character creation view with the possibility to add and remove Skills via some additional Javascript.

**Thoughts:** Cleaned up my code again after the experimentation. It took some time but now I feel confident on the topic of forms with Django and also refreshed some basic Javascript. Next step would be to do some additional validation logic, like for example it is not allowed to have an overall Skill value of 400. And there are of course a lot of other tasks on the list before the project is finished.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 37: 2019 December 5, Thursday

**Today's Progress**: Back after a couple of days pause. Implemented the dynamic validation of the overall Skill value fields which shouldn't exceed a total of 400 points in the Character creation form. This works and gives realtime feedback based on Event listeners.

**Thoughts:** I'm getting a little confused sometimes as I'm now mixing up Python and Javascript due to the frontend validation logic. But overall thats no blocking point and just a matter of familiarization.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 38: 2019 December 7, Saturday

**Today's Progress**: Only some lines of code today as I was mostly investigating on how to get the max attribute on the HTML number input field set by my Django model. Turned out that it's not natively possible, therefore I created a custom field subclass of PositiveSmallIntegerField.

**Thoughts:** I have the feeling I got too much bogged down in details. I should more focus on implementing new features rather then solving every little issue directly.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)

### Day 39: 2019 December 10, Tuesday

**Today's Progress**: I implemented authentication for my character creation form and used the chance to reimplement the character - creator relation.

**Thoughts:** This was a missing piece from my past formset factory investigations. Now I can concentrate on the skill markup and rescue point calculation to finish the basic frontend - backend integration. Unfortunately the last days were quite stressful and I was not able to find time for the challenge. Anyway slow progress is also progress.

**Link(s) to work**
1. [HowToBeAGameMaster repo](https://github.com/p-friedl/HowToBeAGameMaster)
