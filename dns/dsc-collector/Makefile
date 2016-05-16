PORTNAME=		dsc-collector
PORTVERSION=	201502251630
DISTNAME=       dsc-${PORTVERSION}
CATEGORIES=		dns ipv6
MASTER_SITES=   http://dns.measurement-factory.com/tools/dsc/download/

MAINTAINER=		john.bond@icann.org
COMMENT=		DNS Data collection

LICENSE=		BSD3CLAUSE
WRKSRC_SUBDIR=  collector

post-install:
	  ${INSTALL_SCRIPT} ${WRKSRC}/dsc/dsc.sh ${PREFIX}/etc/rc.d/dsc


.include <bsd.port.mk>
