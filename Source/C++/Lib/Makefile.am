# AM_CXXFLAGS = -I $(top_srcdir)/Source/

lib_LTLIBRARIES = libbento4.la

libbento4_la_LIBADD = $(top_builddir)/Source/C++/CApi/libb4capi.la \
					  $(top_builddir)/Source/C++/Core/libb4core.la \
					  $(top_builddir)/Source/C++/System/Posix/libb4posix.la \
					  $(top_builddir)/Source/C++/System/StdC/libb4stdc.la

libbento4_la_SOURCES = libbento4.cpp
