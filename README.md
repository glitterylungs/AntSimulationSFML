# Ants Simulation

### 1. Project description.
The "Ants Simulation" project is an application in English, based on the SFML library (more specifically SFML-GRAPHICS). The main language here is object-oriented C ++. Ants Simulation is an application displayed in the window, while the console itself was only used to print program logs. The main core of the program is the engine class, which is responsible for resource management, transition between game states, controlling the framerate and the general display of the window. Then, based on the state class, all application states were created, such as welcome initState, menuState or even simulationState. The simulationState itself is also divided into two states, which are distinguished by the enum class - these are START and PLANNER. In the simulated state, after setting up obstacles, nests, ants and food, the ants move according to their algorithm, collecting food along the way and carrying it to the anthill. The project also includes an interactive menu and rules of the game.



### 2. User manual
After starting the program, we see the initial window. To go to the interactive menu, press the Spacebar. From now on, you need to use the mouse to navigate through the program.

<img width="494" alt="Zrzut ekranu 2022-04-19 o 22 03 00" src="https://user-images.githubusercontent.com/72377506/164086383-5f59efb3-e18e-403f-869a-f4f82108960a.png">

After going to the main menu, we have three options for action. After clicking on the "Exit" button, the program is exited. After selecting the "Rules" option, our eyes will see an interactive instruction describing what the simulation is all about. By selecting the "Start" option, we will be redirected to the planner.

<img width="517" alt="Zrzut ekranu 2022-04-19 o 22 03 50" src="https://user-images.githubusercontent.com/72377506/164086552-7329edc7-cc08-49d5-ba5d-4e345592c4f6.png">

<img width="538" alt="Zrzut ekranu 2022-04-19 o 22 04 45" src="https://user-images.githubusercontent.com/72377506/164086647-e36d56dc-36ce-4da8-9a1b-f527bd6c1873.png">

  
In the planner, we can set obstacles, anthill and food. It is also possible to go to the rules of the game and return to the menu.

<img width="538" alt="Zrzut ekranu 2022-04-19 o 22 05 23" src="https://user-images.githubusercontent.com/72377506/164086733-1378df63-630a-460d-b4a4-ed1884219372.png">

 
 After unfolding the objects and clicking the "Start" button, the simulation begins. In the anthill, we can see a counter whose task is to count the amount of food brought to the anthill.
 
 <img width="543" alt="Zrzut ekranu 2022-04-19 o 22 06 02" src="https://user-images.githubusercontent.com/72377506/164086811-3c8b5cac-8c0e-4684-87b1-e2cd676608a1.png">

 
 
### 3. Summary and conclusions.
All the assumed functionalities of the project were implemented, although not everything turned out to be as obvious as we thought it would be. One of the most difficult problems here was placing objects on the screen, we had to use a few additional variables (flags) to be able to successively place them in the last position of the mouse at the time of clicking. Another problem was that the ant would move randomly on the screen at a certain speed, the problem was mainly changing directions too often and making it all seem natural. The algorithm itself works by drawing between 0-7 directions, and then randomly drawing one of the neighboring directions every 2 seconds, or maintaining the selected direction. Of course, this is only a fraction of the problems we had to face, albeit the end result definitely brought us satisfaction. In addition, during the project, we gained experience in designing the application and writing it object-oriented.

