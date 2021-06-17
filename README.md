error: libcrypto.os.4
use latest libcripto in your system and make a link as that name

- install or build/install openssl
- find / -name 'libcripto*' 2> /dev/null
#put your location in origin file of course..
- ln -s /usr/lib/i386-linux-gnu/libcrypto.so.1.1 /usr/lib/libcrypto.so.4
- restart gns3

error: key
- execute the python script above
- sudo nano .iourc
- paste as the file print says

error: permision denied in .iourc
- sudo chown $user -R .iourc
