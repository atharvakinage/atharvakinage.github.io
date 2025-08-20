So these are a few projects made by be, mainly out of interest and some of them were also part of the courses in my college!  

 ## 📂 Projects  

- [Dynamic Signature Capture App](https://github.com/atharvakinage/dynamic-signature-capture) | Kotlin, Android Studio  
  This is an Android app to capture dynamic metrics like **velocity, acceleration, pressure and direction** for forgery detection.  
  So I created a custom canvas that lets the user sign and save their signature, and upon saving 2 files are created and stored in the devices internal storage, one is png image of the signauture itself and other is a csv file that contains the dynamic metrics of the signauture at stroke level.  
  This has successfully been used by around 150+ people for data collection as of now.

- [CHIP-8 Emulator](https://github.com/atharvakinage/Chip8) | C++, Raylib  
  This is an Emulator that simulates **CHIP-8 architecture** and runs classic retro games (.ch8). I emulated 34 instructions based on the cowgods specification and followed [Austin Morlans guide](https://austinmorlan.com/posts/chip8_emulator/) for a little help.  
  I Implemented instruction decoding, memory management, and register operations and mimicked the components of a CHIP-8 like the 16 8-bit registers, 4K bytes of memory, 16-bit Index register, 16-bit program counter, 16-level stack, 8-bit stack pointer, 8 bit delay timer, the 16 input keys and the display for which I used Raylib.  

- [Pac-Man](https://github.com/atharvakinage/pacman) | Java, JavaFX, MySQL  
  This is a Classic Pac-Man game built with **MVC architecture** and **database persistence** for player scores. MVC is used for modularity and maintainability and to have a well-structured package organization (model, view, controller, db, observer, factory).  
  This consists of an interactive game UI built using JavaFX, real-time score display, game canvas for maze, player, ghosts and pellets and start and scoreboard screens for user interaction. MySQL is the database used in the backend to store and retrieve player scores.

- [YADTQ (Yet another distributed task queue)](https://github.com/atharvakinage/YADTQ) | Python, Kafka, Redis  
  As a part of the course Big Data me and 3 other people implemented a core yadtq module in python that coordinates between multiple workers in a highly distributed setup. This system uses Apache Kafka as a communication service and Redis as the in memory data store.  
  We also implemented heartbeat checks mechanism and created a shell script to enable auto-partitioning. 

- [my-fzf](https://github.com/atharvakinage/my-fzf) | powershell  
  This a simple script for interactive file navigation and management using fzf fuzzy finder for powershell.  
  I integrated system commands for interactions, enabling directory navigation, file editing and deletion (which has to be fixed).

