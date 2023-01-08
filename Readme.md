# Blink Blue Pill with makefile
## Commands

- `all`: app.bin : to create binary output file .bin and and executable and linkable file .elf

- `make crt.o` to compile startup code

- `make main.o`: to compile main.c

-  `make app.elf` to create .elf output file

## Other ST-Link commands

- Get board info
  `st-info --probe`

- Read flash
	`st-flash read ./saved.img 0x8000000 0x1000`

- Write flash
	`st-flash write ./saved.img 0x8000000`

- Erase chip
	`st-flash erase`
