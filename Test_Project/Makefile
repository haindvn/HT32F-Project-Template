# Target name will be the same as Project Dir
TARGET ?= $(lastword $(subst /, ,$(CURDIR)))

######################################
# building variables
######################################
# debug build?
JLINK_DEVICE = HT32F52220

DEBUG = 1
#Verbose Mode?
VERBOSE = N
# optimization
OPT = -Og

#Please select the modules to be built in file modules_inc

include ../Makefile.include