# GDIM32 In Class Activities

# Devlog


## Week 1

Activity 1 

- Make sure your itch link works. 
- Send itch link to others to playtest.
- Make sure to commit in Github. 
- Attend the office hours.

Activity 2

- 1. 10
- 2. 2
- 3. The PrintMessage() method will cause the console to print "hello world". The Update() method will cause Unity to print "hello world" in the console every frame.
- 4. MonoBehavior
- 5. The PrintMessage() method will cause Unity to print "x = " and the int that was given to this method. The Start() method will call the PrintMessage() at the start. 
- 6. The highlighted lines of code are called arguments and parameters. They are used to give unqiue inputs to methods.
- 7. The code is using Transform.Translate instead of _platerTransform.translate.
- 8. We should change the highlighted code to _playerTransform.

Activity 3

Here is the link: [Week 1 Activity](https://docs.google.com/document/d/11NYqSVvzWFbjYSesEhZULsuZtHzjsLqqcApzmbzIQNQ/edit?usp=sharing)

## Week 2

Activity 1

<img width="960" height="540" alt="W2 In-Class Activity" src="https://github.com/user-attachments/assets/29defdc4-871e-4a13-9ca7-29136c570546" />

Activity 2

[MG 2 commit link](https://github.com/UCI-GDIM32-W25/mg2-lsabe37/commit/5b0e5e1b17f790e88e66fe1eaeb5ee66706c6d92)

I worked on finishing the entire MG 2 game. The player can jump only when the space bar is pressed. The coins move in slowly from the right side of the screen at a random spawn rate. The coins are destroyed when collided with the player game object and the score UI is updated.

## Week 3

Activity 0-2

My teammate for this week was Han.

Activity 3

<img width="960" height="540" alt="W3 In-Class Activity" src="https://github.com/user-attachments/assets/b6360ebb-c769-4992-92cf-a53b0f9b6953" />

## Week 4

Activity 0

I worked with Han this week.

Activity 1

When I add multiple Locator game objects and run the game, the Locator script will get deleted from all but one Locator game object. This is because the Locator script is a singleton and has code that makes sure only one instance of the Locator class can exist during the Awake process. 

Activity 2

<img width="960" height="540" alt="W In-Class Activity" src="https://github.com/user-attachments/assets/b9cb921a-2c03-4db4-b45e-4d0d60c1fbe6" />

Activity 3

[MG4 Commit link](https://github.com/lsabe37/HW4/commit/5bc9cd88b0040ec8671c655b71b44310343c068d)

I worked on setting up the player game object, pipe prefabs, and UI. I also work on the player script and set up for the pipes and pipe spawner scripts.

## Week 5

Activity 1

I think the interface and abstract class designs are good because organize the different features of each playable item. By splitting the two inheritable classes into an interface and abstract class,the child classes can inherit from both these classes if necessry. I think I would keep this structure largely the same if I were to build a game like this.

Activity 2

The ItemW5Demo2 and EnemyStats represent the Model. The InventoryUI and DialogueBubble classes represent the View. The PlayerW5Demo2 and Enemyyw%Demo2  classes repreent the Controller.

Activity 3

Scenario 1: The beats will be prefabs and scriptable objects so that they will have a SpriteRenderer and necessary componets, as well as data such as where in the song they will be present.

Scenario 2: In this game, the Model will be represented by the different types of weapons and their shooting behavior. The View will be represented by the UI and player animations. The Controller will be represented by classes that process player inputs for movements, using abiltiies, etc.

Scenario 3: The model view controller will be used to structure the system. It will help separate the Player class from the UI, Sfx, Game Manager, and other View and Model classes.Inheritance with polymorphism will be used for the different crops. Each crop will have unique traits, such as time it takes to harvest, but they will all share similar features like how they are planted. Thus, each crop will be a child class of the crop parent absrtact class. Finite state machines will be used to determine whicgh state the crops will be in. It will also be used to determine which state the player is in. Singletons will be used in the game on classes such as the GameManager and SfxManager. These are classes that many other classes such as the PLayer class need to access and there will only be one instance of themm.

Activity 4:

Attendance: Leo Abe, Jing Chen, Han Yang

[Final Project Proposal](https://docs.google.com/document/d/13jJEC-fdvdxtT06lxVfHc2n7kMfb3ouPPp6kTowmMfg/edit?usp=sharing)

## Week 6

Activity 1

Gizmos are a helpful way to debug physics and collider related issues. I think Gizmos can be used in my final project to help visualize certain parts of the game that will be invisible to players. For example, I can check how far the player needs to be in order to interact with items by drawing Gizmos. I can use performance profiling to improve my game's performance. For example, I can use performane profiling to check how my game's performance will be influenced when I add features that require lots of calculations to be done at once. I can use breakpoints to help debug my code by allowing the program to stop before the line of code with the error runs. I can use breakpoints in my final project to figure out which lines of my code are null when it runs. This will help me figure out where the issues in my code are.

Activity 2

Attendance: Leo Abe, Jing Chen, Han Yang

[Final Project Proposal](https://docs.google.com/document/d/13jJEC-fdvdxtT06lxVfHc2n7kMfb3ouPPp6kTowmMfg/edit?usp=sharing)

## Week 7

Activity 1

Raycast can be used in commonly seen game mechanics such as aggro conditions for the npc characters. In the example, raycast is used to check what is in the line of sight for the duck npc. When raycast hits the player chicken, the duck will enter the aggro state. However, if the raycast hits something other than the chicken, it will not aggro on the player.

Spherecast, like raycast, can be used to check if something is in front of the the character. In the example, the spherecast on the duck is used to check if an obstacle is in the way of the duck. When the spherecast detects an obstacle, the duck will turn and move in a new direction. 

Activity 2

Attendance: Leo Abe, Jing Chen, Han Yang

Activity 3

<img width="960" height="540" alt="Breakdown" src="https://github.com/user-attachments/assets/5e297f36-bee9-4583-b9f7-d357098be727" />

Activity 4



Activity 5
