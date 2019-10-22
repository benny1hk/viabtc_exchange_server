TARGET  := readhistory.exe
INCS = -I ../network -I ../utils
LIBS = -L ../utils -lutils -L ../network -lnetwork -Wl,-Bstatic -ljansson -lmpdec -lmysqlclient -lz -lhiredis -Wl,-Bdynamic -lm -lpthread -ldl -lev
# libmysqlclient20 seems to link in libstdc++
LIBS += -lstdc++
include ../makefile.inc
