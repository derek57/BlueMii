# BlueMii

BlueMii is a port of [Fullmetal5's BlueBomb exploit](https://github.com/Fullmetal5/bluebomb) for Broadcom's Bluetooth stack used in the Nintendo Wii, **to** the Nintendo Wii.

# How to build

Compatible requirements:

- devkitpro r47
- libOGC v2.13.0

After cloning, navigate to the source code folder and run "make"

# How to run

- Can be run from the Homebrew Channel (Copy folder "apps" from within folder "publish" after building)
- Requires a USB thumb stick or SD-Card connected to the target with a file called "boot.elf" in the root directory which should be the app / tool you might want this to run with

You should already know the target's System Menu version which can be found (with the target running at the main window of the System Menu) at the top right corner after hitting the buttons "Wii" (left corner at the bottom) -> "Wii Settings" (the button on the right)
