# $OpenBSD$

COMMENT =	a simple string key/value database

DISTNAME =	sdb-0.1
GH_ACCOUNT =	rizinorg
GH_PROJECT =	sdb
GH_COMMIT =	6b405914220c5b0afddc89d192066d9b02cc4ce8

CATEGORIES =	databases

HOMEPAGE =	https://rizin.re/

MAINTAINER =	Some Brave Person <puffy@openbsd.org>

# GPLv3
PERMIT_PACKAGE =	Yes

MODULES +=	devel/meson

WANTLIB += c

CONFIGURE_ENV +=	LDFLAGS="-L${LOCALBASE}/lib"

BUILD_DEPENDS =		devel/ninja

.include <bsd.port.mk>
