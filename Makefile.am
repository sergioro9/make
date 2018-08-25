# AUTOMAKE_OPTIONS: since we're not following the standard layout of a
# GNU project, we wwan automake that this is a foreign project:
AUTOMAKE_OPTIONS = foreign

# bin_SUFFIX: here SUFFIX tells automake what properties the file SUFFIX
# should have. Examples of primary suffixes: PROGRAM, SCRIPTS, DATA.
# The bin prefix tells automake that the file  listed here should be
# installed to the directory defined by the variable bindir. There are
# various directories defined for us by autotools: bindir, libdir,
# pkglibdir and we can also define our own

# bin_PROGRAMS: specify the binary file to be produced
bin_PROGRAMS = helloworld

# if you want to install some ruby script you could define rubydir:
#rubydir == $(datadir)/ruby
#ruby_DATA = my_script.rb my_other_script.rb

# since we’ve defined a PROGRAM, we need to tell automake where to find
# its source files.
helloworld_SOURCES = main.c
