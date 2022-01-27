# $OpenBSD$

COMMENT =	yav is a golang live static blog

MODGO_MODNAME =	github.com/lubiedo/yav
MODGO_VERSION =	v0.0.0-20210416231515-36b110ce5c94

DISTNAME =	yav-${MODGO_VERSION}
PKGNAME =	yav-20210416231515

CATEGORIES =	www

MAINTAINER =		Gonzalo L. R. <gonzalo@openbsd.org>

# MIT
PERMIT_PACKAGE =	Yes
PERMIT_DISTFILES =	Yes

MODULES =		lang/go

WANTLIB += c pthread

do-build:
	cd ${WRKSRC}/src \
		&& ${MODGO_CMD} build ${MODGO_FLAGS} -o ${MODGO_WORKSPACE}/bin/yav 

MODGO_MODULES =	\
	github.com/!masterminds/goutils		 v1.1.1 \
	github.com/!masterminds/semver/v3	 v3.1.1 \
	github.com/!masterminds/sprig/v3	 v3.2.2 \
	github.com/davecgh/go-spew		 v1.1.1 \
	github.com/gomarkdown/markdown		 v0.0.0-20210408062403-ad838ccf8cdd \
	github.com/google/uuid			 v1.2.0 \
	github.com/huandu/xstrings		 v1.3.2 \
	github.com/imdario/mergo		 v0.3.12 \
	github.com/mitchellh/copystructure	 v1.1.2 \
	github.com/mitchellh/reflectwalk	 v1.0.1 \
	github.com/pmezard/go-difflib		 v1.0.0 \
	github.com/shopspring/decimal		 v1.2.0 \
	github.com/spf13/cast			 v1.3.1 \
	github.com/stretchr/objx		 v0.1.0 \
	github.com/stretchr/testify		 v1.7.0 \
	golang.org/dl				 v0.0.0-20190829154251-82a15e2f2ead \
	golang.org/x/crypto			 v0.0.0-20210322153248-0c34fe9e7dc2 \
	golang.org/x/net			 v0.0.0-20210226172049-e18ecbb05110 \
	golang.org/x/sys			 v0.0.0-20201119102817-f84b799fce68 \
	golang.org/x/term			 v0.0.0-20201126162022-7de9c90e9dd1 \
	golang.org/x/text			 v0.3.3 \
	golang.org/x/tools			 v0.0.0-20180917221912-90fa682c2a6e \
	gopkg.in/check.v1			 v0.0.0-20161208181325-20d25e280405 \
	gopkg.in/yaml.v2			 v2.4.0 \
	gopkg.in/yaml.v3			 v3.0.0-20200313102051-9f266ea9e77c

MODGO_MODFILES =	\
	github.com/davecgh/go-spew		 v1.1.0 \
	github.com/google/uuid			 v1.1.1 \
	github.com/huandu/xstrings		 v1.3.1 \
	github.com/imdario/mergo		 v0.3.11 \
	github.com/mitchellh/copystructure	 v1.0.0 \
	github.com/mitchellh/reflectwalk	 v1.0.0 \
	github.com/stretchr/testify		 v1.2.2 \
	github.com/stretchr/testify		 v1.5.1 \
	golang.org/x/crypto			 v0.0.0-20190308221718-c2843e01d9a2 \
	golang.org/x/crypto			 v0.0.0-20200414173820-0848c9571904 \
	golang.org/x/net			 v0.0.0-20190404232315-eb5bcb51f2a3 \
	golang.org/x/sys			 v0.0.0-20190215142949-d0b11bdaac8a \
	golang.org/x/sys			 v0.0.0-20190412213103-97732733099d \
	golang.org/x/text			 v0.3.0 \
	gopkg.in/yaml.v2			 v2.2.2 \
	gopkg.in/yaml.v2			 v2.3.0

.include <bsd.port.mk>
