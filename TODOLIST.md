<details>
<summary><h1>Document List</h1></summary>

[**Project Description** *(README.md)*](README.md#bounce-climber-project-description)

[**Game Manual** *(GAMEMANUAL.md)*](GAMEMANUAL.md#game-manual)

[**To-do List** *(TODOLIST.md)*](TODOLIST.md#to-do-list)

[**Project Plans** *(PROJECTPLANS.md)*](PROJECTPLANS.md#project-plans)

</details>

# To-do list

<details>
<summary><h2>Game Structure</h2></summary>

I will gather here things that are mostly done in the side of creating a skeleton for the game to work with.

- [ ] State machines
    - [ ] **Player**
        - [ ] Basic States
            - [ ] In Main Menu
            - [ ] Dead
            - [ ] Playing
            - [ ] Movement
                - [ ] Bouncing
                - [ ] Falling
                - [ ] Jumping

        - [ ] Special States
            - [ ] Static Toggle
            - [ ] Collision Toggle
            - [ ] Showcase for menus
                - [ ] Idle
                - [ ] Bouncing

    - [ ] **Game**
        - [ ] Main Menu
        - [ ] Paused
        - [ ] Playing

- [ ] **Platform changes**
    - [x] Give platforms breakable layers
        - [ ] As a list
        - [ ] Have set their own health

- [ ] **Player changes**
    - [ ] Inflict damage to platforms on contact
        - [ ] Static amount
            - [ ] Eventually upgradeable (lower damage inflicted)
        - [ ] Based on speed on contact

</details>

<details>
<summary><h2>Game Mechanics</h2></summary>

Here I am aiming to use the skeleton of the game

### Game menus

- [ ] **Main Menu**
    - [ ] Play Game Menu
        - [ ] Start Game
        - [ ] Change Gamemode
        - [ ] Back to Main Menu
- [ ] **Pause Menu**
    - [ ] Continue
    - [ ] Settings Menu
    - [ ] To Main Menu

- [ ] **Gameover Menu**
    - [ ] Restart
    - [ ] To Main Menu

- [ ] **Settings Menu**
    - [ ] Game Settings
        - [ ] Ball color change

    - [ ] Sound Settings
        - [ ] Main Volume Slider 0 to 100 (Default 50)

### Minimap

- [ ] Intuitive to read
- [ ] Useful for micro-movements

### Gameplay

-   #### Player Specific

    - [ ] [**Charge jump ability**](GAMEMANUAL.md#charge-jump-ability)
    - [ ] [**Dash ability**](GAMEMANUAL.md#dash-ability)
    - [ ] [**Dive ability**](GAMEMANUAL.md#dive-ability)

    - [ ] Player/Ball deformation
        - [ ] On bounce
        - [ ] On high speeds
        - [ ] Back to original on zero speed
        - [ ] Jump delay based on Falling speed
        - [ ] Deformation amount based on falling speed
        - [ ] Add extra special effects on higher velocities

    - [ ] Double-jump
    - [x] Icy platform break on contact (from above)

-   #### Game Specific

    - [ ] Give platforms "health" for when they break
        - [ ] Some platforms to never break
        - [ ] Some platforms to have layers, which have their own health
    - [ ] Close game loop (Start game --> play --> lose/win --> start game)
    - [ ] Cycle of Seasons with distance

</details>

<details>
<summary><h2>Art</h2></summary>

I aim to create very pleasing looking and sounding game with these effects

- [ ] Polishing game with graphics and sounds
    - [ ] Ball deformation
    - [ ] Better splash animation on landing
    - [ ] Better default platform break animation

- [ ] Add more platform types
    - [x] **Winter**
        - [x] Winter platform animations (Ice break and melt)
        - [ ] Unique sound on ice and the platform
        - [x] Unique animation on land (Ice breaking, none for platform inside)

    - [ ] **Spring**

    - [x] **Summer**
        - [ ] Summer platform animations (maybe flowers growing, bees flying)
        - [ ] Unique sound
        - [ ] Unique animation on land

    - [ ] **Autumn**

</details>