# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD$

PORTNAME=	trytond28_country
PORTVERSION=	2.8.1
CATEGORIES=	finance python
MASTER_SITES=	CHEESESHOP \
		http://downloads.tryton.org/${PORTVERSION:R}/
DISTNAME=	trytond_country-${PORTVERSION}

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Country Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond28>=2.8.2:finance/trytond28

CONFLICTS=	trytond_country-2.[46].*

USES=		python:2.7
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
