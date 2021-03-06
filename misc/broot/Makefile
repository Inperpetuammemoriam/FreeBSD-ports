PORTNAME=	broot
DISTVERSIONPREFIX=	v
DISTVERSION=	1.5.1
CATEGORIES=	misc

MAINTAINER=	lcook@FreeBSD.org
COMMENT=	Quick and easy new way to see and navigate directory trees

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/LICENSE

LIB_DEPENDS=	libgit2.so:devel/libgit2 \
		libonig.so:devel/oniguruma
RUN_DEPENDS=	git:devel/git

USES=		cargo
USE_GITHUB=	yes
GH_ACCOUNT=	canop

CARGO_CRATES=	adler-1.0.2 \
		adler32-1.2.0 \
		ahash-0.4.7 \
		ahash-0.7.2 \
		aho-corasick-0.7.18 \
		ansi_colours-1.0.2 \
		ansi_term-0.11.0 \
		anyhow-1.0.40 \
		argh-0.1.4 \
		argh_derive-0.1.4 \
		argh_shared-0.1.4 \
		atty-0.2.14 \
		autocfg-1.0.1 \
		base64-0.13.0 \
		bet-1.0.0 \
		bincode-1.3.3 \
		bitflags-1.2.1 \
		bstr-0.2.15 \
		bytemuck-1.5.1 \
		byteorder-1.4.3 \
		cc-1.0.67 \
		cfg-if-1.0.0 \
		char_reader-0.1.0 \
		chrono-0.4.19 \
		clap-2.33.3 \
		cli-log-0.1.0 \
		cli-log-2.0.0 \
		clipboard-win-4.1.0 \
		color_quant-1.1.0 \
		crc32fast-1.2.1 \
		crossbeam-0.8.0 \
		crossbeam-channel-0.5.1 \
		crossbeam-deque-0.8.0 \
		crossbeam-epoch-0.9.3 \
		crossbeam-queue-0.3.1 \
		crossbeam-utils-0.8.3 \
		crossterm-0.19.0 \
		crossterm_winapi-0.7.0 \
		csv-1.1.6 \
		csv-core-0.1.10 \
		csv2svg-0.1.5 \
		custom_error-1.9.2 \
		deflate-0.8.6 \
		deser-hjson-0.1.13 \
		directories-3.0.2 \
		directories-next-2.0.0 \
		dirs-sys-0.3.6 \
		dirs-sys-next-0.1.2 \
		either-1.6.1 \
		error-code-2.1.0 \
		fallible-iterator-0.2.0 \
		fallible-streaming-iterator-0.1.9 \
		file-size-1.0.3 \
		flate2-1.0.20 \
		fnv-1.0.7 \
		form_urlencoded-1.0.1 \
		getrandom-0.1.16 \
		getrandom-0.2.2 \
		gif-0.11.2 \
		git2-0.13.18 \
		glassbench-0.3.0 \
		glob-0.3.0 \
		hashbrown-0.9.1 \
		hashlink-0.6.0 \
		heck-0.3.2 \
		hermit-abi-0.1.18 \
		id-arena-2.2.1 \
		idna-0.2.3 \
		image-0.23.14 \
		indexmap-1.6.2 \
		instant-0.1.9 \
		is_executable-0.1.2 \
		itoa-0.4.7 \
		jobserver-0.1.22 \
		jpeg-decoder-0.1.22 \
		lazy-regex-2.1.0 \
		lazy-regex-proc_macros-2.1.0 \
		lazy_static-1.4.0 \
		lazycell-1.3.0 \
		lfs-core-0.3.1 \
		libc-0.2.93 \
		libgit2-sys-0.12.19+1.1.0 \
		libsqlite3-sys-0.20.1 \
		libz-sys-1.1.2 \
		line-wrap-0.1.1 \
		linked-hash-map-0.5.4 \
		lock_api-0.4.3 \
		log-0.4.14 \
		matches-0.1.8 \
		memchr-2.4.0 \
		memmap-0.7.0 \
		memoffset-0.6.3 \
		minimad-0.7.1 \
		minimad-0.8.0 \
		miniz_oxide-0.3.7 \
		miniz_oxide-0.4.4 \
		mio-0.7.11 \
		miow-0.3.7 \
		ntapi-0.3.6 \
		num-integer-0.1.44 \
		num-iter-0.1.42 \
		num-rational-0.3.2 \
		num-traits-0.2.14 \
		num_cpus-1.13.0 \
		once_cell-1.7.2 \
		onig-6.1.1 \
		onig_sys-69.6.0 \
		open-1.7.0 \
		parking_lot-0.11.1 \
		parking_lot_core-0.8.3 \
		pathdiff-0.2.0 \
		percent-encoding-2.1.0 \
		phf-0.8.0 \
		phf_generator-0.8.0 \
		phf_macros-0.8.0 \
		phf_shared-0.8.0 \
		pkg-config-0.3.19 \
		plist-1.1.0 \
		png-0.16.8 \
		ppv-lite86-0.2.10 \
		proc-macro-hack-0.5.19 \
		proc-macro2-1.0.26 \
		proc-status-0.1.1 \
		quote-1.0.9 \
		rand-0.7.3 \
		rand-0.8.3 \
		rand_chacha-0.2.2 \
		rand_chacha-0.3.0 \
		rand_core-0.5.1 \
		rand_core-0.6.2 \
		rand_hc-0.2.0 \
		rand_hc-0.3.0 \
		rand_pcg-0.2.1 \
		rayon-1.5.0 \
		rayon-core-1.9.0 \
		redox_syscall-0.2.6 \
		redox_users-0.4.0 \
		regex-1.5.4 \
		regex-automata-0.1.9 \
		regex-syntax-0.6.25 \
		remove_dir_all-0.5.3 \
		rusqlite-0.24.2 \
		ryu-1.0.5 \
		safemem-0.3.3 \
		same-file-1.0.6 \
		scoped_threadpool-0.1.9 \
		scopeguard-1.1.0 \
		secular-1.0.0 \
		serde-1.0.125 \
		serde_derive-1.0.125 \
		serde_json-1.0.64 \
		signal-hook-0.1.17 \
		signal-hook-registry-1.3.0 \
		siphasher-0.3.5 \
		smallvec-1.6.1 \
		splitty-0.1.0 \
		str-buf-2.0.0 \
		strict-0.1.4 \
		strsim-0.8.0 \
		svg-0.8.2 \
		syn-1.0.70 \
		syntect-4.5.0 \
		tempfile-3.2.0 \
		termimad-0.10.3 \
		termimad-0.11.1 \
		terminal-clipboard-0.2.1 \
		termux-clipboard-0.1.0 \
		textwrap-0.11.0 \
		thiserror-1.0.24 \
		thiserror-impl-1.0.24 \
		tiff-0.6.1 \
		time-0.1.43 \
		tinyvec-1.2.0 \
		tinyvec_macros-0.1.0 \
		toml-0.5.8 \
		umask-1.0.0 \
		unicode-bidi-0.3.5 \
		unicode-normalization-0.1.17 \
		unicode-segmentation-1.7.1 \
		unicode-width-0.1.8 \
		unicode-xid-0.2.1 \
		url-2.2.1 \
		users-0.11.0 \
		vcpkg-0.2.12 \
		vec_map-0.8.2 \
		version_check-0.9.3 \
		walkdir-2.3.2 \
		wasi-0.9.0+wasi-snapshot-preview1 \
		wasi-0.10.2+wasi-snapshot-preview1 \
		weezl-0.1.5 \
		which-4.1.0 \
		winapi-0.3.9 \
		winapi-i686-pc-windows-gnu-0.4.0 \
		winapi-util-0.1.5 \
		winapi-x86_64-pc-windows-gnu-0.4.0 \
		x11-clipboard-0.5.1 \
		xcb-0.9.0 \
		xml-rs-0.8.3 \
		yaml-rust-0.4.5
