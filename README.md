# mysite
this is sample wep application being created by django (python framemwork).   
## **Reference**  
<https://djangogirlsjapan.gitbooks.io/workshop_tutorialjp/content/>

## Environment
* AmazonLinux1
* Apache  2.2.34
* python  3.6.4
* django  2.0.2

## Additional Package
* httpd-devel  
`yum install httpd-devel`
* mod_wsgi 4.5.14  
`wget https://github.com/GrahamDumpleton/mod_wsgi/archive/4.5.14.tar.gz`  
`tar -zxvf 4.5.14.tar.gz`  
`cd mod_wsgi-4.5.14/`  
`./configure --with-python=/usr/bin/.pyenv/versions/3.6.4/bin/python`  
`make`  
**↑error happens!! try to recompile**    
`CONFIGURE_OPTS="--enable-shared" CFLAGS="-fPIC" pyenv install 3.6.4`  
`make clean`  
`./configure CFLAGS=-fPIC --enable-shared`  
`make`  
`sudo make install`  
  
