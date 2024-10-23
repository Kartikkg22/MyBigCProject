AC_PREREQ([2.69])
AC_INIT([MyBigCProject], [1.0], [maintainer@example.com])
AC_CONFIG_SRCDIR([src/main.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs
AC_PROG_CC

# Checks for libraries (e.g., math library)
AC_CHECK_LIB([m], [main], [], [AC_MSG_ERROR([libm (math library) is required!])])

# Automake initialization
AM_INIT_AUTOMAKE([foreign -Wall -Werror])

# Generate Makefile in these directories
AC_CONFIG_FILES([Makefile
                 src/Makefile
                 tests/Makefile])

AC_OUTPUT
