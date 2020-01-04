# op-tools_ubuntu16.04
Install script for openpilot-tools for Ubuntu 16.04
Makes it easier to get up and going with openpilot-tools.
During installation watch out for erros. You'll be prompted to press enter on every apt install.

```bash
git clone https://github.com/danielzmod/op-tools_ubuntu_16.04.git op_tools_installer
cd op_tools_installer
./0_install_pyenv.sh
```

```bash
./1_install_op-tools_ubuntu16.04.sh
```

When rebooting or starting a new terminal dont forget to activate the virtual environment by doing 
```bash
cd openpilot
pipenv shell # Activate virtual environment
```
