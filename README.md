# Dec2c-Plug-in  
A simple to use Dex2c-Plug-in tool

## Prerequisites  
- Termux (Android) or Linux environment  
- Python 3.x 

## Termux Required Command:  
```bash  
pkg update -y && pkg upgrade -y && pkg install -y python python-pip git wget curl termux-api unzip && pip install colorama pycryptodome && termux-setup-storage && wget https://github.com/INCoderHook/Dex2c_Plug-in/archive/refs/heads/main.zip -O dex2c.zip && unzip -o dex2c.zip && rm -rf Dex2c_Plugin && mv -f Dex2c_Plug-in-main Dex2c_Plugin && rm dex2c.zip && cd Dex2c_Plugin && ls
