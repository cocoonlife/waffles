AC_INIT([waffles], [0.0], [paul.brook@cocoon.life])
AM_MAINTAINER_MODE
AM_INIT_AUTOMAKE()
AC_PROG_CXX
AC_PROG_CC
AC_PROG_RANLIB

WAFFLES_LDADD="-L../GClasses -lGClasses -lpthread"
AC_SUBST([WAFFLES_LDADD])

AC_CONFIG_HEADER([config.h])
AC_CONFIG_FILES([Makefile 
	GClasses/Makefile
       	wizard/Makefile
       	audio/Makefile
       	cluster/Makefile
	dimred/Makefile
	learn/Makefile
	plot/Makefile
	recommend/Makefile
	sparse/Makefile
	transform/Makefile
	test/Makefile
	waffles.pc
	])

AC_OUTPUT
