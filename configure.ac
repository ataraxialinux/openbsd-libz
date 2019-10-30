AC_PREREQ([2.64])
AC_INIT([libz], [1.2.3p1], [ataraxialinux@protonmail.ch])
AC_CONFIG_AUX_DIR(aux-dist)
AM_INIT_AUTOMAKE
AM_SANITY_CHECK
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

AC_PROG_MAKE_SET
AC_GNU_SOURCE
AC_STDC_HEADERS
AC_PROG_CC([gcc])
AC_LANG(C)

CFLAGS="-fPIC"

AC_CONFIG_MACRO_DIR([m4])

LT_PREREQ([2.2])
LT_INIT([dlopen shared])

AC_CHECK_HEADERS(unistd.h stddef.h stdarg.h sys/types.h stdio.h sys/types.h string.h stand.h malloc.h)

AC_CONFIG_FILES([libz.pc])

AC_CONFIG_FILES([Makefile include/Makefile src/Makefile])

AC_OUTPUT
