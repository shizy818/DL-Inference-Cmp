# Automatically generated by dlc-backend-jni.sh
CC	= gcc
CFLAGS	= -I./include -I./include/linux -Wall -fPIC -O3 -march=native
OBJDIR	= ../obj

all: \
	$(OBJDIR)/dlcjni.o \
	$(OBJDIR)/library.o

$(OBJDIR)/dlcjni.o:dlcjni.c 
	$(CC) $(CFLAGS) -I/Library/Java/JavaVirtualMachines/jdk1.8.0_112.jdk/Contents/Home/include -c -o $@ $<

$(OBJDIR)/library.o:library.c library.h
	$(CC) $(CFLAGS) -c -o $@ $<

clean:
