# python-from-source
To build a copy of python <br />

1. Download the tar file from  https://www.python.org/ftp/python/2.7.13/Python-2.7.13.tgz  <br />

2. Unzip it using the following command. <br />
**tar -xvf Python-2.7.13.tgz**

3. Inside the folder Python-2.7.13 there will be several folders such as Demo,Grammar,Include,Modules etc. <br />

4. Navigate to the folder using cd and perform the following commands. <br />
 **./configure --enable-optimizations**   <br />
 **make** <br />

5. Login as super user. <br />
 **make altinstall ** <br />
(To install Python not as the primary installation) <br />

6. Check the python version in /usr/local/bin/python2.7.


