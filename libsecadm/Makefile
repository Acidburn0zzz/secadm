SHLIB=	secadm
SHLIB_MAJOR=	1
SRCS=	libsecadm.c
INCS=	secadm.h

.if defined(PREFIX)
INCLUDEDIR?=	${PREFIX}/include
.endif

#LDADD+=	-lmd

CFLAGS+=	-g -O0 -I${.CURDIR}

MAN=

.include <bsd.lib.mk>
