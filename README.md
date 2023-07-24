

# Functions
Alows you to transfer native tokens from one network to another with automatic conversion
via merkly gas refuel. All transactions go via L0

1. Add your private keys to the private_keys.txt file
2. in the main.py file, at the very beginning, select the destination network and the network from which you are transferring. and also indicate how much you want to get a native token in the destination network
3. and run.

# Install: Linux/Mac

Linux/Mac
```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

python main.py
```
Windows 
pip install virtualenv
virtualenv .venv
.venv\Scripts\activate
pip install -r requirements.txt

python main.py
```


