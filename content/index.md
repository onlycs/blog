---
title: About Me
---
My name is Angad Tendulkar. At the time of writing, I am a junior at Shaker High School.

## Things I've Done, Separated by Year

### Grade 4
* I start learning Python using `CodeCombat` because it was engaging to my 10-year-old brain, I guess
### Grade 5
* My dad buys me a book titled `How to Code Games in Python` and I immediately pick up [pgzero](https://pygame-zero.readthedocs.io/en/stable/) on the old family computer
* Somewhere around this time, I also learn HTML, CSS, and start Javascript
### Grade 6
* Make an unblocked games website using my knowledge about embedding `iframe`s
* Got my first phone during the lockdown, familiarized myself with android-development-related-tools (i.e. ADB and fastboot)
* Make a GitHub account (sometime during pandemic)
* Finally made the switch from Windows to Linux Mint
### Grade 7
#### Android
* My phone eventually runs out of software updates (it was cheap, ~$200 I paid for myself)
* I get familiar with booting [Android GSIs](https://developer.android.com/topic/generic-system-image)
* I meet the few people who care enough about these $200 phones to attempt to make ROMs for them. (Thank you so much [Electimon](https://github.com/electimon)!)
* Turns out the lead developer bricked their phone while working on the ROM, I continue development ([device](https://github.com/onlycs/device_motorola_doha), [kernel](https://github.com/onlycs/kernel_motorola_trinket), [vendor](https://github.com/onlycs/vendor_motorola_doha)), learning stuff along the way.
* I cannot do justice to all the people who helped me along this period, it was honestly amazing the support I got for developing the ROM
#### Other
* Find [alloy](https://github.com/titaniumnetwork-dev/alloy) in the wild and make frontend for their webproxy (lost to time)
* Switch from Linux Mint to kUbuntu
### Grade 8
#### Web Proxy
* Once [titaniumnetwork](https://github.com/titaniumnetwork-dev) released [ultraviolet](https://github.com/titaniumnetwork-dev/ultraviolet) I ended up developing a new frontend for it, learning react along the way. Called it [Inertia](https://github.com/inertia-unblocker), and had [a friend](https://github.com/Doomcow500) help with icons and frontend design
* Ended up getting [GeForce Now](https://www.nvidia.com/en-us/geforce-now/games/) running on it — there were literally kids at lunch playing Apex Legends on school Chromebooks. Wild times.
* Through this project, I learned a **lot** about networking and VPNs. I even created my own StrongSwan server on an old laptop running at home. Worked like a charm.
#### Linux
* Distro-hopped a couple of times, ended up settling on daily driving Arch Linux
#### Discord
* Made and maintained a discord bot, `NCI Bot` (preceded by [Smarty](https://github.com/pg-4919/smarty), though both were still used at the time), written in Typescript, for the discord server me and my friends were using at the time. 
#### Misc
* Purchased `onlycs.net` (no longer live, superseded by `angad.page`).
### Grade 9
#### School's CS Classes
* For our second semester of CS classes, I wrote a [wrapper for Applets](https://github.com/onlycs/cs2/blob/main/app/src/main/java/cs2/lwjai/LWJAI.java) called Lightweight Java Applet Interface (aka. `LWJAI`, a parody of `LWJGL`)
* This made animations, positioning, etc, so much easier to write and modify
* For my final project, I wrote both [a game of chess](https://github.com/onlycs/cs2-chess) and tictactoe (in the same repo).
#### FIRST
* Learned Java by [writing the game of chess](https://github.com/onlycs/chess/tree/java-ai).
* Joined the programming subteam for [my school's robotics team](https://github.com/team2791)
* I helped transition our team from the aging [pathweaver](https://docs.wpilib.org/en/stable/docs/software/pathplanning/pathweaver/index.html) to the more modern [pathplanner](https://github.com/mjansen4857/pathplanner) for autonomous paths.
* Coded LEDs
#### Rust
* Learned a new programming language, Rust, in two weeks
* Made a [card game](https://github.com/onlycs/cards.rs) and a chess game to learn.
* Rust is still my primary programming language to date.
#### Chess
* Made a chessboard that could move pieces under it using an electromagnet ([source](https://github.com/onlycs/chess/tree/grbl-chessboard))
* GRBL was running on an Arduino microcontroller.
* Under the board was a linear rail system ([repurposed from a sand table](https://www.instructables.com/Easily-Build-a-MACHINE-THAT-DESTROYS-WHAT-IT-CREAT/)), powered by two stepper motors
#### Discord
* Migrated from NCI Bot to [`oreobot`](https://github.com/onlycs/oreobot), written in Rust. 
#### Web Proxy
* Wrote [atom](https://github.com/onlycs/atom) to learn Vue.
#### Linux
* Switched from GNOME DE to the Hyprland WM.
### Grade 10
#### Jasmine
* Made my own programming language, [Jasmine](https://github.com/onlycs/jasmine), a Rust[^1] → Java compiler.
* Written using the [Pest](https://pest.rs/) parser
#### FIRST
* Worked on April Tag following with our new swerve chassis, using PhotonVision and pain
* Made the arm stay in place instead of falling due to gravity
* Tried and failed to make [Rust bindings](https://github.com/onlycs/robot-rs-old) to the C++ WPILib
* Probably some other stuff I'm forgetting
#### Chess
*  Made a bitboard-based [chess game](https://github.com/onlycs/chess) in Rust. Learned about the internals of how memory was stored and a lot of bit manipulation operations
#### [Radha's Kitchen](https://github.com/radhas-kitchen/radhas-kitchen)
* Produce waste management app for a friend
* Learned gRPC for the API
* The app is finished, but it didn't really go anywhere unfortunately
#### Framework
* I got a [Framework Laptop 16](https://frame.work), and will never again need to buy a new laptop
### Grade 11
#### FIRST Offseason
* Programming team lead (!!!)
* Rewrote the entire 2024 robot code for the offseason because `periodic`s were running over the 0.02s barrier, causing problems
* Learned Kotlin for robot, I used it instead of Java because I had to make stuff work quickly™
* For [NERD](https://www.thebluealliance.com/event/2024matb), we reached 2nd place overall.
* I couldn't find records of it, but we went to Robot Rumble in Ballston Spa. Our Junk Drawer[^2] ended up doing really well though.
#### Attendance
* Made an [attendance system](https://github.com/onlycs/attendance) ([live website](https://attendance.angad.page)) for our team to keep track of hours
* Got away with not storing any student data, just the sha256 hashes of their IDs
#### Fluid Simulation
* I found [Sebastian Lague](https://www.youtube.com/@SebastianLague), and his [Fluid Simulation](https://www.youtube.com/watch?v=rSKMYc1CQHE), which I thought was really cool, so I [wrote something similar in rust](https://github.com/onlycs/fluidsim)
* Rewrote it twice, once to make it run using a super low-level graphics library (`wgpu`) and once again to run all of it on the GPU.
* Brought you the rant, [[The State of Shaders]]
#### Blog
* Made [this blog](https://blog.angad.page) so I can write stuff down.
#### FIRST Dive[^3]
* Brought [AdvantageKit](https://github.com/Mechanical-Advantage/AdvantageKit) to our team. Level 3 logging and simulations are so cool. 
* We're doing [actual simulations](https://github.com/team2791/robot2025/tree/main/src/main/java/frc/robot/subsystems/drivetrain/module/ModuleSim.java) now!
* Finalists at Tech Valley Regional (!!)
#### Operating System
* Currently working on an (emulated) RISC-V Operating System
* See [[Operating Systems - Hello, World!|Part 1]] of how I made it if you're curious.
## What I'm Good At
* I am a talented Rust developer, and I am best with literally anything other than writing UIs[^4]
* I also know Dart, Kotlin, Java, Javascript and Typescript, Python, Lua[^5], C#[^6], Bash and Shell Scripting, React/NextJS, Vue/Nuxt, a little Go, HTML and CSS, C[^7], and a little C++.
* I am very good with Linux[^8]
* I also know Docker and containerization basics
* I *can* make websites, but they don't look too great, usually

[^1]: It wasn't actual rust, just a language that resembled it in syntax and semantics
[^2]: The robot we scrapped together in like, two weeks, using spare parts
[^3]: Events are currently unfolding. May not be up to date by the time you read it
[^4]: I kid you not, I cannot write a good UI to save my life
[^5]: I worked with `neovim` for a while
[^6]: I made a small game in unity, circa pandemic
[^7]: Did a small card game in C at some point, it annoyed me
[^8]: Mandatory "I use arch, btw" incoming