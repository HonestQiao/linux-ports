# Created by: Artyom Mirgorodskiy <artyom.mirgorodsky@gmail.com>
# $FreeBSD$

PORTNAME=	pango
PORTVERSION=	1.28.1
CATEGORIES=	x11-toolkits linux

MAINTAINER=	emulation@FreeBSD.org

COMMENT=	Pango library (Linux  CentOS ${LINUX_DIST_VER})

CONFLICTS=	linux-pango-[0-9]* linux-f10-pango-[0-9]*

ONLY_FOR_ARCHS=	i386 amd64
USE_LINUX=	yes
USE_LINUX_APPS=	cairo expat fontconfig xorglibs
USE_LINUX_RPM=	yes
RPMVERSION=	7.el6_3
BRANDELF_FILES=	usr/bin/pango-querymodules-32
USE_LDCONFIG=	yes

DESCR=		${.CURDIR}/../${PORTNAME}/pkg-descr

.include <bsd.port.mk>
