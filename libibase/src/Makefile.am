EXTRA_DIST = iheaders.h
lib_LTLIBRARIES = libibase.la
libibase_la_SOURCES = ibase.c \
ibase.h \
index.c \
bquery.c \
xquery.c \
summary.c \
utils/logger.h \
utils/logger.c \
utils/mutex.h \
utils/timer.h \
utils/mmtrie.c \
utils/mmtrie.h \
utils/db.h \
utils/db.c \
utils/xmm.h \
utils/xmm.c \
utils/mtree64.h \
utils/mtree64.c \
utils/zvbcode.c \
utils/zvbcode.h 

libibase_la_CPPFLAGS = -I utils -I html -D_FILE_OFFSET_BITS=64 -Wall
libibase_la_LDFLAGS = -lz -lm
include_HEADERS = ibase.h iheaders.h
