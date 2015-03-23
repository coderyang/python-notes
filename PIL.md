#Install PIL in Ubuntu correctly

first, if you have preinstall PIL in your system:
        
        pip uninstall PIL

and then:
        
        sudo apt-get install libjpeg-dev
        pip install -I pillow

at last, for ubuntu x64:
        
        sudo ln -s /usr/lib/x86_64-linux-gnu/libjpeg.so /usr/lib
        sudo ln -s /usr/lib/x86_64-linux-gnu/libfreetype.so /usr/lib
        sudo ln -s /usr/lib/x86_64-linux-gnu/libz.so /usr/lib
