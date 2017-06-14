# python-from-source
To build a copy of python

1. Download the tar file from  https://www.python.org/ftp/python/2.7.13/Python-2.7.13.tgz

2. Unzip it.
kj@KJ:~/Desktop/python-from-source$  tar -xvf Python-2.7.13.tgz

3. Inside the folder Python-2.7.13 there will be several folders such as Demo,Grammar,Include,Modules etc.

4. Navigate to the folder using cd and perform the following commands.
kj@KJ:~/Desktop/Python-2.7.13$ **./configure --enable-optimizations**
kj@KJ:~/Desktop/Python-2.7.13$  **make** 

5. Login as super user.
root@KJ:/home/kj/Desktop/Python-2.7.13# **make altinstall **
(To install Python not as the primary installation)

6. Check the python version in /usr/local/bin/python2.7.


