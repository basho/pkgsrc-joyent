# $NetBSD$

DISTNAME=	moqueue-0.1.4
PKGNAME=	${RUBY_PKGPREFIX}-${DISTNAME}
CATEGORIES=	devel

MAINTAINER=	pedro@joyent.com
HOMEPAGE=	https://github.com/danielsdeleo/moqueue
COMMENT=	Mocktacular Companion to AMQP Library
LICENSE=        ruby-license

DEPENDS+=	${RUBY_PKGPREFIX}-amqp-[0-9]*:../../net/ruby-amqp

.include "../../lang/ruby/gem.mk"
.include "../../mk/bsd.pkg.mk"
