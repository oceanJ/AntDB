#-------------------------------------------------------------------------
#
# Makefile--
#    Makefile for src/agtm/postmaster
#
# IDENTIFICATION
#    src/agtm/postmaster/Makefile
#
#-------------------------------------------------------------------------

subdir = src/agtm/postmaster
top_builddir = ../../..
include $(top_builddir)/src/Makefile.global

OBJS = autovacuum.o bgwriter.o fork_process.o pgarch.o pgstat.o postmaster.o \
	startup.o syslogger.o walwriter.o checkpointer.o

include $(top_srcdir)/src/agtm/common.mk
