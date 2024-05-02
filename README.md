# Yes, it's a simple hello world in assembly
## Compile exe
  - nasm -f win64 hello.asm -o hello2.obj
  - golink /entry _start /console hello2.obj kernel32.dll

  [nasm](https://www.nasm.us/pub/nasm/releasebuilds/2.16.03/win64/)
  [golink](http://www.godevtool.com/#linker)
