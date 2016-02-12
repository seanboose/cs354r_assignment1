ACLOCAL_AMFLAGS= -I m4
noinst_HEADERS= MinimalOgre.cpp

bin_PROGRAMS= OgreApp
OgreApp_CPPFLAGS= -I$(top_srcdir)
OgreApp_SOURCES= MinimalOgre.cpp
OgreApp_CXXFLAGS= $(OGRE_CFLAGS) $(OIS_CFLAGS)
OgreApp_LDADD= $(OGRE_LIBS) $(OIS_LIBS)
OgreApp_LDFLAGS= -lOgreOverlay -lboost_system

EXTRA_DIST= buildit makeit
AUTOMAKE_OPTIONS= foreign
