VER=1

CONFDIR = /etc/aaa

BINPROGS = \
	aaa-build \
	aaa-build-cinnamon \
	aaa-build-all-gits \
	aaa-build-pupvm-prereqs

	

install:
	
	#install scripts
	install -m755 $(BINPROGS) $(DESTDIR)/usr/bin

uninstall:
	for f in $(BINPROGS); do $(RM) $(DESTDIR)/usr/bin/$$f; done
	

.PHONY: install uninstall
