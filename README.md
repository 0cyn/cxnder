

<p align="center">
  nice to see you ~
  <br>
  <strong>
    <a href="https://twitter.com/arm64e">twitter</a> | 
    <a href="https://cynder.me/">website</a> | 
    @cynder#0443 
  </strong>
</p>

---

### current projects:

[ktool](https://github.com/cxnder/ktool) is a multi-purpose, 100% cross platform toolkit for MachO analysis and editing. Now includes a command line GUI.

Things it can do:
* Browse and/or Hexdump Load Commands, Segments, etc via the GUI
* Dump/Browse ObjC headers, classes, .tbds (a la class-dump, tapi, otool, etc.)
* Insert/replace load commands, etc (a la optool, install-name-tool)
* Display a lot of valuable info about MachO binaries, including ones with mangled/corrupted load commands.
* Plenty more

It's also a public, usable, python library, meaning you can go absolutely wild with it.

I've used it to create [sdk-builder](https://github.com/cxnder/sdk-builder) which automatically generates all of the iOS Header dumps for https://headers.cynder.me/ using github actions.

`pip3 install k2l`

[dragon](https://dragon.krit.me/) is a build system targeting iOS/macOS/etc, featuring lightning-fast build times. `pip3 install dragon`

[iBootLoader](https://github.com/cxnder/iBootLoader) is an IDA plugin for loading both 32 and 64 bit SecureROM/iBoot dumps into IDA Pro 7.0+ (including encrypted im4ps!)

---

potentially useful things:

[iOS Toolchain for Arm64 WSL/Arm64 Linux](https://github.com/cxnder/llvm-project-1/releases/tag/10.0.0-arm64)

[On-device NSLog Visible Overlay](https://github.com/cxnder/log-overlay)


