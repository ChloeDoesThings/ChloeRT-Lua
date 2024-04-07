# ChloeRT-Lua
ChloeRT Lua is a port of ChloeRT's LuaU reversing features to Lua. This should work pretty well with certain Roblox executors like Krampus/RoExec (https://krampus.gg).

## Features
Luau Decompiler - Quite literally the same thing used in the actual ChloeRT but instead of being written in C#, its written to work in Lua. Basically how it works is it takes bytecode from a target script and then turns it into more readable Lua pseudocode.

Script Dumper - Gives you a wealth of information such as constants, upvalues, protos, argument count (for functions) and so on. This only works with LocalScripts, ModuleScripts, or Scripts that have their RunContext set to Client.
