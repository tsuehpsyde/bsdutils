bin_PROGRAMS = tail
man_MANS = tail.1

tail_SOURCES = forward.c misc.c read.c reverse.c tail.c
tail_CFLAGS = -I$(top_srcdir)/compat
tail_LDADD = $(top_builddir)/compat/libcompat.la
