# The`long double' type is a distinct type we support if
# -mlong-double-128 option is used (or when it becomes a default
# when -mlong-double-64 is not used).
long-double-fcts = yes
sysdep-CFLAGS += -mlong-double-128

ifeq ($(subdir),stdlib)
tests += tst-strtold-ldbl-128ibm
$(objpfx)tst-strtold-ldbl-128ibm: $(libm)
endif

ifeq ($(subdir),math)
tests += test-fmodl-ldbl-128ibm
endif
