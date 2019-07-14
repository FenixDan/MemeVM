# MemeVM
A small virtualizer for .NET which works together with ConfuserEx

You can download a compiled version of MemeVM from Appveyor:
[![Appveyor](https://ci.appveyor.com/api/projects/status/ys0vhl5y8wf39625?svg=true)](https://ci.appveyor.com/project/xsilent007/memevm/build/artifacts)

## Wtf is this???!

This projects takes your existing .NET MSIL code and "translates" it to instructions only our virtual machine will understand.

## Limitations

- Can be slow
- Lots of unimplemented OpCodes
- Branching is buggy
- No support for typed references
- No support for pointers

# Note

This is not meant to be used as a serious layer of Obfuscation, it was just an experiment.
Feel free to commit if you have any improvements
