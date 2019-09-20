ACLOCAL_AMFLAGS = -I m4

AM_CPPFLAGS =

AM_CFLAGS = -g -Wall -std=gnu11

AM_CXX = clang++
AM_CXXFLAGS = -g -Wall -std=c++14

## Debug info
if DEBUG
  AM_CFLAGS += -g3 -O0
  AM_CXXFLAGS += -g3 -O0
else
  AM_CFLAGS += -O2
  AM_CXXFLAGS += -O2
endif

AM_LDFLAGS =
LIBS = 

lib_LTLIBRARIES = ./.libs/libtinyecdhc.la
libtinyecdhc_la_SOURCES = ecdh.c
