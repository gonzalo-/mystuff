# $OpenBSD$

COMMENT =	free and open-source reverse engineering framework

GH_ACCOUNT =	rizinorg
GH_PROJECT =	rizin
GH_TAGNAME =	v0.3.0

CATEGORIES =	devel

HOMEPAGE =	https://rizin.re/

MAINTAINER =	Some Brave Person <puffy@openbsd.org>

# GPLv3
PERMIT_PACKAGE =	Yes

MODULES +=		devel/meson

COMPILER =		base-clang ports-gcc

CONFIGURE_ARGS +=	-Duse_sys_libzip=enabled \
			-Duse_sys_libzip_openssl=true \
			-Duse_sys_zlib=enabled \
			-Duse_sys_lz4=enabled \
			-Duse_sys_openssl=enabled \
			-Duse_sys_tree_sitter=enabled \
			-Duse_sys_libuv=enabled \
			-Duse_libuv=true

CONFIGURE_ENV +=	LDFLAGS="-L${LOCALBASE}/lib \
			-L${X11BASE}/lib" \
			CPPFLAGS="-I${LOCALBASE}/include -D_BSD_SOURCE"

BUILD_DEPENDS =		devel/ninja

LIB_DEPENDS =		devel/radare2/main>=4.5.1 \
			databases/sdb \
			archivers/libzip \
			archivers/lz4 \
			sysutils/xxhash \
			archivers/lzip/lzlib \
			textproc/tree-sitter \
			devel/libuv 

NO_TEST =		Yes

.include <bsd.port.mk>
