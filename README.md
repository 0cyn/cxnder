

<p align="center">
  nice to see you ~
  <br>
  <strong>
    <a href="https://twitter.com/arm64e">twitter</a> | 
    <a href="https://krit.me/">website</a> | 
    @_kat#0443 
  </strong>
</p>

---

[ktool](https://github.com/kritantadev/ktool) is a multi-purpose, 100% cross platform toolkit for MachO analysis and editing. Now includes a command line GUI.

It and all of its dependencies are pure python, so if you're working in a weird environment (Windows/Linux on Arm, etc.), it has absolutely no issues installing and running.

Things it can do:
* Dump ObjC headers, classes, .tbds (a la class-dump, tapi, otool, etc.)
* Insert/replace load commands, etc (a la optool, install-name-tool)
* Display a lot of valuable info about MachO binaries, including ones with mangled/corrupted load commands.

`pip3 install k2l`

---

[dragon](https://dragon.krit.me/) is a build system targeting iOS/macOS/etc, featuring lightning-fast build times. `pip3 install dragon`

[iBootLoader](https://github.com/KritantaDev/iBootLoader) is an IDA plugin for loading both 32 and 64 bit SecureROM/iBoot dumps into IDA Pro 7.0+ (including encrypted im4ps!)

---

potentially useful things:

[iOS Toolchain for Arm64 WSL/Arm64 Linux](https://github.com/KritantaDev/llvm-project-1/releases/tag/10.0.0-arm64)

[On-device NSLog Visible Overlay](https://github.com/KritantaDev/log-overlay)


