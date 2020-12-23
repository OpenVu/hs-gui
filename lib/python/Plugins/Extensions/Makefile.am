installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = CutListEditor PicturePlayer MediaScanner MediaPlayer GraphMultiEPG SocketMMI DVDBurn hs742xVFD

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

if ENABLE_HS7429
SUBDIRS += hs742xVFD
endif

install_PYTHON =	\
	__init__.py
