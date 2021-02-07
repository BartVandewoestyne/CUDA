################################################################################
#
# Build script for project
#
################################################################################

# Executable name
EXECUTABLE	:= prac1a

# CUDA source files (compiled with nvcc)
CUFILES		:= prac1a.cu

# CUDA dependency files
CU_DEPS		:= Makefile

# C/C++ source files (compiled with gcc/g++)
CCFILES		:= \
		   \

################################################################################
# Rules and targets

#ROOTDIR = /opt/cuda/2.3/sdk/C/common
ROOTDIR = /home/bartv/NVIDIA_GPU_Computing_SDK/C/common
BINDIR  = ./bin
include $(ROOTDIR)/common.mk

# flag to enable double precision
# NVCCFLAGS += -arch sm_13

# flag to save intermediate files to look at PTX code
# NVCCFLAGS += -keep

# flag to clean up afterwards
# NVCCFLAGS += -keep -clean

# flag to report on use of registers, shared memory, etc
NVCCFLAGS += -Xptxas -v

