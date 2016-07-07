PORTNAME=		dsc-collector
PORTVERSION=	2.1.1
DISTNAME=       dsc-${PORTVERSION}
CATEGORIES=		dns ipv6
MASTER_SITES=   https://www.dns-oarc.net/files/dsc/

MAINTAINER=		john.bond@icann.org
COMMENT=		DNS Data collection

LICENSE=		BSD3CLAUSE
WRKSRC_SUBDIR=  collector

post-install:
	  ${INSTALL_SCRIPT} ${WRKSRC}/dsc/dsc.sh ${PREFIX}/etc/rc.d/dsc


.include <bsd.port.mk>
