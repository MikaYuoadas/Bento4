AC_PREREQ([2.67])
AC_INIT([bento4], [1.4.3.606], [anael.beutot@arkena.com])
AM_INIT_AUTOMAKE([foreign -Wall -Werror dist-bzip2])
# AC_CONFIG_HEADERS([config.h])
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

AM_PATH_PYTHON

# Checks for programs.
AC_PROG_CC
AC_PROG_CXX
AM_PROG_AR
AC_PROG_LIBTOOL
# AC_PROG_LEX
# AC_PROG_YACC
# AC_PROG_SED

# Checks for libraries.
# AC_CHECK_LIB([ev], [ev_default_loop], [EVLIB=-lev])
# AC_SUBST([EVLIB])

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
LT_INIT

AC_CONFIG_MACRO_DIR([m4])

AC_CONFIG_FILES([
Makefile
Source/C++/Apps/Aac2Mp4/Makefile
Source/C++/Apps/FixAacSampleDescription/Makefile
Source/C++/Apps/Makefile
Source/C++/Apps/Mp42Aac/Makefile
Source/C++/Apps/Mp42Avc/Makefile
Source/C++/Apps/Mp42Hevc/Makefile
Source/C++/Apps/Mp42Hls/Makefile
Source/C++/Apps/Mp42Ts/Makefile
Source/C++/Apps/Mp4AudioClip/Makefile
Source/C++/Apps/Mp4Compact/Makefile
Source/C++/Apps/Mp4DcfPackager/Makefile
Source/C++/Apps/Mp4Decrypt/Makefile
Source/C++/Apps/Mp4Dump/Makefile
Source/C++/Apps/Mp4Edit/Makefile
Source/C++/Apps/Mp4Encrypt/Makefile
Source/C++/Apps/Mp4Extract/Makefile
Source/C++/Apps/Mp4Fragment/Makefile
Source/C++/Apps/Mp4Info/Makefile
Source/C++/Apps/Mp4Mux/Makefile
Source/C++/Apps/Mp4Pssh/Makefile
Source/C++/Apps/Mp4RtpHintInfo/Makefile
Source/C++/Apps/Mp4Split/Makefile
Source/C++/Apps/Mp4Tag/Makefile
Source/C++/CApi/Makefile
Source/C++/Codecs/Makefile
Source/C++/Core/Makefile
Source/C++/Crypto/Makefile
Source/C++/Lib/Makefile
Source/C++/Makefile
Source/C++/MetaData/Makefile
Source/C++/System/Makefile
Source/C++/System/Posix/Makefile
Source/C++/System/StdC/Makefile
Source/Makefile
Source/Python/Makefile
Source/Python/bento4/Makefile
Source/Python/b4/Makefile
Source/Python/utils/Makefile
                 ])

AC_OUTPUT
