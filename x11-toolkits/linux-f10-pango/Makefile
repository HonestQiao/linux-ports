# Created by: bsam
# $FreeBSD: head/x11-toolkits/linux-f10-pango/Makefile 340722 2014-01-22 17:00:46Z mat $

PORTNAME=	pango
PORTVERSION=	1.28.3
PORTREVISION=	1
CATEGORIES=	x11-toolkits linux
MASTER_SITES=	LOCAL
MASTER_SITE_SUBDIR=	netchild/rpms/${LINUX_DIST}${LINUX_DIST_VER}
MASTER_SITE_SRC_SUBDIR=	netchild/rpms/${LINUX_DIST}${LINUX_DIST_VER}

MAINTAINER=	emulation@FreeBSD.org
COMMENT=	Pango library (Linux Fedora 10)

CONFLICTS=	linux-pango-[0-9]* linux-f8-pango-[0-9]*

ONLY_FOR_ARCHS=	i386 amd64
USE_LINUX=	f10
USE_LINUX_RPM=	yes
# these libraries are required by pango-querymodules
USE_LINUX_APPS=	cairo expat fontconfig xorglibs
RPMVERSION=	1.fc10
BRANDELF_FILES=	usr/bin/pango-querymodules-32
USE_LDCONFIG=	yes

DESCR=		${.CURDIR}/../${PORTNAME}/pkg-descr

.include <bsd.port.mk>
