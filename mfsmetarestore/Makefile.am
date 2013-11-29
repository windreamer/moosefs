sbin_PROGRAMS=mfsmetarestore

AM_CPPFLAGS=-I$(top_srcdir)/mfsmaster -I$(top_srcdir)/mfscommon -DAPPNAME=mfsmetarestore -DMETARESTORE

mfsmetarestore_SOURCES=\
	main.c \
	../mfsmaster/merger.c ../mfsmaster/merger.h \
	../mfsmaster/restore.c ../mfsmaster/restore.h \
	../mfsmaster/filesystem.c ../mfsmaster/filesystem.h \
	../mfsmaster/chunks.c ../mfsmaster/chunks.h \
	../mfscommon/strerr.c ../mfscommon/strerr.h \
	../mfscommon/datapack.h ../mfscommon/massert.h ../mfscommon/slogger.h \
	../mfscommon/MFSCommunication.h
