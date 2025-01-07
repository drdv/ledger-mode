# -*- indent-tabs-mode: t -*-
# because of ../.dir-locals.el (or I have to use C-q TAB)

all: dir

dir: ledger-mode.info
	install-info --section="Emacs custom" $< $@

ledger-mode.info:
	texi2any $(basename $@).texi

clean:
	rm -f dir ledger-mode.info
