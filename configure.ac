AC_INIT([libgsm0710], [1.3.0], [mlauer@vanille-media.de], [libgsm0710])
AC_CONFIG_SRCDIR([Makefile.am])
AC_CONFIG_HEADERS(config.h)
AM_INIT_AUTOMAKE([dist-bzip2 no-dist-gzip])
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

AC_PROG_CC
AC_PROG_CC_C_O
AC_DISABLE_STATIC
AC_PROG_LIBTOOL

AC_PREFIX_DEFAULT(/usr/local)

if (test "${CFLAGS}" = ""); then
	CFLAGS="-Wall -O2"
fi

AC_LANG_C
AC_PROG_INSTALL

AC_CONFIG_FILES([Makefile gsm0710-1.0.pc src/Makefile])
AC_OUTPUT
