# Created by: Sunpoet Po-Chuan Hsieh <sunpoet@FreeBSD.org>
# $FreeBSD$

PORTNAME=	qiniu
PORTVERSION=	6.8.1
CATEGORIES=	net rubygems
MASTER_SITES=	RG

MAINTAINER=	sunpoet@FreeBSD.org
COMMENT=	Qiniu Resource (Cloud) Storage SDK for Ruby

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/LICENSE

RUN_DEPENDS=	rubygem-json1>=1.8:devel/rubygem-json1 \
		rubygem-mime-types>=2.4.0:misc/rubygem-mime-types \
		rubygem-rest-client>=2.0.0:www/rubygem-rest-client \
		rubygem-ruby-hmac>=0.4:security/rubygem-ruby-hmac

NO_ARCH=	yes
USE_RUBY=	yes
USES=		gem

.include <bsd.port.mk>
