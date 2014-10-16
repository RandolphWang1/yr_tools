NOTE: build with arm-linux-gcc 2.95.3 from huanhong


1. How to build md5sum.
	a. tar xvf coreutils-6.9.tar.gz
	b. ./configure --host=arm-linux
	c. make 
		In this step, error will happened when remove.c is built. Ignore the error and do the next step.
	d. cd src
	e. make md5sum
		The md5sum will be generated.
2. How to build curl
	a. tar xvf curl-7.38.0.tar.bz2
	b. ./configure --disable-shared --host=arm-linux
	c. make
		curl will be generated at src/curl

