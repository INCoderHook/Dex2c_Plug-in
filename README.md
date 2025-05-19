# Dex2c-Plug-in  
A simple to use Dex2c-Plug-in tool

## Screenshot

![Dex2c Plugin Image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiA57VOY-wGhLYEuC6ZaryYd9g-mc5uU2Z4iXYh5svJIueY6e44z8Zwq5Rk83KWJljAlE42jt6KG-UMYOwtPGJqoXxvk1sNC337zxDa8LA17kDsigdhbhqu_moY15gnX52IzgvbKWgXC-uSHH2JcuobToNru3RKfR5qHVwqhXjwZpoVwH6E_Mol6lHI2heX/s1600/1000806468.jpg)

* ![Python][Python-Badge]
* [![Androguard][Androguard-Badge]][Androguard_Repository] 
- Python 3.x 

## Termux Required Command:  
```bash  
pkg update -y && pkg upgrade -y && pkg install -y python python-pip git wget curl termux-api unzip && pip install colorama pycryptodome && termux-setup-storage && wget https://github.com/INCoderHook/Dex2c_Plug-in/archive/refs/heads/main.zip -O dex2c.zip && unzip -o dex2c.zip && rm -rf Dex2c_Plugin && mv -f Dex2c_Plug-in-main Dex2c_Plugin && rm dex2c.zip && cd Dex2c_Plugin && ls
