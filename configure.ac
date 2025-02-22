AC_INIT([enigma2-plugin-extensions-kodi], [1.0], [openspateam@gmail.com])

AM_INIT_AUTOMAKE
AC_PROG_CC
AM_PATH_PYTHON

AC_PATH_PROG(MSGFMT, msgfmt, AC_MSG_ERROR(Could not find msgfmt))
AC_PATH_PROG(MSGINIT, msginit, AC_MSG_ERROR(Could not find msginit))
AC_PATH_PROG(MSGMERGE, msgmerge, AC_MSG_ERROR(Could not find msgmerge))
AC_PATH_PROG(MSGUNIQ, msguniq, AC_MSG_ERROR(Could not find msguniq))
AC_PATH_PROG(XGETTEXT, xgettext, AC_MSG_ERROR(Could not find xgettext))

AC_CONFIG_FILES([
Makefile
src/Makefile
src/kodiext/Makefile
src/plugin/Makefile
src/plugin/image/Makefile
src/po/Makefile

])
AC_OUTPUT
