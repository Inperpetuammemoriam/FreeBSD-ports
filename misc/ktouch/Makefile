PORTNAME=	ktouch
DISTVERSION=	${KDE_APPLICATIONS_VERSION}
CATEGORIES=	misc education kde kde-applications

MAINTAINER=	kde@FreeBSD.org
COMMENT=	Touch typing tutor for KDE

RUN_DEPENDS=	kqtquickcharts>=${KDE_APPLICATIONS_VERSION}:graphics/kqtquickcharts

USES=		cmake compiler:c++11-lang gettext kde:5 qt:5 tar:xz xorg
USE_KDE=	auth codecs completion config configwidgets coreaddons doctools \
		ecm i18n iconthemes itemviews kcmutils kdeclarative kio newstuff package \
		parts service sonnet texteditor textwidgets widgetsaddons \
		windowsystem xmlgui
USE_QT=		core dbus declarative gui network quickcontrols2 script sql \
		testlib widgets x11extras xml xmlpatterns \
		buildtools_build qmake_build
USE_XORG=	ice sm x11 xcb xext xkbfile

OPTIONS_DEFINE=	DOCS

.include <bsd.port.mk>
