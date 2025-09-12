#
# This file and its contents are supplied under the terms of the
# Common Development and Distribution License ("CDDL"). You may
# only use this file in accordance with the terms of the CDDL.
#
# A full copy of the text of the CDDL should have accompanied this
# source. A copy of the CDDL is also available via the Internet at
# http://www.illumos.org/license/CDDL.
#

#
# Copyright 2025 Jiwon Na
#

BUILD_STYLE= cmake
include ../../../make-rules/shared-macros.mk

COMPONENT_NAME=           ibus-unikey
COMPONENT_VERSION=        0.7.0
HUMAN_VERSION=        0.7.0-beta1
COMPONENT_GIT_REV=	ede78c312e8c6ed96d0f653a12880d4671c929fe
COMPONENT_SUMMARY=        ibus-unikey - Vietnamese IM Engine for ibus
COMPONENT_SRC=		$(COMPONENT_NAME)-$(COMPONENT_GIT_REV)
COMPONENT_ARCHIVE=        $(COMPONENT_SRC).tar.gz
COMPONENT_ARCHIVE_HASH=   sha256:afb9378e835139f700c9ce00cfff0e235ca0cf092c9265332eead72df2cd5697
COMPONENT_ARCHIVE_URL=    https://codeload.github.com/vn-input/$(COMPONENT_NAME)/tar.gz/$(COMPONENT_GIT_REV)
COMPONENT_FMRI=           system/input-method/ibus/unikey
COMPONENT_CLASSIFICATION= System/Localizations
COMPONENT_LICENSE=        GPLv3
COMPONENT_LICENSE_FILE=   LICENSE
COMPONENT_PROJECT_URL=    https://github.com/vn-input/ibus-unikey

TEST_TARGET= $(NO_TESTS)
include $(WS_MAKE_RULES)/common.mk

PATH= $(PATH.gnu)

# Auto-generated dependencies
REQUIRED_PACKAGES += $(GCC_RUNTIME_PKG)
REQUIRED_PACKAGES += $(GXX_RUNTIME_PKG)
REQUIRED_PACKAGES += library/desktop/gtk3
REQUIRED_PACKAGES += library/glib2
REQUIRED_PACKAGES += system/input-method/ibus
REQUIRED_PACKAGES += system/library