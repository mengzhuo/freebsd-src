_spath=	${SRCTOP}/contrib/ofed/libibumad
.PATH: ${_spath}

SHLIBDIR?=	/usr/lib
LIB=		ibumad
SHLIB_MAJOR=	1
SRCS= \
umad.c \
umad_str.c \
sysfs.c
CFLAGS+=	-I${_spath}
VERSION_MAP=	${_spath}/libibumad.map

.include <bsd.lib.mk>
