# Generated automatically from Makefile.in by configure.
# Makefile.in generated automatically by automake 1.4 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.


SHELL = /bin/sh

srcdir = .
top_srcdir = ..
prefix = /usr/local/zebra
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/zebra
pkglibdir = $(libdir)/zebra
pkgincludedir = $(includedir)/zebra

top_builddir = ..

ACLOCAL = aclocal
AUTOCONF = autoconf
AUTOMAKE = automake
AUTOHEADER = autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL} $(AM_INSTALL_PROGRAM_FLAGS)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL_PROGRAM}
transform = s,x,x,

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
host_alias = i686-pc-linux-gnu
host_triplet = i686-pc-linux-gnu
AR = ar
BGPD = 
CC = gcc
CPP = gcc -E
CURSES = 
IF_METHOD = if_netlink.o
IF_PROC = if_proc.o
INCLUDES = 
IPFORWARD = ipforward_proc.o
KERNEL_METHOD = 
LIBPAM = 
LIB_IPV6 = 
LIB_REGEX = 
MAKEINFO = makeinfo
MULTIPATH_NUM = 1
OSPF6D = 
OSPFD = 
OTHER_METHOD = 
PACKAGE = zebra
RANLIB = ranlib
RIPD = ripd
RIPNGD = 
RTREAD_METHOD = rtread_netlink.o
RT_METHOD = rt_netlink.o
VERSION = 0.92a
VTYSH = 
ZEBRA = zebra

info_TEXINFOS = zebra.texi

zebra_TEXINFOS = appendix.texi basic.texi bgpd.texi filter.texi install.texi 	ipv6.texi kernel.texi main.texi ospf6d.texi ospfd.texi overview.texi 	protocol.texi ripd.texi ripngd.texi routemap.texi snmp.texi vtysh.texi


man_MANS = vtysh.1 bgpd.8 ospf6d.8 ospfd.8 ripd.8 ripngd.8 zebra.8

EXTRA_DIST = BGP-TypeCode draft-zebra-00.ms draft-zebra-00.txt $(man_MANS) 
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = ../config.h
CONFIG_CLEAN_FILES = 
TEXI2DVI = texi2dvi
INFO_DEPS = zebra.info
DVIS = zebra.dvi
TEXINFOS = zebra.texi
man1dir = $(mandir)/man1
man8dir = $(mandir)/man8
MANS = $(man_MANS)

NROFF = nroff
DIST_COMMON =  $(zebra_TEXINFOS) ChangeLog Makefile.am Makefile.in \
texinfo.tex


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = tar
GZIP_ENV = --best
all: all-redirect
.SUFFIXES:
.SUFFIXES: .dvi .info .ps .texi .texinfo .txi
$(srcdir)/Makefile.in: Makefile.am $(top_srcdir)/configure.in $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --foreign --include-deps doc/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status


zebra.info: zebra.texi $(zebra_TEXINFOS)
zebra.dvi: zebra.texi $(zebra_TEXINFOS)


DVIPS = dvips

.texi.info:
	@cd $(srcdir) && rm -f $@ $@-[0-9] $@-[0-9][0-9]
	cd $(srcdir) \
	  && $(MAKEINFO) `echo $< | sed 's,.*/,,'`

.texi.dvi:
	TEXINPUTS=.:$$TEXINPUTS \
	  MAKEINFO='$(MAKEINFO) -I $(srcdir)' $(TEXI2DVI) $<

.texi:
	@cd $(srcdir) && rm -f $@ $@-[0-9] $@-[0-9][0-9]
	cd $(srcdir) \
	  && $(MAKEINFO) `echo $< | sed 's,.*/,,'`

.texinfo.info:
	@cd $(srcdir) && rm -f $@ $@-[0-9] $@-[0-9][0-9]
	cd $(srcdir) \
	  && $(MAKEINFO) `echo $< | sed 's,.*/,,'`

.texinfo:
	@cd $(srcdir) && rm -f $@ $@-[0-9] $@-[0-9][0-9]
	cd $(srcdir) \
	  && $(MAKEINFO) `echo $< | sed 's,.*/,,'`

.texinfo.dvi:
	TEXINPUTS=.:$$TEXINPUTS \
	  MAKEINFO='$(MAKEINFO) -I $(srcdir)' $(TEXI2DVI) $<

.txi.info:
	@cd $(srcdir) && rm -f $@ $@-[0-9] $@-[0-9][0-9]
	cd $(srcdir) \
	  && $(MAKEINFO) `echo $< | sed 's,.*/,,'`

