                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ(2.59)
AC_INIT([libfftpack], [0.4], [patrick.nichols@digitalglobe.com])
AC_CONFIG_SRCDIR([./])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_HEADER([config.h])
AM_INIT_AUTOMAKE([1.9 foreign])

# Checks for programs.
AC_PROG_F77([intel gcc pgf90])
AC_PROG_INSTALL
AC_PROG_LIBTOOL
AC_PROG_LN_S
AC_LANG([Fortran])
# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_SUBST([AM_FCFLAGS])

AC_CONFIG_FILES([Makefile src/Makefile test/Makefile])
AC_OUTPUT

