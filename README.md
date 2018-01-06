# gnuradio-doa
Samwhiting's gnuradio-doa ( https://github.com/samwhiting/gnuradio-doa ) GNU Radio OoT module, with a QT Compass Sink block from Ettus Research's gr-doa (https://github.com/EttusResearch/gr-doa) to provide graphical interfaces. 

Samwhiting's gnuradio-doa cannot be installed along with Ettus Research's gr-doa (module name conflict). This is one possible workaround to the problem. 

This OoT block is needed to run some of my GRC codes. 

To install the OoT module, clone this repository and install gr-doa following the standard OoT module installation process (cd gr-doa -> mkdir build -> cd build -> cmake .. -> make -> sudo make install).
