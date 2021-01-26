# AI Fighting
SCB GAMEDAY CHALLENGE

![Alt text](resource/images/screenshot.png?raw=true "AI Fighting Screenshot")

## Introduction
This project is doing for build learning culture on an organize.
This is Fighting game. So, you can play by the keyboard or AI also.

Registration at [Knockout Schema](https://ai-fighter.web.app)

## Prerequisite
`git`

`jdk 8 or above`

`IntelliJ IDEA`

## Source
`git clone https://github.com/iamgique/FightingICE.git`

## How to run the game
`Import project from directory FightingICE`

```
Add library
- File > project structure > modules 
- Click Plus (+) > JARs or Directories
-- /{your_directory}/AIToolKit.jar
-- /{your_directory}/FightingICE.jar
-- /{your_directory}/lib/javax.json-1.0.4.jar
-- /{your_directory}/lib/py4j0.10.4.jar
-- /{your_directory}/lwjgl/lwjgl.jar
-- /{your_directory}/lwjgl/lwjgl_util.jar
-- /{your_directory}/lwjgl/lwjgl-glfw.jar
-- /{your_directory}/lwjgl/lwjgl-openal.jar
-- /{your_directory}/lwjgl/lwjgl-opengl.jar
```

```
Add library follow by your OS
- File > project structure > modules 
- Click Plus (+) > JARs or Directories
-- /{your_directory}/natives/{your_os}/lwjgl-glfw-natives-{your_os}.jar
-- /{your_directory}/natives/{your_os}/lwjgl-natives-{your_os}.jar
-- /{your_directory}/natives/{your_os}/lwjgl-openal-natives-{your_os}.jar
-- /{your_directory}/natives/{your_os}/lwjgl-opengl-natives-{your_os}.jar
```

![Alt text](resource/images/project_structure.png?raw=true "Project Structure")

![Alt text](resource/images/project_structure_lib.png?raw=true "Project Structure Library")

```
Add configuration for IntelliJ
- Choose application
- At the main class: Main
- At VM Option: -XstartOnFirstThread
- Working directory: your directory
- Use classpath of module: FightingICE
- OK
```

![Alt text](resource/images/project_configuration.png?raw=true "Project Configuration")

`run`

## How to add you AI file to FightingICE
`When you have AI file you can push it into directory '/{your_directory}/data/ai/'`

![Alt text](resource/images/AI_screen.png?raw=true "AI Screen")

---

## How to play
```
- Choose the menu by Arrow on keyboard
- 'Z' is the command to choose
- Choose the Player1 and Player2
- Choose the Character1 and Character2
- Play the game
```

### Play by keyboard
```
Player1
'z' = Punch
'x' = Kick
'Arrow Up' = Jump
'Arrow Down' = Sit
'Arrow Back' = Step back or Guard // You can also double
'Arrow Forward' = Step forward // You can also double
 
Player2
't' = Punch
'y' = Kick
'i' = Jump
'k' = Sit
'l' = Step back or Guard // You can also double
'j' = Step forward // You can also double
```

![Alt text](resource/images/home_screen.png?raw=true "Menu screen")

![Alt text](resource/images/option_screen.png?raw=true "Option screen")

---

## To do AI file
Source [FighterAI](https://github.com/iamgique/FighterAI.git)

## References
Source from [FightingICE](http://www.ice.ci.ritsumei.ac.jp/~ftgaic/index.htm)




