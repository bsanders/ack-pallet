# @SI_Copyright@
# @SI_Copyright@

PKGROOT         = /opt/stack
ROLLROOT	= ../..
DEPENDS.FILES   = z

include $(STACKBUILD)/etc/CCRules.mk

build:

install::
	mkdir -p $(ROOT)/opt/stack/bin/
	$(INSTALL) -T -m 0755 z $(ROOT)/opt/stack/bin/z

