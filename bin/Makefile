SUBDIRS=pktbuf pktctl pktsend pktrecv checker autorun pktlint remotes prfcomp ivcomp x509dec file2hex indexgen

.PHONY: all clean install
all clean install:
	@for subdir in $(SUBDIRS); do \
		$(MAKE) -C $$subdir $@; \
	done
