# Created by: Jens Rehsack <rehsack@liwing.de>
# $FreeBSD: head/devel/php-xdebug/Makefile 375249 2014-12-22 17:12:26Z feld $

PORTNAME=	xdebug
PORTVERSION=	2.4.0rc4
WRKSRC=      	${WRKDIR}/xdebug-2.4.0RC4
CATEGORIES=	devel
MASTER_SITES=	http://www.xdebug.org/files/
PKGNAMEPREFIX=	php-

MAINTAINER=	freebsd-ports-maintainers@intermedix.com
COMMENT=	Xdebug extension for PHP

LICENSE=	PHP30

CONFIGURE_ARGS=	--enable-xdebug
USE_PHP=	yes
USE_PHPIZE=	yes
USE_ZENDEXT=	yes
USES=		tar:tgz

SUB_FILES=	pkg-message

.include <bsd.port.mk>
