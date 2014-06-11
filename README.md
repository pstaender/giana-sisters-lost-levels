# Giana Sisters
## "The lost Levels" on C64

In 1989 the two german programmers **Sandy** and **Prof. Knibble** hacked the C64 game "The Great Giana Sisters".

They programmed a [Giana Sisters Construction Kit](http://www.c64-wiki.de/index.php/Das_Gianna-Sisters_Construction-Kit) which made custom level building possible. Unfortunately they could not officially release the software due to copyright and legal issues. Until today there is no "level packager" to build a executable game of the construction kit generated levels but you can use the construction kit to build seperate levels just for fun.

The following "Giana Sisters" are created by Sandy or Prof. Knibble with the construction kit:

  * Gittys Dreams I + II
  * The Gitty's News (+)
  * Knibble Girls I + II
  * Frankys Horror Trip I + II
  * Power Sisters

### Motivation

Unfortunately I couldn't find any working image of the "Giana Sisters Construction Kit" on the internet. Also some "Giana Sisters" clones were not available. So I transfered some of my old C64 disks to the PC these days.  

### Content

All recovered games can be found in `.d64` images in the corresponding folders.

### Tested

The images are tested with VICE and Emu64 and seems to work fine.

### Cheats and start options

  * Press A+R+M+N to skip current level
  * `POKE 5083, 5` (no giana movement animation)
  * `POKE 8207, 173` (extras stay after loosing a life)
  * `POKE 4242, 42` (alternate jump) 
  * `POKE 6664, 96` (bridges indestructible)
  * `POKE 2213, 164` (giana is always in punk mode)
  * `POKE 7450, 95` (unlimited time)
  * `POKE 7236, 27` (no collision check)
  * `POKE 7326, 173` (unlimited diamonds)
  * `POKE 2446, 255` (unlimited lives)
  * `SYS 2127` (start without highscore load)
  * `SYS 2098` (start with highscore load)

To execute a `POKE`/`SYS` command, you have to load the game and perform a **soft** reset. Then type `POKE …` hit enter and the start the game with typing `SYS 2127` and `SYS 2098` respectively.

### Todo

"The Power Sisters", "The Gitty's News" and "Knibble Girls II" couldn't be recovered from disc; so feel free to contribute these or any other clones.

### Issues

"Franky Horror Trip 1" and "Power Sisters" couldn't be recovered from disc, but I found a disc image on the internet which I copied to this repository.

### Gameplay

  * [Gittys Dreams I](https://www.youtube.com/watch?v=SsZpNDQa5AM)
  * [Gittys Dreams II](https://www.youtube.com/watch?v=HCONoKg4s-Q)
  * [Frankys Horror Trip 2](https://www.youtube.com/watch?v=j_uVOEuHIxk)

### Disclaimer and License

I'm not involved in any of these projects neither I own any copyrights for this software. Owners retain copyright to their respective works (Time Warp Productions, Rainbow Arts, Armin Gessert, Sandy, Prof. Knibble et al.). The disk images are contributed with no commercial intention. I just share the content of these over 15 years old discs to keep a piece of C64 sofware history.

If you have any copyright concern please contact me via [philipp.staender@gmail.com](mailto:philipp.staender@gmail.com)  
