################################################################################
#Library Top Makefile.
################################################################################
subdirs = base

#  
all : $(subdirs)
	@for dir in $(subdirs);do \
	make -C $$dir; done

clean :$(subdirs)
	@for dir in $(subdirs);do \
	make clean -C $$dir; done

clean_tmp:$(subdirs)
	@for dir in $(subdirs);do \
	make clean_tmp -C $$dir; done

