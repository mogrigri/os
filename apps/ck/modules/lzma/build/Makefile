################################################################################
#
#   Copyright (c) 2017 Minoca Corp.
#
#    This file is licensed under the terms of the GNU General Public License
#    version 3. Alternative licensing terms are available. Contact
#    info@minocacorp.com for details. See the LICENSE file at the root of this
#    project for complete licensing information.
#
#   Binary Name:
#
#       LZMA (Build)
#
#   Abstract:
#
#       This Chalk module implements the LZMA compression library interface for
#       Chalk.
#
#   Author:
#
#       Evan Green 22-May-2017
#
#   Environment:
#
#       POSIX
#
################################################################################

BINARY := lzma.a

BINARYTYPE = library

BUILD = yes

INCLUDES += $(SRCDIR)/..;

VPATH += $(SRCDIR)/..:

include $(SRCDIR)/../sources

DIRS := dynamic \

include $(SRCROOT)/os/minoca.mk

dynamic: $(BINARY)

