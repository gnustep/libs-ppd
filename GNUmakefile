#
#  Images makefile for GNUstep PPD Files
#  Copyright (C) 1997 Free Software Foundation, Inc.
#
#  Author: Adam Fedor <fedor@gnu.org>
#  Date:  July 2004
#
#  This file is part of the GNUstep.
#
#  This library is free software; you can redistribute it and/or
#  modify it under the terms of the GNU Library General Public
#  License as published by the Free Software Foundation; either
#  version 2 of the License, or (at your option) any later version.
#
#  This library is distributed in the hope that it will be useful,
#  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.	 See the GNU
#  Library General Public License for more details.
#
#  You should have received a copy of the GNU Library General Public
#  License along with this library; if not, write to the Free
#  Software Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA 02111 USA.

GNUSTEP_INSTALLATION_DIR = $(GNUSTEP_SYSTEM_ROOT)

include $(GNUSTEP_MAKEFILES)/common.make

CVS_MODULE_NAME = ppd
PACKAGE_NAME = gnustep-ppd

RES_INSTALL_DIR = $(GNUSTEP_LIBRARY)/PostScript
PPD_INSTALL_DIR = $(GNUSTEP_LIBRARY)/PostScript/PPD

RESOURCE_DIRS = \
English.lproj	\
French.lproj	\
German.lproj	\
Italian.lproj	\
Spanish.lproj	\
Swedish.lproj


RESOURCE_FILES = Printers

-include GNUmakefile.preamble

-include GNUmakefile.local
# We don't actually build anything in this directory so
# just include the common makefile rules
include $(GNUSTEP_MAKEFILES)/rules.make

include GNUmakefile.postamble
