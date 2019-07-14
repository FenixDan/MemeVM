# MemeVM
A small virtualizer for .NET which works together with ConfuserEx

##### If you want to try MemeVM, you can download an already compiled version from Appveyor:
[![Appveyor](https://ci.appveyor.com/api/projects/status/ys0vhl5y8wf39625?svg=true)](https://ci.appveyor.com/project/xsilent007/memevm/build/artifacts)

## Wtf is this???!

This projects takes your existing .NET MSIL code and "translates" it to instructions only our virtual machine will understand.

## Limitations

- A ton of unimplemented opcodes
- No support for any kind of exception handlers
- No support for generics
- No support for pointers
- No support for typed references
- Branching can be quite broken

# Note

This is not meant to be used as a serious layer of Obfuscation, it was just an experiment.
Feel free to make a PR if you have any improvements
