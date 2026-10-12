# DirectX 8.1 SDK

`include/` and `lib/` of Microsoft's DirectX 8.1 SDK (Final Release, October 2001), unchanged.

[mafia-re](https://github.com/Marvisak/mafia-re) uses it as a git submodule: Steam's 2010 rebuild of Mafia's
`setup.exe` and `IJoy.dll` were linked with these exact libraries.

`.gitattributes` turns off line-ending conversion, so every file checks out byte for byte as the SDK installed it.
