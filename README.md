# rust-os-cs140e
## An Experimental Course on Operating Systems

Assignments from the [CS140 course](https://cs140e.sergio.bz/).

### Directory Structure

```
+-- blinky  
|   +-- phase3  
|   +-- phase4  
+-- shelly  
|   +-- ferris-wheel  
|   +-- questions  
|   +-- stack-vec  
|   +-- ttywrite  
|   +-- volatile  
|   +-- xmodem  
+-- osy  
    +-- bootloader  
    +-- files  
    +-- kernel  
    +-- pi  
    +-- std  
    +-- volatile  
```

### Rust Versioning
```
$ rustup install nightly-2018-01-09
$ rustup default nightly-2018-01-09
$ rustup override set nightly-2018-01-09
$ rustup component add rust-src

$ cargo install xargo --version 0.3.10

$ rustc --version
rustc 1.25.0-nightly (b5392f545 2018-01-08)

$ xargo --version
xargo 0.3.10
cargo 0.25.0-nightly (a88fbace4 2017-12-29)
```

## blinky
Phase 0 - 4 from [Assignment 0: Blinky](https://cs140e.sergio.bz/assignments/0-blinky/).
Get the enviornment setup and make and LED blink in C and Rust.

### Phase 0: Getting Started
- [x] Getting your Pi Ready
- [x] Getting the Skeleton Code

### Phase 1: Baking Pi
- [x] Installing Driver
- [x] Powering the Pi
- [x] Running Programs

### Phase 2: LED There Be Light
- [x] GPIO: General Purpose I/O
- [x] Testing the LED

### Phase 3: Shining C
- [x] Installing a Cross-Compiler
- [x] Talking to Hardware
- [x] GPIO Memory-Mapped Interface
- [x] Writing the Code

### Phase 4: Rusing Away
- [x] Installing Rust and Xargo
- [x] Writing the Code


## shelly
Phase 0 - 2 from [Assignment 1: Shell](https://cs140e.sergio.bz/assignments/1-shell/).
Write `stack-vec`, `volatile`, `ttywrite`, and `xmodem` libraries.

### Phase 0: Getting Started
- [x] Getting the Skeleton Code
- [ ] Questions

### Phase 1: Ferris Wheel
- [x] Diff Budget
- [x] The Rules
- [x] Modify Away!

### Phase 2: Oxidation
- [x] Subphase A: StackVec
- [x] Subphase B: volatile
- [x] Subphase C: xmodem
- [x] Subphase D: ttywrite


## osy
Phase 3 and 4 from [Assignment 1: Shell](https://cs140e.sergio.bz/assignments/1-shell/) and Phase 0, 1, 3, and 4 from [Assignment 2](https://cs140e.sergio.bz/assignments/2-fs/).

The `assignment-1` branch contains the completed code for first assignment, and the `assignment-2` branch contains the completed code for second assignment.

### Assignment 1: Shell

### Phase 3: *Not* a Seashell
- [x] Subphase A: Getting Started
- [x] Subphase B: System Timer
- [x] Subphase C: GPIO
- [x] Subphase D: UART
- [x] Subphase E: The Shell
     
### Phase 4: Boot 'em Up
- [x] Loading Binaries
- [x] Making Space
- [x] Implementing the Bootloader

### Assignment 2: File System

### Phase 0: Getting Started
- [x] Getting the Skeleton Code
- [x] Firmware Update
- [x] Installing ttywrite

### Phase 1: Memory Lane
- [x] Subphase A: Panic!
- [x] Subphase B: ATAGS
- [ ] Subphase C: Warming Up
- [ ] Subphase D: Bump Allocator
- [ ] Subphase E: Bin Allocator

### Phase 3: Saddle Up
- [ ] Subphase A: SD Driver FFI
- [ ] Subphase B: File System

### Phase 4: Mo'sh
- [ ] Working Directory
- [ ] Commands
- [ ]  Implementation


## filey
Phase 2 from [Assignment 2: File System](https://cs140e.sergio.bz/assignments/2-fs/).

### Assignment 2: File System

### Phase 2: 32-bit Lipids
- [ ] Disks and File Systems
- [ ] Disk Layout
- [ ] Code Structure
- [ ] Implementation
