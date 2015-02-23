AM_CXXFLAGS = -I$(top_srcdir)/Source/C++/Core -I$(top_srcdir)/Source/C++/MetaData -I$(top_srcdir)/Source/C++/Codecs -I$(top_srcdir)/Source/C++/Crypto

bin_PROGRAMS = mp4pssh

mp4pssh_SOURCES = Mp4Pssh.cpp
mp4pssh_LDADD = $(top_builddir)/Source/C++/Core/libb4core.la $(top_builddir)/Source/C++/MetaData/libb4metadata.la $(top_builddir)/Source/C++/Codecs/libb4codecs.la $(top_builddir)/Source/C++/System/Posix/libb4posix.la $(top_builddir)/Source/C++/System/StdC/libb4stdc.la $(top_builddir)/Source/C++/CApi/libb4capi.la