.txi.dvi:
	TEXINPUTS=.:$$TEXINPUTS \
	  MAKEINFO='$(MAKEINFO) -I $(srcdir)' $(TEXI2DVI) $<

.txi:
	@cd $(srcdir) && rm -f $@ $@-[0-9] $@-[0-9][0-9]
	cd $(srcdir) \
	  && $(MAKEINFO) `echo $< | sed 's,.*/,,'`
.dvi.ps:
	$(DVIPS) $< -o $@

install-info-am: $(INFO_DEPS)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(infodir)
	@list='$(INFO_DEPS)'; \
	for file in $$list; do \
	  d=$(srcdir); \
	  for ifile in `cd $$d && echo $$file $$file-[0-9] $$file-[0-9][0-9]`; do \
	    if test -f $$d/$$ifile; then \
	      echo " $(INSTALL_DATA) $$d/$$ifile $(DESTDIR)$(infodir)/$$ifile"; \
	      $(INSTALL_DATA) $$d/$$ifile $(DESTDIR)$(infodir)/$$ifile; \
	    else : ; fi; \
	  done; \
	done
	@$(POST_INSTALL)
	@if $(SHELL) -c 'install-info --version | sed 1q | fgrep -s -v -i debian' >/dev/null 2>&1; then \
	  list='$(INFO_DEPS)'; \
	  for file in $$list; do \
	    echo " install-info --info-dir=$(DESTDIR)$(infodir) $(DESTDIR)$(infodir)/$$file";\
	    install-info --info-dir=$(DESTDIR)$(infodir) $(DESTDIR)$(infodir)/$$file || :;\
	  done; \
	else : ; fi

uninstall-info:
	$(PRE_UNINSTALL)
	@if $(SHELL) -c 'install-info --version | sed 1q | fgrep -s -v -i debian' >/dev/null 2>&1; then \
	  ii=yes; \
	else ii=; fi; \
	list='$(INFO_DEPS)'; \
	for file in $$list; do \
	  test -z "$ii" \
	    || install-info --info-dir=$(DESTDIR)$(infodir) --remove $$file; \
	done
	@$(NORMAL_UNINSTALL)
	list='$(INFO_DEPS)'; \
	for file in $$list; do \
	  (cd $(DESTDIR)$(infodir) && rm -f $$file $$file-[0-9] $$file-[0-9][0-9]); \
	done

dist-info: $(INFO_DEPS)
	list='$(INFO_DEPS)'; \
	for base in $$list; do \
	  d=$(srcdir); \
	  for file in `cd $$d && eval echo $$base*`; do \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file; \
	  done; \
	done

mostlyclean-aminfo:
	-rm -f zebra.aux zebra.cp zebra.cps zebra.dvi zebra.fn zebra.fns \
	  zebra.ky zebra.kys zebra.ps zebra.log zebra.pg zebra.toc \
	  zebra.tp zebra.tps zebra.vr zebra.vrs zebra.op zebra.tr \
	  zebra.cv zebra.cn

clean-aminfo:

distclean-aminfo:

maintainer-clean-aminfo:
	cd $(srcdir) && for i in $(INFO_DEPS); do \
	  rm -f $$i; \
	  if test "`echo $$i-[0-9]*`" != "$$i-[0-9]*"; then \
	    rm -f $$i-[0-9]*; \
	  fi; \
	done

install-man1:
	$(mkinstalldirs) $(DESTDIR)$(man1dir)
	@list='$(man1_MANS)'; \
	l2='$(man_MANS)'; for i in $$l2; do \
	  case "$$i" in \
	    *.1*) list="$$list $$i" ;; \
	  esac; \
	done; \
	for i in $$list; do \
	  if test -f $(srcdir)/$$i; then file=$(srcdir)/$$i; \
	  else file=$$i; fi; \
	  ext=`echo $$i | sed -e 's/^.*\\.//'`; \
	  inst=`echo $$i | sed -e 's/\\.[0-9a-z]*$$//'`; \
	  inst=`echo $$inst | sed '$(transform)'`.$$ext; \
	  echo " $(INSTALL_DATA) $$file $(DESTDIR)$(man1dir)/$$inst"; \
	  $(INSTALL_DATA) $$file $(DESTDIR)$(man1dir)/$$inst; \
	done

