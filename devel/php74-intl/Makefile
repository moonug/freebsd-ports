CATEGORIES=	devel

MASTERDIR=	${.CURDIR}/../../lang/php74

PKGNAMESUFFIX=	-intl

USES=		compiler:c++17-lang
USE_CXXSTD=	gnu++17

CPPFLAGS+=	-DU_USING_ICU_NAMESPACE=1

TEST_TARGET=	test

.include "${MASTERDIR}/Makefile"
