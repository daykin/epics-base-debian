#*************************************************************************
# Copyright (c) 2011 UChicago Argonne LLC, as Operator of Argonne
#     National Laboratory.
# Copyright (c) 2002 The Regents of the University of California, as
#     Operator of Los Alamos National Laboratory.
# EPICS BASE is distributed subject to a Software License Agreement found
# in file LICENSE that is included with this distribution. 
#*************************************************************************

# This is a Makefile fragment, see src/ioc/Makefile.

SRC_DIRS += $(IOCDIR)/dbtemplate

PROD_HOST += msi

msi_SRCS = msi.cpp
msi_SYS_LIBS_WIN32 = shlwapi
DOCS += msi.md

INC += dbLoadTemplate.h
INC += dbtoolsIocRegister.h

dbCore_SRCS += dbLoadTemplate.c
dbCore_SRCS += dbtoolsIocRegister.c

CLEANS += dbLoadTemplate_lex.c dbLoadTemplate.c

