# $FreeBSD$

PORTNAME=	kig
DISTVERSION=	${KDE_APPLICATIONS_VERSION}
PORTREVISION=	1
CATEGORIES=	math kde kde-applications

MAINTAINER=	kde@FreeBSD.org
COMMENT=	KDE interactive geometry application

LIB_DEPENDS=	${PY_BOOST}

USES=		cmake:outsource gettext compiler:c++11-lib kde:5 \
		python:2.7,run shebangfix tar:xz
USE_KDE=	archive auth codecs completion config configwidgets coreaddons \
		crash doctools ecm emoticons i18n iconthemes init itemmodels \
		jobwidgets kdelibs4support kio parts service sonnet texteditor \
		textwidgets widgetsaddons xmlgui
USE_QT5=	core dbus gui network printsupport svg widgets xml xmlpatterns \
		buildtools_build qmake_build
SHEBANG_FILES=	pykig/pykig.py

.include <bsd.port.mk>