uninstall-man1:
	@list='$(man1_MANS)'; \
	l2='$(man_MANS)'; for i in $$l2; do \
	  case "$$i" in \
	    *.1*) list="$$list $$i" ;; \
	  esac; \
	done; \
	for i in $$list; do \
	  ext=`echo $$i | sed -e 's/^.*\\.//'`; \
	  inst=`echo $$i | sed -e 's/\\.[0-9a-z]*$$//'`; \
	  inst=`echo $$inst | sed '$(transform)'`.$$ext; \
	  echo " rm -f $(DESTDIR)$(man1dir)/$$inst"; \
	  rm -f $(DESTDIR)$(man1dir)/$$inst; \
	done

install-man8:
	$(mkinstalldirs) $(DESTDIR)$(man8dir)
	@list='$(man8_MANS)'; \
	l2='$(man_MANS)'; for i in $$l2; do \
	  case "$$i" in \
	    *.8*) list="$$list $$i" ;; \
	  esac; \
	done; \
	for i in $$list; do \
	  if test -f $(srcdir)/$$i; then file=$(srcdir)/$$i; \
	  else file=$$i; fi; \
	  ext=`echo $$i | sed -e 's/^.*\\.//'`; \
	  inst=`echo $$i | sed -e 's/\\.[0-9a-z]*$$//'`; \
	  inst=`echo $$inst | sed '$(transform)'`.$$ext; \
	  echo " $(INSTALL_DATA) $$file $(DESTDIR)$(man8dir)/$$inst"; \
	  $(INSTALL_DATA) $$file $(DESTDIR)$(man8dir)/$$inst; \
	done

uninstall-man8:
	@list='$(man8_MANS)'; \
	l2='$(man_MANS)'; for i in $$l2; do \
	  case "$$i" in \
	    *.8*) list="$$list $$i" ;; \
	  esac; \
	done; \
	for i in $$list; do \
	  ext=`echo $$i | sed -e 's/^.*\\.//'`; \
	  inst=`echo $$i | sed -e 's/\\.[0-9a-z]*$$//'`; \
	  inst=`echo $$inst | sed '$(transform)'`.$$ext; \
	  echo " rm -f $(DESTDIR)$(man8dir)/$$inst"; \
	  rm -f $(DESTDIR)$(man8dir)/$$inst; \
	done
install-man: $(MANS)
	@$(NORMAL_INSTALL)
	$(MAKE) $(AM_MAKEFLAGS) install-man1 install-man8
uninstall-man:
	@$(NORMAL_UNINSTALL)
	$(MAKE) $(AM_MAKEFLAGS) uninstall-man1 uninstall-man8
tags: TAGS
TAGS:


distdir = $(top_builddir)/$(PACKAGE)-$(VERSION)/$(subdir)

subdir = doc

distdir: $(DISTFILES)
	@for file in $(DISTFILES); do \
	  d=$(srcdir); \
	  if test -d $$d/$$file; then \
	    cp -pr $$/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done
	$(MAKE) $(AM_MAKEFLAGS) top_distdir="$(top_distdir)" distdir="$(distdir)" dist-info
info-am: $(INFO_DEPS)
info: info-am
dvi-am: $(DVIS)
dvi: dvi-am
check-am: all-am
check: check-am
installcheck-am:
installcheck: installcheck-am
install-exec-am:
install-exec: install-exec-am

install-data-am: install-info-am install-man
install-data: install-data-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-am
uninstall-am: uninstall-info uninstall-man
uninstall: uninstall-am
all-am: Makefile $(INFO_DEPS) $(MANS)
all-redirect: all-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs:
	$(mkinstalldirs)  $(DESTDIR)$(infodir) $(DESTDIR)$(mandir)/man1 \
		$(DESTDIR)$(mandir)/man8


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
mostlyclean-am:  mostlyclean-aminfo mostlyclean-generic

mostlyclean: mostlyclean-am

clean-am:  clean-aminfo clean-generic mostlyclean-am

clean: clean-am

distclean-am:  distclean-aminfo distclean-generic clean-am

distclean: distclean-am

maintainer-clean-am:  maintainer-clean-aminfo maintainer-clean-generic \
		distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-am

.PHONY: install-info-am uninstall-info mostlyclean-aminfo \
distclean-aminfo clean-aminfo maintainer-clean-aminfo install-man1 \
uninstall-man1 install-man8 uninstall-man8 install-man uninstall-man \
tags distdir info-am info dvi-am dvi check check-am installcheck-am \
installcheck install-exec-am install-exec install-data-am install-data \
install-am install uninstall-am uninstall all-redirect all-am all \
installdirs mostlyclean-generic distclean-generic clean-generic \
maintainer-clean-generic clean mostlyclean distclean maintainer-clean


draft-zebra-00.txt:
	groff -T ascii -ms draft-zebra-00.ms > draft-zebra-00.txt

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
