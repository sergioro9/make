# AC_INIT(program, version, aughor): initialise autoconf
AC_INIT([helloworld], [0.1], [george@thoughtbot.com])

# AM_INIT_: specify autotool to be used (automake in this case)
AM_INIT_AUTOMAKE

# AC_PROG_: specify dependencies. In this case only a C compiler
AC_PROG_CC

# AC_PATH_: specify dependencies. Look for a given program on PATH
#AC_PATH_PROG

# AC_CONFIG_FILES: find a file called Makefile.in, substitute placeholders
# like @PACKAGE_VERSION@ with values like 0.1, and write the results to Makefile
AC_CONFIG_FILES([Makefile])

# AC_OUTPUT: output the script
AC_OUTPUT
