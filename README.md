This script will automate installing americancoind 1.6 on centos systems.  
This script will update yum, install the require dependencies, install  
the latest openssl openssl-1.0.1f, boost 1.55, berkeleydb 5.1.19 and  
finally americancoind 1.6. It will also get a base config and create a  
non priviledged user "american" to run the daemon under.  

Tested working on Centos 6.4 64 bit

Thanks to the folks liquidweb.com for the idea to create a more  
automagical version.

Source: http://www.liquidweb.com/kb/install-dogecoin-wallet-on-centos/

