dnl Process this file with autoconf to produce a configure script

AC_PREREQ(2.69)

AC_INIT([obstack], [1.1], [pullmoll@t-online.de])

AM_INIT_AUTOMAKE([1.15])
AC_CONFIG_MACRO_DIR([m4])

AC_PROG_CC
AC_PROG_LIBTOOL

AC_CHECK_HEADERS(stddef.h stdio.h stdint.h inttypes.h)

PKG_INSTALLDIR

AC_CONFIG_FILES([Makefile musl-obstack.pc])
AC_OUTPUT
