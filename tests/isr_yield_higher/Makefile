APPLICATION = isr_yield_higher
include ../Makefile.tests_common

BOARD_INSUFFICIENT_MEMORY := nucleo32-f031

USEMODULE += xtimer

include $(RIOTBASE)/Makefile.include

test:
	./tests/test.py
