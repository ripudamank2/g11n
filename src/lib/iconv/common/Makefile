#
# CDDL HEADER START
#
# The contents of this file are subject to the terms of the
# Common Development and Distribution License (the "License").  
# You may not use this file except in compliance with the License.
#
# You can obtain a copy of the license at src/OPENSOLARIS.LICENSE
# or http://www.opensolaris.org/os/licensing.
# See the License for the specific language governing permissions
# and limitations under the License.
#
# When distributing Covered Code, include this CDDL HEADER in each
# file and include the License file at src/OPENSOLARIS.LICENSE.
# If applicable, add the following below this CDDL HEADER, with the
# fields enclosed by brackets "[]" replaced with your own identifying
# information: Portions Copyright [yyyy] [name of copyright owner]
#
# CDDL HEADER END
#
#
# Copyright 2006 Sun Microsystems, Inc.  All rights reserved.
# Use is subject to license terms.
#
#ident "@(#)Makefile	1.4 03/04/11"
#

SRCS	=	646%CODESET.c 

dummy: all

include ../Makefile.asian

install: all $(TARGETDIRS)
	$(INS) $(ICONV_DIR) -m 644 -u bin -g bin $(PROGS)
	$(INS) $(ICONV_DIR_64) -m 644 -u bin -g bin $(MACH64)/$(PROGS)

all: $(MACH64) $(PROGS)

#$(PROGS): $(OBJS)
#	$(CC) $(CFLAGS) -o $@ $?
#	$(STRIP) $@
#	$(CC) $(CFLAGS_64) -o $(MACH64)/$@ $?
#	$(STRIP) $(MACH64)/$@

