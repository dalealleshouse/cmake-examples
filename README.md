# CMake Examples

A simple learning project to make myself understand CMake better. All code is
created using VIM on WSL.

# Vim, You Complete Me

You complete me requires a complication database in order to provide
intelligent code help. These commands will generate the database and a symbolic
link in the root directory to the database.

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
