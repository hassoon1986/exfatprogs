AM_CFLAGS = -Wall -Werror -Wunused-parameter \
	    -Wno-address-of-packed-member \
	    -include $(top_srcdir)/config.h -I$(top_srcdir)/include -fno-common
LIBS = -lm
mkfs_exfat_LDADD = $(top_builddir)/lib/libexfat.la

sbin_PROGRAMS = mkfs.exfat

mkfs_exfat_SOURCES = mkfs.c upcase.c

man_MANS = mkfs.exfat.8
