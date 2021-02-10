# $FreeBSD$

PORTNAME=	xcwd
DISTVERSION=	1.0
CATEGORIES=	x11

MAINTAINER=	flo@snakeoilproductions.net
COMMENT=	Print the current working directory of the currently focused window

LICENSE=	BSD3CLAUSE

USES=	gmake xorg
USE_XORG=	x11
USE_GITHUB=	yes
GH_ACCOUNT=	schischi

PLIST_FILES=	bin/xcwd

do-install:
	${INSTALL_PROGRAM} ${WRKSRC}/xcwd ${STAGEDIR}${PREFIX}/bin

.include <bsd.port.mk>
