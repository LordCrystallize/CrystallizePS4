A kernel-level exploit for PlayStation 4 firmware versions 13.52 and 14.00, executed directly through the console’s built-in web browser. It provides kernel read/write access, root-level privileges (UID 0), RWX memory mapping, and syscall 11 as a kexec entry point, allowing standard payloads to run just as they would with other kernel exploits.

This browser-based implementation also supports execution through a Lua payload within a game process.
