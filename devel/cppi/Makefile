# $FreeBSD$

PORTNAME=	cppi
PORTVERSION=	1.18
PORTREVISION=	1
CATEGORIES=	devel
MASTER_SITES=	GNU

MAINTAINER=	ports@FreeBSD.org
COMMENT=	Tool to indent the C preprocessor directives

USES=		charsetfix gmake tar:xz	# gmake is needed for -jX builds
GNU_CONFIGURE=	yes
CPPFLAGS+=	-I${LOCALBASE}/include

OPTIONS_DEFINE=	NLS
OPTIONS_SUB=	yes

NLS_USES=	gettext
NLS_CONFIGURE_OFF=	--disable-nls

.include <bsd.port.mk>
