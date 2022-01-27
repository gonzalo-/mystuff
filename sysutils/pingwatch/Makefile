# $OpenBSD$

COMMENT =	pings hosts and reports on availability and trends

MODGO_MODNAME =	github.com/fazalmajid/pingwatch
MODGO_VERSION =	v0.0.0-20210323194850-4a78e7bd7572

DISTNAME =	pingwatch-${MODGO_VERSION}
PKGNAME =	pingwatch-20210323194850

CATEGORIES =	sysutils

# MIT
PERMIT_PACKAGE =	Yes
PERMIT_DISTFILES =	Yes

WANTLIB += c pthread

MODULES =		lang/go

MODGO_MODULES =	\
	github.com/mattn/go-sqlite3	 v2.0.3+incompatible \
	github.com/rakyll/statik	 v0.1.7 \
	golang.org/x/crypto		 v0.0.0-20190308221718-c2843e01d9a2 \
	golang.org/x/net		 v0.0.0-20200602114024-627f9648deb9 \
	golang.org/x/sys		 v0.0.0-20200323222414-85ca7c5b95cd \
	golang.org/x/text		 v0.3.0

MODGO_MODFILES =	\
	golang.org/x/sys	 v0.0.0-20190215142949-d0b11bdaac8a

.include <bsd.port.mk>
