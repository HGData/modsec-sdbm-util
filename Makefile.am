ACLOCAL_AMFLAGS = -I m4

bin_PROGRAMS = modsec-sdbm-util

modsec_sdbm_util_SOURCES = modsec-sdbm-util.c

modsec_sdbm_util_CFLAGS = @APR_CFLAGS@ \
    @APU_CFLAGS@ -I/usr/include/hiredis/

modsec_sdbm_util_LDFLAGS = @APR_LDFLAGS@ \
    @APU_LDFLAGS@ -lhiredis

modsec_sdbm_util_LDADD = @APR_LDADD@ \
    @APU_LDADD@ -lhiredis
