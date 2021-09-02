1. Place the toolchain somewhere on your computer(eg:/usr/local/):

   mv ~/Downloads/gcc-arm-none-eabi-10-2020-q4-major /usr/local/

2. Open the bash_profile on you computer(simply on your terminal enter "open ~/.bash_profile") and copy-paste the following line into your bash_profile file.

   export PATH="$PATH:/usr/local/gcc-arm-none-eabi-10-2020-q4-major/bin/"
