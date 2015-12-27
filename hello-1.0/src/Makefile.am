dist_bin_SCRIPTS = hello.sh
dist_man_MANS = hello.1
CLEANFILES = $(dist_man_MANS)

hello.1: hello.1.ronn
	ronn --roff $?
