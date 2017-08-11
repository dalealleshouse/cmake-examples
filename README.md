# CMake Examples

A simple learning project to make myself understand CMake better. All code is
created using VIM on WSL.

# Vim, You Complete Me

You complete me requires a compilation database in order to provide intelligent
code help. The commands below generate a database and a symbolic link in the
root directory so YCM can find it.

```bash
mkdir build
cd build
cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=ON ..
cd ..
ln -s build/compile_commands.json
```

# Build

```bash
cd build
cmake ..
make
```
