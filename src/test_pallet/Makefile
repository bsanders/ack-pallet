# @SI_Copyright@
# @SI_Copyright@

PKGROOT         = /opt/stack
ROLLROOT	= ../..
DEPENDS.FILES   = ack

include $(STACKBUILD)/etc/CCRules.mk

build:

install::
	mkdir -p $(ROOT)/opt/stack/bin/
	$(INSTALL) -T -m 0755 ack $(ROOT)/opt/stack/bin/ack