CARGO_FEATURES=	--no-default-features

SUB_FILES=	pkg-message
PLIST_FILES=	bin/${PORTNAME} \
		man/man1/${PORTNAME}.1.gz
PORTDOCS=	CHANGELOG.md README.md client-server.md documentation.md \
		features.md

OPTIONS_DEFINE=		CLIENT_SERVER CLIPBOARD DOCS
OPTIONS_DEFAULT=	CLIENT_SERVER CLIPBOARD

CLIENT_SERVER_DESC=	Enable client/server support
CLIPBOARD_DESC=		Enable terminal X11 clipboard support

CLIENT_SERVER_VARS=	CARGO_FEATURES+=client-server

CLIPBOARD_USES=		python:3.6+,build xorg
CLIPBOARD_USE=		XORG=xcb
CLIPBOARD_BINARY_ALIAS=	python3=${PYTHON_CMD}
CLIPBOARD_VARS=		CARGO_FEATURES+=clipboard

_BUILD_VERSION=	${DISTVERSION}
_BUILD_DATE=	$$(date +'%Y/%m/%d')

pre-build:
	@${MV} ${WRKSRC}/man/page ${WRKSRC}/man/${PORTNAME}.1
	@${REINPLACE_CMD} -e 's|#version|${_BUILD_VERSION}|g' \
		-e "s|#date|${_BUILD_DATE}|g" ${WRKSRC}/man/${PORTNAME}.1

post-install:
	${STRIP_CMD} ${STAGEDIR}${PREFIX}/bin/${PORTNAME}
	${INSTALL_MAN} ${WRKSRC}/man/${PORTNAME}.1 ${STAGEDIR}${MAN1PREFIX}/man/man1

post-install-DOCS-on:
	@${MKDIR} ${STAGEDIR}${DOCSDIR}
	${INSTALL_DATA} ${PORTDOCS:S|^|${WRKSRC}/|} ${STAGEDIR}${DOCSDIR}

.include <bsd.port.mk>
