# Conan Example

Details [here](http://conanio.readthedocs.io/en/latest/index.html)

# Build

```bash
mkdir build && cd build
conan install ..
cmake ..
make
```

# Install Conan

```bash
python3 -m venv ~/py_venv/conan
source ~/py_venv/conan/bin/activate
pip install conan
```

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

