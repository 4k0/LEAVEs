
# LEAVEs (2005)

LEAVEs, a Visual Novel from 2005, it's the first and last game from [BEKKO.net](https://vndb.org/p576), made using the Visual Novel Engine NScripter.

## What I used to decompile it?

###  [NSAOut](http://nscripter.insani.org/downloads/nsaout.zip) 
- Author: alamone
-  Platform: Win32 + MinGW source
- Size: 144KB
- Contents: extracts the resources from arc*.nsa.

## Documentation

[*NScripter API Reference](https://kaisernet.org/onscripter/api/NScrAPI-framed.html)

## Wanna compile it back?
### [NScripter SDK](http://nscripter.insani.org/downloads/nscr_sdk.zip)
- Author: Naoki Takahashi
- Platform: Win32
- Size: 535KB
- Contents:
  
```nscr.exe -- mainline NScripter runtime binary. Included only for completeness' sake. Do not use in your translation project, as it does not support 1-byte characters.```

```nscmake.exe -- takes your script file (0.txt) and converts it into compiled bytecode for the runtime binary (nscript.dat).```

```nsaarc.exe -- archives your resources into arc*.nsa format for distribution.```

```bw2aconv.exe -- simple alpha mask generation program.```
