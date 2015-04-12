# rpi_gpio_go
1.
   cd /src/gpio
   gcc -c -fPIC -I . mem.c
   ar cr librpi_mem.a mem.o
   sudo cp librpi_mem.a /usr/lib
   sudo ldconfig

2. 
   cd ../../bin
   go build test

3. 
   sudo ./test

4. 
   Have Fun!
