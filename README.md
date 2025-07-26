# Chess in MIPS

This was a project for my undergraduate Computer Architecture course.

This repo contains the assembly file containing the program as well
as the project report.

## Dependencies

This project requires the [Mars](https://dpetersanderson.github.io/) IDE.

## Running

1. Open Mars.
2. File -> Open -> Open the `chess_in_mips.asm` file in this repo.
3. Open and set up the Bitmap Display
    1. Tools -> Bitmap Display. A new window should open.
    2. Set Unit Width in Pixels and Unit Height in Pixels to 4.
    3. Set Display Width in Pixels and Display Height in Pixels to 512.
    4. Set Base address for display to 0x10008000 ($gp)
    5. Press the Connect to MIPS button at the bottom.
4. Open and set up the Keyboard and Display MMIO Simulator.
    1. Tools -> Keyboard and Display MMIO Simulator. This will open 
       another window.
    2. Press the Connect to MIPS button at the bottom.
5. Back at the main window, press the Assemble the current file and clear breakpoints button (crossed hammer and wrench).
6. Press the play button right next to it.
7. The display should populate. In the Keyboard and Display MMIO
   Simulator window, type WASD into the bottom box to move the cursor.
   Press Space to interact.

## Demonstration

![Demonstration](https://github.com/Ottatop/chess-in-mips/blob/main/demonstration.mp4)
