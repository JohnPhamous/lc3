# LC-3 without running a VM

## Core Files
- LC3sim.jar is the LC-3 simulator, this requires [Java VM](https://java.com/en/download/) to be installed
- lc3os.asm is the LC-3 OS file

You always need to assemble assembly (.asm) files to object files (.obj)

## Assembling .asm to .obj
- Run LC3.sim
- Type `as lc3os.asm` into the console to assemble the code
- You will now have a file called lc3os.obj, this is your assembled code
- Type `load lc3os.obj` to load your assembled code, notice how the registers have changed
- To run your code completely, click ==continue==. If you'd like to go line by line, click ==step==.

## Commands
- `as <file>` assembles your code into machine language (think binary)
- `load <file>` loads your assembed file into the simulator
- `set <register> <value>` changes the value of a register to a value i.e. `set R5 #30`