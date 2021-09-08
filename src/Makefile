PC=fpc
CFLAGS=-O2

pcprint: pcprint.pas ccode.pas cprint.o
	fpc -O2 -B -Mobjfpc -g -gl pcprint

cprint.o:cprint.c

clean:
	rm -f *\.ppu *\.o

distclean:
	rm -f *\.ppu *\.o
	rm -f pcprint
