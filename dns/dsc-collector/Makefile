PORTNAME=		dsc-collector
PORTVERSION=	2.1.1
DISTNAME=       dsc-${PORTVERSION}
CATEGORIES=		dns ipv6
MASTER_SITES=   https://www.dns-oarc.net/files/dsc/

MAINTAINER=		john.bond@icann.org
COMMENT=		DNS Data collection

LICENSE=		BSD3CLAUSE

GNU_CONFIGURE=  yes
post-install:
	  ${MKDIR} ${PREFIX}/etc/rc.d/
	  ${INSTALL_SCRIPT} ${WRKSRC}/src/dsc.sh ${PREFIX}/etc/rc.d/dsc


.include <bsd.port.mk>
