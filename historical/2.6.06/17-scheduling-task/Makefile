## Makefile for linux kernel module 2.6.18
##
##

obj-m += helloscheduling.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean

