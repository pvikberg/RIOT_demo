include ../Makefile.tests_common

BOARD_INSUFFICIENT_MEMORY := nucleo32-f031

DISABLE_MODULE += auto_init

TEST_ON_CI_WHITELIST += all

include $(RIOTBASE)/Makefile.include

test:
	tests/01-run.py
