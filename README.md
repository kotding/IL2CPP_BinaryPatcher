LibIl2Cpp Batch Patcher

A C# desktop application for batch patching code into libil2cpp.so with a user-friendly interface.

Features

Batch patch multiple offsets at once

Supports ARMv7 and ARM64

40+ preset codes for ARMv7, 30+ for ARM64

Custom hex input

Automatic backup before saving

Easy-to-use WinForms UI

Usage

Select architecture (ARMv7 or ARM64)

Open libil2cpp.so

Add patches (hex offset + preset or custom hex)

Add/Delete rows as needed

Click Patch All, then Save File

Preset Codes

ARMv7: Booleans, common numbers, large values, floats, NOP, speed hack, freeze

ARM64: Booleans, numbers, large values, floats/doubles, NOP, return, branch

Hex Format

Offset: 1A2B3C or 0x1A2B3C

Hex: 48 65 6C 6C 6F or 4865616C6C6F

Build
dotnet build
dotnet run --project LibIl2CppPatcher

Requirements

.NET 8.0 (Windows)

Windows Forms

Notes

Backups are created automatically (.backup)

Double-check offsets and bytes before patching

Supports files up to 100MB

License

MIT License
