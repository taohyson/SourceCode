lib_LTLIBRARIES = libILU.la

libILU_la_SOURCES = ilu_alloc.c       ilu_internal.c  ilu_noise.c \
                    ilu_scale.c       ilu_error.c     ilu_main.c \
                    ilu_rotate.c      ilu_scaling.c   ilu_filter.c \
                    ilu_manip.c       ilu_scale2d.c   ilu_states.c \
                    ilu_filter_rcg.c  ilu_mipmap.c    ilu_scale3d.c \
                    ilu_utilities.c   ilu_region.c

AM_CFLAGS = @LIBILU_CFLAGS@

libILU_la_LDFLAGS = -no-undefined @VERSIONINFO@ \
                    -L$(top_srcdir)/src-IL/src/
libILU_la_LIBADD = -lIL

INCLUDES = -I$(top_srcdir)/include -I$(top_srcdir)/src-ILU/include
