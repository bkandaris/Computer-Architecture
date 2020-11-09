<!-- Step 0 - Inventory of the files 

cpu.py -> This is the cpu constructor with an ALU method, and trace method attached to the class that
handle taking care of the mathematical operations and printing out the state of the CPU

ls8.py -> This file is responsible for calling the CPU class

ls8-spec.md -> This is a readme with instructions

examples file -> Holds all of the .ls8 files needed for the project as well as instructions


-->




# Computer Architecture

## Project

* [Implement the LS-8 Emulator](ls8/)

## Task List: add this to the first comment of your Pull Request

### Day 1: Get `print8.ls8` running

- [ ] Inventory what is here
- [ ] Implement the `CPU` constructor
- [ ] Add RAM functions `ram_read()` and `ram_write()`
- [ ] Implement the core of `run()`
- [ ] Implement the `HLT` instruction handler
- [ ] Add the `LDI` instruction
- [ ] Add the `PRN` instruction

### Day 2: Add the ability to load files dynamically, get `mult.ls8` running

- [ ] Un-hardcode the machine code
- [ ] Implement the `load()` function to load an `.ls8` file given the filename
      passed in as an argument
- [ ] Implement a Multiply instruction (run `mult.ls8`)

### Day 3: Stack

- [ ] Implement the System Stack and be able to run the `stack.ls8` program

### Day 4: Get `call.ls8` running

- [ ] Implement the CALL and RET instructions
- [ ] Implement Subroutine Calls and be able to run the `call.ls8` program

### Stretch

- [ ] Add the timer interrupt to the LS-8 emulator
- [ ] Add the keyboard interrupt to the LS-8 emulator
- [ ] Write an LS-8 assembly program to draw a curved histogram on the screen
