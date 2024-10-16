# emulated-USB-devices-on-bindgen
contribution rust lang and windows ecosystem

## some text to USB devices

uinput to have a userspace program virtualize input devices.

FUSE (Filesystem in Userspace) to have a userspace program provide a filesystem

The PTY (Pseudo TTY) system that powers terminal emulators by providing virtualized equivalents to the /dev/tty* modes PySerial connects to. (It basically is the important parts of the kernel's serial device driver reused. I recommend The TTY demystified for anyone dealing with serial on Linux.)


## How to?

1. If C is not working  

- [Debugging in Assembly Mode](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/debugging-in-assembly-mode)

2. If C is work

- [rust-bindgen](https://github.com/rust-lang/rust-bindgen)

3. If rust can  

- [Rust for Windows, and the windows crate](https://learn.microsoft.com/en-us/windows/dev-environment/rust/rust-for-windows)  


+a (Optimizing)
- https://www.amd.com/en/developer/aocc.html  



## ref  

- https://www.youtube.com/watch?app=desktop&v=GFHJMRj3PQc

- https://github.com/potto216/rust-usb-examples

- https://www.reddit.com/r/rust/comments/vz95n3/simulate_usb_device/
