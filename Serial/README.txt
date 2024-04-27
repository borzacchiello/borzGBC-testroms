Sample ROM with serial support.
Taken from: https://gbdev.gg8.se/wiki/articles/Serial_Communication_(Link_Cable)_Tutorial

To make the test succeed, your emulator needs to send:
- The value '0x02' when it first receives a '1' (i.e., as soon as SC=0x80, SB=1)
- The value '0xaa' on every other send
