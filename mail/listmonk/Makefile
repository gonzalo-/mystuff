# $OpenBSD$

COMMENT =	high performace self-hosted newsletter

MODGO_MODNAME =	github.com/knadh/listmonk
MODGO_VERSION =	v0.8.0-beta

DISTNAME =	listmonk-${MODGO_VERSION}

CATEGORIES =	mail

#AGPL-3.0
PERMIT_PACKAGE =	Yes

WANTLIB += c pthread

MODULES =		lang/go

MODGO_MODULES =	\
	github.com/!burnt!sushi/toml		 v0.3.1 \
	github.com/davecgh/go-spew		 v1.1.1 \
	github.com/dgrijalva/jwt-go		 v3.2.0+incompatible \
	github.com/disintegration/imaging	 v1.6.2 \
	github.com/fatih/structs		 v1.1.0 \
	github.com/fsnotify/fsnotify		 v1.4.9 \
	github.com/go-sql-driver/mysql		 v1.4.0 \
	github.com/gofrs/uuid			 v3.2.0+incompatible \
	github.com/golang/protobuf		 v1.4.0 \
	github.com/google/go-cmp		 v0.4.0 \
	github.com/hashicorp/hcl		 v1.0.0 \
	github.com/jaytaylor/html2text		 v0.0.0-20200220170450-61d9dc4d7195 \
	github.com/jmoiron/sqlx			 v1.2.0 \
	github.com/josharian/intern		 v1.0.0 \
	github.com/knadh/goyesql		 v2.0.0+incompatible \
	github.com/knadh/goyesql/v2		 v2.1.1 \
	github.com/knadh/koanf			 v0.12.0 \
	github.com/knadh/smtppool		 v0.2.1 \
	github.com/knadh/stuffbin		 v1.1.0 \
	github.com/kr/pty			 v1.1.1 \
	github.com/kr/text			 v0.1.0 \
	github.com/labstack/echo		 v3.3.10+incompatible \
	github.com/labstack/gommon		 v0.3.0 \
	github.com/lib/pq			 v1.3.0 \
	github.com/mailru/easyjson		 v0.7.6 \
	github.com/mattn/go-colorable		 v0.1.2 \
	github.com/mattn/go-isatty		 v0.0.9 \
	github.com/mattn/go-runewidth		 v0.0.7 \
	github.com/mattn/go-sqlite3		 v1.9.0 \
	github.com/mitchellh/mapstructure	 v1.2.2 \
	github.com/nats-io/jwt			 v0.3.2 \
	github.com/nats-io/nats-server/v2	 v2.1.7 \
	github.com/nats-io/nats.go		 v1.10.0 \
	github.com/nats-io/nkeys		 v0.1.4 \
	github.com/nats-io/nuid			 v1.0.1 \
	github.com/niemeyer/pretty		 v0.0.0-20200227124842-a10e7caefd8e \
	github.com/olekukonko/tablewriter	 v0.0.4 \
	github.com/pelletier/go-toml		 v1.7.0 \
	github.com/pmezard/go-difflib		 v1.0.0 \
	github.com/rhnvrm/simples3		 v0.5.0 \
	github.com/spf13/pflag			 v1.0.5 \
	github.com/ssor/bom			 v0.0.0-20170718123548-6386211fdfcf \
	github.com/stretchr/objx		 v0.1.0 \
	github.com/stretchr/testify		 v1.4.0 \
	github.com/valyala/bytebufferpool	 v1.0.0 \
	github.com/valyala/fasttemplate		 v1.0.1 \
	golang.org/x/crypto			 v0.0.0-20200323165209-0ec3e9974c59 \
	golang.org/x/image			 v0.0.0-20191009234506-e7c1f5e7dbb8 \
	golang.org/x/mod			 v0.3.0 \
	golang.org/x/net			 v0.0.0-20190620200207-3b0461eec859 \
	golang.org/x/sync			 v0.0.0-20190423024810-112230192c58 \
	golang.org/x/sys			 v0.0.0-20200331124033-c3d80250170d \
	golang.org/x/text			 v0.3.2 \
	golang.org/x/tools			 v0.0.0-20191119224855-298f0cb1881e \
	golang.org/x/xerrors			 v0.0.0-20191204190536-9bdfabe68543 \
	google.golang.org/appengine		 v1.6.5 \
	google.golang.org/protobuf		 v1.22.0 \
	gopkg.in/check.v1			 v1.0.0-20200227125254-8fa46927fb4f \
	gopkg.in/volatiletech/null.v6		 v6.0.0-20170828023728-0bef4e07ae1b \
	gopkg.in/yaml.v2			 v2.2.8 \
	jaytaylor.com/html2text			 v0.0.0-20200220170450-61d9dc4d7195
MODGO_MODFILES =	\
	github.com/davecgh/go-spew	 v1.1.0 \
	github.com/golang/protobuf	 v1.3.1 \
	github.com/golang/protobuf	 v1.4.0-rc.1 \
	github.com/golang/protobuf	 v1.4.0-rc.1.0.20200221234624-67d41d38c208 \
	github.com/golang/protobuf	 v1.4.0-rc.2 \
	github.com/golang/protobuf	 v1.4.0-rc.4.0.20200313231945-b860323f09d0 \
	github.com/google/go-cmp	 v0.3.0 \
	github.com/google/go-cmp	 v0.3.1 \
	github.com/lib/pq		 v1.0.0 \
	github.com/mattn/go-isatty	 v0.0.8 \
	github.com/nats-io/nkeys	 v0.1.3 \
	github.com/stretchr/testify	 v1.3.0 \
	golang.org/x/crypto		 v0.0.0-20190308221718-c2843e01d9a2 \
	golang.org/x/crypto		 v0.0.0-20190701094942-4def268fd1a4 \
	golang.org/x/crypto		 v0.0.0-20191011191535-87dc89f01550 \
	golang.org/x/net		 v0.0.0-20190404232315-eb5bcb51f2a3 \
	golang.org/x/net		 v0.0.0-20190603091049-60506f45cf65 \
	golang.org/x/sys		 v0.0.0-20190215142949-d0b11bdaac8a \
	golang.org/x/sys		 v0.0.0-20190222072716-a9d3bda3a223 \
	golang.org/x/sys		 v0.0.0-20190412213103-97732733099d \
	golang.org/x/sys		 v0.0.0-20190726091711-fc99dfbffb4e \
	golang.org/x/sys		 v0.0.0-20190813064441-fde4db37ae7a \
	golang.org/x/sys		 v0.0.0-20191005200804-aed5e4c7ecf9 \
	golang.org/x/text		 v0.3.0 \
	golang.org/x/tools		 v0.0.0-20180917221912-90fa682c2a6e \
	golang.org/x/xerrors		 v0.0.0-20190717185122-a985d3407aa7 \
	golang.org/x/xerrors		 v0.0.0-20191011141410-1b5146add898 \
	google.golang.org/protobuf	 v0.0.0-20200109180630-ec00e32a8dfd \
	google.golang.org/protobuf	 v0.0.0-20200221191635-4d8936d0db64 \
	google.golang.org/protobuf	 v0.0.0-20200228230310-ab0ca4ff8a60 \
	google.golang.org/protobuf	 v1.20.1-0.20200309200217-e05f789c0967 \
	google.golang.org/protobuf	 v1.21.0 \
	gopkg.in/check.v1		 v0.0.0-20161208181325-20d25e280405 \
	gopkg.in/yaml.v2		 v2.2.2

.include <bsd.port.mk>
