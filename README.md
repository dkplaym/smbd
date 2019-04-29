# smbd



d40d5c6b2b4e70dabba13f49059ebf08  smbclient     
42da18aed5eda497abc6a3896d89f0ec  smbd     
4d01e96c24ad0e5fdfd31eb431a65946  smbpasswd        


06bbdb58a291abf69be9ee731c870e44  mount.cifs   
    
./mount.cifs //192.168.30.101/share /101 -o "username=XXXXXX,password=XXXXXXX"   



socket options = IPTOS_LOWDELAY SO_RCVBUF=131072 SO_SNDBUF=131072 TCP_NODELAY
min receivefile size = 2048
use sendfile = true
aio read size = 2048
aio write size = 2048
write cache size = 1024000
read raw = yes
write raw = yes
getwd cache = yes
oplocks = yes
max xmit = 32768
dead time = 15
large readwrite = yes
