# $FreeBSD$

PORTNAME=	grape
PORTVERSION=	0.19.2
CATEGORIES=	devel rubygems
MASTER_SITES=	RG
PKGNAMESUFFIX=	0

MAINTAINER=	ruby@FreeBSD.org
COMMENT=	Framework for rapid API development with great conventions

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/LICENSE

RUN_DEPENDS=	rubygem-activesupport4>=0:devel/rubygem-activesupport4 \
		rubygem-builder>=0:devel/rubygem-builder \
		rubygem-hashie>=2.1.0:devel/rubygem-hashie \
		rubygem-multi_json>=1.3.2:devel/rubygem-multi_json \
		rubygem-multi_xml>=0.5.2:textproc/rubygem-multi_xml \
		rubygem-mustermann-grape>=1.0.0:devel/rubygem-mustermann-grape \
		rubygem-rack>=1.3.0:www/rubygem-rack \
		rubygem-rack-accept>=0:www/rubygem-rack-accept \
		rubygem-virtus>=1.0.0:devel/rubygem-virtus

PORTSCOUT=	limit:^0\.

NO_ARCH=	yes
USE_RUBY=	yes
USES=		gem

.include <bsd.port.mk>
