tdrpg-bugs
==========

This repo doesn't have any code, it's just a convenient dumping ground for any issues users might find in the test builds for DQ1-haxe and DQ2-haxe.

#Instructions

###1. Log in / Sign up for a Github account
You'll need a Github account to report issues and bugs.

###2. Learn how to report a bug! *This is very important!*

In order to fix a bug, we have to be able to reproduce the error or problem you've encountered.
Therefore, please follow this example format: 

```
    BASIC INFORMATION:
    
    Operating System: Windows XP
    Browser/Download: Download
    Demo/Full?      : Full Version
    Version #       : 0.1.2*
    Optional Info** : I was using a netbook with a maximum native resolution of 1024x768
    
    *Version # is at the bottom-right of the title screen
    **Optional info is just anything else you think might be important
```

*This information lets us know which build/version of the game has a problem*

```
STEPS TO REPRODUCE:
    
1. Start a "New Game"
2. Beat the first level 
   (I placed the berserker, boosted him once, 
    and set speed to "2x")
3. Exit the reward screen from the first battle
4. Click on the second level, click "start"
5. Beat the second level 
   (I placed the berserker at the end of the "peninsula," 
    set speed to "4x" and used lightning on the last wave)
6. Exit the reward screen from the second battle
```

*If we can't reproduce the bug, we can't fix it!*

```
WHAT I EXPECTED TO HAPPEN:
    
I expected to see a connection on the map between the second and third battles.
```

*Knowing what you were actually expecting to happen is much more helpful than only knowing what the error was.*

```
WHAT HAPPENED INSTEAD:
    
When I exited the first battle, the first and second levels were connected. 
When I exited the second battle, however, the second and third battles were NOT connected. 
I could still click on the third battle and move there, 
but there was no visual road connection. 
```

*This lets us know what the allegedly bad result was.*
