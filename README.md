# CMake Examples

A simple learning project to make myself understand CMake better. All code is
created using VIM on WSL.

# You Complete Me

You complete me requires a complication database in order to provide
intelligent code help. These command will generate the database. This assumes
you are starting in the root project directory

```bash
mkdir build
cd build
cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=ON ..
cd ..
# This creates a symbolic link to the complication database
ln -s build/compile_commands.json
```

# Build

```bash
cd build
cmake ..
make
```
