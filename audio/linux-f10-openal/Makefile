# Created by: bsam
# $FreeBSD: head/audio/linux-f10-openal/Makefile 340722 2014-01-22 17:00:46Z mat $

PORTNAME=	openal
PORTVERSION=	0.0.9
CATEGORIES=	audio linux
MASTER_SITES=	CRITICAL/rpm/${LINUX_RPM_ARCH}/fedora/${LINUX_DIST_VER}

MAINTAINER=	emulation@FreeBSD.org
COMMENT=	3D positional spatialized sound library (Linux Fedora 10)

CONFLICTS=	linux-openal-[0-9]* linux-f8-openal-[0-9]*

ONLY_FOR_ARCHS=	i386 amd64
USE_LINUX=	f10
USE_LINUX_RPM=	yes
USE_LINUX_APPS=	alsalib arts esound libaudiofile libvorbis sdl12

RPMVERSION=	0.15.20060204cvs.fc9
USE_LDCONFIG=	yes

PLIST_FILES=	etc/openalrc usr/lib/libopenal.so.0 usr/lib/libopenal.so.0.0.0
DOCSDIR=	${PREFIX}/usr/share/doc/${PORTNAME}-${PORTVERSION}
PORTDOCS=	AUTHORS COPYING ChangeLog NOTES README TODO
DESCR=		${.CURDIR}/../${PORTNAME}/pkg-descr

.include <bsd.port.mk>
