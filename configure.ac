AC_PREREQ(2.65)
AC_INIT([sjconf-openvpn], [0.1.0~dev])

AM_INIT_AUTOMAKE([-Wall foreign])

SJ_PROG_SJCONF
AC_PATH_PROG(TXT2TAGS, txt2tags)

AC_CONFIG_FILES([
    Makefile
    doc/Makefile
    confs/Makefile
    plugins/openvpn.py
    templates/Makefile
    templates/openvpn/Makefile
])

AC_OUTPUT
