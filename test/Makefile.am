TESTS = test_filenames test_tags test_audio test_filesize

EXTRA_DIST = $(TESTS) funcs.sh flac

check_PROGRAMS = fpcompare
fpcompare_SOURCES = fpcompare.c
fpcompare_LDADD = -lchromaprint -lavcodec -lavformat -lavutil
